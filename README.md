# System-Programmierung
## Hands-on zu Lektion 4
Für Slides und Code Beispiele, siehe [Lektion 4](../../../fhnw-syspr/blob/master/04/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Prüfen Sie die vorhandenen Forks, um das Repository für Ihre Klasse zu finden.](../../network/members)*

### a) Eigenes *malloc()*, 30'
* Implementieren sie im Programm my_malloc.c die Funktionen *my_malloc()* und *my_free()* "von Hand".
* Nutzen Sie dazu die System Calls *sbrk()* oder *brk()*.
* Starten Sie mit einer einfachen<sup>*</sup> Implementierung.

<sup>*</sup>Läuft *test1()* fehlerfrei? Was braucht es für *test2()*?

### b) Signal Handler, 15'
* Schreiben Sie ein Programm *my_sigint.c*, welches das Signal *SIGINT* mit einem Handler behandelt.
* Die Handler Funktion soll dabei handle() heissen.
* Senden Sie dem Programm *SIGINT* mittels *CTRL-C*.
