---
type: community
cohesion: 0.22
members: 13
---

# test_query_cli.py

**Cohesion:** 0.22 - loosely connected
**Members:** 13 nodes

## Members
- [[F4 query CLI must refuse to parse a graph.json that exceeds the cap.]] - rationale - tests/test_query_cli.py
- [[A single directed `calls` edge on an (on-disk) undirected graph.json,      the s]] - rationale - tests/test_query_cli.py
- [[Same edge, seeded from the caller side — must stay correct too.]] - rationale - tests/test_query_cli.py
- [[Tests for graphify query CLI context filtering.]] - rationale - tests/test_query_cli.py
- [[_write_calls_graph()]] - code - tests/test_query_cli.py
- [[_write_graph()_6]] - code - tests/test_query_cli.py
- [[`graphify query` must render `calls` edges caller-callee regardless of     whic]] - rationale - tests/test_query_cli.py
- [[test_query_cli.py]] - code - tests/test_query_cli.py
- [[test_query_cli_explicit_context_filter()]] - code - tests/test_query_cli.py
- [[test_query_cli_heuristic_context_filter()]] - code - tests/test_query_cli.py
- [[test_query_cli_preserves_calls_direction_when_seeded_on_callee()]] - code - tests/test_query_cli.py
- [[test_query_cli_preserves_calls_direction_when_seeded_on_caller()]] - code - tests/test_query_cli.py
- [[test_query_cli_rejects_oversized_graph()]] - code - tests/test_query_cli.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_query_clipy
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_main]]
- 1 edge to [[_COMMUNITY_graphify__main__.py]]

## Top bridge nodes
- [[test_query_cli.py]] - degree 9, connects to 1 community
- [[test_query_cli_preserves_calls_direction_when_seeded_on_callee()]] - degree 4, connects to 1 community
- [[test_query_cli_preserves_calls_direction_when_seeded_on_caller()]] - degree 4, connects to 1 community
- [[test_query_cli_rejects_oversized_graph()]] - degree 4, connects to 1 community
- [[test_query_cli_explicit_context_filter()]] - degree 3, connects to 1 community