---
type: community
cohesion: 0.08
members: 42
---

# save_semantic_cache

**Cohesion:** 0.08 - loosely connected
**Members:** 42 nodes

## Members
- [[1715 merge_existing=True unions with the prior entry so a file split     acros]] - rationale - tests/test_cache.py
- [[1757 an undispatched file must keep its complete cache entry when a     semant]] - rationale - tests/test_cache.py
- [[1757 the per-chunk incremental checkpoint must not let a chunk's     mis-attri]] - rationale - tests/test_chunking.py
- [[1916 + 1715 with merge_existing=True (the llm.py checkpoint path),     only t]] - rationale - tests/test_cache.py
- [[1950 empty-parse gap a chunk that truncates to an empty parse produces     NO]] - rationale - tests/test_partial_cache.py
- [[A file sliced across chunks an earlier truncated slice must not be     dropped]] - rationale - tests/test_partial_cache.py
- [[A truncated file produced output this run but is left unstamped in the     manif]] - rationale - tests/test_partial_cache.py
- [[Default save_semantic_cache replaces a file's cached entry (the final,     autho]] - rationale - tests/test_cache.py
- [[Ordering guard once a file is partial (from an empty-parse truncation,     so n]] - rationale - tests/test_partial_cache.py
- [[Return cached extraction for this file if hash matches, else None.      Cache ke]] - rationale - graphify/cache.py
- [[Save semantic extraction results to cache, keyed by source_file.      Groups nod]] - rationale - graphify/cache.py
- [[Source files known partial those carrying a ``_partial`` item marker, plus]] - rationale - graphify/llm.py
- [[Tag every nodeedgehyperedge in a truncated chunk result with an internal     `]] - rationale - graphify/llm.py
- [[Tests for partial-extraction cache promotion.  A truncated LLM chunk (`finish_re]] - rationale - tests/test_partial_cache.py
- [[True if any nodeedgehyperedge in a per-file group carries the internal     ``_]] - rationale - graphify/cache.py
- [[_doc()]] - code - tests/test_partial_cache.py
- [[_group_has_partial_marker()]] - code - graphify/cache.py
- [[_mark_partial()]] - code - graphify/llm.py
- [[_partial_source_files must surface a file recorded in _partial_files even     wh]] - rationale - tests/test_partial_cache.py
- [[_partial_source_files()]] - code - graphify/llm.py
- [[load_cached()]] - code - graphify/cache.py
- [[merge_existing must not union a pre-fingerprint entry into a write it is     abo]] - rationale - tests/test_cache.py
- [[save_semantic_cache()]] - code - graphify/cache.py
- [[test_checkpoint_scopes_cache_writes_to_chunk_files()]] - code - tests/test_chunking.py
- [[test_clean_slice_does_not_repromote_empty_parse_partial()]] - code - tests/test_partial_cache.py
- [[test_group_has_partial_marker()]] - code - tests/test_partial_cache.py
- [[test_intrinsic_partial_marker_makes_entry_a_cache_miss()]] - code - tests/test_partial_cache.py
- [[test_mark_partial_and_partial_source_files()]] - code - tests/test_partial_cache.py
- [[test_merge_existing_accumulates_slices_and_stays_partial()]] - code - tests/test_partial_cache.py
- [[test_non_partial_entry_loads_normally()]] - code - tests/test_partial_cache.py
- [[test_partial_cache.py]] - code - tests/test_partial_cache.py
- [[test_partial_entry_self_heals_on_complete_reextraction()]] - code - tests/test_partial_cache.py
- [[test_partial_files_carries_empty_parse_truncation()]] - code - tests/test_partial_cache.py
- [[test_partial_source_files_arg_stamps_entry()]] - code - tests/test_partial_cache.py
- [[test_partial_source_files_empty_when_unmarked()]] - code - tests/test_partial_cache.py
- [[test_save_semantic_cache_merge_existing_prunes_only_incoming()]] - code - tests/test_cache.py
- [[test_save_semantic_cache_merge_existing_unions()]] - code - tests/test_cache.py
- [[test_save_semantic_cache_overwrites_by_default()]] - code - tests/test_cache.py
- [[test_save_semantic_cache_rejects_out_of_scope_source_file()]] - code - tests/test_cache.py
- [[test_save_stamps_partial_file_with_no_items()]] - code - tests/test_partial_cache.py
- [[test_semantic_cache_merge_existing_never_fuses_legacy_vintage()]] - code - tests/test_cache.py
- [[test_stamped_manifest_excludes_partial_files()]] - code - tests/test_partial_cache.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/save_semantic_cache
SORT file.name ASC
```

## Connections to other communities
- 25 edges to [[_COMMUNITY_test_cache.py]]
- 13 edges to [[_COMMUNITY_check_semantic_cache]]
- 8 edges to [[_COMMUNITY_test_chunking.py]]
- 8 edges to [[_COMMUNITY_test_semantic_cache_out_root.py]]
- 7 edges to [[_COMMUNITY_cli.py]]
- 6 edges to [[_COMMUNITY_file_hash]]
- 4 edges to [[_COMMUNITY_llm.py]]
- 3 edges to [[_COMMUNITY_extract]]
- 3 edges to [[_COMMUNITY_test_extract_cli.py]]
- 2 edges to [[_COMMUNITY_test_extract_cache_location.py]]
- 2 edges to [[_COMMUNITY_test_stat_index_portability.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_clear_cache]]
- 1 edge to [[_COMMUNITY__extraction_system]]
- 1 edge to [[_COMMUNITY__extract_with_adaptive_retry]]

## Top bridge nodes
- [[save_semantic_cache()]] - degree 56, connects to 10 communities
- [[load_cached()]] - degree 44, connects to 9 communities
- [[test_partial_cache.py]] - degree 21, connects to 3 communities
- [[_partial_source_files()]] - degree 7, connects to 2 communities
- [[test_checkpoint_scopes_cache_writes_to_chunk_files()]] - degree 6, connects to 2 communities