# ETAP 20
![Schematics](https://github.com/gerryvel/ETAP/blob/main/etap.jpg)

Bootssteuerung für eine ETAP 20

Hauptsteuerung für einen Kleinkreuzer 

*Hardware*

- Landanschluss CEE Steckdose
- Batterie 90Ah
- Solarpanel 130Wp
- Siemens-LOGO! mit Touchpanel von Kinco 4,3"
- NMEA 2000 Netzwerk
- B&G Plotter Vulcan 7

*Funktionen*

- E/A Beleuchtung Raum und Navitisch
- E/A Steckdose E-Motor
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

*Schaltplan*

![Schaltplan](https://github.com/gerryvel/ETAP/blob/main/ETAP.pdf)

*Fotos*

![image](https://user-images.githubusercontent.com/17195231/227980468-d2b7e442-e219-49b4-a7d9-7403569d0187.jpeg)

![image](https://user-images.githubusercontent.com/17195231/227984708-99b8dcd1-320f-438b-afbe-812f05a47e54.jpeg)

![image](https://user-images.githubusercontent.com/17195231/228045143-26477db6-011c-4879-a8df-05baee568746.jpeg)

![image](https://user-images.githubusercontent.com/17195231/228045332-98923f65-827a-4b17-bdb6-ee9eb743253e.jpeg)



