---
name: "Changelog Generator"
on:
  push:
    - repo: "ehcaw/portfolio"
      branch: "main"
    - repo: "ehcaw/pointer"
      branch: "main"
context:
  - repo: "ehcaw/portfolio"
  - repo: "ehcaw/pointer"
automerge: false
---
Generate a changelog entry based on the latest commits. Add the entry to the changelog page with a summary of what changed and why.
