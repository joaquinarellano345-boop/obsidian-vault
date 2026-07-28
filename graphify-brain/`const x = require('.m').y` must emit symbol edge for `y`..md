---
source_file: "tests/test_extract.py"
type: "rationale"
community: "extract_js"
location: "L766"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/extract_js
---

# `const x = require('./m').y` must emit symbol edge for `y`.

## Connections
- [[test_extract_js_member_require_emits_property_symbol()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/extract_js