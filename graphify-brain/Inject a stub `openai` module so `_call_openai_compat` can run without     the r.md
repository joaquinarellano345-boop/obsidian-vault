---
source_file: "tests/test_llm_backends.py"
type: "rationale"
community: "_call_openai_compat"
location: "L385"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/_call_openai_compat
---

# Inject a stub `openai` module so `_call_openai_compat` can run without     the r

## Connections
- [[_install_fake_openai()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/_call_openai_compat