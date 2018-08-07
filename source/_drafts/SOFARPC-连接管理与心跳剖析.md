---
title: SOFARPC-连接管理与心跳剖析
tags: [原创, 技术, 源码分析]]
categories: SOFA-STACK
---
### 前沿
### 长连接
#### tcp 的 keep-alive 是什么
#### 默认值
#### 如何使用
#### 检查
### 应用层 keep-alive
#### 心跳是什么
#### 如何使用
### 应用层心跳还是 tcp-alive
### sofa-rpc 中的连接管理
#### 系统 tcp keep-alive
#### bolt 基于 netty 实现心跳连接
##### 客户端
##### 服务端
#### rpc
### 参考文档