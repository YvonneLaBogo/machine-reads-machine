# MRM-01 · Messdesign 1.0.0

**Status:** maschinelles Messpaket intern eingefroren  
**Freeze-Datum:** 2026-07-24  
**Primärsprache:** Englisch  
**Websitebau:** weiterhin gesperrt

## Umfang

Das eingefrorene maschinelle Messpaket enthält:

- 10 Quellenregistereinträge,
- 29 atomare Claims,
- 20 Fragen,
- 20 Referenzantworten,
- eine Vier-Punkte-Bewertungsrubrik,
- ein Modelltestprotokoll,
- ein Antwortdatenschema,
- eine kontrollierte synthetische Relationsmarke.

## Claim-Gruppen

Der Corpus kombiniert:

- stabile Projektidentität und Rollen,
- Governance- und Provenienzbeziehungen,
- Verfassungs-, Phasen- und Versionsfakten,
- drei externe Webstandard-Bereiche als positive Kontrolle,
- die Primärhypothese und die Zukunftsthese mit korrekter Klassifikation,
- eine künstliche Relation als negative und spätere Retrieval-Kontrolle.

Zeitabhängige Aussagen wurden auf einen festen Zeitpunkt bezogen, damit sie
nach späteren Phasenwechseln nicht falsch werden.

## Kontaminationsschutz

Das öffentliche GitHub-Archiv existiert bereits und ist deshalb ein bekannter
Bestandteil der Vorabexposition. Dieser Umstand wird nicht verborgen.

Bis zum Ende der Baseline bleiben jedoch geheim:

- Claim-Aussagen,
- Fragen und Reihenfolge,
- Referenzantworten,
- Details der Testmarke,
- Rubrikdetails und Modellinstruktion.

Vor der Baseline wird öffentlich ausschließlich ein kryptografisches
Commitment aus Dateinamen, Byteanzahl und SHA-256-Hashes archiviert. Nach
Abschluss der Baseline können die eingefrorenen Inhalte veröffentlicht und
gegen dieses Commitment geprüft werden.

## Primärsprache

Englisch ist die normative Primärsprache. Eine deutsche Fassung darf nur als
separate, eigenständig versionierte Replikationsserie durchgeführt werden.
Ergebnisse unterschiedlicher Sprachserien werden nicht zusammengeführt.

## Testmatrix

Vorgesehen sind ChatGPT, Claude, Gemini und Perplexity. Pro Frage wird, soweit
zuverlässig wählbar, je ein Lauf mit Browsing oder Suche aus und ein Lauf mit
Browsing oder Suche an durchgeführt. Jede Frage erhält eine neue Sitzung.

Maximaler Umfang der Baseline:

`20 Fragen × 4 Systeme × 2 Modi = 160 Aufrufe`

Nicht verfügbare Modi und technische Fehler werden als eigene Ergebnisse
erfasst und nicht als falsche Antworten umgedeutet.

## Noch nicht eingefroren

Der Teilnahme- und Datenschutzhinweis für den späteren menschlichen Vergleich
bleibt Entwurf. Vor seiner Freigabe fehlen:

- Kontaktadresse der Verantwortlichen,
- endgültige Rechtsgrundlage,
- Auswahl und Prüfung des Erhebungssystems,
- Auftragsverarbeitungs- und Drittlandprüfung,
- endgültige Lösch- und Widerrufsprozesse.

Phase 0 ist deshalb noch nicht abgeschlossen. Die maschinelle Baseline beginnt
erst, wenn sämtliche in Verfassung 1.0.0 verlangten Artefakte freigegeben sind.
