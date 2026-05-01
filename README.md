# AI IDE Switcher

> 多 IDE 账号平台 —— **Windsurf · Trae · Kiro** 三账号库 / 一键切换 / 额度监控 / 自动换号 / 托盘后台运行，让你的 AI IDE 永远满额度。
>
> v3.0 起：完整接入 Kiro IDE — 三大 AI IDE 统一管理，一个工具全搞定。
>
> *静态安装目录 / userData 路径仍为 `windsurf-switcher` 以兼容老用户；GitHub 仓库已同步重命名为 `AI-IDE-Switcher-releases`。*

[![Downloads](https://img.shields.io/github/downloads/WanJiu-LF/AI-IDE-Switcher-releases/total)](https://github.com/WanJiu-LF/AI-IDE-Switcher-releases/releases)
[![Latest Release](https://img.shields.io/github/v/release/WanJiu-LF/AI-IDE-Switcher-releases)](https://github.com/WanJiu-LF/AI-IDE-Switcher-releases/releases/latest)

## ✨ 核心功能

### 🎯 多 IDE 账号平台 （v3.0新）
- **三账号库**：Windsurf · Trae · Kiro 完全隔离，顶部一键切换
- **Kiro BuilderId 登录**：AWS SSO PKCE 流程一键完成，Token 自动入库
- **Kiro Live 额度**：实时 Bonus / Premium / Pro 额度查询与监控
- **Kiro 无感切换**：热写入 auth 文件，无需重启 Kiro 即可生效
- **Kiro 自动换号**：监控 Bonus Credits 额度，低于阈值自动切换
- Trae / Windsurf 全部功能保持不变

### 📑 多账号管理
- 一键添加无限账号（三边账号库独立）
- Windsurf 隐藏式浏览器自动登录 · Trae 内置 OAuth 流 · Kiro AWS SSO PKCE
- 一键刷新 Token（三 IDE 都支持）：账号过期时静默 re-login，免去重走完整 OAuth
- JSONL 批量导入（三 IDE 都支持）：注册机导出文件拖放导入，含 Token 的账号免登录直接可用
- 账号信息加密本地存储，跨机器迁移用一份加密备份文件搞定
- **`.wsb` v2 备份**：Windsurf + Trae 一并打包；v1 旧备份向后兼容

### ⚡ 无感切换
- 切换账号**不需重启 IDE**（Windsurf · Trae · Kiro 都支持），新账号瞬间生效
- IDE 状态全保留：编辑窗口、终端会话、未保存的改动 —— 通通不丢
- 切完即用，体感 < 1 秒

### 📊 智能监控 & 自动换号
- 实时查询每个账号的额度（Windsurf Cascade · Trae 美元 · Kiro Bonus/Premium/Pro）
- 三 IDE **独立调度器**：各自设阈值、各自冷却、各自黑名单
- 设阈值（如 < 20% 自动换号）→ 后台守护监控 → 不足自动切下一个有额度的账号
- 详细切换历史 / 错误日志，每一次动作都可追溯

### 📈 使用画像
- Windsurf Cascade：代码行数、模型用量、对话总数
- Trae：7 天 / 365 天热力图 + 模型占比 + 累计美元耗用
- Kiro（v3.0新）：Bonus / Premium / Pro 额度分布 + 过期预警
- 按日 / 周 / 月聚合，一眼看清你的 AI 编程总投入

### ⌨️ 产品化体验（v2.0新）
- **首屏 Onboarding**：首次启动智能引导，三选一上手
- **快捷键**：`Ctrl+1/2/3` 切 IDE · `Ctrl+Shift+S` 切下一个账号 · `Ctrl+/` 帮助
- **托盘菜单升级**：Windsurf / Trae / Kiro 分区块显示，子菜单内联额度，不必打开主窗口即可切号

### 🚀 极致体验
- 现代 UI，深浅主题随系统切换
- 系统托盘后台运行，关窗不退出
- 开机自启 + 启动时直接到后台
- 安装版支持自动更新，无感升级到最新版本
- **性能大幅优化**（v2.0）：日志页虚拟化 / 滚动合成层隔离 / 后台轮询按需

---

## 📥 下载

Windows 10/11 64-bit：[最新版下载](https://github.com/WanJiu-LF/ai-ide-switcher-releases/releases/latest)

- **安装版**（推荐）：`AI IDE Switcher Setup x.x.x.exe` · 支持自动更新
- **便携版**：`AI IDE Switcher-x.x.x-portable.exe` · 单文件免安装 · 不含自动更新


## 🛡️ 隐私保护

- 所有账号数据**本地加密存储**，不上传任何第三方服务器
- 仅在你主动操作（刷新 Token / 切换账号 / 查询额度）时才与 Windsurf / Trae / Kiro 服务通信
- 授权验证仅在激活时与每 24 小时一次的合法性检查时联网，**不传任何账号信息**

## ⚠️ 免责声明

本工具仅供个人多账号 Windsurf / Trae / Kiro 使用场景，与 Windsurf / Codeium / Trae / ByteDance / Kiro / Amazon 官方均无关联。
使用本工具产生的任何后果由使用者自行承担。

---

**作者**：晚九 (WanJiu)
