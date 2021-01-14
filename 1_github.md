# 1 Github Rep

### Rep name(num:22)
```shell
gst-docs
www
gst-plugins-bad
common
gstreamer-vaapi
gstreamer-sharp
gstreamer
gst-plugins-good
cerbero
gst-examples
gst-omx
gst-rtsp-server
gst-build
gst-plugins-base
gst-editing-services
gst-devtools
gst-plugins-ugly
gst-libav
orc
gst-python
gst-integration-testsuites
qt-gstreamer
```

### 1 download:


```shell
git clone https://github.com/GStreamer/gst-docs.git
git clone https://github.com/GStreamer/www.git
git clone https://github.com/GStreamer/gst-plugins-bad.git
git clone https://github.com/GStreamer/gst-examples.git
git clone https://github.com/GStreamer/common.git
git clone https://github.com/GStreamer/gstreamer-vaapi.git
git clone https://github.com/GStreamer/gstreamer-sharp.git
git clone https://github.com/GStreamer/gstreamer.git
git clone https://github.com/GStreamer/gst-plugins-good.git
git clone https://github.com/GStreamer/cerbero.git
git clone https://github.com/GStreamer/gst-omx.git
git clone https://github.com/GStreamer/gst-rtsp-server.git
git clone https://github.com/GStreamer/gst-build.git
git clone https://github.com/GStreamer/gst-plugins-base.git
git clone https://github.com/GStreamer/gst-editing-services.git
git clone https://github.com/GStreamer/gst-devtools.git
git clone https://github.com/GStreamer/gst-plugins-ugly.git
git clone https://github.com/GStreamer/gst-libav.git
git clone https://github.com/GStreamer/orc.git
git clone https://github.com/GStreamer/gst-python.git
git clone https://github.com/GStreamer/gst-integration-testsuites.git
git clone https://github.com/GStreamer/qt-gstreamer.git
```

### 2 find .gitmodules
```
find . -name .gitmodules
```
cd Rep

and
```
git submodule update --init --recursive
```


### 3 tar
```shell
tar cvf gst-docs.tar ./gst-docs
tar cvf www.tar ./www
tar cvf gst-plugins-bad.tar ./gst-plugins-bad
tar cvf common.tar ./common
tar cvf gstreamer-vaapi.tar ./gstreamer-vaapi 
tar cvf gstreamer-sharp.tar ./gstreamer-sharp
tar cvf gstreamer.tar ./gstreamer
tar cvf gst-plugins-good.tar ./gst-plugins-good
tar cvf cerbero.tar ./cerbero
tar cvf gst-examples.tar ./gst-examples
tar cvf gst-omx.tar ./gst-omx
tar cvf gst-rtsp-server.tar ./gst-rtsp-server
tar cvf gst-build.tar ./gst-build
tar cvf gst-plugins-base.tar ./gst-plugins-base
tar cvf gst-editing-services.tar ./gst-editing-services
tar cvf gst-devtools.tar ./gst-devtools
tar cvf gst-plugins-ugly.tar ./gst-plugins-ugly
tar cvf gst-libav.tar ./gst-libav
tar cvf orc.tar ./orc
tar cvf gst-python.tar ./gst-python
tar cvf gst-integration-testsuites.tar ./gst-integration-testsuites
tar cvf qt-gstreamer.tar ./qt-gstreamer
```
### 3 scp
#sshpass -p x6scMyMSYhyz scp -P 29962 root@96.45.180.86:/home/samba_root/ws_gst/*.tar .
```shell
scp -P 29962 root@96.45.180.86:/home/samba_root/ws_gst/*.tar .
x6scMyMSYhyz
```
### 4 untar
```shell
tar xvf ./gst-docs.tar
tar xvf ./www.tar
tar xvf ./gst-plugins-bad.tar
tar xvf ./common.tar
tar xvf ./gstreamer-vaapi.tar
tar xvf ./gstreamer-sharp.tar
tar xvf ./gstreamer.tar
tar xvf ./gst-plugins-good.tar
tar xvf ./cerbero.tar
tar xvf ./gst-examples.tar
tar xvf ./gst-omx.tar
tar xvf ./gst-rtsp-server.tar
tar xvf ./gst-build.tar
tar xvf ./gst-plugins-base.tar
tar xvf ./gst-editing-services.tar
tar xvf ./gst-devtools.tar
tar xvf ./gst-plugins-ugly.tar
tar xvf ./gst-libav.tar
tar xvf ./orc.tar
tar xvf ./gst-python.tar
tar xvf ./gst-integration-testsuites.tar
tar xvf ./qt-gstreamer.tar
```


### 99 files num
https://cloud.tencent.com/developer/article/1751119
The blog is very good.
```shell
ls -l |grep "^-"|wc -l   //统计当前文件夹下文件的个数
ls -l |grep "^d"|wc -l	//统计当前文件夹下目录的个数
ls -lR|grep "^-"|wc -l	//统计当前文件夹下文件的个数，包括子文件夹里的
ls -lR|grep "^d"|wc -l   //统计文件夹下目录的个数，包括子文件夹里的
```


TODO:
.gitmodules


```shell
tom@tom-virtual-machine:~/ws_gst/github$ find . -name .gitmodules
./gst-docs/.gitmodules
./gst-build/.gitmodules
tom@tom-virtual-machine:~/ws_gst/github$
```