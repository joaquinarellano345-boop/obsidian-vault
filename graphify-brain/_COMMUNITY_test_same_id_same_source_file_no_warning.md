---
type: community
cohesion: 1.00
members: 2
---

# test_same_id_same_source_file_no_warning

**Cohesion:** 1.00 - tightly connected
**Members:** 2 nodes

## Members
- [[When two nodes share both ID and source_file (same-file dedup),     no collision]] - rationale - tests/test_dedup.py
- [[test_same_id_same_source_file_no_warning()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_same_id_same_source_file_no_warning
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_deduplicate_entities]]
- 1 edge to [[_COMMUNITY_test_dedup.py]]

## Top bridge nodes
- [[test_same_id_same_source_file_no_warning()]] - degree 3, connects to 2 communities