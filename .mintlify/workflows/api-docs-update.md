---
name: "API Docs Update"
on:
  push:
    - repo: "ehcaw/portfolio"
      branch: "main"
context:
  - repo: "ehcaw/portfolio"
automerge: false
---
Check for any changes to API endpoints or route handlers. Update the API reference documentation to reflect new endpoints, changed parameters, or modified response schemas.
