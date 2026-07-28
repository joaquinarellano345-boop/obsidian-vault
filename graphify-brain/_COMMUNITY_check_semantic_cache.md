---
type: community
cohesion: 0.08
members: 26
---

# check_semantic_cache

**Cohesion:** 0.08 - loosely connected
**Members:** 26 nodes

## Members
- [[1916 (ghost variant) a node group whose source_file does not exist is     sile]] - rationale - tests/test_cache.py
- [[1916 a hyperedge whose member list intersects the skipped ids is     dropped w]] - rationale - tests/test_cache.py
- [[1916 an edge in an ALLOWED file's group referencing a node grouped     under a]] - rationale - tests/test_cache.py
- [[A skill snippet substitutes SPEC_PATH by hand. If it lands on a path that     is]] - rationale - tests/test_cache.py
- [[Check semantic extraction cache for a list of absolute file paths.      Returns]] - rationale - graphify/cache.py
- [[Deep entries must not satisfy mode=None reads (and plain entries must     not sa]] - rationale - tests/test_cache.py
- [[Entries written before fingerprinting have unknowable vintage. They are     stil]] - rationale - tests/test_cache.py
- [[Omitting mode writes exactly the historical cachesemantic layout —     forward]] - rationale - tests/test_cache.py
- [[Once a file is re-extracted under the current prompt, its fingerprinted     entr]] - rationale - tests/test_cache.py
- [[The prompt fingerprint nests inside the deep namespace (1894), so the     two d]] - rationale - tests/test_cache.py
- [[The prompt-file fingerprint is memoized per (path, size, mtime); an edited     s]] - rationale - tests/test_cache.py
- [[The reported bug (1939) after the extraction prompt changes, an     unchanged]] - rationale - tests/test_cache.py
- [[check_semantic_cache()]] - code - graphify/cache.py
- [[mode='deep' saves under cachesemantic-deep and reads back from it.]] - rationale - tests/test_cache.py
- [[test_prompt_file_reflects_edited_spec()]] - code - tests/test_cache.py
- [[test_save_semantic_cache_drops_edges_to_ghost_file_nodes()]] - code - tests/test_cache.py
- [[test_save_semantic_cache_drops_edges_to_out_of_scope_nodes()]] - code - tests/test_cache.py
- [[test_save_semantic_cache_drops_hyperedges_touching_skipped_nodes()]] - code - tests/test_cache.py
- [[test_semantic_cache_deep_invisible_to_plain_reads_and_vice_versa()]] - code - tests/test_cache.py
- [[test_semantic_cache_deep_mode_roundtrip_under_deep_namespace()]] - code - tests/test_cache.py
- [[test_semantic_cache_fingerprinted_entry_beats_legacy()]] - code - tests/test_cache.py
- [[test_semantic_cache_legacy_entries_served_with_warning()]] - code - tests/test_cache.py
- [[test_semantic_cache_mode_none_layout_unchanged()]] - code - tests/test_cache.py
- [[test_semantic_cache_prompt_and_mode_compose()]] - code - tests/test_cache.py
- [[test_semantic_cache_prompt_change_invalidates()]] - code - tests/test_cache.py
- [[test_semantic_cache_unreadable_prompt_file_warns_and_falls_back()]] - code - tests/test_cache.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/check_semantic_cache
SORT file.name ASC
```

## Connections to other communities
- 15 edges to [[_COMMUNITY_test_cache.py]]
- 13 edges to [[_COMMUNITY_save_semantic_cache]]
- 2 edges to [[_COMMUNITY_file_hash]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_test_semantic_cache_out_root.py]]
- 1 edge to [[_COMMUNITY_test_stat_index_portability.py]]

## Top bridge nodes
- [[check_semantic_cache()]] - degree 22, connects to 5 communities
- [[test_semantic_cache_deep_mode_roundtrip_under_deep_namespace()]] - degree 5, connects to 3 communities
- [[test_semantic_cache_mode_none_layout_unchanged()]] - degree 5, connects to 3 communities
- [[test_prompt_file_reflects_edited_spec()]] - degree 4, connects to 2 communities
- [[test_save_semantic_cache_drops_edges_to_ghost_file_nodes()]] - degree 4, connects to 2 communities