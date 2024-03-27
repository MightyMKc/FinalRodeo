# BroncoData Marshal

Dieses README enthält grundlegende Informationen zum Auswertungsprogramm der ESCRA.

## Funktionsumfang

- **Datenbank-Integration:**
  - Teilnehmerdaten und zugehörige Punkte von den Vereinsrodeos werden in der `rodeo.db` Datenbank gespeichert.
  - Auswertungen für Eventrodeos werden nicht in der Datenbank gespeichert, sondern im Browser mit Bezug zum jeweiligen Ort.

- **Auswertung:**
  - Unterstützung der Erfassung von Daten für folgende Klassen: Open, Amateur, Newcomer, Senior, Handicap, Kiddy, Junior, Youth.
  - Auswertung der Disziplinen: Flag-Race, Polebending, Mixed-Race, Barrel-Race und Keyhole-Race gemäß dem offiziellen Regelwerk der ESCRA.

- **Finalrodeolisten:**
  - Automatische Erstellung von Finalisten (TOP15) für die Klassen Open, Amateur, Newcomer und Handicap am Ende der Saison.
  - Finalrodeo für Jugendklassen (Youth, Kiddy und Junior) kann ebenfalls erstellt werden.

- **PDF-Generierung:**
  - Automatische Erstellung von PDFs als Tabellenübersicht oder für Urkunden

## Anmeldung

- Erstellung der Anmeldungen von Startern basierend auf Filtereinstellungen.
- Kombinationsmöglichkeiten:
  1. Auswahl einer Klasse
  2. Auswahl des Ortes 
  3. Teilnehmeranzahl 


## Anmeldungsübersicht

- Anzeigen der Anmeldungen eines Rodeos mit den dazugehörigen zufälligen StartNr.
- Kombinationsmöglichkeiten:
  1. Auswahl einer Klasse
  2. Auswahl des Ortes // Finale
  


## Tabelle

- Erstellung von Auswertungen zu Tagessiegern basierend auf Filtereinstellungen.
- Kombinationsmöglichkeiten:
  1. Auswahl einer Klasse
  2. Auswahl des Ortes (ortsbezogen oder über alle Orte)
  3. Auswahl der Disziplin (einzeln oder alle)
  4. Auswertungen der Finalwertungen

 ## Wertungen

- Eingeben der Rodeoinformation(Zeit,Fehler,Disqualifiziert) und Weiterverarbeitung mit dem Punktesystem der ESCRA.
- Kombinationsmöglichkeiten:
  1. Auswahl einer Klasse
  2. Auswahl des Ortes 
  3. Auswahl der Disziplin 
 

## Gesamtauswertungen

- Erstellung einer Gesamtwertung für eine Klasse über alle Rodeos.
- Enthält verschiedene Durchschnittswerte pro Disziplin, pro Rodeo mit und ohne Finale.
- Laden der Finalwertungen.

## Urkunden

- Generierung von Urkunden für Rodeos und die gesamte Saison.
- Unterschiedliche Generierung je nach Filtereinstellungen.

## Rekorde

- Einsehen der Vereinsrekorde über alle Jahre in Bezug zu den angewendeten Filter.

**Wichtig:**
- Bei Jugendfinalrodeos tauchen Teilnehmer, die nur am Finalrodeo teilgenommen haben, möglicherweise nicht in der Gesamtsaisonwertung auf.
- Urkunden werden dementsprechend auch zur Gesamt-Saison generiert.
- Für Finalteilnehmer können separate Urkunden erstellt werden.
- Wenn die Anmeldungen zu dem Jugendfinalrodeo angezeigt werden sollen, muss Jugendtunier bei der Klasse ausgewählt werden.(Finale+Jugendtunier)


## Eventlösung

- Die Eventlösung hat fast alle Funktionen wie die Vereinslösung. (Anmeldung,Anmeldungsübersicht,Wertungen,Urkunden)
## Installation
Um BroncoData Marshal auf deinem Endgerät ausführen zu können, musst einmal folgende Sachen machen:


- Download der Dateien
- Entpacken der ZIP
- Ausführen der node-v20.11.1-x64.msi Datei aus dem Ordner Installationsdateien
- Doppelklick auf Starte BroncoData Marshal.bat
    -   Anschließend einmal dem Programm folgen und eine Rodeo-Saison anlegen für ein Jahr      wenn keine vorhanden ist.


-------------------------------------------------------------------------------------------

**Wichtig:**
- Es könnte eine Windows Firewall-Meldung angezeigt werden, dort einmal nur mit OK. bestätigen. 




