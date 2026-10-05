# Ich liebe Techno

Dunkler Web-Player für The Art of Techno. Near-black, ein Rot, sonst nichts.

Kein Framework. Eine Datei öffnen, Play drücken, fertig. Der Default-Stream ist Cliqhop von SomaFM, damit der Knopf am ersten Tag nicht tot ist. Eigene Sender stehen in `stations` in `index.html`.

## Drin

- Play / Pause, Senderwechsel, Lautstärke
- Drei Slots: Demo, eigener Stream, Festival-Notiz als Text
- `manifest.json` fürs PWA-Install, Icons fehlen noch
- Mobil zuerst, weil das Ding im Club und nicht am Schreibtisch läuft

## Lokal

```bash
python3 -m http.server 8080
```

Dann `http://localhost:8080`.

## GitHub Pages

Settings → Pages → Branch `main` / root. Danach liegt der Player unter `https://dickgoodman.github.io/ich-liebe-techno/`.

## Als Nächstes

- Eigenes 24/7-Stream-URL rein, SomaFM raus
- 192 und 512 Icons fürs Manifest
- Festival-Liste als echte Daten, nicht als Platzhalter
- Service Worker, wenn der Player offline die letzte Station halten soll
