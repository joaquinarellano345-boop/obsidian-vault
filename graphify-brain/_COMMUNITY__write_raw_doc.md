---
type: community
cohesion: 0.13
members: 21
---

# _write_raw_doc

**Cohesion:** 0.13 - loosely connected
**Members:** 21 nodes

## Members
- [[A corpus with a PREFERRED node (2 useful), a TENTATIVE node (1 useful),     a C]] - rationale - tests/test_reflect.py
- [[A label shared by 1 node id (ambiguous) or absent from the graph     (unresolve]] - rationale - tests/test_reflect.py
- [[A node cited by 5 useful results keeps exactly the 5 most-recent in     provena]] - rationale - tests/test_reflect.py
- [[Path_93]] - code
- [[Regression with a RELATIVE source_file and graph.json under graphify-out,]] - rationale - tests/test_reflect.py
- [[Two reflect runs on identical input + fixed `now` produce a byte-identical     s]] - rationale - tests/test_reflect.py
- [[When a committed .graphify_root marker records the project root (e.g. a     GRAP]] - rationale - tests/test_reflect.py
- [[Write a memory doc with a controlled date so ordering is deterministic to assert]] - rationale - tests/test_reflect.py
- [[Write a minimal graph.json under ``out`` with the given node dicts.]] - rationale - tests/test_reflect.py
- [[_overlay_corpus()]] - code - tests/test_reflect.py
- [[_overlay_graph()]] - code - tests/test_reflect.py
- [[_write_raw_doc()]] - code - tests/test_reflect.py
- [[load_learning_overlay recomputes the file fingerprint unchanged source =     s]] - rationale - tests/test_reflect.py
- [[reflect with a graph writes .graphify_learning.json next to graph.json with]] - rationale - tests/test_reflect.py
- [[test_ambiguous_or_unresolved_citation_is_skipped()]] - code - tests/test_reflect.py
- [[test_loader_marks_entry_stale_when_source_file_changes()]] - code - tests/test_reflect.py
- [[test_provenance_capped_to_five_most_recent()]] - code - tests/test_reflect.py
- [[test_relative_source_file_not_spuriously_stale_in_graphify_out_layout()]] - code - tests/test_reflect.py
- [[test_relative_source_file_resolved_via_graphify_root_marker()]] - code - tests/test_reflect.py
- [[test_sidecar_is_byte_identical_across_runs()]] - code - tests/test_reflect.py
- [[test_sidecar_write_classifies_and_keys_by_canonical_id()]] - code - tests/test_reflect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_write_raw_doc
SORT file.name ASC
```

## Connections to other communities
- 11 edges to [[_COMMUNITY_reflect.py]]
- 11 edges to [[_COMMUNITY_test_reflect.py]]
- 2 edges to [[_COMMUNITY_load_memory_docs]]
- 1 edge to [[_COMMUNITY__run]]
- 1 edge to [[_COMMUNITY_test_analyze.py]]

## Top bridge nodes
- [[_write_raw_doc()]] - degree 14, connects to 3 communities
- [[test_loader_marks_entry_stale_when_source_file_changes()]] - degree 6, connects to 2 communities
- [[test_relative_source_file_not_spuriously_stale_in_graphify_out_layout()]] - degree 6, connects to 2 communities
- [[test_relative_source_file_resolved_via_graphify_root_marker()]] - degree 6, connects to 2 communities
- [[Path_93]] - degree 5, connects to 2 communities