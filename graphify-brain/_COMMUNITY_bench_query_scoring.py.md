---
type: community
cohesion: 0.19
members: 20
---

# bench_query_scoring.py

**Cohesion:** 0.19 - loosely connected
**Members:** 20 nodes

## Members
- [[DiGraph]] - code
- [[Light wrapper that just builds a NetworkX graph from a real     `graphify-outgr]] - rationale - tests/bench_query_scoring.py
- [[Pre-populate the trigram index and IDF cache so the first timed     iteration do]] - rationale - tests/bench_query_scoring.py
- [[Recreates the pre-refactor flow combined scoring plus one     `_score_nodes(to]] - rationale - tests/bench_query_scoring.py
- [[Reproducible broad-match DiGraph short constructed labels + edge noise.      La]] - rationale - tests/bench_query_scoring.py
- [[Split text into word tokens, stripping punctuation and diacritics.]] - rationale - graphify/serve.py
- [[_bench()]] - code - tests/bench_query_scoring.py
- [[_build_random_graph()]] - code - tests/bench_query_scoring.py
- [[_legacy_score_and_pick()]] - code - tests/bench_query_scoring.py
- [[_legacy_traversal_count()]] - code - tests/bench_query_scoring.py
- [[_load_real_graph()]] - code - tests/bench_query_scoring.py
- [[_optimized_score_and_pick()]] - code - tests/bench_query_scoring.py
- [[_resolve_scenarios()]] - code - tests/bench_query_scoring.py
- [[_row()]] - code - tests/bench_query_scoring.py
- [[_run_scenario()]] - code - tests/bench_query_scoring.py
- [[_search_tokens()]] - code - graphify/serve.py
- [[_verify_equality()]] - code - tests/bench_query_scoring.py
- [[_warm_caches()]] - code - tests/bench_query_scoring.py
- [[bench_query_scoring.py]] - code - tests/bench_query_scoring.py
- [[main()_3]] - code - tests/bench_query_scoring.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/bench_query_scoringpy
SORT file.name ASC
```

## Connections to other communities
- 7 edges to [[_COMMUNITY_serve.py]]
- 4 edges to [[_COMMUNITY_test_serve.py]]
- 4 edges to [[_COMMUNITY__score_nodes]]
- 3 edges to [[_COMMUNITY__pick_seeds]]
- 2 edges to [[_COMMUNITY__query_terms]]
- 1 edge to [[_COMMUNITY_cli.py]]

## Top bridge nodes
- [[bench_query_scoring.py]] - degree 19, connects to 5 communities
- [[_search_tokens()]] - degree 15, connects to 4 communities
- [[_legacy_score_and_pick()]] - degree 7, connects to 2 communities
- [[_warm_caches()]] - degree 6, connects to 2 communities
- [[_optimized_score_and_pick()]] - degree 5, connects to 2 communities