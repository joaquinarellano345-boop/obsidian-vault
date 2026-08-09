---
source_file: "graphify/symbol_resolution.py"
type: "code"
community: "parse_python_import_aliases"
location: "L206"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/parse_python_import_aliases
---

# find_unique_python_symbol()

## Connections
- [[ImportedSymbol]] - `references` [EXTRACTED]
- [[Resolve one imported symbol to exactly one Graphify node id.]] - `rationale_for` [EXTRACTED]
- [[resolve_python_import_guided_calls()]] - `calls` [EXTRACTED]
- [[symbol_resolution.py]] - `contains` [EXTRACTED]
- [[test_find_unique_python_symbol_returns_none_when_ambiguous()]] - `calls` [EXTRACTED]
- [[test_symbol_resolution.py]] - `imports` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/parse_python_import_aliases