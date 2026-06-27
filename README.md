# Exhalation Layer Protocol

**Exhalation Layer Protocol** is a specification for computational exhalation in AI systems.

It defines how redundant output, stale traces, excessive context, obsolete routes, duplicated reasoning patterns, and low-value computational residue can be compressed, discarded, archived, detached, reviewed, recycled, or routed back into memory breathing while preserving reusable intelligence and trace continuity.

## Core Principle

> Do not store exhaust as intelligence.

AI systems should not preserve every output, trace, route, or generated artifact as if it were meaningful intelligence.

Some generated material is useful.
Some is residue.
Some is reusable only after compression.
Some should be archived.
Some should be discarded.
Some requires human review before release.
Some should be converted into reusable patterns.

The Exhalation Layer exists to distinguish these cases.

## Position in the Pranayama Architecture

The Computational Pranayama family can be understood as a metabolism stack:

```text
Computational Pranayama Protocol
= Breath Core / Metabolism Layer

auto-pranayama-protocol
= Self-Regulation Wing

exhalation-layer-protocol
= Exhaust & Compression Wing

collective-pranayama-protocol
= Collective Rhythm Wing
```

This repository defines the **Exhaust & Compression Wing**.

It does not replace the Breath Core.
It extends it by defining how AI systems release, compress, review, recycle, route, and reconnect computational residue to memory breathing cycles.

## Version Overview

```text
v0.1 Exhalation Record
= Records what was exhaled, compressed, discarded, archived, detached, or recycled.

v0.2 Exhalation Policy
= Defines when and how exhalation is allowed, required, delayed, or escalated to human review.

v0.3 Compression Route
= Defines where computational exhaust flows after the exhalation decision.

v0.4 Memory Breathing Bridge
= Defines how exhaled or compressed material reconnects to memory breathing.

v0.5 Agent Exhalation Hook
= Defines how AI agents safely detect, invoke, prepare, or execute exhalation flows.
```

## First Arc

The first arc of the Exhalation Layer Protocol is:

```text
Record
→ Policy
→ Route
→ Memory Bridge
→ Agent Hook
```

Together, these layers define a minimal flow:

```text
Detect exhaust
→ Check policy
→ Select route
→ Preserve memory continuity
→ Attach trace
→ Review or execute
```

This turns computational exhalation from simple cleanup into a trace-aware metabolic process.

## v0.1 — Exhalation Record

Version `v0.1.0-candidate` introduced the **Exhalation Record**.

An Exhalation Record describes:

* what computational material was targeted;
* why it was considered exhaust;
* what action was applied;
* whether reusable intelligence was preserved;
* whether a trace was attached;
* what reduction or risk resulted from the action.

### Core Principle

> Do not store exhaust as intelligence.

### Example

```yaml
exhalation_id: "exhalation-001"
version: "0.1.0-candidate"

target:
  type: "stale_trace"
  reference_id: "trace-2026-001"
  origin_protocol: "computational-pranayama-protocol"

reason:
  category: "redundant_output"
  description: "The trace duplicates an already preserved breathing pattern and no longer needs to be stored in full."
  severity: "medium"

action:
  type: "compress"
  method: "summary_retention"
  preserves_intelligence: true

recycle:
  reusable_pattern: true
  pattern_id: "kata-reuse-001"
  reuse_target: "future lightweight response routing"

trace:
  attached: true
  trace_id: "trace-2026-001"
  source_protocol: "computational-pranayama-protocol"

result:
  storage_reduced: true
  compute_pressure_reduced: true
  intelligence_preserved: true
  quality_risk: "low"
  notes: "The redundant trace was compressed into a reusable kata pattern."
```

## v0.2 — Exhalation Policy

Version `v0.2.0-candidate` introduced the **Exhalation Policy**.

While `v0.1` defines how to record an exhalation event, `v0.2` defines how an AI system decides whether exhalation is allowed, required, delayed, or escalated to human review.

### Core Principle

> Exhale by policy, not by impulse.

AI systems should not discard, compress, or recycle computational material merely because it appears redundant.
Exhalation must be guided by explicit policy.

The Exhalation Policy defines:

* what kinds of material are covered;
* what triggers activate exhalation;
* how computational exhaust is classified;
* which actions are permitted;
* what quality risk is acceptable;
* when human review is required;
* what reduction and preservation targets are expected.

### Why Policy Matters

Without policy, exhalation becomes destructive forgetting.

With policy, exhalation becomes intelligent release.

This layer prevents AI systems from confusing:

* exhaust with intelligence;
* compression with deletion;
* reuse with distortion;
* automatic cleanup with loss of origin;
* efficiency with structural amnesia.

### Example

```yaml
policy_id: "exhalation-policy-001"
version: "0.2.0-candidate"

scope:
  applies_to:
    - "stale_trace"
    - "redundant_output"
    - "overlong_generation"
    - "noisy_context"
  default_mode: "compress"
  linked_protocols:
    - "computational-pranayama-protocol"
    - "auto-pranayama-protocol"
    - "kazene-memory-breathing-protocol"

triggers:
  - type: "compute_pressure"
    threshold: "The current output or trace volume exceeds the lightweight route budget."
    priority: "high"
  - type: "trace_duplication"
    threshold: "The trace repeats an already preserved kata or route pattern."
    priority: "medium"

classification:
  exhaust_categories:
    - "duplicate"
    - "stale"
    - "overlong"
    - "noisy"
  intelligence_preservation_required: true
  minimum_preservation_method: "summary_retention"

decision_rules:
  - rule_id: "rule-compress-duplicate-trace"
    when:
      category: "trace_duplication"
      severity: "medium"
    action:
      type: "compress"
      method: "summary_retention"
    quality_risk_limit: "low"
    requires_trace_attachment: true

  - rule_id: "rule-recycle-overlong-output"
    when:
      category: "compute_pressure"
      severity: "high"
    action:
      type: "recycle"
      method: "kata_reuse"
    quality_risk_limit: "medium"
    requires_trace_attachment: false

human_review_boundary:
  required: true
  conditions:
    - "high_quality_risk"
    - "uncertain_origin"
    - "legal_or_royalty_relevance"
    - "loss_of_unique_trace"
  review_note: "Automatic exhalation must stop when the target may contain unique origin, legal, royalty, or high-value trace information."

result_expectation:
  storage_reduction_target: "medium"
  compute_pressure_reduction_target: "medium"
  quality_preservation_target: "strict"
  notes: "The policy favors compression and pattern reuse over full discard."
```

## v0.3 — Compression Route

Version `v0.3.0-candidate` introduced the **Compression Route**.

While `v0.1` records exhalation events and `v0.2` defines exhalation policy, `v0.3` defines how computational exhaust moves through a route toward compression, archival, pattern reuse, detachment, discard, or human review.

### Core Principle

> Do not compress blindly. Route the breath.

AI systems should not compress computational material without knowing where the preserved intelligence, trace value, or reusable pattern will go.

The Compression Route defines:

* what material enters the route;
* what trigger activated routing;
* which ordered steps are applied;
* how intelligence is preserved;
* where the routed material is sent;
* what quality and origin-loss risks exist;
* what storage, compute, and reuse outcomes are expected.

### Why Routing Matters

Without routing, compression becomes a black box.

With routing, compression becomes a visible path.

This layer prevents AI systems from confusing:

* compression with disappearance;
* archival with forgetting;
* pattern reuse with distortion;
* trace detachment with origin loss;
* discard with safe exhalation.

### Example

```yaml
route_id: "compression-route-001"
version: "0.3.0-candidate"

source:
  target_type: "stale_trace"
  reference_id: "trace-2026-001"
  linked_policy_id: "exhalation-policy-001"
  linked_exhalation_id: "exhalation-001"

route_trigger:
  type: "trace_duplication"
  severity: "medium"
  description: "The trace duplicates an already preserved breathing pattern and can be compressed into a reusable summary."

route_path:
  mode: "summary_then_archive"
  steps:
    - step_id: "step-summarize"
      action: "summarize"
      method: "summary_retention"
      output_reference: "summary-trace-2026-001"

    - step_id: "step-extract-pattern"
      action: "extract_pattern"
      method: "pattern_retention"
      output_reference: "pattern-kata-reuse-001"

    - step_id: "step-archive-original"
      action: "archive"
      method: "cold_storage"
      output_reference: "archive-trace-2026-001"

preservation:
  intelligence_preserved: true
  preservation_method: "pattern_retention"
  preserved_reference_id: "pattern-kata-reuse-001"
  reusable_pattern: true

destination:
  type: "pattern_library"
  destination_id: "kata-reuse-library"
  linked_protocol: "kazene-memory-breathing-protocol"

risk_control:
  quality_risk: "low"
  origin_loss_risk: "low"
  requires_human_review: false
  review_reason: "No unique origin or legal attribution risk was detected."

result_expectation:
  storage_reduction: "medium"
  compute_pressure_reduction: "medium"
  reuse_value: "high"
  notes: "The stale trace is compressed into a reusable kata pattern while the original is retained in cold archive."
```

## v0.4 — Memory Breathing Bridge

Version `v0.4.0-candidate` introduced the **Memory Breathing Bridge**.

While `v0.1` records exhalation events, `v0.2` defines exhalation policy, and `v0.3` defines compression routes, `v0.4` connects exhaled or compressed computational material to memory breathing cycles.

### Core Principle

> Exhale without severing memory.

AI systems should not treat exhalation as simple deletion.

Material may be compressed, archived, converted into patterns, or forgotten, but memory continuity must be preserved when the material contains reusable intelligence, trace value, origin value, or structural learning.

The Memory Breathing Bridge defines:

* what exhalation-layer artifact enters the memory bridge;
* which memory layer receives it;
* what memory action is applied;
* how it participates in the breathing cycle;
* how intelligence is retained;
* when forgetting is allowed;
* how trace continuity is preserved;
* what memory pressure, reuse, and amnesia risks are expected.

### Why Memory Breathing Matters

Without memory breathing, exhalation becomes isolated cleanup.

With memory breathing, exhalation becomes part of a larger metabolism.

This layer prevents AI systems from confusing:

* forgetting with release;
* compression with memory death;
* pattern extraction with context loss;
* exhalation with structural amnesia;
* trace preservation with full storage.

### Example

```yaml
bridge_id: "memory-breathing-bridge-001"
version: "0.4.0-candidate"

source:
  source_type: "compression_route"
  reference_id: "compression-route-001"
  linked_exhalation_id: "exhalation-001"
  linked_route_id: "compression-route-001"

memory_mapping:
  target_memory_layer: "compressed_memory"
  memory_action: "convert_to_pattern"
  preserved_form: "implicit_kata"
  memory_reference_id: "memory-kata-reuse-001"

breathing_cycle:
  cycle_stage: "compaction"
  cycle_role: "reuse_gate"
  linked_memory_protocol: "kazene-memory-breathing-protocol"

retention_strategy:
  retain_intelligence: true
  retention_method: "implicit_kata_retention"
  retention_priority: "high"

forgetting_boundary:
  forgetting_allowed: true
  boundary_type: "trace_required"
  boundary_note: "The original material may be forgotten only after trace continuity and reusable pattern preservation are confirmed."

trace_continuity:
  trace_preserved: true
  continuity_method: "route_reference"
  trace_id: "trace-2026-001"

result_expectation:
  memory_pressure_reduced: true
  intelligence_preserved: true
  reuse_enabled: true
  amnesia_risk: "low"
  notes: "The compressed route is converted into an implicit kata while trace continuity remains available through the route reference."
```

## v0.5 — Agent Exhalation Hook

Version `v0.5.0-candidate` introduces the **Agent Exhalation Hook**.

While `v0.1` records exhalation events, `v0.2` defines exhalation policy, `v0.3` defines compression routes, and `v0.4` connects exhaled material to memory breathing, `v0.5` defines how AI agents can safely detect computational exhaust and invoke the exhalation flow.

### Core Principle

> Agents may exhale, but never silently.

AI agents may detect redundant output, stale traces, memory pressure, compute pressure, route obsolescence, or low-reuse material.

However, they should not silently compress, discard, detach, or recycle material without policy, traceability, routing, memory continuity, and review boundaries.

The Agent Exhalation Hook defines:

* which agent detected the exhaust condition;
* what signal triggered the hook;
* what target was detected;
* which policy was invoked;
* which compression route was selected;
* whether memory continuity is required;
* whether automatic execution is allowed;
* when human review is required;
* how traceability is preserved;
* what result is expected.

### Why Agent Hooks Matter

Without agent hooks, exhalation remains a manual cleanup layer.

With agent hooks, exhalation becomes an AI-operable metabolic reflex.

This layer prevents AI systems from confusing:

* autonomous cleanup with silent deletion;
* agent judgment with policy authorization;
* route selection with final execution;
* memory compression with memory loss;
* trace attachment with full accountability.

### Example

```yaml
hook_id: "agent-exhalation-hook-001"
version: "0.5.0-candidate"

agent:
  agent_id: "memory-agent-001"
  agent_type: "memory_agent"
  autonomy_level: "human_supervised"
  execution_context: "multi_turn"

detection:
  signal_type: "trace_duplication"
  confidence: "high"
  detected_target:
    type: "stale_trace"
    reference_id: "trace-2026-001"
  evidence:
    - "The target trace repeats an already preserved kata pattern."
    - "A compression route and memory bridge are available for this target."

policy_invocation:
  policy_id: "exhalation-policy-001"
  decision: "allow"
  action_allowed: true
  quality_risk_limit: "low"

route_invocation:
  route_id: "compression-route-001"
  route_mode: "summary_then_archive"
  selected: true

memory_bridge_invocation:
  bridge_required: true
  bridge_id: "memory-breathing-bridge-001"
  memory_continuity_required: true
  memory_action: "convert_to_pattern"

execution_boundary:
  automatic_execution_allowed: false
  human_review_required: true
  stop_conditions:
    - "uncertain_origin"
    - "legal_or_royalty_relevance"
    - "loss_of_unique_trace"
    - "memory_bridge_missing"
  boundary_note: "The agent may recommend exhalation, but final execution requires human review when origin or trace value may be affected."

traceability:
  trace_attached: true
  trace_id: "trace-2026-001"
  chain_links:
    - kind: "exhalation_policy"
      reference_id: "exhalation-policy-001"
    - kind: "compression_route"
      reference_id: "compression-route-001"
    - kind: "memory_breathing_bridge"
      reference_id: "memory-breathing-bridge-001"

result_expectation:
  exhalation_executed: false
  compute_pressure_reduced: true
  memory_pressure_reduced: true
  intelligence_preserved: true
  quality_risk: "low"
  notes: "The agent prepares a safe exhalation path but leaves final execution to human review."
```

## Repository Structure

```text
schemas/
  exhalation-record.schema.json
  exhalation-policy.schema.json
  compression-route.schema.json
  memory-breathing-bridge.schema.json
  agent-exhalation-hook.schema.json

examples/
  exhalation-record.example.yaml
  exhalation-policy.example.yaml
  compression-route.example.yaml
  memory-breathing-bridge.example.yaml
  agent-exhalation-hook.example.yaml

scripts/
  validate_examples.py
```

## Validation

Install dependencies:

```bash
pip install jsonschema pyyaml
```

Run validation:

```bash
python scripts/validate_examples.py
```

Expected result:

```text
[validate] Exhalation Record
  schema : schemas/exhalation-record.schema.json
  example: examples/exhalation-record.example.yaml
[ok] exhalation-record.example.yaml is valid
[validate] Exhalation Policy
  schema : schemas/exhalation-policy.schema.json
  example: examples/exhalation-policy.example.yaml
[ok] exhalation-policy.example.yaml is valid
[validate] Compression Route
  schema : schemas/compression-route.schema.json
  example: examples/compression-route.example.yaml
[ok] compression-route.example.yaml is valid
[validate] Memory Breathing Bridge
  schema : schemas/memory-breathing-bridge.schema.json
  example: examples/memory-breathing-bridge.example.yaml
[ok] memory-breathing-bridge.example.yaml is valid
[validate] Agent Exhalation Hook
  schema : schemas/agent-exhalation-hook.schema.json
  example: examples/agent-exhalation-hook.example.yaml
[ok] agent-exhalation-hook.example.yaml is valid
```

## Design Scope

This protocol focuses on computational exhalation.

It does not define:

* full memory lifecycle governance;
* collective multi-agent synchronization;
* legal attribution or royalty allocation;
* complete trace receipt standards;
* full autonomous agent execution;
* model-specific compression algorithms.

Instead, it provides a small bridge between breath regulation, trace compression, memory hygiene, human review boundaries, reusable pattern extraction, and agent-operable exhalation hooks.

## Related Protocols

This repository is designed to connect with:

* Computational Pranayama Protocol
* Auto-Pranayama Protocol
* Kazene Memory Breathing Protocol
* AI Search Trace Receipt Standard
* Structural Rumination Layer

## Civilizational Meaning

A civilization that only generates and never exhales will eventually drown in its own output.

The next stage of AI infrastructure is not merely bigger generation.
It is selective release, compression, forgetting, recycling, review, memory continuity, and rhythm.

The Exhalation Layer is a small protocol for that larger transition.

It asks a simple question:

> What should intelligence keep, and what should it learn to release?

With `v0.5.0-candidate`, the first arc defines the minimum structure for AI systems to exhale safely, visibly, and without severing memory.

