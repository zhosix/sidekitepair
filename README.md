# SideKite Pair

[English](#english) · [简体中文](#简体中文)

## English

**The desktop pairing companion for SideKite.**

SideKite Pair helps you discover Apple devices, create or import pairing records, and verify and transfer them between your computer and the selected device. Available for macOS and Windows.

[Download](https://github.com/zhosix/sidekitepair/releases) · [Verify your download](#verify-your-download) · [SideKite for iOS](https://github.com/zhosix/sidekite)

### Key features

- **Device discovery** — Find Apple devices to use with SideKite.
- **Pairing record creation and import** — Generate pairing records or import existing ones.
- **Verification and transfer** — Verify pairing records and transfer them to the selected device.
- **Local handling by default** — Pairing records are handled between your computer and the selected device.

### Download and installation

> SideKite Pair was previously named LinkFlow Pair. Historical releases, installer filenames, and checksums remain unchanged.

Download from this repository’s [Releases](https://github.com/zhosix/sidekitepair/releases) and compare the file’s SHA-256 with the published checksum before installation.

| Platform | Installer | Requirements |
| --- | --- | --- |
| macOS | `LinkFlow-Pair-1.0.0-macOS.dmg` | macOS 11 or later; Apple silicon and Intel |
| Windows | `LinkFlow-Pair-1.0.0-Windows-x64.exe` | Windows 10/11 x64; Microsoft Edge WebView2 Runtime |

**Signing notice:** The macOS installer listed above is not Developer ID–signed or Apple-notarized; the Windows installer is not Authenticode-signed. Your system may show an origin or reputation warning. Download only from this repository and verify SHA-256 first. Do not disable Gatekeeper, SmartScreen, Defender, or other system security features.

**macOS:** No re-signing is needed. Open the DMG and drag the app into Applications. If the first launch is blocked, verify the SHA-256 before using Control-click → Open in Finder, or Open Anyway in System Settings → Privacy & Security.

### Verify your download

macOS:

```bash
shasum -a 256 LinkFlow-Pair-1.0.0-macOS.dmg
```

Windows PowerShell:

```powershell
Get-FileHash .\LinkFlow-Pair-1.0.0-Windows-x64.exe -Algorithm SHA256
```

The result must exactly match the corresponding entry in the release’s `SHA256SUMS` file.

### Privacy and support

Local backups contain device pairing credentials. Keep them in a private, encrypted location with restricted access. Do not upload or share them.

- [Official website](https://sidekite.zhosix.com/)
- [Privacy policy](https://sidekite.zhosix.com/privacy)
- Support and security: `linkflow@zhosix.com` (retained during the transition)

---

## 简体中文

**SideKite 的桌面配对助手。**

SideKite Pair 支持 macOS 与 Windows，帮助你发现 Apple 设备、生成或导入配对资料，并在电脑与所选设备之间完成验证和传输。

[下载应用](https://github.com/zhosix/sidekitepair/releases) · [校验下载文件](#校验下载文件) · [SideKite iOS 版](https://github.com/zhosix/sidekite)

### 主要功能

- **设备发现** — 查找与 SideKite 配合使用的 Apple 设备。
- **配对资料生成与导入** — 生成配对资料，或导入已有资料。
- **验证与传输** — 验证配对资料，并传输至所选设备。
- **默认本地处理** — 配对资料默认只在本机与所选设备之间处理。

### 下载与安装

> SideKite Pair 原名 LinkFlow Pair。历史 Release、安装包文件名和校验值保持不变。

请从本仓库的 [Releases](https://github.com/zhosix/sidekitepair/releases) 下载，并在安装前核对发布页提供的 SHA-256。

| 平台 | 安装包 | 系统要求 |
| --- | --- | --- |
| macOS | `LinkFlow-Pair-1.0.0-macOS.dmg` | macOS 11 或更高版本；Apple 芯片与 Intel |
| Windows | `LinkFlow-Pair-1.0.0-Windows-x64.exe` | Windows 10/11 x64；需 Microsoft Edge WebView2 Runtime |

**签名说明：** 上述 macOS 安装包未使用 Developer ID 签名或 Apple 公证；Windows 安装包未使用 Authenticode 签名，系统可能显示来源或信誉提示。请只从本仓库下载并先核对 SHA-256，不要关闭 Gatekeeper、SmartScreen、Defender 或其他系统安全功能。

**macOS：** 不需要自行重签。打开 DMG 后将 App 拖入“应用程序”；若系统阻止首次打开，在确认 SHA-256 正确后，可在 Finder 中按住 Control 点击 App 并选择“打开”，或前往“系统设置 → 隐私与安全性”选择“仍要打开”。

### 校验下载文件

macOS：

```bash
shasum -a 256 LinkFlow-Pair-1.0.0-macOS.dmg
```

Windows PowerShell：

```powershell
Get-FileHash .\LinkFlow-Pair-1.0.0-Windows-x64.exe -Algorithm SHA256
```

校验值应与 Release 中 `SHA256SUMS` 文件的对应条目完全一致。

### 隐私与支持

本地备份包含设备配对凭据。请仅保存到私人、加密且受访问控制的位置，不要上传或分享。

- [官方网站](https://sidekite.zhosix.com/)
- [隐私政策](https://sidekite.zhosix.com/privacy)
- 支持与安全问题：`linkflow@zhosix.com`（过渡期间继续保留）
