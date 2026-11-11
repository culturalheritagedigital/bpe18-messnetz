# Messnetz – Unterrichtsdatenbank

SQLite-Datenbanken für den Informatikunterricht (Datenbanken, Technisches Gymnasium Umwelttechnik).
Sie enthalten Stammdaten und Messwerte von neun Luftmessstationen im Umkreis von 30 km um Ludwigsburg.

| Datei | Inhalt |
|---|---|
| `messnetz_1.db` | Tabelle `station` (9 Zeilen) |
| `messung_flach.db` | Tabelle `messung_flach` (96 Zeilen) – Station und Messung in einer einzigen, von Hand geführten Tabelle |
| `messnetz_2.db` | Tabellen `station` (9 Zeilen) und `messwert` (6552 Stundenmittelwerte aus zwei Wochen im Januar und Juni 2026) |

## Im Browser öffnen

Die Datenbanken lassen sich ohne Installation in [SQLime](https://sqlime.org) laden:

- `messnetz_1`: https://sqlime.org/#https://raw.githubusercontent.com/culturalheritagedigital/bpe18-messnetz/main/messnetz_1.db
- `messung_flach`: https://sqlime.org/#https://raw.githubusercontent.com/culturalheritagedigital/bpe18-messnetz/main/messung_flach.db
- `messnetz_2`: https://sqlime.org/#https://raw.githubusercontent.com/culturalheritagedigital/bpe18-messnetz/main/messnetz_2.db

SQLime hält die Datenbank nur im Arbeitsspeicher. Änderungen gehen beim Neuladen der Seite verloren
und verändern die Dateien in diesem Repository nicht.

## Quelle und Lizenz

Datenquelle: Umweltbundesamt mit Daten der Messnetze der Länder und des Bundes
(Luftdaten-API, https://luftdaten.umweltbundesamt.de), Messnetzbetrieb LUBW Landesanstalt für Umwelt
Baden-Württemberg, Abruf am 19.08.2026.

Die Daten stehen unter der [Datenlizenz Deutschland – Namensnennung – Version 2.0](https://www.govdata.de/dl-de/by-2-0).

Die Daten wurden für den Unterricht bearbeitet: Sie wurden in eigene Tabellenstrukturen übertragen. In
`messung_flach.db` sind die Messwerte unverändert, Stationsangaben und Einheiten enthalten jedoch
absichtlich eingefügte Erfassungsfehler (abweichende Schreibweisen, Zahlendreher). Diese Tabelle ist deshalb nicht
als Datenquelle geeignet.
