# Kunden-Preview

## Projekt-Gedaechtnis
- **Projekt-Tag:** `allgemein`
- Bei Session-Start: `search_memory(query="<Aufgabe>", project="allgemein")`
- Neues Wissen speichern: `save_memory(title="...", content="...", tags=["allgemein"])`

## Zweck
Statische HTML-Landingpages fuer Kunden-Konzeptvorschauen (A/B-Testing, SEO-optimiert).

## Tech-Stack
- **Frontend:** Vanilla HTML5 + Inline CSS (kein Build-System)
- **Fonts:** Google Fonts (Montserrat)
- **SEO:** OpenGraph, JSON-LD Schema (Article, FAQ, Breadcrumb)
- **Kein Framework, kein NPM, kein Build-Prozess**

## Projektstruktur
```
kunden-preview/
└── sanverdi/
    ├── gewerbeversicherung/        # V1: Konzept
    │   └── index.html
    └── gewerbeversicherung-v2/     # V2: VMK-Editorial-Stil
        └── index.html
```

## Konventionen
- Pro Kunde ein Unterordner (z.B. `sanverdi/`)
- Iterationen als V1, V2 etc. (A/B-Testing)
- Responsive Design (clamp/mobile-first)
- CSS-Variablen fuer zentrale Farbverwaltung
- Schema.org Markup fuer E-E-A-T

## Git-Regeln
- **Repo:** `kahramanatalay/kunden-preview` (oeffentlich)
- Commits auf Deutsch, beschreibend
- Branch: `main` (trunk-based)
