

## RabbitMQ .NET Client [![Build status](https://ci.appveyor.com/api/projects/status/33srpo7owl1h3y4e?svg=true)](https://ci.appveyor.com/project/rabbitmq/rabbitmq-dotnet-client)

MQ全称为Message Queue, 消息队列（MQ）是一种应用程序对应用程序的通信方法。应用程序通过读写出入队列的消息（针对应用程序的数据）来通信，而无需专用连接来链接它们。消息传递指的是程序之间通过在消息中发送数据进行通信，而不是通过直接调用彼此来通信，直接调用通常是用于诸如远程过程调用的技术。排队指的是应用程序通过 队列来通信。队列的使用除去了接收和发送应用程序同时执行的要求。
This repository contains source code of the [RabbitMQ .NET client](https://www.rabbitmq.com/dotnet.html).
The client is maintained by the [RabbitMQ team at Pivotal](https://github.com/rabbitmq/).


## Dependency (Binaries and Nuget Artifact)

### Modern Versions

The client is [distributed via NuGet](https://www.nuget.org/packages/RabbitMQ.Client/).

### Legacy Versions

`3.6.x` and earlier releases were distributed [together with RabbitMQ server 3.6.x](https://github.com/rabbitmq/rabbitmq-server/releases/)
as archives.

[Release archive up to 3.4.3](https://bintray.com/rabbitmq/archive/rabbitmq-dotnet-client) is available from Bintray.


## Tutorials and Documentation

 * [Tutorials](https://www.rabbitmq.com/getstarted.html)
 * [Documentation guide](https://www.rabbitmq.com/dotnet.html)
 * [API Documentation](https://rabbitmq.github.io/rabbitmq-dotnet-client/index.html)


## Supported Platforms and .NET Releases

`4.x` and `5.x` versions of the library require .NET 4.5.1 or later or .NET Core.
For .NET Core users, 2.0 is the minimum supported version for `5.x` series.

`3.6.x` releases support Linux and OS X on [Mono](https://www.mono-project.com/).

## Change Log

See [ChangeLog.md](https://github.com/rabbitmq/rabbitmq-dotnet-client/blob/master/ChangeLog.md).

## Building from Source

Please see [How to Run Tests](./RUNNING_TESTS.md) and [Building .NET Core](./BUILD_DOTNET_CORE.md)
for build process overview.

## Contributing

See [Contributing](./CONTRIBUTING.md) and [How to Run Tests](./RUNNING_TESTS.md).


## License

This package, the RabbitMQ .NET client library, is double-licensed under
the Mozilla Public License 1.1 ("MPL") and the Apache License version 2 ("ASL").
