# Marketing Team Skills

Ein Team aus 16 KI-Agents für Marketing, Vertrieb und Operations — von Landing Pages über CRM bis IT-Infrastruktur.

## Konzept

**Team** = Sammlung von Agents
**Agents** = Einzelne Rollen mit spezialisierten Fähigkeiten
**Skills** = Die konkreten Fähigkeiten jedes Agents

## Das Team

| # | Agent | Kernaufgabe |
|---|-------|-------------|
| 0 | **Projektleiter** | Orchestrierung, Qualitätssicherung, Nutzer-Kommunikation |
| 1 | **Stratege** | Konzept, Positionierung, Wettbewerbsanalyse |
| 2 | **Content Creator** | Texte, Copywriting, Social Content |
| 3 | **SEO-Spezialist** | Suchmaschinenoptimierung, Schema Markup |
| 4 | **CRO-Optimierer** | Conversion-Optimierung, A/B-Tests |
| 5 | **Growth Manager** | Traffic, E-Mail-Marketing, Paid Ads |
| 6 | **Landing Page Builder** | Technische Umsetzung der Landing Page |
| 7 | **Recherche-Agent** | Markt-, Technologie- und Regulatorik-Recherchen |
| 8 | **CRM-Agent** | Salesforce, Lead-Management, Kampagnen-Setup |
| 9 | **Notion-Architekt** | Notion-Strukturen, Datenbanken, Formulare |
| 10 | **Briefing-Agent** | Meeting-Vorbereitung, Status-Reports, Entscheidungsvorlagen |
| 11 | **DevOps-Agent** | GitHub, CI/CD, Domains, Deployments |
| 12 | **Konzept-Agent** | Ideen → professionelle 1-2-Seiter |
| 13 | **Wettbewerbs-Agent** | Wettbewerbsbeobachtung & -analyse |
| 14 | **Monthly-Report-Agent** | GF-Monatsbericht alle 4 Wochen |
| 15 | **Übersetzungs-Agent** | DE → EN/FR/PL mit Fachvokabular |

## Workflow

```
Nutzer-Briefing
     |
[Projektleiter] --> Briefing erstellen
     |
Phase 1: Analyse (parallel)
  - Stratege --> Konzept
  - SEO-Spezialist --> SEO-Audit
     |
Phase 2: Content (sequentiell)
  - Content Creator --> Texte
  - CRO-Optimierer --> Feedback
     |
Phase 3: Umsetzung
  - Landing Page Builder --> Bau
  - SEO --> Schema & Meta
  - CRO --> finale Optimierung
     |
Phase 4: Launch (parallel)
  - Growth Manager --> Promotion
  - CRO --> Tracking & A/B-Tests
```

## Live Landing Pages

**Übersichtsseite:** https://korodur.github.io/Marketing-Team-Skills/

### ARM-Kampagne

| Seite | Link | Status |
|-------|------|--------|
| **Rapid Set ARM v2 (Produktseite)** | [Live](https://korodur.github.io/Marketing-Team-Skills/projekte/korodur-asphalt-repair-mix/landing-page/index.html) | Aktuell — wartet auf Kollegen-Feedback |
| **Print-Onepager A4 einseitig** | [HTML](projekte/korodur-asphalt-repair-mix/print/print-onepager-a4-einseitig.html) | Fertig (03.03.2026) |
| **Print-Onepager A4 zweiseitig** | [HTML](projekte/korodur-asphalt-repair-mix/print/print-onepager-a4-zweiseitig.html) | Fertig (03.03.2026) |

Zielgruppe: Endkunden direkt (Kommunen, GaLa-Bau, Facility Manager, Verarbeiter). Landing Page: Produktinformation ohne Aktionsangebot. Print-Onepager: Postalischer Versand mit Frostschäden-Aufhänger, QR-Code zur Landing Page.

### Weitere Landing Pages

| Produkt | Vollversion | Kurzversion |
|---------|------------|-------------|
| **NEODUR Level** | [Vollversion](https://korodur.github.io/Marketing-Team-Skills/projekte/korodur-neodur-autostore/landing-page/index.html) | [Kurzversion](https://korodur.github.io/Marketing-Team-Skills/projekte/korodur-neodur-autostore/landing-page/index-short.html) |
| **MICROTOP TW** | [Landing Page](https://korodur.github.io/Marketing-Team-Skills/projekte/korodur-microtop-tw/landing-page/index.html) | Trinkwasserbehälter-Beschichtung |

### Archiv

| Seite | Link | Archiviert |
|-------|------|------------|
| ARM v1 Frühjahrsaktion (Voll) | [Ansehen](https://korodur.github.io/Marketing-Team-Skills/projekte/korodur-asphalt-repair-mix/landing-page/archiv/index-v1-fruehjahrsaktion.html) | 27.02.2026 |
| ARM v1 Frühjahrsaktion (Kurz) | [Ansehen](https://korodur.github.io/Marketing-Team-Skills/projekte/korodur-asphalt-repair-mix/landing-page/archiv/index-short-v1-fruehjahrsaktion.html) | 27.02.2026 |

## Projektstruktur

```
index.html        # Übersichtsseite (GitHub Pages Root)
agents/           # Agent-Definitionen (SKILL.md pro Agent)
workflows/        # Workflow-Definitionen
templates/        # Vorlagen (Briefings, etc.)
projekte/         # Landing Pages und Projektdateien
  korodur-asphalt-repair-mix/
    briefing.md                        # Original-Briefing (v1)
    05-briefing-v2-produktseite.md     # Briefing v2 (aktuell)
    06-strategie-update-v2.md          # Strategie v2
    07-seo-update-v2.md                # SEO v2
    08-landing-page-content-v2.md      # Content v2
    09-cro-review-v2.md                # CRO Review v2
    10-briefing-print-onepager.md      # Briefing Print-Onepager
    11-strategie-print-onepager.md     # Print-Strategie
    12-content-print-onepager.md       # Print-Texte
    13-cro-review-print-onepager.md    # CRO-Review Print
    landing-page/
      index.html                       # Aktuelle LP (v2)
      archiv/                          # v1 Versionen
    print/
      print-onepager-a4-einseitig.html   # Variante A (1 Seite)
      print-onepager-a4-zweiseitig.html  # Variante B (2 Seiten)
assets/           # Gemeinsame Assets (Logo, Bilder, Produktfoto)
```

## Quellen & Inspiration

- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills)
- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)
- [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)
