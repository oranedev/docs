# Evidence Intelligence System
*A synthesized concept article — part of the [[Platform Brain Index]]*

---

## What It Is

An [[Evidence Intelligence System]] is a **layered data platform where field-recorded evidence is the core product** and an LLM acts as the compilation engine on top. The LLM is not the moat. The evidence is.

This is the architectural frame for the traffic data business and the model for every domain it scales into.

> The LLM is to evidence what SQL is to a financial database. The SQL isn't the product. The evidence is.

---

## The Three Layers

### [[L1 Evidence Layer]] — The Base
- **What:** Raw field events — immutable, timestamped, GPS-attributed records of what happened on the ground
- **Who manages it:** Data collection infrastructure (roadside ATR units, .ECO files, field technicians)
- **Key properties:** Append-only, scrubbed, legally defensible, auditable
- **Critical rule:** The LLM **never touches L1**. L1 is the ground truth.
- **Analogy:** Bitcoin's blockchain. Once written, it doesn't move.

### [[L2 Compiled Intelligence]] — The Brain
- **What:** The wiki/knowledge base compiled from L1 data — station histories, compliance states, anomaly flags, pattern analysis
- **Who manages it:** LLM as compiler and maintainer
- **Key properties:** Synthesized, queryable, self-healing (health checks), growing over time
- **This is where the [[Domain Schema Moat]] lives** — the encoded regulatory knowledge that shapes how L1 data gets interpreted
- **Analogy:** A financial analyst's model built on top of Bloomberg data

### [[L3 Queryable API]] — The Interface
- **What:** The client-facing layer — dashboards, URL endpoints, report outputs
- **Who sees it:** Clients. They never see an LLM. They see answers grounded in evidence.
- **Key properties:** Real-time heartbeat view of the business, cited and traceable to L1
- **Analogy:** A Bloomberg Terminal — the interface to the underlying data engine

---

## The Domain Schema Moat

This is the actual competitive advantage. Not the LLM. The **proprietary instruction layer** that tells the LLM how to interpret L1 evidence.

For the traffic business, the domain schema encodes:
- Ontario traffic compliance rules
- MTO audit requirements
- RAQS qualification procedures
- Station maintenance history interpretation
- Regulatory tolerance bands for anomaly detection

**A generic LLM doesn't have this.** Every client who uses the system inherits years of encoded regulatory expertise, compiled automatically.

This is why this isn't the "L2 ghost town" problem from blockchain. The L2 adds *disproportionate value* because the domain schema is proprietary — not just a cheaper version of the same thing.

---

## The Platform Scaling Pattern

The [[Platform Scaling Pattern]] is the thesis behind going from one domain to multiple:

```
Traffic Surveys (Ontario MTO compliance)
    ↓ Same operating principles
LTC Compliance (Long-Term Care regulatory layer)
    ↓ Swap domain nouns, same L1/L2/L3 stack
Solana Infra Settlement Rails (on-chain evidence + compiled state)
```

**What stays the same:** Evidence layer structure, compilation engine, health-check loop, API interface pattern

**What changes:** Domain schema (the encoded regulatory/contextual knowledge for each vertical)

This makes the platform a **template**, not a one-off. Each new client category gets:
1. A new domain schema loaded into L2
2. Their L1 data plugged in
3. L3 surfaced as their branded interface

---

## Why This Isn't "Just Using AI"

Common mistake: building a wrapper around an LLM API and calling it a platform.

The distinction that matters:

| Just Using AI | Evidence Intelligence System |
|---|---|
| LLM is the product | Evidence is the product |
| No proprietary training data | L1 is your proprietary corpus |
| Anyone can replicate with the same model | Domain schema takes years to build |
| Trust degrades over time | Trust compounds as evidence accumulates |
| No audit trail | L1 is the audit trail |

---

## Connections

- [[L1 Evidence Layer]] feeds [[L2 Compiled Intelligence]] via the [[Domain Schema Moat]]
- [[IRAP]] can fund the R&D required to build the [[L2 Compiled Intelligence]] compilation engine
- [[Edge AI]] runs locally on devices to generate [[L1 Evidence Layer]] data without cloud transmission
- [[Platform Scaling Pattern]] is the commercialization thesis built on this architecture
- [[Second Brain Architecture]] is the personal-scale version of this same pattern

---

*Source: User-defined architecture from conversation — April 2026*
*Connections: [[funding_intelligence]] | [[venture_ops]] | [[brain_protocols]]*
