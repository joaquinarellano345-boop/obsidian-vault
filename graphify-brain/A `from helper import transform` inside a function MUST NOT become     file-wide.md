---
source_file: "tests/test_symbol_resolution.py"
type: "rationale"
community: "parse_python_import_aliases"
location: "L639"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/parse_python_import_aliases
---

# A `from helper import transform` inside a function MUST NOT become     file-wide

## Connections
- [[test_parse_python_import_aliases_skips_function_local_imports()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/parse_python_import_aliases