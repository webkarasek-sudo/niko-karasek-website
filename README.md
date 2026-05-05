# Niko Karasek — Personal Website

Persönliche Website von Niko Karasek — Dokumentarfilmer & Reporter.

## Struktur

```
index.html         ← Hauptdatei (HTML + CSS + JS)
assets/
  ├─ films/        ← Vorschaubilder der Reportagen
  ├─ experts/      ← Vorschaubilder der Experten-Auftritte
  ├─ logos/        ← Sender-Logos (ZDF, Arte, NTV, ARD, MDR, Stern TV)
  ├─ portrait.webp ← Portrait-Foto für About-Bereich
  └─ footer.gif    ← Animation für Footer
```

## Inhalt bearbeiten

Alle Texte, Filme, Kontakte und Links sind in `index.html` an einer Stelle gepflegt:

- **Filme** → Suche `const FILMS` im JavaScript-Block
- **Experte** → Suche `const EXPERTS`
- **Bio** → Suche `info-lede` und `info-body`
- **Kontakt** → Suche `nikokarasek.tv@gmail.com`
- **Showreel** → Suche `SHOWREEL_YT`

## Deployment

Statische Website — funktioniert auf jedem Hosting:

- **Netlify** (empfohlen) — Auto-Deploy bei Git-Push
- **Vercel** — gleiche Funktionsweise
- **Lokal** — `index.html` einfach im Browser öffnen

## Hinweis

YouTube-Embeds funktionieren nur auf der echten Domain, nicht im lokalen Editor-Vorschau (iframe-in-iframe wird von YouTube blockiert).
