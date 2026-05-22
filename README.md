# Static PNG Hosting

Minimalstruktur, um drei PNG-Dateien per GitHub Pages aus dem `docs/`-Ordner zu veroeffentlichen. Dieses Repository enthaelt nur neutrale statische Dateien.

## Struktur

```text
docs/
  .nojekyll
  index.html
  images/
    chef_illustration.png
    hero_1_neural.png
    hero_outro.png
```

## GitHub Pages aktivieren

1. Repository zu GitHub pushen.
2. Auf GitHub: `Settings` -> `Pages`.
3. `Build and deployment` -> `Source`: `Deploy from a branch`.
4. Branch: `main`, Folder: `/docs`.
5. Speichern.

Die PNGs sind danach direkt erreichbar unter:

```text
https://<user>.github.io/<repo>/images/chef_illustration.png
https://<user>.github.io/<repo>/images/hero_1_neural.png
https://<user>.github.io/<repo>/images/hero_outro.png
```
