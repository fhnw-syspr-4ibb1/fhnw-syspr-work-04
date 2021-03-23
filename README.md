# System-Programmierung
## Hands-on zu Lektion 4
Für Slides und Code Beispiele, siehe [Lektion 4](../../../fhnw-syspr/blob/master/04/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Erstellen Sie eine persönliche Kopie, mit diesem GitHub Classroom Link](https://classroom.github.com/a/nGMlkTJi).*

### a) Eigenes *malloc()*, 30'
* Implementieren sie im Programm my_malloc.c die Funktionen *my_malloc()* und *my_free()* "von Hand".
* Nutzen Sie dazu die System Calls *sbrk()* oder *brk()*.
* Starten Sie mit einer einfachen Implementierung.
* Läuft *test1()* durch? Was braucht es für *test2()*?

### b) Signal Handler, 15'
* Schreiben Sie ein Programm *my_sigint.c*, welches das Signal *SIGINT* mit einem Handler behandelt.
* Die Handler Funktion soll dabei handle() heissen.
* Senden Sie dem Programm *SIGINT* mittels *CTRL-C*.
