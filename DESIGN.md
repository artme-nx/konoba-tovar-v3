# DESIGN.md — Konoba Tovar (v3)

> **Color handoff: MOZAK (hospitality-web-builder) → OKO (Impeccable).**

## Klijent
- **Naziv:** Konoba Tovar · **Mjesto:** Zadar · **Kategorija:** Restorani i konobe
- **Web/Tel:** nema weba (🔴), telefon nije pronađen · TripAdvisor 4.3 / 131 recenzija
- **Napomena iz baze:** „pogođen stil al ne detalj (mačka umjesto tovar)" → **prošli build je promašio detalj: stavio krivu životinju.** Ovaj put: motiv tovara (magarca) ide u COPY i kao simbol; PRAVA fotografija tovara ostavljena kao `TODO[klijent]` (NE lažni magarac/druga životinja).
- **Arhetip:** PRESET 5 — Heritage / rustika (suzdržan, topao registar)

## Brand mode
Register: **brand.md**. Strategija: **Full-palette (restrained earthy)** — boje fizičke lokacije (zadarski kamen, crvenica, slama, maslina). Svjesno izbjegnut „AI cream near-white": baza je pigmentiraniji topli kamen, ne blijeda krema; toplina nošena terakotom i tipografijom.

## Odluka o KARAKTERU palete (i zašto — iz imena "Tovar" + Zadar)
**"Tovar"** (dalmatinski = magarac) = strpljivi radnik stare Dalmacije, simbol sporog i poštenog. → **zemljana terakota + slama/žito + zadarski kamen + maslina.** Topla i mirna. Različita od Masline (maslinasto-srebrna) i Refula (hladno olujno more).

| Token | Hex | Odakle |
|---|---|---|
| `--bg` | `#ECE3D2` | zadarski kamen / slama (pigmentiran topli, NE blijeda krema) |
| `--bg-alt` | `#E0D4BC` | suha slama, sekundarne sekcije |
| `--bg-deep` | `#281F18` | pečena zemlja / ognjište (dark sekcije) |
| `--ink` | `#2A2018` | tamna pržena zemlja, topli near-black (body ≥ 9:1) |
| `--mid` | `#6B5E46` | maslinasto-slamnata siva (čitljiv mid ≥4.5:1) |
| `--accent` | `#B25B36` | **terakota / zadarska crvenica** — primarni brand ton |
| `--accent-2` | `#8A4327` | tamnija terakota za hover |
| `--olive` | `#65663A` | maslina, sekundarni zemljani (štedljivo) |
| `--gold` | `#B0883B` | žito/slama, mali naglasci |

- **Display:** EB Garamond (knjiški heritage) — različit od Maslina (Cormorant) i Reful (Bodoni Moda).
- **Body:** Work Sans (humanistički, NE Inter — izbjegnut overused-font).
- **Hero tip:** **4-image editorial „kronika" grid** (kruh/ruke/roštilj/ulje) — anti-clone vs Maslina (fullbleed) i Reful (split).
- **Potpisne (P5 heritage, suzdržano):** topli sepia/grain filtar galerije, SVG grain overlay, spori fade reveal, count-up „od godine", clip reveal, botanički divajder. NE: WebGL, magnetic, scramble, horizontal, kinetika.

## Sadržajni mandat
Glas: topao, strpljiv, heritage. Tovar kao simbol sporosti i poštenja. Nepoznato (godina, obitelj, chef, PRAVA fotografija tovara) → uvjerljiv tekst + `TODO[klijent]`.
