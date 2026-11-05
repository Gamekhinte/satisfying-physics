# Squish Kitchen

Ein Koch- und Physikspiel fürs Handy im Querformat. Alles ist weich und wabbelig und lässt sich schneiden, zermatschen, mixen, braten, frittieren, backen und einfrieren. Es läuft direkt im Browser, ohne Installation.

## Modi

- **Tutorial:** zeigt in 9 Schritten alles Wichtige.
- **Story:** 100 Gäste in 10 Kapiteln (Omas Küche, Zuckerbäckerei, Grillabend, Gartenfrisch, Feuer & Säure, Backstube, Am Meer, Imbissbude, Eiszeit, Die große Gala). Jeder Gast hat eigene Wünsche, gibt dir nur bestimmte Zutaten und lässt dir begrenzt Zeit. Am Ende jedes Kapitels wartet ein Boss-Kritiker. Bewertet wird nach Geschmack, Garzustand, Temperatur, Portion, Vielfalt, Feinheit, Sauberkeit und mehr, mit bis zu 3 Sternen. 1 Stern schaltet den nächsten Gast frei.
- **Sandkasten:** 213 Zutaten in 10 Kategorien, alles unbegrenzt. Du kannst jeden Kritiker probieren lassen.

## Die Küche

Die Küche hat 5 Stationen. Wisch auf einer freien Stelle nach links oder rechts oder tippe oben auf die Tabs. Wenn du Essen an den Bildschirmrand ziehst, fährt die Küche mit.

| Station | Was es dort gibt |
|---|---|
| Brett | Schneidebrett und Glasschüssel mit Mixer |
| Herd | Pfanne, Glastopf und Grill, jeweils mit Drehknopf |
| Ofen | Backofen (180 °C oder 250 °C) und Mikrowelle |
| Fritte | Fritteuse, Gefrierfach und Panierstraße |
| Teller | Teller und der Gast am Tisch |

**Werkzeuge:** Greifen, Messer und Fleischklopfer.

**Mehrere Sachen auf einmal:** Finger kurz auf eine freie Stelle halten und einen Rahmen ziehen. Alles darin ist ausgewählt (gelb gestrichelt). Ziehst du eins davon, kommen alle mit. Antippen fügt einzelne Stücke hinzu oder nimmt sie weg.

**Schnell zur Station:** Essen beim Tragen oben auf einen Tab ziehen, dann springt die Küche sofort dorthin.

**Panieren:** Bei der Fritteuse stehen drei Schalen. Erst Mehl, dann Ei, dann Brösel, danach ab in die Fritteuse. Aus Fleisch wird ein Schnitzel, aus Fisch ein Backfisch, aus Käse Backkäse.

**Mixen:** Zutaten in die Schüssel legen und auf MIXEN tippen. Daraus wird zum Beispiel ein Obst-Smoothie, eine Schoko-Creme, Scharfe Salsa, ein Rührei-Mix oder Kuchenteig. Kuchenteig wird im Ofen zu Kuchen, eine Frucht-Creme im Gefrierfach zu Eis.

## Online stellen (GitHub Pages)

1. Im Repo auf **Settings → Pages** gehen.
2. Unter **Source** „Deploy from a branch“ wählen, Branch `main`, Ordner `/ (root)`.
3. Speichern. Nach etwa einer Minute ist das Spiel unter `https://<dein-name>.github.io/satisfying-physics/` erreichbar.

## Technik

Eine einzige `index.html` ohne Abhängigkeiten. Die Weichkörper-Physik, die Koch- und Temperatursimulation, alle Grafiken, die Level und alle Sounds werden zur Laufzeit erzeugt.
