---
name: "README Sync"
on:
  push:
    - repo: "ehcaw/portfolio"
    - repo: "ehcaw/pointer"
context:
  - repo: "ehcaw/portfolio"
  - repo: "ehcaw/pointer"
automerge: true
---
Sync the README files from the source repositories into the corresponding documentation pages. Preserve any extra documentation-specific content that doesn't exist in the README.
