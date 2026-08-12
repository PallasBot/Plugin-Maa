# 更新日志

本文件依据 git tag 历史整理，版本号遵循[语义化版本](https://semver.org/lang/zh-CN/)。
新提交合入后请在 `## [Unreleased]` 下记录，发布时随版本 tag 归档。

## [4.0.23] - 2026-08-12

- MAA 路由挂载与任务汇报日志改为叙事格式；getTask 高频轮询日志限频输出。

## [4.0.22] - 2026-08-11

- feat(logging): 补充启动 ready 日志

## [4.0.21] - 2026-08-11

- feat(logging): 统一任务排队事件文案

## [4.0.20] - 2026-08-11

- feat(logging): 补充 MAA 绑定、任务排队与结果投递业务事件日志

## [4.0.19] - 2026-07-26

- feat(llm_tools): 为口令工具补充口语 hints

## [4.0.18] - 2026-07-26

- feat(config): WebUI 配置字段增加 ui_group 分组与 ui_order 排序


## [4.0.17] - 2026-07-25

- feat: 声明群口令 `llm_tools`，供闲聊 selective 工具调用
## [4.0.16] - 2026-07-25

- feat: PluginMetadata.extra 增加 `help_tag`（帮助图分组）

## [4.0.14] - 2026-06-30
- refactor(metadata): `help_audience` 由 `maintainer` 改为 `superuser`（项目无独立维护者权限等级，统一到超管）

## [4.0.13] - 2026-06-27
- docs(readme): 命令权限默认等级改用中文展示

## [4.0.12] - 2026-06-27

- feat(maa): 补齐清空队列/切换设备等命令权限声明，冷却接入 command_limits 并显示中文名

## [4.0.11] - 2026-06-27
- docs(readme): 「怎么使用」口令统一加行内代码标记

## [4.0.10] - 2026-06-27
- fix(help): 二级帮助用法「下表」改为「上方功能一览」，适配 help v3 布局

## [4.0.9] - 2026-06-27
- fix(help): 帮助页用法文案去掉 Markdown 加粗星号，适配 PIL v3 成图

## [4.0.8] - 2026-06-25
- feat(metadata): 补充绑定 MAA 命令冷却声明

## [4.0.7] - 2026-06-24
- feat(knowledge): 声明 knowledge_sources FAQ 供 LLM 注入

## [4.0.6] - 2026-06-19
- docs(assets): 更新头像资源并改用 PyPI 版本徽章
- chore(assets): 替换品牌头像为透明背景版本

## [4.0.5] - 2026-06-18
- docs(readme): 统一官方插件卡片模板

## [4.0.4] - 2026-06-18
- docs(readme): 更新官方扩展安装命令

## [4.0.3] - 2026-06-18
- migrate: src.* → pallas.api.* / pallas.product.* / pallas.core.*
- release: bump to 4.0.3 for pallas import migration

## [4.0.2] - 2026-06-18
- docs(readme): 添加 Pallas-Bot hero 图
- chore(release): 4.0.2 同步 README 进 PyPI 包

## [4.0.1] - 2026-06-17
- feat: Pallas-Bot 4.0 官方扩展首包
- fix(build): 修正 hatch wheel 的 src 包路径
- feat(release): PyPI 发版 workflow 与 4.0.1
