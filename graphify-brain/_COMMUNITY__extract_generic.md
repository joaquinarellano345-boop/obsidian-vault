---
type: community
cohesion: 0.07
members: 29
---

# _extract_generic

**Cohesion:** 0.07 - loosely connected
**Members:** 29 nodes

## Members
- [[Add TSJS receiver bindings to ``table`` (name - TypeName), for member-call]] - rationale - graphify/extractors/engine.py
- [[Collect ``name - TypeName`` for C receiver typing (1609) class fields,     p]] - rationale - graphify/extractors/engine.py
- [[Collect ``var - Type`` from local ``let````var`` bindings in a Swift     funct]] - rationale - graphify/extractors/engine.py
- [[Extract functions, methods, require() imports, and calls from a .lua file.]] - rationale - graphify/extract.py
- [[Generic AST extractor driven by LanguageConfig.      ``source_override`` parses]] - rationale - graphify/extractors/engine.py
- [[If a Swift call expression is a constructor (``Foo()``), return the type name.]] - rationale - graphify/extractors/engine.py
- [[Map ``local_var - ClassName`` for ``var = ClassName.new`` within one Ruby     m]] - rationale - graphify/extractors/engine.py
- [[Module-scope names rebound to NON-function data (`const X = {...}`, `let y = 5`)]] - rationale - graphify/extractors/engine.py
- [[Names rebound by assignment at MODULE scope (top-level `x = ...`, `for`, walrus)]] - rationale - graphify/extractors/engine.py
- [[Path_19]] - code
- [[Pre-scan a Swift compilation unit and return (protocol_names, class_like_names).]] - rationale - graphify/extractors/engine.py
- [[Return names declared as `interface` in this C compilation unit.]] - rationale - graphify/extractors/engine.py
- [[Return the bound name of a Swift property (``let x````var x = ...``).]] - rationale - graphify/extractors/engine.py
- [[Return the leading kind token for a Swift class_declaration classstructenume]] - rationale - graphify/extractors/engine.py
- [[When Language() raises TypeError (e.g. old tree-sitter binding meets a     new t]] - rationale - tests/test_extract.py
- [[_csharp_member_type_table()]] - code - graphify/extractors/engine.py
- [[_csharp_pre_scan_interfaces()]] - code - graphify/extractors/engine.py
- [[_extract_generic()]] - code - graphify/extractors/engine.py
- [[_js_module_bound_names()]] - code - graphify/extractors/engine.py
- [[_python_module_bound_names()]] - code - graphify/extractors/engine.py
- [[_ruby_local_class_bindings()]] - code - graphify/extractors/engine.py
- [[_swift_constructor_type()]] - code - graphify/extractors/engine.py
- [[_swift_declaration_keyword()]] - code - graphify/extractors/engine.py
- [[_swift_local_var_types()]] - code - graphify/extractors/engine.py
- [[_swift_pre_scan()]] - code - graphify/extractors/engine.py
- [[_swift_property_name()]] - code - graphify/extractors/engine.py
- [[_ts_receiver_type_table()]] - code - graphify/extractors/engine.py
- [[extract_lua()]] - code - graphify/extract.py
- [[test_extract_generic_surfaces_tree_sitter_version_mismatch_hint()]] - code - tests/test_extract.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_extract_generic
SORT file.name ASC
```

## Connections to other communities
- 24 edges to [[_COMMUNITY_extract.py]]
- 14 edges to [[_COMMUNITY_engine.py]]
- 4 edges to [[_COMMUNITY_test_languages.py]]
- 2 edges to [[_COMMUNITY_extract_astro]]
- 2 edges to [[_COMMUNITY__make_id]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_extract_python]]
- 1 edge to [[_COMMUNITY_extract_js]]
- 1 edge to [[_COMMUNITY_test_vue_extraction.py]]
- 1 edge to [[_COMMUNITY_extract_groovy]]
- 1 edge to [[_COMMUNITY__edges_with_relation]]
- 1 edge to [[_COMMUNITY_extract_cpp]]
- 1 edge to [[_COMMUNITY_test_ruby_resolution.py]]
- 1 edge to [[_COMMUNITY__relations]]
- 1 edge to [[_COMMUNITY__labels]]
- 1 edge to [[_COMMUNITY_make_id]]
- 1 edge to [[_COMMUNITY_test_security.py]]
- 1 edge to [[_COMMUNITY_e]]
- 1 edge to [[_COMMUNITY_test_extract.py]]

## Top bridge nodes
- [[_extract_generic()]] - degree 38, connects to 17 communities
- [[_swift_local_var_types()]] - degree 7, connects to 2 communities
- [[_swift_pre_scan()]] - degree 6, connects to 2 communities
- [[_csharp_member_type_table()]] - degree 5, connects to 2 communities
- [[_csharp_pre_scan_interfaces()]] - degree 5, connects to 2 communities