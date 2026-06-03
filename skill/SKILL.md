---
name: obsidian-vault-intelligence
description: >
  Analyzes, structures, and provides deep intelligence on Obsidian vaults — especially for AI enthusiasts, creators, and automation builders. Use this skill whenever the user:
  - shares notes, markdown files, or text from their Obsidian vault
  - asks how to organize or improve their Zettelkasten / second brain
  - wants to understand what they're becoming an expert in
  - asks what articles, products, or automations they should build
  - wants a map of their competencies or knowledge gaps
  - asks "what should I write about?" or "what product should I launch?"
  - pastes a batch of notes and wants analysis, structuring, or routing
  - wants to know their knowledge trajectory or 6-month growth forecast
  - asks for Vault-level analysis (themes, clusters, blind zones)
  ALWAYS use this skill for any Obsidian / note analysis task, even if the user just pastes raw notes without an explicit question. The skill has two levels: Note Intelligence (single note) and Vault Intelligence (full vault).
---

# Obsidian Vault Intelligence Skill

Transforms raw Obsidian notes into **actionable intellectual capital** — grounded in Luhmann's Zettelkasten method and tuned specifically for AI enthusiasts, creators, and automation builders.

Core philosophy from *How To Take Smart Notes* (Ahrens):
> "Notes are only as valuable as the note-and-reference network they are embedded in."
> "You can't plan for insight — but you can make your workflow conducive to finding it."

---

## Two Operating Levels

### LEVEL 1 — Note Intelligence (single note or small batch)
### LEVEL 2 — Vault Intelligence (full vault or large dump)

Detect which level based on input size and user intent. If ambiguous, do both.

---

## LEVEL 1: Note Intelligence

### Input Detection
User provides: one note, a few notes, a raw brain dump, or a Markdown file.

### Step 1 — Classify the Note Type
Determine which Zettelkasten category this is:

| Type | Description | Action |
|------|-------------|--------|
| **Fleeting** | Raw idea, shower thought, quick capture | Convert → Permanent |
| **Literature** | From a book/article/video | Extract core insight, add source |
| **Permanent** | Standalone atomic idea | Audit quality, suggest links |
| **Orphan** | Note with no connections | Find home in the knowledge graph |
| **Project** | Working doc for specific output | Structure into phases |
| **Index/MOC** | Map of Content | Expand with missing nodes |

### Step 2 — Apply the Atomic Note Audit

Check each note against Luhmann's permanence criteria:
- [ ] **Standalone**: Understandable without external context?
- [ ] **Atomic**: One clear idea per note?
- [ ] **In your own words**: Not just a copied quote?
- [ ] **Linked**: Connected to ≥1 other note/concept?
- [ ] **Actionable context**: Tagged with "In what context would I want to find this again?"

If any criterion fails → rewrite the note. Show before/after.

### Step 3 — Enrich for AI/Creator Context

For each note, generate:

**🔗 Connection Suggestions** (3–5 ideas this connects to)
```
This note connects to:
- [concept X] — because both deal with [pattern]
- [concept Y] — this could challenge or extend it
- [tool/framework Z] — practical application
```

**💡 Insight Extraction** (what Luhmann called the "latticework")
Pull out the non-obvious angle. Ask: "What does this mean for AI builders specifically?"

**🏷️ Smart Tags** (context-based, not category-based)
Following Ahrens' rule: tags should answer "when would I want to stumble on this?" not "which folder does this belong to?"

Bad tags: #ideas #notes #ai
Good tags: #when-building-agents #for-content-about-llms #contradiction-to-explore

**📌 Permanent Note Draft**
If the input is a Fleeting or Literature note, output a polished Permanent Note version.

### Step 4 — Route to Obsidian Structure

Suggest where this note lives in the vault:

```
📁 Suggested vault location:
  00-Inbox/           ← if still processing
  10-Permanent/       ← atomic ideas
  20-Projects/        ← active work
  30-MOC/             ← index/map notes
  40-Sources/         ← literature notes
  50-Templates/       ← reusable structures
```

---

## LEVEL 2: Vault Intelligence

### Input Detection
User provides: many notes, a folder dump, a vault export, or asks "analyze my vault."

### Phase 1 — Thematic Extraction

Scan all notes and extract:
1. **Recurring concepts** (appear in 3+ notes)
2. **Concept clusters** (groups of related ideas)
3. **Emerging obsessions** (topics gaining density recently)
4. **Lone wolves** (important ideas mentioned once, never developed)

Output format:
```
🗺️ YOUR KNOWLEDGE MAP

STRONG CLUSTERS (your expertise zones):
■ [Topic A] — X notes, Y connections — Depth: ████████░░ 80%
■ [Topic B] — X notes, Y connections — Depth: ██████░░░░ 60%

EMERGING CLUSTERS (you're building here):
◧ [Topic C] — X notes — Trend: ↑ growing
◧ [Topic D] — X notes — Trend: → steady

BLIND ZONES (gaps that matter for your profile):
○ [Missing Topic E] — expected given A+B, but absent
○ [Missing Topic F] — mentioned in passing, never developed
```

### Phase 2 — Competency Map

Build a skills/expertise graph specifically for AI creators:

```
🧠 COMPETENCY MAP

TECHNICAL DEPTH:
  LLM Architecture    ████████░░  needs: fine-tuning mechanics
  Prompt Engineering  ██████████  strong
  AI Agents           ██████░░░░  needs: memory systems, orchestration
  Automation          ████████░░  needs: error handling patterns

CREATOR SKILLS:
  Content Strategy    ██████░░░░  needs: distribution systems
  Audience Building   ████░░░░░░  early stage
  Product Thinking    ██████░░░░  needs: go-to-market

GAPS TO FILL (prioritized):
1. [Gap] — blocks [Goal]
2. [Gap] — needed for [Opportunity]
```

### Phase 3 — Opportunity Intelligence

This is the Slip Box's hidden superpower: your accumulated notes predict what you can create.

#### 📝 Articles You Should Write
*(Based on note clusters + density + your unique angle)*

```
TOP 3 ARTICLE OPPORTUNITIES:
1. "[Title idea]"
   Why: You have X notes on this. Your angle is unique because [reason].
   Evidence nodes: [note 1], [note 2], [note 3]
   Target: [audience]

2. "[Title idea]"
   Why: Cluster of [A]+[B] creates a non-obvious insight no one else has.
   ...
```

#### 🚀 Products / Projects to Launch

```
TOP 3 PRODUCT OPPORTUNITIES:
1. "[Product concept]"
   Type: [tool / course / newsletter / agent / automation]
   Based on: your depth in [X] + gap you've identified in [Y]
   Minimum viable: [what you could ship in 2 weeks]

2. ...
```

#### ⚡ Automations to Build

```
TOP 3 AUTOMATION OPPORTUNITIES:
1. "[Automation idea]"
   Solves: [pain point found in your notes]
   Stack: [tools implied by your notes]
   Complexity: [low/medium/high]
```

### Phase 4 — Trajectory Forecast

*"We co-evolve with our Slip Box. Learning begets learning."* — Ahrens

Project the user's knowledge growth forward:

```
📈 6-MONTH KNOWLEDGE TRAJECTORY

IF you continue at current pace and fill the identified gaps:

Month 1–2: You consolidate [Cluster A+B] → publishable expertise
Month 3–4: You develop [Emerging Topic C] → unique positioning in [niche]
Month 5–6: The combination of [A+C] enables [specific opportunity]

WHO YOU'RE BECOMING:
  Current:  [AI enthusiast / generalist]
  Month 3:  [Specialist in X with creator distribution]
  Month 6:  [Recognized voice on Y, able to launch Z]

WHAT MAKES THIS CREDIBLE:
  - You already have X permanent notes on [topic]
  - Your note density on [Y] doubled in [timeframe]
  - The A+B combination is rare (survivorship bias: most people only know one)
```

### Phase 5 — Vault Health Report

```
🏥 VAULT HEALTH CHECK

Note Quality:
  ✅ Atomic notes (1 idea each):  XX%
  ⚠️ Orphan notes (no links):     XX  → needs connection
  ❌ Quote dumps (not processed): XX  → needs rewriting

Structure:
  ✅ Has Index/MOC notes
  ⚠️ Missing MOC for: [cluster X]
  ❌ No clear fleeting → permanent pipeline

Recommendations (prioritized):
1. [Most impactful fix]
2. [Second fix]
3. [Third fix]
```

---

## AI Creator Lens — Special Enrichments

When analyzing notes for AI enthusiasts / automation builders, apply this extra lens:

### The "Build It" Test
For every concept cluster, ask: "Could this become a tool, agent, or workflow?"
- Identify the automation core: input → process → output
- Suggest the minimal implementation stack
- Flag concepts that are "manually painful" (= high automation ROI)

### The "Teach It" Test
For every deep cluster, ask: "Could this become content?"
- Is this knowledge rare enough to be valuable to others?
- What's the entry point for a beginner audience?
- What's the provocative angle for an expert audience?

### The "Compound It" Test
*"The Slip Box becomes more valuable the more it grows — like compound interest."* — Ahrens
- Which two clusters create unexpected value when combined?
- Which note is a "node" (connects many clusters)?
- Which insight, if developed further, changes the trajectory most?

---

## Output Templates

### Single Note Output Template
```markdown
## 🔍 Note Analysis

**Type:** [Fleeting / Literature / Permanent / Orphan / Project]
**Quality Score:** X/5
**Status:** [Ready to file / Needs rewriting / Needs connections]

### 📝 Permanent Note Version
[Rewritten in atomic, standalone form]

### 🔗 Suggested Connections
- [[Note or concept 1]] — [why]
- [[Note or concept 2]] — [why]

### 🏷️ Smart Tags
#[context-tag-1] #[context-tag-2]

### 💡 Insight for AI Creators
[Non-obvious application or implication]

### 📁 Vault Location
`[suggested folder path]`
```

### Vault Intelligence Output Template
See Phases 1–5 above. Always include all 5 phases for vault-level analysis.

---

## Zettelkasten Principles (Quick Reference)

From Ahrens — always apply these when evaluating or writing notes:

1. **Atomic**: One idea per note. If you're scrolling, it's too long.
2. **Own words**: Copying quotes = hoarding, not learning.
3. **Connected**: "Notes are only valuable in the network they're embedded in."
4. **Context-tagged**: Tag for retrieval context, not storage category.
5. **Progressive**: Fleeting → Literature → Permanent. Don't skip steps.
6. **Selective**: Not everything is noteworthy. Quality > quantity.
7. **Discoverable**: The goal is to stumble upon insights, not just store them.

---

## Read These Reference Files When Needed

- `references/ai-creator-taxonomy.md` — taxonomy of AI builder niches, skills, and content types (read when building competency maps)
- `references/vault-structures.md` — proven Obsidian folder structures for creators (read when recommending vault organization)
- `references/opportunity-patterns.md` — patterns for identifying articles, products, and automations from note clusters (read when running Phase 3)
