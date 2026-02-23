---
name: "Deprecation Notice"
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
Identify any deprecated functions, endpoints, or features in the latest changes. Add deprecation warnings to the relevant documentation pages and suggest migration paths.
