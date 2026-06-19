---
title: Sample article with a GUID
description: Baseline test fixture for the GUID workflows.
ms.date: 06/19/2026
awa-articleGuid: 11111111-1111-1111-1111-111111111111
---

# Sample article with a GUID

This file is a committed baseline fixture for testing the GUID workflows.

Use it for:

- **Changed/removed test:** edit or delete the `awa-articleGuid` value above in a PR; GuidCheck should fail and comment.
- **Duplicate test:** add a new file that reuses `11111111-1111-1111-1111-111111111111`; GuidCheck should fail and comment.
