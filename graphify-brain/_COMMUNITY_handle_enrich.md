---
type: community
cohesion: 0.33
members: 6
---

# handle_enrich

**Cohesion:** 0.33 - loosely connected
**Members:** 6 nodes

## Members
- [[Fetch a document by ID and return it.]] - rationale - worked/example/raw/api.py
- [[Fetch a single document by ID.]] - rationale - worked/example/raw/storage.py
- [[Re-enrich a document to pick up new cross-references.]] - rationale - worked/example/raw/api.py
- [[handle_enrich()]] - code - worked/example/raw/api.py
- [[handle_get()]] - code - worked/example/raw/api.py
- [[load_record()]] - code - worked/example/raw/storage.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/handle_enrich
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_api.py]]
- 2 edges to [[_COMMUNITY_storage.py]]
- 1 edge to [[_COMMUNITY_e]]
- 1 edge to [[_COMMUNITY_processor.py]]

## Top bridge nodes
- [[handle_enrich()]] - degree 6, connects to 3 communities
- [[load_record()]] - degree 6, connects to 2 communities
- [[handle_get()]] - degree 3, connects to 1 community