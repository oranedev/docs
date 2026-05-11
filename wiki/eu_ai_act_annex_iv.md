# EU AI Act Annex IV
*A synthesized concept article — part of the [[Platform Brain Index]]*

---

## What It Is

Under the EU AI Act (Regulation (EU) 2024/1689), **Annex IV** defines the mandatory technical documentation that providers of high-risk AI systems must produce before placing their systems on the market (Article 11).

This documentation acts as the primary evidence of conformity during a market surveillance audit. It proves that the compliance work was not just performed, but was performed against the correct regulatory threshold.

---

## The Compliance Gap

As noted in the [[Conversational AI Compliance]] thesis, the gap for enterprise AI deployments is not technological; it is documentation-based. Directors often measure operational KPIs (intent accuracy, containment rate, CSAT). However, auditors measure against Annex IV.

If an AI system is deployed without Annex IV documentation, it is legally barred from the EU market and exposes the deploying organization to fines of up to **€30M or 6% of global annual turnover**.

---

## The 6 Core Pillars of Annex IV Documentation

### 1. System Identification & Architecture
- **What it covers:** Intended purpose, version history, software/firmware versions, and deployment architecture (APIs, embedded hardware).
- **The catch:** You must document exactly how the AI system interacts with other hardware or software, including legacy systems.

### 2. Development Process & Data Governance
- **What it covers:** The underlying design specifications and development methodology.
- **Third-party components:** You must specify how pre-trained models (e.g., OpenAI, Anthropic APIs) or external tools were integrated or modified.
- **Data Governance (Article 10):** Datasheets detailing training methodologies, data provenance, labelling procedures, and data cleaning. 

### 3. Monitoring, Functioning, and Control
- **What it covers:** Performance capabilities and limitations (accuracy for specific demographic groups, expected overall accuracy).
- **Risk Analysis:** Foreseeable unintended outcomes and risks to health, safety, and fundamental rights.
- **Human Oversight (Article 14):** Proof of technical measures that allow human operators to effectively oversee the system and interpret its outputs.

### 4. Risk Management System (Article 9)
- **What it covers:** Detailed documentation of the risk management system. This includes the identification, mitigation, and residual assessment of risks throughout the system's entire lifecycle. 
- **Connection:** This is the specific failure point for the [[Conversational AI Compliance]] gap.

### 5. Lifecycle Changes & Post-Market Monitoring
- **What it covers:** A description of any changes made to the system's performance after deployment.
- **Post-Market Plan (Article 72):** A detailed plan to evaluate the system continuously in the real world.

### 6. Compliance Declarations
- **What it covers:** A signed EU Declaration of Conformity (Article 47) and a list of all applied harmonised standards or common specifications.

---

## The Audit Reality

Annex IV documentation must be retained for **10 years**. The [[L1 Evidence Layer]] of a compliance architecture must be designed from day one to generate this documentation automatically. If you build the AI system first and try to retrofit Annex IV documentation later, you will fall into the Audit Trap.

---

## Connections

- Defines the exact regulatory standard missing in the [[Conversational AI Compliance]] thesis.
- Demands the creation of an [[L1 Evidence Layer]] to capture immutable lifecycle changes and risk mitigation steps.
- Failure to comply triggers the same structural liability as the IPC ALPR Audit Trap.

---

*Source: EU AI Act Regulation Text / Annex IV Requirements*
*Compiled: 2026-05-11*
