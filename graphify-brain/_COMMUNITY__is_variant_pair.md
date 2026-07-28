---
type: community
cohesion: 0.33
members: 6
---

# _is_variant_pair

**Cohesion:** 0.33 - loosely connected
**Members:** 6 nodes

## Members
- [[Genuine same-length single-char typos should still merge (878 non-regression).]] - rationale - tests/test_dedup.py
- [[True if a and b are sibling modelSKU variants (same stem, different suffix).]] - rationale - graphify/dedup.py
- [[_is_variant_pair correctly identifies chip-model variant pairs (878).]] - rationale - tests/test_dedup.py
- [[_is_variant_pair()]] - code - graphify/dedup.py
- [[test_dedup_still_merges_real_typos()]] - code - tests/test_dedup.py
- [[test_variant_pair_helper()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_is_variant_pair
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_deduplicate_entities]]
- 3 edges to [[_COMMUNITY_test_dedup.py]]
- 1 edge to [[_COMMUNITY_dedup.py]]

## Top bridge nodes
- [[_is_variant_pair()]] - degree 7, connects to 3 communities
- [[test_dedup_still_merges_real_typos()]] - degree 4, connects to 2 communities
- [[test_variant_pair_helper()]] - degree 3, connects to 1 community