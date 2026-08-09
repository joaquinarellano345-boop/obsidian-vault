---
type: community
cohesion: 0.12
members: 24
---

# serve.py

**Cohesion:** 0.12 - loosely connected
**Members:** 24 nodes

## Members
- [[.__call__()_1]] - code - graphify/serve.py
- [[.__init__()_7]] - code - graphify/serve.py
- [[A term matching only 1 of N nodes should get IDF  1.]] - rationale - tests/test_serve.py
- [[Concatenate every field _score_nodes  _find_node match a query against, so]] - rationale - graphify/serve.py
- [[IDF weights for query terms, cached in G.graph'_idf_cache'.      Common terms]] - rationale - graphify/serve.py
- [[NamedTuple]] - code
- [[Per-query scoring result, returned by the private `_score_query` helper.      `r]] - rationale - graphify/serve.py
- [[Pure-ASGI API-key gate for the HTTP transport.      Implemented as raw ASGI (not]] - rationale - graphify/serve.py
- [[Single-pass combined scorer that optionally also records the best seed     for e]] - rationale - graphify/serve.py
- [[_ApiKeyMiddleware]] - code - graphify/serve.py
- [[_QueryScores]] - code - graphify/serve.py
- [[_compute_idf()]] - code - graphify/serve.py
- [[_filter_graph_by_context()]] - code - graphify/serve.py
- [[_infer_context_filters()]] - code - graphify/serve.py
- [[_node_search_text()]] - code - graphify/serve.py
- [[_normalize_context_filters()]] - code - graphify/serve.py
- [[_resolve_context_filters()]] - code - graphify/serve.py
- [[_score_query()]] - code - graphify/serve.py
- [[_strip_diacritics()_1]] - code - graphify/serve.py
- [[serve.py]] - code - graphify/serve.py
- [[test_idf_rare_term_gets_high_weight()]] - code - tests/test_serve.py
- [[test_infer_context_filters_for_calls_question()]] - code - tests/test_serve.py
- [[test_query_graph_text_context_filter_aliases_resolve()]] - code - tests/test_serve.py
- [[test_resolve_context_filters_explicit_overrides_heuristic()]] - code - tests/test_serve.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/servepy
SORT file.name ASC
```

## Connections to other communities
- 23 edges to [[_COMMUNITY_test_serve.py]]
- 10 edges to [[_COMMUNITY__score_nodes]]
- 9 edges to [[_COMMUNITY__make_graph]]
- 7 edges to [[_COMMUNITY_bench_query_scoring.py]]
- 5 edges to [[_COMMUNITY_default_graph_json]]
- 4 edges to [[_COMMUNITY__build_server]]
- 4 edges to [[_COMMUNITY__query_terms]]
- 4 edges to [[_COMMUNITY__pick_seeds]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_graphifybuild.py]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_test_serve_http.py]]
- 1 edge to [[_COMMUNITY_generate]]
- 1 edge to [[_COMMUNITY_test_analyze.py]]
- 1 edge to [[_COMMUNITY_test_benchmark.py]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY__parse_ci]]
- 1 edge to [[_COMMUNITY_attach_graph_impact]]
- 1 edge to [[_COMMUNITY_compute_pr_impact]]
- 1 edge to [[_COMMUNITY_test_prs.py]]
- 1 edge to [[_COMMUNITY_fetch_worktrees]]
- 1 edge to [[_COMMUNITY_test_querylog.py]]
- 1 edge to [[_COMMUNITY_reflect.py]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_test_security.py]]
- 1 edge to [[_COMMUNITY_sanitize_label]]
- 1 edge to [[_COMMUNITY__load_graph]]
- 1 edge to [[_COMMUNITY__MCPASGIApp]]
- 1 edge to [[_COMMUNITY_Graph]]

## Top bridge nodes
- [[serve.py]] - degree 63, connects to 28 communities
- [[_score_query()]] - degree 22, connects to 5 communities
- [[_compute_idf()]] - degree 8, connects to 3 communities
- [[_strip_diacritics()_1]] - degree 8, connects to 2 communities
- [[_node_search_text()]] - degree 7, connects to 2 communities