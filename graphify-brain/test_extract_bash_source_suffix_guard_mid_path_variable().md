---
source_file: "tests/test_extract.py"
type: "code"
community: "test_extract.py"
location: "L2122"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/test_extractpy
---

# test_extract_bash_source_suffix_guard_mid_path_variable()

## Connections
- [[`source lib${X}.sh` keeps an expansion in the suffix, so the     ``$``-in-suf]] - `rationale_for` [EXTRACTED]
- [[extract_bash()]] - `calls` [INFERRED]
- [[test_extract.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/test_extractpy