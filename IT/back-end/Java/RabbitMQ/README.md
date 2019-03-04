# RabbitMQ 消息中间件
#### 大纲

- 了解目前主流消息中间件的特点、架构、原理、底层机制
- 掌握 RabbitMQ 核心概念与基础 API 应用，并结合高并发业务场景应用实战
  - AMQP 协议模型解析
  - 环境搭建、极速入门
  - 命令行，管控台最佳使用
  - Exchange Bingding Queue
  - VirtualHost RoutingKey
  - Message 结构详解
- 掌握 RabbitMQ 高级特性，巧妙服务于你的应用服务、架构设计
  - 可靠性投递解析
  - 消息幂等操作
  - Confirm、Return 机制
  - 自定义消息，QOS 限流策略
  - ACK，重回队列
  - TCL 消息、死信队列
- 学会 RabbitMQ 与 Spring 家族整合，更高效的实现 MQ 与应用服务的集成
  - SpringAMQP 管理 / 消息模板
  - SpringAMQP 监听容器
  - SpringAMQP 适配器 / 转换器
  - 与 SpringBoot2.X 整合实战
  - 与 SpringCloudStream 整合
  - 最佳使用心得、技巧
- 掌握 RabbitMQ 集群架构、构建高可靠消息中间件
  - 主备、远程、镜像、多活
    - 镜像队列 & 可靠性存储
    - 高可用 -KeepAlived 组件
    - 负载均衡 -Haproxy 组件
    - 5 种故障恢复失败转移方案
    - 集群插件安装与使用
- 掌握如何保障 100% 的消息投递成功，消费端如何做到幂等
- 紧随互联网大厂的架构设计思路，带大家一起解读 SET 化架构设计思想
  - 大集群 / 同城双活 / 两地三中心
  - SET 化架构设计策略
  - SET 化架构设计原则
  - RabbitMQ 异地多活架构
  - RabbitMQ 多集群路由策略
  - SET 化中间件设计与实现
- 掌握大厂流行的基础组件设计思路，让别人站在你的肩膀上编码
  - MQ 组件架构设计思路
  - 迅速消息，确认消息
  - 批量消息，延迟消息
  - 顺序消息，事务消息
  - 消息幂等性保障
  - 消息路由规则架构设计思路



###