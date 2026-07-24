# MRM-01 · Notion cockpit design

## Decision

Notion will be the operational cockpit, not the canonical evidence ledger.

The canonical event history remains the append-only `outputs/MRM-01-Protokolle/events.jsonl` file and its future public repository mirror. Notion provides a practical human interface for Yvonne and an operational interface for Codex once the connector is installed and authorized.

## Databases

### Decisions

- Decision ID
- Event ID
- Date
- Actor
- Decision
- Rationale
- Status
- Affected claims
- Affected phase

### Claims

- Claim ID
- Exact statement
- Classification: fact, hypothesis, prediction, observation
- Source IDs
- Version introduced
- Verification status
- Last checked
- Public URL

### Sources

- Source ID
- Title
- Publisher
- Primary or secondary
- URL
- Retrieved at
- Supports claim IDs
- Archive reference

### Experiments

- Experiment ID
- Protocol version
- Reader group
- System or participant
- Date
- Question-bank version
- Result status
- Evidence location

### Model responses

- Response ID
- Experiment ID
- System
- Model
- Access surface
- Browsing state
- Prompt
- Raw answer
- Citations
- Score
- Reviewer

### Human responses

- Anonymous participant ID
- Experiment ID
- Consent status
- Raw response
- Score
- Reviewer
- Retention deadline

### Human interventions

- Intervention ID
- Event ID
- Person
- Reason
- Requested change
- Experimental effect
- Outcome

### Website versions

- Version
- Publication date
- Commit or snapshot ID
- Content hash
- Schema version
- Active claim set
- Public URL

### Social posts

- Post ID
- Event ID
- Campaign phase
- Codex objective
- Draft
- Planned time
- Actual time
- Publisher
- LinkedIn URL
- Metrics checkpoints
- Observations

### Corrections

- Correction ID
- Corrected item
- Error
- Detection source
- Resolution
- Published at
- Event ID

## Synchronization rule

Every material Notion record must include its canonical MRM event, claim, response, or post ID. A Notion edit does not change history until an event is appended to the canonical ledger.

## Setup dependency

The Notion connector is not yet installed or authorized. Installation and database creation require separate logged events.
