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

Stand: 20.10.2026 – 14 PDF-Dateien, 11 Modelle, 5 Marken.

| Marke | Modell | Dokument | Sprachen | Datei | Herkunft | Abgerufen |
|---|---|---|---|---|---|---|
| Ninja | DZ400EU (MAX Dual Zone 9,5 L) | Schnellstart- und Rezeptanleitung | EN, DE, FR | [ninja/dz400eu/schnellstart-rezeptanleitung.pdf](ninja/dz400eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite (support.sharkninja.fr, Produkt AF400EU/DZ400EU, „Guides de démarrage rapide“) | 09.10.2026 |
| Ninja | DZ400EU (MAX Dual Zone 9,5 L) | Gebrauchsanweisung | EN, FR, DE und weitere | [ninja/dz400eu/gebrauchsanweisung.pdf](ninja/dz400eu/gebrauchsanweisung.pdf) | SharkNinja-Supportseite (support.sharkninja.de, Produkt AF400EU/DZ400EU, „Bedienungsanleitungen“) | 09.10.2026 |
| Ninja | AF400EU (Foodi MAX Dual Zone 9,5 L) | Schnellstart- und Rezeptanleitung | EN, DE, FR | [ninja/af400eu/schnellstart-rezeptanleitung.pdf](ninja/af400eu/schnellstart-rezeptanleitung.pdf) | Von Florian per Google-Suche gefunden (Originaldatei „8263AF400EU-4.pdf“), Herkunftsseite nicht notiert | 10.10.2026 |
| Ninja | AF400EU (Foodi MAX Dual Zone 9,5 L) | Gebrauchsanweisung (deutscher Teil) | DE | [ninja/af400eu/gebrauchsanweisung.pdf](ninja/af400eu/gebrauchsanweisung.pdf) | Händlerseite media.hoeffner.de (Originaldatei „46151277_3-202509090910.pdf“), von Florian heruntergeladen | 10.10.2026 |
| Ninja | AF300EU (Foodi Dual Zone 7,6 L) | Schnellstartanleitung mit Kochtabellen und Rezepten | DE, FR | [ninja/af300eu/schnellstartanleitung.pdf](ninja/af300eu/schnellstartanleitung.pdf) | Händlerseite shop.computerworks.ch (Originaldatei „DE_AF300_0.pdf“), von Florian heruntergeladen | 10.10.2026 |
| Ninja | AF140EU (PRO 4,7 L) | Schnellstart- und Rezeptanleitung | EN, DE, FR | [ninja/af140eu/schnellstart-rezeptanleitung.pdf](ninja/af140eu/schnellstart-rezeptanleitung.pdf) | Von Florian per Google-Suche gefunden (Originaldatei „media.pdf“), Herkunftsseite nicht notiert | 10.10.2026 |
| Ninja | AF500EU (Foodi FlexDrawer 10,4 L) | Kurzanleitung mit Kochtabellen und Rezepten | DE | [ninja/af500eu/schnellstart-rezeptanleitung.pdf](ninja/af500eu/schnellstart-rezeptanleitung.pdf) | Händlerseite d.otto.de (Originaldatei „6ce7dace-f349-5d67-8588-4f52695f3d61.pdf“, 134 Seiten). Abgelegt sind nur die Seiten 1–21; der Rest war die mehrsprachige Gebrauchsanweisung | 10.10.2026 |
| Ninja | AF500EU (Foodi FlexDrawer 10,4 L) | Gebrauchsanweisung (Ausgabe AF500DE) | DE | [ninja/af500eu/gebrauchsanweisung.pdf](ninja/af500eu/gebrauchsanweisung.pdf) | Geizhals-Dateiablage gzhls.at (Originaldatei „9cbfa49bc1ab50e9e73b371dfb7c0cf5f441.pdf“), von Florian heruntergeladen | 10.10.2026 |
| Ninja | SL400EU (Double Stack XL 9,5 L) | Gebrauchsanweisung | DA, DE, EN, ES, FR, IT, NL, NO, PT, FI, SV | [ninja/sl400eu/gebrauchsanweisung.pdf](ninja/sl400eu/gebrauchsanweisung.pdf) | Händlerseite d.otto.de (Originaldatei „9b91e902-d9b0-5dab-8173-2f513e52376e.pdf“), von Florian heruntergeladen | 10.10.2026 |
| Ninja | AF160EU (Air Fryer MAX 5,2 L) | Gebrauchsanweisung | DA, DE, EN, ES, FR, IT, NL, NO, FI, SV | [ninja/af160eu/gebrauchsanweisung.pdf](ninja/af160eu/gebrauchsanweisung.pdf) | Geizhals-Dateiablage gzhls.at (Originaldatei „c2c1a6d7d753ac6a175df2e65f9b5a20b690.pdf“), von Florian heruntergeladen | 10.10.2026 |
| Pampered Chef | Deluxe Air Fryer | Rezeptheft | DE | [pampered-chef/deluxe-air-fryer/rezeptheft.pdf](pampered-chef/deluxe-air-fryer/rezeptheft.pdf) | Von Florian per Google-Suche gefunden (Originaldatei „PDF-Rezeptheft-Deluxe-Air-Fryer.pdf“), Herkunftsseite nicht notiert | 10.10.2026 |
| Tefal | EY505D (Easy Fry & Grill Deluxe) | Rezeptheft | DE | [tefal/ey505d/rezeptheft.pdf](tefal/ey505d/rezeptheft.pdf) | Herstellerseite tefal.de, Produkt EY505D (Datei auf dam.groupeseb.com, Originaldatei „Easy-Fry-Grill_Rezeptheft.pdf“) | 20.10.2026 |
| Rommelsbacher | FRH 1500 / FRH 1700 | Rezeptheft | DE | [rommelsbacher/frh1500/rezeptheft.pdf](rommelsbacher/frh1500/rezeptheft.pdf) | Herstellerseite rommelsbacher.de → Service → Downloads (Originaldatei „ROMMELSBACHER-Rezeptheft-Heissluftfritteusen.pdf“) | 20.10.2026 |
| Caso | AirFry 6.0 (3185), DuoChef (3186), DuoTower (3189), PizzaChef (3191) | Kochbuch | DE, EN | [caso/airfry-6-0/kochbuch.pdf](caso/airfry-6-0/kochbuch.pdf) | Herstellerseite caso-design.de, Produkt AirFry 6.0 (Originaldatei „202607_kochbuch_af_a5_screen.pdf“) | 20.10.2026 |

## Prüfstand

Zuletzt geprüft: 20.10.2026, alle 14 Dateien.

- **Sprache:** Jede Datei enthält einen deutschen Teil. Keine Datei liegt nur in einer Sprache vor, die wir nicht brauchen.
- **Doppelte Dateien:** Keine. Alle Dateien unterscheiden sich im Inhalt (Prüfsummen verglichen).
- **Doppelte Hefte je Gerät:** Keine. Pro Modell gibt es jede Dokumentart höchstens einmal.
- **Aussortiert am 10.10.2026:** Beim AF500EU lag die Gebrauchsanweisung doppelt vor, einmal als eigene deutsche Datei und einmal als mehrsprachiger Anhang (Seiten 22–134) der Otto-Datei. Behalten wurde die deutsche Einzeldatei; aus der Otto-Datei sind nur die Seiten 1–21 (Kurzanleitung, Kochtabellen, Rezepte) abgelegt.
- **Ähnliche Hefte verschiedener Geräte:** Die deutsche Gebrauchsanweisung der AF400EU stimmt zu rund 84 % mit der der DZ400EU überein (Vorgänger und Nachfolger). Beide bleiben, weil sie zu verschiedenen Geräten gehören.
- **Überschneidung bei Rezepten:** Die Ninja-Hefte teilen sich Rezepte. Von den 30 Rezepten der DZ400EU stehen 18 auch im AF400EU-Heft, 16 im AF300EU-Heft und 2 im AF140EU-Heft. Die Hefte bleiben trotzdem alle erhalten, weil Kochtabellen und Mengen je Gerät abweichen. Doppelte Rezepte werden beim Einarbeiten in Fritti zusammengeführt. Das AF500EU-Heft ist darauf noch nicht geprüft.
- **Gerätedaten:** Leistung bei AF400EU, AF500EU, SL400EU (je 2470 W) und AF160EU (1750 W) aus den Gebrauchsanweisungen bestätigt. Noch ungeprüft: AF300EU und AF140EU (keine Gebrauchsanweisung vorhanden), Volumen der AF160EU; beim Pampered Chef fehlen Volumen und Leistung.
- **Neu am 20.10.2026 (noch nicht in Fritti eingearbeitet):** Rezepthefte von Tefal (EY505D), Rommelsbacher (FRH 1500/1700) und Caso (AirFry-Reihe), jeweils direkt von der Herstellerseite. Das Tefal-Heft nennt selbst kein Modell; die Zuordnung zum EY505D stammt von der Tefal-Produktseite. Das Rommelsbacher- und das Caso-Heft gelten für mehrere Geräte; abgelegt sind sie unter dem ersten genannten Modell. Ob die Hefte Kochtabellen enthalten und für welche Geräte in Fritti Einträge entstehen, wird beim Einarbeiten geklärt. Gerätedaten (Körbe, Volumen, Leistung) fehlen noch.
- **Es fehlt noch:** Gebrauchsanweisung für AF300EU und AF140EU; Schnellstart-/Rezeptanleitung für SL400EU und AF160EU.

## Regeln für dieses Repo

- Diese README ist immer aktuell. Wer eine PDF hinzufügt, verschiebt oder löscht, passt im selben Schritt die Tabelle „Inhalt“, die Zeile „Stand“ und den Abschnitt „Prüfstand“ an.
- Vor dem Ablegen prüfen: Enthält die Datei Deutsch? Gibt es dieselbe Datei oder dasselbe Heft für dieses Gerät schon? Wenn ja, nicht noch einmal ablegen.
- Dateien, die nur in einer nicht benötigten Sprache vorliegen oder doppelt sind, werden wieder entfernt.

## Direktlinks

Über GitHub Pages (falls aktiviert) sind die Dateien unter
`https://thetraderflow.github.io/AirFryer-Manuals-and-more/<marke>/<modell>/<datei>.pdf` erreichbar.
Ohne Pages: `https://raw.githubusercontent.com/TheTraderFlow/AirFryer-Manuals-and-more/main/<marke>/<modell>/<datei>.pdf`.

Alle Rechte an den Dokumenten liegen bei den jeweiligen Herstellern.
