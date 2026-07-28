---
source_file: "tests/test_extract.py"
type: "rationale"
community: "extract_js"
location: "L742"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/extract_js
---

# `const { foo } = require('./mod')` must emit imports_from to the resolved module

## Connections
- [[test_extract_js_destructured_require_imports_from()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/extract_js