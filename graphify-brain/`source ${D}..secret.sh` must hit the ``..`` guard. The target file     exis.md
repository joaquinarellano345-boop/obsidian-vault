---
source_file: "tests/test_extract.py"
type: "rationale"
community: "extract_bash"
location: "L2156"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/extract_bash
---

# `source "${D}/../secret.sh"` must hit the ``..`` guard. The target file     exis

## Connections
- [[test_extract_bash_source_suffix_guard_rejects_traversal()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/extract_bash