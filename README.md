# WebSocket
websocket 网页版Spring4实现


Spring 4.0的一个最大更新是增加了websocket的支持。websocket提供了一个在web应用中的高效、双向的通讯，需要考虑到客户端（浏览器）和服务器之间的高频和低延时消息交换。一般的应用场景有：在线交易、游戏、协作、数据可视化等。
 
使用websocket需要考虑的浏览器的支持（IE<10不支持），目前主流的浏览器都能很好的支持websocket。
websocket协议中有一些子协议，可以从更高的层次实现编程模型，就像我们使用HTTP而不是TCP一样。这些子协议有STOMP,WAMP等。
