# RUN CONFIG — Settings for This Session

Edit these before starting a run. The agent reads this file fresh every
session — it does NOT persist changes back into RULEBOOK.md.

```yaml
platform: indeed                # indeed | linkedin | naukri | other (name it)
target_cities: ["Noida", "Gurugram", "Delhi"]  # empty [] = no city restriction
max_jobs_to_process: 50         # stop after processing this many listings this run
auto_fill_external_forms: false # true = agent will also fill Google Forms / career-site
                                 # ATS forms it finds, not just Indeed's own apply flow.
                                 # Keep false until you've reviewed a few logged links
                                 # and trust the agent's judgement.
send_manual_emails: false       # true = agent will draft AND send emails where JD only
                                 # lists an email address (requires separate email-sending
                                 # tool/access to be wired up — leave false otherwise).
include_less_technical_roles: false  # true = also consider QA/testing, support, BD roles
                                      # per earlier conversation with the user.
resume_path: "docs/Resume_Aman_Mishra.pdf"
notes_for_this_run: ""          # free text — e.g. "focus only on AI/LLM roles today"
```