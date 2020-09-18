[**Startseite**](index.md)

[1. Sensor bauen](build_sensor.md) |
[2. Sensor konfigurieren](configure_device.md) | 
[3. Sensor im WLAN finden](find_device_in_wifi.md) |
[4. Sensor registrieren](register_sensor.md) |
[5. Sensor auf Karte finden](sensor_map.md) 

[Vorheriger Schritt](find_device_in_wifi.md)

# Sensor in der Sensor Community registrieren

Der Sensor kann nun mit der [offenen Sensor Community](https://sensor.community/en/)
verbunden werden.
Durch die Registrierung hilft man dem Projekt die aktuellen Feinstaubwerte
zu erfassen und eine ausführliche Auswertung der Daten inklusive grafischer
Anzeige auf einer [Karte](http://deutschland.maps.sensor.community/#15/49.4511/11.0764) zu erstellen.

2. [Geräte Verwaltung](https://devices.sensor.community/) öffnen
3. Registrieren (oben rechts)
4. Nach erfolgreicher Registrierung [einloggen](https://devices.sensor.community/login)
5. Neuen Sensor über Button "Neuen Sensor registrieren" hinzufügen:
	1. Eigene Sensor ID richtig eingeben (Beispiel für eine Sensor ID: 2703647)
	2. Sensorboard: esp8266
	3. Interner Name: Freitext für Bezeichnung des Sensors
	4. Adresse: Wird benötigt, um den Standort zu ermitteln
	5. Zusätzliche Informationen: Freiwillige Angaben die helfen, die Sensordaten besser bewerten zu können
	6. Hardware Konfiguration: Nichts verändern (Sensortyp SDS011 mit Pin 1 und Sensortype DHT22 mit Pin 7)
	7. Oberhalb der Karte auf "Eingegebene Adresse suchen" klicken und prüfen, ob die Adresse korrekt angezeigt wird
	8. Alternativ können auch die Koordinaten in die Felder oberhalb der Karte direkt eingegeben werden
	9. Einstellungen speichern
6. Die Sensor ID für das Auffinden auf der Karte herausfinden
    1. In der Geräteübersicht sollte nun der Sensor erscheinen. Dort steht ganz links unterhalb des "#" Zeichens die 
    ID des Sensors, wie sie auf der Karte verwendet wird
    2. *Diese ID merken.*

[Nächster Schritt](sensor_map.md)
