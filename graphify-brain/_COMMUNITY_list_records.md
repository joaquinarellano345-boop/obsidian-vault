---
type: community
cohesion: 0.50
members: 4
---

# list_records

**Cohesion:** 0.50 - moderately connected
**Members:** 4 nodes

## Members
- [[List all document IDs in storage.]] - rationale - worked/example/raw/api.py
- [[Return all record IDs currently in storage.]] - rationale - worked/example/raw/storage.py
- [[handle_list()]] - code - worked/example/raw/api.py
- [[list_records()]] - code - worked/example/raw/storage.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/list_records
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_api.py]]
- 2 edges to [[_COMMUNITY_storage.py]]

## Top bridge nodes
- [[list_records()]] - degree 5, connects to 2 communities
- [[handle_list()]] - degree 3, connects to 1 community