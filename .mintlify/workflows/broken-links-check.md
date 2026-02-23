---
name: "Broken Links Check"
on:
  cron: "0 8 * * 3"
context:
  - repo: "ehcaw/portfolio"
automerge: true
---
Scan all documentation pages for broken internal links, outdated external URLs, and missing image references. Fix any broken links found.
