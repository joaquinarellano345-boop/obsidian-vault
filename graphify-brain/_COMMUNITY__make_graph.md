---
type: community
cohesion: 0.08
members: 38
---

# _make_graph

**Cohesion:** 0.08 - loosely connected
**Members:** 38 nodes

## Members
- [[A high-degree hub plus a low-degree answer node, to force the answer past     a]] - rationale - tests/test_serve.py
- [[An annotated node gets a `learning=status` suffix inside its NODE     bracket;]] - rationale - tests/test_serve.py
- [[BUG2 regression guard the query path must pass seeds to the renderer (a     bra]] - rationale - tests/test_serve.py
- [[BUG2 a low-degree answer node passed as a seed is rendered first and     surviv]] - rationale - tests/test_serve.py
- [[Render subgraph as text, cutting at token_budget (approx 3 charstoken).      se]] - rationale - graphify/serve.py
- [[The learning= suffix is part of the NODE line BEFORE the budget cut, so it     i]] - rationale - tests/test_serve.py
- [[Truncation message must tell Claude what to do, not just say truncated.]] - rationale - tests/test_serve.py
- [[With no overlay on the graph, NODE lines carry no learning= suffix.]] - rationale - tests/test_serve.py
- [[_bfs()]] - code - graphify/serve.py
- [[_dfs()]] - code - graphify/serve.py
- [[_make_graph()_4]] - code - tests/test_serve.py
- [[_query_graph_text()]] - code - graphify/serve.py
- [[_star_graph()]] - code - tests/test_serve.py
- [[_subgraph_to_text()]] - code - graphify/serve.py
- [[test_bfs_depth_1()]] - code - tests/test_serve.py
- [[test_bfs_depth_2()]] - code - tests/test_serve.py
- [[test_bfs_disconnected()]] - code - tests/test_serve.py
- [[test_bfs_returns_edges()]] - code - tests/test_serve.py
- [[test_dfs_depth_1()]] - code - tests/test_serve.py
- [[test_dfs_full_chain()]] - code - tests/test_serve.py
- [[test_filter_graph_by_context_limits_traversal()]] - code - tests/test_serve.py
- [[test_query_graph_text_explicit_context_filter_changes_traversal()]] - code - tests/test_serve.py
- [[test_query_graph_text_heuristic_context_filter_changes_traversal()]] - code - tests/test_serve.py
- [[test_query_graph_text_keeps_short_non_english_terms()]] - code - tests/test_serve.py
- [[test_query_graph_text_parameter_type_context_filter_changes_traversal()]] - code - tests/test_serve.py
- [[test_query_graph_text_passes_seeds_so_answer_survives()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_annotates_node_with_learning_status()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_contains_labels()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_edge_included()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_includes_edge_context()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_learning_suffix_counts_against_budget()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_marks_stale_status()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_no_notice_when_under_budget()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_no_overlay_is_unchanged()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_seed_survives_truncation()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_truncates()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_truncation_hint_is_actionable()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_truncation_notice_at_top()]] - code - tests/test_serve.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_make_graph
SORT file.name ASC
```

## Connections to other communities
- 33 edges to [[_COMMUNITY_test_serve.py]]
- 9 edges to [[_COMMUNITY_serve.py]]
- 8 edges to [[_COMMUNITY_Graph]]
- 8 edges to [[_COMMUNITY__score_nodes]]
- 3 edges to [[_COMMUNITY__load_graph]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 1 edge to [[_COMMUNITY_sanitize_label]]
- 1 edge to [[_COMMUNITY__query_terms]]
- 1 edge to [[_COMMUNITY__pick_seeds]]
- 1 edge to [[_COMMUNITY__make_noisy_graph]]

## Top bridge nodes
- [[_query_graph_text()]] - degree 20, connects to 8 communities
- [[_make_graph()_4]] - degree 35, connects to 5 communities
- [[_subgraph_to_text()]] - degree 20, connects to 4 communities
- [[_bfs()]] - degree 8, connects to 2 communities
- [[_star_graph()]] - degree 6, connects to 2 communities