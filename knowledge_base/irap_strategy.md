# IRAP Strategy & Execution Guide
## For Klarifi (Edge AI Healthcare Compliance)

**Status:** Active Strategy  
**Focus:** NRC-IRAP Research & Development Project (ARP)  
**Target:** $50K - $150K Non-repayable contribution (Phase 1)

---

## 1. The "Hook" for IRAP
IRAP does not fund "product development" (building the app). They fund **technological uncertainty** (solving hard technical problems).

**Klarifi's Weak Pitch (Rejection Risk):**
> "We are building a compliance dashboard and a medication reminder device."
> *Why it fails:* Standard software dev + off-the-shelf hardware integration. Low technical risk.

**Klarifi's Winning Pitch (Fundable R&D):**
> "We are developing novel **Edge AI optimization techniques** to run complex privacy-preserving NLP models on low-power IoT hardware (Guardian) without cloud transmission, ensuring 100% PHIPA compliance."
> *Why it works:* It's hard. It might fail. It requires experimentation.

---

## 2. Eligibility & Readiness Checklist

### Basic Gatekeepers
- [x] Incorporated non-profit (Klarifi Inc.)
- [x] < 500 employees
- [x] Objective to grow through innovation
- [ ] **Financial Capability:** Can you cover the other 20-50% of costs?
  - *Strategy:* Show Guardian pre-orders ($750 deposits) + SR&ED eligibility as proof of solvency.

### Technical Uncertainty Criteria (Must have 2/3)
1. **Technological Uncertainty:** "We don't know if the standard SLM (Small Language Model) can run on this specific ARM chip with < 100ms latency."
2. **Technical Content:** "We aren't just calling APIs; we are quantizing models and writing custom firmware."
3. **Hypothesis validation:** "We are testing if local-only inference provides sufficient accuracy vs. cloud models."

---

## 3. Engagement Strategy (The ITA)

**Goal:** Get an Industrial Technology Advisor (ITA) assigned and excited. ITAs are the gatekeepers. If they like you, they write the proposal *with* you.

### "Day 1" Outreach Script (Use This Today)
**To:** [General IRAP Inbox or Specific ITA from Network]
**Subject:** R&D Eligibility Inquiry - Edge AI for Healthcare Privacy

> Hello,
>
> I am the founder of **Klarifi**, a Canadian health-tech company developing privacy-first hardware.
>
> We are solving a critical technical challenge: **Deploying real-time NLP models on low-power edge devices (Guardian) to eliminate cloud data transmission risks (PHIPA/PIPEDA).**
>
> We have successfully secured initial pre-orders and are now encountering technical uncertainties regarding model quantization and on-device resource management that require R&D.
>
> Could we allow 15 minutes to discuss if this technical roadmap aligns with IRAP's current mandates for AI or Health/Bio-manufacturing?
>
> Best,
> [Founder Name]
> [Link to Klarifi Website]

---

## 4. R&D Project Narrative (Draft Material)

When the ITA asks "What is the project?", use these 3 technically dense paragraphs.

### The Technical Problem
Current medication adherence systems rely on cloud processing, which creates unacceptable privacy risks (data residency/breaches) for Canadian medical data. However, running high-accuracy adherence models (vision + audio) on edge devices is constrained by limited compute (NPU ops) and thermal envelopes. **Standard lightweight models (e.g., MobileNet) fail to achieve the required 99.9% accuracy for narcotic reconciliation.**

### The Technical Objectives
1.  **Develop a custom quantization pipeline** to compress our proprietary adherence model by 40% without exceeding a 2% accuracy loss.
2.  **Engineer a "privacy-gated" hardware architecture** where the microphone/camera signal path is physically isolated from the network stack, reachable only by the local inference engine.
3.  **Validate a novel "federated learning" approach** for updating device models using only scrubbed, aggregated gradients, ensuring zero PII reconstruction risk.

### The Innovation
Unlike competitors (e.g., Karie, Spencer) who simply stream video to the cloud, Klarifi is creating a **Zero-Trust Edge Architecture**. If successful, this creates a new standard for medical IoT where "air-gapped" security is compatible with "cloud-like" intelligence.

---

## 5. Budget Strategy (The Ask)

**Phase 1 Target: Accelerated Review Process (ARP)**
- **Cap:** Usually $50K (sometimes up to $75K)
- **Speed:** Fast approval (< 4 weeks)
- **Focus:** Feasibility study, hiring a contractor/consultant, or internal salary support for 6 months.

**Line Item Suggestions:**
1.  **Salaries (Internal):** 65-80% of technical founder/CTO salary while working on *this specific R&D*.
2.  **Contractors:** Hiring a specialized firm for "Embedded NPU Optimization".
3.  **Materials:** Purchase of dev boards (NVIDIA Jetson / specialized ARM MCUs) for testing. (Note: IRAP hates funding "capital assets", frame it as "consumables for prototyping").

---

## 6. Next Steps (Execution)
1.  **Send the Inquiry Email** (See Section 3).
2.  **Register on the NRC Portal** (If not done).
3.  **Prepare a 5-Part Slide Deck** (Problem, Solution, *Technical Challenges*, Team, Market).
    - *Note: The "Technical Challenges" slide is the most important one for IRAP.*

---
*Stored in Knowledge Base for Day 1 Protocols.*
