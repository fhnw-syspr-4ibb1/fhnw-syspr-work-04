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

### Abgabe (optional)
* Lokale Änderungen [committen und pushen](#git).
* GitHub [Issue erstellen](../../issues/new) mit "Bitte um Review, @tamberg".
* Offene Fragen ausformulieren, was geht nicht, was haben Sie versucht.
* GitHub mailt mir (@tamberg) automatisch, ich versuche in weniger als 24h zu antworten :)

## Tools
### Git
Auf Ihrem Computer
* Zu Beginn jeder Lektion wird ein Hands-on Repository Link freigeschaltet
* Nachdem Sie das "Assessment" annehmen, bekommen Sie per Email ein Repository
* Die REPO_URL enthält Ihren GitHub Account USER_NAME und Ihre Klasse 3ia oder 3ib, z.B.<br/>
            https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-04-tamberg

Auf dem Raspberry Pi
* Repository klonen<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Neue Datei kreieren<pre>
    $ git add FILE</pre>
* Änderungen committen<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Änderungen hochladen<pre>
    $ git push</pre>

### Nano
Auf dem Raspberry Pi
* Neue oder bestehende Datei öffnen mit $ nano FILE
* Editieren (Achtung, nano hat kein Undo)
* Speichern mit `CRTL-X` `Y` `RETURN`

### SSH
Auf Ihrem Computer
* Terminal öffnen (Mac) oder `WINDOWS` `R` cmd `RETURN` (Windows)
* SSH Session starten mit<pre>
    $ ssh pi@raspberrypi.local</pre>

## Support
- [FHNW Syspr Slack](https://fhnw-syspr.slack.com/)
