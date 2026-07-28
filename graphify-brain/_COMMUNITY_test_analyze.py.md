---
type: community
cohesion: 0.04
members: 103
---

# test_analyze.py

**Cohesion:** 0.04 - loosely connected
**Members:** 103 nodes

## Members
- [[IMPORTANT resolve endpoints using source_file only; never infer from labelid]] - rationale - graphify/analyze.py
- [[AMBIGUOUS edge should score higher than an otherwise identical EXTRACTED edge.]] - rationale - tests/test_analyze.py
- [[Build a minimal graph.json + analysislabels in tmp_pathgraphify-out.      Mir]] - rationale - tests/test_reflect.py
- [[Code→doc INFERRED calls edge should score lower than same-language EXTRACTED.]] - rationale - tests/test_analyze.py
- [[Code↔paper INFERRED calls should still surface — it is a meaningful link.]] - rationale - tests/test_analyze.py
- [[Code↔paper edge should score higher than code↔code edge.]] - rationale - tests/test_analyze.py
- [[Compare two graph snapshots and return what changed.      Returns         {]] - rationale - graphify/analyze.py
- [[Concept nodes (empty source_file) must not appear in surprises.]] - rationale - tests/test_analyze.py
- [[Create a graph node resembling real graphify schema.]] - rationale - tests/test_analyze.py
- [[Cross-file edges between real codedoc entities, ranked by a composite     surpr]] - rationale - graphify/analyze.py
- [[Cross-language INFERRED calls edge should score lower than same-language EXTRACT]] - rationale - tests/test_analyze.py
- [[Cross-language INFERRED uses edge (the exact rsl-siege-manager false positive) s]] - rationale - tests/test_analyze.py
- [[Detect circular import dependencies at the file level.      Collapses symbol-lev]] - rationale - graphify/analyze.py
- [[DiGraph_1]] - code
- [[EXTRACTED code↔doc edges are real facts — must not be penalised.]] - rationale - tests/test_analyze.py
- [[EXTRACTED cross-language edges are real structural facts — must not be penalised]] - rationale - tests/test_analyze.py
- [[Find connections that are genuinely surprising - not obvious from file structure]] - rationale - graphify/analyze.py
- [[For single-source corpora find edges that bridge different communities.     The]] - rationale - graphify/analyze.py
- [[Graph analysis god nodes (most connected), surprising connections (cross-commun]] - rationale - graphify/analyze.py
- [[Helper Python node in backend, TypeScript node in frontend, different communi]] - rationale - tests/test_analyze.py
- [[Helper build a small nx.Graph from nodeedge specs.]] - rationale - tests/test_analyze.py
- [[INFERRED calls within the same language family must not be affected.]] - rationale - tests/test_analyze.py
- [[JSON-key filter must match regardless of label casing.]] - rationale - tests/test_analyze.py
- [[Multi-file graph should find cross-file edges between real entities.]] - rationale - tests/test_analyze.py
- [[Return True if this node is a manually-injected semantic concept node     rather]] - rationale - graphify/analyze.py
- [[Return True if two source files belong to different language families.]] - rationale - graphify/analyze.py
- [[Return the first path component - used to detect cross-repo edges.]] - rationale - graphify/analyze.py
- [[Return the top_n most-connected real entities - the core abstractions.      File]] - rationale - graphify/analyze.py
- [[Score how surprising a cross-file edge is. Returns (score, reasons).]] - rationale - graphify/analyze.py
- [[Single-file graph should return cross-community edges, not empty list.]] - rationale - tests/test_analyze.py
- [[Tests for analyze.py.]] - rationale - tests/test_analyze.py
- [[_cross_community_surprises()]] - code - graphify/analyze.py
- [[_cross_file_surprises()]] - code - graphify/analyze.py
- [[_cross_language()]] - code - graphify/analyze.py
- [[_file_category falls back to 'doc' for unknown extensions, so INFERRED     calls]] - rationale - tests/test_analyze.py
- [[_file_category()]] - code - graphify/analyze.py
- [[_is_concept_node()]] - code - graphify/analyze.py
- [[_is_json_key_node()]] - code - graphify/analyze.py
- [[_make_code_doc_graph()]] - code - tests/test_analyze.py
- [[_make_cross_lang_graph()]] - code - tests/test_analyze.py
- [[_make_cycle_graph_directed()]] - code - tests/test_analyze.py
- [[_make_file_node()]] - code - tests/test_analyze.py
- [[_make_graph()_3]] - code - tests/test_reflect.py
- [[_make_simple_graph()]] - code - tests/test_analyze.py
- [[_surprise_score()]] - code - graphify/analyze.py
- [[_top_level_dir()]] - code - graphify/analyze.py
- [[`semantically_similar_to` across code↔doc is explicit LLM insight — must not be]] - rationale - tests/test_analyze.py
- [[`semantically_similar_to` across languages is a genuine insight — must not be su]] - rationale - tests/test_analyze.py
- [[find_import_cycles()]] - code - graphify/analyze.py
- [[god_nodes must not return generic JSON key nodes like 'name' or 'id'.]] - rationale - tests/test_analyze.py
- [[god_nodes()]] - code - graphify/analyze.py
- [[graph_diff()]] - code - graphify/analyze.py
- [[graphifyanalyze.py]] - code - graphify/analyze.py
- [[make_graph()]] - code - tests/test_analyze.py
- [[npm package.json dep-block keys must be filtered from god_nodes output.      Con]] - rationale - tests/test_analyze.py
- [[parametrize_1]] - code
- [[surprising_connections()]] - code - graphify/analyze.py
- [[test_analyze.py]] - code - tests/test_analyze.py
- [[test_code_doc_extracted_calls_not_suppressed()]] - code - tests/test_analyze.py
- [[test_code_doc_inferred_calls_suppressed()]] - code - tests/test_analyze.py
- [[test_code_doc_inferred_semantically_similar_not_suppressed()]] - code - tests/test_analyze.py
- [[test_code_doc_inferred_uses_suppressed()]] - code - tests/test_analyze.py
- [[test_code_paper_inferred_calls_not_suppressed()]] - code - tests/test_analyze.py
- [[test_code_unknown_extension_inferred_calls_suppressed()]] - code - tests/test_analyze.py
- [[test_cross_language_extracted_calls_not_suppressed()]] - code - tests/test_analyze.py
- [[test_cross_language_inferred_calls_suppressed()]] - code - tests/test_analyze.py
- [[test_cross_language_inferred_uses_suppressed()]] - code - tests/test_analyze.py
- [[test_cross_language_semantically_similar_not_suppressed()]] - code - tests/test_analyze.py
- [[test_file_category()]] - code - tests/test_analyze.py
- [[test_find_import_cycles_detects_2_and_3_cycles()]] - code - tests/test_analyze.py
- [[test_find_import_cycles_empty_graph()]] - code - tests/test_analyze.py
- [[test_find_import_cycles_handles_undirected_graph_input()]] - code - tests/test_analyze.py
- [[test_find_import_cycles_ignores_non_import_relations()]] - code - tests/test_analyze.py
- [[test_find_import_cycles_includes_self_loop_cycle()]] - code - tests/test_analyze.py
- [[test_find_import_cycles_no_cycles()]] - code - tests/test_analyze.py
- [[test_find_import_cycles_respects_max_cycle_length()]] - code - tests/test_analyze.py
- [[test_find_import_cycles_returns_structured_records()]] - code - tests/test_analyze.py
- [[test_find_import_cycles_skips_nodes_without_source_file()]] - code - tests/test_analyze.py
- [[test_god_nodes_excludes_json_noise()]] - code - tests/test_analyze.py
- [[test_god_nodes_excludes_npm_dep_block_keys()]] - code - tests/test_analyze.py
- [[test_god_nodes_filter_is_case_insensitive()]] - code - tests/test_analyze.py
- [[test_god_nodes_have_required_keys()]] - code - tests/test_analyze.py
- [[test_god_nodes_returns_list()]] - code - tests/test_analyze.py
- [[test_god_nodes_sorted_by_degree()]] - code - tests/test_analyze.py
- [[test_graph_diff_empty_diff()]] - code - tests/test_analyze.py
- [[test_graph_diff_new_edges()]] - code - tests/test_analyze.py
- [[test_graph_diff_new_nodes()]] - code - tests/test_analyze.py
- [[test_graph_diff_removed_nodes()]] - code - tests/test_analyze.py
- [[test_is_concept_node_empty_source()]] - code - tests/test_analyze.py
- [[test_is_concept_node_real_file()]] - code - tests/test_analyze.py
- [[test_is_json_key_node_noise_label()]] - code - tests/test_analyze.py
- [[test_is_json_key_node_non_json_file()]] - code - tests/test_analyze.py
- [[test_is_json_key_node_real_label()]] - code - tests/test_analyze.py
- [[test_same_language_inferred_calls_not_suppressed()]] - code - tests/test_analyze.py
- [[test_suggest_questions_excludes_rationale_nodes_from_isolated_count()]] - code - tests/test_analyze.py
- [[test_surprise_score_accepts_precomputed_degrees()]] - code - tests/test_analyze.py
- [[test_surprising_connections_ambiguous_scores_higher_than_extracted()]] - code - tests/test_analyze.py
- [[test_surprising_connections_cross_source_multi_file()]] - code - tests/test_analyze.py
- [[test_surprising_connections_cross_type_scores_higher()]] - code - tests/test_analyze.py
- [[test_surprising_connections_excludes_concept_nodes()]] - code - tests/test_analyze.py
- [[test_surprising_connections_have_required_keys()]] - code - tests/test_analyze.py
- [[test_surprising_connections_have_why_field()]] - code - tests/test_analyze.py
- [[test_surprising_connections_single_file_uses_community_bridges()]] - code - tests/test_analyze.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_analyzepy
SORT file.name ASC
```

## Connections to other communities
- 22 edges to [[_COMMUNITY_generate]]
- 8 edges to [[_COMMUNITY__rebuild_code]]
- 8 edges to [[_COMMUNITY_test_export.py]]
- 5 edges to [[_COMMUNITY_export.py]]
- 5 edges to [[_COMMUNITY_build_from_json]]
- 5 edges to [[_COMMUNITY_test_pipeline.py]]
- 5 edges to [[_COMMUNITY_test_semantic_similarity.py]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 4 edges to [[_COMMUNITY_test_cli_export.py]]
- 4 edges to [[_COMMUNITY__run]]
- 3 edges to [[_COMMUNITY_test_swift_builtin_noise.py]]
- 3 edges to [[_COMMUNITY_test_reflect.py]]
- 2 edges to [[_COMMUNITY_graphifybuild.py]]
- 2 edges to [[_COMMUNITY_serve.py]]
- 2 edges to [[_COMMUNITY__build_server]]
- 2 edges to [[_COMMUNITY_test_cross_extension_reexport_self_cycle.py]]
- 2 edges to [[_COMMUNITY_test_js_import_resolution.py]]
- 1 edge to [[_COMMUNITY_test_file_label_disambiguation.py]]
- 1 edge to [[_COMMUNITY_test_cluster.py]]
- 1 edge to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY_graphifycluster.py]]
- 1 edge to [[_COMMUNITY_to_json]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY__write_raw_doc]]

## Top bridge nodes
- [[graphifyanalyze.py]] - degree 31, connects to 12 communities
- [[god_nodes()]] - degree 32, connects to 9 communities
- [[surprising_connections()]] - degree 28, connects to 9 communities
- [[_make_graph()_3]] - degree 13, connects to 7 communities
- [[test_analyze.py]] - degree 67, connects to 6 communities