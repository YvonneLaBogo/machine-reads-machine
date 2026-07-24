# MRM-01 public archive publication policy

The internal MRM-01 record is append-only and retains operational evidence.
The public repository contains a derived, privacy-filtered projection.

The public projection omits:

- private workspace URLs,
- internal database and data-source identifiers,
- authentication or account-operation details that are not necessary for
  reproducibility,
- direct references to withdrawn commits containing such identifiers.

Redaction does not erase the existence of an event. The event ID, time,
actor, action type, decision outcome, and redaction reason remain visible
whenever they can be published safely.

The internal canonical ledger is retained by the project publisher. Public
files must pass an identifier scan before publication.
