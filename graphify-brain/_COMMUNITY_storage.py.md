---
type: community
cohesion: 0.24
members: 15
---

# storage.py

**Cohesion:** 0.24 - loosely connected
**Members:** 15 nodes

## Members
- [[Delete a document by ID.]] - rationale - worked/example/raw/api.py
- [[Load the full document index from disk.]] - rationale - worked/example/raw/storage.py
- [[Persist the index to disk.]] - rationale - worked/example/raw/storage.py
- [[Remove a document and its index entry. Returns True if it existed.]] - rationale - worked/example/raw/storage.py
- [[Storage module - persists documents to disk and maintains the search index. All]] - rationale - worked/example/raw/storage.py
- [[Write a parsed document to storage. Returns the assigned record ID.]] - rationale - worked/example/raw/storage.py
- [[Write an enriched document to storage, updating the index with keywords.]] - rationale - worked/example/raw/storage.py
- [[_ensure_storage()]] - code - worked/example/raw/storage.py
- [[delete_record()]] - code - worked/example/raw/storage.py
- [[handle_delete()]] - code - worked/example/raw/api.py
- [[load_index()]] - code - worked/example/raw/storage.py
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
- 6 edges to [[_COMMUNITY_processor.py]]
- 5 edges to [[_COMMUNITY_api.py]]
- 3 edges to [[_COMMUNITY_parser.py]]
- 2 edges to [[_COMMUNITY_list_records]]
- 2 edges to [[_COMMUNITY_handle_enrich]]

## Top bridge nodes
- [[storage.py]] - degree 12, connects to 5 communities
- [[load_index()]] - degree 12, connects to 3 communities
- [[delete_record()]] - degree 7, connects to 1 community
- [[_ensure_storage()]] - degree 7, connects to 1 community
- [[save_parsed()]] - degree 7, connects to 1 community