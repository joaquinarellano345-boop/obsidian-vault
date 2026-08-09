---
type: community
cohesion: 1.00
members: 2
---

# test_build_calls_dedup

**Cohesion:** 1.00 - tightly connected
**Members:** 2 nodes

## Members
- [[build() should deduplicate near-identical nodes across extractions.]] - rationale - tests/test_dedup.py
- [[test_build_calls_dedup()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_build_calls_dedup
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_deduplicate_entities]]

## Top bridge nodes
- [[test_build_calls_dedup()]] - degree 3, connects to 2 communities