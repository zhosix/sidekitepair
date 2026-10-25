# SideKite Pair

[English](#english) · [简体中文](#简体中文)

## English

**Install signed IPAs and set up Remote Pairing for SideKite on macOS and Windows.**

Use SideKite Pair to install an already signed IPA on your iPhone or iPad, including a first-time SideKite installation. You can also create Remote Pairing files, import them directly into SideKite, save them to SideKite Archive, or keep a local backup. The app includes 19 interface languages.

[Download](https://github.com/zhosix/sidekitepair/releases/latest) · [Official website](https://sidekite.zhosix.com) · [SideKite for iOS](https://github.com/zhosix/sidekite)

### What you can do

| Task | What it does |
| --- | --- |
| **Install a signed IPA** | Install an IPA that has already been signed with a certificate or Apple ID. This also supports the first installation of SideKite. |
| **Generate and import** | Create a Remote Pairing file, transfer it to SideKite, and confirm the import. |
| **Save to SideKite Archive** | Keep a new pairing file for later manual import without changing the active pairing. |
| **Save a local backup** | Save a new pairing file on your computer for later use. |

### Requirements

| | Requirements |
| --- | --- |
| **macOS** | macOS 11 or later; Apple silicon and Intel. |
| **Windows** | Windows 10/11 x64, with Apple Devices or the desktop edition of iTunes installed. The EXE is portable. |
| **IPA installation** | iPhone or iPad running iOS/iPadOS 17 or later, with a signed IPA whose provisioning profile authorizes the device. |
| **Remote Pairing** | iOS/iPadOS 17.4 or later. Automatic import and Archive delivery require SideKite to be installed and open. |
| **Connection** | Unlock the device and complete **Trust This Computer** over USB. Wireless use additionally requires Wi-Fi sync and the same local network. |

### Download and installation

On macOS, open the DMG and drag the app into Applications. On Windows, download and run the EXE.

These applications are not Developer ID–signed, Apple-notarized, or Authenticode-signed. No macOS re-signing is needed. If the first launch is blocked, verify the checksum, then use Finder's **Open** or **System Settings → Privacy & Security → Open Anyway**.

The SHA-256 is shown beside each asset on the [download page](https://github.com/zhosix/sidekitepair/releases/latest).

### Install a signed IPA

1. Save an IPA that has already been signed with a certificate or Apple ID to your computer.
2. Connect and unlock the iPhone or iPad, trust the computer, and select the device in Pair.
3. Open **Install a signed IPA**, choose the file, and confirm the app and target device before installation.
4. Keep the device connected while Pair checks the result. Follow any Developer Mode or developer-trust prompts on the device.

SideKite does not need to be installed beforehand. Pair preserves the IPA's existing signature; iOS still checks the signature, provisioning profile, and device authorization.

### Set up Remote Pairing

1. Open SideKite on the device and keep it in the foreground.
2. Connect the trusted, unlocked device and select it in Pair.
3. Open **Remote Pairing**, then choose **Generate and import**. Alternatively, save a new file to SideKite Archive or save a local backup.
4. Wait for Pair to confirm that SideKite imported the file, then check the connection in SideKite.

Automatic import targets `com.zhosix.sidekite`. If signing changes the Bundle ID, use **Save a local backup**, transfer the file to your device, and import it from inside SideKite. Saving to Archive requires a SideKite version that supports this feature.

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

**Support and security:** [sidekite@zhosix.com](mailto:sidekite@zhosix.com)

---

## 简体中文

**SideKite 的桌面安装与远程配对助手，支持 macOS 与 Windows。**

将已签名 IPA 安装到 iPhone 或 iPad，也可用于首次安装 SideKite；生成远程配对文件并直接导入 SideKite，或保存到档案页和本地留作备用。界面支持 19 种语言。

[下载最新版](https://github.com/zhosix/sidekitepair/releases/latest) · [SideKite 官网](https://sidekite.zhosix.com) · [SideKite iOS 版](https://github.com/zhosix/sidekite)

### 主要功能

| 操作 | 用途 |
| --- | --- |
| **安装已签名 IPA** | 安装已使用证书或 Apple ID 签好的 IPA，也支持首次安装 SideKite。 |
| **生成并导入** | 生成远程配对文件，传送到 SideKite 并确认完成导入。 |
| **保存到 SideKite 档案** | 将新配对文件留作之后手动导入，当前启用的配对保持不变。 |
| **保存本地备份** | 将新配对文件保存到电脑，留作备用。 |

### 使用要求

| | 要求 |
| --- | --- |
| **macOS** | macOS 11 或更高版本，支持 Apple 芯片与 Intel。 |
| **Windows** | Windows 10/11 x64，需安装 Apple Devices 或桌面版 iTunes；EXE 为便携版。 |
| **IPA 安装** | iPhone 或 iPad 运行 iOS/iPadOS 17 或更高版本，IPA 已签名且描述文件允许该设备安装。 |
| **远程配对** | iOS/iPadOS 17.4 或更高版本；自动导入及保存到档案需先安装并打开 SideKite。 |
| **设备连接** | 解锁设备，并先通过 USB 完成“信任此电脑”；无线连接还需开启 Wi-Fi 同步，并处于同一局域网。 |

### 下载与安装

macOS 打开 DMG 后将 App 拖入“应用程序”；Windows 下载后直接运行 EXE。

当前版本未使用 Developer ID/Apple 公证或 Authenticode 签名。macOS 不需要自行重签；首次打开若被系统阻止，请在确认校验值后使用 Finder 的“打开”或“系统设置 → 隐私与安全性 → 仍要打开”。

文件的 SHA-256 可在[下载页](https://github.com/zhosix/sidekitepair/releases/latest)对应附件旁查看。

### 安装已签名 IPA

1. 将已使用证书或 Apple ID 签好的 IPA 保存到电脑。
2. 连接并解锁 iPhone 或 iPad，信任电脑，然后在 Pair 中选择目标设备。
3. 打开 **安装已签名 IPA**，选择文件，核对应用与目标设备后确认安装。
4. 保持连接，等待 Pair 核验安装结果，再按设备提示启用开发者模式或信任开发者。

首次安装时，手机上无需已有 SideKite。Pair 保留 IPA 原有签名，iOS 仍会检查签名、描述文件及设备授权。

### 设置远程配对

1. 在设备上打开 SideKite，并保持在前台。
2. 连接已信任且解锁的设备，在 Pair 中选择它。
3. 打开 **远程配对**，选择 **生成并导入**；也可按需要将新文件保存到 SideKite 档案或本地备份。
4. 等待 Pair 确认 SideKite 已完成导入，再检查 App 中的连接状态。

自动导入对应 `com.zhosix.sidekite`。若签名后应用的 Bundle ID 已改变，请选择 **保存本地备份**，将文件传到设备后，在 SideKite 内手动导入。保存到档案需搭配支持该功能的 SideKite 版本。

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

**支持与安全问题：** [sidekite@zhosix.com](mailto:sidekite@zhosix.com)

##
