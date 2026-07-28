---
type: community
cohesion: 0.25
members: 8
---

# iter_raw_calls

**Cohesion:** 0.25 - loosely connected
**Members:** 8 nodes

## Members
- [[A non-dict per_file entry (e.g. junk fragment) must be silently skipped.]] - rationale - tests/test_symbol_resolution.py
- [[Items inside `raw_calls` list that aren't dicts must be dropped.]] - rationale - tests/test_symbol_resolution.py
- [[Return raw calls from all per-file extraction fragments.      Parameter is ``Seq]] - rationale - graphify/symbol_resolution.py
- [[`raw_calls` that isn't a list must yield empty.]] - rationale - tests/test_symbol_resolution.py
- [[iter_raw_calls()]] - code - graphify/symbol_resolution.py
- [[test_iter_raw_calls_drops_non_dict_items_in_list()]] - code - tests/test_symbol_resolution.py
- [[test_iter_raw_calls_skips_non_dict_per_file_entries()]] - code - tests/test_symbol_resolution.py
- [[test_iter_raw_calls_skips_non_list_raw_calls()]] - code - tests/test_symbol_resolution.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/iter_raw_calls
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_test_symbol_resolution.py]]
- 1 edge to [[_COMMUNITY_symbol_resolution.py]]
- 1 edge to [[_COMMUNITY_build_label_index]]
- 1 edge to [[_COMMUNITY_resolve_cross_file_raw_calls]]

## Top bridge nodes
- [[iter_raw_calls()]] - degree 8, connects to 4 communities
- [[test_iter_raw_calls_drops_non_dict_items_in_list()]] - degree 3, connects to 1 community
- [[test_iter_raw_calls_skips_non_dict_per_file_entries()]] - degree 3, connects to 1 community
- [[test_iter_raw_calls_skips_non_list_raw_calls()]] - degree 3, connects to 1 community