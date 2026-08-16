---
type: community
cohesion: 0.19
members: 17
---

# test_cluster.py

**Cohesion:** 0.19 - loosely connected
**Members:** 17 nodes

## Members
- [[Clustering should not emit ANSI escape codes or other output.      graspologic's]] - rationale - tests/test_cluster.py
- [[Ratio of actual intra-community edges to maximum possible.]] - rationale - graphify/cluster.py
- [[Same as above but for stderr — ANSI codes can go to either stream.]] - rationale - tests/test_cluster.py
- [[cohesion_score()]] - code - graphify/cluster.py
- [[make_graph()_1]] - code - tests/test_cluster.py
- [[test_cluster.py]] - code - tests/test_cluster.py
- [[test_cluster_covers_all_nodes()]] - code - tests/test_cluster.py
- [[test_cluster_does_not_write_to_stderr()]] - code - tests/test_cluster.py
- [[test_cluster_does_not_write_to_stdout()]] - code - tests/test_cluster.py
- [[test_cluster_returns_dict()]] - code - tests/test_cluster.py
- [[test_cohesion_score_complete_graph()]] - code - tests/test_cluster.py
- [[test_cohesion_score_disconnected()]] - code - tests/test_cluster.py
- [[test_cohesion_score_range()]] - code - tests/test_cluster.py
- [[test_cohesion_score_single_node()]] - code - tests/test_cluster.py
- [[test_remap_communities_to_previous_assigns_deterministic_new_ids()]] - code - tests/test_cluster.py
- [[test_remap_communities_to_previous_reuses_old_ids()]] - code - tests/test_cluster.py
- [[test_score_all_keys_match_communities()]] - code - tests/test_cluster.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_clusterpy
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_test_export.py]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 3 edges to [[_COMMUNITY_generate]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_graphifycluster.py]]
- 1 edge to [[_COMMUNITY_export.py]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]

## Top bridge nodes
- [[test_cluster.py]] - degree 19, connects to 6 communities
- [[cohesion_score()]] - degree 11, connects to 5 communities
- [[test_score_all_keys_match_communities()]] - degree 4, connects to 2 communities
- [[make_graph()_1]] - degree 8, connects to 1 community
- [[test_cluster_does_not_write_to_stderr()]] - degree 4, connects to 1 community