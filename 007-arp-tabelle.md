# Lab: ARP Tabelle

## In Aufgabe 3 werden drei ARP Pakete verschickt aber keine ICMP (Ping) Pakete. Wieso?

Weil es keinen client mit der gesuchten IP Adresse gibt und deshalb keiner auf die arp Anfrage antwortet. Was einen ping überflüssig macht da auch keiner auf den icmp antworten wird.  

## Stimmt in Aufgabe 4 die Source MAC Adresse mit der Antwort im ARP Response Paket überein?

Ja, weil die source seine eigene MAC Adresse mitteilt.

## Wieso gibt es in Aufgabe 5 keinen neuen Eintrag für die IP Adresse 185.183.157.23 in der ARP Tabelle?

Weil die ARP Tabelle nur für clients im Netzwerk geführt wird.