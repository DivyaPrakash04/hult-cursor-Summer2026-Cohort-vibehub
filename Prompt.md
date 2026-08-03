Divya, here is **the final, clean, step‑wise, end‑to‑end IDE prompt** you should paste directly into Cursor or Windsurf.  
This version incorporates **everything**: your chosen name (**VibeHub**), the full Week 3 requirements, your Phase‑1 scaffolding files, your builder identity line, and the phased execution model that prevents truncation.

Requirement for the context:
Week 3 · Vibe marketing

Vibe marketing platform
Build a vibe marketing platform that presents the cohort — and each participant's work — with energy that attracts attention and partners.
Week 3 contest: a public-facing vibe marketing platform for the cohort. This is not a dry portfolio dump — it should make the work feel alive, credible, and worth following. Include participant profiles, project evidence, deployment links, and partner-facing narrative. The winning submission becomes the cohort's public marketing surface for the rest of the pilot.


This is the **exact prompt** you will use to start building in your IDE.

---

# 🚀 **FINAL WEEK 3 IDE PROMPT — VibeHub (Copy/Paste This Entire Block)**

Act as a world-class Full-Stack Engineer and UX Designer specializing in high-energy, modern tech aesthetics (Vercel, Linear, shadcn-style) with punchy typography and dynamic motion.

We are building **VibeHub — the Hult Cursor Cohort 3 Vibe Marketing Platform.**

This is a **public-facing**, **high-credibility**, and **high-energy** platform showcasing our cohort’s engineering progress.  
It must **not** feel like a dry portfolio directory.  
It should feel like a **living, breathing tech ecosystem**—a launchpad and high-signal marketing surface for partners, founders, and recruiters.

---

# 1. **Core Architecture Requirements**

Use:

- **Next.js (App Router)**
- **TypeScript**
- **Tailwind CSS**
- **shadcn/ui**
- **framer-motion**

Place the project under:

```
submissions/divyaprakash04-project-3/
```

Create these routes:

### `/` — Home / Hub Page
- High-vibe dashboard with cohort stats (mocked but credible)
- Strong partner-facing narrative
- Motion-enhanced hero section

### `/participants`
- Dynamic roster of cohort members
- Each card shows:
  - Name
  - GitHub handle
  - Tech stack
  - Builder identity tagline
  - GitHub/LinkedIn links

### `/participants/[handle]`
- Deep profile
- Highlighted projects
- Deployment links
- Narrative: “What they ship, why it matters”

### `/projects`
- Grid of active projects
- Each card includes:
  - Title
  - Owner handle
  - Week number
  - Tech stack
  - Summary
  - “Live Deployment” CTA
  - “Source Code” CTA

### Project Detail View
- Evidence sections (screenshots/code snippet placeholders)
- Technical changelog (mocked)
- “Why this matters” partner-facing section

### Optional `/partners`
- Dedicated partner narrative
- Collaboration paths
- CTA (Calendly/Typeform/email)

---

# 2. **Design System & Visual Vibe**

- **Dark mode first**
- Electric accent colors:
  - emerald green  
  - cyber blue  
  - hazard orange  
- **framer-motion** for:
  - Page transitions
  - Staggered list animations
  - Hover micro-interactions
- Typography:
  - Inter / Space Grotesk for headers
  - JetBrains Mono for technical data
- `<title>`:
  - `"VibeHub — Hult Cursor Cohort 3"`

---

# 3. **Data Modeling & Seed Data**

Create `src/data/cohort.ts` with:

### Participant fields:
- `handle`
- `name`
- `tagline`
- `techStack`
- `focus`
- `githubUrl`
- `linkedinUrl?`
- `latentUrl?`
- `projects: string[]`

Include **3 premium participants**, including:

**@DivyaPrakash04**  
`"Shipping full-stack AI orchestration engines that turn raw compute into elite, partner-ready product surfaces."`

### Project fields:
- `id`
- `title`
- `ownerHandle`
- `week`
- `deployUrl`
- `sourceUrl`
- `techStack`
- `summary`
- `whyItMatters`
- `changelog: { date, description }[]`

Include **2 cutting-edge AI/full-stack projects** with credible fake deploy URLs and realistic changelogs.

---

# 4. **Official Week 3 Narrative Requirement**

Satisfy:

> “Build a vibe marketing platform that presents the cohort — and each participant's work — with energy that attracts attention and partners. This is not a dry portfolio dump — it should make the work feel alive, credible, and worth following. Include participant profiles, project evidence, deployment links, and partner-facing narrative.”

---

# 5. **PR Body Structure for `[Project 3] Submission — divyaprakash04`**

Generate this PR body:

```md
## Production URL
<Week 3 deployed URL>

## Vibe marketing summary
<Explain how VibeHub presents the cohort with energy, credibility, and partner-facing narrative. Emphasize that it is a living marketing surface, not a static portfolio list.>

## Agent usage
<Describe how AI/IDE assisted in scaffolding, structuring pages, designing the data model, and refining copy.>

## Additional Architecture Details
<Optional: tech stack, routing, data model, motion/animation choices, deployment notes.>
```

Constraints:
- Project must live in `submissions/divyaprakash04-project-3/`
- No secrets committed
- Must deploy successfully to Vercel

---

# 6. **Step-by-Step Phased Execution (Critical)**

Build sequentially.  
Do **not** summarize or use placeholders.  
Output full files.

---

## **PHASE 1 — Environment & Scaffolding (Execute Now)**

Create directory structure under:

```
submissions/divyaprakash04-project-3/
```

Output **fully**:

### `package.json`
```
{ ...your provided package.json... }
```

### `tailwind.config.js`
```
{ ...your provided tailwind config... }
```

### `postcss.config.js`
```
{ ...your provided postcss config... }
```

### `components.json`
```
{ ...your provided components.json... }
```

### `src/app/globals.css`
```
{ ...your provided globals.css... }
```

### `src/data/cohort.ts`
Include:
- 3 premium participants (including @DivyaPrakash04)
- 2 premium projects
- Cohort stats object

**Stop after Phase 1 and ask for approval.**

---

## **PHASE 2 — Core Layout & Hub Page**

After approval:

- Implement `src/app/layout.tsx`
- Implement `/` page with:
  - Hero section
  - Cohort stats
  - Partner narrative
  - Motion-enhanced sections

Stop and wait for feedback.

---

## **PHASE 3 — Participants & Projects**

After approval:

- Implement `/participants` and `/participants/[handle]`
- Implement `/projects` and project detail view
- Add framer-motion animations

---

## **PHASE 4 — Polish + PR Body + Git Commands**

After approval:

- Add branding/motion polish
- Generate PR body
- Output git commands:
  - `git add .`
  - `git commit -m "feat: add VibeHub Cohort 3 platform"`
  - `git push origin submissions/divyaprakash04-project-3`
- Provide final merge checklist

---

# **End of Prompt**

