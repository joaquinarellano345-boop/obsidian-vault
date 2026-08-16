---
type: community
cohesion: 0.18
members: 19
---

# storage.py

**Cohesion:** 0.18 - loosely connected
**Members:** 19 nodes

## Members
- [[Delete a document by ID.]] - rationale - worked/example/raw/api.py
- [[Fetch a single document by ID.]] - rationale - worked/example/raw/storage.py
- [[Load the full document index from disk.]] - rationale - worked/example/raw/storage.py
- [[Persist the index to disk.]] - rationale - worked/example/raw/storage.py
- [[Remove a document and its index entry. Returns True if it existed.]] - rationale - worked/example/raw/storage.py
- [[Simple keyword search over the index.     Returns documents whose keyword list o]] - rationale - worked/example/raw/api.py
- [[Storage module - persists documents to disk and maintains the search index. All]] - rationale - worked/example/raw/storage.py
- [[Write a parsed document to storage. Returns the assigned record ID.]] - rationale - worked/example/raw/storage.py
- [[Write an enriched document to storage, updating the index with keywords.]] - rationale - worked/example/raw/storage.py
- [[_ensure_storage()]] - code - worked/example/raw/storage.py
- [[delete_record()]] - code - worked/example/raw/storage.py
- [[handle_delete()]] - code - worked/example/raw/api.py
- [[handle_search()]] - code - worked/example/raw/api.py
- [[load_index()]] - code - worked/example/raw/storage.py
- [[load_record()]] - code - worked/example/raw/storage.py
- [[save_index()]] - code - worked/example/raw/storage.py
- [[save_parsed()]] - code - worked/example/raw/storage.py
- [[save_processed()]] - code - worked/example/raw/storage.py
- [[storage.py]] - code - worked/example/raw/storage.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/storagepy
SORT file.name ASC
```

## Connections to other communities
- 7 edges to [[_COMMUNITY_e]]
- 6 edges to [[_COMMUNITY_processor.py]]
- 3 edges to [[_COMMUNITY_parser.py]]
- 2 edges to [[_COMMUNITY_list_records]]
- 1 edge to [[_COMMUNITY_handle_get]]

## Top bridge nodes
- [[storage.py]] - degree 12, connects to 4 communities
- [[load_index()]] - degree 12, connects to 3 communities
- [[load_record()]] - degree 6, connects to 2 communities
- [[delete_record()]] - degree 7, connects to 1 community
- [[save_parsed()]] - degree 7, connects to 1 community