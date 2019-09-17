---
title: Glossar
published: false
taxonomy:
    category:
        - docs
visible: true
---

Glossar
 | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X | Y | Z

.
.config-Dateien
Von DoublePics genutze Konfigurationsdateien verwenden grundsätzlich die Dateierweiterung .config und liegen im XML-Format vor.

 

## A
### Analysevorgang
Während des Analysevorgangs werden Elemente erzeugt bzw. aktualisiert.
Je nach Einstellung wird dabei versucht, Bildmuster zu extrahieren, oder es entstehen nur Basis-Elemente.

### Auto-Markierung
Nach der Sortierung werden mit diesem Tool Markierungen (Flags) gesetzt.

Siehe http://manual.doublepics.de/de/auto-markierung-3440712.html

### Anwendungsfall
Bereitstellen verschiedener Szenarien. Überblick, welche Funktionen standardmäßig in DoublePics enthalten sind, welche Möglichkeiten DoublePics bietet und was DoublePics von gewöhnlichen Bildverwaltungs-Tools unterscheidet.

Siehe

Seite:
Sammeln, Pflegen & Kategorisieren
Seite:
Finden ähnlicher Bild-Elemente in großen Datenmengen
Seite:
Illegales Bildmaterial im Internet-Verkehr
Seite:
Illegales Bildmaterial auf Computern
Seite:
Finden ähnlicher Bild-Elemente mit anderer Software
Seite:
Live-Abfrage (z.B. für Online-Datenbank)
Seite:
Anwendungsfälle
Seite:
Logos / Muster in Bild-Elementen finden
Seite:
Zusammenfassen/Archivieren aus verschiedenen Quellen
 

 

## B
### Basis-Element
Basis-Elemente enthalten nur die Informationen über die Elementquelle, jedoch keine Bildmuster. Dazu gehören z.B. Dateiname, Pfad, Datum, Größe und optional der MD5-Hash.
Basis-Elemente können sowohl vom Typ "unbekannt" als auch "DATA" sein.

Bild-Element
Dateien, die beim Analysieren durch DoublePics als Bildmaterial erkannt werden, werden als Thumbnails dargestellt. Auch diese Daten-Elemente werden in der Cockpit-Datenbankübersicht angezeigt. 
Konnte bei der Analyse kein Bildmuster extrahiert werden, entsteht nur ein Basis-Element. Wurden dagegen mehrere Bildmuster extrahiert, entsteht ein Multi-Element.

Bildmuster
Ein Bildmuster ist ein Computermodell des visuellen Inhalts eines Bildes. Es schafft die Möglichkeit, andere Bildmuster ähnlichem Inhalt suchen zu können, ohne die originalen Bilddateien zu benötigen.

Siehe

Seite:
Datei-Vergleich (MD5-Vergleich) (Doku DoublePics)
Bildmustervariante
Das interne "Datenformat" eines Bildmusters. 
Beispiele: SQ24, PixelMD5

Bildserie
Als Bildserie werden Bild-Elemente bezeichnet, die in einem Zusammenhang stehen. So sind zum Beispiel Multipage Dateien wie TIFF- oder gif-Dateien eine Bildserie, da diese nichts anderes als eine Aneinanderreihung von Einzelbildern sind.

Siehe

Seite:
Filmgruppierung
Seite:
Szenenübersicht
Seite:
Film-Sequenzen
 

 

C
Client
In einem DoublePics Client/Server - Netzwerk werden die PCs, auf welchen die zu analysierenden Daten liegen, als  Client -PCs bezeichnet. 
Das Gegenstück dazu ist der DoublePics-Server, welcher mehrere Clients bedienen kann.



D
DATA-Element (Daten-Element)
Daten-Elemente, die beim Analysieren durch DoublePics nicht als Bildmaterial erkannt werden, werden als DATA gekennzeichnet.  Auch diese Daten-ELemente werden in der Cockpit-Datenbankübersicht angezeigt.  Sie haben jedoch die Möglichkeit als DATA markierte Dateien auszublenden.

Datenbank-ID
Die Datenbank-ID ist ein Hashwert der beim Datenbank-Export im DoublePics Cockpit erstellt wird. Anhand dieser ID lässt sich eindeutig die Identität einer Referenzdatenbank nachweisen. Somit können Sie auf einen Blick jegliche Manipulation an einer Referenzdatenbank feststellen oder auch genau bestimmen mit welcher Referenzdatenbank zu einem gewissen Zeitpunkt ein Suchauftrag durchgeführt wurde.




DirectShow
DirectShow oder ehemals ActiveMovie bzw. DirectX Media dient der Verarbeitung von Video- und Audio-Dateien, womit sich verschiedenste Arten von Video-Dateien (AVI, MPEG) und Ton-Dateien (z. B. MP3) wiedergeben oder erstellen lassen. Es wird auch Streaming unterstützt und ist durch DirectShow-Filter beliebig erweiterbar.

DirectShow wurde inzwischen aus dem DirectX SDK entfernt und ist in das Windows Plattform-SDK aufgenommen worden. Somit gehört DirectShow streng genommen nicht mehr zu DirectX, sondern ist jetzt ein Bestandteil der Windows-Plattform.

Drag&Drop
Drag & Drop bedeutet "Ziehen und Ablegen". Bei DoublePics können so - mithilfe der gedrückten linken Maustaste - Fenster an andere Stellen oder auf einen anderen Bildschirm gezogen und angedockt werden.



E
Einlesevorgang
Die Eingliederung der Elemente in die Datenbank wird als Einlesevorgang bezeichnet. Um einen Bild- oder Video-Bestand einzulesen, wird eine DoublePics Datenbank benötigt. Dies geschieht durch das "Datei"-Menü und die Auswahl von "Neue Datenbank erstellen" oder "Bestehende Datenbank öffnen". Mit Hilfe des Reiters "Einlesen" werden die Elemente dann in die Datenbank eingegliedert.

Siehe

Seite:
Optionen
Seite:
Fortschritt
Seite:
Warteschlangen
Seite:
Ergebnis
Seite:
Elemente einlesen


Elementliste
Die Elementliste ist eine sichtbare Liste der selektierten Elemente der Baum-/Ordnerstruktur.

Siehe

Seite:
Elementliste
 

Elementquelle
Jedes Element ist mit einer Elementquelle verbunden, aus welcher das Element ursprünglich während der Analyse erstellt wurde. Dateien sind die häufigsten Elementquellen.

Die Elementquelle muss für einen Suchlauf nicht verfügbar sein.

 

exif-Dateien
Das Exchangeable Image File Format (offizielle Abkürzung ist Exif) ist ein Standardformat für das Abspeichern von Metadaten in digitalen Bildern.

Exif-Daten werden direkt in die Datei von Bildern der Formate JFIF (JPEG) oder TIFF geschrieben – im sogenannten Header. Inzwischen legt praktisch jede Digitalkamera und jedes Smartphone diese zusätzlichen Informationen zu der Bildaufnahme ab. Fast jede Bildbearbeitungs-Software ist in der Lage, diese Parameter ausgeben, z.B.

Datum und Uhrzeit
Brennweite
Belichtungszeit
Blendeneinstellung
Geographische Koordinaten (diese Daten können durch Geotagging hinzugefügt werden)
Vorschaubild („Thumbnail“)
Weitere nützliche Informationen können nachträglich in Form der sogenannten IPTC-Daten (International Press Telecommunications Council) hinzugefügt werden. Der IPTC-Standard ist neben Exif ein weiterer Standard, der überwiegend im Fotojournalismus zum Einsatz kommt. Beispiele von typischen IPTC-Feldern sind:

Bildbeschreibung
Ersteller
Urheberrechtsvermerk
 

F
False-Positive
Als False-Positive wird ein falscher Suchtreffer, sprich ein Treffer, dessen Bildmuster nicht gleich bzw. ähnlich sind, bezeichnet. Dies kann insbesondere bei toleranten Sucheinstellungen vorkommen.

Siehe

Seite:
False-Positive-Management
Farbtoleranz
Legt fest, wie empfindlich ein Suchvorgang auf unterschiedliche Farben reagieren soll. Je höher Sie die Toleranz einstellen, desto eher werden auch Bilder gefunden, die gleich aussehen, aber unterschiedlich hell sind, oder z.B. durch unterschiedliche Scanner, verschiedene Farbstiche haben. Bei relativ hoher Farbtoleranz werden auch Bilder gefunden, die sowohl in Farbe als auch in Graustufen vorliegen. Eine höhere Farbtoleranz verlangsamt den Suchvorgang nur leicht. 
Eine zu hoch gewählte Farbtoleranz wird zu Fehlerkennungen führen.

Favoritenliste
Kategoriewerte können vorab durch Auswahl im "Suchen"-Menü durch Anwahl des "+"-Elements in die darunterliegende Favoritenliste verlinkt werden. Somit ist eine schnellere Zuweisung möglich, da dieser Kategoriewert nicht bei jeder Zuweisung neu gesucht werden muss.

 

G
Gesamt-Toleranz
Legt fest, ab bzw. über welchem "Ähnlichkeits"-Wert gefundene Bilder nicht im Suchergebnis auftauchen. Mit diesem Wert können Sie verhindern, dass bei extrem hohen Toleranzen zu viele Bilder angezeigt werden, die inhaltlich nicht ähnlich sind.

Siehe

Seite:
Toleranzen
 

 

H
Hash Algorithmus
Beschreibt die notwendigen Schritte, um einen Hashwert eines bestimmten Hashtyps zu berechnen.

HashSet
Als HashSet wird eine Sammlung von Hashwerten (z.B. MD5, SHA1 usw.) bezeichnet, die allesamt aus Dateien eines bestimmten Ursprungs oder eines bestimmten Inhaltstyps (z.B. illegales Bildmaterial) erstellt wurden.
DoublePics Cockpit kann HashSets komfortabel importieren und weiterverarbeiten

Hashwert
Die Prüfsumme (= Hashwert), welche unter Anwendung eines Hash-Algorithmus auf eine Datenmenge (z.B. Inhalt einer Datei) berechnet wurde.

Beispiel (SHA1): 68ac906495480a3404beee4874ed853a037a7a8f
(Berechnet aus "Franz jagt im komplett verwahrlosten Taxi quer durch Bayern")

Siehe

Seite:
Hash-Verwaltung
Seite:
CSV-Hash Import
Seite:
Arbeiten mit dem Hashwert
Seite:
Hash-Dubletten entfernen?
Hauptfenster
Im Hauptfenster befinden sich die standardmäßig eingestellten Unterbereiche (Ordner/Baum, Filter, Server-Suchjobs, etc.), welche angedockt, entkoppelt, versteckt und verschoben werden können.

Siehe

Seite:
Reiter - Tabs
Seite:
Optionen - Globale Einstellungen
 



I
Integrationspunkt
Unter Integrationspunkten versteht man weitere Unterteilungen von Kategorien, in die dann die jeweiligen Kategoriewerte "eingehängt" werden. Dies wird hier besonders deutlich.

Siehe

Seite:
Kategorien
Seite:
Arbeiten mit Kategorien
 

 

J
  Job

 Allgemeiner Oberbegriff für eine von DoublePics-Server auszuführende Aufgabe.

Job-Verzeichnis
Über das Jobverzeichnis werden die einzelnen, zu erledigenden Jobs, koordiniert. Die Dateiendung der dort erstellten Dateien entscheidet über deren Verwendung bzw. deren Status.

 

K
Kategorie
Jedes Bild, welches in einer DoublePics-Datenbank enthalten ist, kann einer oder mehreren Kategorien zugewiesen werden. Auf diesem Weg können Metadaten mit Bildmengen verbunden werden und z.B. für Reports zur Verfügung stehen. Kategorien werden vom Administrator serverseitig angelegt.

Siehe

Seite:
Kategorien
Seite:
Arbeiten mit Kategorien
Kategoriewert
Kategoriewerte sind Unterkategorien, die - im Gegensatz zu Kategorien und Integrationspunkten - vom Benutzer selbst definiert und angelegt werden können. Bei der Kategorisierung werden die Elemente den Kategoriewerten zugewiesen, die wiederum unter den Integrationspunkten und Kategorien eingeordnet sind.

Siehe

Seite:
Kategorien
Seite:
Arbeiten mit Kategorien
 
Konsolidierte Treffer
Sämtliche Treffer werden in Gruppen zusammengefasst.

Siehe

Seite:
Suchergebnis
Seite:
Strukturkopie (nur in C/S Version implementiert)
Seite:
Auto-Markierung
Seite:
Report
Seite:
Gespeichertes Suchergebnis laden
Seite:
Suchergebnis: Kategorien
Kontextmenü
Menü, welches sich öffnet, wenn man die rechte Maustaste drückt. Man erhält eine Übersicht aller Aktionsmöglichkeiten, die in diesem konkreten Kontext verfügbar sind.

Kunden-Center der DotNetFabrik
Im Kunden-Center der DotNetFabrik (https://customercare.dotnetfabrik.de) finden sich verschiedene Möglichkeiten der Kontaktaufnahme, aber auch Optionen wie "Passwort ändern". Ihre verfügbaren Lizenzpakete und Lizenzberechtigungen sind dort ebenfalls aufgelistet.

 

L
Lizenzverwaltung
In der Lizenzverwaltung sind die benutzten Versionen als auch die nicht aktivierten Lizenzen sichtbar (z.B. noch nicht aktivierte Verlängerungen). Mehr dazu finden Sie in der Rubrik Lizenzverwaltung und den FAQs.

Siehe

Seite:
Lizenzverwaltung (Dialog)
Seite:
Ändern der aktiven Lizenz
Seite:
FAQ - Fragen zur Lizenzverwaltung
Löschfunktion
In DoublePics gibt es zwei verschiedene Möglichkeiten, Elemente zu entfernen, bzw. zu löschen:

"Markierte Dateien entfernen" - markierte Elemente werden aus der Datenbank entfernt (NICHT auf der Festplatte!)
"Markierte Dateien löschen" - markierte Dateien werden auf der Festplatte gelöscht!
Siehe

Seite:
Elemente löschen
 

 

M
MagicCategory
Aus Regeln, welche auf den vollen Pfad (ohne Dateiname) des Referenz-Elements angewendet werden, berechnete Kategorien.

MD5
Prüfsumme über den Inhalt einer Datei. Details siehe Wikipedia

Siehe

Seite:
Datei-Vergleich (MD5-Vergleich)
Metadaten
Als Metadaten werden alle Daten bezeichnet, die zusätzlich zum "eigentlichen Dateiinhalt" existieren. Darunter fallen Informationen wie zum Beispiel Dateinamen, Dateigröße, etc.
Hinweis: Änderungen an diesen Daten verändert auch den Hashwert einer Datei.

Siehe

Seite:
Elemente einlesen
Multi-Element
Ein Element, zu welchem mehrere Bildmuster gehören. Ein Multi-Element entsteht entweder bei der Analyse von Bild-Dateien mit mehreren Seiten, z.B. GIFs oder TIFFs oder bei der Filmanalyse.
Multi-Element deswegen, weil ein Film - egal welches Format - nichts anderes als eine Aneinanderreihung einzelner Bild-Elemente ist.

Siehe

Seite:
Filmgruppierung
Seite:
Szenenübersicht
Seite:
Film-Sequenzen
 

 

N
 

O
Ordnerstatistik
In dieser Übersicht stehen Informationen zu den Elementen des Ordners/Verzeichnis', wie z.B., Anzahl der Elemente im Verzeichnis, davon Bilder, Größe, etc.

P
Passwort ändern
Das Passwort kann jederzeit unter https://customercare.dotnetfabrik.de/ geändert werden. Der Login mit dem Benutzernamen und dem aktuellen Passwort führt zum User-Profil. Im Dropdown-Menü "Konto" kann das Passwort geändert werden.

Siehe

Seite:
Passwort ändern
Primäre Kategorie
Ist ein Bild mehreren Kategorien zugewiesen, so kann eine dieser Kategorien als Primärkategorie festgelegt werden. Beim Datenaustausch mit anderer Software (z.B. X-Ways) wird diese Kategorie bevorzugt übertragen. 

 

Q
 

R
Referenz-Datenbank
Eine spezielle DoublePics-Datenbank, die aus ausgesuchten Bild- bzw. Video-Elementen besteht.
In Verbindung mit Kategoriedaten kann der DoublePics-Server die Kategorien der Referenz-Elemente auf die Treffer kopieren.

Rekursiv
Falls mehrere Ordner rekursiv (inkl. Unterordner) durchsucht werden sollen, muss im Ordner (Baum) der oberste zu durchsuchende Knoten ausgewählt und die Option "inkl. Unterordner" aktiviert sein.

Report
Graphisch aufbereiteter Trefferbericht der vorangegangenen Suche.

Siehe

Seite:
Strukturkopie (nur in C/S Version implementiert)
Seite:
Auto-Markierung
Seite:
Report
Seite:
Suchergebnis
 

 

S
Scan/Repo
Scan (Vergleichs-Basis)
Die Scan-Quelle bildet die Vergleichs-Basis, dies bedeutet: alle Bilder die sich in der Scan-Quelle befinden werden mit dem Repo, dem Vergleichs-Ziel, verglichen.
Die Scan-Quelle ist also der Bildbestand den Sie nach Matches durchsuchen möchten.

Repo (Vergleichs-Ziel)
Das Repo (engl. repository = Lager, Depot oder auch Quelle) ist das Vergleichs-Ziel eines Suchlaufs, also der Bildbestand auf den die Scan-Quelle (die Vergleichs-Basis) verglichen werden soll.

Siehe

Seite:
Ordner-Konfiguration (Scan & Repo)
Beispiele
Durchsuchen einer Bildmenge nach Duplikaten 
Wenn Sie im DoublePics Cockpit eine Datenbank geladen haben und eine neue Suche starten ohne Scan und Repo vorher zuzuweisen, wird die gesamte Datenbank mit sich selbst verglichen.
Dies bedeutet, die Datenbank dient sowohl als Vergleichs-Basis als auch als Vergleichs-Ziel.
Sie werden also Bilder finden, die in Ihrer Datenbank bzw. Bildmenge mehrfach vorhanden sind.

Vergleich einer Bildmenge mit einer anderen Bildmenge 
Wenn Sie zwei Bildmengen miteinander vergleichen, finden Sie Bilder die in beiden Bildmengen vorhanden sind.

Um zwei Bildmengen miteinander zu vergleichen gibt es verschiedene Möglichkeiten:
Wenn Sie z.B. mit dem DoublePics Client einen Fall an den DoublePics Server übertragen,
wird die Bildmenge Ihres Falls (Scan) mit der bereits auf dem Server vorhandenen Referenz-Datenbank (Repo) verglichen.

Sie können auch im DoublePics Cockpit zwei Bildmengen miteinander vergleichen.
Weisen Sie dazu einfach per Kontextmenü einem Ordner oder einer Datei in Ihrer Datenbank die jeweilige Position zu.

 

Sequentielle Treffer 
Suchtreffer im 1:1 Vergleich. Das bedeutet, es wird jeweils ein Bild aus dem Scan mit dem gefundenen Match aus dem Repo gelistet.

Siehe

Seite:
Suchergebnis
Seite:
Strukturkopie (nur in C/S Version implementiert)
Seite:
Auto-Markierung
Seite:
Report
Seite:
Gespeichertes Suchergebnis laden
Seite:
Suchergebnis: Kategorien
Serie / Bildserie
Als Bildserie werden Bilder bezeichnet, die in einem Zusammenhang stehen.
So sind zum Beispiel Multipage Dateien wie TIFF- oder gif-Dateien Bildserien.
Auch die bei der Videoanalyse erstellten SceneFiles zählen als eine Bildserie.
Möchten Sie mehrere Bilder einer Bildserie in zukünftigen Suchen ignorieren, markieren Sie diese als False-Positive-Serie.

Server
In Verbindung mit DoublePics Server kann der Datenabgleich zentral auf einem Server gegen eine Referenzdatenbank erfolgen. Dies ist aber nur mit der Cockpit CS Version möglich.

Siehe

Seite:
Kategorien (Server)
Seite:
Suchen (Server)
Seite:
Export (Server)
Sortieren von Suchergebnissen
Die Sortierung der Treffer-Anzeige ist möglich nach Fundreihenfolge und Treffer-Reihenfolge.

Siehe

Seite:
Gespeichertes Suchergebnis laden
 

Störungs-Toleranz
Legt fest, wie empfindlich ein Suchvorgang auf Unterschiede in den Bildern reagieren soll. Je höher Sie die Toleranz einstellen, desto eher werden auch Bilder gefunden, die nachträglich verändert wurden, z.B. durch eingefügte Logos, anderen Randbeschnitt oder sonstige Veränderungen. Eine höhere Störungstoleranz verlangsamt den Suchvorgang deutlich.

Eine zu hoch gewählte Störungstoleranz wird zu Fehlerkennungen führen.

Siehe

Seite:
Toleranzen
Struktur-Kopie
Speichern des Suchergebnisses in einem selbstgewählten Verzeichnis auf der lokalen Festplatte

Siehe

Seite:
Strukturkopie (nur in C/S Version implementiert)
Seite:
Auto-Markierung
Seite:
Report
Seite:
Suchergebnis
Suchergebnis speichern
Die Suchergebnisse können mit Hilfe verschiedener Instrumente (Struktur-Kopie, Report) gespeichert werden.

Siehe

Seite:
Strukturkopie (nur in C/S Version implementiert)
Seite:
Auto-Markierung
Seite:
Report
Seite:
Suchergebnis
Such-Job
Ein Suchlauf, welcher zur Ausführung auf einem Server in einen Job verpackt wurde.

Suchlauf
Ein Suchlauf wird der Prozess, den DoublePics durchläuft, um ähnliche Bilder zu finden, bezeichnet.
Suchläufe sind entweder elementbasiert (MD5) oder bildmusterbasiert (Classic / PixelMD5).
Siehe: Neue Suche

Siehe

Seite:
Neue Suche
Suspect-Datenbank
Die Suspect-Datenbank wird von einem PureFiles-Job aus einer Ansammlung von Bilddateien, z.B. einem DoublePics Client Fall, erstellt.
Sie dient dem DoublePics Server als Scan-Quelle und wird mit der Referenz-Datenbank verglichen.

 

T
Thumbnails

Kleinstansichten von Bildern. DIese werden benutzt, da sie meist aussagekräftiger sind als der Dateiname selbst.

Toleranz
Dieses Tool regelt die Toleranzgrenze für farbliche Abweichungen, Bildstörungen und legt fest, wie stark ein Bild insgesamt von der Vergleichs-Basis abweichen darf.

Siehe

Seite:
Toleranzen
Tooltip
Mauszeigerhinweis. WIrd die Maus über ein  gezogen, erscheint eine Kurzinformation. Klickt man auf dieses Fragezeichen, wird man direkt an die entsprechenden Stelle im Handbuch weitergeleitet.

Treffer
Ein Treffer ist die Kombination von zwei Bildmustern, die bei einem Suchlauf als gleich oder ähnlich erkannt wurden. Im Suchergebnis werden einzelne Treffer immer zu Treffergruppen zusammengefasst.

Treffergruppe
Bei der Dublettensuche werden die Suchergebnisse (jedes gefundene, multiple Bild-Element) in einer Treffergruppe dargestellt. Hier wird zwischen sequentiellen und konsolidierten Treffern unterschieden.

Siehe

Seite:
Suchergebnis
Seite:
Strukturkopie (nur in C/S Version implementiert)
Seite:
Auto-Markierung
Seite:
Report
Seite:
Gespeichertes Suchergebnis laden
Seite:
Suchergebnis: Kategorien
 


 

U
UND-Verknüpfung
Durch Auswahl mehrere Filterkriterien, werden diese als UND-Funktion miteinander verknüpft, d.h. es werden nur die Datei-Elemente ausgewählt, die ALLE ausgewählten Kriterien erfüllen.

Siehe

Seite:
Filter für Elemente
Seite:
Bild-Filter
Seite:
Datei-Filter
Seite:
Suchen mit der Filterfunktion
UserTracking
Durch das UserTracking kann immer nachvollzogen werden (in den Versionen Professional als auch der Server-Version CS), wer Kategoriezuweisungen getätigt hat.

 

V


Vorschau
Wird ein Bild aus der Elementliste markiert, erscheint in dem dafür vorgesehenen Fenster ein vergrößertes Vorschaubild. In diesem Fenster kann das Bild-Element noch weiter gezoomt (Zoom-In und Zoom-Out) werden.

 

W
Waise
Ein in der DoublePics-Datenbank existierendes Element, dessen Elementquelle nicht mehr verfügbar ist, wird als "Waise" bzw. "verwaist" bezeichnet.
Im allgemeinen sind Waisen entweder Dateien, welche zwischenzeitlich ausserhalb von DoublePics gelöscht wurden, oder sich auf Datenträgern (USB-Sticks, CDs, Wechselplatten, ...) befinden, die momentan nicht angeschlossen bzw. eingelegt sind.

WIC
WIC (Windows Imaging Component) ist eine in Microsoft Windows integrierte Komponente zum Dekodieren von Bildformaten. Sie stellt somit das Gegenstück zu DirectShow dar, welches das Dekodieren von Filmformaten ermöglicht.
WIC ist beliebig erweiterbar durch Codec-Packs, und erlaubt somit auch das Dekodieren von Bildformaten, z.B. RAW-Dateien von Kameras, welche erst nach einem Release von DoublePics entstanden sind.

In der Basis-Installation von Windows (XP, Vista, 7, 8, 8.1, ...) unterstützt WIC folgende Bildformate: BMP, DDS, GIF, HD Photo, ICO, JPEG, JPEG XR, PNG und TIFF. siehe http://msdn.microsoft.com/library/windows/desktop/gg430027.aspx

Bekannte Code-Packs:

Microsoft-Kamera-Codec-Paket (kostenlos)
FastPictureViewer Codec Pack (ca. $15-$20)
 

X
XML-ID
Die XML-ID wird zur Übergabe von Kategoriedaten in Treffern im Zusammenspiel mit Fremdsoftware benötigt.
Für X-Ways wird vom DoublePics Server pro XML-ID eine Berichtstabelle generiert, deren Bezeichnung der XML-ID entspricht. Die durch die Suche gefundenen Dateien werden in diese Berichtstabelle eingefügt.

 

Y
 

Z
 