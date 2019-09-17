---
title: 'Häufige Fragen (FAQ)'
taxonomy:
    category:
        - docs
    author:
        - SaS
visible: true
page-toc:
    active: true
---

##### Gibt es ein Größenlimit für Mails an MailToFlowwer?
Ja, der F2-Mailserver nimmt E-Mails mit höchstens 5 MB Übertragungsgröße an.

##### Warum wird von FLOWWER v2 nur im .PDF-Format übertragen?
Das hat mehrere Gründe:
1. Das Freigabeprotokoll muss an die Übertragungsdatei angehängt werden können.
2. Bei ZUGFeRD-Rechnungen sind die Rechnungsdaten im XML-Format an das PDF angehängt.
3. PDF-Dateien können extrem kompakt sein, wenn das Belegbild nicht als [Rastergrafik](https://de.wikipedia.org/wiki/Grafikformat#Liste_von_Dateiformaten_f%C3%BCr_Rastergrafiken) sondern in einem [Vektorformat](https://de.wikipedia.org/wiki/Grafikformat#Liste_von_Dateiformaten_f%C3%BCr_2D-Vektorgrafiken) vorliegt.
4. Die allermeisten elektronischen Rechnungen werden als .PDF-Datei verschickt

Unabhängig vom Ausgabeformat haben wir in Planung, auch andere Dateiformate (TIF, JPG, PNG) in FLOWWER v2 hochladen zu lassen.  
Diese sollen dann bei Weitergabe zu einer .PDF-Datei zusammengefügt werden.

##### Macht es Sinn, per Mail empfangene Dateien auszudrucken, einzuscannen und in FLOWWER v2 hochzuladen?
Grundsätzlich funktioniert das genausogut, wie die E-Mail per MailToFlowwer direkt verarbeiten zu lassen oder den .PDF-Anhang abzuspeichern und in FLOWWER v2 hochzuladen.  
Jedoch: digital erstellte Rechnungen sind in der Regel reine Vektor-PDFs und damit sehr kompakt. Wird eine solche Datei ausgedruckt und wieder eingescannt, geht dieser Größenvorteil verloren. Das liegt daran, dass der Scanner nur ein Rasterabbild des Ausdrucks erstellen kann.  
Deutlich platzsparender ist somit in aller Regel die unmittelbare Verarbeitung der .PDF-Datei.