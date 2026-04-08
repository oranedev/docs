# Brain Protocols
*A synthesized concept article — part of the [[Platform Brain Index]]*

---

## What This Is

The operating manual for your [[Second Brain Architecture]]. These are the exact prompts and protocols that keep the brain growing, healthy, and useful.

The [[Compounding Loop]] only works if every session ends with answers *filed back into the wiki*. This document ensures that.

---

## [[Second Brain Architecture]]

```
External Memory (You Don't Remember)
├── /wiki/index.md          ← The entry point — paste this first every session
├── /wiki/*.md              ← Compiled concept articles
├── /raw/*.md               ← Unprocessed source material
└── /daily_funding_tracker  ← L1 operational data

         ↓ feeds

The Processor (Rotation + Protocols)
├── 10-Day Rotation Schedule
├── Recovery Playbooks
└── Risk Matrix

         ↓ executes

Daily Agent (15-Minute Loop)
├── Phase 1: Scan (min 1-3)
├── Phase 2: Execute (min 4-7)
├── Phase 3: Save (min 8-12)
└── Phase 4: Send (min 13-15)

         ↓ writes back to

External Memory  ← THE COMPOUNDING LOOP
```

---

## Protocol 1: Starting a New AI Session

**Every session with AI starts exactly this way. No exceptions.**

```
Paste this at the start of every session:

"Here is my wiki index — this is my external brain context.
[PASTE wiki/index.md]

Today's focus is: [TOPIC or TASK]
Relevant concept article: [PASTE relevant wiki/*.md if needed]

[Then ask your actual question or give your task]"
```

**Why this works:** The AI reads the index and knows everything you've built without you re-explaining. You pick up exactly where you left off, every time.

---

## [[Synthesis Protocol]] — Adding New Sources

When you have new raw material (article, transcript, conversation, document):

**Step 1:** Save the raw material to `/raw/` with a descriptive name
```
raw/karpathy-llm-knowledge-base-2026.md
raw/mto-audit-requirements-2026.md
raw/irap-ita-meeting-notes-2026-04-08.md
```

**Step 2:** Run this prompt:
```
I'm adding a new source to my knowledge base.

Here is my current wiki index (so you know what already exists):
[PASTE wiki/index.md]

Here is the new source:
[PASTE the raw material]

Please:
1. Write a 200-word summary of this source
2. List the main concepts (as a bullet list)
3. Note connections to existing concepts — mark with [[wikilinks]]
4. Flag anything that contradicts existing wiki content with ⚠️
5. Add any new concepts to the index (give me the updated rows)
```

**Step 3:** 
- Save the summary as `wiki/summary-[source-name].md`
- Update `wiki/index.md` with any new concept rows
- Update the Brain Health Snapshot table in the index

---

## Protocol 2: Asking Questions Against the Brain

Once you have 5+ compiled articles:

```
Here is my knowledge base index:
[PASTE wiki/index.md]

My question: [YOUR QUESTION]

Please research the answer using the concepts in my wiki.
If you need specific articles, tell me which ones and I'll paste them.
Cite your sources using [[wikilinks]].
After answering, give me the answer formatted as markdown
so I can save it as a wiki article.
```

**Critical habit:** Always save the answer back as `wiki/[topic-name].md`. This is the [[Compounding Loop]].

---

## [[Health Check Protocol]] — Weekly (Every Tuesday)

```
Here is my knowledge base index:
[PASTE wiki/index.md]

Please perform a health check:
1. Which concepts are mentioned but don't have their own article yet?
   (These are gaps I should fill next)
2. Which items are likely outdated?
   (Flag anything with dates >3 months old that may have changed)
3. Are there any contradictions between concepts?
4. What are 3 high-value questions I could research next?
5. Which concepts have no [[wikilinks]] connecting them to others?
   (These are orphans — they need connecting)
```

**File the health check output as:** `wiki/health-check-[date].md`

---

## [[Daily Agent Protocol]] — The 15-Minute Execution Loop

**Trigger:** 8:00 AM daily
**Structure:** 4 phases, 15 minutes total, non-negotiable

### Phase 1: Scan (Minutes 1-3)
- Open Innovation Canada Portal
- Open `daily_funding_tracker.md`
- Flag deadlines <90 days as 🔴 Urgent
- Log any overnight email replies → update status

### Phase 2: Execute (Minutes 4-7)
- Look up today's [[10-Day Rotation Protocol]] day
- Execute ONLY the assigned micro-task for that source
- **Single-threaded focus. Do not think about other funding sources.**

### Phase 3: Save (Minutes 8-12)
- Update tracker row with action taken
- Update status: `📋 To Do` → `🔄 In Progress` → `⏳ Waiting` → `✅ Done`
- Add new contacts to `master_contacts.md`

### Phase 4: Send (Minutes 13-15)
- Draft one email using templates
- Click send
- Session over

---

## [[Recovery Playbooks]]

Pre-scripted responses to the common exceptions that derail the protocol.

### IF you miss a day:
```
Do NOT double up.
Resume the rotation exactly where you left off.
The cycle extends, it never skips.
```

### IF you feel stuck:
```
Execute a low-friction action only:
✅ Read one guideline section
✅ Update one contact row
✅ Send one short email
❌ Do not attempt a deep dive
❌ Do not try to catch up
```

### IF a rejection arrives:
```
1. Take 30 seconds
2. Open risk matrix
3. Update rejected source status
4. Identify next Tier 1 source
5. Shift energy allocation
DO NOT: ruminate, send angry reply, abandon the cycle
```

### IF a deadline is <7 days:
```
Override normal rotation.
Enter Deadline Sprint Mode:
  Day -7 to -5: Draft completion
  Day -4 to -3: Review + polish
  Day -2: Final checks
  Day -1: Submit
  Day 0: Celebrate or contingency
Return to normal rotation after submission.
```

### IF a hot lead emerges:
```
Mark as ⭐ in tracker.
Add to Buffer Day priority.
Do NOT disrupt today's rotation.
Exception: if lead requires <24hr response, handle in Phase 4 send slot.
```

---

## Status Codes (Universal Across All Trackers)

| Code | Meaning |
|------|---------|
| 📋 | To Do |
| 🔄 | In Progress |
| ⏳ | Waiting on Reply |
| ✅ | Complete |
| 🚫 | Blocked / Rejected |
| ⭐ | Hot Lead |
| 🔴 | Urgent (deadline <90 days) |

---

## The [[Compounding Loop]]

This is the mechanism that makes the brain get smarter over time:

```
Raw source added
    → Synthesized into wiki
    → Question asked against wiki
    → Answer generated
    → Answer filed back as new wiki article
    → Next question benefits from all previous answers
    → Cycle continues
```

**The failure mode:** Asking questions but not filing answers. The brain doesn't grow. You're back to amnesia.

**The success metric:** After 30 days, you should be able to ask a question you couldn't have answered when you started, and get a cited answer in seconds.

---

## Brain File Structure

```
axial-space/
├── wiki/
│   ├── index.md                      ← START HERE every session
│   ├── evidence_intelligence_system.md
│   ├── funding_intelligence.md
│   ├── venture_ops.md
│   ├── brand_positioning.md
│   └── brain_protocols.md            ← this file
├── raw/
│   └── [unprocessed sources go here]
├── daily_funding_tracker.md           ← L1 operational data
├── master_contacts.md                 ← L1 contact data
├── agentic_roadmap.md                 ← L1 strategy doc
├── funding_strategy_map.md            ← L1 strategy doc
└── drafts/                           ← outbox
```

---

## Connections

- [[Second Brain Architecture]] mirrors [[L2 Compiled Intelligence]] at personal scale
- [[Daily Agent Protocol]] implements the [[10-Day Rotation Protocol]]
- [[Recovery Playbooks]] are the error handlers for [[Daily Agent Protocol]]
- [[Compounding Loop]] is what makes this an [[Evidence Intelligence System]] for knowledge, not just information
- [[LLM Knowledge Base]] (the Karpathy system) is the broader category this implements

---

*Sources: daily_agent_protocol.md, agentic_roadmap.md + Karpathy knowledge base methodology*
*Compiled: 2026-04-08*
