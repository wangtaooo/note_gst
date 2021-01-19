# 7 Remote Server



### 1 patch

command:
```shell
sshpass -p x6scMyMSYhyz ssh root@96.45.180.86 -p 29962


sshpass -p x6scMyMSYhyz scp -P 29962 root@96.45.180.86:/home/samba_root/ws_mavlink/qgc-dev-guide.tar .

```


### 2 open_remote_server.sh
```shell
#!/bin/bash


#NOTE:

#First we need to run cmd 
#"ssh $SERVER_USER_NAME@$SERVER_IP -p $ERVER_PORT"
#to creat key

#and we need have sshpass
#sudo apt-get install sshpass



SERVER_USER_NAME=tom
SERVER_USER_PASSWORD=tom

SERVER_IP=67.218.157.69
SERVER_PORT=26239

#sshpass -p nvidia ssh nvidia@10.42.0.1

#ssh $SERVER_USER_NAME@$SERVER_IP -p $SERVER_PORT

sshpass -p $SERVER_USER_PASSWORD ssh $SERVER_USER_NAME@$SERVER_IP -p $SERVER_PORT
```




### 3 sftp_login.sh

```shell
#!/bin/bash

#NOTE:

#First we need to run cmd 
#"sftp -P $SERVER_PORT $SERVER_USER_NAME@$SERVER_IP"
#to creat key

#and we need have sshpass
#sudo apt-get install sshpass


SERVER_USER_NAME=tom
SERVER_USER_PASSWORD=tom

SERVER_IP=67.218.157.69
SERVER_PORT=26239

#sftp -P $SERVER_PORT $SERVER_USER_NAME@$SERVER_IP

sshpass -p $SERVER_USER_PASSWORD sftp -P $SERVER_PORT $SERVER_USER_NAME@$SERVER_IP
```