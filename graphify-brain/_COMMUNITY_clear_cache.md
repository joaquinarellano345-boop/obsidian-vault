---
type: community
cohesion: 0.22
members: 14
---

# clear_cache

**Cohesion:** 0.22 - loosely connected
**Members:** 14 nodes

## Members
- [[Count files by extension.]] - rationale - tests/bench_extract.py
- [[Delete all cache entries (ast, semantic, semantic-deep, and legacy     flat e]] - rationale - graphify/cache.py
- [[Path_58]] - code
- [[Run extraction, return (elapsed_seconds, node_count, edge_count).]] - rationale - tests/bench_extract.py
- [[_count_by_ext()]] - code - tests/bench_extract.py
- [[_format_languages()]] - code - tests/bench_extract.py
- [[_run_extraction()]] - code - tests/bench_extract.py
- [[bench_extract.py]] - code - tests/bench_extract.py
- [[clear_cache removes all .json files from graphify-outcache (all subdirs).]] - rationale - tests/test_cache.py
- [[clear_cache sweeps cachesemantic-deep alongside semantic and ast.]] - rationale - tests/test_cache.py
- [[clear_cache()]] - code - graphify/cache.py
- [[main()_2]] - code - tests/bench_extract.py
- [[test_clear_cache()]] - code - tests/test_cache.py
- [[test_clear_cache_removes_deep_namespace()]] - code - tests/test_cache.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/clear_cache
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_test_cache.py]]
- 2 edges to [[_COMMUNITY_extract]]
- 2 edges to [[_COMMUNITY_test_extract.py]]
- 1 edge to [[_COMMUNITY_save_semantic_cache]]
- 1 edge to [[_COMMUNITY_extract.py]]

## Top bridge nodes
- [[bench_extract.py]] - degree 9, connects to 4 communities
- [[test_clear_cache_removes_deep_namespace()]] - degree 4, connects to 2 communities
- [[clear_cache()]] - degree 10, connects to 1 community
- [[main()_2]] - degree 7, connects to 1 community
- [[_run_extraction()]] - degree 6, connects to 1 community