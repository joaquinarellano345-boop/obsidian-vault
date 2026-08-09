---
source_file: "tests/test_extract.py"
type: "rationale"
community: "extract_bash"
location: "L1602"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/extract_bash
---

# `source "${DIR}/lib/x.sh"` (the `dirname "${BASH_SOURCE[0]}"` idiom) must     re

## Connections
- [[test_extract_bash_source_via_variable_path_resolves_to_real_file()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/extract_bash