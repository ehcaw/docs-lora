---
name: "test"
on:
  push:
    - repo: "ehcaw/docs-lora"
notify:
  slack:
    channels:
      - "all-ryan-testing"
---

when there are pushes to main on docs-lora, add a page about wild kratts.
