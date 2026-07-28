---
type: community
cohesion: 0.33
members: 6
---

# _make_noisy_graph

**Cohesion:** 0.33 - loosely connected
**Members:** 6 nodes

## Members
- [[20 error-handler nodes + 1 rare identifier FooBarService.]] - rationale - tests/test_serve.py
- [[FooBarService error handling' should expand from FooBarService,     not from err]] - rationale - tests/test_serve.py
- [[_make_noisy_graph()]] - code - tests/test_serve.py
- [[error' matches 20 nodes, 'foobarservice' matches 1 — IDF should make     FooBarS]] - rationale - tests/test_serve.py
- [[test_idf_downweights_common_terms()]] - code - tests/test_serve.py
- [[test_query_seeds_from_identifier_not_noise()]] - code - tests/test_serve.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_make_noisy_graph
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_test_serve.py]]
- 1 edge to [[_COMMUNITY__score_nodes]]
- 1 edge to [[_COMMUNITY__make_graph]]
- 1 edge to [[_COMMUNITY_Graph]]

## Top bridge nodes
- [[_make_noisy_graph()]] - degree 5, connects to 2 communities
- [[test_idf_downweights_common_terms()]] - degree 4, connects to 2 communities
- [[test_query_seeds_from_identifier_not_noise()]] - degree 4, connects to 2 communities