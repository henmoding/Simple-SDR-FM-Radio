## Simple-SDR-FM-Radio
Hello this Reposertorie is for a Simple FM Radio SDR APP.
# What You Nead
An Sdr
An PC oder Laptop
And an Antenna
# Install
### Linux (Ubuntu/Debian-basiert)
#### Paketquellen aktualisieren:
sudo apt update && sudo apt upgrade

#### GNU Radio & SDR-Treiber installieren:
sudo apt install gnuradio python3-pyqt5 soapysdr-module-rtlsdr rtl-sdr

#### Hardware-Zugriff einrichten: Damit dein SDR-Stick ohne Root-Rechte erkannt wird, müssen die Udev-Regeln aktiv sein. Teste die Erkennung mit:
rtl_test

### Windows
#### Radioconda (Empfohlen): Lade den Installer von der Radioconda Releases Seite herunter. Dies installiert GNU Radio, Python und alle notwendigen Bibliotheken in einem Rutsch.
Zadig-Treiber:

Öffne Zadig.

Wähle Options List All Devices.

Wähle den Eintrag Bulk-In, Interface (Interface 0).

Klicke auf Replace Driver (es muss der WinUSB Treiber sein).

Hinweis: Ohne diesen Schritt wird das Skript den Stick nicht finden.
