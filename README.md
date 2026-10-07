# HS2026 – IVAs 107:e Högtidssammankomst

Webbanimering: Stadshuset i gryning, IVAs logotyp som ritas in (bågen sveper medsols, bokstäverna tonar in), därefter text för sammankomsten. Loop på 18 sekunder, format 1:1. Bakgrunden renderas i WebGL med en djupkarta, så kameran glider och bilden får parallax. Musen styr kameran.

Öppna `index.html` via en lokal webbserver (t.ex. `python3 -m http.server`). Klick ger helskärm, mellanslag pausar.

`assets/`
- `stadshuset-clean.webp` – bakgrundsbilden (1:1) med den AI-ritade logotypen bortretuscherad
- `stadshuset-depth.png` – djupkarta (ljust = nära) som styr parallaxen
- `stadshuset-wide.webp` – 16:9-version med speglade, oskarpa kanter (används inte längre av sidan)
- `iva-arc.png`, `iva-letters.png` – IVAs märke uppdelat i båge och bokstäver för animeringen
- `iva-mark-white.png`, `iva-wordmark-en-white.png` – märket och den engelska ordbilden, oförändrade
