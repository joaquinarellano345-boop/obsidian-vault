---
source_file: "tests/test_charmap_encoding.py"
type: "rationale"
community: "TestSubprocessEncoding"
location: "L81"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/TestSubprocessEncoding
---

# text=True without encoding= relies on the locale codec (cp1252 on Windows).

## Connections
- [[.test_subprocess_does_not_use_text_true_without_encoding()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/TestSubprocessEncoding