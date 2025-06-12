# Tung Tung Turret

Automatisiertes Turret mit ESP32-CAM - Ein Schulprojekt der HTL Mössingerstraße.

## Übersicht

Das Tung Tung Turret ist eine automatisierte Geschützturm-Anlage mit ESP32-CAM Integration für Objekterkennung und Zielverfolgung. Das Projekt kombiniert Hardware-Engineering, Embedded Programming und Web-Entwicklung zu einem funktionsfähigen autonomen System.

## Features

- **Automatische Zielerkennung** mit ESP32-CAM
- **Manuelle Steuerung** über Web-Interface
- **Servo-basierte Pan/Tilt-Mechanik**
- **WiFi-Konnektivität** für Remote-Control
- **Live-Kamera-Stream**
- **Terminal-Interface** für Systemverwaltung
- **Developer-Panel** für Hardware-Konfiguration

## Installation

1. Repository klonen:
```bash
git clone [repository-url]
cd tung-tung-turret
```

2. Hardware Setup:
    - ESP32-CAM Board konfigurieren
    - Servo-Motoren anschließen (Pan: Pin 12, Tilt: Pin 13)
    - Geschütz montieren

3. Software Upload:
    - Arduino IDE verwenden
    - ESP32 Board Package installieren
    - Code auf ESP32-CAM flashen

4. Web-Interface starten:
    - HTML-Dateien auf Webserver deployen
    - Oder lokal öffnen (index.html)

## Nutzung

### Web-Interface
- **index.html** - Hauptseite mit Projektübersicht
- **control.html** - Control Center für manuelle Steuerung
- **dev.html** - Developer Panel für Hardware-Konfiguration
- **terminal.html** - Terminal-Interface für Systemkommandos
- **impressum.html** - Rechtliche Informationen

### Grundfunktionen
1. System über WiFi verbinden
2. Kamera-Stream aktivieren
3. Manuelle Steuerung oder Auto-Modus wählen
4. Ziele erfassen und verfolgen

## Technologie-Stack

**Hardware:**
- ESP32-CAM
- Geschütz
- Servo-Motoren (2x)
- 3D-gedruckte Halterungen

**Software:**
- Arduino C++ (Firmware)
- HTML5/CSS3/JavaScript (Web-Interface)
- Bootstrap 5 (UI Framework)
- WebSocket (Kommunikation)

## Konfiguration

### WiFi Setup
```cpp
const char* ssid = "TungTungNet";
const char* password = "your_password";
```

### Servo-Konfiguration
- Pan-Servo: Pin 12 (0-180°)
- Tilt-Servo: Pin 13 (0-90°)
- Geschwindigkeit einstellbar

### Kamera-Einstellungen
- Auflösung: VGA bis UXGA
- Bildqualität: 4-63
- Helligkeit/Kontrast anpassbar

## Projektteam

- **Pascal Hornbanger** - CEO
- **Ferdinand Gebenetter** - CTO
- **Michael Hammer** - CSDO, CFDO
- **Luka Kaiser** - CQO, CSDO, CFDO
- **Fabian Forstner** - Documentation Manager
- **Christian Isak** - CPO
- **Maximilian Ferner** - CTO
- **Lukas Hillebrand** - CMO

## Schulinformation

**Institution:** HTL Mössingerstraße
**Adresse:** Mössingerstraße 25, 9020 Klagenfurt am Wörthersee
**Abteilung:** Elektronik
**Schuljahr:** 2024/2025

## Lizenz

Dieses Projekt ist ausschließlich für Bildungszwecke erstellt und steht unter der Aufsicht der HTL Mössingerstraße.

## Kontakt

Für Fragen zum Projekt wenden Sie sich an:
- HTL Mössingerstraße - Abteilung Elektronik
- E-Mail: elektronik@htl-klu.at