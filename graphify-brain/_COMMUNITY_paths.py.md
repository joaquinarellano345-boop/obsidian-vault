---
type: community
cohesion: 0.13
members: 23
---

# paths.py

**Cohesion:** 0.13 - loosely connected
**Members:** 23 nodes

## Members
- [[Atomically replace ``path`` with content written by ``write_fn(f)``.      Writes]] - rationale - graphify/paths.py
- [[Atomically write ``obj`` as JSON to ``path``, streaming the encode into the]] - rationale - graphify/paths.py
- [[Atomically write ``text`` (UTF-8) to ``path``. See func`_atomic_replace`.]] - rationale - graphify/paths.py
- [[NFC-normalize a path string.      macOS (HFS+APFS) reports filenames in NFD whi]] - rationale - graphify/paths.py
- [[On Windows os.replace raises PermissionError when the destination is     briefly]] - rationale - tests/test_atomic_writes.py
- [[Single source of truth for the graphify output-directory name.  The output direc]] - rationale - graphify/paths.py
- [[Tests for atomic JSON writes (graph.json  manifest.json).  A crash, kill, or di]] - rationale - tests/test_atomic_writes.py
- [[_atomic_replace()]] - code - graphify/paths.py
- [[nfc()]] - code - graphify/paths.py
- [[paths.py]] - code - graphify/paths.py
- [[test_atomic_writes.py]] - code - tests/test_atomic_writes.py
- [[test_save_manifest_writes_atomically()]] - code - tests/test_atomic_writes.py
- [[test_to_json_writes_atomically_no_tmp_leftover()]] - code - tests/test_atomic_writes.py
- [[test_write_json_atomic_ensure_ascii_false_preserves_utf8()]] - code - tests/test_atomic_writes.py
- [[test_write_json_atomic_roundtrip()]] - code - tests/test_atomic_writes.py
- [[test_write_text_atomic_new_file_respects_umask()]] - code - tests/test_atomic_writes.py
- [[test_write_text_atomic_preserves_existing_mode()]] - code - tests/test_atomic_writes.py
- [[test_write_text_atomic_preserves_existing_on_failure()]] - code - tests/test_atomic_writes.py
- [[test_write_text_atomic_windows_permission_fallback()]] - code - tests/test_atomic_writes.py
- [[test_write_text_atomic_writes_and_leaves_no_tmp()]] - code - tests/test_atomic_writes.py
- [[test_write_text_atomic_writes_through_symlink()]] - code - tests/test_atomic_writes.py
- [[write_json_atomic()]] - code - graphify/paths.py
- [[write_text_atomic()]] - code - graphify/paths.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/pathspy
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_cli.py]]
- 5 edges to [[_COMMUNITY_detect.py]]
- 4 edges to [[_COMMUNITY_disambiguate_ambiguous_candidates]]
- 3 edges to [[_COMMUNITY_to_json]]
- 2 edges to [[_COMMUNITY_graphify__main__.py]]
- 1 edge to [[_COMMUNITY_test_benchmark.py]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_test_cache.py]]
- 1 edge to [[_COMMUNITY_callflow_html.py]]
- 1 edge to [[_COMMUNITY__stale_graph_sources]]
- 1 edge to [[_COMMUNITY_export.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_default_graph_json]]
- 1 edge to [[_COMMUNITY_prs.py]]
- 1 edge to [[_COMMUNITY_reflect.py]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY_symbol_resolution.py]]
- 1 edge to [[_COMMUNITY_test_transcribe.py]]
- 1 edge to [[_COMMUNITY__rebuild_code]]

## Top bridge nodes
- [[paths.py]] - degree 30, connects to 17 communities
- [[write_json_atomic()]] - degree 16, connects to 4 communities
- [[test_atomic_writes.py]] - degree 16, connects to 2 communities
- [[nfc()]] - degree 4, connects to 2 communities
- [[write_text_atomic()]] - degree 12, connects to 1 community