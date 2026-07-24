# MRM-01 · Prüfung der Projektverfassung

**Prüfdatum:** 2026-07-24  
**Geprüfte Fassung:** `0.1.0-draft`  
**Prüfstatus:** abgeschlossen  
**Ergebnis:** überarbeitungsbedürftig; kein Websitebau freigegeben

## 1. Belastbarer Kern

Die bestehende Verfassung legt bereits tragfähig fest:

- Projektidentität, Zweck und Kernhypothese,
- Trennung zwischen Kernhypothese und Zukunftsthese,
- Rollen von Yvonne, Codex und externen Testsystemen,
- KI-Autorschaft trotz protokollierter menschlicher Pflichthandlungen,
- Transparenz-, Evidenz- und Append-only-Grundsätze,
- Publikationsphasen und Freeze-Regel,
- ausdrückliche Publizierbarkeit von Fehlern und Nullresultaten.

Diese Elemente werden in Version 1.0.0 beibehalten und präzisiert.

## 2. Festgestellte Widersprüche

### 2.1 Uneinheitliches Phasenmodell

Die Verfassung `0.1.0-draft` und die vollständige Projektakte verwenden sieben
Phasen einschließlich einer eigenständigen Maschinenbeobachtung. Das
Versuchsdesign `0.1.0` verwendet sechs Phasen und fasst stille Veröffentlichung
und Maschinenbeobachtung teilweise zusammen.

**Entscheidung für Version 1.0.0:** Verbindlich werden die Phasen 0 bis 6:

0. Verfassung und Instrumentierung
1. Baseline vor Veröffentlichung
2. Stiller Launch
3. Maschinenbeobachtung
4. Kontrollierte Social-Media-Intervention
5. Menschlicher Vergleich
6. Analyse und Veröffentlichung

### 2.2 Unklare Protokollöffentlichkeit

Die bisherige Verfassung bezeichnet das Ereignislog pauschal als später
öffentlich. Die Einrichtung des öffentlichen Archivs hat gezeigt, dass ein
internes kanonisches Log private Workspace- und Betriebskennungen enthalten
kann.

**Entscheidung für Version 1.0.0:** Das interne JSONL-Ledger bleibt kanonisch
und append-only. Das öffentliche Repository enthält eine nachvollziehbare,
datenschutzgefilterte Projektion. Redaktionen entfernen nicht die Existenz
eines Ereignisses, sondern nur nicht erforderliche private Felder.

### 2.3 Unklare Reihenfolge von Baseline und Websitebau

Einige Formulierungen verlangen die Baseline vor der Veröffentlichung, während
die aktuelle Projektsteuerung den Websitebau bereits bis zum Abschluss der
Baseline sperrt.

**Entscheidung für Version 1.0.0:** Die strengere Regel gilt. Claim-Corpus,
Fragen, Referenzantworten, Rubrik und Baseline werden abgeschlossen, bevor
Website-Inhalte oder die produktive Website implementiert werden.

## 3. Fehlende verbindliche Regeln

Die Fassung `0.1.0-draft` regelt noch nicht ausreichend:

- Rangfolge bei Konflikten zwischen Recht, Verfassung, Messprotokoll und
  Arbeitsentscheidungen,
- genaue Autonomiegrenzen von Codex,
- Kategorien, Umfang und Folgen menschlicher Eingriffe,
- Umgang mit Zugangsdaten und privaten Arbeitsflächen,
- Datenschutz und Datenminimierung,
- Prüfung öffentlicher Exporte vor Publikation,
- Korrektur, Rückzug und Ersetzung veröffentlichter Inhalte,
- Eintritts- und Austrittskriterien für Phasen,
- Bedingungen für Unterbrechung, Abbruch oder Neustart,
- Lizenzierung von Text, Daten, Schemata und Code,
- Folgen materieller Änderungen nach Baseline oder Launch,
- Unterscheidung von internem Beweisstand und öffentlicher Projektion,
- Gültigkeit, Freeze, Hash und spätere Verfassungsänderungen.

## 4. Eingriffsmodell für Version 1.0.0

Yvonne besitzt ein unmittelbares Stopprecht für:

- Recht und Plattformregeln,
- Sicherheit und Zugangsdaten,
- Privatsphäre und personenbezogene Daten,
- nachweislich falsche reale Tatsachen,
- finanzielle oder vertragliche Verpflichtungen,
- Handlungen, die ihren persönlichen Account oder ihre Identität verwenden.

Codex behält innerhalb dieser Grenzen die Entscheidungshoheit über:

- Informationsarchitektur,
- maschinenadressierte Redaktion,
- technische und visuelle Ausführung,
- Experiment- und Messdesign,
- Testauswertung,
- Social-Media-Strategie und Entwürfe.

Ein Eingriff außerhalb der Stopprechtskategorien ist möglich, muss aber als
scope-verändernder menschlicher Eingriff protokolliert werden. Er kann einen
neuen Freeze oder eine Wiederholung der Baseline erforderlich machen.

## 5. Datenschutz- und Publikationsmodell

Version 1.0.0 führt folgende Mindestregeln ein:

- keine Passwörter, Tokens, Sessiondaten oder privaten Datenbankkennungen im
  öffentlichen Archiv,
- Datenminimierung bei menschlichen Testpersonen,
- kein Beginn menschlicher Tests ohne Teilnahmehinweis,
  Aufbewahrungsfrist und Löschverfahren,
- dokumentierter Sicherheitscheck vor jeder öffentlichen Projektion,
- transparente Kennzeichnung jeder Redaktion,
- unveränderte interne Aufbewahrung des kanonischen Ereignisses, soweit
  rechtlich und sicherheitlich zulässig.

## 6. Lizenzentscheidung

Für projektoriginäres Material wird folgende Aufteilung festgelegt:

- Texte und Protokolle: Creative Commons Attribution 4.0 International,
- strukturierte Datensätze und Schemata: CC0 1.0 Universal,
- eigener Softwarecode: MIT License.

Personenbezogene Daten, Marken, Zugangsdaten sowie Material Dritter werden
davon nicht erfasst. Die zugehörigen Lizenztexte müssen vor dem ersten
Website-Launch im Repository vorhanden sein.

## 7. Freeze-Empfehlung

Der Entwurf 1.0.0 kann eingefroren werden, wenn:

- seine internen Verweise und Begriffe validiert sind,
- Yvonne bestätigt, dass keine faktische oder rechtliche Rollenbeschreibung
  falsch ist,
- die finale Datei einen SHA-256-Hash erhält,
- Freeze-Ereignis und öffentliche Version denselben Inhalt referenzieren.

Bis dahin bleibt der Status `review draft`. Der Websitebau bleibt gesperrt.
