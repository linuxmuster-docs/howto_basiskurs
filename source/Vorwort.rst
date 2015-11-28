Vorwort
=======

Stand:

Zuerst sei darauf hingewiesen, dass in der vorliegenden Dokumentation aus Gründen der Vereinfachung und besseren Lesbarkeit fast ausschließlich die männliche Form der Schreibweise verwendet wurde. Es ist jedoch stets ausdrücklich auch die weibliche Schreibweise gemeint, ohne dass dies immer erwähnt wird.


Die Anforderungen an ein Computernetzwerk in einer Schulungsumgebung, also an ein sogenanntes pädagogisches Netzwerk, sind komplexer als beispielsweise die in einer reinen Büroumgebung.


Abgestürzte Arbeitsstationen unter Windows müssen in Minutenschnelle – etwa während einer Abschlussprüfung am Rechner oder von einer Unterrichtsstunde zur anderen – auf Knopfdruck (und damit auch vom Schüler bedienbar) restaurierbar sein.


In bestimmten Unterrichtssituationen ist es wünschenswert, den Zugriff auf das Internet und damit auf diverse Kommunikationsmöglichkeiten wie Mail etc. auf Knopfdruck ausschalten zu können. Entsprechendes kann auch für den Raumdrucker gelten.


Selbstverständlich müssen alle anderen Anforderung an ein LAN/Intranet erfüllt sein, wie Sicherheit gegen Zugriff von außen (Firewall), Internetzugang (www, ftp, mail), Intranetdienste, Datei- und Druckdienste, einfache Benutzeradministration (wer versetzt 1500 Schüler am Schuljahresende?) usw.


Die Musterinstallation
en
für Schulserver sind vorkonfigurierte Serverlösungen, die all diese Funktionalitäten bieten, ohne dass die Netzwerkberater an den Schulen über das Knowhow von IT-Experten verfügen müssen!


Die Musterinstallation des Linux-Servers besitzt im Einzelnen folgende Leistungsmerkmale:

*   Restauration der Betriebssysteme (Linux, Windows) eines Clientrechners auf Knopfdruck: Selbstheilende Arbeitsstationen (SheilA)



*   Filterung problematischer Internet-Inhalte (Sex, Gewalt, Drogen, Raubkopien) über
    *IP*
    FIR



*   Sicherheit im LAN: Paketfilter Firewall (
    *IP*
    FIRE
    )



*   Massenhafte Erzeugung privater Schüler- und Lehrer-Benutzerzulassungen aus Namenslisten, automatische Zuordnung zu Klassen, automatisches Versetzen, persönliche E-mail Adresse



*   Tauschmöglichkeiten innerhalb der Klassen, unter den Lehrern und schulweit



*   Eingeschränkter Plattenplatz für Benutzer (Quotas)



*   Sichere Umgebung für Klassenarbeiten und Abschlussprüfungen am Rechner



*   Komplettes Intranet (E-Mail, www,
    Datenbankanbindung
    )



*   vorinstalliertes
    moodle



*   Remote Administration über das Internet möglich



*   Administration des Systems für den Administrator und Nutzung der unterrichtlichen Möglichkeiten für Schüler, Lehrer über die
    *Schulkonsole*
    im Browser.



*   Webaccess auf Mails vom LAN und von zu Hause für Schüler und Lehrer



*   Verschlüsselter Zugriff auf eigene Daten für Lehrer und Schüler von zu Hause aus



*   Drucker- und Internetzugang raumweise an- u. abschaltbar



*   Vollautomatische Installation!



*   Halbautomatische Aufnahme der Arbeitsstationen in den DHCP- und DNS-Server



*   Auf den Arbeitsstationen kann wahlweise
    *Linux*
    oder
    *Windows*
    als Betriebssystem eingesetzt werden.




Weitere Informationen finden Sie unter:

`www.lehrerfortbildung-bw.de/netz/muster/linux <http://www.lehrerfortbildung-bw.de/netz/muster/linux>`_


**Zielgruppe für den Basiskurs**

Das vorliegende Basiskursskript ist gedacht für Netzwerkberater, die an einer einwöchigen Schulung an der Landesakademie für Fortbildung und Personalentwicklung an Schulen (Standort Esslingen) teilnehmen. Diese sollen mit dem im Kurs vermittelten Wissen in der Lage sein, ein installiertes Schulnetz auf Basis der
*linuxmuster.net*
zu pflegen. Es handelt sich schon aus diesem Grunde weder um ein Linux-Buch, noch um eine Installationsanleitung.


Voraussetzung für die Umsetzung der im Kurs behandelten Themen ist eine vorhandene Installation der
*linuxmuster.net*
in der Version
6
.1 im Schulnetz.


Um Doppelungen zu vermeiden, wird im vorliegenden Skript zum Basiskurs öfters auf Kapitel im Installationshandbuch verwiesen, in denen der jeweilige Sachverhalt schon ausführlich dargestellt wurde. Das Installationshandbuch als Ganzes muss aber als ergänzende Literatur angesehen werden, um sich vertiefendes Wissen anzueignen.


Dieses Dokument wurde ursprünglich mit
*OpenOffice 2.x*
/ 3.x geschrieben
und wird inzwischen mit

*LibreOffice *
4
*.x*
überarbeitet.


Vielen Dank an die unermüdlich arbeitende Open Source-Gemeinde für ihre professionelle Software und Dokumentation!
