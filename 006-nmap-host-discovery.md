# Lab: Nmap Host Discovery

## Wieso nutzt Nmap vier verschiedene Paket-Typen und Scans um festzustellen, ob ein Remote-Host online/erreichbar ist?

Weil ein Host der online ist meistens mindestens eines der vier Pakete irgendwie beantwortet und diese Anfragen interessante Bereiche abdecken

## Wieso nutzt Nmap für ein Host Discovery im lokalen Netzwerk (Aufgabe 4) andere Paketdee als für ein Host Discovery eines Rechners im Internet (Aufgabe 2)?

Weil der ARP Scan viel schneller ist als der Ping Scan und ARP Anfragen beantwortet werden müssen (kann aber nur im lokalen netz gebraucht werden) 

## Welches Protokoll haben die beiden Pakete, die am Schluss von Aufgabe 4 angezeigt werden? Welche Destination Adresse haben die beiden Protokolle?

Das Address Resolution Protocol (ARP) -> Die Anfrage geht für jede mögliche Adresse an den Broadcast. Falls ein Gerät unter einer IP im angegebenen Bereich erreichbar ist (im Bild CZNICzsp_00)  antwortet das Gerät direkt an den client der die Anfrage gestartet hat