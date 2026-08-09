---
type: community
cohesion: 0.25
members: 8
---

# _labels

**Cohesion:** 0.25 - loosely connected
**Members:** 8 nodes

## Members
- [[_labels()_5]] - code - tests/test_multilang.py
- [[test_go_finds_struct()]] - code - tests/test_multilang.py
- [[test_rust_finds_function()]] - code - tests/test_multilang.py
- [[test_rust_finds_impl_methods()]] - code - tests/test_multilang.py
- [[test_rust_finds_struct()]] - code - tests/test_multilang.py
- [[test_ts_finds_class()]] - code - tests/test_multilang.py
- [[test_ts_finds_function()]] - code - tests/test_multilang.py
- [[test_ts_finds_methods()]] - code - tests/test_multilang.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_labels
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_test_multilang.py]]
- 3 edges to [[_COMMUNITY_extract_js]]
- 3 edges to [[_COMMUNITY_extract_go]]
- 3 edges to [[_COMMUNITY_extract_rust]]

## Top bridge nodes
- [[_labels()_5]] - degree 10, connects to 2 communities
- [[test_go_finds_struct()]] - degree 3, connects to 2 communities
- [[test_rust_finds_function()]] - degree 3, connects to 2 communities
- [[test_rust_finds_impl_methods()]] - degree 3, connects to 2 communities
- [[test_rust_finds_struct()]] - degree 3, connects to 2 communities