# MRM-01 · Protokollablage

Dieser Ordner ist der feste, für Yvonne sichtbare Ablageort für alle aktuellen und zukünftigen Protokolle von MACHINE READS MACHINE.

`events.jsonl` is the canonical local event ledger for MACHINE READS MACHINE.

Rules:

1. One JSON object represents one event.
2. Event IDs are permanent and sequential.
3. Existing events are not rewritten or deleted.
4. A correction is a new event with a `corrects_event` field.
5. Unknown historical timestamps remain `null`; they are not reconstructed from memory.
6. Human and AI actions are identified explicitly.
7. Domain availability, purchase intent, registration, DNS configuration, and publication are separate events.

## Inhalt

- `01-Ursprung.md` — Ursprung und geklärtes Briefing
- `02-Projektverfassung.md` — eingefrorene Projektverfassung Version 1.0.0
- `03-Versuchsdesign.md` — Mess- und Vergleichsplan
- `04-Notion-Cockpit.md` — operative Datenbanken
- `05-Social-Media-Protokoll.md` — Codex-geführte LinkedIn-Regeln
- `06-Website-Architektur.md` — maschinennative Seitenstruktur
- `07-Naechste-Schritte.md` — verbindliche Reihenfolge ab Phase 0
- `08-Externe-Arbeitsflaechen.md` — Notion-Cockpit und öffentliches Archiv
- `09-Verfassungspruefung.md` — Prüfung von Fassung 0.1.0 und Entscheidungen für 1.0.0
- `10-Projektverfassung-1.0.0-entwurf.md` — historischer Review-Entwurf vor dem Freeze
- `11-Messdesign-1.0.0.md` — öffentliches, inhaltsfreies Designprotokoll des Messpakets
- `12-Messinstrumente-Commitment-1.0.0.json` — öffentliches Hash-Commitment ohne Claims oder Antworten
- `13-Datenschutz-und-Teilnahmeverfahren-1.0.0.md` — eingefrorene Regeln für den späteren menschlichen Vergleich
- `14-Interventionsprotokoll-1.0.0.md` — eingefrorene Regeln für die spätere LinkedIn-Interventionsserie
- `messinstrumente/` — privates eingefrorenes Messpaket; bis Baseline-Ende nicht öffentlich kopieren
- `events.jsonl` — kanonisches append-only Ereignislog
- `event.schema.json` — Schema der Ereignisdatensätze

Neue Protokolle werden künftig in diesem Ordner oder einem eindeutig benannten
Unterordner abgelegt. Das interne JSONL-Ledger bleibt kanonisch; das öffentliche
Repository enthält die datenschutzgefilterte Projektion nach Verfassung 1.0.0.
