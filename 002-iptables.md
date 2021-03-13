# Lab: Iptables Webserver

## Begründen Sie Ihre Antworten aus Aufgabe 6 und 7. Berücksichtigen Sie dabei auch den Faktor der zeitlichen Reaktion.

6 -> Ist die Webseite aus Kali noch erreichbar?

Ja, wenn die INPUT policy geändert wird betrifft das nur Anfragen die von aussen kommen 

7 -> Ist die Webseite von Ihrem Hostsystem aus noch erreichbar?

Nein, weil durch die INPUT DROP policy alle Anfragen von aussen nicht beantwortet werden (deshalb auch der timeout)  

## Wie lautet der ganze Befehl, um Aufgabe 8 zu erfüllen?

 sudo iptables -A INPUT -p tcp -d 192.168.68.128 --dport 80 -j ACCEPT

## Wie lautet der ganze Befehl, um Aufgabe 9 zu erfüllen? Verwenden Sie als Action DROP oder REJECT? Begründen Sie.

 sudo iptables -A INPUT -p tcp -d 192.168.68.128 --dport 80 -m range --src-range 13.13.13.13-13.13.23.23 -j DROP