---
type: community
cohesion: 0.15
members: 20
---

# test_multilang.py

**Cohesion:** 0.15 - loosely connected
**Members:** 20 nodes

## Members
- [[Scoped calls (Typemethod) and blocklisted names must not produce     INFERRED]] - rationale - tests/test_multilang.py
- [[Tests for multi-language AST extraction JSTS, Go, Rust, SQL.]] - rationale - tests/test_multilang.py
- [[_call_pairs()]] - code - tests/test_multilang.py
- [[_edges_with_relation()_1]] - code - tests/test_multilang.py
- [[test_cache_hit_returns_same_result()]] - code - tests/test_multilang.py
- [[test_cache_miss_after_file_change()]] - code - tests/test_multilang.py
- [[test_extract_dispatches_all_languages()]] - code - tests/test_multilang.py
- [[test_go_call_edges_have_call_context()]] - code - tests/test_multilang.py
- [[test_go_emits_calls()]] - code - tests/test_multilang.py
- [[test_go_import_edges_have_import_context()]] - code - tests/test_multilang.py
- [[test_multilang.py]] - code - tests/test_multilang.py
- [[test_rust_call_edges_have_call_context()]] - code - tests/test_multilang.py
- [[test_rust_emits_calls()]] - code - tests/test_multilang.py
- [[test_rust_import_edges_have_import_context()]] - code - tests/test_multilang.py
- [[test_rust_no_cross_crate_spurious_edges()]] - code - tests/test_multilang.py
- [[test_ts_call_edges_have_call_context()]] - code - tests/test_multilang.py
- [[test_ts_calls_are_extracted()]] - code - tests/test_multilang.py
- [[test_ts_emits_calls()]] - code - tests/test_multilang.py
- [[test_ts_import_edges_have_import_context()]] - code - tests/test_multilang.py
- [[test_ts_no_dangling_edges()]] - code - tests/test_multilang.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_multilangpy
SORT file.name ASC
```

## Connections to other communities
- 16 edges to [[_COMMUNITY_extract_rust]]
- 14 edges to [[_COMMUNITY__extract_sql_or_skip]]
- 10 edges to [[_COMMUNITY_extract_go]]
- 8 edges to [[_COMMUNITY__labels_1]]
- 6 edges to [[_COMMUNITY_extract_js]]
- 5 edges to [[_COMMUNITY_extract]]
- 1 edge to [[_COMMUNITY_extract.py]]

## Top bridge nodes
- [[test_multilang.py]] - degree 63, connects to 7 communities
- [[test_go_call_edges_have_call_context()]] - degree 3, connects to 1 community
- [[test_go_emits_calls()]] - degree 3, connects to 1 community
- [[test_go_import_edges_have_import_context()]] - degree 3, connects to 1 community
- [[test_rust_call_edges_have_call_context()]] - degree 3, connects to 1 community