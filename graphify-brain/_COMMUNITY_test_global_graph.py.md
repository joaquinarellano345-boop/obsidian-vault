---
type: community
cohesion: 0.11
members: 43
---

# test_global_graph.py

**Cohesion:** 0.11 - loosely connected
**Members:** 43 nodes

## Members
- [[F4 global_add must refuse to read a source graph.json that     exceeds the siz]] - rationale - tests/test_global_graph.py
- [[Add or update a project graph in the global graph.      Returns a summary dict w]] - rationale - graphify/global_graph.py
- [[Build a simple nx.Graph from node dicts.]] - rationale - tests/test_global_graph.py
- [[Edges incident to an external node that gets deduplicated against an     already]] - rationale - tests/test_global_graph.py
- [[Path_38]] - code
- [[Remove all nodes for repo_tag from the global graph. Returns count removed.]] - rationale - graphify/global_graph.py
- [[Remove all nodes tagged with repo_tag from G in-place. Returns count removed.]] - rationale - graphify/build.py
- [[Return a copy of G with all node IDs prefixed with repo_tag.      Labels are p]] - rationale - graphify/build.py
- [[Return the manifest repos dict.]] - rationale - graphify/global_graph.py
- [[Tests for the global graph infrastructure (graphifyglobal_graph.py), prefixpru]] - rationale - tests/test_global_graph.py
- [[_file_hash()]] - code - graphify/global_graph.py
- [[_graph_to_json()]] - code - tests/test_global_graph.py
- [[_load_global_graph()]] - code - graphify/global_graph.py
- [[_load_manifest()]] - code - graphify/global_graph.py
- [[_make_graph()_2]] - code - tests/test_global_graph.py
- [[_save_global_graph()]] - code - graphify/global_graph.py
- [[_save_manifest()]] - code - graphify/global_graph.py
- [[global_add()]] - code - graphify/global_graph.py
- [[global_graph.py]] - code - graphify/global_graph.py
- [[global_list()]] - code - graphify/global_graph.py
- [[global_path()]] - code - graphify/global_graph.py
- [[global_remove()]] - code - graphify/global_graph.py
- [[merge-graphs should prefix node IDs with repo name to avoid silent collision.]] - rationale - tests/test_global_graph.py
- [[prefix_graph_for_global()]] - code - graphify/build.py
- [[prune_repo_from_graph()]] - code - graphify/build.py
- [[test_dedup_ok_with_no_repo_attr()]] - code - tests/test_global_graph.py
- [[test_dedup_ok_with_single_repo()]] - code - tests/test_global_graph.py
- [[test_dedup_raises_on_cross_repo_nodes()]] - code - tests/test_global_graph.py
- [[test_global_add_collision_warning()]] - code - tests/test_global_graph.py
- [[test_global_add_creates_global_graph()]] - code - tests/test_global_graph.py
- [[test_global_add_rejects_oversized_source_graph()]] - code - tests/test_global_graph.py
- [[test_global_add_rewires_edges_to_deduplicated_externals()]] - code - tests/test_global_graph.py
- [[test_global_add_skip_on_unchanged_hash()]] - code - tests/test_global_graph.py
- [[test_global_add_two_repos_no_collision()]] - code - tests/test_global_graph.py
- [[test_global_graph.py]] - code - tests/test_global_graph.py
- [[test_global_remove()]] - code - tests/test_global_graph.py
- [[test_global_remove_unknown_tag_raises()]] - code - tests/test_global_graph.py
- [[test_merge_graphs_prefixes_ids()]] - code - tests/test_global_graph.py
- [[test_prefix_graph_preserves_label()]] - code - tests/test_global_graph.py
- [[test_prefix_graph_rewrites_edges()]] - code - tests/test_global_graph.py
- [[test_prefix_graph_sets_repo_and_local_id()]] - code - tests/test_global_graph.py
- [[test_prune_repo_removes_correct_nodes()]] - code - tests/test_global_graph.py
- [[test_prune_repo_returns_zero_if_not_present()]] - code - tests/test_global_graph.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_global_graphpy
SORT file.name ASC
```

## Connections to other communities
- 12 edges to [[_COMMUNITY_cli.py]]
- 4 edges to [[_COMMUNITY_deduplicate_entities]]
- 3 edges to [[_COMMUNITY_paths.py]]
- 3 edges to [[_COMMUNITY_test_security.py]]
- 2 edges to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_Graph]]

## Top bridge nodes
- [[global_add()]] - degree 21, connects to 2 communities
- [[global_graph.py]] - degree 13, connects to 2 communities
- [[prefix_graph_for_global()]] - degree 11, connects to 2 communities
- [[_load_global_graph()]] - degree 8, connects to 2 communities
- [[_save_manifest()]] - degree 5, connects to 2 communities