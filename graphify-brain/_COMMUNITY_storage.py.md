---
type: community
cohesion: 0.09
members: 37
---

# storage.py

**Cohesion:** 0.09 - loosely connected
**Members:** 37 nodes

## Members
- [[Add keyword index and cross-references to a validated document.]] - rationale - worked/example/raw/processor.py
- [[Delete a document by ID.]] - rationale - worked/example/raw/api.py
- [[Enrich a validated document and persist it. Returns the record ID.]] - rationale - worked/example/raw/processor.py
- [[Fetch a document by ID and return it.]] - rationale - worked/example/raw/api.py
- [[Fetch a single document by ID.]] - rationale - worked/example/raw/storage.py
- [[List all document IDs in storage.]] - rationale - worked/example/raw/api.py
- [[Load the full document index from disk.]] - rationale - worked/example/raw/storage.py
- [[Look up the index and return IDs of related documents by keyword overlap.]] - rationale - worked/example/raw/processor.py
- [[Persist the index to disk.]] - rationale - worked/example/raw/storage.py
- [[Processor module - transforms validated documents into enriched records ready fo]] - rationale - worked/example/raw/processor.py
- [[Pull non-stopword tokens from text, deduplicated.]] - rationale - worked/example/raw/processor.py
- [[Re-enrich all records in the index. Returns count of records updated.]] - rationale - worked/example/raw/processor.py
- [[Remove a document and its index entry. Returns True if it existed.]] - rationale - worked/example/raw/storage.py
- [[Return all record IDs currently in storage.]] - rationale - worked/example/raw/storage.py
- [[Simple keyword search over the index.     Returns documents whose keyword list o]] - rationale - worked/example/raw/api.py
- [[Storage module - persists documents to disk and maintains the search index. All]] - rationale - worked/example/raw/storage.py
- [[Write a parsed document to storage. Returns the assigned record ID.]] - rationale - worked/example/raw/storage.py
- [[Write an enriched document to storage, updating the index with keywords.]] - rationale - worked/example/raw/storage.py
- [[_ensure_storage()]] - code - worked/example/raw/storage.py
- [[delete_record()]] - code - worked/example/raw/storage.py
- [[enrich_document()]] - code - worked/example/raw/processor.py
- [[extract_keywords()]] - code - worked/example/raw/processor.py
- [[find_cross_references()]] - code - worked/example/raw/processor.py
- [[handle_delete()]] - code - worked/example/raw/api.py
- [[handle_get()]] - code - worked/example/raw/api.py
- [[handle_list()]] - code - worked/example/raw/api.py
- [[handle_search()]] - code - worked/example/raw/api.py
- [[list_records()]] - code - worked/example/raw/storage.py
- [[load_index()]] - code - worked/example/raw/storage.py
- [[load_record()]] - code - worked/example/raw/storage.py
- [[process_and_save()]] - code - worked/example/raw/processor.py
- [[processor.py]] - code - worked/example/raw/processor.py
- [[reprocess_all()]] - code - worked/example/raw/processor.py
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
- 18 edges to [[_COMMUNITY_e]]

## Top bridge nodes
- [[storage.py]] - degree 12, connects to 1 community
- [[load_index()]] - degree 12, connects to 1 community
- [[processor.py]] - degree 10, connects to 1 community
- [[process_and_save()]] - degree 7, connects to 1 community
- [[delete_record()]] - degree 7, connects to 1 community