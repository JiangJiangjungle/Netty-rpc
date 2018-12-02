﻿# Netty-rpc

一个用于个人学习的轻量级rpc框架

### 服务注册与发现中心
 - **ZooKeeper**
 
### 通信框架
 - **Netty**

### 序列化
- **Protostuff**
- **JSON**

### 两种调用模式
- **同步调用**
- **异步（Future）调用**

### 可靠连接
- **自定义的简单通信协议**

| 长度（4byte） | 消息类型（1byte） | 数据(不定长) |
| :-------- | --------:| :--: |

- **心跳检测机制**
- **断线重连机制**
