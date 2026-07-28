---
type: community
cohesion: 1.00
members: 2
---

# test_numeric_tokens_differ_helper

**Cohesion:** 1.00 - tightly connected
**Members:** 2 nodes

## Members
- [[_numeric_tokens_differ compares digit runs as zero-padding-insensitive     multi]] - rationale - tests/test_dedup.py
- [[test_numeric_tokens_differ_helper()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_numeric_tokens_differ_helper
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_deduplicate_entities]]
- 1 edge to [[_COMMUNITY_test_dedup.py]]

## Top bridge nodes
- [[test_numeric_tokens_differ_helper()]] - degree 3, connects to 2 communities