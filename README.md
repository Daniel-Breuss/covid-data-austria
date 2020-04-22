# covid-data-austria
Täglich aktualisierte CSV-Datei, die aktuelle Covid19-Daten aus Österreich beinhaltet.

Basiert auf denselben Daten, die als Basis für dieses [Covid19-Dashboard](https://covid19.danielbreuss.com/) dienen.

## Datenquellen für diese Aggregation
https://info.gesundheitsministerium.at/

https://www.sozialministerium.at/Informationen-zum-Coronavirus/Neuartiges-Coronavirus-(2019-nCov).html

https://www.bmi.gv.at/news.aspx?id=4A7171477A51625143334D3D



## Struktur
Datum,Fälle_gesamt,Fälle_Zuwachs,Burgenland,Kärnten,Niederösterreich,Oberösterreich,Salzburg,Steiermark,Tirol,Vorarlberg,Wien,Tote_v1,Tote_v1_Zuwachs,Tote_v2,Tote_v2_Zuwachs,Genesene,Genesene_Zuwachs,Hospitalisiert,Intensivstation,IBett_frei,IBett_Kapazität,Testungen,Testungen_Zuwachs

## Erläuterungen
- **Datum** = selbsterklärend
- **Fälle_gesamt** = Anzahl der bisher positiv getesteten Personen in ganz Österreich - Stand jeweils 8:00
- **Fälle_Zuwachs** = Differenz zum Vortag zur selben Uhrzeit
- **Burgenland,Kärnten,Niederösterreich,Oberösterreich,Salzburg,Steiermark,Tirol,Vorarlberg,Wien** = Anzahl der positiv getesteten Personen in dem jeweiligen Bundesland - Stand jeweils 8:00
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


## Wie kann ich diese Daten bei mir einbinden?
### Variante 1: Download als Gesamtpaket
Github bietet einen Button, der mit "Clone or Download" betitelt ist. Dort lässt sich der Inhalt dieses Repository herunterladen.
Zip-Datei enthält Lizenzinformationen und diese Readme-Datei.

### Variante 2: Direkt einbinden
Indem man die rohe CSV-Datei aufruft, lässt sie sich in Visualisierungstools direkt einbinden oder über diesen Direktlink herunterladen:
https://raw.githubusercontent.com/Daniel-Breuss/covid-data-austria/master/austriadata.csv
