---
type: community
cohesion: 1.00
members: 2
---

# test_dedup_gapfill_is_order_independent_with_multiple_losers

**Cohesion:** 1.00 - tightly connected
**Members:** 2 nodes

## Members
- [[(fix A) With 3+ same-ID same-source records, the merged attributes must not]] - rationale - tests/test_dedup.py
- [[test_dedup_gapfill_is_order_independent_with_multiple_losers()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_dedup_gapfill_is_order_independent_with_multiple_losers
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_deduplicate_entities]]
- 1 edge to [[_COMMUNITY_test_dedup.py]]

## Top bridge nodes
- [[test_dedup_gapfill_is_order_independent_with_multiple_losers()]] - degree 3, connects to 2 communities