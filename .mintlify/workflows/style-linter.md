---
name: "Style Linter"
on:
  cron: "0 10 * * 5"
context:
  - repo: "ehcaw/portfolio"
automerge: true
---
Review all documentation pages for consistent writing style, formatting, and tone. Fix any inconsistencies in heading capitalization, code block formatting, and admonition usage.
