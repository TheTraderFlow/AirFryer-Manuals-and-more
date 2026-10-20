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

Stand: 20.10.2026 – 72 PDF-Dateien, 57 Modelle, 15 Marken.

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
| Caso | Caso AirFry & Steam 700 | AirFry & Steam Kochbuch | DE, EN | [caso/airfry-steam-700/kochbuch.pdf](caso/airfry-steam-700/kochbuch.pdf) | caso-design.de, Produkt AirFry & Steam 700 | 20.10.2026 |
| Gastroback | Gastroback Heat & Crisp Family 8 L / Duo Family 9 L | Rezeptheft für Gastroback Heißluftfritteusen | DE | [gastroback/42585/rezeptheft.pdf](gastroback/42585/rezeptheft.pdf) | gastroback.de, Produktseiten 42585 und 42586 | 20.10.2026 |
| Ambiano | Ambiano Heißluftfritteuse GT-AF-07 | Rezeptbuch | DE | [ambiano/gt-af-07/rezeptbuch.pdf](ambiano/gt-af-07/rezeptbuch.pdf) | gt-support.de (Globaltronics, Aldi-Eigenmarke) | 20.10.2026 |
| Ambiano | Ambiano XXL Heißluftfritteuse GT-AF-08 | Rezeptbuch | DE | [ambiano/gt-af-08/rezeptbuch.pdf](ambiano/gt-af-08/rezeptbuch.pdf) | gt-support.de (Globaltronics, Aldi-Eigenmarke) | 20.10.2026 |
| Ambiano | Ambiano Doppelkorb-Heißluftfritteuse GT-DAF-01 | Rezeptbuch | DE | [ambiano/gt-daf-01/rezeptbuch.pdf](ambiano/gt-daf-01/rezeptbuch.pdf) | gt-support.de (Globaltronics, Aldi-Eigenmarke) | 20.10.2026 |
| Tchibo | Tchibo Digitale Heißluft-Fritteuse | Rezepte | DE | [tchibo/618161/rezeptheft.pdf](tchibo/618161/rezeptheft.pdf) | tchibo.de/anleitungen | 20.10.2026 |
| Tchibo | Tchibo Heißluft-Fritteuse | Gebrauchsanweisung mit Garzeiten-Tabelle | DE | [tchibo/201363/gebrauchsanweisung.pdf](tchibo/201363/gebrauchsanweisung.pdf) | tchibo.de, Produkt Heißluft-Fritteuse | 20.10.2026 |
| Tchibo | Tchibo Mini-Heißluft-Fritteuse | Gebrauchsanweisung mit Rezepten | DE | [tchibo/97302/gebrauchsanweisung.pdf](tchibo/97302/gebrauchsanweisung.pdf) | tchibo.de/anleitungen | 20.10.2026 |
| Tchibo | Tchibo Digitale Heißluft-Fritteuse (2020) | Gebrauchsanweisung | DE | [tchibo/109215/gebrauchsanweisung.pdf](tchibo/109215/gebrauchsanweisung.pdf) | tchibo.de/anleitungen | 20.10.2026 |
| Sage | Sage the Smart Oven Air Fryer | Rezept-E-Book | DE | [sage/sov860/rezeptheft.pdf](sage/sov860/rezeptheft.pdf) | sageappliances.com/de-de, Produkt BOV860 | 20.10.2026 |
| Sage | Sage the Combi Wave 3 in 1 | Rezeptkarten | DE | [sage/smo870/rezeptkarten.pdf](sage/smo870/rezeptkarten.pdf) | sageappliances.com/de-de, Produkt BMO870 | 20.10.2026 |
| Tefal | Tefal Easy Fry Oven & Grill | Rezeptbuch | DE | [tefal/fw5018/rezeptbuch.pdf](tefal/fw5018/rezeptbuch.pdf) | tefal.de, Produkt FW5018 | 20.10.2026 |
| Tefal | Tefal Easy Fry Deluxe | Benutzerhandbuch mit Garzeiten-Tabelle | DE | [tefal/ey401d/gebrauchsanweisung.pdf](tefal/ey401d/gebrauchsanweisung.pdf) | tefal.de, Produkt EY401D | 20.10.2026 |
| Bosch | Bosch Airfryer Serie 6 (MAF671) | Gebrauchsanleitung mit Anwendungsbeispielen | mehrsprachig mit DE | [bosch/maf671/gebrauchsanweisung.pdf](bosch/maf671/gebrauchsanweisung.pdf) | bosch-home.com, Produkt MAF671B1 | 20.10.2026 |
| Bosch | Bosch Doppelkammer-Airfryer (MAFD661) | Gebrauchsanleitung mit Anwendungsbeispielen | mehrsprachig mit DE | [bosch/mafd661/gebrauchsanweisung.pdf](bosch/mafd661/gebrauchsanweisung.pdf) | bosch-home.com, Produkt MAFD661B0 | 20.10.2026 |
| Bosch | Bosch Airfryer (MAFS2462) | Gebrauchsanleitung mit Anwendungsbeispielen | mehrsprachig mit DE | [bosch/mafs2462/gebrauchsanweisung.pdf](bosch/mafs2462/gebrauchsanweisung.pdf) | bosch-home.com, Produkt MAFS2462B | 20.10.2026 |
| Klarstein | Klarstein AeroVital Fry | Bedienungsanleitung mit Rezepten | mehrsprachig mit DE | [klarstein/10034575/gebrauchsanweisung.pdf](klarstein/10034575/gebrauchsanweisung.pdf) | Hersteller-Ablage Chal-Tec (res.cloudinary.com/chal-tec) | 20.10.2026 |
| Klarstein | Klarstein VitAir Pommesmaster | Bedienungsanleitung mit Zubereitungstabelle | mehrsprachig mit DE | [klarstein/10034528/gebrauchsanweisung.pdf](klarstein/10034528/gebrauchsanweisung.pdf) | Hersteller-Ablage Chal-Tec (res.cloudinary.com/chal-tec) | 20.10.2026 |
| Klarstein | Klarstein AeroVital | Bedienungsanleitung mit Tabelle für das Luftgaren | mehrsprachig mit DE | [klarstein/10032848/gebrauchsanweisung.pdf](klarstein/10032848/gebrauchsanweisung.pdf) | Hersteller-Ablage Chal-Tec (res.cloudinary.com/chal-tec) | 20.10.2026 |
| Klarstein | Klarstein AirVital | Bedienungsanleitung mit Zutatentabelle | mehrsprachig mit DE | [klarstein/10032331/gebrauchsanweisung.pdf](klarstein/10032331/gebrauchsanweisung.pdf) | Hersteller-Ablage Chal-Tec (res.cloudinary.com/chal-tec) | 20.10.2026 |
| Klarstein | Klarstein Vigor Air | Bedienungsanleitung mit Gartabellen | mehrsprachig mit DE | [klarstein/10039941/gebrauchsanweisung.pdf](klarstein/10039941/gebrauchsanweisung.pdf) | Hersteller-Ablage Chal-Tec (res.cloudinary.com/chal-tec) | 20.10.2026 |
| Klarstein | Klarstein VitAir Smart | Bedienungsanleitung mit empfohlenen Einstellungen | mehrsprachig mit DE | [klarstein/10035590/gebrauchsanweisung.pdf](klarstein/10035590/gebrauchsanweisung.pdf) | Hersteller-Ablage Chal-Tec (res.cloudinary.com/chal-tec) | 20.10.2026 |
| Midea | Midea Air Fryer MF-CN55A | Bedienungsanleitung | DE | [midea/mf-cn55a/gebrauchsanweisung.pdf](midea/mf-cn55a/gebrauchsanweisung.pdf) | midea.com/de, Produkt MF-CN55A2 | 20.10.2026 |
| Midea | Midea Air Fryer MF-CY75A2 | Bedienungsanleitung | DE | [midea/mf-cy75a2/gebrauchsanweisung.pdf](midea/mf-cy75a2/gebrauchsanweisung.pdf) | midea.com/de | 20.10.2026 |
| Zwilling | Zwilling Heißluftfritteuse 4 l | Bedienungsanleitung (ohne Garzeiten) | mehrsprachig mit DE | [zwilling/36450/gebrauchsanweisung.pdf](zwilling/36450/gebrauchsanweisung.pdf) | zwilling.com/de | 20.10.2026 |
| Silvercrest | Silvercrest Heißluftfritteuse SHFD 1000 A1 | Bedienungsanleitung mit Rezeptheft | DE (mehrsprachige Ausgabe) | [silvercrest/shfd1000a1/gebrauchsanweisung.pdf](silvercrest/shfd1000a1/gebrauchsanweisung.pdf) | lidl.de Produktseite (manuals.sit-connect.com) | 20.10.2026 |
| Silvercrest | Silvercrest Heißluftfritteuse SHFD 1400 C1 | Bedienungsanleitung mit Rezeptheft | DE (mehrsprachige Ausgabe) | [silvercrest/shfd1400c1/gebrauchsanweisung.pdf](silvercrest/shfd1400c1/gebrauchsanweisung.pdf) | lidl.de Produktseite (manuals.sit-connect.com) | 20.10.2026 |
| Silvercrest | Silvercrest Heißluftfritteuse SHFD 2000 D2 | Bedienungsanleitung mit Rezeptheft | DE (mehrsprachige Ausgabe) | [silvercrest/shfd2000d2/gebrauchsanweisung.pdf](silvercrest/shfd2000d2/gebrauchsanweisung.pdf) | lidl.de Produktseite (manuals.sit-connect.com) | 20.10.2026 |
| Silvercrest | Silvercrest Tower Air Fryer SHFDV 2470 A1 | Bedienungsanleitung mit Rezeptheft | DE (mehrsprachige Ausgabe) | [silvercrest/shfdv2470a1/gebrauchsanweisung.pdf](silvercrest/shfdv2470a1/gebrauchsanweisung.pdf) | lidl.de Produktseite (manuals.sit-connect.com) | 20.10.2026 |
| Silvercrest | Silvercrest Heißluftfritteuse SHFD 2150 B1 | Bedienungsanleitung mit Rezeptheft | DE (mehrsprachige Ausgabe) | [silvercrest/shfd2150b1/gebrauchsanweisung.pdf](silvercrest/shfd2150b1/gebrauchsanweisung.pdf) | lidl.de Produktseite (manuals.sit-connect.com) | 20.10.2026 |
| Silvercrest | Silvercrest Heißluftfritteuse SHFD 2150 B2 | Bedienungsanleitung mit Rezeptheft | DE (mehrsprachige Ausgabe) | [silvercrest/shfd2150b2/gebrauchsanweisung.pdf](silvercrest/shfd2150b2/gebrauchsanweisung.pdf) | lidl.de Produktseite (manuals.sit-connect.com) | 20.10.2026 |
| Silvercrest | Silvercrest Ultrazone Airfryer SHFDA 2600 A1 | Bedienungsanleitung mit Rezeptheft | DE (mehrsprachige Ausgabe) | [silvercrest/shfda2600a1/gebrauchsanweisung.pdf](silvercrest/shfda2600a1/gebrauchsanweisung.pdf) | lidl.de Produktseite (manuals.sit-connect.com) | 20.10.2026 |
| Silvercrest | Silvercrest Heißluftfritteuse mit Grill SHFG 2460 A1 | Bedienungsanleitung mit Rezeptheft | DE (mehrsprachige Ausgabe) | [silvercrest/shfg2460a1/gebrauchsanweisung.pdf](silvercrest/shfg2460a1/gebrauchsanweisung.pdf) | lidl.de Produktseite (manuals.sit-connect.com) | 20.10.2026 |
| Silvercrest | Silvercrest Glas-Heißluftfritteuse SHFDG 1500 A1 | Bedienungsanleitung mit Rezeptheft | DE (mehrsprachige Ausgabe) | [silvercrest/shfdg1500a1/gebrauchsanweisung.pdf](silvercrest/shfdg1500a1/gebrauchsanweisung.pdf) | lidl.de Produktseite (manuals.sit-connect.com) | 20.10.2026 |
| Ninja | Ninja Heißluftfritteuse AF100EU | Schnellstart- und Rezeptanleitung | mehrsprachig mit DE | [ninja/af100eu/schnellstart-rezeptanleitung.pdf](ninja/af100eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Heißluftfritteuse MAX 5,2 L | Schnellstartanleitung mit Rezepten | mehrsprachig mit DE | [ninja/af160eu/schnellstart-rezeptanleitung.pdf](ninja/af160eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Heißluftfritteuse MAX PRO | Inspirationsheft mit Kochtabellen und Rezepten | mehrsprachig mit DE | [ninja/af170eu/schnellstart-rezeptanleitung.pdf](ninja/af170eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Heißluftfritteuse Max Pro (AF180DE) | Kurzanleitung und Rezeptbuch | mehrsprachig mit DE | [ninja/af180de/schnellstart-rezeptanleitung.pdf](ninja/af180de/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Heißluftfritteuse AF200EU | Schnellstart- und Rezeptanleitung | mehrsprachig mit DE | [ninja/af200eu/schnellstart-rezeptanleitung.pdf](ninja/af200eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi MAX Dual Zone mit Thermometer | Kurzanleitung und Rezeptbuch | mehrsprachig mit DE | [ninja/af451eu/schnellstart-rezeptanleitung.pdf](ninja/af451eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja CRISPi Glas-Heißluftfritteuse | Schnellstart- und Rezeptanleitung | mehrsprachig mit DE | [ninja/fn101eu/schnellstart-rezeptanleitung.pdf](ninja/fn101eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Double Stack | Schnellstart- und Rezeptanleitung | mehrsprachig mit DE | [ninja/sl300eu/schnellstart-rezeptanleitung.pdf](ninja/sl300eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Double Stack XL | Schnellstart- und Rezeptanleitung | mehrsprachig mit DE | [ninja/sl400eu/schnellstart-rezeptanleitung.pdf](ninja/sl400eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi FlexDrawer DZ801EU | Schnellstart- und Rezeptanleitung | mehrsprachig mit DE | [ninja/dz801eu/schnellstart-rezeptanleitung.pdf](ninja/dz801eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi MAX Dual Zone DZ901EU | Schnellstart- und Rezeptanleitung | mehrsprachig mit DE | [ninja/dz901eu/schnellstart-rezeptanleitung.pdf](ninja/dz901eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja CRISPi PRO 7-in-1 | Schnellstart- und Rezeptanleitung | mehrsprachig mit DE | [ninja/as101eu/schnellstart-rezeptanleitung.pdf](ninja/as101eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi Grill & Heißluftfritteuse | Rezeptbuch | mehrsprachig mit DE | [ninja/ag301eu/schnellstart-rezeptanleitung.pdf](ninja/ag301eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi MAX PRO Grill & Heißluftfritteuse | Rezeptbuch | mehrsprachig mit DE | [ninja/ag651eu/schnellstart-rezeptanleitung.pdf](ninja/ag651eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi MAX Grill & Heißluftfritteuse | Schnellstartanleitung mit Rezepten | mehrsprachig mit DE | [ninja/dg551eu/schnellstart-rezeptanleitung.pdf](ninja/dg551eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Speedi Rapid Cooking System & Heißluftfritteuse | Kurzanleitung und Rezeptbuch | mehrsprachig mit DE | [ninja/on400de/schnellstart-rezeptanleitung.pdf](ninja/on400de/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi 11-in-1 SmartLid Multikocher | Rezeptbuch | mehrsprachig mit DE | [ninja/ol550eu/schnellstart-rezeptanleitung.pdf](ninja/ol550eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi MAX 12-in-1 SmartLid Multikocher | Rezeptbuch | mehrsprachig mit DE | [ninja/ol650eu/schnellstart-rezeptanleitung.pdf](ninja/ol650eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi MAX 14-in-1 SmartLid Multikocher | Rezeptbuch | mehrsprachig mit DE | [ninja/ol750eu/schnellstart-rezeptanleitung.pdf](ninja/ol750eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi Multikocher | Rezeptbuch | mehrsprachig mit DE | [ninja/op300eu/schnellstart-rezeptanleitung.pdf](ninja/op300eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi MAX Multikocher | Rezeptbuch | mehrsprachig mit DE | [ninja/op500eu/schnellstart-rezeptanleitung.pdf](ninja/op500eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi 8-in-1 Multifunktionsofen | Rezeptbuch | mehrsprachig mit DE | [ninja/sp101eu/schnellstart-rezeptanleitung.pdf](ninja/sp101eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Foodi 10-in-1 XL Multifunktionsofen | Inspirationsheft mit Rezepten | mehrsprachig mit DE | [ninja/dt200eu/schnellstart-rezeptanleitung.pdf](ninja/dt200eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |
| Ninja | Ninja Combi 12-in-1 Multikocher | Schnellstart- und Rezeptanleitung | mehrsprachig mit DE | [ninja/sfp700eu/schnellstart-rezeptanleitung.pdf](ninja/sfp700eu/schnellstart-rezeptanleitung.pdf) | SharkNinja-Supportseite support.sharkninja.de | 20.10.2026 |

## Prüfstand

Zuletzt geprüft: 20.10.2026, alle 72 Dateien.

- **Sprache:** Jede Datei enthält einen deutschen Teil. Keine Datei liegt nur in einer Sprache vor, die wir nicht brauchen.
- **Doppelte Dateien:** Keine. Alle Dateien unterscheiden sich im Inhalt (Prüfsummen verglichen).
- **Doppelte Hefte je Gerät:** Keine. Pro Modell gibt es jede Dokumentart höchstens einmal.
- **Aussortiert am 10.10.2026:** Beim AF500EU lag die Gebrauchsanweisung doppelt vor, einmal als eigene deutsche Datei und einmal als mehrsprachiger Anhang (Seiten 22–134) der Otto-Datei. Behalten wurde die deutsche Einzeldatei; aus der Otto-Datei sind nur die Seiten 1–21 (Kurzanleitung, Kochtabellen, Rezepte) abgelegt.
- **Ähnliche Hefte verschiedener Geräte:** Die deutsche Gebrauchsanweisung der AF400EU stimmt zu rund 84 % mit der der DZ400EU überein (Vorgänger und Nachfolger). Beide bleiben, weil sie zu verschiedenen Geräten gehören.
- **Überschneidung bei Rezepten:** Die Ninja-Hefte teilen sich Rezepte. Von den 30 Rezepten der DZ400EU stehen 18 auch im AF400EU-Heft, 16 im AF300EU-Heft und 2 im AF140EU-Heft. Die Hefte bleiben trotzdem alle erhalten, weil Kochtabellen und Mengen je Gerät abweichen. Doppelte Rezepte werden beim Einarbeiten in Fritti zusammengeführt. Das AF500EU-Heft ist darauf noch nicht geprüft.
- **Gerätedaten:** Leistung bei AF400EU, AF500EU, SL400EU (je 2470 W) und AF160EU (1750 W) aus den Gebrauchsanweisungen bestätigt. Noch ungeprüft: AF300EU und AF140EU (keine Gebrauchsanweisung vorhanden), Volumen der AF160EU; beim Pampered Chef fehlen Volumen und Leistung.
- **Neu am 20.10.2026 (noch nicht in Fritti eingearbeitet):** Rezepthefte von Tefal (EY505D), Rommelsbacher (FRH 1500/1700) und Caso (AirFry-Reihe), jeweils direkt von der Herstellerseite. Das Tefal-Heft nennt selbst kein Modell; die Zuordnung zum EY505D stammt von der Tefal-Produktseite. Das Rommelsbacher- und das Caso-Heft gelten für mehrere Geräte; abgelegt sind sie unter dem ersten genannten Modell. Ob die Hefte Kochtabellen enthalten und für welche Geräte in Fritti Einträge entstehen, wird beim Einarbeiten geklärt. Gerätedaten (Körbe, Volumen, Leistung) fehlen noch.
- **Zweite Ladung am 20.10.2026:** 60 weitere Dokumente von Herstellerseiten (Ninja-Supportseite, Caso, Gastroback, Globaltronics/Ambiano, Tchibo, Sage, Tefal, Bosch, Klarstein, Silvercrest/Lidl, Midea, Zwilling). Alle enthalten einen deutschen Teil (geprüft am Seitentext). Bei Silvercrest ist jeweils die Ausgabe „_1“ abgelegt (deutscher Teil mit Rezeptheft); die mehrsprachige Ausgabe „_OS“ enthält dieselben Inhalte und fehlt bewusst. Die drei Ambiano-Rezeptbücher sind zu über 99 % gleich, ebenso Ninja SL300EU und SL400EU; sie bleiben, weil sie zu verschiedenen Geräten gehören. Die Datei für Silvercrest „Heißluftfritteuse Digital 4,7 l“ (Lidl 100408836) war Byte für Byte gleich der SHFD 2000 D2 und ist deshalb nur dort abgelegt. Die zuerst bei Tchibo 618161 abgelegte Anleitung gehörte zu einem anderen Gerät (Artikel 11822, AF9001TH-GS) und ist entfernt. Zwilling 36450 sowie Midea MF-CN55A und MF-CY75A2 enthalten keine Garzeiten-Tabelle und keine Rezepte; sie bleiben als Bedienungsanleitungen hier, ergeben in Fritti aber kein Gerät. Nicht ladbar: Grundig FRY 6840 Kochbuch (Server sperrt automatische Abrufe).
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
