---
type: community
cohesion: 0.05
members: 71
---

# graphify/build.py

**Cohesion:** 0.05 - loosely connected
**Members:** 71 nodes

## Members
- [[1007 manifest stores absolute paths, graph nodes store relative paths.     pru]] - rationale - tests/test_build.py
- [[1007 prune_sources with Windows-style backslash absolute paths must still matc]] - rationale - tests/test_build.py
- [[1796 guard must not break real deletions a file in prune_sources but NOT     i]] - rationale - tests/test_build_merge_hyperedges_and_prune.py
- [[1796 protection must hold in absolute-identity space too a file present     in]] - rationale - tests/test_build_merge_hyperedges_and_prune.py
- [[1796 a file present in BOTH new_chunks (re-extracted) and prune_sources     mu]] - rationale - tests/test_build_merge_hyperedges_and_prune.py
- [[2012 a node whose source_file survived in ABSOLUTE form must still be     prun]] - rationale - tests/test_build_merge_hyperedges_and_prune.py
- [[F4 build_merge must refuse to read an existing graph.json that     exceeds the]] - rationale - tests/test_build.py
- [[A symlinked scan root (macOS var - privatevar, symlinked homeworktree)]] - rationale - tests/test_build_merge_hyperedges_and_prune.py
- [[Best-effort scan root for relativizing paths in build_merge when the caller]] - rationale - graphify/build.py
- [[Canonical dedup key — Unicode-aware, preserves CJKword characters.]] - rationale - graphify/build.py
- [[Fold legacy edge field aliases onto canonical keys, in place (2194).      ``typ]] - rationale - graphify/build.py
- [[Fold legacy node field aliases onto canonical keys, in place (2194).      ``nam]] - rationale - graphify/build.py
- [[Incremental --update hyperedge preservation (1574) and root-less prune (1571)]] - rationale - tests/test_build_merge_hyperedges_and_prune.py
- [[Load (nodes, edges, hyperedges) from an existing graph.json for an     increment]] - rationale - graphify/build.py
- [[Load existing graph.json, merge new chunks into it, and save back.      Re-extra]] - rationale - graphify/build.py
- [[Map a markdown quick-scan's bare doc node ``slug`` to the semantic     ``slug]] - rationale - graphify/build.py
- [[Merge multiple extraction results into one graph.      directed=True produces a]] - rationale - graphify/build.py
- [[Merge nodes that share a normalised label, rewriting edge references.      Prefe]] - rationale - graphify/build.py
- [[Merge the existing raw graph.json forward into a fresh raw extraction     (the `]] - rationale - graphify/build.py
- [[Normalize path separators and relativize absolute paths.      Converts backslash]] - rationale - graphify/build.py
- [[Path_2]] - code
- [[Path_61]] - code
- [[Pre-migration stem forms a semantic fragment may have used for ``rel``.      Ord]] - rationale - graphify/build.py
- [[Re-extracting a CHANGED file must REPLACE its prior nodesedges, not     accumul]] - rationale - tests/test_build.py
- [[Regression for 760.      When the callee is defined before the caller in source]] - rationale - tests/test_build.py
- [[Return a form-insensitive absolute identity for a source_file.      prunereplac]] - rationale - graphify/build.py
- [[Skill contract the extraction subagent must emit source_file as the     verbati]] - rationale - tests/test_build.py
- [[The read-only-consumer nudge (queryserve) flags a pre-1504 graph and     leave]] - rationale - tests/test_build.py
- [[The runbook omits root; the fallback root must not break preservation.]] - rationale - tests/test_build_merge_hyperedges_and_prune.py
- [[Whether a loaded graph still uses pre-1504 node IDs (parent-dir  filename]] - rationale - graphify/build.py
- [[Write a graph.json in the shape to_json emits (top-level hyperedges).]] - rationale - tests/test_build_merge_hyperedges_and_prune.py
- [[_abs_identity()]] - code - graphify/build.py
- [[_doc_twin_remap()]] - code - graphify/build.py
- [[_fold_edge_aliases()]] - code - graphify/build.py
- [[_fold_node_aliases()]] - code - graphify/build.py
- [[_he_ids()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[_infer_merge_root()]] - code - graphify/build.py
- [[_load_existing_graph()]] - code - graphify/build.py
- [[_norm_label()]] - code - graphify/build.py
- [[_norm_source_file()]] - code - graphify/build.py
- [[_old_file_stems()]] - code - graphify/build.py
- [[_seed_two_file_graph()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[_write_graph()_2]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[build()]] - code - graphify/build.py
- [[build() passes root through to build_from_json (932).]] - rationale - tests/test_build.py
- [[build_merge()]] - code - graphify/build.py
- [[deduplicate_by_label()]] - code - graphify/build.py
- [[graph_has_legacy_ids()]] - code - graphify/build.py
- [[graphifybuild.py]] - code - graphify/build.py
- [[merge_raw_extraction()]] - code - graphify/build.py
- [[skipif]] - code
- [[test_build_merge_hyperedges_and_prune.py]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[test_build_merge_preserves_call_edge_direction()]] - code - tests/test_build.py
- [[test_build_merge_prune_absolute_paths_match_relative_nodes()]] - code - tests/test_build.py
- [[test_build_merge_prune_windows_backslash_paths()]] - code - tests/test_build.py
- [[test_build_merge_rejects_oversized_existing_graph()]] - code - tests/test_build.py
- [[test_build_merge_replaces_changed_file_stale_edges()]] - code - tests/test_build.py
- [[test_build_merge_root_collapses_convention_drift()]] - code - tests/test_build.py
- [[test_build_merges_multiple_extractions()]] - code - tests/test_build.py
- [[test_build_relativizes_absolute_source_file()]] - code - tests/test_build.py
- [[test_deleted_file_hyperedges_are_pruned()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[test_genuine_deletion_still_prunes()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[test_graph_has_legacy_ids_detects_old_scheme()]] - code - tests/test_build.py
- [[test_prune_matches_across_symlinked_root()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[test_prune_matches_node_stored_absolute_against_relative_delete()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[test_prune_reextracted_absolute_node_not_deleted()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[test_prune_without_root_removes_ghost_nodes_via_grandparent_fallback()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[test_prune_without_root_uses_graphify_root_marker()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[test_reextracted_file_in_prune_sources_is_not_deleted()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[test_update_preserves_hyperedges_of_unchanged_files()]] - code - tests/test_build_merge_hyperedges_and_prune.py
- [[test_update_without_root_still_preserves_hyperedges()]] - code - tests/test_build_merge_hyperedges_and_prune.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/graphify/buildpy
SORT file.name ASC
```

## Connections to other communities
- 26 edges to [[_COMMUNITY_build_from_json]]
- 14 edges to [[_COMMUNITY_cli.py]]
- 7 edges to [[_COMMUNITY_make_id]]
- 5 edges to [[_COMMUNITY_test_file_label_disambiguation.py]]
- 5 edges to [[_COMMUNITY__semantic_id_remap]]
- 5 edges to [[_COMMUNITY_test_cross_extension_reexport_self_cycle.py]]
- 4 edges to [[_COMMUNITY_deduplicate_entities]]
- 4 edges to [[_COMMUNITY_test_multigraph_diagnostics.py]]
- 2 edges to [[_COMMUNITY_export.py]]
- 2 edges to [[_COMMUNITY_semantic_cleanup.py]]
- 2 edges to [[_COMMUNITY_test_global_graph.py]]
- 2 edges to [[_COMMUNITY__make_id]]
- 2 edges to [[_COMMUNITY_default_graph_json]]
- 2 edges to [[_COMMUNITY_test_security.py]]
- 2 edges to [[_COMMUNITY_validate_extraction]]
- 2 edges to [[_COMMUNITY_serve.py]]
- 2 edges to [[_COMMUNITY_generate]]
- 2 edges to [[_COMMUNITY_to_json]]
- 1 edge to [[_COMMUNITY_test_benchmark.py]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_to_wiki]]
- 1 edge to [[_COMMUNITY_test_analyze.py]]
- 1 edge to [[_COMMUNITY_test_cluster.py]]
- 1 edge to [[_COMMUNITY_test_cpp_objc_cross_file_calls.py]]
- 1 edge to [[_COMMUNITY_test_export.py]]
- 1 edge to [[_COMMUNITY_test_extract.py]]
- 1 edge to [[_COMMUNITY_test_import_self_loops.py]]
- 1 edge to [[_COMMUNITY_test_java_type_resolution.py]]
- 1 edge to [[_COMMUNITY_test_manifest_ingest.py]]
- 1 edge to [[_COMMUNITY_test_phantom_external_import.py]]
- 1 edge to [[_COMMUNITY_extract_python]]
- 1 edge to [[_COMMUNITY__surprise_score]]
- 1 edge to [[_COMMUNITY_test_src_layout_import_resolution.py]]
- 1 edge to [[_COMMUNITY_test_swift_cross_file_calls.py]]
- 1 edge to [[_COMMUNITY_test_swift_import_resolution.py]]
- 1 edge to [[_COMMUNITY_extract_terraform]]
- 1 edge to [[_COMMUNITY_test_watch.py]]
- 1 edge to [[_COMMUNITY__load_graph]]
- 1 edge to [[_COMMUNITY_test_build_calls_dedup]]
- 1 edge to [[_COMMUNITY_extract_js]]

## Top bridge nodes
- [[graphifybuild.py]] - degree 72, connects to 36 communities
- [[graph_has_legacy_ids()]] - degree 14, connects to 6 communities
- [[build()]] - degree 24, connects to 5 communities
- [[build_merge()]] - degree 33, connects to 4 communities
- [[_norm_source_file()]] - degree 11, connects to 4 communities