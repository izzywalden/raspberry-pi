Raspberry Pi Projekt

Anleitung für das Raspberry Pi Projekt von J.K, F.A und I.W. 
Der Raspberry Pi wird in ein Legohaus verbaut. Auf einem 4-Digit Display wird die Zeit, das Datum, die Temperatur so wie ein Schriftzug (Cool HSLU) angezeigt. Die Uhrzeit sowie das Datum und das entsprechende Jahr erhält der Raspberry Pi vom Internet. Der Pi muss also immer mit dem Internet verbunden sein. Die Temperatur wird mit einem Temperatursensor gemessen. Mit Hilfe eines Geräuschsensors und einem Bewegungssensor werden die verschidenen Funktionen (Datum, Uhrzeit, Jahr, Temperatur, Cool Hslu) angezeigt. Zusätzlich reagiert ein LED Lämpchen auf Geräusche und Bewegung. Dazu braucht man ein LED als Aktor sowie ein Geräuschsensor und ein Bewegungssensor.

Hardware und Port

Für dieses Projekt braucht man: 
Raspberry Pi 3 Model B;
Erweiterungsboard GrovePi+;
Temperatursensor GRV Temp Hum Pro = Port D4;
4-Digit-Display GRV 4Num Display = Port D5;
Bewegungssesnor GRV Pir Motion = Port D8;
LED-Lämpchen GRV Flash Color = Port D3;
Geräusch Sensor GRV Loudness = Port A0;
Computeranschluss

Aufbau und Instellation

1. Raspberry Pi und GrovePi aufeinander stecken und die Sensoren und Aktoren mit den entsprechenden Ports verbinden.
2. Neues Projekt in PyCharm eröffnen (Anleitung wie man den Raspberry Pi mit PyCharm verbident findet man im Internet)
3. Code von Github importieren. (Option mit oder ohne Kommentar möglich)
4. Die verschiedenen Module auf Pycharm installieren. (Smbus1 und 2, Grove.adc, Grove.i2c und Grovepi)
5. Projekt mit Hilfe von "Deployment" auf Raspberry Pi deployen.


Code Quellen

