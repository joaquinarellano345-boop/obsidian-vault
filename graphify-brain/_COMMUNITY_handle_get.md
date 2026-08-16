---
type: community
cohesion: 1.00
members: 2
---

# handle_get

**Cohesion:** 1.00 - tightly connected
**Members:** 2 nodes

## Members
- [[Fetch a document by ID and return it.]] - rationale - worked/example/raw/api.py
- [[handle_get()]] - code - worked/example/raw/api.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/handle_get
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_e]]
- 1 edge to [[_COMMUNITY_storage.py]]

## Top bridge nodes
- [[handle_get()]] - degree 3, connects to 2 communities