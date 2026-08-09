---
type: community
cohesion: 0.05
members: 86
---

# test_export.py

**Cohesion:** 0.05 - loosely connected
**Members:** 86 nodes

## Members
- [[1324 empty communities (e.g. --no-cluster builds) on a populated graph     mus]] - rationale - tests/test_export.py
- [[1409 an all-punctuation label (e.g. `@`) must not produce a `@.md`-style]] - rationale - tests/test_export.py
- [[1409 same guard on the canvas exporter's file-node names.]] - rationale - tests/test_export.py
- [[1452 a community's node cards are laid out in the same ceil(sqrt(n))-column]] - rationale - tests/test_export.py
- [[1775 a node with source_file=None or label=None must not crash to_html     (sy]] - rationale - tests/test_export.py
- [[1838 neighbor links dropped an unescaped JSON.stringify(nid) into a     quoted]] - rationale - tests/test_export.py
- [[A 2-node graph where one node's label is all-punctuation (e.g. a `@`     tscon]] - rationale - tests/test_export.py
- [[A generated `_1` suffix must not collide with a node whose literal label is]] - rationale - tests/test_export.py
- [[A node with an overlay entry gets learning_status + learning_stale fields,     a]] - rationale - tests/test_export.py
- [[All-default labels → no backup (not curated).]] - rationale - tests/test_export.py
- [[Both notes must survive as separate files. On a case-insensitive filesystem]] - rationale - tests/test_export.py
- [[Canvas file-node references for case-only-distinct labels must be distinct     c]] - rationale - tests/test_export.py
- [[Changed graph.json on same day overwrites the existing backup in place.]] - rationale - tests/test_export.py
- [[Coercion must leave GraphML-native scalars (intfloatboolstr) untouched,     o]] - rationale - tests/test_export.py
- [[Export graph as GraphML - opens in Gephi, yEd, and any GraphML-compatible tool.]] - rationale - graphify/export.py
- [[Export graph as an Obsidian Canvas file - communities as groups, nodes as cards.]] - rationale - graphify/export.py
- [[Extract the RAW_NODES JSON array embedded in the generated HTML.]] - rationale - tests/test_export.py
- [[GRAPHIFY_NO_BACKUP=1 disables backup entirely.]] - rationale - tests/test_export.py
- [[Generate an interactive vis.js HTML visualization of the graph.      Features n]] - rationale - graphify/exporters/html.py
- [[No graph.json → no backup.]] - rationale - tests/test_export.py
- [[Node count of an existing graph.json.      Returns       - an ``int`` node coun]] - rationale - graphify/export.py
- [[Node file paths in canvas must be vault-root-relative (just fname.md), not hardc]] - rationale - tests/test_export.py
- [[Path_9]] - code
- [[Run Leiden community detection. Returns {community_id node_ids}.      Communi]] - rationale - graphify/cluster.py
- [[Same content on same day returns existing backup dir without re-copying.]] - rationale - tests/test_export.py
- [[The CLI calls to_obsidian and to_canvas separately with no shared map, so     th]] - rationale - tests/test_export.py
- [[Two nodes whose labels differ only by case - on macOSAPFS and WindowsNTFS]] - rationale - tests/test_export.py
- [[With no overlay, the HTML is byte-identical whether learning_overlay is     omit]] - rationale - tests/test_export.py
- [[_case_collision_graph()]] - code - tests/test_export.py
- [[_punct_graph()]] - code - tests/test_export.py
- [[_vis_nodes_from_html()]] - code - tests/test_export.py
- [[cluster()]] - code - graphify/cluster.py
- [[existing_graph_node_count()]] - code - graphify/export.py
- [[graph.json + .graphify_semantic_marker → backup taken.]] - rationale - tests/test_export.py
- [[graph.json + non-default label in .graphify_labels.json → backup taken.]] - rationale - tests/test_export.py
- [[graph.json present but no sentinel and no curated labels → no backup.]] - rationale - tests/test_export.py
- [[make_graph()_2]] - code - tests/test_export.py
- [[nx.write_graphml only accepts scalars; a dictlist attribute (per-node     metad]] - rationale - tests/test_export.py
- [[nx.write_graphml raises ValueError on a None attribute value; to_graphml     mus]] - rationale - tests/test_export.py
- [[test_backup_curated_labels()]] - code - tests/test_export.py
- [[test_backup_default_labels_only()]] - code - tests/test_export.py
- [[test_backup_env_disable()]] - code - tests/test_export.py
- [[test_backup_no_graph_json()]] - code - tests/test_export.py
- [[test_backup_no_markers()]] - code - tests/test_export.py
- [[test_backup_same_day_changed_content()]] - code - tests/test_export.py
- [[test_backup_same_day_no_accumulation()]] - code - tests/test_export.py
- [[test_backup_semantic_marker()]] - code - tests/test_export.py
- [[test_existing_graph_node_count()]] - code - tests/test_export.py
- [[test_export.py]] - code - tests/test_export.py
- [[test_obsidian_canvas_filenames_agree()]] - code - tests/test_export.py
- [[test_to_canvas_case_only_distinct_labels_get_distinct_files()]] - code - tests/test_export.py
- [[test_to_canvas_file_paths_relative_to_vault()]] - code - tests/test_export.py
- [[test_to_canvas_never_emits_punctuation_only_filenames()]] - code - tests/test_export.py
- [[test_to_canvas_no_communities_still_populates()]] - code - tests/test_export.py
- [[test_to_canvas_node_grid_matches_box_columns()]] - code - tests/test_export.py
- [[test_to_cypher_contains_merge_statements()]] - code - tests/test_export.py
- [[test_to_cypher_creates_file()]] - code - tests/test_export.py
- [[test_to_graphml_creates_file()]] - code - tests/test_export.py
- [[test_to_graphml_has_community_attribute()]] - code - tests/test_export.py
- [[test_to_graphml_preserves_native_scalar_types()]] - code - tests/test_export.py
- [[test_to_graphml_tolerates_dict_and_list_attribute_values()]] - code - tests/test_export.py
- [[test_to_graphml_tolerates_none_attribute_values()]] - code - tests/test_export.py
- [[test_to_graphml_valid_xml()]] - code - tests/test_export.py
- [[test_to_html_annotated_node_gets_learning_status_and_ring()]] - code - tests/test_export.py
- [[test_to_html_contains_legend_with_labels()]] - code - tests/test_export.py
- [[test_to_html_contains_nodes_and_edges()]] - code - tests/test_export.py
- [[test_to_html_contains_search()]] - code - tests/test_export.py
- [[test_to_html_contains_visjs()]] - code - tests/test_export.py
- [[test_to_html_contested_stale_node_gets_dashed_desaturated_ring()]] - code - tests/test_export.py
- [[test_to_html_creates_file()]] - code - tests/test_export.py
- [[test_to_html_handles_null_source_file_and_label()]] - code - tests/test_export.py
- [[test_to_html_member_counts_accepted()]] - code - tests/test_export.py
- [[test_to_html_neighbor_links_have_no_inline_onclick_xss()]] - code - tests/test_export.py
- [[test_to_html_pins_visjs_version_with_sri()]] - code - tests/test_export.py
- [[test_to_html_unannotated_identical_to_pre_feature()]] - code - tests/test_export.py
- [[test_to_json_creates_file()]] - code - tests/test_export.py
- [[test_to_json_nodes_have_community()]] - code - tests/test_export.py
- [[test_to_json_valid_json()]] - code - tests/test_export.py
- [[test_to_obsidian_case_only_distinct_labels_dont_overwrite()]] - code - tests/test_export.py
- [[test_to_obsidian_generated_suffix_doesnt_overwrite_literal()]] - code - tests/test_export.py
- [[test_to_obsidian_never_emits_punctuation_only_filenames()]] - code - tests/test_export.py
- [[to_canvas()]] - code - graphify/export.py
- [[to_graphml()]] - code - graphify/export.py
- [[to_html accepts member_counts without raising.]] - rationale - tests/test_export.py
- [[to_html()]] - code - graphify/exporters/html.py
- [[vis-network script tag must use a pinned versioned URL with a sha384     Subreso]] - rationale - tests/test_export.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_exportpy
SORT file.name ASC
```

## Connections to other communities
- 23 edges to [[_COMMUNITY_cli.py]]
- 19 edges to [[_COMMUNITY_to_obsidian]]
- 14 edges to [[_COMMUNITY_export.py]]
- 13 edges to [[_COMMUNITY_to_json]]
- 8 edges to [[_COMMUNITY_build_from_json]]
- 8 edges to [[_COMMUNITY_test_cluster.py]]
- 8 edges to [[_COMMUNITY_generate]]
- 6 edges to [[_COMMUNITY_test_analyze.py]]
- 4 edges to [[_COMMUNITY_graphifycluster.py]]
- 2 edges to [[_COMMUNITY_test_cli_export.py]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_test_reflect.py]]
- 1 edge to [[_COMMUNITY_test_security.py]]
- 1 edge to [[_COMMUNITY_reflect.py]]
- 1 edge to [[_COMMUNITY_sanitize_label]]
- 1 edge to [[_COMMUNITY_Graph]]

## Top bridge nodes
- [[cluster()]] - degree 65, connects to 9 communities
- [[test_export.py]] - degree 69, connects to 7 communities
- [[to_html()]] - degree 26, connects to 6 communities
- [[to_canvas()]] - degree 17, connects to 3 communities
- [[existing_graph_node_count()]] - degree 8, connects to 3 communities