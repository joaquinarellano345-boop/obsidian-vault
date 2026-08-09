---
type: community
cohesion: 0.05
members: 75
---

# _get_extractor

**Cohesion:** 0.05 - loosely connected
**Members:** 75 nodes

## Members
- [[A `.h` with a C++ class must route to extract_cpp, not extract_c (which has]] - rationale - tests/test_languages.py
- [[A bridging header that is only `import X.h` (no @interface) must route to]] - rationale - tests/test_languages.py
- [[A plain C header (no C++ signal) must keep its extract_c routing.]] - rationale - tests/test_languages.py
- [[An ObjC `.h` (has @interface) routes to extract_objc; a plain C `.h` stays     o]] - rationale - tests/test_languages.py
- [[Any_2]] - code
- [[Any_6]] - code
- [[Append a node if not already present. ``kind`` is metadata, not file_type.]] - rationale - graphify/mcp_ingest.py
- [[Append an edge if (source, target, relation) is not already present.]] - rationale - graphify/mcp_ingest.py
- [[Drop the ``@version`` suffix from an npm package id, preserving the scope.]] - rationale - graphify/mcp_ingest.py
- [[Emit nodesedges for one entry under ``mcpServers``.]] - rationale - graphify/mcp_ingest.py
- [[Extensionless CLIs resolve their extractor from the shebang, mirroring     detec]] - rationale - tests/test_extract.py
- [[Parse an MCP config file into Graphify nodes and edges.      Behaviour matches o]] - rationale - graphify/mcp_ingest.py
- [[Path_45]] - code
- [[Path_82]] - code
- [[Return True when ``path`` is a recognised MCP config filename.]] - rationale - graphify/mcp_ingest.py
- [[Return the correct extractor function for a file, or None if unsupported.]] - rationale - graphify/extract.py
- [[Return the first arg that looks like an npm or pypi package id, else None.]] - rationale - graphify/mcp_ingest.py
- [[Tests for graphify.mcp_ingest — MCP config file extraction.]] - rationale - tests/test_mcp_ingest.py
- [[_add_edge()]] - code - graphify/mcp_ingest.py
- [[_add_node()]] - code - graphify/mcp_ingest.py
- [[_detect_package_from_args()]] - code - graphify/mcp_ingest.py
- [[_emit_server()]] - code - graphify/mcp_ingest.py
- [[_get_extractor should route .psd1 to extract_powershell_manifest.]] - rationale - tests/test_languages.py
- [[_get_extractor()]] - code - graphify/extract.py
- [[_label_by_kind()]] - code - tests/test_mcp_ingest.py
- [[_labels()_4]] - code - tests/test_mcp_ingest.py
- [[_node_kinds()]] - code - tests/test_mcp_ingest.py
- [[_relations()_2]] - code - tests/test_mcp_ingest.py
- [[_strip_version()]] - code - graphify/mcp_ingest.py
- [[_write()_13]] - code - tests/test_mcp_ingest.py
- [[extract_mcp_config()]] - code - graphify/mcp_ingest.py
- [[is_mcp_config_path()]] - code - graphify/mcp_ingest.py
- [[mcp_ingest.py]] - code - graphify/mcp_ingest.py
- [[mcp_ingest.py — Extract MCP (Model Context Protocol) server configuration files.]] - rationale - graphify/mcp_ingest.py
- [[test_cpp_header_routes_to_cpp_extractor()]] - code - tests/test_languages.py
- [[test_dispatch_does_not_reroute_generic_json()]] - code - tests/test_mcp_ingest.py
- [[test_dispatch_routes_mcp_filename_to_mcp_extractor()]] - code - tests/test_mcp_ingest.py
- [[test_dispatch_table()]] - code - tests/test_dotnet.py
- [[test_env_var_values_never_appear_anywhere()]] - code - tests/test_mcp_ingest.py
- [[test_every_edge_has_confidence_score()]] - code - tests/test_mcp_ingest.py
- [[test_extensionless_shebang_via_dispatch()]] - code - tests/test_extract.py
- [[test_extensionless_without_usable_shebang_stays_unsupported()]] - code - tests/test_extract.py
- [[test_extract_bash_via_dispatch()]] - code - tests/test_extract.py
- [[test_extract_json_via_dispatch()]] - code - tests/test_extract.py
- [[test_filesystem_path_not_persisted_as_node()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_emits_commands_as_global_nodes()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_emits_env_var_names()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_emits_every_server()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_emits_npm_packages()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_emits_python_packages()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_parses_without_error()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_relations_include_contains_references_requires_env()]] - code - tests/test_mcp_ingest.py
- [[test_fixture_strips_version_from_npm_package()]] - code - tests/test_mcp_ingest.py
- [[test_get_extractor_routes_matlab_m_away_from_objc()]] - code - tests/test_extract.py
- [[test_is_mcp_config_path_recognises_known_filenames()]] - code - tests/test_mcp_ingest.py
- [[test_is_mcp_config_path_rejects_generic_json()]] - code - tests/test_mcp_ingest.py
- [[test_malformed_json_returns_error()]] - code - tests/test_mcp_ingest.py
- [[test_mcp_ingest.py]] - code - tests/test_mcp_ingest.py
- [[test_missing_mcp_servers_key()]] - code - tests/test_mcp_ingest.py
- [[test_nested_mcp_servers_shape()]] - code - tests/test_mcp_ingest.py
- [[test_no_dangling_edges()]] - code - tests/test_mcp_ingest.py
- [[test_no_package_detected_for_unknown_arg_shape()]] - code - tests/test_mcp_ingest.py
- [[test_non_dict_server_entry_skipped()]] - code - tests/test_mcp_ingest.py
- [[test_objc_header_dispatch_routes_objc_not_c()]] - code - tests/test_languages.py
- [[test_objc_header_with_import_routes_to_objc()]] - code - tests/test_languages.py
- [[test_oversize_file_skipped()]] - code - tests/test_mcp_ingest.py
- [[test_package_detection_skips_flags()]] - code - tests/test_mcp_ingest.py
- [[test_plain_c_header_stays_on_c_extractor()]] - code - tests/test_languages.py
- [[test_powershell_psd1_dispatched()]] - code - tests/test_languages.py
- [[test_recognised_filenames_set_is_frozen()]] - code - tests/test_mcp_ingest.py
- [[test_root_not_an_object()]] - code - tests/test_mcp_ingest.py
- [[test_same_command_collapses_to_one_node_across_configs()]] - code - tests/test_mcp_ingest.py
- [[test_same_env_var_collapses_to_one_node_across_configs()]] - code - tests/test_mcp_ingest.py
- [[test_same_server_name_in_different_dirs_does_not_collide()]] - code - tests/test_mcp_ingest.py
- [[test_server_without_command_still_emits_server_node()]] - code - tests/test_mcp_ingest.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_get_extractor
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_Path]]
- 7 edges to [[_COMMUNITY__make_id]]
- 6 edges to [[_COMMUNITY_test_extract.py]]
- 6 edges to [[_COMMUNITY_test_languages.py]]
- 5 edges to [[_COMMUNITY_make_id]]
- 4 edges to [[_COMMUNITY_extract.py]]
- 3 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_test_manifest_ingest.py]]
- 2 edges to [[_COMMUNITY_test_dotnet.py]]
- 2 edges to [[_COMMUNITY__extract_pascal_regex]]
- 2 edges to [[_COMMUNITY_sanitize_label]]
- 1 edge to [[_COMMUNITY_classify_file]]
- 1 edge to [[_COMMUNITY_extract_cpp]]
- 1 edge to [[_COMMUNITY_extract]]
- 1 edge to [[_COMMUNITY_extract_objc]]
- 1 edge to [[_COMMUNITY_extract_powershell]]
- 1 edge to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY_extract_terraform]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_run_language_resolvers]]

## Top bridge nodes
- [[_get_extractor()]] - degree 39, connects to 13 communities
- [[mcp_ingest.py]] - degree 17, connects to 6 communities
- [[_add_node()]] - degree 10, connects to 4 communities
- [[extract_mcp_config()]] - degree 35, connects to 3 communities
- [[_add_edge()]] - degree 8, connects to 3 communities