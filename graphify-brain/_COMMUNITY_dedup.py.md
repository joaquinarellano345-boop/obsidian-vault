---
type: community
cohesion: 0.07
members: 32
---

# dedup.py

**Cohesion:** 0.07 - loosely connected
**Members:** 32 nodes

## Members
- [[A file-level semantic node whose id is exactly the slugified path (no     `_enti]] - rationale - tests/test_dedup.py
- [[A total order for choosing the survivor of an ID collision, independent of     t]] - rationale - graphify/dedup.py
- [[Entity deduplication pipeline for graphify knowledge graphs.  Pipeline exact no]] - rationale - graphify/dedup.py
- [[Fill the survivor's absentNone attributes from a same-source duplicate,     wit]] - rationale - graphify/dedup.py
- [[Lowercase + collapse non-alphanumeric runs to space (Unicode-aware).]] - rationale - graphify/dedup.py
- [[Report an ID collision in proportion to what dropping the loser actually costs.]] - rationale - graphify/dedup.py
- [[Return k-gram character shingles of text.]] - rationale - graphify/dedup.py
- [[Return user-facing accepted API-key variable names.]] - rationale - graphify/llm.py
- [[The ID prefixes a node extracted from ``source_file`` may legitimately mint.]] - rationale - graphify/dedup.py
- [[The prefix-extension guard must fire for pairs where one is a strict prefix]] - rationale - tests/test_dedup.py
- [[The prefix-extension guard must not fire for same-length pairs — only strict]] - rationale - tests/test_dedup.py
- [[True for AST-extracted code symbols.      Code-node identity is the node ID (whi]] - rationale - graphify/dedup.py
- [[True when exact-ID records came from the same source file.      Exact IDs can al]] - rationale - graphify/dedup.py
- [[True when the node's own source_file is the file its ID encodes.      A doc that]] - rationale - graphify/dedup.py
- [[_collision_rank()]] - code - graphify/dedup.py
- [[_defines_id()]] - code - graphify/dedup.py
- [[_format_backend_env_keys()]] - code - graphify/llm.py
- [[_id_prefixes()]] - code - graphify/dedup.py
- [[_is_code()]] - code - graphify/dedup.py
- [[_make_minhash()]] - code - graphify/dedup.py
- [[_merge_missing_attributes()]] - code - graphify/dedup.py
- [[_norm()]] - code - graphify/dedup.py
- [[_report_id_collision()]] - code - graphify/dedup.py
- [[_same_source_entity()]] - code - graphify/dedup.py
- [[_shingles()]] - code - graphify/dedup.py
- [[dedup.py]] - code - graphify/dedup.py
- [[test_bare_file_node_defines_its_own_id()]] - code - tests/test_dedup.py
- [[test_defines_id_helper()]] - code - tests/test_dedup.py
- [[test_prefix_guard_does_not_block_same_length_typos()]] - code - tests/test_dedup.py
- [[test_prefix_guard_fires_for_extension_pairs()]] - code - tests/test_dedup.py
- [[test_shingles_produces_trigrams()]] - code - tests/test_dedup.py
- [[test_shingles_short_string()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/deduppy
SORT file.name ASC
```

## Connections to other communities
- 16 edges to [[_COMMUNITY_deduplicate_entities]]
- 12 edges to [[_COMMUNITY_test_dedup.py]]
- 4 edges to [[_COMMUNITY_test_minhash.py]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY__call_llm]]
- 2 edges to [[_COMMUNITY_test_llm_backends.py]]
- 2 edges to [[_COMMUNITY_llm.py]]
- 1 edge to [[_COMMUNITY__is_variant_pair]]
- 1 edge to [[_COMMUNITY_test_js_import_resolution.py]]

## Top bridge nodes
- [[dedup.py]] - degree 27, connects to 6 communities
- [[_format_backend_env_keys()]] - degree 9, connects to 5 communities
- [[_norm()]] - degree 10, connects to 3 communities
- [[_make_minhash()]] - degree 4, connects to 2 communities
- [[_defines_id()]] - degree 8, connects to 1 community