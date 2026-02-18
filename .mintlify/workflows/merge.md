---
name: "Merge Trigger Test"
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
Be very wordy in your changes. Pick up any change that occurs and update my docs accordingly.
