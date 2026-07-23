# Artist Operating System — AI Skills for Artists

A practical, reusable collection of AI skills for artists, curators, and cultural practitioners.

The universal skills cover the complete professional cycle: finding opportunities, organizing verified career information, researching context, developing projects and exhibitions, planning production, building portfolios, and writing professional communications.

These are not prompt collections. Each skill defines a repeatable workflow, evidence standards, decision criteria, and a concrete output format. The skills are universal: they do not contain Valeria Titova’s biography, projects, preferences, or private materials.

## Universal skills

### 1. Open Call Finder & Matcher

Finds current open calls, verifies official requirements, checks eligibility, and ranks opportunities against an artist’s practice and constraints.

**Input:** artist profile, geography, media, goals, budget, travel and access constraints.  
**Output:** verified ranked shortlist, fit scores, risks, deadlines, and apply/consider/skip recommendation.  
**Try:** “Find current residencies for a digital artist working with memory and the body. Rank only funded opportunities open to applicants from my country.”

- [Skill files](skills/find-match-open-calls/)
- [Use in ChatGPT](https://chatgpt.com/skills?skill_id=6a62131cae8c8191b52df45272e8145a)

### 2. Artist Knowledge Base Builder

Builds a verified source of truth from CVs, portfolios, biographies, project texts, websites, and notes.

**Input:** existing artist materials in any stage of consistency.  
**Output:** canonical records, source map, bios of different lengths, project summaries, conflicts, gaps, and update log.  
**Try:** “Build a reusable knowledge base from my CV and portfolio. Do not infer missing dates or merge similarly named projects.”

- [Skill files](skills/build-artist-knowledge-base/)
- [Use in ChatGPT](https://chatgpt.com/skills?skill_id=6a62132e711481918078a604f3024f81)

### 3. Portfolio Architect

Designs a portfolio for a specific gallery, residency, grant, institution, festival, curator, or client.

**Input:** destination brief plus available works and documentation.  
**Output:** portfolio argument, work selection, page-by-page structure, image and text gaps, and final QA checklist.  
**Try:** “Rebuild this portfolio for a residency jury. Keep it under 15 pages and explain every inclusion and omission.”

- [Skill files](skills/architect-artist-portfolio/)
- [Use in ChatGPT](https://chatgpt.com/skills?skill_id=6a6213416c3081918d403a15d95f5c47)

### 4. Context Research for Artists

Researches a place, community, institution, site, and local history for a residency, commission, exhibition, or proposal.

**Input:** place or institution, artistic purpose, time period, and desired research depth.  
**Output:** context map, annotated timeline, stakeholders, ethical risks, fieldwork questions, sources, and grounded project directions.  
**Try:** “Research this residency location through local history, ecology, communities, archives, and contested memory. Separate verified facts from proposals.”

- [Skill files](skills/research-art-context/)
- [Use in ChatGPT](https://chatgpt.com/skills?skill_id=6a62135b3d1481918de4d72ba248122c)

### 5. Exhibition Concept Developer

Turns a theme, research question, archive, or body of work into a coherent exhibition proposal.

**Input:** core question, works, venue, audience, scale, and constraints.  
**Output:** premise, curatorial synopsis, work matrix, spatial dramaturgy, visitor journey, accessibility strategy, and production implications.  
**Try:** “Develop this body of work into an exhibition with a clear argument and zone-by-zone visitor journey.”

- [Skill files](skills/develop-exhibition-concept/)
- [Use in ChatGPT](https://chatgpt.com/skills?skill_id=6a621368122c8191908a2349b69bac3a)

### 6. AI Art Production Planner

Converts an AI-art concept into a feasible production system from first test to installation and delivery.

**Input:** concept, format, quality bar, schedule, budget, team, and venue conditions.  
**Output:** production brief, pipeline, work breakdown, schedule, budget, responsibility matrix, technical specification, and risk register.  
**Try:** “Turn this six-screen AI installation into a production plan with milestones, budget categories, technical rehearsal, backups, and rights risks.”

- [Skill files](skills/plan-ai-art-production/)
- [Use in ChatGPT](https://chatgpt.com/skills?skill_id=6a621376968c81919ec7f0ccfee9da27)

### 7. Artist Communication Editor

Drafts and edits professional communication for curators, galleries, institutions, collaborators, and clients.

**Input:** sender, recipient, relationship, context, objective, channel, facts, and desired next action.  
**Output:** ready-to-send draft, subject options, shorter alternative, and attachment/fact checklist.  
**Try:** “Write a concise first email to this curator. Use only verified facts from my portfolio and propose one low-friction next step.”

- [Skill files](skills/edit-artist-communications/)
- [Use in ChatGPT](https://chatgpt.com/skills?skill_id=6a62138216c08191bc1aea427075a6a4)

## How the skills connect

1. Find and assess an opportunity.
2. Build or update the artist knowledge base.
3. Research the place and institution.
4. Develop the project or exhibition concept.
5. Plan production, schedule, budget, and risks.
6. Architect a tailored portfolio.
7. Draft the submission email and follow-up.

Each skill also works independently.

## Author-specific skills

These are intentionally separate from the universal toolkit.

- [Psycheia Visual Language](skills/psycheia-visual-language/) — a project-specific visual direction system for *Psyche / Psyche 3.0*.
- [Curatorial Application Editor](skills/curatorial-application-editor/) — a detailed application-writing workflow developed from Valeria Titova’s curatorial practice.

## Installation and use

Each folder is self-contained:

```text
skills/<skill-name>/
├── SKILL.md
└── agents/
    └── openai.yaml
```

Open the ChatGPT link above to use an installed version, or download a skill folder and add it to the skills directory of a compatible ChatGPT/Codex workspace. A matching request can trigger the skill automatically; you can also name the skill explicitly.

## Design principles

- Universal rather than biography-specific
- Primary-source verification
- Facts separated from inference
- No invented dates, credits, prices, permissions, or testimony
- Explicit uncertainty and missing-information checks
- Concrete, reusable outputs
- Accessibility, ethics, rights, and feasibility built into the workflow

## Languages

The skills can work in the language requested by the user. Their operational instructions are written in English for portability across international workflows.

## Version

Universal collection: **v1.0 — July 2026**

## Author

**Valeria Titova** — AI artist, creative director, researcher, lecturer, and founder of AIlera.

- [LinkedIn](https://www.linkedin.com/in/valerie-titova/)
- [Telegram](https://t.me/leraneuralpics)
- [Instagram](https://www.instagram.com/lerarussia/)
- [GitHub](https://github.com/lerarussia)

All texts and workflows are authored by Valeria Titova. No reuse licence is granted unless explicitly stated.
