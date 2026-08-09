---
type: community
cohesion: 0.07
members: 37
---

# _score_nodes

**Cohesion:** 0.07 - loosely connected
**Members:** 37 nodes

## Members
- [[A lone generic-word exact match must not bury a multi-term match.      Reproduce]] - rationale - tests/test_serve.py
- [[A multi-word query equal to a whole label must resolve uniquely.      Regression]] - rationale - tests/test_serve.py
- [[Across many deterministic random graphs and many random multi-term     queries,]] - rationale - tests/test_serve.py
- [[Combined query scorer returning the existing ranked `(score, node_id)` list.]] - rationale - graphify/serve.py
- [[Coverage scaling must not touch full-coverage queries (coverage == 1).      A si]] - rationale - tests/test_serve.py
- [[IDF results are stored in G.graph so repeated queries don't recompute.]] - rationale - tests/test_serve.py
- [[Per-token winner the single-pass scorer records matches the legacy     `_score_n]] - rationale - tests/test_serve.py
- [[Reproducible broad-match DiGraph short constructed labels + edge noise.      La_1]] - rationale - tests/test_serve.py
- [[Searching for '路由' should match a node with label containing '路由'.]] - rationale - tests/test_serve.py
- [[Test-only oracle for the legacy per-term `_pick_seeds(terms=...)` loop.      Re-]] - rationale - tests/test_serve.py
- [[The seeds produced by `_pick_seeds(qs.ranked, G=G, best_seed_by_term=     qs.bes]] - rationale - tests/test_serve.py
- [[Two separate graph instances must not share an IDF cache.]] - rationale - tests/test_serve.py
- [[When the trigram prefilter falls back to a full-graph scan, the     single-pass]] - rationale - tests/test_serve.py
- [[_make_random_scoring_graph()]] - code - tests/test_serve.py
- [[_reference_best_seed_by_term()]] - code - tests/test_serve.py
- [[_score_nodes()]] - code - graphify/serve.py
- [[`_query_graph_text` must invoke `_score_query` exactly once per query,     regar]] - rationale - tests/test_serve.py
- [[`_score_query(..., collect_per_term_seeds=False).ranked` is the byte-for-     by]] - rationale - tests/test_serve.py
- [[`collect_per_term_seeds=False` returns empty `best_seed_by_term` and     does no]] - rationale - tests/test_serve.py
- [[parametrize_22]] - code
- [[test_idf_cached_on_graph()]] - code - tests/test_serve.py
- [[test_idf_new_graph_starts_fresh()]] - code - tests/test_serve.py
- [[test_pick_seeds_with_optimized_best_seed_matches_legacy_semantics()]] - code - tests/test_serve.py
- [[test_query_graph_text_makes_exactly_one_score_query_call()]] - code - tests/test_serve.py
- [[test_score_nodes_chinese_substring_match()]] - code - tests/test_serve.py
- [[test_score_nodes_coverage_full_coverage_query_is_unchanged()]] - code - tests/test_serve.py
- [[test_score_nodes_coverage_lone_generic_exact_hit_loses_to_multi_term_match()]] - code - tests/test_serve.py
- [[test_score_nodes_exact_label_match()]] - code - tests/test_serve.py
- [[test_score_nodes_ignores_trailing_punctuation()]] - code - tests/test_serve.py
- [[test_score_nodes_multiword_exact_label_outranks_superset()]] - code - tests/test_serve.py
- [[test_score_nodes_no_match()]] - code - tests/test_serve.py
- [[test_score_nodes_source_file_partial()]] - code - tests/test_serve.py
- [[test_score_query_best_seed_by_term_matches_legacy_singleton_scoring()]] - code - tests/test_serve.py
- [[test_score_query_collect_per_term_seeds_false_omits_tracking()]] - code - tests/test_serve.py
- [[test_score_query_matches_legacy_across_random_deterministic_graphs()]] - code - tests/test_serve.py
- [[test_score_query_matches_legacy_under_full_scan_fallback()]] - code - tests/test_serve.py
- [[test_score_query_ranked_matches_score_nodes_byte_identical()]] - code - tests/test_serve.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_score_nodes
SORT file.name ASC
```

## Connections to other communities
- 21 edges to [[_COMMUNITY_test_serve.py]]
- 10 edges to [[_COMMUNITY_serve.py]]
- 8 edges to [[_COMMUNITY__make_graph]]
- 4 edges to [[_COMMUNITY_bench_query_scoring.py]]
- 4 edges to [[_COMMUNITY__pick_seeds]]
- 3 edges to [[_COMMUNITY_Graph]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 1 edge to [[_COMMUNITY__make_noisy_graph]]

## Top bridge nodes
- [[_score_nodes()]] - degree 28, connects to 6 communities
- [[test_pick_seeds_with_optimized_best_seed_matches_legacy_semantics()]] - degree 7, connects to 3 communities
- [[test_score_query_matches_legacy_across_random_deterministic_graphs()]] - degree 7, connects to 3 communities
- [[test_query_graph_text_makes_exactly_one_score_query_call()]] - degree 6, connects to 3 communities
- [[test_score_nodes_coverage_full_coverage_query_is_unchanged()]] - degree 5, connects to 3 communities