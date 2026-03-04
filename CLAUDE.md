# Marketing Team Skills - Claude Code Anweisungen

## Projektbeschreibung

Dieses Projekt definiert ein Team aus 12 KI-Agents für Marketing, Vertrieb und Operations — von Landing Pages über CRM bis IT-Infrastruktur.

## Agents

Die Agent-Definitionen liegen unter `agents/`. Jeder Agent hat eine SKILL.md Datei mit:
- Rollenbeschreibung und Verantwortlichkeiten
- Verfügbare Skills und deren Anwendung
- Input/Output-Spezifikation
- Qualitätskriterien

## Workflow

Der Projektleiter-Agent (Agent 0) orchestriert den Ablauf. Siehe `workflows/landing-page-workflow.md` für den vollständigen Prozess.

## Konventionen

- Sprache: Deutsch (Projektdokumentation), Englisch (Code/technische Begriffe)
- Jeder Agent arbeitet auf Basis eines Briefings vom Projektleiter
- Ergebnisse werden immer vom Projektleiter geprüft bevor sie weitergehen
- Qualität vor Geschwindigkeit
