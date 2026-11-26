<p align="center">
<a href="README.md">English</a> |
<a href="README.ko.md">한국어</a> |
<a href="README.ja.md">日本語</a> |
<a href="README.zh-CN.md">简体中文</a> |
<a href="README.zh-TW.md">繁體中文</a> |
<a href="README.de.md">Deutsch</a> |
<a href="README.es.md">Español</a> |
<b>Français</b> |
<a href="README.pt-BR.md">Português</a>
</p>

<p align="center">
  <img src="images/icon.svg" width="96" alt="Icône de Screen Mouse">
</p>

<h1 align="center">Screen Mouse</h1>

<p align="center">
  Utilisez un seul clavier et une seule souris avec plusieurs ordinateurs du même réseau.<br>
  Windows · macOS · Linux
</p>

<p align="center">
  <a href="https://github.com/mid2tonight/ScreenMouse/releases/latest"><img src="https://img.shields.io/github/v/release/mid2tonight/ScreenMouse?label=release&color=C15F3C" alt="Dernière version"></a>
  <a href="https://github.com/mid2tonight/ScreenMouse/releases"><img src="https://img.shields.io/github/downloads/mid2tonight/ScreenMouse/total?color=C15F3C" alt="Téléchargements"></a>
</p>

<p align="center">
  <img src="images/main-window.png" width="860" alt="Fenêtre principale de Screen Mouse montrant un MacBook Pro avec deux écrans connecté à un PC Windows">
</p>

Screen Mouse est un KVM logiciel léger que je développe et maintiens moi-même. Lorsque vous déplacez le pointeur au-delà du bord de l’écran, il continue sur l’ordinateur suivant. La saisie au clavier et le presse-papiers suivent.

Il n’y a aucun bouton à appuyer ni aucune attente pendant que l’écran bascule : passer d’un ordinateur à l’autre est plus rapide qu’avec un commutateur KVM matériel. Chaque ordinateur garde son propre moniteur, sans câble ni périphérique supplémentaire.

## Fonctionnement

- Screen Mouse s’exécute sur chaque ordinateur. Les ordinateurs d’un même réseau se détectent mutuellement. Après une première connexion avec un code à 4 chiffres, ils se reconnectent automatiquement.
- Il n’y a ni serveur ni client. Chaque ordinateur connecté peut contrôler les autres.
- Lorsque le pointeur atteint un bord de l’écran, la saisie est envoyée à l’ordinateur situé de ce côté. Les positions se définissent dans l’écran de disposition des moniteurs.

## Fonctionnalités

- Presse-papiers partagé pour le texte et les fichiers
- Glisser-déplacer de fichiers vers un autre ordinateur
- Disposition des moniteurs identique à celle de votre bureau
- Connexion depuis un navigateur web sans installation
- Inversion automatique de Ctrl et Commande lorsque vous contrôlez un Mac depuis un PC
- Empêcher la veille et quitter tous les ordinateurs connectés en même temps
- Mises à jour automatiques signées
- Français, anglais, coréen, japonais, chinois (simplifié et traditionnel), allemand, espagnol et portugais

<p align="center">
  <img src="images/settings.png" width="860" alt="Réglages de Screen Mouse avec les options de licence, de mise à jour automatique, de connexion automatique et Empêcher la veille">
</p>

## Téléchargement

| Système d’exploitation | Configuration requise | Fichier |
|---|---|---|
| Windows | Windows 10 ou 11, 64 bits | [ScreenMouse_2.1.0_Setup.exe](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.1.0/ScreenMouse_2.1.0_Setup.exe) |
| macOS | macOS 13 ou version ultérieure, Apple silicon ou Intel | [ScreenMouse_2.1.0.dmg](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.1.0/ScreenMouse_2.1.0.dmg) |
| Linux | x86_64, X11 ou Wayland | [ScreenMouse_2.1.0_x86_64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.1.0/ScreenMouse_2.1.0_x86_64.AppImage) |
| Linux (ARM) | aarch64, par exemple Raspberry Pi 4 ou 5 | [ScreenMouse_2.1.0_aarch64.AppImage](https://github.com/mid2tonight/ScreenMouse/releases/download/v2.1.0/ScreenMouse_2.1.0_aarch64.AppImage) |

Les versions précédentes sont disponibles sur la page [Versions](https://github.com/mid2tonight/ScreenMouse/releases).

## Prise en main

1. Connectez vos ordinateurs au même routeur, par câble ou par Wi-Fi. Une connexion filaire est la plus rapide.
2. Installez et exécutez Screen Mouse sur chaque ordinateur.
   - **Windows :** exécutez le fichier d’installation. Les droits d’administrateur ne sont pas nécessaires.
   - **macOS :** ouvrez le fichier DMG et faites glisser Screen Mouse vers le dossier **Applications**. Lorsque vous y êtes invité, activez **Accessibilité** pour Screen Mouse dans Réglages Système.
   - **Linux :** autorisez l’exécution du fichier AppImage en tant que programme, puis ouvrez-le. Sur Wayland, GNOME 46 ou KDE Plasma 6.1 ou version ultérieure est requis.
3. Sur un ordinateur, entrez le code de connexion à 4 chiffres affiché sur l’autre ordinateur, puis sélectionnez **Connexion**.
4. Déplacez le pointeur vers le bord de l’écran. Pour ramener le pointeur sur cet ordinateur à tout moment, appuyez sur **Ctrl+F12** (touche modifiable).

## Période gratuite et licence

Screen Mouse est gratuit pendant 1 mois après l’installation, avec toutes les fonctionnalités Standard (2 ordinateurs, jusqu’à 3 moniteurs). Aucune information de paiement n’est requise.

En participant à la promotion, vous obtenez 1 mois gratuit supplémentaire.

Ensuite, vous pouvez acheter une licence annuelle. Toutes les offres ont les mêmes fonctionnalités. Seul le nombre d’ordinateurs et de moniteurs change.

> Ce dépôt contient uniquement la documentation et les fichiers de version. Le code source n’est pas public.
