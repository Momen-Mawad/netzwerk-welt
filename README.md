# Netzwerk-Welt für die FOSSGIS 2021

Karten für https://workadventu.re

## Aktuelle Version der Welt / der Karten interaktiv ausprobieren

https://play.workadventu.re/_/global/fossgis-2021.github.io/netzwerk-welt/campus.json

Diese Version wird per GitHub-Action aus dem `main`-Branch erzeugt.

## Eine Karte mit _Tiled_ bearbeiten

Den Kachel-Karten-Editor [Tiled](https://www.mapeditor.org/) installieren und dann:

1. Dieses Repository klonen:
   ```bash
   git clone git@github.com:fossgis-2021/netzwerk-welt.git
   ```
2. In das lokale Repo-Verzeichnis wechseln:
   ```bash
   cd netzwerk-welt
   ```
3. Die JSON-Datei zur Karte in Tiled öffnen:
   ```bash
   tiled campus.json
   ```
