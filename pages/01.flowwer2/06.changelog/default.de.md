---
title: Changelog
---

## 2.5.4 (2019-07-31 / b380)
* Feature (MailToFlowwer): Anhänge auch aus angehängten E-Mails extrahieren (#348)
* Usability (MailToFlowwer): Alle Absender (anstatt nur dem ersten, gültigen Absender) in Absenderprüfung einbeziehen (#347)
* Bugfix (MailToFlowwer): ZUGFeRD-Daten dürfen nicht von MimeMessage-Daten überschrieben werden (#349)

## 2.5.3 (2019-07-26 / b344)
* Allgemein (MailToFlowwer): Floww-Adressierung über Zieladresse nur noch auf Basis von Floww-ID (Floww-Name ist weiterhin über F2-Befehle im Nachrichtentext möglich) (#337)
* Usability (MailToFlowwer): Belegdatum auf aktuelles Tagesdatum vorbelegen (#336)
* Usability (MailToFlowwer): Kopfzeile "X-Receiver" wird für Zieladress-Prüfung miteinbezogen (#334)
* Usability (MailToFlowwer): Kopfzeile "X-Sender" und CC wird für Absenderprüfung miteinbezogen (#330)
* Bugfix (MailToFlowwer): Attachments von Mails aus Mac OS X Mail werden korrekt verarbeitet (#332)
* Intern (MailToFlowwer): Nachrichten von noreply@flowwer2.de werden grundsätzlich ignoriert (#340)
* Intern (MailToFlowwer): Korrekte Verarbeitung von Mails ohne PlainText / mit reinem HTML-Inhalt (#331, #339)

## 2.5.2 (2019-07-25 / b322)
_Interner Release_

## 2.5.1 (2019-07-24 / b311)
* Allgemein: Kompatibilität mit restriktiven Proxy-Servern / Firewalls deutlich verbessern. Nutzung von F2 über DATEVnet nun auch ohne Proxy-Ausnahme möglich

## 2.5 (2019-07-06 / b198)
* Feature: Marktplatz-Modul "GUI-Anpassungen" (Primärfarbe kann geändert werden, Upload eines eigenen Logos und einer eigener Schriftart, Bezeichnung von KOST2 anpassbar)
* Feature: Zusätzliches Datenfeld "Kostenstelle 2" am Beleg und im Logbuch (wird als Filtermerkmal verwendet)
* Feature: Zusätzlicher Infoblock auf Statusmail über abgelehnte Belege (Benutzerberechtigung "Abgelehnte Belege verwalten" vorausgesetzt)
* Feature: Betrag wird in Belegliste angezeigt und ist als Gruppierungsmerkmal verfügbar
* Usability: Deutlich mehr Info auf Statusmail (neu sind Belegdatum, Firma, Floww, Kostenstelle)
* Usability: Dashboard zeigt Beleganzahl auf den jeweiligen Funktionsschaltflächen
* Bugfix: Handling außergewöhnlicher Datenformatierung in ZUGFeRD-Belegen

## 2.4 (2019-06-28 / b161)
* Feature: Templatemöglichkeit für FiBu-Notizen (#309)
* Feature: CC/BCC-Kontoeinstellung für Erinnerungsnachrichten (#302)
* Feature: ZUGFeRD-Daten werden extrahiert und an den Beleg geschrieben (#288, #290)
* Feature: MailToFlowwer verfügbar (#308) - Featurebuchung notwendig.
* Usability: Der Floww von bereits zugewiesenen Belegen kann nun ohne vorhergehendes Ablehnen geändert werden (entsprechende Berechtigung vorausgesetzt)
* Usability: Account-spezifische Mails werden detaillierter verschickt (#306, #292)
* Intern: Verbrauchsdaten stehen im .JSON-Format zur Verfügung

## 2.3 (2019-06-14 / b132)
* Feature: Die Protokollseite kann nun auf Wunsch auch an schreibgeschützte PDF-Dokumente angehängt werden (#304)
* Feature: Erste Version von [F2-Client](https://client.flowwer2.de) für Systeme hinter empfindlichen Firewalls (#294)
* Feature: Gruppier-, Filter- und Sortiermöglichkeit in der Oberfläche (#303, #225, #241)
* F2CLI: Protokoll anhängen steuerbar über Kommandozeile (#297)

## 2.2 (2019-05-31)
* Bugfix: Belege mit ZUGFeRD-Daten werden korrekt an DATEV übermittelt (#296)

## 2.1 (April 2019)
* F2FTP: erster, interner Test
* Marktplatz wird freigegeben

## 2.0 (März 2019)
* Belegtyp reaktivieren (Fix #189)
* DATEV "Accounting/Documents"-Schnittstelle verwenden
* Flowwer-Log an PDF anhängen
* List auf aktive Dokumente auf Dashboard (Add IndexActionCard for AdministerAllDocuments)
* Link zu mobiler Freigabe auf Dashboard (Add mobile-button to SignableDocumentsCard)
* Zeichenbegrenzung auf 255 Zeichen beim DATEV-Upload (Fix #190)
* Originaldateiname und fortlaufende Nummer als Dateiname für DATEV-Upload (Fix #191)
* Links in Statusmails korrigieren (fix: #187: /app aus Links Statusmail entfernen)
* Tool Tipp fehlt (Fix #180)
* Fibu Notiz nimmt mehr als 255, folgt Fehlemeldung (Fix #182)
* Englisches Wort "ANNOTATION" in Logbuch (Fix #185)
* Mobile Dokumentenfreigabe entwickeln (Improve responsitivity + #169: Dokumenten Freigabe mobil)
* Badges verschmelzen je nach Warn-Farbe mit Hintergrund
* Neues Farbschema (Apply theme styles)