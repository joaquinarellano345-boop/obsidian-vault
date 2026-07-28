---
source_file: "tests/test_chunking.py"
type: "rationale"
community: "_extract_with_adaptive_retry"
location: "L618"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/_extract_with_adaptive_retry
---

# No retry when finish_reason='stop' — single call, result passes through.

## Connections
- [[test_adaptive_retry_returns_directly_when_not_truncated()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/_extract_with_adaptive_retry