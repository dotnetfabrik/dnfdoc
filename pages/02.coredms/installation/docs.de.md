---
title: Installation
published: false
taxonomy:
    category:
        - docs
visible: true
---

## IIS-Hosting

Microsoft IIS wird als Reverse-Proxy vor die CoreDMS-Instanz geschaltet und übernimmt deren Startup/Shutdown.  
Diese Installationsvariante wird aus Sicherheitsgründen deutlich bevorzugt, insbesonderen wenn die CoreDMS-API direkt aus einem ungesichterten Netzwerk erreichbar sein soll.

///// Installierter Microsoft IIS wird vorausgesetzt.
Cockpit Web / PhotoCenter erfordert "WebSocket-Protokoll" für optimale Leistung.  

* Website anlegen (korrektes Binding beachten)
* CoreDMS-Binaries in Website-Root kopieren
* Berechtigungen setzen
* Zugriff testen über Browser

## Standalone-Server

Zwei mögliche Betriebsvarianten:

### GUI-Modus
CoreDMS läuft im Kontext des aktuell angemeldeten Benutzers. Ideal für einfache Teststellungen und Fehlersuche.

### Windows-Dienst
CoreDMS wird als Windows-Dienst registriert und kann ohne Benutzeranmeldung automatisch gestartet werden.