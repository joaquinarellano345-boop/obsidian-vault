---
type: community
cohesion: 0.08
members: 40
---

# to_obsidian

**Cohesion:** 0.08 - loosely connected
**Members:** 40 nodes

## Members
- [[1236 follow-up the fix landed in to_obsidian but not to_canvas, so     `graphi]] - rationale - tests/test_obsidian_dangling_member.py
- [[1506 exporting into an existing vault must not overwrite a user's note that]] - rationale - tests/test_export.py
- [[1896 follow-on a node that disappears and later returns must be writable     a]] - rationale - tests/test_export.py
- [[1896 re-exporting into the same vault must delete graphify's own notes for]] - rationale - tests/test_export.py
- [[A community whose members are all dangling should still not crash.]] - rationale - tests/test_obsidian_dangling_member.py
- [[A re-run overwrites graphify's own prior notes (via the manifest) but leaves a]] - rationale - tests/test_export.py
- [[Escape a value for safe embedding in a YAML double-quoted scalar (F-009).      S]] - rationale - graphify/export.py
- [[Export graph as an Obsidian vault - one .md file per node with wikilinks,]] - rationale - graphify/export.py
- [[Map each node_id to a unique note filename, appending a numeric suffix on     co]] - rationale - graphify/export.py
- [[No regression a freshempty dir still gets every note + .obsidiangraph.json.]] - rationale - tests/test_export.py
- [[Regression test for issue 1236 to_obsidian must not crash with KeyError when a]] - rationale - tests/test_obsidian_dangling_member.py
- [[Regression tests for issue 1094 to_obsidian  to_canvas must cap filenames to]] - rationale - tests/test_obsidian_filename_cap.py
- [[Sanitize a community name for use as an Obsidian tag.      Obsidian tags only al]] - rationale - graphify/export.py
- [[Two community labels differing only by case must each get their own     `_COMMUN]] - rationale - tests/test_export.py
- [[Two real nodes plus a community that references a third, non-existent id.]] - rationale - tests/test_obsidian_dangling_member.py
- [[_dedup_node_filenames()]] - code - graphify/export.py
- [[_four_node_two_community_graph()]] - code - tests/test_export.py
- [[_graph()_1]] - code - tests/test_obsidian_filename_cap.py
- [[_graph_with_dangling_member()]] - code - tests/test_obsidian_dangling_member.py
- [[_max_name_bytes()]] - code - tests/test_obsidian_filename_cap.py
- [[_obsidian_tag()]] - code - graphify/export.py
- [[_two_node_graph()]] - code - tests/test_export.py
- [[_yaml_str()]] - code - graphify/export.py
- [[test_canvas_dangling_community_member_does_not_crash()]] - code - tests/test_obsidian_dangling_member.py
- [[test_canvas_long_label_file_ref_capped()]] - code - tests/test_obsidian_filename_cap.py
- [[test_obsidian_community_of_only_dangling_members()]] - code - tests/test_obsidian_dangling_member.py
- [[test_obsidian_dangling_community_member_does_not_crash()]] - code - tests/test_obsidian_dangling_member.py
- [[test_obsidian_dangling_member.py]] - code - tests/test_obsidian_dangling_member.py
- [[test_obsidian_distinct_long_labels_sharing_prefix_do_not_collide()]] - code - tests/test_obsidian_filename_cap.py
- [[test_obsidian_filename_cap.py]] - code - tests/test_obsidian_filename_cap.py
- [[test_obsidian_long_ascii_label_does_not_crash()]] - code - tests/test_obsidian_filename_cap.py
- [[test_obsidian_long_cjk_label_byte_cap()]] - code - tests/test_obsidian_filename_cap.py
- [[test_obsidian_wikilink_resolves_after_truncation()]] - code - tests/test_obsidian_filename_cap.py
- [[test_to_obsidian_community_notes_case_collision()]] - code - tests/test_export.py
- [[test_to_obsidian_empty_dir_writes_full_vault()]] - code - tests/test_export.py
- [[test_to_obsidian_preserves_existing_user_notes_and_obsidian_config()]] - code - tests/test_export.py
- [[test_to_obsidian_removed_node_returning_is_writable_again()]] - code - tests/test_export.py
- [[test_to_obsidian_rerun_prunes_removed_nodes()]] - code - tests/test_export.py
- [[test_to_obsidian_rerun_updates_own_notes_but_not_user_files()]] - code - tests/test_export.py
- [[to_obsidian()]] - code - graphify/export.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/to_obsidian
SORT file.name ASC
```

## Connections to other communities
- 19 edges to [[_COMMUNITY_test_export.py]]
- 7 edges to [[_COMMUNITY_export.py]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_to_json]]

## Top bridge nodes
- [[to_obsidian()]] - degree 31, connects to 5 communities
- [[test_obsidian_filename_cap.py]] - degree 11, connects to 2 communities
- [[test_obsidian_dangling_member.py]] - degree 8, connects to 2 communities
- [[_dedup_node_filenames()]] - degree 4, connects to 2 communities
- [[test_to_obsidian_community_notes_case_collision()]] - degree 4, connects to 2 communities