# Lab: Nmap Basics

## Nach Aufgabe 3 zeigt Nmap den Port 80 als geschlossen ('closed') an. Wieso?

Weil keine Applikation den Port "bedient"

## Nach Aufgabe 7 zeigt Nmap den Port als gefiltert ('filtered') an. Wieso?

Da der input von meiner ip auf deny gesetzt ist, werden alle pakete ignoriert und nicht beantwortet. nmap kann deshalb nicht prüfen ob der port offen oder geschlossen ist  

## Nach Aufgabe 8 zeigt Nmap den Port als geschlossen ('closed') an. Begründen Sie.

durch die reject regel wird der request mit einer reject response beantwortet, womit nmap erkennt, dass der port erreichbar ist 