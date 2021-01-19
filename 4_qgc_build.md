# 4 QGC Build


### 1、清除
```shell
/usr/bin/make clean -j4
```
### 2、生成makefile
```shell
/home/tom/Qt/5.12.6/gcc_64/bin/qmake /home/tom/ws_qgc/qgc_356/qgroundcontrol/qgroundcontrol.pro -spec linux-g++ CONFIG+=debug CONFIG+=qml_debug
```
### 3、这步没实际作用
```shell
/usr/bin/make -f /home/tom/ws_qgc/qgc_356/build/Makefile qmake_all
```
### 4、编译
```shell
/usr/bin/make -j4
```
### 5、启动QGC
```shell
cd ./staging/QGroundControl
```