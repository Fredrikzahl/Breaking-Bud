# Breaking Bud

Hjemmesiden til Breaking Bud, et lite garasjebryggeri i Eidkjosen på Kvaløya i Tromsø. Stiftet i 2024 av Birger Pedersen, Vegard Johansen, Andreas Myrvold, Markus Ottesen og Fredrik Zahl Karlsen.

Siden er på norsk med engelsk som valg, og viser gjengen, ølet, hele bryggeprosessen steg for steg, oppskrifter og hvordan man blir med som gjestebrygger. Ølet selges ikke.

## Innhold

- `index.html` er hele siden, med CSS og JavaScript i samme fil.
- `img/` inneholder bilder og etiketter.
- `clips/` inneholder korte videoklipp fra bryggedagen, hvert med et stillbilde (`.jpg`).
- `intro/` inneholder introfilmen øverst på siden.

## Kjøre lokalt

Åpne `index.html` i nettleseren, eller start en enkel server i mappen:

```
python3 -m http.server 8000
```

Gå så til http://localhost:8000.

## Publisere med GitHub Pages

Gå til Settings → Pages, velg grenen `main` og mappen `/ (root)`. Da ligger siden ute etter et minutt eller to.
