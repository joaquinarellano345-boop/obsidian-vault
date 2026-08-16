---
type: community
cohesion: 0.03
members: 119
---

# build_from_json

**Cohesion:** 0.03 - loosely connected
**Members:** 119 nodes

## Members
- [[1145 ghost-merge a semantic ghost collapses into the single AST node     shari]] - rationale - tests/test_build.py
- [[1279 a semanticLLM edge lacking source_file must inherit it from its     sour]] - rationale - tests/test_build.py
- [[1749 an `imports``references` edge must not bind across a language     family]] - rationale - tests/test_build.py
- [[1753 two NON-AST (semantic) nodes sharing (basename, label) but from     DIFFE]] - rationale - tests/test_build.py
- [[1799 guard a code symbol `foo` and an unrelated `foo_doc` (not     file_type=d]] - rationale - tests/test_build.py
- [[1799 the markdown quick-scan's bare `slug` doc node and the semantic     `s]] - rationale - tests/test_build.py
- [[1916 build_from_json used to copy hyperedges into G.graphhyperedges     ve]] - rationale - tests/test_build.py
- [[1960 an explicit ``weight null`` (JSON null - None) used to survive     ``]] - rationale - tests/test_build.py
- [[2068 the ghost-merge key is the full source_file, not the bare basename.     A]] - rationale - tests/test_build.py
- [[2068 two unrelated non-AST nodes with the same basename+label in     DIFFERENT]] - rationale - tests/test_build.py
- [[2194 a mixed batch of schema errors must report per-cause counts, not     just]] - rationale - tests/test_build.py
- [[2194 a recovered alias node must serialize with a non-empty norm_label     so]] - rationale - tests/test_build.py
- [[2194 an alias-only semantic node (namepath) must participate in the     ASTL]] - rationale - tests/test_build.py
- [[2194 edges carrying `type``confidence_score` instead of     `relation``confi]] - rationale - tests/test_build.py
- [[2194 when both the canonical field and its alias are present, the     canonica]] - rationale - tests/test_build.py
- [[2197 a semantic fragment whose ids were derived from an ABSOLUTE     source_fi]] - rationale - tests/test_build.py
- [[A genuine duplicate — two non-AST nodes with the SAME source_file and     label]] - rationale - tests/test_build.py
- [[A node_link JSON with multigraph true must load as MultiGraph and the     helpe]] - rationale - tests/test_build.py
- [[A same-directory .h.cpp pair collides on their shared pre-extension id     and]] - rationale - tests/test_build.py
- [[Alias normalization must run BEFORE the semantic id-remap loop so a     `members]] - rationale - tests/test_hypergraph.py
- [[Already-relative source_file paths must not be modified.]] - rationale - tests/test_build.py
- [[Build a NetworkX graph from an extraction dict.      directed=True produces a Di]] - rationale - graphify/build.py
- [[Companion to the ambiguous case above when exactly one real file claims     an]] - rationale - tests/test_build.py
- [[Known invalid file_type values map to their canonical equivalents.]] - rationale - tests/test_build.py
- [[Legacy 'from''to' keys on edges are accepted alongside 'source''target'.]] - rationale - tests/test_build.py
- [[Legacy 'source' key on nodes is renamed to 'source_file' before graph build.]] - rationale - tests/test_build.py
- [[Legacy nodes with file_type=None (e.g. preserved from older graph.json     by `_]] - rationale - tests/test_build.py
- [[Nodes missing file_type entirely should also be canonicalized to 'concept'.]] - rationale - tests/test_build.py
- [[Non-numeric  NaN  inf  negative weights fall back to 1.0 (the backends     re]] - rationale - tests/test_build.py
- [[Regression for 1061.      When an extraction emits two `calls` edges between th]] - rationale - tests/test_build.py
- [[Return every edge attribute dict for (u, v); always a list.]] - rationale - graphify/build.py
- [[Return one edge attribute dict for (u, v), tolerating MultiGraph.      For Multi]] - rationale - graphify/build.py
- [[Semantic subagents emit absolute source_file paths; build_from_json must     rel]] - rationale - tests/test_build.py
- [[Store hyperedges in the graph's metadata dict.]] - rationale - graphify/export.py
- [[Tests for hyperedge support in graphify.]] - rationale - tests/test_hypergraph.py
- [[The 1504 old-stem alias (e.g. ping.h - bare ping) is meant to let a     st]] - rationale - tests/test_build.py
- [[The 1749 guard only drops when BOTH endpoints are known code languages,     so]] - rationale - tests/test_build.py
- [[Three hyperedges, one per member-key spelling nodes  members  node_ids.]] - rationale - tests/test_hypergraph.py
- [[Unknown file_type values are coerced through the synonym mapper, falling     bac]] - rationale - tests/test_build.py
- [[Windows backslash paths and POSIX paths for the same file must produce one node.]] - rationale - tests/test_build.py
- [[Write graph.json then reload it - hyperedges must survive.]] - rationale - tests/test_hypergraph.py
- [[_alias_extraction()]] - code - tests/test_hypergraph.py
- [[_make_report()]] - code - tests/test_hypergraph.py
- [[attach_hyperedges()]] - code - graphify/export.py
- [[build_from_json()]] - code - graphify/build.py
- [[build_from_json(root=...) must relativize hyperedge source_file like it     alre]] - rationale - tests/test_hypergraph.py
- [[edge_data()]] - code - graphify/build.py
- [[edge_datas()]] - code - graphify/build.py
- [[load_extraction()]] - code - tests/test_build.py
- [[test_absolute_derived_semantic_ids_rekeyed()]] - code - tests/test_build.py
- [[test_alias_node_gets_nonempty_norm_label()]] - code - tests/test_build.py
- [[test_alias_node_ghost_merges_into_ast_twin()]] - code - tests/test_build.py
- [[test_ambiguous_edge_preserved()]] - code - tests/test_build.py
- [[test_attach_hyperedges_adds_new()]] - code - tests/test_hypergraph.py
- [[test_attach_hyperedges_deduplicates()]] - code - tests/test_hypergraph.py
- [[test_attach_hyperedges_multiple_different_ids()]] - code - tests/test_hypergraph.py
- [[test_attach_hyperedges_skips_entry_without_id()]] - code - tests/test_hypergraph.py
- [[test_build.py]] - code - tests/test_build.py
- [[test_build_canonical_nodes_wins_over_alias()]] - code - tests/test_hypergraph.py
- [[test_build_dedups_alias_members_preserving_order()]] - code - tests/test_hypergraph.py
- [[test_build_from_json_ambiguous_alias_detected_despite_header_impl_salting()]] - code - tests/test_build.py
- [[test_build_from_json_ambiguous_old_stem_alias_stays_dangling()]] - code - tests/test_build.py
- [[test_build_from_json_edge_count()]] - code - tests/test_build.py
- [[test_build_from_json_missing_hyperedges_key()]] - code - tests/test_hypergraph.py
- [[test_build_from_json_no_hyperedges()]] - code - tests/test_hypergraph.py
- [[test_build_from_json_node_count()]] - code - tests/test_build.py
- [[test_build_from_json_preserves_first_direction_on_bidirectional_pair()]] - code - tests/test_build.py
- [[test_build_from_json_prunes_dangling_hyperedge_members()]] - code - tests/test_build.py
- [[test_build_from_json_relative_source_file_unchanged()]] - code - tests/test_build.py
- [[test_build_from_json_relativizes_absolute_source_file()]] - code - tests/test_build.py
- [[test_build_from_json_relativizes_hyperedge_source_file()]] - code - tests/test_hypergraph.py
- [[test_build_from_json_skips_edge_with_non_hashable_endpoint()]] - code - tests/test_build.py
- [[test_build_from_json_skips_non_hashable_node_id()]] - code - tests/test_build.py
- [[test_build_from_json_stores_hyperedges()]] - code - tests/test_hypergraph.py
- [[test_build_from_json_unambiguous_old_stem_alias_still_resolves()]] - code - tests/test_build.py
- [[test_build_normalizes_member_aliases_to_nodes()]] - code - tests/test_hypergraph.py
- [[test_build_rekeys_alias_keyed_hyperedge_members()]] - code - tests/test_hypergraph.py
- [[test_build_warns_once_per_aliased_hyperedge()]] - code - tests/test_hypergraph.py
- [[test_cross_family_reference_to_unknown_ext_is_kept()]] - code - tests/test_build.py
- [[test_cross_language_imports_references_are_dropped()]] - code - tests/test_build.py
- [[test_dedupe_edges_collapses_exact_parallels()]] - code - tests/test_build.py
- [[test_dedupe_edges_is_idempotent()]] - code - tests/test_build.py
- [[test_dedupe_nodes_collapses_by_id_last_wins()]] - code - tests/test_build.py
- [[test_doc_twin_merge_does_not_touch_code_symbols()]] - code - tests/test_build.py
- [[test_edge_data_multidigraph()]] - code - tests/test_build.py
- [[test_edge_data_multigraph_with_parallel_edges()]] - code - tests/test_build.py
- [[test_edge_data_node_link_multigraph_roundtrip()]] - code - tests/test_build.py
- [[test_edge_data_simple_graph()]] - code - tests/test_build.py
- [[test_edge_datas_multigraph_returns_all_parallel_edges()]] - code - tests/test_build.py
- [[test_edge_datas_simple_graph_returns_singleton_list()]] - code - tests/test_build.py
- [[test_edge_missing_source_file_backfilled_from_node()]] - code - tests/test_build.py
- [[test_edges_have_confidence()]] - code - tests/test_build.py
- [[test_extraction_warning_breakdown_by_cause()]] - code - tests/test_build.py
- [[test_file_type_synonym_mapping()]] - code - tests/test_build.py
- [[test_ghost_merge_non_ast_different_files_both_survive()]] - code - tests/test_build.py
- [[test_ghost_merge_non_ast_same_file_still_merges()]] - code - tests/test_build.py
- [[test_ghost_merge_not_across_directories_same_basename()]] - code - tests/test_build.py
- [[test_ghost_merge_unique_located_node_still_merges()]] - code - tests/test_build.py
- [[test_ghost_merge_uses_source_file_not_basename()]] - code - tests/test_build.py
- [[test_hyperedges_roundtrip_via_json_file()]] - code - tests/test_hypergraph.py
- [[test_hypergraph.py]] - code - tests/test_hypergraph.py
- [[test_legacy_edge_from_to_canonicalized()]] - code - tests/test_build.py
- [[test_legacy_edge_type_confidence_score_aliases_folded()]] - code - tests/test_build.py
- [[test_legacy_node_source_canonicalized()]] - code - tests/test_build.py
- [[test_malformed_weights_normalize()]] - code - tests/test_build.py
- [[test_markdown_doc_twin_merges_into_semantic_doc_node()]] - code - tests/test_build.py
- [[test_missing_file_type_defaults_to_concept()]] - code - tests/test_build.py
- [[test_node_alias_canonical_field_wins()]] - code - tests/test_build.py
- [[test_nodes_have_label()]] - code - tests/test_build.py
- [[test_none_file_type_defaults_to_concept()]] - code - tests/test_build.py
- [[test_null_weight_edge_builds_and_clusters()]] - code - tests/test_build.py
- [[test_real_invalid_file_type_coerced_to_concept()]] - code - tests/test_build.py
- [[test_report_includes_hyperedge_node_list()]] - code - tests/test_hypergraph.py
- [[test_report_includes_hyperedges_section()]] - code - tests/test_hypergraph.py
- [[test_report_skips_hyperedges_section_when_empty()]] - code - tests/test_hypergraph.py
- [[test_report_skips_hyperedges_section_when_key_missing()]] - code - tests/test_hypergraph.py
- [[test_source_file_backslash_normalized()]] - code - tests/test_build.py
- [[test_to_json_hyperedges_empty_when_none()]] - code - tests/test_hypergraph.py
- [[test_to_json_includes_hyperedges()]] - code - tests/test_hypergraph.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/build_from_json
SORT file.name ASC
```

## Connections to other communities
- 26 edges to [[_COMMUNITY_graphifybuild.py]]
- 14 edges to [[_COMMUNITY_generate]]
- 13 edges to [[_COMMUNITY_cli.py]]
- 10 edges to [[_COMMUNITY_to_json]]
- 8 edges to [[_COMMUNITY_test_export.py]]
- 6 edges to [[_COMMUNITY_make_id]]
- 6 edges to [[_COMMUNITY_validate_extraction]]
- 5 edges to [[_COMMUNITY_export.py]]
- 5 edges to [[_COMMUNITY__semantic_id_remap]]
- 4 edges to [[_COMMUNITY_test_src_layout_import_resolution.py]]
- 3 edges to [[_COMMUNITY_test_file_label_disambiguation.py]]
- 3 edges to [[_COMMUNITY_to_wiki]]
- 3 edges to [[_COMMUNITY_test_cpp_objc_cross_file_calls.py]]
- 3 edges to [[_COMMUNITY_test_falkordb_integration.py]]
- 3 edges to [[_COMMUNITY_test_import_self_loops.py]]
- 3 edges to [[_COMMUNITY_test_java_type_resolution.py]]
- 3 edges to [[_COMMUNITY_test_manifest_ingest.py]]
- 3 edges to [[_COMMUNITY_test_phantom_external_import.py]]
- 2 edges to [[_COMMUNITY_test_benchmark.py]]
- 2 edges to [[_COMMUNITY_to_obsidian]]
- 2 edges to [[_COMMUNITY_serve.py]]
- 2 edges to [[_COMMUNITY__build_server]]
- 2 edges to [[_COMMUNITY_test_multigraph_diagnostics.py]]
- 2 edges to [[_COMMUNITY_test_analyze.py]]
- 2 edges to [[_COMMUNITY_test_cli_export.py]]
- 2 edges to [[_COMMUNITY_test_cluster.py]]
- 2 edges to [[_COMMUNITY_extract_python]]
- 2 edges to [[_COMMUNITY__surprise_score]]
- 2 edges to [[_COMMUNITY_test_swift_cross_file_calls.py]]
- 2 edges to [[_COMMUNITY_test_swift_import_resolution.py]]
- 2 edges to [[_COMMUNITY_extract_terraform]]
- 1 edge to [[_COMMUNITY_semantic_cleanup.py]]
- 1 edge to [[_COMMUNITY__make_id]]
- 1 edge to [[_COMMUNITY_Graph]]
- 1 edge to [[_COMMUNITY_test_extract.py]]
- 1 edge to [[_COMMUNITY_extract_json]]
- 1 edge to [[_COMMUNITY_test_languages.py]]
- 1 edge to [[_COMMUNITY__labels]]
- 1 edge to [[_COMMUNITY_test_reflect.py]]
- 1 edge to [[_COMMUNITY_test_scip_ingest.py]]
- 1 edge to [[_COMMUNITY_ingest_scip_json]]
- 1 edge to [[_COMMUNITY_extract_js]]

## Top bridge nodes
- [[build_from_json()]] - degree 155, connects to 36 communities
- [[test_build.py]] - degree 76, connects to 8 communities
- [[edge_data()]] - degree 24, connects to 8 communities
- [[test_hypergraph.py]] - degree 30, connects to 4 communities
- [[edge_datas()]] - degree 11, connects to 4 communities