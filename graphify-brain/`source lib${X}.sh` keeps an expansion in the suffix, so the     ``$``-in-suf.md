---
source_file: "tests/test_extract.py"
type: "rationale"
community: "extract_bash"
location: "L2123"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/extract_bash
---

# `source "lib/${X}.sh"` keeps an expansion in the suffix, so the     ``$``-in-suf

## Connections
- [[test_extract_bash_source_suffix_guard_mid_path_variable()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/extract_bash