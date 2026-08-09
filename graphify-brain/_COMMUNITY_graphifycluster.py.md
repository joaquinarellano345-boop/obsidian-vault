---
type: community
cohesion: 0.14
members: 25
---

# graphify/cluster.py

**Cohesion:** 0.14 - loosely connected
**Members:** 25 nodes

## Members
- [[An incremental rebuild must not reuse a saved label for a community whose     me]] - rationale - tests/test_watch.py
- [[Community detection on NetworkX graphs. Uses Leiden (graspologic) if available,]] - rationale - graphify/cluster.py
- [[Context manager to suppress stdoutstderr during library calls.      graspologic]] - rationale - graphify/cluster.py
- [[Deterministic, LLM-free community labels — `label_communities_by_hub`.  Names ea]] - rationale - tests/test_community_hub_labels.py
- [[Deterministic, LLM-free community labels name each community after its     high]] - rationale - graphify/cluster.py
- [[Per-community membership fingerprints ``{cid sha256(sorted member ids)}``.]] - rationale - graphify/cluster.py
- [[Run a second Leiden pass on a community subgraph to split it further.]] - rationale - graphify/cluster.py
- [[Run community detection. Returns {node_id community_id}.      Tries Leiden (gra]] - rationale - graphify/cluster.py
- [[_g()_1]] - code - tests/test_community_hub_labels.py
- [[_partition()]] - code - graphify/cluster.py
- [[_split_community()]] - code - graphify/cluster.py
- [[_suppress_output()]] - code - graphify/cluster.py
- [[community_member_sigs()]] - code - graphify/cluster.py
- [[graphifycluster.py]] - code - graphify/cluster.py
- [[label_communities_by_hub()]] - code - graphify/cluster.py
- [[test_absent_members_fall_back_to_placeholder()]] - code - tests/test_community_hub_labels.py
- [[test_community_hub_labels.py]] - code - tests/test_community_hub_labels.py
- [[test_community_member_sigs_are_deterministic_and_order_independent()]] - code - tests/test_community_hub_labels.py
- [[test_community_member_sigs_change_when_membership_changes()]] - code - tests/test_community_hub_labels.py
- [[test_labels_by_highest_degree_hub()]] - code - tests/test_community_hub_labels.py
- [[test_multiple_communities_each_get_their_own_hub()]] - code - tests/test_community_hub_labels.py
- [[test_node_without_label_attr_uses_id()]] - code - tests/test_community_hub_labels.py
- [[test_not_a_placeholder_for_a_real_community()]] - code - tests/test_community_hub_labels.py
- [[test_rebuild_code_drops_labels_whose_community_changed()]] - code - tests/test_watch.py
- [[test_tie_breaks_deterministically_by_node_id()]] - code - tests/test_community_hub_labels.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/graphify/clusterpy
SORT file.name ASC
```

## Connections to other communities
- 10 edges to [[_COMMUNITY_cli.py]]
- 4 edges to [[_COMMUNITY_test_export.py]]
- 3 edges to [[_COMMUNITY_generate]]
- 3 edges to [[_COMMUNITY_test_watch.py]]
- 2 edges to [[_COMMUNITY_test_cluster.py]]
- 1 edge to [[_COMMUNITY_test_analyze.py]]
- 1 edge to [[_COMMUNITY_to_json]]
- 1 edge to [[_COMMUNITY_Graph]]

## Top bridge nodes
- [[graphifycluster.py]] - degree 18, connects to 7 communities
- [[community_member_sigs()]] - degree 11, connects to 2 communities
- [[_partition()]] - degree 6, connects to 2 communities
- [[test_rebuild_code_drops_labels_whose_community_changed()]] - degree 4, connects to 2 communities
- [[label_communities_by_hub()]] - degree 13, connects to 1 community