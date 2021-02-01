> 关于前端的HTTP

传输层: TCP、UDP

应用层(构建于TCP协议之上)：HTTP


#### HTTP1.1：
TCP 持久连接connection
pipeline：同一个连接发送多个请求
增加host和其他一些命令 => 一台物理机跑多个服务

#### HTTP2
所有数据以二进制传输
同一个连接发送多个请求，不再需要按照顺序
头信息压缩，以及推送等提高效率的功能

#####

user(创建一个http request) <=> TCP connection <=> 服务器




