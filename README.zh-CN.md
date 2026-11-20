<p align="center">
<a href="README.md">English</a> |
<a href="README.ko.md">한국어</a> |
<a href="README.ja.md">日本語</a> |
<b>简体中文</b> |
<a href="README.zh-TW.md">繁體中文</a> |
<a href="README.de.md">Deutsch</a> |
<a href="README.es.md">Español</a> |
<a href="README.fr.md">Français</a> |
<a href="README.pt-BR.md">Português</a>
</p>

<p align="center">
  <img src="images/icon.svg" width="96" alt="Screen Mouse 图标">
</p>

<h1 align="center">Screen Mouse</h1>

<p align="center">
  用一套键盘和鼠标使用同一网络中的多台电脑。<br>
  Windows · macOS · Linux
</p>

<p align="center">
  <a href="https://github.com/mid2tonight/ScreenMouse/releases/latest"><img src="https://img.shields.io/github/v/release/mid2tonight/ScreenMouse?label=release&color=C15F3C" alt="最新版本"></a>
  <a href="https://github.com/mid2tonight/ScreenMouse/releases"><img src="https://img.shields.io/github/downloads/mid2tonight/ScreenMouse/total?color=C15F3C" alt="下载次数"></a>
</p>

<p align="center">
  <a href="https://github.com/mid2tonight/ScreenMouse/releases/latest"><b>下载</b></a> ·
  <a href="https://mid55.com/">网站</a> ·
  <a href="CHANGELOG.md">更新日志</a>
</p>

<p align="center">
  <img src="images/main-window.png" width="860" alt="Screen Mouse 主窗口，显示一台带有两台显示器的 MacBook Pro 已连接到一台 Windows PC">
</p>

Screen Mouse 是我自己开发和维护的轻量级软件 KVM。将指针移过屏幕边缘，它会在相邻的电脑上继续移动。键盘输入和剪贴板也会一起切换。

无需按下按钮，也无需等待显示器切换，因此切换电脑比硬件 KVM 切换器更快。每台电脑都继续使用自己的显示器，无需额外的线缆或设备。

## 工作原理

- 在每台电脑上运行 Screen Mouse。同一网络中的电脑会自动发现彼此。首次使用 4 位数代码连接一次后，之后会自动重新连接。
- 没有服务器和客户端之分。所有已连接的电脑都可以互相控制。
- 指针到达屏幕边缘时，输入会发送到该方向上的电脑。位置在显示器布局界面中设置。

## 功能

- 文本和文件的剪贴板共享
- 将文件拖放到另一台电脑
- 按实际桌面摆放的显示器布局
- 无需安装，通过网页浏览器连接
- 从 PC 控制 Mac 时自动交换 Ctrl 和 Command
- 防止睡眠，一次退出所有已连接的电脑
- 带签名的自动更新
- 简体中文、繁体中文、英语、韩语、日语、德语、西班牙语、法语、葡萄牙语

<p align="center">
  <img src="images/settings.png" width="860" alt="Screen Mouse 设置，显示许可证、自动更新、自动连接和防止睡眠选项">
</p>

## 下载

| 操作系统 | 要求 | 文件 |
|---|---|---|
| Windows | Windows 10 或 11，64 位 | [ScreenMouse_2.0.1_Setup.exe](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_Setup.exe) |
| macOS | macOS 13 或更高版本，Apple 芯片或 Intel | [ScreenMouse_2.0.1.dmg](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1.dmg) |
| Linux | x86_64，X11 或 Wayland | [ScreenMouse_2.0.1_x86_64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_x86_64.AppImage) |
| Linux (ARM) | aarch64，例如 Raspberry Pi 4 或 5 | [ScreenMouse_2.0.1_aarch64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_aarch64.AppImage) |

可在[发行版](https://github.com/mid2tonight/ScreenMouse/releases)页面获取以前的版本。

## 入门

1. 通过网线或 Wi-Fi 将电脑连接到同一台路由器。有线连接速度最快。
2. 在每台电脑上安装并运行 Screen Mouse。
   - **Windows:** 运行安装文件。无需管理员权限。
   - **macOS:** 打开 DMG 文件，将 Screen Mouse 拖到**应用程序**文件夹。出现提示时，在“系统设置”中为 Screen Mouse 打开**辅助功能**。
   - **Linux:** 允许 AppImage 文件作为程序运行，然后打开它。在 Wayland 上，需要 GNOME 46 或 KDE Plasma 6.1 或更高版本。
3. 在一台电脑上，输入另一台电脑上显示的 4 位数字连接代码，然后选择**连接**。
4. 将指针移到屏幕边缘。若要随时将指针移回这台电脑，请按 **Ctrl+F12**（可更改此按键）。

## 免费期和许可证

安装后可免费使用 1 个月，包含所有 Standard 功能（2 台电脑，最多 3 台显示器）。无需提供付款信息。

参与促销活动可再免费使用 1 个月。

之后可以购买年度许可证。所有方案的功能相同，只是可连接的电脑和显示器数量不同。

> 此存储库仅包含文档和发行文件。源代码不公开。
