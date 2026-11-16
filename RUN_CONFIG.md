# RUN CONFIG — Settings for This Session

Edit these before starting a run. The agent reads this file fresh every
session — it does NOT persist changes back into RULEBOOK.md.

```yaml
platform: glassdoor                # indeed | linkedin | naukri | other (name it)
target_cities: []  # empty [] = no city restriction
max_job_age_days: 7             # strict: only jobs posted within the last N days
max_jobs_to_process: 50         # target number of actionable jobs: applied or external-required
resume_path: "docs/Resume_Aman_Mishra.pdf"
notes_for_this_run: ""          # free text — e.g. "focus only on AI/LLM roles today"
```
