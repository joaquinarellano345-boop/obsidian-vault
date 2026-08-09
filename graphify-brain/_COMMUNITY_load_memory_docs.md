---
type: community
cohesion: 0.25
members: 8
---

# load_memory_docs

**Cohesion:** 0.25 - loosely connected
**Members:** 8 nodes

## Members
- [[Determinism hinges on this sort docs come back oldest-first, filename as tiebre]] - rationale - tests/test_reflect.py
- [[Parse every memory doc under ``memory_dir``, sorted by date then filename.]] - rationale - graphify/reflect.py
- [[dead_endscorrections are appended in doc order, so their determinism rides on]] - rationale - tests/test_reflect.py
- [[load_memory_docs()]] - code - graphify/reflect.py
- [[test_dead_ends_and_corrections_follow_doc_order()]] - code - tests/test_reflect.py
- [[test_load_memory_docs_missing_dir_is_empty()]] - code - tests/test_reflect.py
- [[test_load_memory_docs_orders_by_date_then_filename()]] - code - tests/test_reflect.py
- [[test_load_memory_docs_skips_foreign_and_sorts()]] - code - tests/test_reflect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/load_memory_docs
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_test_reflect.py]]
- 4 edges to [[_COMMUNITY_reflect.py]]
- 2 edges to [[_COMMUNITY__write_raw_doc]]
- 1 edge to [[_COMMUNITY_save_query_result]]
- 1 edge to [[_COMMUNITY_parse_memory_doc]]
- 1 edge to [[_COMMUNITY_generate]]
- 1 edge to [[_COMMUNITY_cli.py]]

## Top bridge nodes
- [[load_memory_docs()]] - degree 15, connects to 5 communities
- [[test_dead_ends_and_corrections_follow_doc_order()]] - degree 5, connects to 2 communities
- [[test_load_memory_docs_orders_by_date_then_filename()]] - degree 4, connects to 2 communities
- [[test_load_memory_docs_skips_foreign_and_sorts()]] - degree 3, connects to 2 communities
- [[test_load_memory_docs_missing_dir_is_empty()]] - degree 2, connects to 1 community