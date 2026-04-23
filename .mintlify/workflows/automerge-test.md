---
name: "test"
on:
  push:
    - repo: "ehcaw/docs-lora"
    - repo: "ehcaw/colorme"
context:
  - repo: "ehcaw/console.blog"
automerge: true
---

when there are pushes to main on docs-lora, add a page about wild kratts.
