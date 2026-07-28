---
source_file: "tests/test_languages.py"
type: "code"
community: "extract_fortran"
location: "L1677"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/extract_fortran
---

# test_fortran_finds_function_call()

## Connections
- [[`y = f(x)` function invocations must emit a calls edge.      Function calls are]] - `rationale_for` [EXTRACTED]
- [[extract_fortran()]] - `calls` [INFERRED]
- [[test_languages.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/extract_fortran