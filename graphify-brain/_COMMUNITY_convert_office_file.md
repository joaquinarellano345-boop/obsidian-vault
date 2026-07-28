---
type: community
cohesion: 0.14
members: 20
---

# convert_office_file

**Cohesion:** 0.14 - loosely connected
**Members:** 20 nodes

## Members
- [[1649 — a modified .docx.xlsx must re-enter --update.  detect_incremental track]] - rationale - tests/test_office_incremental.py
- [[2059 the sidecar name must depend on the scan-root-RELATIVE path, not the]] - rationale - tests/test_detect.py
- [[A second conversion of an unchanged source must not rewrite the sidecar,     so]] - rationale - tests/test_detect.py
- [[A source outside the scan root (--include, custom layouts) falls back to the]] - rationale - tests/test_detect.py
- [[Convert a .docx or .xlsx to a markdown sidecar in out_dir.      Returns the path]] - rationale - graphify/detect.py
- [[Path_85]] - code
- [[Set path's mtime relative to now so ordering is deterministic.]] - rationale - tests/test_office_incremental.py
- [[The sidecar name must be identical whether the source path arrives in     NFC or]] - rationale - tests/test_detect.py
- [[Two same-stem Office files in different subdirs must still get distinct     side]] - rationale - tests/test_detect.py
- [[_bump_mtime()]] - code - tests/test_office_incremental.py
- [[_make_docx()]] - code - tests/test_office_incremental.py
- [[convert_office_file()]] - code - graphify/detect.py
- [[test_convert_office_file_does_not_rewrite_existing_sidecar()]] - code - tests/test_detect.py
- [[test_convert_office_file_hash_disambiguates_same_stem()]] - code - tests/test_detect.py
- [[test_convert_office_file_hash_stable_across_nfc_nfd()]] - code - tests/test_detect.py
- [[test_convert_office_file_outside_root_falls_back()]] - code - tests/test_detect.py
- [[test_convert_office_file_sidecar_name_stable_across_checkouts()]] - code - tests/test_detect.py
- [[test_modified_docx_reconverts_sidecar()]] - code - tests/test_office_incremental.py
- [[test_office_incremental.py]] - code - tests/test_office_incremental.py
- [[test_unchanged_docx_sidecar_not_rewritten()]] - code - tests/test_office_incremental.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/convert_office_file
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_detect.py]]
- 6 edges to [[_COMMUNITY_test_detect.py]]

## Top bridge nodes
- [[convert_office_file()]] - degree 14, connects to 2 communities
- [[test_office_incremental.py]] - degree 6, connects to 1 community
- [[test_convert_office_file_does_not_rewrite_existing_sidecar()]] - degree 3, connects to 1 community
- [[test_convert_office_file_hash_disambiguates_same_stem()]] - degree 3, connects to 1 community
- [[test_convert_office_file_hash_stable_across_nfc_nfd()]] - degree 3, connects to 1 community