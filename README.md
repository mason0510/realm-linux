# realm-linux
服务器流量转发工具


# 从服务器拉代码到本地
scp -r root@23.254.167.135:/root/releam /Users/houzi/home/pandaCapital/realm-linux


# 本地上传
scp /home/work/source.txt work@192.168.0.10:/home/work/   #把本地的source.txt文件拷贝到192.168.0.10机器上的/home/work目录下


# 服务起停
systemctl daemon-reload
systemctl enable realm
systemctl restart realm
systemctl status myrealm
systemctl stop myrealm
