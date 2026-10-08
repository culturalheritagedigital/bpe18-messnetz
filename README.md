# Messnetz – Unterrichtsdatenbank

SQLite-Datenbank für den Informatikunterricht (Datenbanken, Technisches Gymnasium Umwelttechnik).
Sie enthält die Stammdaten von neun Luftmessstationen im Umkreis von 30 km um Ludwigsburg.

| Datei | Inhalt |
|---|---|
| `messnetz_1.db` | Tabelle `station` (9 Zeilen) |

## Im Browser öffnen

Die Datenbank lässt sich ohne Installation in [SQLime](https://sqlime.org) laden:

https://sqlime.org/#https://raw.githubusercontent.com/culturalheritagedigital/bpe18-messnetz/main/messnetz_1.db

SQLime hält die Datenbank nur im Arbeitsspeicher. Änderungen gehen beim Neuladen der Seite verloren
und verändern die Datei in diesem Repository nicht.

## Quelle und Lizenz

Datenquelle: Umweltbundesamt mit Daten der Messnetze der Länder und des Bundes
(Luftdaten-API, https://luftdaten.umweltbundesamt.de), Messnetzbetrieb LUBW Landesanstalt für Umwelt
Baden-Württemberg, Abruf am 19.08.2026.

Die Daten stehen unter der [Datenlizenz Deutschland – Namensnennung – Version 2.0](https://www.govdata.de/dl-de/by-2-0).
