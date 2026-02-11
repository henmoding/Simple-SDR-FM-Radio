# Simple-SDR-FM-Radio
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
