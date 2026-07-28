---
source_file: "tests/test_watch.py"
type: "rationale"
community: "test_watch.py"
location: "L751"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/test_watchpy
---

# An incremental rebuild must not treat ./foo.py as a deleted live source.

## Connections
- [[test_rebuild_code_normalizes_preserved_source_paths()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/test_watchpy