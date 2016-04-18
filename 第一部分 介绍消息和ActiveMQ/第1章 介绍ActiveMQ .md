# 第1章 介绍ActiveMQ
```
这一章的内容
- 对ActiveMQ的特性和使用进行高度概括
- 下载和安装ActiveMQ
- 理解ActiveMQ的目录结构
- 运行ActiveMQ的一个例子
```

企业级消息软件从1980就有了。它不仅是应用间系统通信的一种方式，也是一种集成方式。因此，消息传递实现需要应用间相互通知和交互。但是开源实现在近10年才出现。Apache ActiveMQ就是其中一种开源实现，它为应用间的交流提供了一种异步，低耦合的方式。这一章主要向你介绍ActiveMQ。

ActiveMQ是一个开源，遵循Java消息服务(JMS:Java MessageService)1.1规范，它是Apache基金会的一个消息中间件(MOM:message-oriented middleware)项目，提供高可用，高性能，可扩展，高可靠和安全的企业级消息中间件。ActiveMQ使用Apache基金会的许可证，一个最自由和最友好的开源倡议。因为使用Apache许可证，任何人都可以使用更改ActiveMQ。这对使用ActiveMQ的企业有战略意义。 在后续的第2章将介绍中间件在应用之间传递消息和事件，确保消息可靠性。中间件最重要的就是高可用，可靠性，可扩展。
