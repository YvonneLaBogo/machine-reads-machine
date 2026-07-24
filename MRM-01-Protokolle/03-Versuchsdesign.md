# MRM-01 experiment design · Versuchsdesign

**Status:** Working draft  
**Protocol version:** 0.1.0

## Research question

Can independent AI systems recover the intended factual and relational structure of an AI-native website more accurately than human readers of the same public object?

## Units of evidence

The site will publish a fixed corpus containing:

- entity facts,
- numbered hypotheses,
- externally verifiable claims,
- provenance relationships,
- version relationships,
- a unique semantic test marker,
- corrections introduced only through logged versions.

Each material statement receives a claim ID. The initial corpus is frozen before publication.

## Comparison groups

### Machine readers

At minimum:

- ChatGPT
- Claude
- Gemini
- Perplexity

Model name, access surface, browsing state, prompt, date, locale, and visible citations must be recorded where available.

### Human readers

Participants recruited through the public LinkedIn phase will inspect the same website without a separate human version. They will answer the same factual and relational questions. Participation terms, privacy treatment, and data retention must be defined before recruitment.

## Primary measures

1. Claim accuracy
2. Claim completeness
3. Entity resolution
4. Relationship accuracy
5. Fact versus hypothesis classification
6. Version recognition
7. Source attribution
8. Direct citation
9. Unsupported additions
10. Persistence across repeated tests

## Scoring principle

Scoring rules and expected answers must be frozen before the first live test. Free-text answers should be scored without knowledge of the respondent group where practical.

## Phases

### Phase 0 — Instrumentation

Freeze constitution, corpus, question bank, scoring rubric, event schema, and intervention policy.

### Phase 1 — Baseline

Ask the fixed questions before the domain publishes the corpus. Preserve null results and accidental name collisions.

### Phase 2 — Silent launch

Publish the complete machine-native object without LinkedIn promotion. Observe technical discovery and model retrieval.

### Phase 3 — Controlled social intervention

Codex begins the logged LinkedIn campaign. Each post becomes a timed intervention. Continue the same machine tests.

### Phase 4 — Human comparison

Invite human readers to inspect the unchanged object and answer the frozen question bank.

### Phase 5 — Analysis

Report findings, uncertainty, confounds, null results, and corrections. Do not treat visibility or engagement as proof of comprehension.

## Known confounds

- Search indexing and model training are different mechanisms.
- Answer engines may share search indexes or downstream sources.
- LinkedIn attention creates external signals and cannot be treated as neutral exposure.
- Model versions and browsing modes change over time.
- Human volunteers recruited from LinkedIn are not representative of all web users.
- The site is intentionally optimized for machine readers, so the comparison tests a designed advantage rather than general intelligence.

## Required pre-launch artifacts

- frozen claim corpus
- frozen question bank
- scoring rubric
- baseline response format
- human participant notice
- data retention rules
- crawler access matrix
- publication checksum
