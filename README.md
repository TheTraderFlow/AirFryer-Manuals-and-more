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

| Marke | Modell | Dokument | Datei | Herkunft | Abgerufen |
|---|---|---|---|---|---|
| Ninja | DZ400EU (MAX Dual Zone 9,5 L) | Schnellstart- und Rezeptanleitung | [ninja/dz400eu/schnellstart-rezeptanleitung.pdf](ninja/dz400eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite (support.sharkninja.fr, Produkt AF400EU/DZ400EU, „Guides de démarrage rapide“) | 09.10.2026 |
| Ninja | DZ400EU (MAX Dual Zone 9,5 L) | Gebrauchsanweisung | [ninja/dz400eu/gebrauchsanweisung.pdf](ninja/dz400eu/gebrauchsanweisung.pdf) | SharkNinja-Supportseite (support.sharkninja.de, Produkt AF400EU/DZ400EU, „Bedienungsanleitungen“) | 09.10.2026 |

## Direktlinks

Über GitHub Pages (falls aktiviert) sind die Dateien unter
`https://thetraderflow.github.io/AirFryer-Manuals-and-more/<marke>/<modell>/<datei>.pdf` erreichbar.
Ohne Pages: `https://raw.githubusercontent.com/TheTraderFlow/AirFryer-Manuals-and-more/main/<marke>/<modell>/<datei>.pdf`.

Alle Rechte an den Dokumenten liegen bei den jeweiligen Herstellern.
