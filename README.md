# System-Programmierung
## Hands-on zu Lektion 4
Für Slides und Code Beispiele, siehe [Lektion 4](../../../fhnw-syspr/blob/master/04/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Erstellen Sie eine persönliche Kopie, mit diesem GitHub Classroom Link](https://classroom.github.com/a/nGMlkTJi).*

### a) Eigenes *malloc()*, 30'
* Implementieren Sie ein Programm my_malloc.c das Funktionen *my_malloc()* und *my_free()* anbietet.
* Nutzen Sie dazu die System Calls *sbrk()* oder *brk()*.
* Eine Skizze des *malloc()* Algorithmus' gibt es unter https://stackoverflow.com/a/31026883/3588
* Vereinfachung: Gerüst von [my_malloc.c](my_malloc.c) im Repo.

### b) Signal Handler, 15'
* Ihr nächstes Programm *my_sigint.c*, soll das Signal *SIGINT* mit einer Funktion *handle()* behandeln.
* Schicken Sie ihrem Programm SIGINT mit CTRL-C.
* Welche Rolle spielen User, Shell, Kernel, Prozess?
* Zeichnen Sie ein Sequenzdiagramm des Aufrufs, z.B. mit https://www.websequencediagrams.com/
