# Kollagen-VI Muskeldystrophie Notfallpass

Statische Notfallinformationen für Kollagen-VI Muskeldystrophie. Diese Seite wird über GitHub Pages gehostet und enthält ausschließlich allgemeine, nicht-personenbezogene Informationen für medizinisches Personal.

## 🎯 Projektziel

Diese Website bietet schnell zugängliche, verlässliche Notfallhinweise für Kollagen-VI Muskeldystrophien. Sie ist für medizinisches Personal konzipiert und enthält keine personenbezogenen Daten.

## 🚀 Live Demo

- **Website**: [https://sb97.github.io/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/](https://sb97.github.io/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/)
- **Deutsche Version**: [https://sb97.github.io/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/german](https://sb97.github.io/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/german)
- **English Version**: [https://sb97.github.io/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/english](https://sb97.github.io/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/english)

## 🛠️ Technische Details

- **Framework**: Jekyll 4.4.1 (GitHub Pages)
- **CSS Framework**: Bootstrap 5 (CDN)
- **Icons**: Bootstrap Icons
- **Theme**: Just the Docs
- **Sprachen**: Deutsch und Englisch
- **Inhalte**: Statische Notfallhinweise, keine personenbezogenen Daten

## 📁 Projektstruktur

```
TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/
├── index.md                    # Startseite mit Sprachauswahl
├── german.md                   # Deutsche Notfallinformationen
├── english.md                  # Englische Notfallinformationen
├── about.md                    # Projektinformationen
├── _layouts/
│   └── default.html           # Hauptlayout mit Navigation
├── assets/
│   ├── css/
│   │   └── custom.scss        # Eigenes Styling
│   └── images/
│       ├── OpenMoji_flag_Germany_1F1E9-1F1EA_color.png
│       └── OpenMoji_flag_UK_1F1EC-1F1E7_color.png
├── _config.yml                # Jekyll-Konfiguration
└── Gemfile                    # Ruby-Dependencies
```

## 🚀 Lokale Entwicklung

### Voraussetzungen
- Ruby 3.2+
- Bundler

### Setup
```bash
# Repository klonen
git clone https://github.com/sb97/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass.git
cd TEST-Kollagen-VI_Muskeldystrophie_Notfallpass

# Dependencies installieren
bundle install

# Lokalen Server starten
bundle exec jekyll serve --host 0.0.0.0 --port 4001

# Website ist dann verfügbar unter: http://localhost:4001
```

### Build
```bash
# Statische Dateien generieren
bundle exec jekyll build

# Generierte Dateien sind in _site/
```

## 🌐 GitHub Pages Setup

1. Repository-Einstellungen → Pages
2. Source: "GitHub Actions"
3. Branch: `main`

Die GitHub Actions Workflow (`.github/workflows/jekyll.yml`) baut automatisch die Jekyll-Seite und deployed sie.

## 📱 Features

### Responsive Design
- Mobile-first Ansatz
- Burger-Menü für mobile Navigation
- Touch-optimierte Buttons
- Vollständig responsive auf allen Geräten

### Barrierefreiheit
- Semantisches HTML
- Skip-Links für Tastaturnavigation
- Ausreichender Kontrast (WCAG AA)
- Screen Reader optimiert

### Performance
- Schnelle Ladezeiten
- CDN für Bootstrap und Icons
- Optimierte Bilder
- Keine externen Tracker

### Druckversion
- A4-optimierte Druckansicht
- "Seite drucken" Button auf allen Inhaltsseiten
- Print-CSS für optimale Darstellung

## 📋 Inhalte

### Deutsche Version
- Krankheitsüberblick
- Allgemeine Akutmaßnahmen
- Kontraindikationen
- Hinweise für Rettungsdienst/Notaufnahme
- Hinweise für Anästhesie/Intensivmedizin
- Weiterführende Informationen

### English Version
- Brief overview
- General immediate measures
- Contraindications / Caution
- Notes for EMS and Emergency Department
- Notes for Anaesthesia/Intensive Care
- Further reading

## 🔧 Konfiguration

### _config.yml
```yaml
title: Kollagen-VI Muskeldystrophie Notfallpass
baseurl: "/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass"
url: "https://sb97.github.io"
remote_theme: just-the-docs/just-the-docs
```

### Theme-Konfiguration
- Light Color Scheme
- Suchfunktion aktiviert
- Navigation mit Anker-Links
- Mobile Navigation aktiviert

## 🤝 Beitragen

1. Fork das Repository
2. Erstelle einen Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Committe deine Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen Pull Request

## 📄 Lizenz

Dieses Projekt ist Open Source und unter der MIT-Lizenz verfügbar.

## ⚠️ Wichtiger Hinweis

Diese Informationen ersetzen nicht die individuelle medizinische Beurteilung. Bei Unsicherheit sollte immer Rücksprache mit erfahrenen Zentren gehalten werden.

## 📞 Support

Bei Fragen oder Problemen:
- Erstelle ein [Issue](https://github.com/sb97/TEST-Kollagen-VI_Muskeldystrophie_Notfallpass/issues)
- Kontaktiere uns über das GitHub Repository

---

**Version**: 1.0  
**Letzte Aktualisierung**: August 2024  
**Status**: Aktiv
