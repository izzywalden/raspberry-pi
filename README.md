Raspberry Pi Projekt

Anleitung für das Raspberry Pi Projekt von J.K, F.A und I.W. 
Der Raspberry Pi wird in ein Legohaus verbaut. Auf einem 4-Digit Display wird die Zeit, das Datum, die Temperatur, sowie ein Schriftzug (Cool HSLU) angezeigt. Die Uhrzeit, das Datum und das entsprechende Jahr erhält der Raspberry Pi vom Internet. Der Pi muss also immer mit dem Internet verbunden sein. Die Temperatur wird mit einem Temperatursensor gemessen. Mithilfe eines Geräuschsensors und einem Bewegungssensor werden die verschiedenen Funktionen (Datum, Uhrzeit, Jahr, Temperatur, Cool Hslu) angezeigt. Zusätzlich reagiert ein LED Lämpchen auf Bewegung. Dazu braucht man ein LED als Aktor und einen Bewegungssensor.

Hardware und Port

Für dieses Projekt braucht man: 
Raspberry Pi 3 Model B;
Erweiterungsboard GrovePi+;
Temperatursensor GRV Temp Hum Pro = Port D4;
4-Digit-Display GRV 4Num Display = Port D5;
Bewegungssensor GRV Pir Motion = Port D8;
LED-Lämpchen GRV Flash Color = Port D3;
Geräusch Sensor GRV Loudness = Port A0;
Computeranschluss

Aufbau und Instellation

1. Raspberry Pi und GrovePi aufeinander stecken und die Sensoren und Aktoren mit den entsprechenden Ports verbinden.
2. Neues Projekt in PyCharm eröffnen (Anleitung wie man den Raspberry Pi mit PyCharm verbindet, findet man im Internet).
3. Code von Github importieren (Option mit oder ohne Kommentar möglich).
4. Die verschiedenen Module auf Pycharm installieren (Smbus1 und 2, Grove.adc, Grove.i2c und Grovepi).
5. Projekt mit Hilfe von "Deployment" auf Raspberry Pi deployen.


Code Quellen

Der Code wurde mit Hilfe von diesen Seiten erstellt:
1. Loudness Sensor:  http://wiki.seeedstudio.com/Grove-Loudness_Sensor/
2. Temperatur: http://wiki.seeedstudio.com/Grove-Temperature_and_Humidity_Sensor_Pro/
3. Display: http://wiki.seeedstudio.com/Grove-4-Digit_Display/
4. Bewegungssensor: http://wiki.seeedstudio.com/Grove-PIR_Motion_Sensor/
5. Grove_LED v1.1: http://wiki.seeedstudio.com/Grove-LED_Socket_Kit/

Autoren

J.K - Studentin HSLU
F.A - Studentin HSLU
I.W - Studentin HSLU
