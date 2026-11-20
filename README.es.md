<p align="center">
<a href="README.md">English</a> |
<a href="README.ko.md">한국어</a> |
<a href="README.ja.md">日本語</a> |
<a href="README.zh-CN.md">简体中文</a> |
<a href="README.zh-TW.md">繁體中文</a> |
<a href="README.de.md">Deutsch</a> |
<b>Español</b> |
<a href="README.fr.md">Français</a> |
<a href="README.pt-BR.md">Português</a>
</p>

<p align="center">
  <img src="images/icon.svg" width="96" alt="Icono de Screen Mouse">
</p>

<h1 align="center">Screen Mouse</h1>

<p align="center">
  Use un solo teclado y un solo ratón con varios equipos de la misma red.<br>
  Windows · macOS · Linux
</p>

<p align="center">
  <a href="https://github.com/mid2tonight/ScreenMouse/releases/latest"><img src="https://img.shields.io/github/v/release/mid2tonight/ScreenMouse?label=release&color=C15F3C" alt="Última versión"></a>
  <a href="https://github.com/mid2tonight/ScreenMouse/releases"><img src="https://img.shields.io/github/downloads/mid2tonight/ScreenMouse/total?color=C15F3C" alt="Descargas"></a>
</p>

<p align="center">
  <img src="images/main-window.png" width="860" alt="Ventana principal de Screen Mouse que muestra un MacBook Pro con dos pantallas conectado a un equipo con Windows">
</p>

Screen Mouse es un KVM de software ligero que desarrollo y mantengo yo mismo. Al mover el puntero más allá del borde de la pantalla, continúa en el equipo siguiente. La entrada del teclado y el portapapeles cambian con él.

No hay que presionar ningún botón ni esperar a que cambie la pantalla, por lo que cambiar de equipo es más rápido que con un conmutador KVM de hardware. Cada equipo conserva su propio monitor y no se necesitan cables ni dispositivos adicionales.

## Cómo funciona

- Screen Mouse se ejecuta en cada equipo. Los equipos de la misma red se detectan entre sí. Después de conectarlos una vez con un código de 4 dígitos, se vuelven a conectar automáticamente.
- No hay servidor ni cliente. Cualquier equipo conectado puede controlar a los demás.
- Cuando el puntero llega a un borde de la pantalla, la entrada se envía al equipo de ese lado. Las posiciones se establecen en la pantalla de distribución de monitores.

## Características

- Portapapeles compartido para texto y archivos
- Arrastrar y colocar archivos en otro equipo
- Distribución de monitores igual a la de su escritorio
- Conexión desde un explorador web sin instalar nada
- Ctrl y Comando se intercambian automáticamente al controlar un Mac desde un PC
- Evitar la suspensión y salir de todos los equipos conectados a la vez
- Actualizaciones automáticas firmadas
- Español, inglés, coreano, japonés, chino (simplificado y tradicional), alemán, francés y portugués

<p align="center">
  <img src="images/settings.png" width="860" alt="Ajustes de Screen Mouse con las opciones de licencia, actualización automática, conexión automática y evitar la suspensión">
</p>

## Descarga

| SO | Requisitos | Archivo |
|---|---|---|
| Windows | Windows 10 u 11, de 64 bits | [ScreenMouse_2.0.1_Setup.exe](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_Setup.exe) |
| macOS | macOS 13 o posterior, Apple silicon o Intel | [ScreenMouse_2.0.1.dmg](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1.dmg) |
| Linux | x86_64, X11 o Wayland | [ScreenMouse_2.0.1_x86_64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_x86_64.AppImage) |
| Linux (ARM) | aarch64, como Raspberry Pi 4 o 5 | [ScreenMouse_2.0.1_aarch64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.0.1/ScreenMouse_2.0.1_aarch64.AppImage) |

Las versiones anteriores están disponibles en la página [Versiones](https://github.com/mid2tonight/ScreenMouse/releases).

## Introducción

1. Conecte los equipos al mismo enrutador, por cable o por Wi-Fi. La conexión por cable es la más rápida.
2. Instale y ejecute Screen Mouse en cada equipo.
   - **Windows:** ejecute el archivo de instalación. No se requieren derechos de administrador.
   - **macOS:** abra el archivo DMG y arrastre Screen Mouse a la carpeta **Aplicaciones**. Cuando se le solicite, active **Accesibilidad** para Screen Mouse en Ajustes del Sistema.
   - **Linux:** permita que el archivo AppImage se ejecute como programa y, a continuación, ábralo. En Wayland, se requiere GNOME 46 o KDE Plasma 6.1 o posterior.
3. En un equipo, escriba el código de conexión de 4 dígitos que se muestra en el otro equipo y, a continuación, seleccione **Conectar**.
4. Mueva el puntero hasta el borde de la pantalla. Para devolver el puntero a este equipo en cualquier momento, pulse **Ctrl+F12** (esta tecla se puede cambiar).

## Periodo gratuito y licencia

Screen Mouse es gratuito durante 1 mes después de instalarlo, con todas las características de Standard (2 equipos, hasta 3 monitores). No se requiere información de pago.

Si participa en la promoción, obtiene 1 mes gratis más.

Después, puede comprar una licencia anual. Todos los planes tienen las mismas características. Solo cambia el número de equipos y monitores.

> Este repositorio contiene únicamente documentación y archivos de versión. El código fuente no es público.
