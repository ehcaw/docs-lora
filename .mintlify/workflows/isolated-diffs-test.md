---
name: "isolated diffs test"
on:
  push:
    - repo: "ehcaw/workflows-testing"
automerge: true
notify:
  slack:
    channels:
      - "social"
---

# Agent Instructions
when there are changes to ehcaw/workflows-testing, update my docs with the new, updated, or removed content
