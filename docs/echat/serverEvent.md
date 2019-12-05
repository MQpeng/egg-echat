## 接收服务器事件推送 {docsify-ignore}

在文档的快速入门章节已经详细的讲解了服务端的设置，本章节将详细介绍企业微信推送给服务端的事件，服务端的接收到的*MsgType*固定为 `event`,此时需要根据*Event* 判断是哪个事件，对于特殊的通讯录变更事件（`change_contact`）来确定是哪一类事件变更，对于**菜单事件**，需要通过判断`key`来判断，当然这是你自己设定的！

#### 事件列表

参考各企业微信的私有化部署的文档，此处由于特殊原因不公开。


