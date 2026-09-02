# Chaotic Golfer

**Bauen. Schlagen. Eskalieren.**

Dieses Repository enthaelt ausschliesslich die offiziellen Windows-Builds
von Chaotic Golfer. Der Quellcode ist nicht Teil dieses oeffentlichen
Download-Kanals.

## Aktuelle Version: 7.0.1

Release: https://github.com/Feuerbrand/chaotic-golfer-releases/releases/latest

## Installation

1. Oeffne das [neueste Release](https://github.com/Feuerbrand/chaotic-golfer-releases/releases/latest).
2. Lade `ChaoticGolferLauncher.exe` herunter (Lila-Launcher, ~68 MB).
3. Doppelklick auf den Launcher. Er liest `installed-version.txt`, holt
   das passende Spiel-Paket (7.0.1) vom Repo, entpackt es nach
   `%LOCALAPPDATA%\Programs\ChaoticGolfer` und startet das Spiel.

Das Spiel wird pro Benutzer unter `%LOCALAPPDATA%\Programs\ChaoticGolfer`
installiert - ohne Administratorrechte, ohne Registry-Eintrag, ohne
externen Installer. Der Lila-Launcher (Version 2.6.0) prueft beim Start
automatisch auf neue Versionen und validiert deren SHA-256-Pruefsumme.

Updates passieren ohne weiteren Download: einfach den Lila-Launcher
starten, er holt das neue Spiel-Paket automatisch.

> Windows SmartScreen kann bei neuen, noch nicht code-signierten Builds
> eine Warnung anzeigen. Lade den Launcher ausschliesslich von dieser
> Release-Seite.
