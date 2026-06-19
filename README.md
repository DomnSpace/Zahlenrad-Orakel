# Zahlenrad-Orakel

Mobile-first interactive Zahlenrad oracle for GitHub Pages.

The app reads a birth date through **Atolische Gestenzahl**: numbers are treated not only as values, but as gestures, directions, colors, and houses.

## Core mapping

- `0 / V` — Mitte / Gelb — Quelle, Hand, Herd
- `I / VI` — Nord / Blau — Strich, Führung, Berg
- `II / VII` — Süd / Rot — Paarung, Feuer, Wagen
- `III / VIII` — Ost / Grün — Reihe, Wachstum, Herz
- `IV / IX` — West / Weiß — Schnitt, Silber, Maß

## Gesture layer

- `I` — Strich / Setzung
- `II` — Paarung / Spannung
- `III` — Reihe / Wachstum
- `IV` — Schnitt vor der Hand
- `V` — Hand / Mitte
- `VI` — Hand + Strich
- `VII` — Hand + Paarung
- `VIII` — Hand + Reihe
- `IX` — Schnitt vor dem Kreuz
- `X` — Kreuz / Vollendung / Wegkreuzung

## Deployment

This repository is set up as a static site.

To host with GitHub Pages:

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. Push to the default branch or manually run the workflow.

The site should then appear at:

`https://domnspace.github.io/Zahlenrad-Orakel/`

## Notes

This is an experimental interpretive interface inspired by publicly known Zahl-Farbe-Richtungs mappings associated with the Tiroler Zahlenrad, extended with an original Atolische Gestenzahl rule engine and visual language. It is not an official Paungger/Poppe product and does not reproduce a proprietary full system.
