# 简介

EMQ X Cloud Rule Engine (以下简称规则引擎) 用于配置 EMQ X 消息流与设备事件的处理、响应规则。规则引擎不仅提供了清晰、灵活的「配置式」的业务集成方案，简化了业务开发流程，提升用户易用性，降低业务系统与 EMQ X 的耦合度；也为 EMQ X 的私有功能定制提供了一个更优秀的基础架构。

在 EMQ X Cloud 中，使用规则引擎会有如下要求：

- 对于免费试用部署以及共享部署：数据库等资源访问仅支持公网访问，因此在创建资源前您需要确保资源具有公网访问能力，同时开放安全组。

- 对于独享部署: 数据库等资源访问仅支持内网访问，因此在创建资源前您需要先配置 VPC 对等连接，同时开放安全组。

![rule_engine](./_assets/rule_engine.jpg)


## [规则](./rule.md)
规则引擎不仅提供了清晰、灵活的 "配置式" 的业务集成方案，简化了业务开发流程，提升用户易用性，降低业务系统与 EMQ X 的耦合度；也为 EMQ X 的私有功能定制提供了一个更优秀的基础架构。

## [资源](./resource.md)
EMQ X Cloud 资源用于规则引擎响应动作， 在此之前您需要确保部署状态为 `running`。