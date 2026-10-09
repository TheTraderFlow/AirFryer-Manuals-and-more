# AirFryer – Manuals and more

Original-Hefte (Gebrauchsanweisungen, Rezept- und Schnellstartanleitungen) zu Heißluftfritteusen, sortiert nach Hersteller und Modell.
Wird von [Fritti – Heißluft-Schnellsuche](https://github.com/TheTraderFlow/AirFryer) genutzt, um die PDFs auszuliefern („Im Heft öffnen“, „Herunterladen“).

## Ordnerstruktur

```
<marke>/              z. B. ninja       (klein, ohne Leerzeichen)
  <modell>/           z. B. dz400eu
    *.pdf             Gebrauchsanweisung, Rezeptheft, ...
    modell.json       Stammdaten und Liste der Dokumente
```

Neue PDF: in den passenden Ordner legen (neuen Ordner für neue Marke/Modell anlegen), in `modell.json` unter `dokumente` eintragen und die Herkunft unten in der Tabelle ergänzen. Dieselbe Struktur gilt im Fritti-Repo unter `quellen/`.

## Inhalt

Stand: 10.10.2026 – 6 PDF-Dateien, 5 Modelle, 2 Marken.

| Marke | Modell | Dokument | Sprachen | Datei | Herkunft | Abgerufen |
|---|---|---|---|---|---|---|
| Ninja | DZ400EU (MAX Dual Zone 9,5 L) | Schnellstart- und Rezeptanleitung | EN, DE, FR | [ninja/dz400eu/schnellstart-rezeptanleitung.pdf](ninja/dz400eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite (support.sharkninja.fr, Produkt AF400EU/DZ400EU, „Guides de démarrage rapide“) | 09.10.2026 |
| Ninja | DZ400EU (MAX Dual Zone 9,5 L) | Gebrauchsanweisung | EN, FR, DE und weitere | [ninja/dz400eu/gebrauchsanweisung.pdf](ninja/dz400eu/gebrauchsanweisung.pdf) | SharkNinja-Supportseite (support.sharkninja.de, Produkt AF400EU/DZ400EU, „Bedienungsanleitungen“) | 09.10.2026 |
| Ninja | AF400EU (Foodi MAX Dual Zone 9,5 L) | Schnellstart- und Rezeptanleitung | EN, DE, FR | [ninja/af400eu/schnellstart-rezeptanleitung.pdf](ninja/af400eu/schnellstart-rezeptanleitung.pdf) | Von Florian per Google-Suche gefunden (Originaldatei „8263AF400EU-4.pdf“), Herkunftsseite nicht notiert | 10.10.2026 |
| Ninja | AF300EU (Foodi Dual Zone 7,6 L) | Schnellstartanleitung mit Kochtabellen und Rezepten | DE, FR | [ninja/af300eu/schnellstartanleitung.pdf](ninja/af300eu/schnellstartanleitung.pdf) | Händlerseite shop.computerworks.ch (Originaldatei „DE_AF300_0.pdf“), von Florian heruntergeladen | 10.10.2026 |
| Ninja | AF140EU (PRO 4,7 L) | Schnellstart- und Rezeptanleitung | EN, DE, FR | [ninja/af140eu/schnellstart-rezeptanleitung.pdf](ninja/af140eu/schnellstart-rezeptanleitung.pdf) | Von Florian per Google-Suche gefunden (Originaldatei „media.pdf“), Herkunftsseite nicht notiert | 10.10.2026 |
| Pampered Chef | Deluxe Air Fryer | Rezeptheft | DE | [pampered-chef/deluxe-air-fryer/rezeptheft.pdf](pampered-chef/deluxe-air-fryer/rezeptheft.pdf) | Von Florian per Google-Suche gefunden (Originaldatei „PDF-Rezeptheft-Deluxe-Air-Fryer.pdf“), Herkunftsseite nicht notiert | 10.10.2026 |

## Prüfstand

Zuletzt geprüft: 10.10.2026, alle 6 Dateien.

- **Sprache:** Jede Datei enthält einen deutschen Teil. Keine Datei liegt nur in einer Sprache vor, die wir nicht brauchen.
- **Doppelte Dateien:** Keine. Alle Dateien unterscheiden sich im Inhalt (Prüfsummen verglichen).
- **Doppelte Hefte je Gerät:** Keine. Pro Modell gibt es jede Dokumentart höchstens einmal.
- **Überschneidung bei Rezepten:** Die Ninja-Hefte teilen sich Rezepte. Von den 30 Rezepten der DZ400EU stehen 18 auch im AF400EU-Heft, 16 im AF300EU-Heft und 2 im AF140EU-Heft. Die Hefte bleiben trotzdem alle erhalten, weil Kochtabellen und Mengen je Gerät abweichen. Doppelte Rezepte werden beim Einarbeiten in Fritti zusammengeführt.
- **Noch offen:** Gerätedaten in den `modell.json` (Liter, Körbe, Watt) sind bei AF300EU, AF400EU und AF140EU noch nicht gegen ein Handbuch geprüft; beim Pampered Chef fehlen Volumen und Leistung. Gebrauchsanweisungen gibt es bisher nur zur DZ400EU.

## Regeln für dieses Repo

- Diese README ist immer aktuell. Wer eine PDF hinzufügt, verschiebt oder löscht, passt im selben Schritt die Tabelle „Inhalt“, die Zeile „Stand“ und den Abschnitt „Prüfstand“ an.
- Vor dem Ablegen prüfen: Enthält die Datei Deutsch? Gibt es dieselbe Datei oder dasselbe Heft für dieses Gerät schon? Wenn ja, nicht noch einmal ablegen.
- Dateien, die nur in einer nicht benötigten Sprache vorliegen oder doppelt sind, werden wieder entfernt.

## Direktlinks

Über GitHub Pages (falls aktiviert) sind die Dateien unter
`https://thetraderflow.github.io/AirFryer-Manuals-and-more/<marke>/<modell>/<datei>.pdf` erreichbar.
Ohne Pages: `https://raw.githubusercontent.com/TheTraderFlow/AirFryer-Manuals-and-more/main/<marke>/<modell>/<datei>.pdf`.

Alle Rechte an den Dokumenten liegen bei den jeweiligen Herstellern.
