轻解 v0.14.0 · Windows x64 体验版

**[下载完整发布包](https://github.com/boshili1234567-droid/-clear-/releases/download/v0.14.0/QingJie-0.14.0-windows-x64.zip)**

在 **Assets（附件）** 中选择 `QingJie-0.14.0-windows-x64.zip`。解压后进入 `轻解-0.14.0` 文件夹，运行 `轻解.exe`。适用于 Windows 10 / 11 x64，需 .NET Framework 4.8 或 4.8.1。GitHub 自动生成的 `Source code (zip)` 和 `Source code (tar.gz)` 是仓库说明文件包。

## 大文件拖出修复

- **拖到目标文件夹即可松手。** 轻解在拖动时提供文件名和大小，放下后再解压并交给 Windows 复制。大文件所需的准备时间移到了松手之后。
- 支持多选文件和文件夹。文件夹的子目录、中文名称和空目录会随复制保留。复制期间使用经过校验的临时文件，正常完成后清理。
- 对于只接收普通文件路径的应用，可以在轻解中按 **Ctrl+C**，再到目标位置粘贴。

## 验证

通过 693 项自动化检查。使用 Windows 原生文件夹拖放接收接口验证了 512 MiB 文件、中文目录和空子目录的复制，目标文件的 SHA-256 与源内容一致。

发布包 SHA-256

`24dfa2f26ef8ae48994bb36b4a1305baf1e638e89b569dec36966c1b3934194a`
