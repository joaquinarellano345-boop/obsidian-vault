---
type: community
cohesion: 0.10
members: 23
---

# _pick_seeds

**Cohesion:** 0.10 - loosely connected
**Members:** 23 nodes

## Members
- [[DiGraph_2]] - code
- [[End-to-end for 1900 a German question over a graph with German     heading-noi]] - rationale - tests/test_serve.py
- [[FooBarService at 1000 vs error nodes at 1.0 → only 1 seed chosen.]] - rationale - tests/test_serve.py
- [[Gbest_seed_by_term are optional and default to None existing callers     see i]] - rationale - tests/test_serve.py
- [[Many nodes sharing one generic label (e.g. framework `GET` handlers)     must co]] - rationale - tests/test_serve.py
- [[Never return more than max_k seeds even when all scores are close.]] - rationale - tests/test_serve.py
- [[Reproduces 1445 a vague natural-language query where one term's     incidental]] - rationale - tests/test_serve.py
- [[Select BFS seed nodes, stopping when score drops too far below the top.      Pre]] - rationale - graphify/serve.py
- [[The per-term guarantee loop must honor the same per-label cap, so it can't     a]] - rationale - tests/test_serve.py
- [[When all scores are within 20% of the top, keep up to 3 seeds.]] - rationale - tests/test_serve.py
- [[_pick_seeds()]] - code - graphify/serve.py
- [[`GET``Get``get` are the same generic label and must dedup together.]] - rationale - tests/test_serve.py
- [[test_pick_seeds_close_scores_keeps_multiple()]] - code - tests/test_serve.py
- [[test_pick_seeds_dedup_key_is_case_and_diacritic_normalized()]] - code - tests/test_serve.py
- [[test_pick_seeds_dedups_homonymous_generic_labels()]] - code - tests/test_serve.py
- [[test_pick_seeds_diversity_recovers_starved_term()]] - code - tests/test_serve.py
- [[test_pick_seeds_dominant_identifier_gives_one_seed()]] - code - tests/test_serve.py
- [[test_pick_seeds_empty()]] - code - tests/test_serve.py
- [[test_pick_seeds_german_query_seeds_content_node_not_heading_noise()]] - code - tests/test_serve.py
- [[test_pick_seeds_per_term_guarantee_does_not_reintroduce_generic_dupe()]] - code - tests/test_serve.py
- [[test_pick_seeds_respects_max_k()]] - code - tests/test_serve.py
- [[test_pick_seeds_single()]] - code - tests/test_serve.py
- [[test_pick_seeds_without_diversity_args_is_unchanged()]] - code - tests/test_serve.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_pick_seeds
SORT file.name ASC
```

## Connections to other communities
- 12 edges to [[_COMMUNITY_test_serve.py]]
- 4 edges to [[_COMMUNITY_serve.py]]
- 4 edges to [[_COMMUNITY__score_nodes]]
- 3 edges to [[_COMMUNITY_bench_query_scoring.py]]
- 1 edge to [[_COMMUNITY__query_terms]]
- 1 edge to [[_COMMUNITY__make_graph]]
- 1 edge to [[_COMMUNITY__load_graph]]

## Top bridge nodes
- [[_pick_seeds()]] - degree 20, connects to 5 communities
- [[test_pick_seeds_german_query_seeds_content_node_not_heading_noise()]] - degree 6, connects to 3 communities
- [[DiGraph_2]] - degree 8, connects to 2 communities
- [[test_pick_seeds_diversity_recovers_starved_term()]] - degree 5, connects to 2 communities
- [[test_pick_seeds_per_term_guarantee_does_not_reintroduce_generic_dupe()]] - degree 5, connects to 2 communities