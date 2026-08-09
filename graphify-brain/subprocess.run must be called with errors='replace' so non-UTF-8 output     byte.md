---
source_file: "tests/test_llm_backends.py"
type: "rationale"
community: "_call_claude_cli"
location: "L1026"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/_call_claude_cli
---

# subprocess.run must be called with errors='replace' so non-UTF-8 output     byte

## Connections
- [[test_call_claude_cli_passes_errors_replace_to_subprocess()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/_call_claude_cli