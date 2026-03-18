---
name: "isolated diffs test"
on:
  push:
    - repo: "ehcaw/workflows-testing"
notify:
  slack:
    channels:
      - new-channel
---

# Agent Instructions
when there are changes to ehcaw/workflows-testing, update my docs with the new, updated, or removed content
