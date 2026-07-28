---
type: community
cohesion: 0.25
members: 8
---

# lessons_fresh

**Cohesion:** 0.25 - loosely connected
**Members:** 8 nodes

## Members
- [[True if ``out_path`` exists and is at least as new as every input that     feeds]] - rationale - graphify/reflect.py
- [[lessons_fresh()]] - code - graphify/reflect.py
- [[parametrize_19]] - code
- [[test_lessons_fresh_false_when_graph_newer()]] - code - tests/test_reflect.py
- [[test_lessons_fresh_false_when_graph_sidecar_newer()]] - code - tests/test_reflect.py
- [[test_lessons_fresh_false_when_memory_newer()]] - code - tests/test_reflect.py
- [[test_lessons_fresh_missing_output_is_not_fresh()]] - code - tests/test_reflect.py
- [[test_lessons_fresh_true_when_output_newer_than_inputs()]] - code - tests/test_reflect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/lessons_fresh
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_test_reflect.py]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_reflect.py]]

## Top bridge nodes
- [[lessons_fresh()]] - degree 11, connects to 3 communities
- [[test_lessons_fresh_false_when_graph_sidecar_newer()]] - degree 3, connects to 1 community
- [[test_lessons_fresh_false_when_graph_newer()]] - degree 2, connects to 1 community
- [[test_lessons_fresh_false_when_memory_newer()]] - degree 2, connects to 1 community
- [[test_lessons_fresh_missing_output_is_not_fresh()]] - degree 2, connects to 1 community