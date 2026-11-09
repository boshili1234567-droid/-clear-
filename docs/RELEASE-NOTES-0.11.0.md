轻解 v0.11.0 · Windows x64 体验版

**[下载轻解完整发布包：QingJie-0.11.0-windows-x64.zip](https://github.com/boshili1234567-droid/-clear-/releases/download/v0.11.0/QingJie-0.11.0-windows-x64.zip)**

请选择下方 **Assets（附件）** 中的同名 ZIP（约 1.9 MB），解压后打开 `轻解-0.11.0` 文件夹，运行 `轻解.exe`。

GitHub 自动提供的 `Source code (zip)`、`Source code (tar.gz)` 以及 `Code → Download ZIP` 打包的是仓库说明和图标，解压后会看到 `README.md` 和 `docs`。轻解的可运行程序位于上面的完整发布包中。

本版新增：

- 压缩包详细列表：Windows 文件图标、类型、压缩前后大小与修改时间。
- 右键“删除”、工具栏删除及 Delete 键，支持多选和整个文件夹。
- 修改、重命名和导入时保留已有项目的修改时间。

已有功能包括 ZIP / RAR 浏览和解压、ZIP AES-256 加密、基础 RAR5 创建、分层文件夹浏览、复制与拖出、文件加入和重命名、ZIP 剪切，以及批量解压完成判断。

下载本页附件 `QingJie-0.11.0-windows-x64.zip`，解压后运行“轻解.exe”。需要 x64 Windows 10 / 11 和 .NET Framework 4.8 / 4.8.1。运行组件已内置。完整发布包包含使用说明、组件许可、示例文件和验证报告。

RAR 创建和修改限单文件 16 MiB、总计 64 MiB、1,000 项；加密或超限 RAR 保持只读。删除不保留自动备份，操作前会弹出确认。

验证：单 EXE、改名运行、不同工作目录和双实例场景中，各通过 611 项自动化检查；RAR 创建另经 Windows tar 独立解码核对。完整报告见包内 `TEST-REPORT.txt`。

完整发布包 SHA256：

`0622cbf9c88899fc32093ba9184d8cbdacfdf00dbbc86839df9e498577eeab24`

包内可执行文件 SHA256：

`755421102cf21af95856462e2b78c480ddbebff10dbd65a2ce47397cce9f12fd`
