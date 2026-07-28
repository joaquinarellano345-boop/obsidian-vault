---
type: community
cohesion: 0.11
members: 44
---

# test_benchmark.py

**Cohesion:** 0.11 - loosely connected
**Members:** 44 nodes

## Members
- [[2212 run_benchmark must accept a raw --no-cluster graph.json.  The clustered w]] - rationale - tests/test_benchmark_raw_graph.py
- [[F4 run_benchmark must refuse to read a graph.json that exceeds     the size ca]] - rationale - tests/test_benchmark.py
- [[A --no-cluster graph.json (edges key) must not raise KeyError.]] - rationale - tests/test_benchmark_raw_graph.py
- [[Both spellings of the same graph must produce the same stats.]] - rationale - tests/test_benchmark_raw_graph.py
- [[Horizontal rule that survives non-UTF-8 stdout (e.g. Windows cp1252 console).]] - rationale - graphify/benchmark.py
- [[Measure token reduction corpus tokens vs graphify query tokens.      Args]] - rationale - graphify/benchmark.py
- [[Print a human-readable benchmark report.]] - rationale - graphify/benchmark.py
- [[Regression U+2500  U+2192 used to crash with UnicodeEncodeError on cp1252.]] - rationale - tests/test_benchmark.py
- [[Return unicode_char if stdout can encode it, else ascii_fallback.      Windows c]] - rationale - graphify/benchmark.py
- [[Run BFS from best-matching nodes and return estimated tokens in the subgraph con]] - rationale - graphify/benchmark.py
- [[Tests for graphifybenchmark.py.]] - rationale - tests/test_benchmark.py
- [[The clustered writer's links key keeps working identically.]] - rationale - tests/test_benchmark_raw_graph.py
- [[Token-reduction benchmark - measures how much context graphify saves vs naive fu]] - rationale - graphify/benchmark.py
- [[_estimate_tokens()]] - code - graphify/benchmark.py
- [[_graph_payload()]] - code - tests/test_benchmark_raw_graph.py
- [[_hr()]] - code - graphify/benchmark.py
- [[_make_graph()]] - code - tests/test_benchmark.py
- [[_query_subgraph_tokens()]] - code - graphify/benchmark.py
- [[_safe()]] - code - graphify/benchmark.py
- [[_write_graph()_1]] - code - tests/test_benchmark.py
- [[benchmark.py]] - code - graphify/benchmark.py
- [[print_benchmark()]] - code - graphify/benchmark.py
- [[run_benchmark()]] - code - graphify/benchmark.py
- [[test_benchmark.py]] - code - tests/test_benchmark.py
- [[test_benchmark_raw_graph.py]] - code - tests/test_benchmark_raw_graph.py
- [[test_print_benchmark_error_message()]] - code - tests/test_benchmark.py
- [[test_print_benchmark_no_crash()]] - code - tests/test_benchmark.py
- [[test_print_benchmark_survives_cp1252_stdout()]] - code - tests/test_benchmark.py
- [[test_query_bfs_expands_neighbors()]] - code - tests/test_benchmark.py
- [[test_query_keeps_short_non_english_terms()]] - code - tests/test_benchmark.py
- [[test_query_returns_positive_for_matching_question()]] - code - tests/test_benchmark.py
- [[test_query_returns_zero_for_no_match()]] - code - tests/test_benchmark.py
- [[test_raw_and_links_graphs_benchmark_identically()]] - code - tests/test_benchmark_raw_graph.py
- [[test_run_benchmark_corpus_tokens_proportional()]] - code - tests/test_benchmark.py
- [[test_run_benchmark_error_on_empty_graph()]] - code - tests/test_benchmark.py
- [[test_run_benchmark_estimates_corpus_if_no_words()]] - code - tests/test_benchmark.py
- [[test_run_benchmark_includes_node_edge_counts()]] - code - tests/test_benchmark.py
- [[test_run_benchmark_links_keyed_graph()]] - code - tests/test_benchmark_raw_graph.py
- [[test_run_benchmark_per_question_list()]] - code - tests/test_benchmark.py
- [[test_run_benchmark_raw_edges_keyed_graph()]] - code - tests/test_benchmark_raw_graph.py
- [[test_run_benchmark_rejects_oversized_graph()]] - code - tests/test_benchmark.py
- [[test_run_benchmark_returns_reduction()]] - code - tests/test_benchmark.py
- [[test_safe_falls_back_when_unencodable()]] - code - tests/test_benchmark.py
- [[test_safe_returns_unicode_when_encodable()]] - code - tests/test_benchmark.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_benchmarkpy
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_cli.py]]
- 3 edges to [[_COMMUNITY_Graph]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_default_graph_json]]
- 2 edges to [[_COMMUNITY__query_terms]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_serve.py]]

## Top bridge nodes
- [[benchmark.py]] - degree 16, connects to 7 communities
- [[run_benchmark()]] - degree 21, connects to 2 communities
- [[_query_subgraph_tokens()]] - degree 11, connects to 2 communities
- [[_make_graph()]] - degree 13, connects to 1 community
- [[print_benchmark()]] - degree 10, connects to 1 community