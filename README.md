# ETAP 20
![Schematics](https://github.com/gerryvel/ETAP/blob/main/etap.jpg)

Bootssteuerung für eine ETAP 20

Hauptsteuerung für einen Kleinkreuzer 

*Hardware*

- Landanschluss CEE Steckdose
- Batterie 90Ah
- Solarpanel 130Wp
- Siemens-LOGO! mit Touchpanel von ESA SC103

*Funktionen*

- E/A Beleuchtung
- E/A Toplicht
- E/A der Bordelektronik (Plotter, Windmesser)
- Unterspannungsabschaltung Verbraucher
- USV (Ladung Akku)
- Solaranlage (epever) mit Modbus-Kopplung zu Panel
- USB Steckdose

*Messtechnik*

- Windmesser mit ESP8266, WLAN AP, sendet Daten NMEA0183 über WLAN
- Wetterstation mit ESP32, WLAN AP, empfängt die Winddaten vom Windmesser, sendet alle Daten an Plotter über NMEA200
- AIS Empfänger, NMEA0183, Gateway zu NMEA2000, sendet Daten an Vulcan 7
- Kartenplotter B&G Vulcan 7
- Echolot am Vulcan

![Schaltplan](https://github.com/gerryvel/ETAP/blob/main/ETAP.pdf)

![Schematics](https://github.com/gerryvel/ETAP/blob/main/photo_2020-10-09_16-40-10.jpg)

![Schematics](https://github.com/gerryvel/ETAP/blob/main/photo_2020-10-09_16-40-08.jpg)

![Schematics](https://github.com/gerryvel/ETAP/blob/main/photo_2020-05-25_15-32-57.jpg)

![Schematics](https://github.com/gerryvel/ETAP/blob/main/photo/Panel1.jpg)
![Schematics](https://github.com/gerryvel/ETAP/blob/main/photo/Panel2.jpg)
