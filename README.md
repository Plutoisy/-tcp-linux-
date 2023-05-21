## 基于tcp的linux聊天室
njuee的linux大作业
## 功能：
+ 用户需要登录，登录时只需要输入一个昵称，需判断昵称是否重复 
+ 用户登录后连接服务器端，进入聊天室 
+ 用户可以输入聊天信息，也可以收到别人的聊天信息。 
+ 用户可以用某个特殊字符退出聊天室。
+ 启动服务器，开放端口 
+ 等待客户端的连接，每连接上一个客户端，启动一个线程或进程 
+ 在新的线程或进程中与客户端交互，交互过程：如果有客户端登录、退出、提交聊天，都应该发给所有的客户端。需要保存所有客户端。
+ 实现TCP/UDP的各类文件传输（文本、语音、图片等）。
