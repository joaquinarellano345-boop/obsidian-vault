---
type: community
cohesion: 1.00
members: 2
---

# _doc_community

**Cohesion:** 1.00 - tightly connected
**Members:** 2 nodes

## Members
- [[The community a doc belongs to the plurality community of its source nodes.]] - rationale - graphify/reflect.py
- [[_doc_community()]] - code - graphify/reflect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_doc_community
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_reflect.py]]
- 1 edge to [[_COMMUNITY_test_reflect.py]]

## Top bridge nodes
- [[_doc_community()]] - degree 3, connects to 2 communities