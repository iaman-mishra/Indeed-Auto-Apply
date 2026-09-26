# Job Application Log

This file is the running record of every job the agent has processed.
The agent appends to it after every job (see AGENT_INSTRUCTIONS.md Step 4).
Do not delete past entries — this file is also used to prevent duplicate
applications across runs.

Format per entry:

```
### [Date] — [Company] — [Role Title]
- JD URL: <link>
- City: <city>
- Platform: Indeed / LinkedIn / Company site / etc.
- Decision: Applied (native) / Applied (external, auto-filled) / External —
  Manual Required / Manual Email Required / Skipped — Not a Fit /
  Suspicious — Did Not Apply / Paused — Needs Input
- Contact info found in JD: <email / phone / name, or "None listed">
- Notes: <caveats — night shift, relocation, CTC quoted, unresolved
  question text if paused, reason if skipped, etc.>
```

---

## ✅ Applied via Portal (Native Apply)

*(Jobs the agent applied to directly through Indeed/LinkedIn Easy Apply etc.)*

---

## 🌐 External Application Required (Career Page / Google Form / ATS)

*(Jobs where the platform's "Apply" button redirected elsewhere. The agent
extracted the link and logged it here instead of auto-submitting, unless
external auto-fill was explicitly enabled for that run.)*

---

## 📧 Manual Email Application Required

*(Jobs where the JD only listed an email/phone and no form — agent does not
send emails automatically unless configured to. Follow up yourself using
these contacts.)*

---

## ⏸️ Paused — Needs Input

*(Jobs where a form asked a question not covered by RULEBOOK.md. Agent
stopped before submitting. Answer the listed question, then either update
RULEBOOK.md for future runs or tell the agent the answer for this one.)*

---

## ⏭️ Skipped — Not a Fit

*(Jobs the agent deliberately did not apply to, with a one-line reason
each — e.g. wrong stack, seniority mismatch, visa requirement.)*

---

## ⚠️ Suspicious — Did Not Apply

*(Listings that showed scam-like signals — unusually high pay with a
personal email domain, upfront payment requests, etc. No personal info
was submitted for these.)*

---

*(No entries yet — this is the starter template.)*
