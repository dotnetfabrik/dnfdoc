---
title: 'Demo-Paket - Readme'
taxonomy:
    category:
        - docs
visible: true
---

Zip-Datei auspacken

### Struktur / Inhalt
    CoreDMS-Demo.7z
    .\App_Data
      .\AutoStart                        // Arbeitsverzeichnis für von CoreDMS kontrollierte, externe Dienstanwendungen
      .\DBs                              // Datenbanken (leere Demo-Datenbank wird mitgeliefert)
      .\Jobs                             // Arbeitsverzeichnis für asynchrone Aufträge, Multi-Server Synchronisierung und automatische Datenbank-Updates
      .\Logs                             // Protokollverzeichnis für CoreDMS-Logs
    .\Cockpit                            // Programmdateien von DoublePics Cockpit C/S
    .\SERVER                             // Programmdateien von CoreDMS
    .\_start Cockpit.cmd                 // siehe unten
    .\_start SERVER.cmd                  // siehe unten
    .\Server-DB mit Cockpit öffnen.cmd   // siehe unten

**_start SERVER.cmd** startet CoreDMS im GUI-Modus  
Standard API-Binding: http auf TCP 4455 (Testen über Browser auf http://localhost:4455 - Anmeldefenster wird angezeigt wenn erfolgreich verbunden)  
Standard-API-Credendials: admin / admin

**_start Cockpit.cmd** startet DoublePics Cockpit C/S  
-> Neue Datenbank erstellen... "mit einem SERVER verbinden und Einstellungen synchronisieren" auswählen (siehe auch [manual.doublepics.de](http://manual.doublepics.de/server-version-cs-12321128.html))

**Server-DB mit Cockpit öffnen.cmd** startet DoublePics Cockpit C/S und öffnet die mitgelieferte DemoDB-Datenbank (CoreDMS sollte geschlossen sein)