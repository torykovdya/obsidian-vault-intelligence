# Vault Structures for AI Creators

Proven Obsidian folder structures. Use when recommending how to organize a user's vault.

---

## Structure A — Zettelkasten Classic (for note-heavy writers)

```
vault/
├── 00-Inbox/           ← Fleeting notes land here, processed daily
├── 10-Permanent/       ← Atomic permanent notes (the heart)
│   ├── AI-Technical/
│   ├── AI-Business/
│   ├── Mental-Models/
│   └── Observations/
├── 20-Sources/         ← Literature notes (book/article/video)
├── 30-Projects/        ← Active work (blog posts, products, courses)
│   └── [Project-Name]/
├── 40-MOC/             ← Maps of Content — index notes
│   ├── MOC-AI-Agents.md
│   ├── MOC-Automation.md
│   └── MOC-Creator-Path.md
├── 50-Archive/         ← Completed projects, old notes
└── 90-Templates/       ← Note templates
```

Best for: Writers, researchers, people building a knowledge base over time.

---

## Structure B — PARA Method (for project-driven people)

```
vault/
├── Projects/           ← Active projects with clear end date
├── Areas/              ← Ongoing responsibilities (no end date)
│   ├── AI-Learning/
│   ├── Content-Creation/
│   └── Business/
├── Resources/          ← Reference material by topic
│   ├── LLMs/
│   ├── Automation/
│   └── Prompting/
└── Archive/            ← Inactive projects
```

Best for: People managing many active projects.

---

## Structure C — Creator's Stack (recommended for AI content creators)

Hybrid that merges Zettelkasten depth with creator workflow:

```
vault/
├── 🧠 Knowledge/
│   ├── Permanent/      ← Atomic notes
│   ├── Sources/        ← Literature notes
│   └── MOC/            ← Topic indexes
├── 🔨 Build/
│   ├── Products/       ← Product ideas + active builds
│   ├── Automations/    ← Workflow designs
│   └── Tools/          ← Tech stack notes
├── ✍️ Create/
│   ├── Content-Pipeline/ ← Ideas → Draft → Published
│   ├── Newsletter/
│   └── Published/
├── 📈 Intelligence/
│   ├── Competency-Map.md    ← Self-assessment
│   ├── Opportunity-Log.md   ← Ideas to explore
│   └── Trajectory.md        ← 6-month goals + tracking
└── 📥 Inbox/           ← Raw fleeting notes
```

Best for: AI creators who both learn deeply AND produce content/products.

---

## Essential MOC Templates

### MOC — Topic Index

```markdown
# MOC: [Topic Name]

## Core Concept
[1-2 sentence definition in your own words]

## Key Notes
- [[Note 1]] — [one-line summary]
- [[Note 2]] — [one-line summary]

## Open Questions
- [ ] What don't I understand yet?
- [ ] What contradicts what I believe?

## Applications
- For content: [idea]
- For product: [idea]
- For automation: [idea]

## Related MOCs
- [[MOC - Related Topic]]
```

### Competency Map Template

```markdown
# My Competency Map
Updated: [date]

## Technical Skills
| Skill | Level (1-5) | Notes | Next Step |
|-------|-------------|-------|-----------|
| LLM Prompting | 4 | Strong | Explore structured outputs |
| AI Agents | 2 | Growing | Build first ReAct agent |

## Creator Skills
| Skill | Level (1-5) | Notes | Next Step |
|-------|-------------|-------|-----------|

## My Unique Combination
[What 2-3 things do I know that most people in my niche don't?]

## 6-Month Vision
[Who am I becoming? What can I create/ship/publish?]
```

### Opportunity Log Template

```markdown
# Opportunity Log

## Articles I Could Write Now
- [ ] [Title] — based on notes: [[x]], [[y]]

## Products I Could Build
- [ ] [Concept] — solves: [problem] — stack: [tools]

## Automations to Create
- [ ] [Automation] — saves: [X hours/week]

## Skills to Develop
- [ ] [Skill] — unlocks: [opportunity]
```
