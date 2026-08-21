---
name: GitHub publication permissions
description: Publishing source through the connected GitHub account and its workflow-file permission boundary.
---

Publish regular project files through the connected GitHub authorization, but treat `.github/workflows/` files as separately permissioned.

**Why:** The connected GitHub account can write the project source and assets, but GitHub rejects workflow-file tree entries without the additional workflow-file permission.

**How to apply:** Publish the app code, data, and documentation normally. Before adding or updating GitHub Actions workflows, confirm that the active GitHub authorization grants workflow-file write access.