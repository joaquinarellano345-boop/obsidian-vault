---
type: community
cohesion: 0.13
members: 15
---

# _load_graph

**Cohesion:** 0.13 - loosely connected
**Members:** 15 nodes

## Members
- [[A non-decode ValueError (e.g. a non-.json path) must still print the     generic]] - rationale - tests/test_serve.py
- [[Write a minimal graph.json with the given node IDs.]] - rationale - tests/test_serve.py
- [[_load_graph()]] - code - graphify/serve.py
- [[_write_graph()_7]] - code - tests/test_serve.py
- [[json.JSONDecodeError is a ValueError subclass, so its except clause     must be]] - rationale - tests/test_serve.py
- [[mtime_ns + size uniquely identifies a graph version (874).]] - rationale - tests/test_serve.py
- [[serve() picks up a new graph.json written after startup (874).]] - rationale - tests/test_serve.py
- [[test_load_graph_accepts_under_cap()]] - code - tests/test_serve.py
- [[test_load_graph_cache_key_changes_with_content()]] - code - tests/test_serve.py
- [[test_load_graph_corrupted_json_prints_recovery_message()]] - code - tests/test_serve.py
- [[test_load_graph_generic_value_error_message_unchanged()]] - code - tests/test_serve.py
- [[test_load_graph_missing_file()]] - code - tests/test_serve.py
- [[test_load_graph_rejects_oversized_file()_1]] - code - tests/test_serve.py
- [[test_load_graph_roundtrip()]] - code - tests/test_serve.py
- [[test_maybe_reload_detects_graph_change()]] - code - tests/test_serve.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_load_graph
SORT file.name ASC
```

## Connections to other communities
- 10 edges to [[_COMMUNITY_test_serve.py]]
- 3 edges to [[_COMMUNITY__make_graph]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_cli.py]]
- 1 edge to [[_COMMUNITY_reflect.py]]
- 1 edge to [[_COMMUNITY_test_security.py]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__pick_seeds]]

## Top bridge nodes
- [[_load_graph()]] - degree 13, connects to 6 communities
- [[_write_graph()_7]] - degree 5, connects to 2 communities
- [[test_load_graph_accepts_under_cap()]] - degree 3, connects to 2 communities
- [[test_load_graph_rejects_oversized_file()_1]] - degree 3, connects to 2 communities
- [[test_load_graph_roundtrip()]] - degree 3, connects to 2 communities