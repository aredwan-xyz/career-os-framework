# Module 04 — Pipeline Automation

> **Timeline:** Week 3+, ongoing  
> **Goal:** Build a machine that feeds you qualified opportunities every week without manual browsing

---

## Job Source Hierarchy

Not all applications are equal. Allocate your effort accordingly:

| Source | Avg. Conversion | Priority | Time Allocation |
|--------|----------------|----------|-----------------|
| Warm referral (direct intro) | 30–50% | ★★★★★ | 40% |
| Direct hiring manager outreach | 15–25% | ★★★★★ | 20% |
| Recruiter inbound (via signal building) | 10–20% | ★★★★ | 10% (passive) |
| Target company direct apply | 5–10% | ★★★ | 20% |
| LinkedIn / Indeed cold apply | 1–3% | ★★ | 10% |

**The core insight:** 50% of your effort should go to things that aren't "applying to jobs." Most people do the opposite and wonder why their conversion rate is terrible.

---

## Job Alert Setup — Never Browse

Set it up once. Let alerts come to you.

**Platforms to configure:**
1. **LinkedIn** — Job Alerts on saved searches (daily email)
2. **Indeed** — Saved searches with email frequency
3. **Wellfound** (AngelList) — for startup roles
4. **Greenhouse** / **Lever** — apply to company career pages directly via Google alerts
5. **Google Alerts** — `"[company name]" "we're hiring"` for target companies not on boards

**Setup rules:**
- Email digest only — never open the app to browse (it's a time trap)
- Keywords: your exact job title + 2–3 variations
- Location: your geography + "Remote"
- Frequency: daily
- Archive immediately after review — don't let it pile up

---

## Weekly Output Targets

Run these targets every week, without exception:

| Activity | Target | Notes |
|----------|--------|-------|
| Targeted applications | 8–12 | Skip anything that doesn't match your IEP |
| Hiring manager DMs | 5–8 | For every application sent |
| Referral requests | 2–3 | From your network at target companies |
| Informational interviews | 1–2 | Intelligence + relationship building |
| LinkedIn posts | 3 | The signal-building engine |
| LinkedIn comments on target company posts | 20–30 | Passive visibility |
| Follow-up messages | All pending at day 5 + 10 | Don't let anything go cold |

---

## The 8-Step Application Process

For every application, run this exact sequence:

```
Step 1: Qualify the role
  └── Does it match your IEP? If not, skip.
  
Step 2: Tailor your CV
  └── Run CV tailoring AI prompt → Swap bullets → ATS check (85+ required)
  
Step 3: Write cover letter
  └── Run cover letter AI prompt → Customize paragraph 1 → Review

Step 4: Find the hiring manager
  └── LinkedIn search: "[Company] + [role type] hiring" or
      search current employees with "hiring manager" or team lead titles

Step 5: Apply via the job board
  └── Note: date applied, job ID, and application link in your CRM

Step 6: Connect with the hiring manager on LinkedIn
  └── Do this BEFORE or simultaneously with applying

Step 7: Send a value-first DM (24–48h after applying)
  └── Use the DM template below

Step 8: Log everything in your CRM
  └── Set a follow-up reminder for day 5 and day 10
```

Total time per application: 8–12 minutes.

---

## Outreach DM Templates

### Post-Application DM to Hiring Manager

```
Hi [Name] — I just applied for the [Role] on your team.

I've spent the last [X years] helping [company type] [specific outcome they care about], 
most recently [specific result with a number].

Wanted to put a face to the application. Happy to share more if useful — 
either way, best of luck with the search.

[Your Name]
```

**Rules:**
- Under 75 words
- Specific result in paragraph 2 — no generic "I'm passionate about..."
- "Either way, best of luck" shows confidence and takes pressure off them
- Never ask for a job in the first message

---

### Cold Outreach — No Open Role

```
Hi [Name] — I've been following [Company]'s work on [specific product/initiative] closely.

I'm a [role] who [specific result] — the kind of [problem] your team is probably thinking about.

Would you be open to a 15-minute call? No agenda, just genuine curiosity about how you're 
thinking about [relevant challenge]. I can work around your schedule.

[Your Name]
```

---

### Referral Ask — Weak Connection

```
Hey [Name] — hope things are going well at [Company].

I'm exploring a move into [space/role] and noticed [Company] is hiring for [Role]. 
I know it's a big ask, but if you'd be open to a referral or an intro to the 
hiring team, I'd genuinely appreciate it.

Totally understand if it's not the right time — no pressure either way.

[Your Name]
```

---

### Follow-Up (Day 5 — No Response)

```
Hi [Name] — just wanted to follow up on my application for [Role].

Still very interested and happy to answer any questions about my background.

Best,
[Your Name]
```

**Rule:** Short follow-ups outperform long ones. Don't re-pitch. Just stay visible.

---

### Follow-Up (Day 10 — Still No Response)

```
Hi [Name] — one last nudge on [Role].

[One new piece of evidence or a relevant observation about their business]

Happy to connect whenever it's convenient.

[Your Name]
```

After day 10 with no response: move to "passive" in your CRM. Check quarterly.

---

## CRM Setup

Track every application. Without a CRM, you'll lose track, miss follow-ups, and have no data to improve from.

### Notion CRM Structure (free template in [`templates/job-tracker.md`](../templates/job-tracker.md))

**Columns:**
- Company
- Role title
- Source (LinkedIn / Referral / Direct / Inbound)
- Date applied
- HM found? (Y/N)
- HM contacted? (Y/N)
- Stage (Applied / Screened / Interview 1 / Interview 2 / Final / Offer / Rejected / Stalled)
- Response received (date)
- Next action
- Next action date
- Notes
- Salary range (from JD or research)
- Link to application

**Weekly CRM Review (15 min every Friday):**
1. Update all stages
2. Identify everything due for follow-up
3. Archive anything dead (no response in 20+ days)
4. Calculate your weekly conversion rates: applications → responses, responses → interviews
5. Adjust targeting if conversion is below 10% application → response

---

## Automation Stack

| Tool | Purpose | Cost |
|------|---------|------|
| [Teal](https://tealhq.com) | Job tracker + auto-imports from job boards | Free |
| Claude / ChatGPT | CV tailoring, cover letters, outreach drafts | Free/Paid |
| [Jobscan](https://jobscan.co) | ATS match scoring | Paid |
| [LinkedIn Sales Navigator](https://business.linkedin.com/sales-solutions) | Finding hiring managers | Paid (trial available) |
| [Hunter.io](https://hunter.io) | Finding email addresses | Free tier |
| [Notion](https://notion.so) | CRM and tracking | Free |
| [Calendly](https://calendly.com) | Interview scheduling | Free |
| [Google Alerts](https://alerts.google.com) | Target company monitoring | Free |

---

## Module 04 Deliverables Checklist

- [ ] Job alerts configured on 3+ platforms
- [ ] CRM set up in Notion/Teal/Airtable
- [ ] 8-step application process internalized
- [ ] DM templates saved and personalized
- [ ] First 10 applications sent
- [ ] First 5 HM DMs sent
- [ ] Follow-up reminders set for all pending applications
- [ ] Automation stack accounts created

---

**Previous:** [Module 03 — Application Materials ←](03-materials.md)  
**Next:** [Module 05 — Network Activation →](05-network.md)
