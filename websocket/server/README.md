# 包含客户端和服务器端 websocket 测试 demo

# 启动

客户端启动：使用 vs code 插件 Live Server 打开，在 index.html 文件中右键使用 Open With Live Server

服务器端启动：终端进入 server 目录，运行 yarn start

服务器和客户端都启动后，就可以在客户端浏览器中对服务器端 ws 服务进行连接、发送消息、关闭连接的操作。

# ws 客户端：client

包含连接服务端 ws，给服务端发送 ws 信息，关闭 ws 连接功能

# ws 服务器端：server
