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

### Community

- **Telegram:** [@sidekitezhosix](https://t.me/sidekitezhosix)
- **QQ group:** [1045595997](https://qun.qq.com/universal-share/share?ac=1&authKey=68WjRxihKNF6h0Tiy3YRf38laumuG2iWqSZrljs%2FDKwlbXh3VdjMIr8sh6Q265Cx&busi_data=eyJncm91cENvZGUiOiIxMDQ1NTk1OTk3IiwidG9rZW4iOiIzR09ZT2t5OUNha2NUN1J3OUNTalBxaUJ2ZU13NW9QakNidDJRRWdRZnp5VmxidzBuWGNxRUpIUFN6QUR2MVVtIiwidWluIjoiOTE3NjM5OTUwIn0%3D&data=OaVYdY30H8XnRS8e4AAQ-WCIXe6GHpc23EtL1risW5EbjS003_o-Qvx90Ldgqm9eRgi1DVQ247bltYfuoLXR1A&svctype=4&tempid=h5_group_info)

### Support the author

Donations are entirely voluntary. Thank you for supporting SideKite Pair's continued maintenance.

- **PayPal:** [Support via Ko-fi](https://ko-fi.com/zhosix)
- **WeChat:** [View the appreciation code](https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e)
- **Alipay:** [Open the payment link](https://qr.alipay.com/2m6148879y1ivwkicusrh9e) · [View the QR code](https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162)

<details open>
<summary>WeChat and Alipay QR codes</summary>

Click a code to view it at full size, then scan or save it using the corresponding app.

| WeChat | Alipay |
| :---: | :---: |
| [<img src="https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e" width="200" alt="WeChat appreciation code">](https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e) | [<img src="https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162" width="200" alt="Alipay donation code">](https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162) |

</details>

### Privacy and support

Local backups contain device pairing credentials. Keep them in a private, encrypted location with restricted access. Do not upload or share them.

- [Official website](https://sidekite.zhosix.com/)
- [Privacy policy](https://sidekite.zhosix.com/privacy)
- Support and security: `sidekite@zhosix.com`

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

### 社群

- **Telegram 交流群：** [@sidekitezhosix](https://t.me/sidekitezhosix)
- **QQ 交流群：** [1045595997](https://qun.qq.com/universal-share/share?ac=1&authKey=68WjRxihKNF6h0Tiy3YRf38laumuG2iWqSZrljs%2FDKwlbXh3VdjMIr8sh6Q265Cx&busi_data=eyJncm91cENvZGUiOiIxMDQ1NTk1OTk3IiwidG9rZW4iOiIzR09ZT2t5OUNha2NUN1J3OUNTalBxaUJ2ZU13NW9QakNidDJRRWdRZnp5VmxidzBuWGNxRUpIUFN6QUR2MVVtIiwidWluIjoiOTE3NjM5OTUwIn0%3D&data=OaVYdY30H8XnRS8e4AAQ-WCIXe6GHpc23EtL1risW5EbjS003_o-Qvx90Ldgqm9eRgi1DVQ247bltYfuoLXR1A&svctype=4&tempid=h5_group_info)

### 赞助

赞助完全自愿，感谢你支持 SideKite Pair 的持续维护。

- **PayPal：** [通过 Ko-fi 赞助](https://ko-fi.com/zhosix)
- **微信：** [查看微信赞赏码](https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e)
- **支付宝：** [打开赞助链接](https://qr.alipay.com/2m6148879y1ivwkicusrh9e) · [查看二维码](https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162)

<details open>
<summary>微信与支付宝赞助码</summary>

点击二维码可查看原图，再使用对应 App 扫描或保存识别。

| 微信 | 支付宝 |
| :---: | :---: |
| [<img src="https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e" width="200" alt="微信赞赏码">](https://github.com/user-attachments/assets/360e001b-ceef-4ace-9385-4e15fecfba2e) | [<img src="https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162" width="200" alt="支付宝赞助码">](https://github.com/user-attachments/assets/bbb4ecd3-6800-4825-a1c5-d4819e9a4162) |

</details>

### 隐私与支持

本地备份包含设备配对凭据。请仅保存到私人、加密且受访问控制的位置，不要上传或分享。

- [官方网站](https://sidekite.zhosix.com/)
- [隐私政策](https://sidekite.zhosix.com/privacy)
- 支持与安全问题：`sidekite@zhosix.com`
