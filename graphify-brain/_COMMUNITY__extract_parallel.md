---
type: community
cohesion: 0.25
members: 8
---

# _extract_parallel

**Cohesion:** 0.25 - loosely connected
**Members:** 8 nodes

## Members
- [[2173 a resolved worker count of 1 must not spawn a ProcessPoolExecutor.      T]] - rationale - tests/test_extract.py
- [[Extract uncached files in parallel using ProcessPoolExecutor.      Returns True]] - rationale - graphify/extract.py
- [[Guard the 2173 skip 1 worker must still take the pool path.]] - rationale - tests/test_extract.py
- [[_extract_parallel must catch BrokenProcessPool internally and return False.]] - rationale - tests/test_extract.py
- [[_extract_parallel()]] - code - graphify/extract.py
- [[test_extract_parallel_returns_false_on_broken_pool()]] - code - tests/test_extract.py
- [[test_extract_parallel_skips_pool_when_max_workers_is_one()]] - code - tests/test_extract.py
- [[test_extract_parallel_still_spawns_pool_for_multiple_workers()]] - code - tests/test_extract.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_extract_parallel
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_test_extract.py]]
- 2 edges to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_extract]]

## Top bridge nodes
- [[_extract_parallel()]] - degree 8, connects to 3 communities
- [[test_extract_parallel_returns_false_on_broken_pool()]] - degree 3, connects to 1 community
- [[test_extract_parallel_skips_pool_when_max_workers_is_one()]] - degree 3, connects to 1 community
- [[test_extract_parallel_still_spawns_pool_for_multiple_workers()]] - degree 3, connects to 1 community