# Lab: Passwort knacken

# In Aufgabe 1 haben Sie ermittelt, wie viele cracks/s Ihr System schafft. Gehen Sie davon aus, Ihr Rechner schafft 11'693'718 cracks/s, wie lange würde es also maximal dauern, ein Passwort das nur aus Zahlen besteht und 7 Zeichen lang ist zu cracken? Geben Sie die Formel und das Ergebnis an.

10^7 = 1'000'000 

1 / 11'693'718 * 1'000'000 = 0.085 Sekunden

# Wie lautet das Passwort der Datei Secret.zip? Geben Sie auch Ihren Befehl in Ihrem Lösungsvorschlag an.

Das Passwort lautet: 23571113

Der Befehl: fcrackzip -b -c '1' -l 8 -v -u Secret.zip

# Wie lautet das Passwort der Datei TopSecret.zip? Geben Sie auch Ihren Befehl in Ihrem Lösungsvorschlag an.

Das Passwort lautet: SUCCESS

Der Befehl: fcrackzip -b -D -v -u -p rockyou.txt TopSecret.zip