---
type: community
cohesion: 0.11
members: 29
---

# test_file_label_disambiguation.py

**Cohesion:** 0.11 - loosely connected
**Members:** 29 nodes

## Members
- [[Any_12]] - code
- [[Build a ``{name, total_count, children}`` hierarchy.      Each leaf is either a]] - rationale - graphify/tree_html.py
- [[File-node labels are disambiguated when basenames collide (2032).  In directory]] - rationale - tests/test_file_label_disambiguation.py
- [[Full pipeline two entry-point index.ts files get distinguishable labels     and]] - rationale - tests/test_file_label_disambiguation.py
- [[Given (key, label, source_file) triples, return {key new_label} for file     no]] - rationale - graphify/build.py
- [[Path_55]] - code
- [[Relabel colliding-basename file nodes on a graph (2032). Idsedges are     neve]] - rationale - graphify/build.py
- [[Shortest trailing path suffix (basename + k parent dirs) of sf that is     uni]] - rationale - graphify/build.py
- [[The extract --no-cluster path writes the merged node dicts directly     (bypassi]] - rationale - tests/test_file_label_disambiguation.py
- [[Whether label is a file node's label for source_file — the bare     basename]] - rationale - graphify/build.py
- [[_common_root()]] - code - graphify/tree_html.py
- [[_disambiguate_file_node_labels()]] - code - graphify/build.py
- [[_file_label_reassignments()]] - code - graphify/build.py
- [[_file_node()]] - code - tests/test_file_label_disambiguation.py
- [[_is_file_node_label()]] - code - graphify/build.py
- [[_make_truncation_leaf()]] - code - graphify/tree_html.py
- [[_shortest_unique_suffix()]] - code - graphify/build.py
- [[build_tree()]] - code - graphify/tree_html.py
- [[emit_html()]] - code - graphify/tree_html.py
- [[test_colliding_file_labels_are_qualified_uniques_left_bare()]] - code - tests/test_file_label_disambiguation.py
- [[test_disambiguate_raw_node_list_for_no_cluster_path()]] - code - tests/test_file_label_disambiguation.py
- [[test_disambiguation_is_idempotent()]] - code - tests/test_file_label_disambiguation.py
- [[test_end_to_end_build_and_lookup()]] - code - tests/test_file_label_disambiguation.py
- [[test_file_label_disambiguation.py]] - code - tests/test_file_label_disambiguation.py
- [[test_is_file_node_label_and_suffix_helpers()]] - code - tests/test_file_label_disambiguation.py
- [[test_three_way_collision_grows_suffix_until_unique()]] - code - tests/test_file_label_disambiguation.py
- [[tree_html — emit a D3 v7 collapsible-tree HTML view of a graph.  A self-containe]] - rationale - graphify/tree_html.py
- [[tree_html.py]] - code - graphify/tree_html.py
- [[write_tree_html()]] - code - graphify/tree_html.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_file_label_disambiguationpy
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_graphifybuild.py]]
- 5 edges to [[_COMMUNITY_cli.py]]
- 3 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_extract]]
- 2 edges to [[_COMMUNITY_test_security.py]]
- 2 edges to [[_COMMUNITY_test_serve.py]]
- 1 edge to [[_COMMUNITY_test_analyze.py]]
- 1 edge to [[_COMMUNITY_generate]]
- 1 edge to [[_COMMUNITY_export.py]]

## Top bridge nodes
- [[test_file_label_disambiguation.py]] - degree 16, connects to 5 communities
- [[_is_file_node_label()]] - degree 10, connects to 3 communities
- [[test_end_to_end_build_and_lookup()]] - degree 6, connects to 3 communities
- [[tree_html.py]] - degree 9, connects to 2 communities
- [[_disambiguate_file_node_labels()]] - degree 8, connects to 2 communities