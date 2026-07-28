---
source_file: "tests/test_extract.py"
type: "rationale"
community: "extract_js"
location: "L820"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/extract_js
---

# `exports.X = fn` and `module.exports.X = fn` must produce function nodes.

## Connections
- [[test_extract_js_commonjs_exports_assignment()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/extract_js