# HS2026 – IVAs 107:e Högtidssammankomst

Webbanimering: Stadshuset i gryning, IVAs logotyp som ritas in (bågen sveper medsols, bokstäverna tonar in), därefter text för sammankomsten. Loop på 18 sekunder, format 1:1. Bakgrunden renderas i WebGL med en djupkarta, så kameran glider och bilden får parallax. Musen styr kameran.

Öppna `index.html` via en lokal webbserver (t.ex. `python3 -m http.server`). Klick ger helskärm, mellanslag pausar.

`assets/`
- `stadshuset-clean.webp` – bakgrundsbilden (1:1) med den AI-ritade logotypen bortretuscherad
- `stadshuset-depth.png` – djupkarta (ljust = nära) som styr parallaxen
- `stadshuset-wide.webp` – 16:9-version med speglade, oskarpa kanter (används inte längre av sidan)
- `iva-arc.png`, `iva-letters.png` – IVAs märke uppdelat i båge och bokstäver för animeringen
- `iva-mark-white.png`, `iva-wordmark-en-white.png` – märket och den engelska ordbilden, oförändrade

## journey.html – resan 1919–2026

Tecknad resa från Grev Turegatan 1919 till Stadshuset 2026 i åtta scener. En ritning ritas fram medan kameran glider; bakgrund och stil skiftar per epok, och sista scenen tonar in den målade bilden med IVAs logotyp. Piltangenter hoppar mellan år, mellanslag pausar.
