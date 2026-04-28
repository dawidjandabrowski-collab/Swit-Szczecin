# KS Świt Szczecin — Oficjalna strona klubu

Makieta strony głównej KS Świt Szczecin — Duma Skolwina.

## Struktura projektu

```
swit-szczecin/
├── index.html          ← główna strona
├── assets/
│   ├── crest.png       ← herb Świtu
│   ├── podbeskidzie.png ← herb rywala
│   └── betclic-2liga.png ← logo ligi
└── README.md
```

## GitHub Pages

1. Wgraj na GitHub jako nowe repozytorium
2. Settings → Pages → Deploy from branch: `main` / `root`
3. Strona działa pod: `https://[twoj-nick].github.io/swit-szczecin/`

## Zamiana zdjęć

Sekcje `card-img` mają placeholder tła — zastąp je przez:
```css
.feat .card-img { background-image: url('assets/foto-mecz.jpg'); background-size: cover; }
```
