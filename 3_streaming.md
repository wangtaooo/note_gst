# 3 Streaming Operation

### 1.push on TX1

```shell
gst-launch-1.0 nvcamerasrc sensor_id=0 ! 'video/x-raw(memory:NVMM), width=640, height=480, framerate=30/1' ! nvvidconv ! timeoverlay ! omxh264enc bitrate=2000000 ! video/x-h264,stream-format=byte-stream ! h264parse ! rtph264pay pt=96 ! udpsink host=192.168.232.239 port=5600
```




### 2.recevier on my Laptop
```
gst-launch-1.0 -v udpsrc port=5000 ! application/x-rtp,clock-rate=90000,payload=96 ! rtph264depay ! h264parse ! avdec_h264 ! videoconvert ! queue leaky=downstream max-size-buffers=100 ! x264enc ! h264parse ! mp4mux ! ximageview
```


### 3.QGC

UDP Stream 
H264
Port = 5600