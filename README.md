# Emoji 转 QQ 表情

> 本插件由 [Wenaixi](https://github.com/Wenaixi) 维护，是专为生产环境深度调优的高可用分支。

## 简介与定位

基于出站拦截钩子，自动将回复消息中的 Unicode Emoji 转换为 QQ 原生 Face 表情段。

- **插件目录**：`wenaixi_mai_emoji_to_qq_face`
- **生效版本**：`v1.0.0`
- **开源许可证**：`MIT`

---

## 核心特性与本地深度调优

- 优化映射表，防止特殊符号被误替换，与复读机原生表情复读完全兼容

---

## 指令与工具速查

### 常用指令 (Command)
- `(出站消息处理型插件，无独立命令)`

### 大模型工具 (Tool)
- `(出站前置 Hook 自动转换，无独立工具)`

---

## 快速配置

配置文件统一定位于插件根目录下的 `config.toml`。修改后重启或通过 WebUI 热重载即可生效。

---

## 上游项目与开源溯源

- **原作者 / 组织**：`Wenaixi (本地自研与社区规范分支)`
- **官方原版开源仓库**：[https://github.com/Wenaixi/wenaixi_mai_emoji_to_qq_face](https://github.com/Wenaixi/wenaixi_mai_emoji_to_qq_face)
- **开源协议**：`MIT`
- **声明**：本项目遵循开源协议，特此致敬原作者的杰出贡献。本分支针对生产环境的高并发网络、个性化社交和抗风控需求进行了深度稳定性修复与定制化演进。
