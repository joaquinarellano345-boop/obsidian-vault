---
type: community
cohesion: 0.05
members: 68
---

# export.py

**Cohesion:** 0.05 - loosely connected
**Members:** 68 nodes

## Members
- [[1236 follow-up the fix landed in to_obsidian but not to_canvas, so     `graphi]] - rationale - tests/test_obsidian_dangling_member.py
- [[1452 a community's node cards are laid out in the same ceil(sqrt(n))-column]] - rationale - tests/test_export.py
- [[1506 exporting into an existing vault must not overwrite a user's note that]] - rationale - tests/test_export.py
- [[1896 follow-on a node that disappears and later returns must be writable     a]] - rationale - tests/test_export.py
- [[1896 re-exporting into the same vault must delete graphify's own notes for]] - rationale - tests/test_export.py
- [[A community whose members are all dangling should still not crash.]] - rationale - tests/test_obsidian_dangling_member.py
- [[A re-run overwrites graphify's own prior notes (via the manifest) but leaves a]] - rationale - tests/test_export.py
- [[Cap a filename stem to ``limit`` UTF-8 bytes so it stays under the 255-byte]] - rationale - graphify/export.py
- [[Escape a string for safe embedding in a Cypher single-quoted literal.      Handl]] - rationale - graphify/export.py
- [[Escape a value for safe embedding in a YAML double-quoted scalar (F-009).      S]] - rationale - graphify/export.py
- [[Export graph as an Obsidian Canvas file - communities as groups, nodes as cards.]] - rationale - graphify/export.py
- [[Export graph as an Obsidian vault - one .md file per node with wikilinks,]] - rationale - graphify/export.py
- [[Export graph as an SVG file using matplotlib + spring layout.      Lightweight a]] - rationale - graphify/export.py
- [[Invert communities dict node_id - community_id.]] - rationale - graphify/analyze.py
- [[Map each node_id to a unique note filename, appending a numeric suffix on     co]] - rationale - graphify/export.py
- [[No regression a freshempty dir still gets every note + .obsidiangraph.json.]] - rationale - tests/test_export.py
- [[Path_9]] - code
- [[Push graph directly to a running FalkorDB instance via the Python SDK.      Requ]] - rationale - graphify/exporters/graphdb.py
- [[Push graph directly to a running Neo4j instance via the Python driver.      Requ]] - rationale - graphify/exporters/graphdb.py
- [[Regression test for issue 1236 to_obsidian must not crash with KeyError when a]] - rationale - tests/test_obsidian_dangling_member.py
- [[Regression tests for issue 1094 to_obsidian  to_canvas must cap filenames to]] - rationale - tests/test_obsidian_filename_cap.py
- [[Remove edges whose source or target node is not in the node set.      Returns th]] - rationale - graphify/export.py
- [[Sanitise a value used in identifier position (node label  rel type).      Cyphe]] - rationale - graphify/export.py
- [[Sanitize a community name for use as an Obsidian tag.      Obsidian tags only al]] - rationale - graphify/export.py
- [[Shared constantshelpers for the graphify exporters package.  Symbols used by mo]] - rationale - graphify/exporters/base.py
- [[The CLI calls to_obsidian and to_canvas separately with no shared map, so     th]] - rationale - tests/test_export.py
- [[Two community labels differing only by case must each get their own     `_COMMUN]] - rationale - tests/test_export.py
- [[Two real nodes plus a community that references a third, non-existent id.]] - rationale - tests/test_obsidian_dangling_member.py
- [[_cap_filename()]] - code - graphify/export.py
- [[_cypher_escape()]] - code - graphify/export.py
- [[_cypher_label()]] - code - graphify/export.py
- [[_dedup_node_filenames()]] - code - graphify/export.py
- [[_four_node_two_community_graph()]] - code - tests/test_export.py
- [[_graph()_1]] - code - tests/test_obsidian_filename_cap.py
- [[_graph_with_dangling_member()]] - code - tests/test_obsidian_dangling_member.py
- [[_max_name_bytes()]] - code - tests/test_obsidian_filename_cap.py
- [[_node_community_map()]] - code - graphify/analyze.py
- [[_obsidian_tag()]] - code - graphify/export.py
- [[_two_node_graph()]] - code - tests/test_export.py
- [[_yaml_str()]] - code - graphify/export.py
- [[export.py]] - code - graphify/export.py
- [[exportersbase.py]] - code - graphify/exporters/base.py
- [[graphdb — moved verbatim from graphifyexport.py.]] - rationale - graphify/exporters/graphdb.py
- [[graphdb.py]] - code - graphify/exporters/graphdb.py
- [[prune_dangling_edges()]] - code - graphify/export.py
- [[push_to_falkordb()]] - code - graphify/exporters/graphdb.py
- [[push_to_neo4j()]] - code - graphify/exporters/graphdb.py
- [[test_canvas_dangling_community_member_does_not_crash()]] - code - tests/test_obsidian_dangling_member.py
- [[test_canvas_long_label_file_ref_capped()]] - code - tests/test_obsidian_filename_cap.py
- [[test_obsidian_canvas_filenames_agree()]] - code - tests/test_export.py
- [[test_obsidian_community_of_only_dangling_members()]] - code - tests/test_obsidian_dangling_member.py
- [[test_obsidian_dangling_community_member_does_not_crash()]] - code - tests/test_obsidian_dangling_member.py
- [[test_obsidian_dangling_member.py]] - code - tests/test_obsidian_dangling_member.py
- [[test_obsidian_distinct_long_labels_sharing_prefix_do_not_collide()]] - code - tests/test_obsidian_filename_cap.py
- [[test_obsidian_filename_cap.py]] - code - tests/test_obsidian_filename_cap.py
- [[test_obsidian_long_ascii_label_does_not_crash()]] - code - tests/test_obsidian_filename_cap.py
- [[test_obsidian_long_cjk_label_byte_cap()]] - code - tests/test_obsidian_filename_cap.py
- [[test_obsidian_wikilink_resolves_after_truncation()]] - code - tests/test_obsidian_filename_cap.py
- [[test_to_canvas_node_grid_matches_box_columns()]] - code - tests/test_export.py
- [[test_to_obsidian_community_notes_case_collision()]] - code - tests/test_export.py
- [[test_to_obsidian_empty_dir_writes_full_vault()]] - code - tests/test_export.py
- [[test_to_obsidian_preserves_existing_user_notes_and_obsidian_config()]] - code - tests/test_export.py
- [[test_to_obsidian_removed_node_returning_is_writable_again()]] - code - tests/test_export.py
- [[test_to_obsidian_rerun_prunes_removed_nodes()]] - code - tests/test_export.py
- [[test_to_obsidian_rerun_updates_own_notes_but_not_user_files()]] - code - tests/test_export.py
- [[to_canvas()]] - code - graphify/export.py
- [[to_obsidian()]] - code - graphify/export.py
- [[to_svg()]] - code - graphify/export.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/exportpy
SORT file.name ASC
```

## Connections to other communities
- 33 edges to [[_COMMUNITY_test_export.py]]
- 9 edges to [[_COMMUNITY_cli.py]]
- 7 edges to [[_COMMUNITY_to_json]]
- 5 edges to [[_COMMUNITY_test_analyze.py]]
- 4 edges to [[_COMMUNITY_build_from_json]]
- 3 edges to [[_COMMUNITY__rebuild_code]]
- 3 edges to [[_COMMUNITY_test_pipeline.py]]
- 2 edges to [[_COMMUNITY_test_falkordb_integration.py]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_test_security.py]]
- 1 edge to [[_COMMUNITY_generate]]
- 1 edge to [[_COMMUNITY_test_cross_extension_reexport_self_cycle.py]]

## Top bridge nodes
- [[export.py]] - degree 39, connects to 13 communities
- [[to_obsidian()]] - degree 31, connects to 4 communities
- [[_node_community_map()]] - degree 15, connects to 4 communities
- [[Path_9]] - degree 6, connects to 4 communities
- [[to_canvas()]] - degree 17, connects to 2 communities