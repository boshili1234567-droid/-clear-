# 轻解

<img src="docs/qingjie-icon.png" width="96" alt="轻解图标">

轻解是一款 Windows 压缩包工具，文件在本机处理。支持 ZIP、RAR / RAR5 浏览与解压、ZIP 密码加密，以及压缩包内文件管理。

设计原则：简约、免费、快速、便捷，减少无关弹窗。

## 下载与运行

下载 [轻解 0.11.0 完整发布包](https://github.com/boshili1234567-droid/-clear-/releases/download/v0.11.0/QingJie-0.11.0-windows-x64.zip)，解压后运行 `轻解.exe`。更新说明见 [v0.11.0 发布页面](https://github.com/boshili1234567-droid/-clear-/releases/tag/v0.11.0)。

- 系统：Windows 10 / 11，x64。
- 运行环境：.NET Framework 4.8 或 4.8.1。
- ZIP、加密和 RAR 读取组件已内置，无需安装 WinRAR 或另行复制 DLL。
- 当前版本：0.11.0 体验版。发布包附带使用说明、组件许可和自动化验证报告。

## 功能

- 创建 ZIP、基础 RAR5 压缩包；支持多个文件合并打包。
- 解压 ZIP、RAR / RAR5，支持密码 ZIP 和单卷加密 RAR。
- ZIP AES-256 密码加密。
- 按文件夹层级浏览压缩包，显示项目图标、类型、大小、压缩后大小和修改时间。
- 文本、常见图片预览；复制和拖出文件或整个文件夹。
- 向压缩包加入文件、重命名、删除；ZIP 支持剪切到指定文件夹。
- 批量解压跳过当前队列中已完成的任务，可手动重新解压所选任务。
- 可启用 ZIP / RAR 双击打开，以及拖文件到桌面压缩包图标后加入。

## 使用说明

双击文件关联需在轻解中点击“关联 / 图标拖入”→“启用双击与图标拖入”，再由用户在 Windows 中选择默认应用。移动下载文件不会影响固定安装副本。

压缩包内删除操作会直接修改原包，不保留自动备份或恢复记录；删除前会显示确认提示。

RAR 创建与修改目前限单文件 16 MiB、总计 64 MiB、最多 1,000 项；暂不支持创建加密、分卷或固实 RAR。加密或超过修改范围的 RAR 可浏览、解压，保持只读。不支持 7z、分卷压缩包或压缩包修复。

## 许可与反馈

第三方组件及其许可见发布包中的 `THIRD-PARTY.txt`、`UNRAR-LICENSE.txt`、`RAR-ENCODER-REFERENCE.txt` 和 `component-licenses/`，软件中的“关于 / 组件许可”也可查看。

目前该仓库用于发布软件包与使用说明，项目源代码暂未公开。

可以在 [Issues](https://github.com/boshili1234567-droid/-clear-/issues) 反馈问题，请说明 Windows 版本、软件版本、压缩格式和复现步骤。提交日志或截图前，请检查其中的个人文件路径和资料。
