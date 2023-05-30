# Projekt-Dokumentation
Dragonfruit
Gilardoni, Bytyqi, Kritzner

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|16.05.23 | 0.0.1   | Erste Website veröffentlicht und angefangen Projektdokumentation auszufüllen. |
|23.05.23| 0.0.2   | Angefangen Funktionen zu implementieren. |
|30.05.23| 0.0.3   | Einige Funktionen implementiert und Dokumentation ausgefüllt. |

## 1 Informieren

### 1.1 Ihr Projekt

Wir machen eine Website, wo man sich über Ernährung und Körperliches informieren kann. Es gibt Tipps für verschiedene Ernährungsarten wie Cut (Kalorien Defizit) und Bulk (Kalorien Zunahme).

![MicrosoftTeams-image (42)](https://user-images.githubusercontent.com/110892683/237025824-f704b7c6-94a4-48ca-90a1-124fc1d5d810.png)

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | kann | funktional | Als ein User möchte ich den Dark Mode aktivieren, damit ich meinen bevorzugten Modus aussuchen kann. |
| 2  | muss | funktional | Als ein User möchte ich, dass sich die Website auf den Bildschirm anpasst, damit ich auch mit dem Handy auf die Website kann. |
| 3  | kann | funktional | Als ein User möchte ich, dass die Sprachen geändert werden können, damit ich meine bevorzugte Sprache auswählen kann. |
| 4  | muss | funktional | Als ein User möchte ich geeignete Bilder zu den Informationen sehen, damit ich diese besser verstehe. |
| 5  | muss | funktional | Als ein User möchte ich verschieden Farben und Schriftarten haben, damit ich mich besser orientieren kann. |
| 6  | muss | funktional | Als ein User möchte ich, dass mein bevorzugtes Farbschema erkennt wird, damit die Seite automatisch daran angepasst wird. |
| 7  | kann | funktional | Als ein User möchte ich, dass es Videos gibt, damit ich mir bei der Ausführung sicher bin. |
| 8  | muss | funktional | Als ein User möchte ich viele Informationen erhalten, damit ich viel neues lernen kann. |
| 9  | muss | funktional | Als ein User möchte ich ein tolles Layout, damit ich eine gute Orientation und Motivation habe diese Seite zu lesen. |
| 10  | muss | funktional | Als ein User möchte ich am Anfang ein Carousel sehen, damit ich einen Eindruck erhalte, was auf dieser Website steht. |
| 11 | muss | funktional | Als ein User möchte ich ein Formular, bei dem ich meine Makros eintragen kann. (Keine Funktionalität) |
| 12 | muss | funktional | Als ein User möchte ich Videos, welche nicht von Youtube verlinkt werden, sondern als <video> tag eingebunden werden. |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | 
| ---- | ------------ | ------- | ----------------- |
| 1.1   |Website ist offen |Der User klickt auf den Dark Mode     | Die ganze Seite ist jetzt im Dark Mode  |
| 2.1    |- | Website wird auf Handy geöffnet | Website passt sich an |
| 3.1    |Website ist offen| Der User ändert die Sprache | Die Seite wird übersetzt |
| 4.1    | Website ist offen | Der User klickt auf zum Beispiel auf Ernährung  | Man sieht die Bilder auf der Unterseite Ernährung |
| 5.1   | Website ist offen | keine Eingabe | Der User sieht verschiedene Farben und Schriftarten |
| 6.1   | - | Website wird geöffnet |Die Farben passen sich automatisch an|
| 7.1   | Website ist offen | Auf ein Video wird geklickt |Video wird abgespielt|
| 8.1   | Website ist offen |Es wird eine Unterseite geöffnet |Es gibt viel informativen Text|
| 9.1   | Website ist offen |keine Eingabe|Es gibt ein übersichtliches Layout|
| 10.1   | Website ist offen |keine Eingabe|Es gibt animiertes Carousel|
| 11.1   | Website ist offen |keine Eingabe|Es gibt ein interaktives Formular, bei dem man nur Zahlen eingeben kann|
| 12.1   | Website ist offen |keine Eingabe|Es gibt Videos, welche sich der Website anpassen|  
  
### 1.4 Diagramme

![LA1600 (1)](https://github.com/V4nil/LA-1600/assets/110892683/4f41b21e-2c7a-41b2-9d8f-cb4f143fcca9)

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |23.04.23|Bytyqi| Darkmode implementieren | 4 * 45' |
| 2.A  |23.04.23|Gilardoni| Website passt sich dem Bildschirm an | 4 * 45' |
| 3.A  |23.04.23|Kritzner| Sprachen können geändert werden | 2 * 45' |
| 4.A  |23.04.23|Kritzner| geeignete Bilder aussuchen | 45' |
| 4.B  |23.04.23|Kritzner| Bilder zuschneiden und anpassen | 2 * 45' |
| 4.C  |23.04.23|Kritzner| Bilder implementieren | 45' |
| 5.A  |23.04.23|Gilardoni| Farbschema aussuchen | 20' |
| 5.B  |23.04.23|Gilardoni| Farbe in die Website implementieren | 25' |
| 5.C  |23.04.23|Gilardoni| Schriftfarbe auswählen | 15' |
| 5.D  |23.04.23|Gilardoni| Schriftfarbe implementieren | 30' |
| 6.A  |23.04.23|Bytyqi| Website passt sich den ausgewählten Farbschema an | 2 * 45' |
| 7.A  |23.04.23|Kritzner| Passendes Video aussuchen | 25' |
| 7.B  |23.04.23|Kritzner|Video implementieren | 65' |
| 8.A  |23.04.23|Gilardoni|Informativen Text erstellen | 45' |
| 9.A  |23.04.23|Kritzner|Website Layout erstellen | 45' |
| 10.A  |30.04.23|Gilardoni|Carousel erstellen | 2 * 45' |
| 11.A  |30.04.23|Bytyqi|Formular erstellen | 25' |
| 11.B |30.04.23|Bytyqi|Das Design des Formulars passt sich an (Feld wird hervorgehoben) | 20' |
| 11.C  |30.04.23|Bytyqi|Es können nur Zahlen eingegeben werden | 30' |
| 12.A  |30.04.23|Kritzner|Videos einbinden mit <video> tag | 25' |
| 12.B |30.04.23|Kritzner|Videos passen sich der Website an | 20' |

## 3 Entscheiden



## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 4.A|13.05.23|Kritzner|45'|50'|
| 4.B|13.05.23|Kritzner|2 * 45'|20'|
| 4.C|13.05.23|Kritzner|45'|30'|
| 7.A  |16.05.23|Kritzner|25'|25'|
| 7.B|13.05.23|Kritzner|65'|70'|
| 12.A|13.05.23|Kritzner|25'|25'|



## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |


