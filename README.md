# Squish Kitchen

Ein Koch- und Physikspiel fürs Handy im Querformat. Alles ist weich, wabbelig und lässt sich schneiden, zermatschen, mixen und kochen. Es läuft direkt im Browser, ohne Installation.

## Modi

- **Story:** 7 Restaurant-Kritiker mit eigenen Vorlieben (süß, herzhaft, scharf, sauber, fein geschnitten, gebacken …). Jeder Gast gibt dir nur bestimmte Zutaten. Leg dein Gericht auf den Teller und tippe auf „Servieren“. Bewertet wird nach Geschmack, Garzustand, Temperatur, Portion, Vielfalt und mehr, mit bis zu 3 Sternen. 1 Stern schaltet den nächsten Gast frei.
- **Sandkasten:** Alle Zutaten unbegrenzt. Du kannst jeden Kritiker probieren lassen.

## Mixen

Leg Zutaten in die Glasschüssel und tippe auf MIXEN. Daraus entsteht eine Mischung mit eigenem Namen und Geschmack, zum Beispiel Obst-Smoothie, Schoko-Erdbeer-Creme, Scharfe Salsa, Rührei-Mix oder Kuchenteig. Kuchenteig im Ofen wird zu Kuchen.

## Spielen

- **Online:** über GitHub Pages (siehe unten), dann auf dem Handy „Zum Home-Bildschirm“ wählen. Danach startet es wie eine App im Vollbild.
- **Lokal:** `index.html` im Browser öffnen.

## Was man machen kann

| Werkzeug | Was es macht |
|---|---|
| Greifen | Essen packen, ziehen, werfen |
| Messer | Mit dem Finger durchwischen und das Essen schneiden |
| Fleischklopfer | Draufhauen und zermatschen (Steak wird flach geklopft) |

**Küche**
- **Herd mit Pfanne und Glastopf:** Tippe auf die Drehknöpfe (aus, mittel, voll).
- **Backofen:** Tippe auf das Bedienfeld oben für 180 °C oder 250 °C und auf die Tür, um sie zu öffnen oder zu schließen.
- **Mikrowelle:** Tippe aufs Fenster für die Tür und auf START. Sie läuft 12 Sekunden.

**Essen**
- **Süß:** Zitrone, Schokolade (schmilzt), Marshmallow (geht auf und röstet), Erdbeere, Banane (wird braun), Wackelpudding, Melone, Orange, Popcorn (Maiskörner poppen im heißen Topf)
- **Herzhaft:** Tomate, Chili, Ei (Spiegelei in der Pfanne, hart gekocht im Topf, explodiert in der Mikrowelle), Steak (Röstaromen und Grillstreifen, innen rosa bis durch), Würstchen (platzt, wenn es zu lange brät), Käse (schmilzt), Butter (schmilzt), Teig (geht im Ofen zu Brot auf)

Alles kann verbrennen, wenn es zu lange auf der Hitze bleibt.

## Online stellen (GitHub Pages)

1. Im Repo auf **Settings → Pages** gehen.
2. Unter **Source** „Deploy from a branch“ wählen, Branch `main`, Ordner `/ (root)`.
3. Speichern. Nach etwa einer Minute ist das Spiel unter `https://<dein-name>.github.io/satisfying-physics/` erreichbar.

## Technik

Eine einzige `index.html` ohne Abhängigkeiten. Die Weichkörper-Physik (Shape Matching, Volumenerhalt, Schnitte entlang beliebiger Linien), die Hitze- und Kochsimulation, alle Grafiken und alle Sounds werden zur Laufzeit erzeugt.
