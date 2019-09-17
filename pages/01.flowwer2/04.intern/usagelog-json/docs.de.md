---
title: Verbrauchsinfo-JSON
media_order: F2-UsageLogSample.json.txt
taxonomy:
    category:
        - docs
visible: true
---

Das FLOWWER2-System protokolliert chronologisch Statusänderungen an zubuchbaren Features.  
Mit dieser Information wird ein Nutzungsprotokoll für jedes FLOWWER2-Konto erstellt, welches als .JSON-Datei zum Export verfügbar ist.  
Vollständige Beispieldatei zum Download: [F2-UsageLogSample.json.txt](F2-UsageLogSample.json.txt)

>>>>> Zeitangaben sind [ISO 8601-Formatiert](https://de.wikipedia.org/wiki/ISO_8601)

### Schematischer Aufbau
Das JSON-File beinhaltet ein JSON-Objekt mit allen Accounts des Abrechnungszeitraums
  + Interne Id
    - [Account](#class-account)
    - [Bill](#class-bill)
  + Interne Id
    - [Account](#class-account)
    - [Bill](#class-bill)
  + Interne Id
    - [Account](#class-account)
    - [Bill](#class-bill)

... weitere Accounts

---

### "Account"-Klasse <a id="class-account"></a>
| Eigenschaft       | Beschreibung                                                                          | Beispielwert |
|-------------------|---------------------------------------------------------------------------------------|--------------|
| Id                | Automatisch erzeugte, interne ID des Kontos                                           | 2012345      |
| ExternalId        | Optionale ZusatzId, welche zum Abgleich mit externen Systemen eingetragen werden kann |              |
| CustomTitle       | Alternativer Firmenname                                                               |              |
| Name1             | Firmenname 1                                                                          |              |
| Name2             | Firmenname 2                                                                          |              |
| Street            | Straße der Firma                                                                      |              |
| ZipCode           | Postleitzahl                                                                          |              |
| Location          | Ort                                                                                   |              |
| TaxIdNumber       | USt-ID                                                                                |              |
| CentralPhone      | Telefonnummer der Zentrale                                                            |              |
| ContactPersonName | Name des Ansprechpartners                                                             |              |
| Email             | E-Mail der Firma                                                                      |              |
| Website           | WWW-Adresse der Firmenwebsite                                                         |              |

---

### "Bill"-Klasse <a id="class-bill"></a>
| Eigenschaft         | Beschreibung                                                                          | Beispielwert               |
|---------------------|---------------------------------------------------------------------------------------|----------------------------|
| RunningNo           | Automatisch erzeugte, interne ID des Kontos                                           | 2012345                    |
| Timestamp           | Optionale ZusatzId, welche zum Abgleich mit externen Systemen eingetragen werden kann |                            |
| Start               | Beginn des Bezugszeitraums                                                            | "2019-04-14T16:21:31.423Z" |
| Stop                | Ende des Bezugszeitraums                                                              | "2019-05-14T16:21:30.423Z" |
| TotalDays           | Errechnete Anzahl Tage im Bezugszeitraum                                              | 30                         |
| DocumentUploads     | Anzahl hochgeladener Dokumente im Bezugszeitraum                                      | 6                          |
| DocumentUploadBytes | Summe hochgeladener Bytes (der Dokumente) im Bezugszeitraum                           | 652260                     |
| Features            | Aktive Features im Bezugszeitraum                                                     |                            |
| Companies           | Aktive Unternehmen im Bezugszeitraum                                                  |                            |

---

### "FeatureInfo"-Klasse (Activation, CustomizedMails, usw.) <a id="class-featureinfo"></a>
| Eigenschaft         | Beschreibung                                                                          | Beispielwert               |
|---------------------|---------------------------------------------------------------------------------------|----------------------------|
| BookedDays          | Automatisch erzeugte, interne ID des Kontos                                           | 21                         |
| PercentDuration     | Nutzungsanteil des Features am Bezugszeitraum ([mehr Info](#percentduration))         | 70                         |
| DifferingStart      | Optional: Featurebuchung abweichend vom Bezugszeitraum der "Bill"                     | "2019-04-24T15:29:59.027Z" |

---

#### Hinweis zu "PercentDuration" <a id="percentduration"></a>
Dieser Wert beträgt für das Gesamtkonto immer 100 (%).  
Werden zusätzliche Features zum Konto hinzugefügt, wird der erste Buchungsmonat auf den Bezugszeitraum des Gesamtkontos angeglichen. (erkennbar am "DifferingStart"-Wert)  
Das bedeutet, dass normalerweise im ersten Monat weniger als 100 Prozent berechnet wird, in allen darauffolgenden jedoch genau 100% (weil Bezugszeitraum dann identisch zum Gesamtkonto).