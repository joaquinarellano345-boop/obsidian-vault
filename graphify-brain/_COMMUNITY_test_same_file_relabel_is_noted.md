---
type: community
cohesion: 1.00
members: 2
---

# test_same_file_relabel_is_noted

**Cohesion:** 1.00 - tightly connected
**Members:** 2 nodes

## Members
- [[Two labels for one ID from one file the loser's label is discarded, which is]] - rationale - tests/test_dedup.py
- [[test_same_file_relabel_is_noted()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_same_file_relabel_is_noted
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_deduplicate_entities]]
- 1 edge to [[_COMMUNITY_test_dedup.py]]

## Top bridge nodes
- [[test_same_file_relabel_is_noted()]] - degree 3, connects to 2 communities