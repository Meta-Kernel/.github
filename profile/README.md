# MetaKernel

**Constitutional infrastructure for governed digital, agentic, and physical systems.**

MetaKernel is a provider-neutral metakernel and system foundry for building portable, policy-governed products from canonical contracts. It treats identity, authority, schema, policy, bindings, evidence, execution, retrieval, and runtime behavior as explicit machine-readable infrastructure rather than application conventions.

## Core position

MetaKernel is built around a simple rule:

> No effect without canonical resolution, authority, policy, admissibility, durable intent, and evidence.

The kernel is designed to support hosted, on-premises, edge, sovereign, and air-gapped deployments while keeping domain products and external providers replaceable.

## Architecture

The architecture is **Constitution-First, Object-First, Contract-First, Registry-First, Policy-First, Evidence-First, Deterministic-First, Zero-Trust, Sandbox-First, and Agentic-First**.

First-class planes include:

- Control, Semantic, Data, Governance, Execution, Exchange, Runtime, Commercial, and Communication
- Knowledge & Retrieval
- Assurance
- Perception & Learning
- Observability
- Developer / Code Intelligence

Canonical resources include namespaces, objects, schemas, contracts, manifests, capabilities, authorities, policies, bindings, obligations, effects, evidence, workflows, runtimes, agents, tools, connectors, providers, knowledge sources, retrieval runs, context packs, evaluations, findings, checkpoints, and replay policies.

## T=0

MetaKernel uses a canonical admission boundary for material actions:

```text
resource
  -> contract
  -> constitution / invariants
  -> authority grants
  -> policy
  -> boundary
  -> binding requirements / instances
  -> obligation discharges
  -> idempotency / replay
  -> ADMIT | DENY
  -> committed effect intent
  -> effect
  -> evidence / lineage
```

Caller assertions, model outputs, retrieval results, risk classifiers, agent frameworks, and external services are never authoritative by themselves.

## Native knowledge and retrieval

MetaKernel treats retrieval as kernel infrastructure, not as a hard-coded vector database.

```text
Source
  -> SourceVersion
  -> governed ingestion
  -> canonical Document / Fragment
  -> lexical | vector | graph | symbol retrieval
  -> RetrievalRun
  -> EvidencePack
  -> ContextPack
  -> optional model / JEv-style advisory signal
  -> deterministic T=0
```

Indexes and embeddings are derived, versioned, rebuildable projections. Context must preserve provenance and evidence-grade citations must resolve to a versioned source.

## Assurance and durable execution

Evaluation, red-team testing, findings, approvals, controls, checkpoints, replay policy, and execution outcomes are first-class. External evaluation, security, agent, browser, document, retrieval, telemetry, and sandbox systems bind through canonical provider contracts.

No external side effect should cross the effect boundary before a durable `ExecutionIntent` has been committed.

## Provider-neutral by design

MetaKernel can integrate external runtimes and engines without surrendering canonical state or authority. Provider registration is not conformance:

```text
DECLARED -> WIRED -> LOCAL_CONFORMANT -> CLOUD_CONFORMANT
```

Each transition requires evidence.

## Product model

MetaKernel is intended to sit beneath domain kernels and products:

```text
MetaKernel
    |
    +-- Workspace Runtime Infrastructure
    |
    +-- Domain Kernels
          |
          +-- Finance
          +-- Healthcare
          +-- Regulation
          +-- Commerce
          +-- Property
          +-- Logistics
          +-- Identity
          +-- other governed domains
```

## Principles

**Preserve before normalize. Resolve before infer. Canonicalize before enrich. Commit intent before effect. Evidence every material outcome.**

---

This organization contains the evolving MetaKernel architecture, reference implementations, conformance assets, tooling, and domain-kernel work.
