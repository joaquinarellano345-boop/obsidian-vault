---
type: community
cohesion: 0.07
members: 35
---

# _relations

**Cohesion:** 0.07 - loosely connected
**Members:** 35 nodes

## Members
- [[Extract classes, functions, methods, namespace uses, and calls from a .php file.]] - rationale - graphify/extract.py
- [[Extract projects and inter-project dependencies from a .sln file.]] - rationale - graphify/extractors/sln.py
- [[Module-level arrow functions must still emit a node and capture their calls (10]] - rationale - tests/test_languages.py
- [[Path_32]] - code
- [[Solution folders are virtual groupings, not files. Their node ids must be     de]] - rationale - tests/test_dotnet.py
- [[_relations()_1]] - code - tests/test_languages.py
- [[extract_php()]] - code - graphify/extract.py
- [[extract_sln()]] - code - graphify/extractors/sln.py
- [[test_apex_soql_uses_edge()]] - code - tests/test_languages.py
- [[test_cpp_finds_includes()]] - code - tests/test_languages.py
- [[test_java_finds_imports()]] - code - tests/test_languages.py
- [[test_js_module_level_arrow_produces_node_and_call_edges()]] - code - tests/test_languages.py
- [[test_php_config_helper_target_matches_first_segment()]] - code - tests/test_languages.py
- [[test_php_constructor_property_promotion_contexts()]] - code - tests/test_languages.py
- [[test_php_container_bind_links_contract_to_implementation()]] - code - tests/test_languages.py
- [[test_php_event_listener_links_event_to_listener()]] - code - tests/test_languages.py
- [[test_php_finds_class()]] - code - tests/test_languages.py
- [[test_php_finds_config_helper_call()]] - code - tests/test_languages.py
- [[test_php_finds_container_bind()]] - code - tests/test_languages.py
- [[test_php_finds_event_listeners()]] - code - tests/test_languages.py
- [[test_php_finds_function()]] - code - tests/test_languages.py
- [[test_php_finds_imports()]] - code - tests/test_languages.py
- [[test_php_finds_methods()]] - code - tests/test_languages.py
- [[test_php_finds_static_property_access()]] - code - tests/test_languages.py
- [[test_php_no_error()]] - code - tests/test_languages.py
- [[test_php_property_parameter_and_return_contexts()]] - code - tests/test_languages.py
- [[test_php_splits_inherits_implements_mixes_in()]] - code - tests/test_languages.py
- [[test_php_static_prop_target_is_holding_class()]] - code - tests/test_languages.py
- [[test_sln_contains_edges()]] - code - tests/test_dotnet.py
- [[test_sln_contains_edges()_1]] - code - tests/test_languages.py
- [[test_sln_finds_projects()]] - code - tests/test_languages.py
- [[test_sln_no_error()]] - code - tests/test_languages.py
- [[test_sln_project_dependency_edges()]] - code - tests/test_languages.py
- [[test_sln_solution_folder_ids_are_relative()]] - code - tests/test_dotnet.py
- [[test_swift_finds_imports()]] - code - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_relations
SORT file.name ASC
```

## Connections to other communities
- 33 edges to [[_COMMUNITY_test_languages.py]]
- 10 edges to [[_COMMUNITY__labels]]
- 7 edges to [[_COMMUNITY_test_dotnet.py]]
- 3 edges to [[_COMMUNITY__edges_with_relation]]
- 3 edges to [[_COMMUNITY__make_id]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 2 edges to [[_COMMUNITY_extract_cpp]]
- 2 edges to [[_COMMUNITY_extract_groovy]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_extract_js]]
- 1 edge to [[_COMMUNITY__extract_generic]]
- 1 edge to [[_COMMUNITY_extract_markdown]]

## Top bridge nodes
- [[_relations()_1]] - degree 25, connects to 7 communities
- [[extract_php()]] - degree 23, connects to 5 communities
- [[extract_sln()]] - degree 14, connects to 3 communities
- [[test_js_module_level_arrow_produces_node_and_call_edges()]] - degree 5, connects to 3 communities
- [[test_apex_soql_uses_edge()]] - degree 4, connects to 2 communities