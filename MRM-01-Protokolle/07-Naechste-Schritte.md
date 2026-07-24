# MRM-01 · Nächste Schritte

**Beschlossen am:** 2026-07-23  
**Aktuelle Phase:** Phase 0 — Verfassung und Instrumentierung  
**Websitebau:** noch nicht freigegeben

## Verbindliche Reihenfolge

### 1. Projektübergabe abschließen

Die vollständige Projektakte und der Ordner `MRM-01-Protokolle` werden in das neu eingerichtete Codex-Projekt übernommen. `AGENTS.md` und `PROJECT.md` bleiben als automatisch lesbare Steuerdateien an der Projektwurzel.

### 2. Domainstatus bestätigen

Yvonne bestätigt, ob `machine-reads-machine.org` tatsächlich registriert wurde. Registrierung, Registrar und Registrierungsdatum werden als separates Ereignis protokolliert. DNS und Hosting werden noch nicht verändert.

### 3. Notion-Cockpit einrichten

Die Notion-Verbindung wird installiert und autorisiert. Danach legt Codex die bereits definierten Datenbanken für Decisions, Claims, Sources, Experiments, Responses, Interventions, Versions, Social Posts und Corrections an.

Notion ist die operative Oberfläche. Das JSONL-Ereignislog bleibt die kanonische Historie.

### 4. Öffentliches Versionsarchiv einrichten

Ein öffentliches Git-Repository wird erstellt. Die aktuelle Projektakte, Protokolle, Schemata und späteren Website-Stände werden dort nachvollziehbar versioniert. Der erste öffentliche Stand erhält einen Hash und eine protokollierte Versionsnummer.

### 5. Projektverfassung 1.0 einfrieren

Codex prüft die Verfassung auf Widersprüche und ergänzt mindestens:

- Autonomiegrenzen,
- erlaubte menschliche Eingriffe,
- Datenschutzregeln,
- Korrekturverfahren,
- Abbruchbedingungen,
- Lizenzierung,
- Phasenwechsel-Regeln.

Nach der Freigabe wird Version 1.0.0 eingefroren. Spätere Änderungen dürfen frühere Ergebnisse nicht rückwirkend umdeuten.

### 6. Messinstrumente entwickeln

Vor jedem Websitebau erstellt Codex:

- den ersten Claim-Corpus,
- das Quellenregister,
- die semantische Testmarke,
- den festen Fragenkatalog,
- erwartete Referenzantworten,
- die Bewertungsrubrik,
- das Testprotokoll für ChatGPT, Claude, Gemini und Perplexity,
- den Teilnahme- und Datenschutzhinweis für Menschen.

### 7. Baseline durchführen

Die festgelegten Fragen werden vor Veröffentlichung der Website an alle ausgewählten Systeme gestellt. Antworten, Nichtwissen, falsche Zuordnungen und Halluzinationen werden unverändert gespeichert und bewertet.

### 8. Technische Plattformentscheidung treffen

Codex prüft Webflow gegen die eingefrorenen Anforderungen. Erst danach wird entschieden, ob Webflow allein genügt oder eine zusätzliche statische Schicht erforderlich ist.

### 9. Website bauen und prüfen

Codex erstellt die maschinennative Website, validiert HTML, strukturierte Daten, Root-Dateien, Links, Claim-IDs, Versionen und Inhalts-Hashes. Der Launch benötigt einen eigenen Phasenwechsel-Eintrag.

### 10. Stiller Launch

Die Website wird ohne LinkedIn-Kommunikation veröffentlicht. Die Dauer der stillen Beobachtungsphase wird vorab festgelegt. Während dieser Zeit laufen nur die eingefrorenen Maschinentests.

### 11. LinkedIn-Intervention

Erst nach der stillen Phase beginnt die von Codex gesteuerte LinkedIn-Kampagne. Jeder Beitrag erhält eine Post-ID, Offenlegung, Zeitmarke und Messpunkte.

## Unmittelbar benötigte Information von Yvonne

Der einzige aktuell blockierende Sachverhalt ist:

> Ist `machine-reads-machine.org` inzwischen vollständig registriert?

Alle anderen Entscheidungen trifft Codex innerhalb der Projektverfassung.

## Startauftrag für das neue Codex-Projekt

> Lies `PROJECT.md`, `AGENTS.md`, die vollständige Projektakte und alle Dateien im Ordner `MRM-01-Protokolle`. Übernimm MRM-01 in Phase 0. Prüfe zuerst die Projektverfassung auf Widersprüche und fehlende experimentelle Regeln. Entwirf anschließend Version 1.0.0, ohne Website-Content oder Design zu erstellen. Frage Yvonne nur nach Informationen, die rechtlich, faktisch oder technisch nicht von Codex entschieden werden können. Protokolliere jede materielle Entscheidung im append-only Ereignislog.

