---
type: community
cohesion: 0.18
members: 11
---

# _defines_id

**Cohesion:** 0.18 - loosely connected
**Members:** 11 nodes

## Members
- [[A file-level semantic node whose id is exactly the slugified path (no     `_enti]] - rationale - tests/test_dedup.py
- [[A total order for choosing the survivor of an ID collision, independent of     t]] - rationale - graphify/dedup.py
- [[Report an ID collision in proportion to what dropping the loser actually costs.]] - rationale - graphify/dedup.py
- [[The ID prefixes a node extracted from ``source_file`` may legitimately mint.]] - rationale - graphify/dedup.py
- [[True when the node's own source_file is the file its ID encodes.      A doc that]] - rationale - graphify/dedup.py
- [[_collision_rank()]] - code - graphify/dedup.py
- [[_defines_id()]] - code - graphify/dedup.py
- [[_id_prefixes()]] - code - graphify/dedup.py
- [[_report_id_collision()]] - code - graphify/dedup.py
- [[test_bare_file_node_defines_its_own_id()]] - code - tests/test_dedup.py
- [[test_defines_id_helper()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_defines_id
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_deduplicate_entities]]
- 4 edges to [[_COMMUNITY_dedup.py]]
- 1 edge to [[_COMMUNITY__norm]]

## Top bridge nodes
- [[_report_id_collision()]] - degree 5, connects to 3 communities
- [[_defines_id()]] - degree 8, connects to 2 communities
- [[_collision_rank()]] - degree 4, connects to 2 communities
- [[_id_prefixes()]] - degree 3, connects to 1 community
- [[test_bare_file_node_defines_its_own_id()]] - degree 3, connects to 1 community