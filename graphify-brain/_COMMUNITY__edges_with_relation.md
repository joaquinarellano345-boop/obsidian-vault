---
type: community
cohesion: 0.07
members: 31
---

# _edges_with_relation

**Cohesion:** 0.07 - loosely connected
**Members:** 31 nodes

## Members
- [[Extract functions and includes from a .c.h file.]] - rationale - graphify/extract.py
- [[Extract modules, functions, imports, and calls from a .ex.exs file.]] - rationale - graphify/extractors/elixir.py
- [[Path_18]] - code
- [[_edges_with_relation()]] - code - tests/test_languages.py
- [[`alias Foo.{Bar, Baz}` must emit one imports edge per expanded module.      The]] - rationale - tests/test_languages.py
- [[extract_c()]] - code - graphify/extract.py
- [[extract_elixir()]] - code - graphify/extractors/elixir.py
- [[test_c_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_c_calls_are_extracted()]] - code - tests/test_languages.py
- [[test_c_emits_calls()]] - code - tests/test_languages.py
- [[test_c_finds_functions()]] - code - tests/test_languages.py
- [[test_c_finds_includes()]] - code - tests/test_languages.py
- [[test_c_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_c_no_error()]] - code - tests/test_languages.py
- [[test_c_parameter_and_return_type_contexts()]] - code - tests/test_languages.py
- [[test_cpp_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_elixir_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_elixir_finds_calls()]] - code - tests/test_languages.py
- [[test_elixir_finds_functions()]] - code - tests/test_languages.py
- [[test_elixir_finds_imports()]] - code - tests/test_languages.py
- [[test_elixir_finds_module()]] - code - tests/test_languages.py
- [[test_elixir_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_elixir_method_edges()]] - code - tests/test_languages.py
- [[test_elixir_multi_alias_expands()]] - code - tests/test_languages.py
- [[test_java_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_julia_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_objc_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_php_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_php_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_swift_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_swift_import_edges_have_import_context()]] - code - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_edges_with_relation
SORT file.name ASC
```

## Connections to other communities
- 32 edges to [[_COMMUNITY_test_languages.py]]
- 4 edges to [[_COMMUNITY__make_id]]
- 3 edges to [[_COMMUNITY__relations]]
- 3 edges to [[_COMMUNITY__labels]]
- 3 edges to [[_COMMUNITY_extract_dm]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY__extract_generic]]
- 1 edge to [[_COMMUNITY_extract_cpp]]
- 1 edge to [[_COMMUNITY_extract_objc]]
- 1 edge to [[_COMMUNITY_extract_groovy]]

## Top bridge nodes
- [[extract_c()]] - degree 13, connects to 4 communities
- [[_edges_with_relation()]] - degree 20, connects to 3 communities
- [[extract_elixir()]] - degree 15, connects to 2 communities
- [[test_c_finds_functions()]] - degree 3, connects to 2 communities
- [[test_c_finds_includes()]] - degree 3, connects to 2 communities