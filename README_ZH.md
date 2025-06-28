<p align="center">
  <h1 align="center">OpenMetadata元数据管理平台</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>

## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍
‌[OpenMetadata‌](https://github.com/open-metadata/OpenMetadata) 是一个统一的元数据平台，用于数据发现，数据可观察性和数据治理，由中央元数据存储库，深入的列级血统来提供支撑。Open Metadata基于开放元数据标准和API，支持各种数据服务的连接器，可实现端到端元数据管理，让您自由释放数据资产的价值。

**核心特性：**
1. 数据协作- 通过活动源获取事件通知。使用 webhook 发送警报和通知。添加公告以通知团队即将发生的更改。添加任务以请求描述或术语表术语批准工作流程。添加用户提及并使用对话线程进行协作。
2. 数据质量和分析器- 标准化测试和数据质量元数据。将相关测试分组为测试套件。支持自定义SQL数据质量测试。有一个交互式仪表板可以深入了解详细信息。
3. 数据血缘- 支持丰富的列级沿袭。有效过滤查询以提取沿袭。根据需要手动编辑谱系，并使用无代码编辑器连接实体。
4. 全面的角色和策略- 处理复杂的访问控制用例和分层团队。
5. 连接器- 支持连接到各种数据库、仪表板、管道和消息传递服务的 55 个连接器, 术语表- 添加受控词汇来描述组织内的重要概念和术语。添加词汇表、术语、标签、描述和审阅者。

**架构设计：**

![](./images/img001.png)


本项目提供的开源镜像商品 [**OpenMetadata元数据管理平台**](https://marketplace.huaweicloud.com/hidden/contents/f5371015-bb64-4f24-ae68-c8718967e232#productid=OFFI1144191777593155584)，已预先安装 OpenMetadata 软件及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

> **系统要求如下：**
> - CPU: 2GHz 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                                                                      | 特性说明                                         | 备注 |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------| --- |
| [OpenMetadata1.7-kunpeng-v1.0](https://github.com/HuaweiCloudDeveloper/airflow-image/tree/OpenMetadata1.7-kunpeng-v1.0)      | 基于 鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |
| [OpenMetadata1.7-kunpeng-v1.0](https://github.com/HuaweiCloudDeveloper/airflow-image/tree/OpenMetadata1.7-kunpeng-v1.0) | 基于 鲲鹏服务器 + Ubuntu24.04 64bit 安装部署         |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/OpenMetadata-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
