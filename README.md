# Notenblatt.fods
Notenblatt.fods ist ein LibreOfficeCalc Dokument dass den Notendurchschnitt für den bayerischen "Förderschulabschluss/Mittelschulabschluss im Förderlehrgang Lernen" aus den Einzelnoten berechnet. Es bietet Verechnungsfaktoren für alle mehrteiligen Prüfungen.
## Empfehlungen:
### Format in .ots umwandeln
Wenn das Dokument im Kollegium bereit gestellt wird, empfehle ich das Format der Datei in eine ODF-Spreadsheet-Template (Dateiendung `.ots`) umzuwandeln.
### Dokument schützen
`Cell Protection` sollte unbedingt eingeschaltet sein. Das Dokument kommt mit einem voreingestellten Zellenschutz, das Passwort für die Deaktivierung ist im Dokument in einer (in gedruckter Form nicht sichtbaren) Zelle angegeben. Ich empfehle dringend, das verwendete Passwort für den Zellenschutz in der Datei zu belassen (auch ggf. geänderte Passwörter). Niemand erinnert sich in 2 Jahren an das vergebene Passwort und den Schaden richten unbedarfte Kolleg/innen im Regelfall nur am eigenen Dokument an (voraussgesetzt, das Dokument wird als `.ots` verteilt).
## Installation/Download
### 1. Möglichkeit git
Repository clonen und Dokument öffnen:
```shell
git clone https://github.com/bubens/Notenblatt.git
cd Notenblatt
localc notenblatt.fods
```
### 2. Möglichkeit Download
Eine jeweils aktuelle Version steht hier zum Download bereit:
http://unpunk.de/Notenblatt/notenblatt.fods
