---
source_file: "tests/test_languages.py"
type: "rationale"
community: "extract_objc"
location: "L1182"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/extract_objc
---

# `@protocol Derived <Base>` must emit an implements edge Derived->Base.     Proto

## Connections
- [[test_objc_protocol_adopts_protocol()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/extract_objc