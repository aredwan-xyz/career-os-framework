# Automation Stack — Complete Tool Guide

A lean, mostly-free stack that handles discovery, tailoring, tracking, and outreach.

---

## The Core Stack

### 1. Teal — Job Tracking & Discovery
**URL:** https://tealhq.com  
**Cost:** Free  
**Use for:** Auto-importing job postings from LinkedIn, Indeed, and other boards directly into a CRM. Tracks application stages, saves JDs, and has a built-in resume builder.  
**Setup:**
1. Install the Chrome extension
2. Browse job boards normally — click the Teal button to save any role
3. Your CRM populates automatically with company, title, date, and the full JD

---

### 2. Claude / ChatGPT — AI Assistant
**URL:** https://claude.ai | https://chat.openai.com  
**Cost:** Free tier / $20/month Pro  
**Use for:** CV tailoring, cover letters, outreach drafts, mock interviews, STAR story sharpening, LinkedIn posts, interview research summaries  
**Best practices:**
- Keep a prompt library (see [`../prompts/`](../prompts/)) — never start from scratch
- Paste the full JD into every CV tailoring session
- Use Claude for longer, more nuanced tasks; GPT-4 is comparable
- Save good outputs as templates for future roles

---

### 3. Jobscan — ATS Scoring
**URL:** https://jobscan.co  
**Cost:** Free (limited scans) / $50/month  
**Use for:** Paste your CV + a JD → get a match score + specific missing keywords  
**Workflow:**
1. Paste tailored CV + JD
2. Check score (target: 85+)
3. Add missing high-priority keywords to your CV naturally
4. Re-scan until 85+

---

### 4. LinkedIn Sales Navigator — Finding Decision Makers
**URL:** https://business.linkedin.com/sales-solutions  
**Cost:** $99/month (free 30-day trial — use the trial strategically)  
**Use for:** Finding the hiring manager or team lead for every company you're targeting  
**Alternative (free):** Boolean LinkedIn search: `"[Company]" AND ("hiring manager" OR "engineering manager" OR "VP" OR "head of") AND "[function]"`

---

### 5. Hunter.io — Email Finding
**URL:** https://hunter.io  
**Cost:** Free tier (25 searches/month) / Paid  
**Use for:** Finding direct email addresses when you want to send email instead of LinkedIn DM  
**Alternative:** Guess the format (firstname@company.com, first.last@company.com) and verify with mail-tester.com

---

### 6. Notion — CRM & Knowledge Base
**URL:** https://notion.so  
**Cost:** Free personal tier  
**Use for:** Your job search CRM, STAR story bank, research notes, weekly reviews  
**Alternative:** Airtable (more structured), Trello (simpler), Google Sheets (most basic)  
**Template:** See [`../templates/job-tracker.md`](../templates/job-tracker.md)

---

### 7. Calendly — Interview Scheduling
**URL:** https://calendly.com  
**Cost:** Free tier  
**Use for:** Sending a scheduling link instead of endless email back-and-forth  
**Setup:**
1. Connect to Google or Outlook Calendar
2. Set your available slots (avoid very early and very late — you want to be sharp)
3. Use your Calendly link in follow-up emails: "Happy to connect — here's a link to book a time that works"

---

### 8. Google Alerts — Target Company Monitoring
**URL:** https://alerts.google.com  
**Cost:** Free  
**Use for:** Get notified when target companies publish news, job postings, or press mentions  
**Recommended alerts:**
- `"[Company name]" "we're hiring"` or `"[Company name]" hiring [role type]`
- `"[Company name]" site:techcrunch.com OR site:venturebeat.com`
- `[Founder/CEO name] interview`

---

### 9. Taplio — LinkedIn Content Scheduling
**URL:** https://taplio.com  
**Cost:** $49/month  
**Use for:** Writing, scheduling, and analyzing LinkedIn posts  
**Free alternative:** LinkedIn's native post scheduler (available through Creator Mode)  
**Alternative:** Buffer ($6/month) — simpler but works

---

### 10. Levels.fyi — Salary Research (Tech)
**URL:** https://levels.fyi  
**Cost:** Free  
**Use for:** Market salary data by role, level, company, and location. Most granular database for tech roles.  
**Also use:** Glassdoor, Blind, LinkedIn Salary, Payscale for non-tech

---

## Minimal Free Stack (Zero Budget)

If you want to start with no cost:

| Need | Free Tool |
|------|----------|
| Job discovery | LinkedIn alerts + Indeed alerts |
| CRM | Notion free / Google Sheets |
| AI assistance | Claude.ai free / ChatGPT free |
| ATS checking | Jobscan (3 free scans/month) |
| HM finding | LinkedIn Boolean search |
| Content scheduling | LinkedIn native scheduler |
| Interview scheduling | Google Calendar share |
| Salary research | Glassdoor + Levels.fyi |

---

## Recommended Tool Budget by Search Intensity

| Search Level | Monthly Budget | Tools to Prioritize |
|-------------|---------------|---------------------|
| Passive (occasional looking) | $0 | Free stack only |
| Active (8–12 apps/week) | $20–30 | Claude Pro + Jobscan |
| Aggressive (12+ apps/week) | $70–100 | Above + LinkedIn Sales Nav trial + Taplio |
