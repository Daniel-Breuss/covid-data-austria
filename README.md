# covid-data-austria
Zwei Dateien, einmal im CSV- und einmal im JSON-Format, die tagesaktuelle Covid19-Daten aus Österreich beinhalten.

Basiert auf denselben Daten, die als Basis für dieses [Covid19-Dashboard](https://covid19.danielbreuss.com/) dienen.

## Datenquellen für diese Aggregation
https://info.gesundheitsministerium.at/

https://www.sozialministerium.at/Informationen-zum-Coronavirus/Neuartiges-Coronavirus-(2019-nCov).html

https://www.bmi.gv.at/news.aspx?id=4A7171477A51625143334D3D



## Struktur der Spalten / Objekte
Datum,Fälle_gesamt,Fälle_Zuwachs,Tote_v1,Tote_v1_Zuwachs,Tote_v2,Tote_v2_Zuwachs,Genesene,Genesene_Zuwachs,Hospitalisiert,Intensivstation,IBett_frei,IBett_Kapazität,Testungen,Testungen_Zuwachs,Burgenland,Burgenland_Tote,Burgenland_Genesene,Burgenland_Spital,Burgenland_Intensiv,Burgenland_Tests,Kärnten,Kärnten_Tote,Kärnten_Genesene,Kärnten_Spital,Kärnten_Intensiv,Kärnten_Tests,Niederösterreich,Niederösterreich_Tote,Niederösterreich_Genesene,Niederösterreich_Spital,Niederösterreich_Intensiv,Niederösterreich_Tests,Oberösterreich,Oberösterreich_Tote,Oberösterreich_Genesene,Oberösterreich_Spital,Oberösterreich_Intensiv,Oberösterreich_Tests,Salzburg,Salzburg_Tote,Salzburg_Genesene,Salzburg_Spital,Salzburg_Intensiv,Salzburg_Tests,Steiermark,Steiermark_Tote,Steiermark_Genesene,Steiermark_Spital,Steiermark_Intensiv,Steiermark_Tests,Tirol,Tirol_Tote,Tirol_Genesene,Tirol_Spital,Tirol_Intensiv,Tirol_Tests,Vorarlberg,Vorarlberg_Tote,Vorarlberg_Genesene,Vorarlberg_Spital,Vorarlberg_Intensiv,Vorarlberg_Tests,Wien,Wien_Tote,Wien_Genesene,Wien_Spital,Wien_Intensiv,Wien_Tests

## Erläuterungen
- **Datum** = selbsterklärend
- **Fälle_gesamt** = Anzahl der bisher positiv getesteten Personen in ganz Österreich - Stand jeweils 8:00
- **Fälle_Zuwachs** = Differenz zum Vortag zur selben Uhrzeit
- **Tote_v1** = Gesamtanzahl der Personen, die gestorben sind und vorher positiv auf Covid19 getestet wurden - Stand jeweils 10:00
- **Tote_v1_Zuwachs** = Differenz zum Vortag zur selben Uhrzeit
- **Tote_v2** = Gesamtanzahl der Personen, die an den Folgen ihrer Covid19-Erkrankung gestorben sind. Diese Zahl wird anders ermittelt als "Tote_v1" und wird daher extra ausgewiesen - Stand jeweils 10:00
- **Tote_v2_Zuwachs** = Differenz zum Vortag zur selben Uhrzeit
- **Genesene** = Anzahl der Personen, die positiv getestet wurden und als geheilt gelten - Stand jeweils 10:00
- **Genesene_Zuwachs** = Differenz zum Vortag zur selben Uhrzeit
- **Hospitalisiert** = Anzahl der Personen, die an diesem Tag aufgrund ihrer Covid19-Erkrankung im Spital behandelt werden müssen, normale Station wie Intensivstation kombiniert - Stand jeweils 10:00
- **Intensivstaton** = Anzahl der Personen, die aufgrund ihrer Covid19-Erkrankung auf der Intensivstation behandelt werden müssen - Stand jeweils 10:00
- **IBett_frei** =  Anzahl der noch für Covid19-Patienten freien Betten auf Intensivstationen in ganz Österreich - Stand jeweils 10:00
- **IBett_Kapazität** = In Österreich gibt es 2457 Intensivbetten (Stand 2018). Diese Zahl ergibt sich aus der Summe von Intensiv-Patietnen mit Covid19 und der noch für Covid19-Patienten freien Betten und lässt darauf schließen, wieviele Betten durchschnittlich aufgrund anderer Krankheiten benötigt werden. Vor 1. April musste dieser Wert mit 1000 beschätzt werden, da die offiziellen Daten des Gesundheitsministeriums nicht weiter zurück reichen.
- **Testungen** =  Gesamtanzahl der bisher in Österreich durchgeführten Covid19-Tests - Stand jeweils 10:00
- **Testungen_Zuwachs** = Differenz zum Vortag zur selben Uhrzeit
- **Jeweiliges Bundesland (Burgenland,Kärnten,Niederösterreich,Oberösterreich,Salzburg,Steiermark,Tirol,Vorarlberg,Wien)** = Anzahl der positiv getesteten Personen in dem jeweiligen Bundesland - Stand jeweils 8:00
- **Bundesland_Tote** = Anzahl der Personen, die im jeweiligen Bundesland gestorben sind und vorher positiv auf Covid19 getestet wurden - Stand jeweils 10:00
- **Bundesland_Genesene** = Anzahl der als geheilt geltenden Personen - Stand jeweils 10:00
- **Bundesland_Spital** = Anzahl der Personen, die im jeweiligen Bundesland im Spital behandelt werden müssen, normale Station und Intensivstation - Stand jeweils 10:00
- **Bundesland_Intensiv** = Anzahl der Personen, die im jeweiligen Bundesland auf der Intensivstation behandelt werden - Stand jeweils 10:00
- **Bundesland_Tests** = Anzahl der im jeweiligen Bundesland durchgeführten Testungen - Stand jeweils 10:00

## Wie kann ich diese Daten nutzen?
### Variante 1: Download als Gesamtpaket
Github bietet einen Button, der mit "Clone or Download" betitelt ist. Dort lässt sich der Inhalt dieses Repository herunterladen.
Zip-Datei enthält Lizenzinformationen und diese Readme-Datei.

### Variante 2: Direkt einbinden
Indem man die rohe CSV- oder JSON-Datei aufruft, lässt sie sich in Visualisierungstools direkt einbinden oder über diesen Direktlink herunterladen:
https://raw.githubusercontent.com/Daniel-Breuss/covid-data-austria/master/austriadata.csv
https://raw.githubusercontent.com/Daniel-Breuss/covid-data-austria/master/austriadata.json
