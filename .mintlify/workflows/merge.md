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
automerge: false
---
Be very wordy in your changes. Pick up any change to the configured repos and update my docs accordingly. Make new pages if new content is being added, and if content that is in the repos that isn't in the docs exists, make new pages for them too.
