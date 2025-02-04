<!-- 
    title: RTX Upscaler - KI-gestützte Videoverbesserung mit NVIDIA RTX-Technologie
    description: Transformieren Sie qualitativ minderwertige und alte Videos mit dem NVIDIA Maxine SDK. Bietet KI-gestützte Superauflösung und Artefaktreduzierung mit RTX-Echtzeitbeschleunigung. Benutzerfreundliche Gradio-Oberfläche für nahtlose Videoverbesserung.
    keywords: Video-Upscaling, NVIDIA RTX, KI-Videoverbesserung, Superauflösung, Artefaktreduzierung, Vintage-Videorestaurierung, Maxine SDK, Gradio GUI, Videoverarbeitung
    author: ABUS
    version: 1.0.0
    last-updated: 2025-2-3
    product-type: Videoverbessungssoftware
    platforms: Windows
    technology-stack: NVIDIA RTX, Maxine SDK, Super Resolution, Artifact Reduction, Gradio, CUDA, ffmpeg
    license: Kommerziell
-->

# RTX Upscaler: KI-gestützte Videooptimierung mit NVIDIA RTX-Technologie 📺

🌍 [English](../README.md) ∙ [한국어](README.kor.md) ∙ [日本語](README.jpn.md) ∙ [中文简体](README.zh.md) ∙ [中文繁體](README.tw.md) ∙ [Deutsch](README.de.md) ∙ [Español](README.es.md)

Verwandeln Sie qualitativ minderwertige Videos in kristallklare Meisterwerke mit NVIDIA RTX-Technologie. RTX Upscaler ist eine benutzerfreundliche Gradio-basierte GUI, die die Leistung des NVIDIA Maxine Video Effects SDK für KI-gestützte Videooptimierung nutzt.

[![GitHub Release](https://img.shields.io/github/v/release/abus-aikorea/rtx-upscaler)](https://github.com/abus-aikorea/rtx-upscaler/releases)

<p align="center">
  <img style="width: 90%; height: 90%" src="images/main_page.eng.png?raw=true" alt="NVIDIA RTX Video Super Resolution Web UI Interface"/>
</p>  

## 🚀 Hauptfunktionen

- **KI-gestützte Optimierung**: Nutzt NIVIDAs modernste Super Resolution und Artefaktreduktionstechnologie
- **Echtzeit-GPU-Beschleunigung**: Nutzt RTX-Fähigkeiten für schnellere Verarbeitung
- **Benutzerfreundliche Oberfläche**: Einfache Gradio-basierte GUI für mühelose Bedienung
- **Restaurierung alter Videos**: Perfekt für die Aufwertung alter Aufnahmen auf moderne Standards
- **Ein-Klick-Installation**: Portabel und einfach einzurichten

## 🛸 Demovideos
- [You Call It Love (from L étudiante)](https://youtu.be/HXomwoKS3V4)
- [A-ha • “Take On Me” • 1985 [Reelin' In The Years Archive]](https://youtu.be/cZPSTTsmHxI)

## 🎯 Systemanforderungen

- **Betriebssystem**: Nur Windows 10/11 (64-bit)
- **Grafikkarte**: NVIDIA RTX Serie (20, 30, 40, 50) oder NVIDIA Quadro RTX
- **VRAM**: Mindestens 4GB (8GB empfohlen)
- **RAM**: Mindestens 4GB
- **Speicherplatz**: 20GB freier Speicherplatz
- **Internet**: Erforderlich für Installation und Updates
- **Treiber**: Neuester NVIDIA Grafiktreiber erforderlich

## 🛠️ Installationsanleitung

### Schnellstart
1. 🚀 Führen Sie `configure.bat` aus (Ersteinrichtung)
   - Installiert erforderliche Abhängigkeiten (git, ffmpeg, CUDA)
   - Einmaliger Vorgang, Internetverbindung erforderlich
   
2. 🚀 Führen Sie `start.bat` aus
   - Startet RTX Upscaler mit Web-UI
   - Erste Ausführung beinhaltet automatische Installation

### Aktualisierung
- Führen Sie `update.bat` aus, um die Python-Umgebung zu aktualisieren
- Empfohlen für bestehende Benutzer

### Deinstallation
- Führen Sie `uninstall.bat` aus, um alle Komponenten zu entfernen
- Oder löschen Sie einfach den Installationsordner (portable Installation)

## 💻 Funktionen

### RTX Studio Oberfläche
- Integrierter YouTube-Downloader
- KI-gestützte Artefaktreduzierung
- Super Resolution Verbesserung
- Video-Komprimierungswerkzeuge
- Unterstützung für alle ffmpeg-kompatiblen Formate
- Anpassbare Ausgabeeinstellungen (wav, flac, mp3)
- Einstellbare Modi, Skalierung, CRF und Voreinstellungen

## ⚠️ Wichtige Hinweise

- **Einschränkungen der kostenlosen Version**: Verarbeitet bis zu 60 Sekunden Video
- **GPU-Kompatibilität**: Unterstützt nur NVIDIA RTX 20 Serie und neuer
- **Erforderliche Software**:
  - Neuester [NVIDIA Grafiktreiber](https://www.nvidia.com/en-us/drivers/)
  - [NVIDIA Video Effects SDK](https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-sdk/resources/)

## 🔧 Fehlerbehebung

Wenn der Browser nicht automatisch startet:
1. Starten Sie die Anwendung über start.bat neu
2. Navigieren Sie manuell zur angezeigten Adresse (z.B. http://127.0.0.1:7892)

Bei Windows-Sicherheitswarnungen:
- Klicken Sie auf "Weitere Informationen" und dann auf "Trotzdem ausführen", falls verfügbar
- Setzen Sie die Dateieigenschaften auf "Entsperren", falls erforderlich


## 📬 Kontakt & Support

- E-Mail: abus.aikorea@gmail.com
- Offizielle Website: https://abuskorea.imweb.me
- Verfügbar auf Amazon: USA, Japan, Singapur, VAE
- Produkt-Demos: [YouTube-Kanal](https://www.youtube.com/watch?v=z8g8LMhoh_o&list=PLwx5dnMDVC9Y7dAjm9r26CZUw1uU5VIeq)

## 🙏 Danksagungen
* NVIDIA Maxine SDK: <https://docs.nvidia.com/deeplearning/maxine/vfx-sdk-system-guide/index.html>
* yt-dlp: <https://github.com/yt-dlp/yt-dlp>
* gradio: <https://github.com/gradio-app/gradio>

## ©️ Urheberrecht
  <img src="images/ABUS-logo.jpg" width="100" height="100"> by [ABUS](https://abuskorea.imweb.me)