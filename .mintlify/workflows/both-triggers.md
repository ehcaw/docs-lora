---
name: "Both Triggers"
on:
  push:
    - repo: "ehcaw/portfolio"
      branch: "main"
  cron: "0 9 * * 1"
---
This workflow specifies both push and cron triggers simultaneously.
