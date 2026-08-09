---
type: community
cohesion: 0.13
members: 15
---

# resolve_python_import_guided_calls

**Cohesion:** 0.13 - loosely connected
**Members:** 15 nodes

## Members
- [[A None per_file slot is treated as empty fragment (no crash, no edges).]] - rationale - tests/test_symbol_resolution.py
- [[A non-dict per_file slot (e.g. a string) must not raise AttributeError.]] - rationale - tests/test_symbol_resolution.py
- [[Edge metadata produced by the import-guided resolver must pass through     sanit]] - rationale - tests/test_symbol_resolution.py
- [[Python import-guided resolver also tolerates malformed raw_calls.]] - rationale - tests/test_symbol_resolution.py
- [[Resolve raw Python calls using explicit import evidence.      Only ``from module]] - rationale - graphify/symbol_resolution.py
- [[Strong regression for cycle-2.7-Codex-v2 monkeypatch the alias parser     so t]] - rationale - tests/test_symbol_resolution.py
- [[per_file shorter than paths must not raise IndexError.]] - rationale - tests/test_symbol_resolution.py
- [[resolve_python_import_guided_calls()]] - code - graphify/symbol_resolution.py
- [[test_resolve_python_import_guided_calls_emits_extracted_edge()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_metadata_is_sanitized()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_metadata_sanitizes_hostile_alias()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_non_dict_per_file_slot()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_per_file_none_slot()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_per_file_shorter_than_paths()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_survives_malformed_raw_calls()]] - code - tests/test_symbol_resolution.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/resolve_python_import_guided_calls
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_test_symbol_resolution.py]]
- 4 edges to [[_COMMUNITY_symbol_resolution.py]]
- 4 edges to [[_COMMUNITY_resolve_bash_source_edges]]
- 2 edges to [[_COMMUNITY_parse_python_import_aliases]]
- 1 edge to [[_COMMUNITY_test_security.py]]

## Top bridge nodes
- [[resolve_python_import_guided_calls()]] - degree 17, connects to 5 communities
- [[test_resolve_python_import_guided_calls_metadata_is_sanitized()]] - degree 4, connects to 2 communities
- [[test_resolve_python_import_guided_calls_metadata_sanitizes_hostile_alias()]] - degree 4, connects to 2 communities
- [[test_resolve_python_import_guided_calls_emits_extracted_edge()]] - degree 3, connects to 2 communities
- [[test_resolve_python_import_guided_calls_non_dict_per_file_slot()]] - degree 3, connects to 1 community