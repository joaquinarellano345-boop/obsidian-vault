---
source_file: "tests/test_extract.py"
type: "rationale"
community: "extract_bash"
location: "L1924"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/extract_bash
---

# When 'source' is a user-defined function, 'source ./file.sh' must emit a     cal

## Connections
- [[test_extract_bash_source_user_defined_emits_calls_not_imports_from()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/extract_bash