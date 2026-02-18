---
name: "Scheduled Docs Sync"
on:
  cron: "0 9 * * 1"
context:
  - repo: "ehcaw/portfolio"
automerge: true
---
Review the latest changes in the repository and update the documentation to reflect any new features or modifications.
