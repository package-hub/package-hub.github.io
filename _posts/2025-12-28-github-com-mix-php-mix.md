---
title: mix
categories: ['php', 'swoole', 'coroutine']
---
## [mix](https://github.com/mix-php/mix)

### ☄️  PHP CLI mode development framework, supports Swoole, WorkerMan, FPM, CLI-Server / PHP 命令行模式开发框架，支持 Swoole、Swow、WorkerMan、FPM、CLI-Server


核心模块全部可独立使用，并且都支持原生代码开发。

- [mix/vega](src/vega) PHP 编写的 CLI 模式 HTTP 网络框架，支持 Swoole、Swow、WorkerMan、FPM、CLI-Server
- [mix/database](src/database) 可在各种环境中使用的轻量数据库，支持 FPM、CLI、Swoole、WorkerMan，可选的连接池 (协程)
- [mix/redis](src/redis) 可在各种环境中使用的 PHP Redis，支持 FPM、CLI、Swoole、WorkerMan，可选的连接池 (协程)
- [mix/redis-subscriber](src/redis-subscriber) 基于 Swoole 协程的 Redis 原生协议订阅库
- [mix/grpc](src/grpc) 基于 Swoole 协程的 PHP gRPC 库，包含 protoc 代码生成器、服务器、客户端
- [mix/websocket](src/websocket) 基于 Swoole 协程的 PHP WebSocket 服务器与客户端
- [mix/cli](src/cli) PHP 命令行交互指挥官
- [mix/worker-pool](src/worker-pool) 基于 Swoole 的协程池、工作池库
- [mix/validator](src/validator) 基于 PSR-7 的验证库
- [mix/event](src/event) 基于 PSR-14 标准的事件调度库
- [mix/init](src/init) 帮助执行类的静态初始化，通常用于预加载单例
