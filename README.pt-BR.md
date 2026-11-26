<p align="center">
<a href="README.md">English</a> |
<a href="README.ko.md">한국어</a> |
<a href="README.ja.md">日本語</a> |
<a href="README.zh-CN.md">简体中文</a> |
<a href="README.zh-TW.md">繁體中文</a> |
<a href="README.de.md">Deutsch</a> |
<a href="README.es.md">Español</a> |
<a href="README.fr.md">Français</a> |
<b>Português</b>
</p>

<p align="center">
  <img src="images/icon.svg" width="96" alt="Ícone do Screen Mouse">
</p>

<h1 align="center">Screen Mouse</h1>

<p align="center">
  Use um único teclado e um único mouse com vários computadores na mesma rede.<br>
  Windows · macOS · Linux
</p>

<p align="center">
  <a href="https://github.com/mid2tonight/ScreenMouse/releases/latest"><img src="https://img.shields.io/github/v/release/mid2tonight/ScreenMouse?label=release&color=C15F3C" alt="Versão mais recente"></a>
  <a href="https://github.com/mid2tonight/ScreenMouse/releases"><img src="https://img.shields.io/github/downloads/mid2tonight/ScreenMouse/total?color=C15F3C" alt="Downloads"></a>
</p>

<p align="center">
  <img src="images/main-window.png" width="860" alt="Janela principal do Screen Mouse mostrando um MacBook Pro com dois monitores conectado a um PC com Windows">
</p>

O Screen Mouse é um KVM de software leve que eu mesmo desenvolvo e mantenho. Ao mover o ponteiro além da borda da tela, ele continua no próximo computador. A entrada do teclado e a área de transferência acompanham o ponteiro.

Não é preciso pressionar nenhum botão nem esperar a tela trocar, por isso alternar entre computadores é mais rápido do que com um comutador KVM de hardware. Cada computador continua com o próprio monitor, sem cabos ou dispositivos adicionais.

## Como funciona

- O Screen Mouse é executado em cada computador. Os computadores da mesma rede se encontram automaticamente. Depois de conectá-los uma vez com um código de 4 dígitos, eles se reconectam automaticamente.
- Não há servidor nem cliente. Qualquer computador conectado pode controlar os outros.
- Quando o ponteiro chega à borda da tela, a entrada vai para o computador daquele lado. As posições são definidas na tela de layout dos monitores.

## Recursos

- Área de transferência compartilhada para textos e arquivos
- Arrastar e soltar arquivos em outro computador
- Layout dos monitores igual ao da sua mesa
- Conexão por um navegador da web, sem instalação
- Ctrl e Command são trocados automaticamente ao controlar um Mac a partir de um PC
- Impedir suspensão e encerrar todos os computadores conectados de uma vez
- Atualizações automáticas assinadas
- Português, inglês, coreano, japonês, chinês (simplificado e tradicional), alemão, espanhol e francês

<p align="center">
  <img src="images/settings.png" width="860" alt="Configurações do Screen Mouse com as opções de licença, atualização automática, conexão automática e Impedir suspensão">
</p>

## Download

| SO | Requisitos | Arquivo |
|---|---|---|
| Windows | Windows 10 ou 11, 64 bits | [ScreenMouse_2.1.0_Setup.exe](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.1.0/ScreenMouse_2.1.0_Setup.exe) |
| macOS | macOS 13 ou posterior, Apple silicon ou Intel | [ScreenMouse_2.1.0.dmg](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.1.0/ScreenMouse_2.1.0.dmg) |
| Linux | x86_64, X11 ou Wayland | [ScreenMouse_2.1.0_x86_64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.1.0/ScreenMouse_2.1.0_x86_64.AppImage) |
| Linux (ARM) | aarch64, como Raspberry Pi 4 ou 5 | [ScreenMouse_2.1.0_aarch64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.1.0/ScreenMouse_2.1.0_aarch64.AppImage) |

As versões anteriores estão disponíveis na página [Versões](https://github.com/mid2tonight/ScreenMouse/releases).

## Introdução

1. Conecte os computadores ao mesmo roteador, por cabo ou Wi-Fi. A conexão com fio é a mais rápida.
2. Instale e execute o Screen Mouse em cada computador.
   - **Windows:** Execute o arquivo de instalação. Não são necessários direitos de administrador.
   - **macOS:** Abra o arquivo DMG e arraste o Screen Mouse para a pasta **Aplicativos**. Quando solicitado, ative **Acessibilidade** para o Screen Mouse em Ajustes do Sistema.
   - **Linux:** Permita que o arquivo AppImage seja executado como programa e, em seguida, abra-o. No Wayland, é necessário GNOME 46 ou KDE Plasma 6.1 ou posterior.
3. Em um computador, insira o código de conexão de 4 dígitos exibido no outro computador e, em seguida, selecione **Conectar**.
4. Mova o ponteiro até a borda da tela. Para trazer o ponteiro de volta a este computador a qualquer momento, pressione **Ctrl+F12** (é possível alterar essa tecla).

## Período gratuito e licença

O Screen Mouse é gratuito por 1 mês após a instalação, com todos os recursos do Standard (2 computadores, até 3 monitores). Não é necessário informar dados de pagamento.

Ao participar da promoção, você ganha mais 1 mês grátis.

Depois disso, você pode comprar uma licença anual. Todos os planos têm os mesmos recursos. Só muda o número de computadores e monitores.

> Este repositório contém apenas a documentação e os arquivos de versão. O código-fonte não é público.
