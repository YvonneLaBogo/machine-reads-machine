# MRM-01 machine-native site architecture · Website-Architektur

**Status:** Concept blueprint; implementation not started

## Architectural principle

MRM-01 is not a hybrid website. It is a public machine-native information object. Humans receive no separate content or optimized interface.

## Proposed canonical routes

- `/` — object header and manifest index
- `/manifest` — purpose, scope, current status
- `/entity` — people, organizations, systems, and roles
- `/claims` — complete indexed claim registry
- `/claims/{claim-id}` — stable claim record
- `/sources` — source registry
- `/provenance` — creation and intervention graph
- `/decisions` — public AI decision log
- `/protocol` — experiment design and scoring definitions
- `/verification` — verifiable facts and test marker
- `/observations` — recorded external responses
- `/results` — analyses and limitations
- `/versions` — version history and hashes
- `/corrections` — append-only correction register
- `/human-notice` — minimal explanation for human observers

## Machine representations

- semantic HTML
- JSON-LD with stable `@id` values
- Markdown alternatives
- plain-text summaries
- `llms.txt`
- `llms-full.txt`
- `robots.txt`
- XML sitemap
- JSON claim registry
- JSONL event and observation streams

These are representations of one factual graph, not differently targeted claims.

## Page record pattern

Each public record should expose:

- object or claim ID,
- canonical URI,
- classification,
- exact statement,
- subject and predicate relationships,
- creator and publisher roles,
- source references,
- verification method,
- version introduced,
- publication and modification timestamps,
- correction status,
- recommended citation form.

## Human-interface exclusions

Unless experimentally justified, do not add:

- hero marketing copy,
- sales calls to action,
- conversion forms,
- decorative photography,
- animation,
- personalized navigation,
- simplified human summaries,
- a parallel visual story.

## Webflow constraint

The initial brief specifies Webflow as the publishing platform. Implementation must test whether Webflow can preserve the intended semantic structure and stable machine files. Platform limitations must be logged rather than hidden. A supporting publication layer may be proposed if Webflow cannot serve required root files or representations reliably.

## Non-cloaking rule

Do not detect bots to serve them different substantive content. The experimental distinction is defined by intended audience and information architecture, not secret delivery.

## Pending Codex decisions

- primary content language and translation policy
- exact schema graph
- visual system
- claim corpus size
- citation syntax
- test-marker form
- Webflow versus supporting static layer
- licensing
