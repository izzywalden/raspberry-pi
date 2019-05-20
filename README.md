Raspberry Pi Projekt: Lego-Smarthome mit LED und Display 

Dies ist eine Anleitung für das Raspberry Pi Projekt von J.K, F.A und I.W. In diesem Projekt wird der Raspberry Pi mit den dazugehörigen Sensoren und Aktoren in ein Legohaus eingebaut und dient damit der Veranschaulichung eines Smart Homes. Durch den dadurch hergestellten Lebensweltbezug eignet sich das Projekt besonders für den Einsatz in der Volksschule. 
Als Aktoren dienen ein 4-Digit Display und ein LED-Lämpchen. Als Sensoren werden ein Bewegungs-, ein Geräusch- und ein Temperatursensor verbaut. Auf dem Display werden nacheinander die Zeit, das Datum, die Temperatur, sowie ein Schriftzug ("COOL HSLU") angezeigt, wenn dies über den Geräuschsensor oder den Bewegungssensor aktiviert wird. Die Uhrzeit, das Datum und das entsprechende Jahr erhält der Raspberry Pi vom Internet. Der Pi muss also immer mit dem Internet verbunden sein. Die Temperatur wird mit einem Temperatursensor gemessen. Mithilfe des Geräuschsensors und des Bewegungssensors kann zwischen den verschiedenen Anzeigen gewechselt werden. Zusätzlich leuchtet das LED-Lämpchen auf, wenn eine Bewegung wahrgenommen wird. 

Für dieses Projekt braucht man: 
-	Raspberry Pi 3 Model B
-	Erweiterungsboard GrovePi+
-	Temperatursensor GRV Temp Hum Pro            = Port D4
-	4-Digit-Display GRV 4Num Display                   = Port D5
-	Bewegungssensor GRV Pir Motion                    = Port D8
-	LED-Lämpchen GRV Flash Color                        = Port D3
-	Geräuschsensor GRV Loudness                        = Port A0
-	Computeranschluss

Hinweis: Alle Sensoren und Aktoren können beispielsweise über reichelt.ch bestellt werden. Sie lassen sich einfach über die hier verwendeten Bezeichnungen finden. 
Installation und Umsetzung

1.	Raspberry Pi und GrovePi aufeinander stecken und die Sensoren und Aktoren mit den oben angegebenen Ports verbinden.
2.	Ein neues Projekt in PyCharm öffnen.
3.	Falls noch nicht gemacht: Raspberry Pi mit PyCharm verbinden (Anleitungen dazu findet man im Internet).
4.	Code von Github importieren (Option mit oder ohne Kommentar möglich).
5.	Die folgenden Module in PyCharm installieren: Smbus1, Smbus 2, Grove.adc, Grove.i2c und Grovepi.
6.	Projekt durch Deployment auf Raspberry Pi laden.
7.	Das Programm starten und testen. 
8.	Die Implementierung in einem Legohaus ist optional und wird deshalb hier nicht weiter erläutert. Dabei sind der Kreativität keine Grenzen gesetzt. 

Quellen

Der Code wurde teilweise von den folgenden Quellen übernommen und abgeändert. Zudem finden sich auf den respektiven Websiten weitere Informationen zu den Sensoren und Aktoren. 

Loudness Sensor: http://wiki.seeedstudio.com/Grove-Loudness_Sensor/
Temperatursensor: http://wiki.seeedstudio.com/Grove-Temperature_and_Humidity_Sensor_Pro/
Display: http://wiki.seeedstudio.com/Grove-4-Digit_Display/
Bewegungssensor: http://wiki.seeedstudio.com/Grove-PIR_Motion_Sensor/
Grove_LED v1.1: http://wiki.seeedstudio.com/Grove-LED_Socket_Kit/

Autorinnen
J.K - Studentin HSLU, F.A - Studentin HSLU, I.W - Studentin HSLU
