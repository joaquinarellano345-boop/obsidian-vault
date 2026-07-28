---
source_file: "tests/test_extract.py"
type: "rationale"
community: "extract_js"
location: "L2558"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/extract_js
---

# export { localVar } without 'from' should NOT create re_exports edges.

## Connections
- [[test_pure_export_no_from_not_treated_as_reexport()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/extract_js