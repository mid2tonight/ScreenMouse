<p align="center">
<a href="README.md">English</a> |
<b>한국어</b> |
<a href="README.ja.md">日本語</a> |
<a href="README.zh-CN.md">简体中文</a> |
<a href="README.zh-TW.md">繁體中文</a> |
<a href="README.de.md">Deutsch</a> |
<a href="README.es.md">Español</a> |
<a href="README.fr.md">Français</a> |
<a href="README.pt-BR.md">Português</a>
</p>

<p align="center">
  <img src="images/icon.svg" width="96" alt="Screen Mouse 아이콘">
</p>

<h1 align="center">Screen Mouse</h1>

<p align="center">
  같은 네트워크에 있는 여러 컴퓨터를 키보드와 마우스 하나로 사용합니다.<br>
  Windows · macOS · Linux
</p>

<p align="center">
  <a href="https://github.com/mid2tonight/ScreenMouse/releases/latest"><img src="https://img.shields.io/github/v/release/mid2tonight/ScreenMouse?label=release&color=C15F3C" alt="최신 버전"></a>
  <a href="https://github.com/mid2tonight/ScreenMouse/releases"><img src="https://img.shields.io/github/downloads/mid2tonight/ScreenMouse/total?color=C15F3C" alt="다운로드 수"></a>
</p>

<p align="center">
  <img src="images/main-window.png" width="860" alt="Screen Mouse 기본 화면: 모니터 2대를 사용하는 MacBook Pro와 Windows PC가 연결된 모습">
</p>

Screen Mouse는 직접 개발하고 관리하는 가벼운 소프트웨어 KVM입니다. 포인터를 화면 가장자리 너머로 이동하면 옆 컴퓨터에서 이어서 움직입니다. 키보드 입력과 클립보드도 함께 전환됩니다.

버튼을 누르거나 화면이 바뀌기를 기다릴 필요가 없으므로 하드웨어 KVM 스위치보다 빠르게 컴퓨터를 전환할 수 있습니다. 각 컴퓨터는 자기 모니터를 그대로 사용하며 추가 케이블이나 장치가 필요하지 않습니다.

## 동작 방식

- 각 컴퓨터에서 Screen Mouse를 실행합니다. 같은 네트워크의 컴퓨터를 자동으로 찾으며, 처음 한 번만 4자리 코드로 연결하면 이후에는 자동으로 다시 연결됩니다.
- 서버와 클라이언트를 구분하지 않습니다. 연결된 모든 컴퓨터가 서로를 제어할 수 있습니다.
- 포인터가 화면 가장자리에 닿으면 그쪽에 배치한 컴퓨터로 입력이 전달됩니다. 위치는 모니터 배치 화면에서 지정합니다.

## 기능

- 텍스트와 파일의 클립보드 공유
- 다른 컴퓨터로 파일 끌어서 놓기
- 실제 책상 배치에 맞춘 모니터 배치
- 설치하지 않고 웹 브라우저로 연결
- PC에서 Mac을 제어할 때 Ctrl과 Command 자동 전환
- 절전 모드 방지, 연결된 모든 컴퓨터 함께 종료
- 서명된 자동 업데이트
- 한국어, 영어, 일본어, 중국어(간체·번체), 독일어, 스페인어, 프랑스어, 포르투갈어

<p align="center">
  <img src="images/settings.png" width="860" alt="Screen Mouse 설정 화면: 라이선스, 자동 업데이트, 자동 연결, 절전 모드 방지">
</p>

## 다운로드

| 운영 체제 | 요구 사항 | 파일 |
|---|---|---|
| Windows | Windows 10 또는 11, 64비트 | [ScreenMouse_2.0.1_Setup.exe](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_Setup.exe) |
| macOS | macOS 13 이상, Apple 실리콘 또는 Intel | [ScreenMouse_2.0.1.dmg](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1.dmg) |
| Linux | x86_64, X11 또는 Wayland | [ScreenMouse_2.0.1_x86_64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_x86_64.AppImage) |
| Linux(ARM) | aarch64(Raspberry Pi 4, 5 등) | [ScreenMouse_2.0.1_aarch64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_aarch64.AppImage) |

이전 버전은 [Releases](https://github.com/mid2tonight/ScreenMouse/releases) 페이지에서 다운로드할 수 있습니다.

## 시작하기

1. 컴퓨터를 같은 공유기에 유선 또는 Wi-Fi로 연결합니다. 유선 연결이 가장 빠릅니다.
2. 각 컴퓨터에 Screen Mouse를 설치하고 실행합니다.
   - **Windows:** 설치 파일을 실행합니다. 관리자 권한은 필요하지 않습니다.
   - **macOS:** DMG 파일을 열고 Screen Mouse를 **응용 프로그램** 폴더로 끌어 옮깁니다. 안내가 표시되면 시스템 설정에서 Screen Mouse의 **손쉬운 사용** 권한을 켭니다.
   - **Linux:** AppImage 파일에 실행 권한을 부여한 후 실행합니다. Wayland에서는 GNOME 46 또는 KDE Plasma 6.1 이상이 필요합니다.
3. 한 컴퓨터에서 다른 컴퓨터에 표시된 4자리 연결 코드를 입력하고 **연결**을 선택합니다.
4. 포인터를 화면 가장자리로 이동합니다. 언제든지 **Ctrl+F12**(키 변경 가능)를 누르면 포인터가 이 컴퓨터로 돌아옵니다.

## 무료 사용 기간과 라이선스

설치 후 1개월 동안 Standard 기능 전체(컴퓨터 2대, 모니터 최대 3대)를 무료로 사용할 수 있습니다. 결제 정보는 필요하지 않습니다.

프로모션에 참여하면 1개월을 추가로 무료로 사용할 수 있습니다.

그 이후에는 연간 라이선스를 구입할 수 있습니다. 모든 요금제의 기능은 같으며 연결할 수 있는 컴퓨터와 모니터 수만 다릅니다.

> 이 저장소에는 설명서와 배포 파일만 있습니다. 소스 코드는 공개하지 않습니다.
