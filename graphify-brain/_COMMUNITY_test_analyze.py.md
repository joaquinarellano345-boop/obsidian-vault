---
type: community
cohesion: 0.07
members: 55
---

# test_analyze.py

**Cohesion:** 0.07 - loosely connected
**Members:** 55 nodes

## Members
- [[Compare two graph snapshots and return what changed.      Returns         {]] - rationale - graphify/analyze.py
- [[Concept nodes (empty source_file) must not appear in surprises.]] - rationale - tests/test_analyze.py
- [[Create a graph node resembling real graphify schema.]] - rationale - tests/test_analyze.py
- [[Detect circular import dependencies at the file level.      Collapses symbol-lev]] - rationale - graphify/analyze.py
- [[DiGraph_1]] - code
- [[Find connections that are genuinely surprising - not obvious from file structure]] - rationale - graphify/analyze.py
- [[Helper build a small nx.Graph from nodeedge specs.]] - rationale - tests/test_analyze.py
- [[JSON-key filter must match regardless of label casing.]] - rationale - tests/test_analyze.py
- [[Multi-file graph should find cross-file edges between real entities.]] - rationale - tests/test_analyze.py
- [[Single-file graph should return cross-community edges, not empty list.]] - rationale - tests/test_analyze.py
- [[Tests for analyze.py.]] - rationale - tests/test_analyze.py
- [[_file_category falls back to 'doc' for unknown extensions, so INFERRED     calls]] - rationale - tests/test_analyze.py
- [[_file_category()]] - code - graphify/analyze.py
- [[_is_json_key_node()]] - code - graphify/analyze.py
- [[_make_cycle_graph_directed()]] - code - tests/test_analyze.py
- [[_make_file_node()]] - code - tests/test_analyze.py
- [[_make_simple_graph()]] - code - tests/test_analyze.py
- [[find_import_cycles()]] - code - graphify/analyze.py
- [[god_nodes must not return generic JSON key nodes like 'name' or 'id'.]] - rationale - tests/test_analyze.py
- [[graph_diff()]] - code - graphify/analyze.py
- [[make_graph()]] - code - tests/test_analyze.py
- [[npm package.json dep-block keys must be filtered from god_nodes output.      Con]] - rationale - tests/test_analyze.py
- [[parametrize_1]] - code
- [[surprising_connections()]] - code - graphify/analyze.py
- [[test_analyze.py]] - code - tests/test_analyze.py
- [[test_code_unknown_extension_inferred_calls_suppressed()]] - code - tests/test_analyze.py
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
- [[test_is_json_key_node_noise_label()]] - code - tests/test_analyze.py
- [[test_is_json_key_node_non_json_file()]] - code - tests/test_analyze.py
- [[test_is_json_key_node_real_label()]] - code - tests/test_analyze.py
- [[test_suggest_questions_excludes_rationale_nodes_from_isolated_count()]] - code - tests/test_analyze.py
- [[test_surprising_connections_cross_source_multi_file()]] - code - tests/test_analyze.py
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
- 19 edges to [[_COMMUNITY__surprise_score]]
- 16 edges to [[_COMMUNITY_generate]]
- 11 edges to [[_COMMUNITY_export.py]]
- 6 edges to [[_COMMUNITY_cli.py]]
- 6 edges to [[_COMMUNITY_test_export.py]]
- 2 edges to [[_COMMUNITY_test_cli_export.py]]
- 2 edges to [[_COMMUNITY_to_json]]
- 2 edges to [[_COMMUNITY_test_cross_extension_reexport_self_cycle.py]]
- 2 edges to [[_COMMUNITY_test_js_import_resolution.py]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__build_server]]
- 1 edge to [[_COMMUNITY_test_reflect.py]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_graphifycluster.py]]
- 1 edge to [[_COMMUNITY_extract.py]]

## Top bridge nodes
- [[test_analyze.py]] - degree 67, connects to 9 communities
- [[surprising_connections()]] - degree 28, connects to 9 communities
- [[find_import_cycles()]] - degree 18, connects to 4 communities
- [[_is_json_key_node()]] - degree 6, connects to 2 communities
- [[_file_category()]] - degree 5, connects to 2 communities