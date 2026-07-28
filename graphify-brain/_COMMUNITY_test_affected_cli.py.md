---
type: community
cohesion: 0.12
members: 25
---

# test_affected_cli.py

**Cohesion:** 0.12 - loosely connected
**Members:** 25 nodes

## Members
- [[A caller whose call site (L158) differs from its own def line (L90).]] - rationale - tests/test_affected_cli.py
- [[A graph persisted with directed=false must still recover caller-callee     dire]] - rationale - tests/test_affected_cli.py
- [[A trailing path separator must not change the match (parity with explain's     _]] - rationale - tests/test_affected_cli.py
- [[An edge with no stored location honestly falls back to the node's def line.]] - rationale - tests/test_affected_cli.py
- [[Several nodes share a source_file but none is the L1 file node and none's     ba]] - rationale - tests/test_affected_cli.py
- [[_write_callsite_graph()]] - code - tests/test_affected_cli.py
- [[_write_graph()]] - code - tests/test_affected_cli.py
- [[graphify's `extract` writes graph.json with an edges key (not networkx's     d]] - rationale - tests/test_affected_cli.py
- [[resolve_seed()]] - code - graphify/affected.py
- [[test_affected_cli.py]] - code - tests/test_affected_cli.py
- [[test_affected_cli_forces_directed_on_undirected_graph()]] - code - tests/test_affected_cli.py
- [[test_affected_cli_loads_edges_keyed_graph()]] - code - tests/test_affected_cli.py
- [[test_affected_cli_relation_filter_limits_reverse_traversal()]] - code - tests/test_affected_cli.py
- [[test_affected_cli_reverse_traverses_impact_edges()]] - code - tests/test_affected_cli.py
- [[test_affected_cli_source_file_path_uses_file_level_node()]] - code - tests/test_affected_cli.py
- [[test_affected_falls_back_to_def_line_when_edge_has_no_location()]] - code - tests/test_affected_cli.py
- [[test_affected_reports_call_site_line_not_def_line()]] - code - tests/test_affected_cli.py
- [[test_resolve_seed_bare_name_matches_callable_label()]] - code - tests/test_affected_cli.py
- [[test_resolve_seed_bare_name_tie_still_returns_none()]] - code - tests/test_affected_cli.py
- [[test_resolve_seed_decorated_query_matches_bare_label()]] - code - tests/test_affected_cli.py
- [[test_resolve_seed_matches_unicode_normalized_label()]] - code - tests/test_affected_cli.py
- [[test_resolve_seed_preserves_distinct_accents()]] - code - tests/test_affected_cli.py
- [[test_resolve_seed_source_file_ambiguous_no_file_node_returns_none()]] - code - tests/test_affected_cli.py
- [[test_resolve_seed_source_file_path_prefers_file_level_node()]] - code - tests/test_affected_cli.py
- [[test_resolve_seed_source_file_trailing_slash_parity()]] - code - tests/test_affected_cli.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_affected_clipy
SORT file.name ASC
```

## Connections to other communities
- 7 edges to [[_COMMUNITY_test_install.py]]
- 5 edges to [[_COMMUNITY_affected.py]]
- 1 edge to [[_COMMUNITY_graphify__main__.py]]

## Top bridge nodes
- [[test_affected_cli.py]] - degree 19, connects to 1 community
- [[resolve_seed()]] - degree 14, connects to 1 community
- [[test_affected_cli_forces_directed_on_undirected_graph()]] - degree 3, connects to 1 community
- [[test_affected_cli_loads_edges_keyed_graph()]] - degree 3, connects to 1 community
- [[test_affected_cli_relation_filter_limits_reverse_traversal()]] - degree 3, connects to 1 community