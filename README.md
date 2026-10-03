# SideKite Pair

SideKite Pair（原 LinkFlow Pair）官方 macOS 与 Windows 版本发布页。

项目现已更名为 SideKite Pair。历史 Release、安装包文件名和校验值保持不变；过渡期间旧支持入口继续保留。

Official macOS and Windows releases for SideKite Pair (formerly LinkFlow Pair). Historical release assets and checksums remain unchanged.

LinkFlow Pair 用于在电脑与运行 LinkFlow 的 Apple 设备之间完成设备发现、配对资料生成或导入、验证和传输。配对资料默认只在本机和所选设备之间处理。

## 下载

请从本仓库的 [Releases](https://github.com/zhosix/sidekitepair/releases) 下载最新版本，并核对发布页提供的 SHA-256。

当前公开版本：**LinkFlow Pair 1.0.0**

| 平台 | 发布文件 | 系统要求 |
| --- | --- | --- |
| macOS | `LinkFlow-Pair-1.0.0-macOS.dmg` | macOS 11 或更高版本；Apple 芯片与 Intel |
| Windows | `LinkFlow-Pair-1.0.0-Windows-x64.exe` | Windows 10/11 x64；需 Microsoft Edge WebView2 Runtime |

当前版本未使用 Developer ID/Apple 公证或 Authenticode 签名，系统可能显示来源或信誉提示。请只从本仓库下载并先核对 SHA-256，不要关闭 Gatekeeper、SmartScreen、Defender 或其他系统安全功能。

macOS 不需要自行重签。打开 DMG 后将 App 拖入“应用程序”；若系统阻止首次打开，在确认 SHA-256 正确后，可在 Finder 中按住 Control 点击 App 并选择“打开”，或前往“系统设置 → 隐私与安全性”选择“仍要打开”。

## 校验下载文件

macOS：

```bash
shasum -a 256 LinkFlow-Pair-1.0.0-macOS.dmg
```

Windows PowerShell：

```powershell
Get-FileHash .\LinkFlow-Pair-1.0.0-Windows-x64.exe -Algorithm SHA256
```

校验值应与 Release 中的 `SHA256SUMS` 完全一致。

## 隐私与支持

本地备份包含设备配对凭据。请仅保存到私人、加密且受访问控制的位置，不要上传或分享。

- [LinkFlow 隐私政策](https://linkflow.zhosix.com/privacy)
- 支持与安全问题：`linkflow@zhosix.com`
