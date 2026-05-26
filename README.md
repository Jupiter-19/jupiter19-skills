# jupiter19-skills

个人 SKILL 集合。

## Config 配置审计助手

查询云上资源、配置、Schema 和合规规则。

- **资源概览** — 按云服务/类型/区域汇总资源数量
- **资源 Schema** — 获取资源类型的完整结构定义
- **SQL 查询** — 用 SQL 灵活查询资源，内置 46 条示例覆盖 ECS/VPC/OBS/RDS 等主流服务
- **合规规则** — 检索 Config 预置合规规则

依赖：`pip install huaweicloudsdkconfig huaweicloudsdkcore`，需配置 `HUAWEICLOUD_AK` / `HUAWEICLOUD_SK` 环境变量。

## Python SDK 查询工具

自动发现已安装华为云 SDK 的所有内容，无需翻阅源码。

- **列出 SDK 包** — 一键查看已安装的所有服务 SDK
- **查看 Client 方法** — 展示指定 Client 的全部 API 方法及描述
- **查询入参详情** — 自动提取 Request 类的属性名、类型和中文描述
- **关键字搜索** — 在方法名和描述中快速定位目标 API
- **查看类定义** — 展示 SDK 类的 `__init__` 参数、属性和类型

依赖：`pip install huaweicloudsdk<service>`，按需安装目标服务 SDK 即可。
