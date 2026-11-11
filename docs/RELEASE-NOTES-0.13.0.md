轻解 v0.13.0 · Windows x64 体验版

**[下载完整发布包](https://github.com/boshili1234567-droid/-clear-/releases/download/v0.13.0/QingJie-0.13.0-windows-x64.zip)**

在 **Assets（附件）** 中选择 `QingJie-0.13.0-windows-x64.zip`。解压后进入 `轻解-0.13.0` 文件夹，运行 `轻解.exe`。适用于 Windows 10 / 11 x64，需 .NET Framework 4.8 或 4.8.1。GitHub 自动生成的 `Source code (zip)` 和 `Source code (tar.gz)` 是仓库说明文件包。

## 本版改进

- **扩展文件预览。** PDF 支持翻页。Word 显示正文，Excel 可切换工作表并查看单元格，PowerPoint 可按页查看幻灯片文字。现代 Office 内容预览支持 DOCX、XLSX、PPTX 及对应的宏文件扩展名。新增 TIFF 和 ICO 图片预览。常见音视频在预览窗口点击“播放”，具体格式取决于 Windows 已安装的解码器。旧版 Office、WPS 和 RTF 可使用 Windows 中已注册的兼容预览组件。
- **直接浏览包内的压缩文件。** 双击 ZIP、RAR、TAR、TAR.GZ 或 TGZ，即可在只读窗口查看内容、继续预览或复制文件。每次仅暂存所选的内嵌压缩包，关闭窗口时清理临时副本。单个内嵌包预览上限为 2 GiB。修复了较长的包内路径导致目录无法浏览的问题。
- **TAR 系列支持改名。** 在外层 `.tar`、`.tar.gz` 或 `.tgz` 中选中文件或文件夹，按 **F2** 或点击“重命名”。改文件夹名会一并更新子项目路径。轻解写入并校验临时压缩包后再替换原包。大包改名需要时间和同一磁盘上的临时空间。

## 验证

通过 673 项自动化检查。另用约 2.68 GB 的 TAR.GZ 核对了 6 个内嵌 ZIP 的目录，在副本上改名后逐项核对，文件内容的 SHA-256 一致。更多预览格式和大小限制见发布包中的 `使用说明.txt`。

发布包 SHA-256

`4e1749eb1f837e52afe73d98c27580b951203b373a482b41022a9cbaa6939f7f`
