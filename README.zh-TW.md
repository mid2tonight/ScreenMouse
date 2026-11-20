<p align="center">
<a href="README.md">English</a> |
<a href="README.ko.md">한국어</a> |
<a href="README.ja.md">日本語</a> |
<a href="README.zh-CN.md">简体中文</a> |
<b>繁體中文</b> |
<a href="README.de.md">Deutsch</a> |
<a href="README.es.md">Español</a> |
<a href="README.fr.md">Français</a> |
<a href="README.pt-BR.md">Português</a>
</p>

<p align="center">
  <img src="images/icon.svg" width="96" alt="Screen Mouse 圖示">
</p>

<h1 align="center">Screen Mouse</h1>

<p align="center">
  用一組鍵盤和滑鼠使用同一網路中的多部電腦。<br>
  Windows · macOS · Linux
</p>

<p align="center">
  <a href="https://github.com/mid2tonight/ScreenMouse/releases/latest"><img src="https://img.shields.io/github/v/release/mid2tonight/ScreenMouse?label=release&color=C15F3C" alt="最新版本"></a>
  <a href="https://github.com/mid2tonight/ScreenMouse/releases"><img src="https://img.shields.io/github/downloads/mid2tonight/ScreenMouse/total?color=C15F3C" alt="下載次數"></a>
</p>

<p align="center">
  <img src="images/main-window.png" width="860" alt="Screen Mouse 主視窗，顯示一部配有兩台顯示器的 MacBook Pro 已連線到一部 Windows PC">
</p>

Screen Mouse 是我自己開發和維護的輕量軟體 KVM。將游標移過螢幕邊緣，它就會在相鄰的電腦上繼續移動。鍵盤輸入和剪貼簿也會一起切換。

不需要按下按鈕，也不需要等待顯示器切換，因此切換電腦比硬體 KVM 切換器更快。每部電腦都繼續使用自己的顯示器，不需要額外的纜線或裝置。

## 運作方式

- 在每部電腦上執行 Screen Mouse。同一網路中的電腦會自動找到彼此。第一次使用 4 位數代碼連線後，之後會自動重新連線。
- 沒有伺服器和用戶端之分。所有已連線的電腦都可以互相控制。
- 游標到達螢幕邊緣時，輸入會傳送到該方向的電腦。位置在顯示器配置畫面中設定。

## 功能

- 文字和檔案的剪貼簿共用
- 將檔案拖放到另一部電腦
- 依照實際桌面擺放的顯示器配置
- 不需安裝，透過網頁瀏覽器連線
- 從 PC 控制 Mac 時自動交換 Ctrl 和 Command
- 防止睡眠，一次結束所有已連線的電腦
- 經過簽署的自動更新
- 繁體中文、簡體中文、英文、韓文、日文、德文、西班牙文、法文、葡萄牙文

<p align="center">
  <img src="images/settings.png" width="860" alt="Screen Mouse 設定，顯示授權、自動更新、自動連線和防止睡眠選項">
</p>

## 下載

| 作業系統 | 需求 | 檔案 |
|---|---|---|
| Windows | Windows 10 或 11，64 位元 | [ScreenMouse_2.0.1_Setup.exe](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_Setup.exe) |
| macOS | macOS 13 或更新版本，Apple 晶片或 Intel | [ScreenMouse_2.0.1.dmg](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1.dmg) |
| Linux | x86_64，X11 或 Wayland | [ScreenMouse_2.0.1_x86_64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_x86_64.AppImage) |
| Linux (ARM) | aarch64，例如 Raspberry Pi 4 或 5 | [ScreenMouse_2.0.1_aarch64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_aarch64.AppImage) |

您可以在[發行版本](https://github.com/mid2tonight/ScreenMouse/releases)頁面取得舊版。

## 開始使用

1. 以網路線或 Wi-Fi 將電腦連線到同一部路由器。有線連線速度最快。
2. 在每部電腦上安裝並執行 Screen Mouse。
   - **Windows:** 執行安裝檔。不需要系統管理員權限。
   - **macOS:** 開啟 DMG 檔案，將 Screen Mouse 拖曳到 **應用程式**資料夾。出現提示時，在「系統設定」中為 Screen Mouse 開啟**輔助使用**。
   - **Linux:** 允許 AppImage 檔案以程式方式執行，然後開啟該檔案。在 Wayland 上，需要 GNOME 46 或 KDE Plasma 6.1 或更新版本。
3. 在一部電腦上，輸入另一部電腦上顯示的 4 位數連線代碼，然後選取**連線**。
4. 將游標移到螢幕邊緣。若要隨時將游標移回這部電腦，請按 **Ctrl+F12**（可變更此按鍵）。

## 免費期間與授權

安裝後可免費使用 1 個月，包含所有 Standard 功能（2 部電腦，最多 3 台顯示器）。不需要提供付款資訊。

參加優惠活動即可再免費使用 1 個月。

之後可以購買年度授權。所有方案的功能都相同，只有可連線的電腦和顯示器數量不同。

> 此存放庫僅包含文件和版本檔案。原始程式碼不公開。
