---
source_file: "tests/test_extract.py"
type: "code"
community: "test_extract.py"
location: "L1601"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/test_extractpy
---

# test_extract_bash_source_via_variable_path_resolves_to_real_file()

## Connections
- [[`source ${DIR}libx.sh` (the `dirname ${BASH_SOURCE0}` idiom) must     re]] - `rationale_for` [EXTRACTED]
- [[extract_bash()]] - `calls` [INFERRED]
- [[test_extract.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/test_extractpy