# Kollagen-VI Muskeldystrophie Notfallpass

Statische Notfallinformationen für Kollagen-VI Muskeldystrophie. Diese Seite wird über GitHub Pages gehostet und enthält ausschließlich allgemeine, nicht-personenbezogene Informationen.

## Technische Details

- **Framework**: Jekyll (GitHub Pages)
- **CSS**: Bootstrap 5 (lokal gehostet)
- **Sprachen**: Deutsch und Englisch
- **Inhalte**: Statische Notfallhinweise, keine personenbezogenen Daten

## GitHub Pages Setup

1. Repository-Einstellungen → Pages
2. Source: "GitHub Actions"
3. Branch: `main`

Die GitHub Actions Workflow (`.github/workflows/jekyll.yml`) baut automatisch die Jekyll-Seite und deployed sie.

## Lokale Entwicklung

```bash
# Jekyll installieren
gem install jekyll bundler

# Dependencies installieren
bundle install

# Lokalen Server starten
bundle exec jekyll serve
```

## Dateistruktur

- `index.html` - Startseite mit Sprachauswahl
- `german.html` - Deutsche Notfallinformationen
- `english.html` - Englische Notfallinformationen
- `_layouts/default.html` - Basis-Layout
- `_includes/` - Wiederverwendbare Komponenten (Navbar, Footer)
- `bootstrap/` - Lokale Bootstrap-Dateien
- `Markdown/` - Projektinformationen

## URLs

- Startseite: `https://sb97.github.io/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/`
- Deutsch: `https://sb97.github.io/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/german.html`
- Englisch: `https://sb97.github.io/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/english.html`
