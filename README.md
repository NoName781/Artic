# Artic Emulator

**Artic** ist ein quelloffener Emulator, der für Forschungs- und Entwicklungszwecke erstellt wurde.  
Er basiert auf dem öffentlichen Citra-Code (GPLv2) und zielt darauf ab, die Architektur moderner Handheld-Systeme zu verstehen und zu reproduzieren.

## ⚙️ Features
- High-level-Emulation moderner Handheld-Grafikpipelines  
- Cross-Platform (Windows / Linux / macOS)  
- Modularer Code mit CMake

## 🧩 Lizenz
Dieses Projekt steht unter der **GNU General Public License v2 (GPLv2)**.  
Der vollständige Lizenztext befindet sich in der Datei [`LICENSE`](LICENSE).

## ⚠️ Rechtlicher Hinweis
Artic enthält **keine** urheberrechtlich geschützten Inhalte von Nintendo oder anderen Herstellern.  
Es werden **keine ROMs, BIOS-Dateien oder Schlüsseldateien** bereitgestellt oder verlinkt.  
Die Nutzung von Artic setzt voraus, dass du ausschließlich selbst erstellte oder rechtmäßig erworbene Inhalte nutzt.

## 🛠️ Build
```bash
git clone https://github.com/NoName781/Artic.git
cd Artic
mkdir build && cd build
cmake ..
cmake --build .
