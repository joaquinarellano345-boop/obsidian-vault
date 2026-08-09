---
type: community
cohesion: 0.09
members: 48
---

# test_cli_export.py

**Cohesion:** 0.09 - loosely connected
**Members:** 48 nodes

## Members
- [[1423 `graphify extract` honours GRAPHIFY_OUT for where it WRITES, not only]] - rationale - tests/test_cli_export.py
- [[1747 Case 1 `extract corpus --out elsewhere` must not leave a stray     gr]] - rationale - tests/test_cli_export.py
- [[1747 Case 2 `cluster-only --graph elsewheregraphify-outgraph.json`     mus]] - rationale - tests/test_cli_export.py
- [[Build a minimal graph.json + analysislabels files in tmp_pathgraphify-out.]] - rationale - tests/test_cli_export.py
- [[CompletedProcess]] - code
- [[If a graph.json was somehow written without any per-node `community`     attribu]] - rationale - tests/test_cli_export.py
- [[Integration tests for graphify export subcommands and CLI commands.  Each test b]] - rationale - tests/test_cli_export.py
- [[Path_64]] - code
- [[Stronger assertion the reconstructed `communities` dict should have the     SAM]] - rationale - tests/test_cli_export.py
- [[When .graphify_analysis.json is absent, export html should reconstruct     commu]] - rationale - tests/test_cli_export.py
- [[_make_graph()_1]] - code - tests/test_cli_export.py
- [[_run()_1]] - code - tests/test_cli_export.py
- [[cluster-only must invoke remap_communities_to_previous so the existing     .grap]] - rationale - tests/test_cli_export.py
- [[cluster-only must not crash with FileNotFoundError when graphify-out is absent]] - rationale - tests/test_cli_export.py
- [[cluster-only must refresh .graphify_analysis.json alongside graph.json.      Dow]] - rationale - tests/test_cli_export.py
- [[test_cli_export.py]] - code - tests/test_cli_export.py
- [[test_cluster_only_creates_output_dir_when_missing()]] - code - tests/test_cli_export.py
- [[test_cluster_only_graph_in_graphify_out_writes_beside_it()]] - code - tests/test_cli_export.py
- [[test_cluster_only_persists_analysis_sidecar()]] - code - tests/test_cli_export.py
- [[test_cluster_only_remaps_labels_to_previous_cids()]] - code - tests/test_cli_export.py
- [[test_explain_missing_graph_fails()]] - code - tests/test_cli_export.py
- [[test_explain_runs_without_error()]] - code - tests/test_cli_export.py
- [[test_explain_uses_graphify_out_env()]] - code - tests/test_cli_export.py
- [[test_export_falkordb_creates_cypher()]] - code - tests/test_cli_export.py
- [[test_export_graphml_creates_file()]] - code - tests/test_cli_export.py
- [[test_export_html_creates_file()]] - code - tests/test_cli_export.py
- [[test_export_html_error_without_graph()]] - code - tests/test_cli_export.py
- [[test_export_html_fallback_recovers_multiple_communities()]] - code - tests/test_cli_export.py
- [[test_export_html_falls_back_to_node_community_attribute()]] - code - tests/test_cli_export.py
- [[test_export_html_no_community_data_at_all_still_succeeds()]] - code - tests/test_cli_export.py
- [[test_export_html_no_viz_removes_file()]] - code - tests/test_cli_export.py
- [[test_export_neo4j_creates_cypher()]] - code - tests/test_cli_export.py
- [[test_export_obsidian_creates_vault()]] - code - tests/test_cli_export.py
- [[test_export_obsidian_custom_dir()]] - code - tests/test_cli_export.py
- [[test_export_unknown_format_fails()]] - code - tests/test_cli_export.py
- [[test_export_wiki_accepts_edges_only_graph_json()]] - code - tests/test_cli_export.py
- [[test_export_wiki_creates_articles()]] - code - tests/test_cli_export.py
- [[test_extract_out_does_not_pollute_corpus()]] - code - tests/test_cli_export.py
- [[test_extract_writes_to_graphify_out_env()]] - code - tests/test_cli_export.py
- [[test_path_missing_graph_fails()]] - code - tests/test_cli_export.py
- [[test_path_runs_without_error()]] - code - tests/test_cli_export.py
- [[test_path_uses_graphify_out_env()]] - code - tests/test_cli_export.py
- [[test_query_budget_flag()]] - code - tests/test_cli_export.py
- [[test_query_dfs_flag()]] - code - tests/test_cli_export.py
- [[test_query_missing_graph_fails()]] - code - tests/test_cli_export.py
- [[test_query_returns_output()]] - code - tests/test_cli_export.py
- [[test_query_uses_graphify_out_env()]] - code - tests/test_cli_export.py
- [[test_update_no_cluster_writes_raw_graph()]] - code - tests/test_cli_export.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_cli_exportpy
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_generate]]
- 2 edges to [[_COMMUNITY_test_analyze.py]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_test_export.py]]
- 2 edges to [[_COMMUNITY_to_json]]
- 1 edge to [[_COMMUNITY_test_indirect_dispatch.py]]

## Top bridge nodes
- [[test_cli_export.py]] - degree 42, connects to 6 communities
- [[_make_graph()_1]] - degree 33, connects to 5 communities