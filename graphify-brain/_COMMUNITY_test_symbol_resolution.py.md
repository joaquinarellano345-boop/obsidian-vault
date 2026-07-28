---
type: community
cohesion: 0.12
members: 27
---

# test_symbol_resolution.py

**Cohesion:** 0.12 - loosely connected
**Members:** 27 nodes

## Members
- [[A None per_file slot is treated as empty fragment (no crash, no edges).]] - rationale - tests/test_symbol_resolution.py
- [[A non-dict per_file slot (e.g. a string) must not raise AttributeError.]] - rationale - tests/test_symbol_resolution.py
- [[Edge metadata produced by the import-guided resolver must pass through     sanit]] - rationale - tests/test_symbol_resolution.py
- [[Non-bash raw_calls inside sourced-file per_file entries are ignored.]] - rationale - tests/test_symbol_resolution.py
- [[Path_103]] - code
- [[Python import-guided resolver also tolerates malformed raw_calls.]] - rationale - tests/test_symbol_resolution.py
- [[Resolve raw Python calls using explicit import evidence.      Only ``from module]] - rationale - graphify/symbol_resolution.py
- [[Strong regression for cycle-2.7-Codex-v2 monkeypatch the alias parser     so t]] - rationale - tests/test_symbol_resolution.py
- [[Tests for graphify.symbol_resolution.]] - rationale - tests/test_symbol_resolution.py
- [[When a callee function is defined in multiple sourced files, skip it.]] - rationale - tests/test_symbol_resolution.py
- [[per_file shorter than paths must not raise IndexError.]] - rationale - tests/test_symbol_resolution.py
- [[resolve_python_import_guided_calls()]] - code - graphify/symbol_resolution.py
- [[test_bash_call_resolver_emits_call_edges_from_sourced_files()]] - code - tests/test_symbol_resolution.py
- [[test_bash_call_resolver_emits_source_edges()]] - code - tests/test_symbol_resolution.py
- [[test_bash_call_resolver_skips_ambiguous_multiple_candidates()]] - code - tests/test_symbol_resolution.py
- [[test_bash_call_resolver_skips_existing_pair()]] - code - tests/test_symbol_resolution.py
- [[test_bash_call_resolver_skips_non_bash_raw_calls()]] - code - tests/test_symbol_resolution.py
- [[test_find_unique_python_symbol_returns_none_when_ambiguous()]] - code - tests/test_symbol_resolution.py
- [[test_parse_python_import_aliases_supports_from_import_alias()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_emits_extracted_edge()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_metadata_is_sanitized()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_metadata_sanitizes_hostile_alias()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_non_dict_per_file_slot()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_per_file_none_slot()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_per_file_shorter_than_paths()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_python_import_guided_calls_survives_malformed_raw_calls()]] - code - tests/test_symbol_resolution.py
- [[test_symbol_resolution.py]] - code - tests/test_symbol_resolution.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_symbol_resolutionpy
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_resolve_bash_source_edges]]
- 13 edges to [[_COMMUNITY_build_label_index]]
- 11 edges to [[_COMMUNITY_symbol_resolution.py]]
- 9 edges to [[_COMMUNITY_resolve_cross_file_raw_calls]]
- 4 edges to [[_COMMUNITY_iter_raw_calls]]
- 3 edges to [[_COMMUNITY__bash_make_id]]
- 1 edge to [[_COMMUNITY_sanitize_metadata]]

## Top bridge nodes
- [[test_symbol_resolution.py]] - degree 55, connects to 6 communities
- [[resolve_python_import_guided_calls()]] - degree 17, connects to 4 communities
- [[test_bash_call_resolver_skips_ambiguous_multiple_candidates()]] - degree 4, connects to 1 community
- [[test_bash_call_resolver_skips_non_bash_raw_calls()]] - degree 4, connects to 1 community
- [[test_find_unique_python_symbol_returns_none_when_ambiguous()]] - degree 4, connects to 1 community