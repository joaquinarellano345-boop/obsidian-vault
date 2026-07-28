---
type: community
cohesion: 0.11
members: 42
---

# test_mcp_ingest.py

**Cohesion:** 0.11 - loosely connected
**Members:** 42 nodes

## Members
- [[Parse an MCP config file into Graphify nodes and edges.      Behaviour matches o]] - rationale - graphify/mcp_ingest.py
- [[Path_45]] - code
- [[Path_82]] - code
- [[Return True when ``path`` is a recognised MCP config filename.]] - rationale - graphify/mcp_ingest.py
- [[Tests for graphify.mcp_ingest — MCP config file extraction.]] - rationale - tests/test_mcp_ingest.py
- [[_label_by_kind()]] - code - tests/test_mcp_ingest.py
- [[_labels()_4]] - code - tests/test_mcp_ingest.py
- [[_node_kinds()]] - code - tests/test_mcp_ingest.py
- [[_relations()_2]] - code - tests/test_mcp_ingest.py
- [[_write()_13]] - code - tests/test_mcp_ingest.py
- [[extract_mcp_config()]] - code - graphify/mcp_ingest.py
- [[is_mcp_config_path()]] - code - graphify/mcp_ingest.py
- [[test_dispatch_does_not_reroute_generic_json()]] - code - tests/test_mcp_ingest.py
- [[test_dispatch_routes_mcp_filename_to_mcp_extractor()]] - code - tests/test_mcp_ingest.py
- [[test_env_var_values_never_appear_anywhere()]] - code - tests/test_mcp_ingest.py
- [[test_every_edge_has_confidence_score()]] - code - tests/test_mcp_ingest.py
- [[test_filesystem_path_not_persisted_as_node()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_emits_commands_as_global_nodes()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_emits_env_var_names()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_emits_every_server()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_emits_npm_packages()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_emits_python_packages()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_parses_without_error()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_relations_include_contains_references_requires_env()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_strips_version_from_npm_package()]] - code - tests/test_mcp_ingest.py
- [[test_is_mcp_config_path_recognises_known_filenames()]] - code - tests/test_mcp_ingest.py
- [[test_is_mcp_config_path_rejects_generic_json()]] - code - tests/test_mcp_ingest.py
- [[test_malformed_json_returns_error()]] - code - tests/test_mcp_ingest.py
- [[test_mcp_ingest.py]] - code - tests/test_mcp_ingest.py
- [[test_missing_mcp_servers_key()]] - code - tests/test_mcp_ingest.py
- [[test_nested_mcp_servers_shape()]] - code - tests/test_mcp_ingest.py
- [[test_no_dangling_edges()]] - code - tests/test_mcp_ingest.py
- [[test_no_package_detected_for_unknown_arg_shape()]] - code - tests/test_mcp_ingest.py
- [[test_non_dict_server_entry_skipped()]] - code - tests/test_mcp_ingest.py
- [[test_oversize_file_skipped()]] - code - tests/test_mcp_ingest.py
- [[test_package_detection_skips_flags()]] - code - tests/test_mcp_ingest.py
- [[test_recognised_filenames_set_is_frozen()]] - code - tests/test_mcp_ingest.py
- [[test_root_not_an_object()]] - code - tests/test_mcp_ingest.py
- [[test_same_command_collapses_to_one_node_across_configs()]] - code - tests/test_mcp_ingest.py
- [[test_same_env_var_collapses_to_one_node_across_configs()]] - code - tests/test_mcp_ingest.py
- [[test_same_server_name_in_different_dirs_does_not_collide()]] - code - tests/test_mcp_ingest.py
- [[test_server_without_command_still_emits_server_node()]] - code - tests/test_mcp_ingest.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_mcp_ingestpy
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY__extract_pascal_regex]]
- 5 edges to [[_COMMUNITY_Path]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY__read_text]]
- 1 edge to [[_COMMUNITY_make_id]]

## Top bridge nodes
- [[extract_mcp_config()]] - degree 35, connects to 5 communities
- [[is_mcp_config_path()]] - degree 8, connects to 3 communities
- [[test_mcp_ingest.py]] - degree 39, connects to 2 communities
- [[test_dispatch_does_not_reroute_generic_json()]] - degree 3, connects to 1 community
- [[test_dispatch_routes_mcp_filename_to_mcp_extractor()]] - degree 3, connects to 1 community