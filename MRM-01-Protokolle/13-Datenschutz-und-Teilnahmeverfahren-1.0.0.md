# MRM-01 · Datenschutz- und Teilnahmeverfahren 1.0.0

**Status:** eingefroren; noch nicht aktiviert  
**Beschlossen:** 2026-07-24  
**Geltungsbereich:** späterer menschlicher Vergleich in Phase 5

## Entscheidung

Für den menschlichen Vergleich wird ein getrennt geöffneter Fragebogen bei
Tally BV, Belgien, vorgesehen. Das Formular darf nicht in die MRM-01-Website
eingebettet werden.

Die Auswahl beruht auf der dokumentierten Anbieterangabe, dass Formulardaten
verschlüsselt übertragen, verschlüsselt gespeichert und in Europa gespeichert
werden. Tally stellt eine Auftragsverarbeitungsvereinbarung bereit und
beschreibt sich für die erhobenen Formulardaten als Auftragsverarbeiter.

## Verbindliche Datenminimierung

Erhoben werden nur eine zufällige Einreichungskennung, die technisch erzeugte
Respondent-ID, Antworten, Einreichungszeitpunkt, Sprachserie, Formularstatus
und getrennte Einwilligungsentscheidungen.

Nicht erhoben werden Name, E-Mail-Adresse, LinkedIn-Profil, Telefonnummer,
Anschrift, besondere Kategorien personenbezogener Daten, Werbedaten oder
Profilingdaten.

Untersagt sind:

- versteckte Felder und URL-Trackingparameter,
- Ländererkennung,
- IP-, E-Mail- oder Social-Login-basierte Dublettenprüfung,
- CRM-, Notion-, Analyse-, Werbe- und E-Mail-Marketingintegrationen,
- automatische Übermittlung von Rohantworten an KI-Dienste,
- vorangekreuzte oder gebündelte Einwilligungen.

## Rechtsgrundlage und Kontrolle

Vorgesehene Rechtsgrundlage ist die ausdrückliche Einwilligung nach Artikel 6
Absatz 1 Buchstabe a DSGVO. Die allgemeine Teilnahme und die optionale
Veröffentlichung anonymer Zitate erhalten getrennte Entscheidungen.

Der Verantwortlichenkontakt lautet `mail@la-mentrepreneur.de`.

Vor Aktivierung müssen Konto, Auftragsverarbeitungsvereinbarung, Anbieterstand,
Formularkonfiguration, Teilnehmerhinweis, Einwilligungsfelder,
Einreichungskennung, Export, Widerruf und Löschung in einem protokollierten
Kontrolllauf verifiziert werden. Diese Aktivierungskontrolle ist eine
Ausführungssperre, keine offene Gestaltungsentscheidung.

## Aufbewahrung

Tally-Einreichungen werden spätestens 30 Tage nach Ende des Antwortfensters
exportiert und aus Konto und Papierkorb gelöscht. Laut Anbieter werden
gelöschte Daten innerhalb von höchstens 90 weiteren Tagen aus
Sicherungskopien entfernt.

Pseudonymisierte Rohdaten und Einwilligungsnachweise werden spätestens 180 Tage
nach Veröffentlichung des Abschlussberichts gelöscht. Irreversibel
anonymisierte Aggregatdaten dürfen erhalten bleiben.

## Änderungsregel

Ein anderer Erhebungsdienst, neue Datenfelder, neue Empfänger, Integrationen,
Tracking, eine andere Rechtsgrundlage oder längere Speicherfristen sind
materielle Änderungen. Sie erfordern vor jeder Erhebung:

1. eine neue versionierte Anbieter- und Datenschutzprüfung,
2. einen ersetzenden Teilnahmehinweis,
3. einen neuen Hash und Freeze,
4. einen append-only Änderungseintrag.

## Quellenstand

Geprüft am 2026-07-24:

- https://eur-lex.europa.eu/eli/reg/2016/679/oj
- https://tally.so/help/gdpr
- https://tally.so/help/data-processing-agreement
- https://tally.so/help/privacy-policy
- https://tally.so/help/how-to-create-a-gdpr-compliant-form
- https://tally.so/help/faq

Der vollständige eingefrorene Teilnehmerhinweis liegt intern unter
`MRM-01-Protokolle/messinstrumente/human-participant-notice-1.0.0.md`.

