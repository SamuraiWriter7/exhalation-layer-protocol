# Changelog

All notable changes to this project will be documented in this file.

[0.4.0-candidate] - 2026-06-28
Added
Added Memory Breathing Bridge as the fourth schema of the Exhalation Layer Protocol.
Added schemas/memory-breathing-bridge.schema.json.
Added examples/memory-breathing-bridge.example.yaml.
Updated scripts/validate_examples.py to validate:
Exhalation Record
Exhalation Policy
Compression Route
Memory Breathing Bridge
Changed
Extended the protocol from route-based compression to memory-cycle integration.
Added support for:
source artifact mapping;
memory layer targeting;
memory action definition;
breathing cycle placement;
retention strategy;
forgetting boundaries;
trace continuity;
memory pressure and amnesia risk expectations.
Design Principle

Established the v0.4 principle:

Exhale without severing memory.

Positioning
v0.1 records what was exhaled.
v0.2 defines when and how exhalation is allowed.
v0.3 defines where computational exhaust flows.
v0.4 defines how exhaled or compressed material reconnects to memory breathing.

This makes the protocol ready for deeper integration with memory compression, structural rumination, trace continuity, and reusable kata formation.

[0.3.0-candidate] - 2026-06-28
Added
Added Compression Route as the third schema of the Exhalation Layer Protocol.
Added schemas/compression-route.schema.json.
Added examples/compression-route.example.yaml.
Updated scripts/validate_examples.py to validate:
Exhalation Record
Exhalation Policy
Compression Route
Changed
Extended the protocol from policy-based exhalation to route-based compression.
Added support for:
route source definition;
route triggers;
ordered route steps;
intelligence preservation methods;
destination mapping;
quality and origin-loss risk control;
storage, compute, and reuse expectations.
Design Principle

Established the v0.3 principle:

Do not compress blindly. Route the breath.

Positioning
v0.1 records what was exhaled.
v0.2 defines when and how exhalation is allowed.
v0.3 defines where computational exhaust flows after the exhalation decision.

This makes the protocol ready for future memory breathing bridges, agent hooks, trace routing, and reusable pattern libraries.

## [0.2.0-candidate] - 2026-06-27

### Added

* Added `Exhalation Policy` as the second schema of the Exhalation Layer Protocol.
* Added `schemas/exhalation-policy.schema.json`.
* Added `examples/exhalation-policy.example.yaml`.
* Updated `scripts/validate_examples.py` to validate both:

  * `Exhalation Record`
  * `Exhalation Policy`

### Changed

* Extended the protocol from exhalation event recording to exhalation decision policy.
* Added support for:

  * scope definition;
  * trigger conditions;
  * exhaust classification;
  * decision rules;
  * quality risk limits;
  * human review boundaries;
  * result expectations.

### Design Principle

* Established the v0.2 principle:

  > Exhale by policy, not by impulse.

### Positioning

* `v0.1` records what was exhaled.
* `v0.2` defines when and how exhalation should be allowed.

This makes the protocol safer for future AI agent hooks, memory compression bridges, and automatic computational cleanup.

## [0.1.0-candidate] - 2026-06-27

### Added

* Introduced `Exhalation Record` as the first schema of the Exhalation Layer Protocol.
* Added `schemas/exhalation-record.schema.json`.
* Added `examples/exhalation-record.example.yaml`.
* Added validation script at `scripts/validate_examples.py`.
* Added GitHub Actions workflow for schema/example validation.
* Defined the initial scope of the protocol as computational exhalation, compression, discard, archive, detach, and reusable pattern extraction.

### Design Principle

* Established the core principle:

  > Do not store exhaust as intelligence.

### Positioning

* Positioned this repository as the **Exhaust & Compression Wing** of the Computational Pranayama architecture.
* Defined the first bridge toward:

  * Computational Pranayama Protocol
  * Auto-Pranayama Protocol
  * Kazene Memory Breathing Protocol
  * AI Search Trace Receipt Standard
  * Structural Rumination Layer
