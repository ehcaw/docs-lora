---
name: "Weekly Summary"
on:
  cron: "0 9 * * 5"
context:
  - repo: "ehcaw/portfolio"
  - repo: "ehcaw/pointer"
automerge: true
---
Generate a weekly summary of all documentation changes made during the week. Add it as an entry to a summary page so the team can review what was updated.
