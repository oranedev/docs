# Venture Operations
*A synthesized concept article — part of the [[Platform Brain Index]]*

---

## The Company: [[Klarifi]]

**Stage:** Pre-seed to seed transition (Q1 2026)
**Category:** Healthcare compliance SaaS + edge AI hardware
**Geography:** Canada-first (Ontario)
**Core mission:** Make regulatory compliance feel like peace of mind, not anxiety

**Revenue model:**
- SaaS: $199/month per medical practice
- Hardware: [[Guardian]] ($2,999), Sterile-Cam ($1,999)
- Enterprise: Hospital system contracts

---

## Products

### [[Guardian]]
Medication adherence monitoring device. Edge AI on-device. No cloud transmission.

**Why it matters technically:**
- Runs NLP inference on low-power ARM hardware locally
- Camera + microphone signal path physically isolated from network stack
- Achieves PHIPA compliance by design — PHI never leaves the device
- Target accuracy: 99.9% for narcotic reconciliation events

**Why it matters commercially:**
- First device combining air-gapped security with cloud-like intelligence
- Replaces manual nursing spot-checks (saves 8+ hours/week per station)
- [[948% ROI Claim]] for the hospital: validated through pilot data framework

**Competitive differentiation:**
- Competitors (Karie, Spencer) stream video to cloud — PHIPA liability
- Guardian is the only zero-trust edge architecture in this category

### Sterile-Cam
Infection control monitoring device. Same edge AI architecture as Guardian.
Entry point: hospital infection control departments.

---

## The Platform UX

### [[Safety Blocks]]
Regulations translated into discrete, actionable compliance tasks. The "Red Brain" language system.

**Philosophy:** Compliance anxiety is the real barrier to adoption. Complex regulatory text → simple, clear blocks removes that anxiety. Higher adoption = more data = better product.

**Why this matters for funding:** The UX framing is what makes SMB self-serve possible. 14-day trial → paid in <14 days with no sales assist.

---

## Stage: [[Pre-Seed to Seed Transition]]

**Current traction signals:**
- [[Guardian Pre-Orders]]: $750 deposits (non-dilutive validation — investors and IRAP both care about this)
- Compliance Brain active users (tracking)
- Provincial Coverage Map (tracking)

**What traction signals prove:**
- Pre-orders → real customers will pay, de-risks hardware manufacturing
- Active users → product-market fit signal, makes accelerator apps stronger
- Hospital pilots (0 → 2 by Q2) → enterprise readiness for seed round story

**The 30-day activation milestone:**
Getting from "zero real contacts" to "IRAP ITA meeting scheduled + 1 hospital innovation lead identified + Velocity app drafted."

---

## [[Edge AI]] — The Technical Moat

Running ML inference on-device rather than in the cloud.

**Why this creates a moat:**
1. **Regulatory moat** — PHIPA/PIPEDA compliance by architecture, not policy
2. **Trust moat** — Clients can physically verify the device isn't transmitting
3. **Cost moat** — No per-inference cloud API costs at scale
4. **Latency moat** — Real-time response (<100ms) without network round-trips

**The unsolved technical problem (what IRAP cares about):**
Standard lightweight models (MobileNet-class) fail to achieve 99.9% accuracy for narcotic reconciliation at the constraint level of Guardian's hardware. The R&D is in the quantization pipeline and privacy-gated architecture.

---

## [[PHIPA Compliance]] — The Pain Point

Ontario's Personal Health Information Protection Act.

**Why it matters commercially:**
- $100K+ fines for violations
- Every Canadian medical practice is exposed
- Cloud-based solutions create liability by design
- Guardian eliminates the exposure at the hardware level

**The Klarifi positioning:**
> "Only platform combining Canadian data residency + Edge AI hardware + regulatory monitoring"

**Transfers to:**
- PIPEDA (federal Canadian privacy law)
- UK NHS / GDPR (Commonwealth expansion path)
- US HIPAA (eventual US market)

---

## Competitive Positioning

```
                    High Healthcare-Specific
                            ↑
    US Healthcare Players   |   [KLARIFI TARGET ZONE]
                            |
Low Canadian Focus ←————————+————————→ High Canadian Focus
                            |
    Generic GRC Tools       |   Canadian Generic
                            ↓
                    Low Healthcare-Specific
```

**Five differentiation talking points:**
1. Only Canadian data residency for healthcare compliance
2. Edge AI hardware (Guardian, Sterile-Cam) — not just software
3. "Safety Blocks" language reduces compliance anxiety → higher adoption
4. Provincial expertise (PHIPA, PIPA) not HIPAA copy-paste
5. Immutable audit trails exceeding regulatory requirements

---

## [[948% ROI Claim]]

**The number that opens hospital doors.**

Framework for validation:
- Nursing hours saved × hourly cost
- Adverse event reduction × average liability cost
- Compliance fine avoidance × annual exposure
- Documentation time saved × admin cost

**Important:** This is a pilot validation framework, not a proven number yet. The 2 hospital pilot target by Q2 2026 is the event that proves or adjusts this figure.

---

## Key People / Network Targets

| Category | Priority Target | Entry Point |
|----------|----------------|-------------|
| Hospital | UHN Innovation Hub | Innovation department |
| Hospital (realistic first) | Sunnybrook Digital Health | Digital health team |
| Academic (Mitacs) | UofT CS — Edge AI focus | Professor research match |
| Academic (Velocity) | McMaster Biomedical Eng | Health Informatics |
| ITA | NRC-IRAP (pending assignment) | Initial inquiry sent |

---

## Connections

- [[Guardian]] is funded via [[IRAP]] + [[SR&ED]] — see [[funding_intelligence]]
- [[Edge AI]] powers [[PHIPA Compliance]] and generates [[L1 Evidence Layer]] — see [[evidence_intelligence_system]]
- [[Guardian Pre-Orders]] validate [[Pre-Seed to Seed Transition]] thesis
- [[Safety Blocks]] UX drives the SMB self-serve funnel
- Hospital partnerships unlock [[ISC Challenges]] eligibility and seed round story
- [[Second Brain Architecture]] in [[brain_protocols]] is what you're using right now to manage all of this

---

*Sources: funding_strategy_map.md, agentic_roadmap.md, knowledge_base/irap_strategy.md*
*Compiled: 2026-04-08*
