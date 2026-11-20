<p align="center">
<a href="README.md">English</a> |
<a href="README.ko.md">한국어</a> |
<b>日本語</b> |
<a href="README.zh-CN.md">简体中文</a> |
<a href="README.zh-TW.md">繁體中文</a> |
<a href="README.de.md">Deutsch</a> |
<a href="README.es.md">Español</a> |
<a href="README.fr.md">Français</a> |
<a href="README.pt-BR.md">Português</a>
</p>

<p align="center">
  <img src="images/icon.svg" width="96" alt="Screen Mouse のアイコン">
</p>

<h1 align="center">Screen Mouse</h1>

<p align="center">
  同じネットワーク上の複数のコンピューターを、1 組のキーボードとマウスで使用できます。<br>
  Windows · macOS · Linux
</p>

<p align="center">
  <a href="https://github.com/mid2tonight/ScreenMouse/releases/latest"><img src="https://img.shields.io/github/v/release/mid2tonight/ScreenMouse?label=release&color=C15F3C" alt="最新リリース"></a>
  <a href="https://github.com/mid2tonight/ScreenMouse/releases"><img src="https://img.shields.io/github/downloads/mid2tonight/ScreenMouse/total?color=C15F3C" alt="ダウンロード数"></a>
</p>

<p align="center">
  <a href="https://github.com/mid2tonight/ScreenMouse/releases/latest"><b>ダウンロード</b></a> ·
  <a href="https://mid55.com/">Web サイト</a> ·
  <a href="CHANGELOG.md">更新履歴</a>
</p>

<p align="center">
  <img src="images/main-window.png" width="860" alt="2 台のディスプレイを接続した MacBook Pro と Windows PC がつながっている Screen Mouse のメイン ウィンドウ">
</p>

Screen Mouse は、私が開発・保守している軽量なソフトウェア KVM です。ポインターを画面の端から外へ動かすと、隣のコンピューターでそのまま動き続けます。キーボード入力とクリップボードも一緒に切り替わります。

ボタンを押したり、画面の切り替えを待ったりする必要がないため、ハードウェア KVM 切り替え器より速くコンピューターを切り替えられます。各コンピューターはそれぞれのモニターをそのまま使用し、追加のケーブルや機器は必要ありません。

## しくみ

- 各コンピューターで Screen Mouse を実行します。同じネットワーク上のコンピューターは自動的に検出されます。最初に 4 桁のコードで 1 回接続すると、その後は自動的に再接続されます。
- サーバーとクライアントの区別はありません。接続したすべてのコンピューターが互いに操作できます。
- ポインターが画面の端に達すると、その方向に配置したコンピューターに入力が送られます。配置はモニター配置画面で設定します。

## 機能

- テキストとファイルのクリップボード共有
- 別のコンピューターへのファイルのドラッグ アンド ドロップ
- 実際の机に合わせたモニター配置
- インストール不要の Web ブラウザーからの接続
- PC から Mac を操作するときの Ctrl と Command の自動切り替え
- スリープの防止、接続したすべてのコンピューターの一括終了
- 署名付きの自動更新
- 日本語、英語、韓国語、中国語 (簡体字・繁体字)、ドイツ語、スペイン語、フランス語、ポルトガル語

<p align="center">
  <img src="images/settings.png" width="860" alt="ライセンス、自動更新、自動接続、スリープ防止のオプションを表示した Screen Mouse の設定">
</p>

## ダウンロード

| OS | 要件 | ファイル |
|---|---|---|
| Windows | Windows 10 または 11 (64 ビット) | [ScreenMouse_2.0.1_Setup.exe](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_Setup.exe) |
| macOS | macOS 13 以降、Apple シリコンまたは Intel | [ScreenMouse_2.0.1.dmg](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1.dmg) |
| Linux | x86_64、X11 または Wayland | [ScreenMouse_2.0.1_x86_64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_x86_64.AppImage) |
| Linux (ARM) | aarch64 (Raspberry Pi 4 または 5 など) | [ScreenMouse_2.0.1_aarch64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_aarch64.AppImage) |

以前のバージョンは、[リリース](https://github.com/mid2tonight/ScreenMouse/releases) ページから入手できます。

## はじめに

1. コンピューターを、有線または Wi-Fi で同じルーターに接続します。有線接続が最も高速です。
2. 各コンピューターに Screen Mouse をインストールして実行します。
   - **Windows:** セットアップ ファイルを実行します。管理者権限は必要ありません。
   - **macOS:** DMG ファイルを開き、Screen Mouse を **[アプリケーション]** フォルダーにドラッグします。確認が表示されたら、システム設定で Screen Mouse の **[アクセシビリティ]** をオンにします。
   - **Linux:** AppImage ファイルにプログラムとして実行する許可を与えてから、開きます。Wayland では、GNOME 46 または KDE Plasma 6.1 以降が必要です。
3. 一方のコンピューターで、もう一方のコンピューターに表示されている 4 桁の接続コードを入力し、**[接続]** を選択します。
4. ポインターを画面の端へ動かします。ポインターをいつでもこのコンピューターに戻すには、**Ctrl+F12** キー (変更可能) を押します。

## 無料期間とライセンス

インストール後 1 か月間、Standard のすべての機能 (コンピューター 2 台、モニター最大 3 台) を無料で使用できます。支払い情報は必要ありません。

お得な特典に参加すると、さらに 1 か月間無料で使用できます。

その後は、年間ライセンスを購入できます。どのプランも機能は同じで、異なるのはコンピューターとモニターの台数だけです。

> このリポジトリには、ドキュメントとリリース ファイルのみが含まれています。ソース コードは公開されていません。
