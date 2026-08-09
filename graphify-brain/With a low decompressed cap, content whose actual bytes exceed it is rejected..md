---
source_file: "tests/test_office_limits.py"
type: "rationale"
community: "detect.py"
location: "L65"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/detectpy
---

# With a low decompressed cap, content whose actual bytes exceed it is rejected.

## Connections
- [[test_streaming_ceiling_rejects_oversized_actual()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/detectpy