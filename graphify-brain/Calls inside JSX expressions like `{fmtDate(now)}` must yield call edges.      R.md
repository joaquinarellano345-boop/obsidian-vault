---
source_file: "tests/test_extract.py"
type: "rationale"
community: "extract_js"
location: "L1403"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/extract_js
---

# Calls inside JSX expressions like `{fmtDate(now)}` must yield call edges.      R

## Connections
- [[test_extract_tsx_jsx_expression_calls_resolve()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/extract_js