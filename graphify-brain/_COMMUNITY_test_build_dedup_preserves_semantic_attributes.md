---
type: community
cohesion: 1.00
members: 2
---

# test_build_dedup_preserves_semantic_attributes

**Cohesion:** 1.00 - tightly connected
**Members:** 2 nodes

## Members
- [[The default build path must not discard semantic enrichment (2091).]] - rationale - tests/test_dedup.py
- [[test_build_dedup_preserves_semantic_attributes()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_build_dedup_preserves_semantic_attributes
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_deduplicate_entities]]

## Top bridge nodes
- [[test_build_dedup_preserves_semantic_attributes()]] - degree 3, connects to 2 communities