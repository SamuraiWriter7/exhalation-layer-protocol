# Changelog

All notable changes to this project will be documented in this file.

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
