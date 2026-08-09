---
type: community
cohesion: 0.11
members: 28
---

# Graph

**Cohesion:** 0.11 - loosely connected
**Members:** 28 nodes

## Members
- [[2080 review a straydangling _src_tgt on an edge (hand-edited or     adversar]] - rationale - tests/test_serve.py
- [[2080 a valid _src_tgt (the stored direction) is honored even when the     tra]] - rationale - tests/test_serve.py
- [[.add_edge()]] - code - tests/fixtures/sample.rs
- [[.add_node()]] - code - tests/fixtures/sample.rs
- [[.build()_3]] - code - tests/fixtures/sample.rs
- [[.new()]] - code - tests/fixtures/sample.rs
- [[A term matching most nodes should get IDF  1.]] - rationale - tests/test_serve.py
- [[DataProcessor_6]] - code - tests/fixtures/sample.rs
- [[Equal-degree nodes render in a stable order regardless of set iteration.]] - rationale - tests/test_serve.py
- [[Full pipeline '页面路由' should find nodes with '路由' in label.]] - rationale - tests/test_serve.py
- [[Graph]] - code - tests/fixtures/sample.rs
- [[GraphEvent]] - code - tests/fixtures/sample.rs
- [[GraphPair]] - code - tests/fixtures/sample.rs
- [[HashMap]] - code
- [[Logger_3]] - code - tests/fixtures/sample.rs
- [[Processor_3]] - code - tests/fixtures/sample.rs
- [[Result_5]] - code - tests/fixtures/sample.rs
- [[Self]] - code
- [[String_3]] - code
- [[T_2]] - code
- [[Vec]] - code
- [[build_graph()]] - code - tests/fixtures/sample.rs
- [[sample.rs]] - code - tests/fixtures/sample.rs
- [[test_idf_common_term_gets_low_weight()]] - code - tests/test_serve.py
- [[test_query_text_chinese_finds_routing_nodes()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_honors_valid_src_tgt_direction()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_ignores_dangling_src_tgt()]] - code - tests/test_serve.py
- [[test_subgraph_to_text_order_is_deterministic()]] - code - tests/test_serve.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Graph
SORT file.name ASC
```

## Connections to other communities
- 10 edges to [[_COMMUNITY_test_serve.py]]
- 8 edges to [[_COMMUNITY__make_graph]]
- 3 edges to [[_COMMUNITY_test_benchmark.py]]
- 3 edges to [[_COMMUNITY_compute_pr_impact]]
- 3 edges to [[_COMMUNITY__score_nodes]]
- 1 edge to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY_graphifycluster.py]]
- 1 edge to [[_COMMUNITY_test_export.py]]
- 1 edge to [[_COMMUNITY_test_global_graph.py]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__make_noisy_graph]]
- 1 edge to [[_COMMUNITY_validate_extraction]]
- 1 edge to [[_COMMUNITY_rawanalyze.py]]

## Top bridge nodes
- [[Graph]] - degree 40, connects to 12 communities
- [[test_idf_common_term_gets_low_weight()]] - degree 4, connects to 2 communities
- [[test_query_text_chinese_finds_routing_nodes()]] - degree 4, connects to 2 communities
- [[test_subgraph_to_text_honors_valid_src_tgt_direction()]] - degree 4, connects to 2 communities
- [[test_subgraph_to_text_ignores_dangling_src_tgt()]] - degree 4, connects to 2 communities