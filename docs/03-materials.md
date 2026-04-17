# Module 03 — Application Materials

> **Timeline:** Build once in Week 2–3, use and refine forever  
> **Goal:** A modular system that produces world-class, tailored applications in 8 minutes flat

Most people have one CV they update occasionally and a cover letter template they copy-paste. This module replaces that with a systematic engine.

---

## The 4-Layer CV System

### Layer 1 — Master CV (The Archive)

**Purpose:** Never sent. Your complete professional record.  
**Length:** 4–8 pages  
**Update cadence:** Monthly, and immediately after any significant win

This is your source of truth. Every role, every metric, every project, every achievement — nothing omitted. Organized so you can quickly find and extract bullets for tailored applications.

**Structure:**
```
MASTER CV
│
├── Executive Summary (3–4 versions for different role types)
├── Core Skills (categorized: Technical / Domain / Leadership)
│
├── EXPERIENCE
│   ├── [Company, Role, Date]
│   │   ├── [Impact bullets — tagged: revenue/technical/leadership/etc.]
│   │   ├── [Challenge bullets]
│   │   └── [Context bullets]
│   └── [Next role...]
│
├── PROJECTS (notable work outside main roles)
├── EDUCATION
├── CERTIFICATIONS
└── PUBLICATIONS / TALKS / OPEN SOURCE
```

**Bullet tagging system:**
Add a tag at the end of each bullet in your master CV:
- `[R]` — Revenue / growth impact
- `[T]` — Technical / engineering
- `[L]` — Leadership / management
- `[P]` — Process / efficiency
- `[C]` — Customer / user impact
- `[D]` — Data / analysis

When tailoring, just filter by relevant tags.

---

### Layer 2 — Base CV (The 1-Page Core)

**Purpose:** Your ATS-safe default. Passes screening without tailoring.  
**Length:** 1 page (2 pages max for 10+ years experience)  
**ATS target score:** 80+ on Jobscan

Selected from your master CV — the 12–15 bullets that best represent your overall profile.

**Formatting rules for ATS compatibility:**
- Single column layout (no text boxes, tables, or columns)
- Standard section headings: Experience, Education, Skills
- No headers or footers (ATS often can't read these)
- No graphics, icons, or photos
- Standard fonts: Calibri, Arial, Georgia, Times New Roman
- .docx format for ATS; PDF for human readers (have both ready)
- File name: `FirstName-LastName-Resume.pdf`

---

### Layer 3 — Tailored CV (Per-Role Variant)

**Purpose:** Maximizes match score for each specific application.  
**Time to produce:** 5–8 minutes with the AI prompt  
**ATS target score:** 85+ on Jobscan

**The 8-minute tailoring process:**
1. Copy the job description (2 min)
2. Run the CV Tailoring AI prompt (see below)
3. Swap in 3–4 bullets from master CV as suggested (2 min)
4. Check score on Jobscan — must be 85+ (1 min)
5. Update executive summary with company name and key priority (2 min)
6. Export as PDF with correct filename (1 min)

> **AI Prompt:** See [`prompts/cv-tailoring.md`](../prompts/cv-tailoring.md)

---

### Layer 4 — Executive Summary (The 3-Line Hook)

**Purpose:** The first thing a human sees above your experience. Sets the frame.  
**Length:** 2–3 sentences

**Formula:**
```
[Role] with [X years] of experience [key strength/approach].
Known for [best measurable outcome] at [company type].
Currently focused on [what you're targeting and why].
```

**Example:**
```
ML Engineer with 6 years building production AI systems for fintech companies.
Reduced model inference costs 62% at two Series B startups, saving $80K/month combined.
Currently targeting ML infrastructure roles at AI-native companies scaling their first production LLM systems.
```

Rewrite the third sentence for each application to reference the company by name where possible.

---

## ATS Optimization Cheatsheet

Applicant Tracking Systems reject ~75% of CVs before a human sees them. Pass the filter:

| Rule | Why |
|------|-----|
| Use exact keywords from the JD | ATS matches exact strings |
| Spell out acronyms first time | ATS may not match "PM" to "Product Manager" |
| Use standard date formats | MM/YYYY |
| Don't use tables or columns | ATS linearizes content unpredictably |
| Save as .docx AND .pdf | Some ATS prefer .docx |
| Keep formatting minimal | Bold and italics fine; text boxes break |
| Include a Skills section | ATS often parses this specifically |
| Use the job title from the posting | Exact match matters |

**Tools:**
- [Jobscan](https://jobscan.co) — paste CV + JD, get match score and keyword gaps
- [Resume Worded](https://resumeworded.com) — ATS + human readability scoring
- [EnhanCV](https://enhancv.com) — template library with ATS-friendly designs

---

## Cover Letter System

Most cover letters are terrible because they're about the candidate, not the employer. Flip this.

### The 3-Paragraph Framework

**Paragraph 1 — The Hook (Why them, specifically)**
- One sentence proving you've done your research
- Reference: a specific product feature, recent hire, press coverage, mission statement, or challenge they've publicly discussed
- Never start with "I am excited to apply for..."

**Examples:**
- "Your recent pivot to real-time fraud detection — covered in the Fintech Times last month — is exactly the infrastructure problem I've been solving for the last three years."
- "I've been following Acme's approach to carbon accounting since your Series A, and the gap between your data pipeline capabilities and what enterprise clients need is a problem I've solved twice."

**Paragraph 2 — The Proof (Your best STAR story)**
- One concrete example directly relevant to their biggest challenge
- Format: Situation → Action → Result
- 80–100 words maximum
- Always include a number

**Paragraph 3 — The CTA (Confident close)**
- One sentence on fit
- One sentence requesting the call
- Not "I hope to hear from you" — that's passive and forgettable

**Example close:**
"Given your team's focus on scaling ML inference, my experience cutting costs 62% at similar-stage companies feels directly applicable. I'd welcome 20 minutes to explore this further — happy to work around your schedule."

### Cover Letter Rules
- Never exceed one page
- Address to a named person where possible — find the hiring manager on LinkedIn
- Send as PDF; name the file: `FirstName-LastName-CoverLetter-CompanyName.pdf`
- Update for every application — a generic cover letter is often worse than none

> **AI Prompt:** See [`prompts/cover-letter.md`](../prompts/cover-letter.md)

---

## Templates

- [`templates/master-cv.md`](../templates/master-cv.md) — Master CV structure with tagging system
- [`templates/cover-letter.md`](../templates/cover-letter.md) — Cover letter template with examples

---

## Module 03 Deliverables Checklist

- [ ] Master CV built (all roles, all metrics, all bullets tagged)
- [ ] Base CV created (1 page, ATS score 80+)
- [ ] 4 executive summary variants written for different role types
- [ ] AI tailoring prompt tested on 3 real JDs
- [ ] Cover letter framework internalized, template ready
- [ ] Jobscan account set up
- [ ] Both .docx and .pdf versions ready
- [ ] Portfolio URL in CV header

---

**Previous:** [Module 02 — Signal Building ←](02-signal.md)  
**Next:** [Module 04 — Pipeline Automation →](04-pipeline.md)
