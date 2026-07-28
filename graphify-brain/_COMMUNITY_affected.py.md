---
type: community
cohesion: 0.18
members: 19
---

# affected.py

**Cohesion:** 0.18 - loosely connected
**Members:** 19 nodes

## Members
- [[1669 — affected Class must reach callers that bind to the class's method node]] - rationale - tests/test_affected_member_seed.py
- [[AffectedHit]] - code - graphify/affected.py
- [[Lowercased label with the callable decoration (trailing ()) removed.]] - rationale - graphify/affected.py
- [[Path_1]] - code
- [[Return the file-level node when a source_file query matches many nodes.]] - rationale - graphify/affected.py
- [[_bare_name()]] - code - graphify/affected.py
- [[_format_location()]] - code - graphify/affected.py
- [[_g()]] - code - tests/test_affected_member_seed.py
- [[_node_label()]] - code - graphify/affected.py
- [[_normalize_label()]] - code - graphify/affected.py
- [[_prefer_file_node()]] - code - graphify/affected.py
- [[affected.py]] - code - graphify/affected.py
- [[affected_nodes()]] - code - graphify/affected.py
- [[format_affected()]] - code - graphify/affected.py
- [[test_affected_member_seed.py]] - code - tests/test_affected_member_seed.py
- [[test_class_affected_reaches_method_bound_caller()]] - code - tests/test_affected_member_seed.py
- [[test_class_level_caller_still_works()]] - code - tests/test_affected_member_seed.py
- [[test_member_method_node_not_reported_as_hit()]] - code - tests/test_affected_member_seed.py
- [[test_method_contains_still_excluded_from_general_walk()]] - code - tests/test_affected_member_seed.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/affectedpy
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_test_affected_cli.py]]
- 4 edges to [[_COMMUNITY_test_indirect_dispatch.py]]
- 3 edges to [[_COMMUNITY_test_multigraph_diagnostics.py]]
- 3 edges to [[_COMMUNITY_test_indirect_dispatch_assign_return.py]]
- 3 edges to [[_COMMUNITY_test_indirect_dispatch_getattr.py]]
- 2 edges to [[_COMMUNITY_cli.py]]

## Top bridge nodes
- [[affected.py]] - degree 15, connects to 5 communities
- [[affected_nodes()]] - degree 15, connects to 3 communities
- [[format_affected()]] - degree 7, connects to 2 communities
- [[_prefer_file_node()]] - degree 5, connects to 1 community
- [[_bare_name()]] - degree 4, connects to 1 community