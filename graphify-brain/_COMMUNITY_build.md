---
type: community
cohesion: 0.11
members: 18
---

# build

**Cohesion:** 0.11 - loosely connected
**Members:** 18 nodes

## Members
- [[1007 manifest stores absolute paths, graph nodes store relative paths.     pru]] - rationale - tests/test_build.py
- [[1007 prune_sources with Windows-style backslash absolute paths must still matc]] - rationale - tests/test_build.py
- [[Fold legacy node field aliases onto canonical keys, in place (2194).      ``nam]] - rationale - graphify/build.py
- [[Merge multiple extraction results into one graph.      directed=True produces a]] - rationale - graphify/build.py
- [[Re-extracting a CHANGED file must REPLACE its prior nodesedges, not     accumul]] - rationale - tests/test_build.py
- [[Skill contract the extraction subagent must emit source_file as the     verbati]] - rationale - tests/test_build.py
- [[The default build path must not discard semantic enrichment (2091).]] - rationale - tests/test_dedup.py
- [[_fold_node_aliases()]] - code - graphify/build.py
- [[build()]] - code - graphify/build.py
- [[build() passes root through to build_from_json (932).]] - rationale - tests/test_build.py
- [[build() should deduplicate near-identical nodes across extractions.]] - rationale - tests/test_dedup.py
- [[test_build_calls_dedup()]] - code - tests/test_dedup.py
- [[test_build_dedup_preserves_semantic_attributes()]] - code - tests/test_dedup.py
- [[test_build_merge_prune_absolute_paths_match_relative_nodes()]] - code - tests/test_build.py
- [[test_build_merge_prune_windows_backslash_paths()]] - code - tests/test_build.py
- [[test_build_merge_replaces_changed_file_stale_edges()]] - code - tests/test_build.py
- [[test_build_merge_root_collapses_convention_drift()]] - code - tests/test_build.py
- [[test_build_relativizes_absolute_source_file()]] - code - tests/test_build.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/build
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_build_from_json]]
- 8 edges to [[_COMMUNITY_graphifybuild.py]]
- 4 edges to [[_COMMUNITY_test_cross_extension_reexport_self_cycle.py]]
- 3 edges to [[_COMMUNITY_test_dedup.py]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 1 edge to [[_COMMUNITY_deduplicate_entities]]
- 1 edge to [[_COMMUNITY_extract_js]]

## Top bridge nodes
- [[build()]] - degree 24, connects to 7 communities
- [[_fold_node_aliases()]] - degree 4, connects to 2 communities
- [[test_build_merge_prune_absolute_paths_match_relative_nodes()]] - degree 4, connects to 2 communities
- [[test_build_merge_prune_windows_backslash_paths()]] - degree 4, connects to 2 communities
- [[test_build_merge_replaces_changed_file_stale_edges()]] - degree 4, connects to 2 communities