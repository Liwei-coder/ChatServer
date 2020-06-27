# ChatServer
基于redis、muduo网络库、MySQL服务，运行在nginx tcp负载均衡环境中的集群聊天服务器和客户端代码源码 

1.编译方式
（1）cd build
（2）sudo rm -rf *
（3）cmake ..
（4）make

2.使用nginx负载均衡时要先启动nginx服务
（1）cd /usr/local/nginx/sbin
（2）./nginx
——————————————————————————————————————————————————————————————————————————————————————
3.后面记得补充每个文件夹内容，服务的详细介绍
