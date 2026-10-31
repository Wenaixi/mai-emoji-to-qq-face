# CLAUDE.md - Emoji 转 QQ 表情 (emoji2face)

## 1. 模块定位与系统职责
- **插件标识符**：`emoji2face`
- **当前生效版本**：`v1.0.0`
- **托管仓库**：[`Wenaixi/emoji2face`](https://github.com/Wenaixi/emoji2face)
- **核心定位**：基于出站拦截钩子（send_service.before_send），自动将消息中的 Unicode Emoji 转换为 QQ 原生 Face 表情段。

## 2. 关键工程规范与配置说明
- **配置路径**：`config.toml`（所有业务调优与鉴权参数收敛于此）；
- **数据持久化**：优先遵循 MaiBot SDK 标准持久化规范，不直接向源码目录写入易失数据；
- **编码与日志规范**：严格遵循 PEP 8 风格，文档与代码注释杜绝 emoji，避免虚假套话。

## 3. 本地深度定制与稳定性修复
优化映射表，防止特殊符号被误替换，与复读机插件完全协同。

---

## 上游项目与开源溯源
- **原作者 / 组织**：`Wenaixi (本地自研与社区规范分支)`
- **官方上游仓库**：[https://github.com/Wenaixi/emoji2face](https://github.com/Wenaixi/emoji2face)
- **开源许可证**：`MIT`
- **分支演进模式**：本仓库作为主人的深度定制与生产维护分支（`Wenaixi/emoji2face`）。在保持与官方上游架构演进对齐的同时，锁死并持续维护针对本服务器生产环境的稳定性补丁与核心特性。
