---
type: community
cohesion: 0.18
members: 20
---

# test_incomplete_build_guard.py

**Cohesion:** 0.18 - loosely connected
**Members:** 20 nodes

## Members
- [[2169 an INCREMENTAL --no-cluster run merges the existing graph forward,     so]] - rationale - tests/test_incomplete_build_guard.py
- [[2169 an incremental --no-cluster run must hard-fail on an unparseable     exis]] - rationale - tests/test_incomplete_build_guard.py
- [[A present-but-unparseable existing graph.json (corrupt or mid-write) could     b]] - rationale - tests/test_incomplete_build_guard.py
- [[Patch export.to_json to record the ``force`` it was called with and return     a]] - rationale - tests/test_incomplete_build_guard.py
- [[Tests for the incomplete-build shrink-guard on `graphify extract`.  A full build]] - rationale - tests/test_incomplete_build_guard.py
- [[_arm_extract()]] - code - tests/test_incomplete_build_guard.py
- [[_arm_no_cluster()]] - code - tests/test_incomplete_build_guard.py
- [[_make_docs_corpus()]] - code - tests/test_incomplete_build_guard.py
- [[_seed_existing_graph()]] - code - tests/test_incomplete_build_guard.py
- [[_seed_to_json_recorder()]] - code - tests/test_incomplete_build_guard.py
- [[test_allow_partial_forces_write_despite_incomplete()]] - code - tests/test_incomplete_build_guard.py
- [[test_complete_extraction_keeps_force_write()]] - code - tests/test_incomplete_build_guard.py
- [[test_incomplete_build_guard.py]] - code - tests/test_incomplete_build_guard.py
- [[test_no_cluster_allow_partial_overwrites()]] - code - tests/test_incomplete_build_guard.py
- [[test_no_cluster_incomplete_build_fails_closed_on_malformed_existing_graph()]] - code - tests/test_incomplete_build_guard.py
- [[test_no_cluster_incomplete_build_refuses_to_shrink()]] - code - tests/test_incomplete_build_guard.py
- [[test_no_cluster_incremental_incomplete_build_carries_existing_nodes()]] - code - tests/test_incomplete_build_guard.py
- [[test_no_cluster_incremental_malformed_existing_graph_refuses_merge()]] - code - tests/test_incomplete_build_guard.py
- [[test_partial_extraction_refuses_to_shrink_existing_graph()]] - code - tests/test_incomplete_build_guard.py
- [[test_partial_extraction_writes_when_not_shrinking()]] - code - tests/test_incomplete_build_guard.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_incomplete_build_guardpy
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_test_install.py]]
- 1 edge to [[_COMMUNITY_graphify__main__.py]]

## Top bridge nodes
- [[test_incomplete_build_guard.py]] - degree 16, connects to 1 community
- [[test_allow_partial_forces_write_despite_incomplete()]] - degree 4, connects to 1 community
- [[test_complete_extraction_keeps_force_write()]] - degree 4, connects to 1 community
- [[test_no_cluster_incomplete_build_fails_closed_on_malformed_existing_graph()]] - degree 4, connects to 1 community
- [[test_no_cluster_incremental_incomplete_build_carries_existing_nodes()]] - degree 4, connects to 1 community