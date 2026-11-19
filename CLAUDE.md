# CLAUDE.md – legal-tech-portfolio

## Zweck
Öffentliches Portfolio von Aron Schlüter für Bewerbungen als Legal Engineer:
Skills, n8n-Workflows, agentische Systeme und Konzepte für juristische Anwendungsfälle.
Jede Datei ist öffentlich sichtbar und muss als professioneller Arbeitsnachweis taugen.

## Struktur
- `skills/` – Claude Skills (je Ordner eine SKILL.md, ggf. assets/ und references/)
- `n8n-workflows/` – exportierte n8n-Workflows (JSON) mit README und Screenshot
- `konzepte/` – Architektur- und Konzeptstudien (z. B. Behörden-App)
- `fallstudien/` – anonymisierte Praxisprojekte
- `lernpfad/` – Übungen zur Claude-API und zu Python
- `docs/` – Setup-Anleitungen (z. B. n8n lokal, MCP-Anbindung)

## Pflichtregeln
1. Keine Secrets: keine API-Keys, Tokens, Passwörter, keine `.env`. Credentials in n8n nur per Name referenzieren.
2. Keine personenbezogenen Daten: keine privaten E-Mail-Adressen, keine Mandats-, Kanzlei- oder Mitarbeiterdaten. Nur Testdaten oder öffentliche Beispiele.
3. Keine Drittinhalte ohne Lizenz: fremde API-Specs, Dokumente oder Texte verlinken statt kopieren.
4. Vor jedem Commit prüfen: `git status` und `git diff --staged` auf Secrets und personenbezogene Daten durchsehen.

## Aufbau jeder Projekt-README
Problem · Lösung · Architektur (Skizze) · Datenschutz/Compliance · Setup · Grenzen/Haftungshinweis

## Konventionen
- Sprache: Deutsch, Fachbegriffe dürfen englisch bleiben.
- Commit-Messages: kurz, im Imperativ, deutsch (z. B. „CompanyCheck-Workflow ergänzen“).
- n8n: Workflows über den MCP-Server der lokalen Instanz (localhost:5678) lesen und bauen.