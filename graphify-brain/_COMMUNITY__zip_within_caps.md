---
type: community
cohesion: 0.14
members: 20
---

# _zip_within_caps

**Cohesion:** 0.14 - loosely connected
**Members:** 20 nodes

## Members
- [[A PDF larger than the raw cap is skipped before pypdf opens it.]] - rationale - tests/test_office_limits.py
- [[A normal multi-member office zip passes the streaming-ceiling pass.]] - rationale - tests/test_office_limits.py
- [[A tiny file that expands far past the ratio threshold is rejected.]] - rationale - tests/test_office_limits.py
- [[Reject a zip-based office file that is a likely zipXML bomb.      Two layers, b]] - rationale - graphify/detect.py
- [[Resource-cap guards for parsing untrusted officePDF files (F2).  .docx.xlsx ar]] - rationale - tests/test_office_limits.py
- [[The live converters bail out (return ) on a bomb before parsing.]] - rationale - tests/test_office_limits.py
- [[True if path exists and its on-disk size is within cap.]] - rationale - graphify/detect.py
- [[With a low decompressed cap, content whose actual bytes exceed it is rejected.]] - rationale - tests/test_office_limits.py
- [[_file_within_size_cap()]] - code - graphify/detect.py
- [[_write_zip()]] - code - tests/test_office_limits.py
- [[_zip_within_caps()]] - code - graphify/detect.py
- [[test_converters_return_empty_for_bomb()]] - code - tests/test_office_limits.py
- [[test_file_within_size_cap()]] - code - tests/test_office_limits.py
- [[test_legit_multi_member_passes_streaming()]] - code - tests/test_office_limits.py
- [[test_legit_zip_passes()]] - code - tests/test_office_limits.py
- [[test_non_zip_rejected()]] - code - tests/test_office_limits.py
- [[test_office_limits.py]] - code - tests/test_office_limits.py
- [[test_pdf_over_cap_returns_empty()]] - code - tests/test_office_limits.py
- [[test_streaming_ceiling_rejects_oversized_actual()]] - code - tests/test_office_limits.py
- [[test_zip_ratio_bomb_rejected()]] - code - tests/test_office_limits.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_zip_within_caps
SORT file.name ASC
```

## Connections to other communities
- 11 edges to [[_COMMUNITY_detect.py]]
- 2 edges to [[_COMMUNITY_test_detect.py]]

## Top bridge nodes
- [[test_pdf_over_cap_returns_empty()]] - degree 4, connects to 2 communities
- [[_zip_within_caps()]] - degree 11, connects to 1 community
- [[test_office_limits.py]] - degree 11, connects to 1 community
- [[_file_within_size_cap()]] - degree 6, connects to 1 community
- [[test_converters_return_empty_for_bomb()]] - degree 5, connects to 1 community