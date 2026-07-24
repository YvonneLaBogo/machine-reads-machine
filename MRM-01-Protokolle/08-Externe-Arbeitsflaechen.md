# MRM-01 · Externe Arbeitsflächen

**Status:** Phase 0  
**Kanonische Historie:** `MRM-01-Protokolle/events.jsonl`

## Notion-Cockpit

**Status:** eingerichtet und privat  
**Öffentliche Kennungen:** keine

Notion ist die operative Oberfläche. Ein Notion-Eintrag verändert die
Projektgeschichte erst, wenn ein entsprechendes Ereignis im kanonischen
JSONL-Log ergänzt wurde.

Das Cockpit umfasst zehn operative Datenbanken: Decisions, Claims, Sources,
Experiments, Model Responses, Human Responses, Human Interventions, Website
Versions, Social Posts und Corrections. Private Workspace-URLs und interne
Data-Source-IDs werden nicht im öffentlichen Archiv publiziert.

## Öffentliches Versionsarchiv

**Repository:** https://github.com/YvonneLaBogo/machine-reads-machine  
**Sichtbarkeit:** öffentlich  
**Status:** erster öffentlicher Snapshot verifiziert  
**Snapshot-ID:** `MRM-ARCHIVE-0.1.1-SANITIZED`

Das GitHub-Plugin ist installiert und mit dem Konto `YvonneLaBogo` verbunden.
Das Repository wurde über die GitHub-Oberfläche angelegt und anschließend von
`maschine-reads-maschine` auf den kanonischen Namen `machine-reads-machine`
korrigiert.

Der bereinigte öffentliche Stand enthält Projektakte, vollständige Projektakte,
Projektsteuerung, kanonische Protokolle, Ereignisschema, append-only
Ereignislog, Snapshot-Manifest sowie den als nichtkanonisch gekennzeichneten
provisorischen Fortsetzungsdatensatz. Das Ereignislog im öffentlichen
Repository ist eine privacy-gefilterte Projektion des internen kanonischen
Logs. Die Bereinigung ist unter `MRM-E0034` dokumentiert.
