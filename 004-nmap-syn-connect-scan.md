# Lab: Nmap SYN- und Connect Scan

# Was ist die Idee der Host Discovery in Nmap?

Die Idee von Host Discovery ist herauszufinden, ob der Host überhaupt erreichbar ist, bevor man einen port scan startet

# Wie viele Pakete werden von wem mit dem TCP Connect Scan -sT und wie viele mit dem SYN Scan -sS über das Netzwerk geschickt?

TCP Connect: 4 Pakete
SYN: 3 Pakete

# Was ist ein Einsatzszenario für den TCP Connect Scan und was für den SYN Scan?

Der SYN scan wird gebraucht um die möglichen offenen ports zu finden (die schnellere methode gegenüber TCP Connect). Es wird kein 3way handshake durchgeführt.

Der TCP Connect Scan dagegen wird gebraucht, wenn der SYN scan nicht verfügbar ist (z.B. keine root Rechte)