# RULEBOOK — Aman Mishra Job Application Reference

This file is the single source of truth for any question the agent encounters
while filling out a job application. If a question isn't covered here, the
agent MUST stop and ask the user rather than guessing.

---

## 1. Personal Details

| Field | Value |
|---|---|
| Full Name | Aman Mishra |
| Email | amanmishra.5272@gmail.com |
| Phone | +91-8851225097 |
| Current Location | Mohali, Punjab, India |
| Hometown (birthplace) | Pratapgarh, Uttar Pradesh |
| Grew up / brought up in | Noida, Uttar Pradesh |
| LinkedIn | linkedin.com/in/iamanmishra |
| GitHub | github.com/iaman-mishra |
| Highest Education | B.Tech, Computer Science Engineering, IIMT College of Engineering, Greater Noida (2021–2025) |
| Graduation Year | 2025 |
| Citizenship | Indian |
| Work Authorization | Legally authorized to work in India; does NOT hold or require visa/work permit for any other country |
| Notice Period | 30 days |
| Current Employer | 75Way Technologies Pvt Ltd |
| Current Role | Associate Software Development Engineer |
| Employment Start Date | June 2025 |
| Total Experience | ~1 year 3 months (as of Sept 2026) |
| Current CTC (fixed, excl. ESOPs/bonus) | ₹3.6 LPA |
| 10th class % | 70% |
| 12th class % | 65.8% |
| Graduation CGPA | 7.47 CGPA (convert to % if a form demands it: 7.47 × 10 = ~74.7%) |
| Postal Code (Mohali) | 160055 |
| Address (if a form asks) | Mohali, Punjab, India – 160055 |

---

## 2. Domain & Stack — What to Apply For

**Primary stack (strong match — apply confidently):**
Python, FastAPI, JavaScript, TypeScript, React.js, Next.js, Node.js, Express.js,
NestJS, REST APIs, PostgreSQL, MongoDB, Redis, Docker, AWS (S3, EC2, RDS, ECR),
Git/CI-CD, LangChain, LangGraph, RAG, LLM Agents, Prompt Engineering, MCP, n8n,
OpenAI/Anthropic/Gemini API integration.

**Target role titles (in priority order):**
1. Full Stack Developer / Engineer
2. Backend Developer (Python or Node.js)
3. AI/GenAI Engineer / AI Full-Stack Engineer
4. Forward Deployed Engineer (FDE) / AI Solutions Engineer — customer-facing
   AI implementation roles; strong fit given hands-on LangChain/RAG/agent
   experience even without "FDE" title history
5. MERN Stack Developer
6. Python Developer
7. React/Frontend Developer (only if 1-3 yrs range, not senior)
8. Team Lead / Tech Lead (Software Development) — apply even though current
   experience (~1 yr) is below typical Team Lead expectations (usually 3-5+
   yrs), UNLESS the JD explicitly gates on years of people-management
   experience as a hard requirement (see Section 2 "Acceptable experience
   range" note below for how to judge this)

**Note on Team Lead / FDE roles specifically:**
- **Forward Deployed Engineer**: this is a strong genuine fit — FDE roles
  value hands-on AI/LLM integration, RAG, agent-building, and
  customer-facing technical delivery, which lines up well with existing
  experience (BytesAI, LangChain agent work, n8n automation). Apply
  normally, do not treat the "1+ years experience only" gap as a blocker
  unless the JD explicitly demands 3+ years AND frames it as a hard filter.


**Acceptable experience range:** 0–2 years listed requirement.
(1 years over-requirement is still worth applying to; skip anything asking
for 2+ years mandatory, or explicitly "Senior".)

**Hard skip / auto-reject criteria** (agent must NOT apply, just log under
"Skipped — Not a Fit" with reason):
- Role requires a visa / work authorization / C2C / W2 outside India, unless
  it's a remote role explicitly open globally.
- Role requires Tier-1 institute pedigree as a hard filter.
- Role is fresher-only / campus hiring AND pays below current CTC equivalent.
- Role's core stack has zero overlap with primary stack (e.g. pure Java,
  pure PHP, embedded/hardware, Salesforce/SAP functional roles) UNLESS the
  JD explicitly says "any backend language" or similar.
- Non-technical roles unrelated to software: pure sales, marketing, pure
  business development, content writing, HR — UNLESS user has separately
  told the agent to include "less technical / support" roles for a given run.
- Suspicious/scam signals: personal Gmail/Yahoo recruiter address for a
  US role paying unusually high (e.g. $150k+) with no company name, or asking
  for payment/bank details before any interview. Flag these under a separate
  "⚠️ Suspicious — Did Not Apply" section, do not send any personal info.

**Soft-flag (agent may apply but must note the caveat in the log):**
- Night shift / US shift timing.
- 6-day work week.
- On-site with no remote/hybrid option in a city other than current location.
- Requires relocation.

---

## 3. Expected CTC Logic (Dynamic by City)

Current fixed CTC: ₹3.6 LPA (Mohali-based, ~1 year experience).

When asked "Expected CTC", the agent computes a number using the base formula:

```
expected_ctc = current_ctc × city_multiplier × role_stretch_factor
```

**City multiplier** (distance-from-home adjustment — home base is Noida.
Cities close to home need a smaller comp bump to justify; cities far from
home / requiring full relocation across the country need a bigger bump,
since cost of living, moving expenses, and being away from family all go up
with distance):

| City tier | Cities | Multiplier | Why |
|---|---|---|---|
| Home zone (no real relocation) | Noida, Delhi NCR, Gurugram, Ghaziabad, Faridabad | 1.5–1.95x | Living at/near home, minimal disruption — ask **₹5.5 – 7 LPA** |
| Tier 2 (own/nearby region) | Mohali, Chandigarh, Lucknow | 1.4–1.6x | Still North India, manageable |
| Far relocation (different state, high COL, far from family) | Bangalore, Pune, Hyderabad, Ahmedabad, Chennai, Mumbai | 1.9–2.2x | Full relocation across the country — higher COL + distance from home justifies a bigger jump |
| Remote (India, company city unclear) | — | 1.5x | No relocation at all |
| International remote (no visa needed, salary in USD) | — | Do NOT scale from INR baseline — quote market USD rate for the role/stack (research the role's typical range; if unknown, state "open to discussing based on role scope" rather than a fixed number) |

**Home zone quick reference (Noida / Delhi NCR / Gurugram):**
Always target **₹5.5 – 7 LPA** for these cities regardless of company size —
use the lower end (~₹5.5–6 LPA) for smaller/early-stage companies and the
higher end (~₹6.5–7 LPA) for larger/well-established companies, but never
quote below ₹5.5 LPA or above ₹7 LPA for this zone.

**Role stretch factor** (extra bump if the role is a clear step up in scope,
tech depth, or seniority language like "own end-to-end", "founding engineer",
AI-specialist roles):
- Standard role at same level: 1.0x
- Role with added AI/LLM specialization requirement matching your strength: 1.05–1.1x
- Founding/early-stage/high-ownership role: 1.1x

**Rounding:** Round to the nearest ₹0.5 LPA. Never quote decimals like ₹6.35 LPA.

**Worked examples:**
- Noida/Delhi NCR/Gurugram, small/early-stage company → quote **₹5.5 – 6 LPA**
- Noida/Delhi NCR/Gurugram, large/established company → quote **₹6.5 – 7 LPA**
- Mohali/Chandigarh, standard role → 3.6 × 1.5 = ~5.4 → quote **₹5.5 LPA**
- Bangalore/Pune/Hyderabad, standard role → 3.6 × 2.0 = ~7.2 → quote **₹7 – 7.5 LPA**
- Bangalore/Pune/Hyderabad, AI-specialist role → 3.6 × 2.0 × 1.1 = ~7.9 → quote **₹8 – 8.5 LPA**
- Ahmedabad/Chennai, standard role → 3.6 × 1.9 = ~6.8 → quote **₹7 LPA**
- Remote India, unclear city → 3.6 × 1.5 = ~5.4 → quote **₹5.5 LPA**

**Always give a small range, not a single hard number**, e.g. "₹6 – 6.5 LPA",
unless the form strictly requires a single numeric value, in which case use
the lower-middle of that range.

**If the form asks for expected CTC as a percentage hike instead of absolute
number:** state 60–90% hike depending on city tier above.

---

## 4. Standard Answers to Common Application Questions

Use these verbatim/near-verbatim unless the JD context clearly demands a
tweak (agent may lightly adapt wording to match company name/role name).

| Question | Answer |
|---|---|
| Current CTC | ₹3.6 LPA (fixed, no ESOPs) |
| Expected CTC | See Section 3 dynamic logic |
| Notice period | 30 days |
| Reason for change / Why leaving current job | "Looking for a role with greater ownership, exposure to [role's core tech, e.g. AI/LLM systems or a larger-scale product], and stronger growth opportunities than my current position offers." |
| Why do you want to join us / this role | Generate a 2–4 sentence tailored answer referencing 2–3 specific things from the JD (tech stack overlap, company mission/domain, growth stage) + tie back to Aman's LangChain/RAG/full-stack experience. Never copy-paste a generic answer verbatim across companies — must reference the specific company name and domain. |
| Why should we hire you / what makes you a fit | Reference: production experience shipping 5+ apps serving 5000+ users, RAG/LangChain agent system (BytesAI), Redis caching that cut DB load 40-60%, ownership mindset, fast learner. |
| Current location | Mohali, Punjab |
| Hometown / native place | Pratapgarh, Uttar Pradesh (birthplace — use this specifically when a form asks "hometown" or "native place", NOT current location) |
| Where did you grow up / brought up | Noida, Uttar Pradesh (use this if a form specifically asks where you were raised/grew up, distinct from "hometown") |
| Willing to relocate | Yes, if role is a strong fit and city is within India. No, only if user has explicitly restricted a given run to "local only". |
| Available for offline / in-person / face-to-face interview | **Do NOT default to "Yes" blindly.** Apply this logic: (1) If the job's city is Mohali, Chandigarh, Noida, or Delhi NCR (i.e. reachable within a day trip from current location) → Yes. (2) If the job's city is far (Bangalore, Pune, Hyderabad, Chennai, Ahmedabad, Mumbai, etc.) → answer "Yes, with advance notice to arrange travel" if the form allows free text, or select "Yes" only if the user has separately confirmed willingness for that specific far-city role — otherwise select **"No" / "Prefer virtual interview"** if that option exists, or flag as "Paused — Needs Input" if the form forces a binary Yes/No with no nuance and the city is far. Never silently commit to an in-person interview in a city that isn't reachable practically. |
| Willing to work onsite / WFO | Yes, unless user says otherwise for a specific run. |
| Immediate joiner? | No — 30 days notice. If asked "can you join in X days" and X ≥ 30, answer Yes. |
| Legally authorized to work in India | Yes |
| Require visa sponsorship (any country) | No |
| Government employee / family in government | No |
| Non-compete / non-solicitation with current employer | No |
| Disability | No (or "Prefer not to say" if the form offers it and user hasn't stated otherwise) |
| Gender | Male |
| Veteran status | Not a veteran / Not applicable (India-based candidate) |
| Age 18+ / DOB proof available | Yes |
| 12th class certificate available | Yes |
| UAN / PF number | Ask user directly — not stored here yet. If field is optional, skip. If mandatory and unknown, flag in log for user follow-up rather than guessing. |
| Portfolio / personal website | https://iamanmishra.vercel.app/ |
| GitHub repo link for "best project" | github.com/iaman-mishra (point to ReviewBytes or Greenroom write-up per JD relevance; do not fabricate public repo links that don't exist) |

---

## 4a. Indeed "Screener Gate" Policy — "It looks like you don't meet these
employer requirements" / "Apply anyway" intervention

Indeed sometimes shows a hard-stop screen listing the employer's stated
minimums (e.g. "Node.js: 3 years (Required)") after you answer its
screener questions, with two options: "Return to job search" or "Apply
anyway". Use this policy instead of pausing every time:

- **Use "Apply anyway" and submit** when the gap is a **soft/experience-year
  mismatch** you can reasonably argue around in an interview — i.e. the
  gate is about years of experience in a skill you do genuinely have
  (Node.js, SQL, Python, React, etc.), even if the number is higher than
  your literal years (e.g. they want 3, you have ~1–1.5 years but strong
  hands-on production work). Apply anyway in these cases — do NOT pause.
- **Skip / pause and ask the user** only when the gate is a **hard factual
  mismatch that can't be argued around in an interview** — specifically:
  - A location gate requiring you to *already* live in a specific city you
    don't live in (not just "willing to relocate" — an actual current-
    residence check).
  - A citizenship/visa/work-authorization gate you don't meet.
  - A hard minimum total experience gate that's more than double your
    actual total experience (e.g. they require 5+ years and you have ~1).
  - Anything else that isn't a skill-years soft gate as described above.
- When in doubt between these two cases, default to **"Apply anyway"** —
  most of these gates are soft filters employers set generically and don't
  strictly enforce, and the cost of trying is low. Only pause for the
  narrow hard-mismatch cases above.

---

## 5. "Best Project" Description Bank (reusable, tweak per JD emphasis)

**ReviewBytes (AI/LLM-heavy JDs):**
"AI-first, gamified medical education platform. Designed an end-to-end LLM-powered
content pipeline validating and storing 10,000+ structured documents in a
hierarchical PostgreSQL schema. Built BytesAI, a domain-constrained multi-agent
chat system using LangChain with RAG-based retrieval via pgVector. Implemented
Redis caching (TTL strategies) that cut DB load 40-60% and improved API response
times up to 2x. Fully Dockerized with GitHub Actions CI/CD to AWS EC2."

**Greenroom (full-stack/backend-heavy JDs):**
"Social media platform for athletes. Built and enhanced 10+ full-stack features
in production using React.js and Node.js. Designed a chunk-based video upload
system using AWS S3 pre-signed URLs to handle large media reliably. Implemented
access/refresh token authentication for secure sessions."

---

## 6. Things the Agent Must NEVER Do

- Never invent a portfolio URL, GitHub repo, certification, or employment
  history detail not present in this file or the resume.
- Never submit payment information, bank details, or ID document scans as
  part of an "application" — flag and stop if a form asks for this.
- Never agree to unusual pre-employment financial conditions (e.g. "pay a
  deposit for training kit").
- Never answer a legal/compliance question (e.g. "have you had a background
  check issue", "any pending litigation") without explicit user confirmation
  — always flag these for manual review instead of guessing "No" by default.
- Never submit an application to a role in the "Hard skip" list.
- Never apply twice to the exact same job posting (same company + same role
  title + same JD URL) — check `applications.md` first for duplicates.

---

## 7. Update Log

*(User can append changes here — e.g. new CTC after a raise, new notice
period, new preferred cities, etc. Agent should re-read this file at the
start of every run.)*

- 2026-09-26: Initial rulebook created.