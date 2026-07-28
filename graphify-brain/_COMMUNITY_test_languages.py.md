---
type: community
cohesion: 0.03
members: 123
---

# test_languages.py

**Cohesion:** 0.03 - loosely connected
**Members:** 123 nodes

## Members
- [[Dot-source `. .Shared.psm1` emits an imports_from edge.]] - rationale - tests/test_languages.py
- [[Dot-source `. .Utils.ps1` (backslash path) emits an imports_from edge.]] - rationale - tests/test_languages.py
- [[Dot-source inside a function body still produces an imports_from edge.]] - rationale - tests/test_languages.py
- [[Extract classes, methods, constructors, and imports from a .groovy.gradle file.]] - rationale - graphify/extract.py
- [[Extract functions and includes from a .c.h file.]] - rationale - graphify/extract.py
- [[Extract functions, classes, and includes from a .cpp.cc.cxx.hpp file.]] - rationale - graphify/extract.py
- [[Extract modules, functions, imports, and calls from a .ex.exs file.]] - rationale - graphify/extractors/elixir.py
- [[Extract modules, structs, functions, imports, and calls from a .jl file.]] - rationale - graphify/extractors/julia.py
- [[If the injected field's type name is ambiguous (two classes named Database),]] - rationale - tests/test_languages.py
- [[Import-Module -Name Bar.psm1 resolves to module stem 'bar'.]] - rationale - tests/test_languages.py
- [[Import-Module Foo at top level emits an imports_from edge.]] - rationale - tests/test_languages.py
- [[Import-Module inside a function body still produces an imports_from edge.]] - rationale - tests/test_languages.py
- [[Import-Module must not appear in raw_calls (it is an import, not a function call]] - rationale - tests/test_languages.py
- [[Path_18]] - code
- [[Path_23]] - code
- [[Qualified (`using Base.Threads`) and relative (`using ..Mod`) imports     must e]] - rationale - tests/test_languages.py
- [[Quoted `import X.h` edges must target the real (disambiguated) file node id,]] - rationale - tests/test_languages.py
- [[Regression for 915 `class Derived  public Base {}` should emit an inherits ed]] - rationale - tests/test_languages.py
- [[Structs use the same ` Base` syntax as classes and must also emit inherits.]] - rationale - tests/test_languages.py
- [[Tests for language extractors Java, C, C++, Ruby, C, Kotlin, Scala, PHP, Swift]] - rationale - tests/test_languages.py
- [[The decisive 1316 guardrail two classes each define `query`, but the     injec]] - rationale - tests/test_languages.py
- [[_edges_with_relation()]] - code - tests/test_languages.py
- [[_node_by_label()]] - code - tests/test_languages.py
- [[_normalize_symbol_label()]] - code - tests/test_languages.py
- [[_ts_label_calls()]] - code - tests/test_languages.py
- [[`alias Foo.{Bar, Baz}` must emit one imports edge per expanded module.      The]] - rationale - tests/test_languages.py
- [[`class PooledClient  public ConnectionHttpClient` must emit the inherits]] - rationale - tests/test_languages.py
- [[`class Sub  Base` must emit an inherits edge.      Ruby exposes the base class]] - rationale - tests/test_languages.py
- [[`class X extends Base` must emit an inherits edge.      tree-sitter-groovy expos]] - rationale - tests/test_languages.py
- [[`class X implements Iface` must emit an implements edge.]] - rationale - tests/test_languages.py
- [[`extension Foo` in a separate file from `class Foo` must resolve to a     single]] - rationale - tests/test_languages.py
- [[extract_c()]] - code - graphify/extract.py
- [[extract_cpp()]] - code - graphify/extract.py
- [[extract_elixir()]] - code - graphify/extractors/elixir.py
- [[extract_groovy()]] - code - graphify/extract.py
- [[extract_julia()]] - code - graphify/extractors/julia.py
- [[test_c_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_c_calls_are_extracted()]] - code - tests/test_languages.py
- [[test_c_emits_calls()]] - code - tests/test_languages.py
- [[test_c_finds_functions()]] - code - tests/test_languages.py
- [[test_c_finds_includes()]] - code - tests/test_languages.py
- [[test_c_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_c_no_error()]] - code - tests/test_languages.py
- [[test_c_parameter_and_return_type_contexts()]] - code - tests/test_languages.py
- [[test_cpp_class_inherits_edge()]] - code - tests/test_languages.py
- [[test_cpp_field_and_template_argument_contexts()]] - code - tests/test_languages.py
- [[test_cpp_finds_class()]] - code - tests/test_languages.py
- [[test_cpp_finds_methods()]] - code - tests/test_languages.py
- [[test_cpp_generic_parents_include_type_argument_references()]] - code - tests/test_languages.py
- [[test_cpp_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_cpp_method_parameter_and_return_type_contexts()]] - code - tests/test_languages.py
- [[test_cpp_no_error()]] - code - tests/test_languages.py
- [[test_cpp_struct_inherits_edge()]] - code - tests/test_languages.py
- [[test_cuda_finds_kernel_and_device_functions()]] - code - tests/test_languages.py
- [[test_cuda_finds_struct()]] - code - tests/test_languages.py
- [[test_cuda_host_call_edges()]] - code - tests/test_languages.py
- [[test_cuda_no_error()]] - code - tests/test_languages.py
- [[test_dmf_elem_under_window()]] - code - tests/test_languages.py
- [[test_dmf_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_dmf_no_error()]] - code - tests/test_languages.py
- [[test_dmi_no_error()]] - code - tests/test_languages.py
- [[test_dmi_state_contained_by_file()]] - code - tests/test_languages.py
- [[test_elixir_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_elixir_finds_calls()]] - code - tests/test_languages.py
- [[test_elixir_finds_functions()]] - code - tests/test_languages.py
- [[test_elixir_finds_imports()]] - code - tests/test_languages.py
- [[test_elixir_finds_module()]] - code - tests/test_languages.py
- [[test_elixir_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_elixir_method_edges()]] - code - tests/test_languages.py
- [[test_elixir_multi_alias_expands()]] - code - tests/test_languages.py
- [[test_groovy_extends_edge()]] - code - tests/test_languages.py
- [[test_groovy_finds_class()]] - code - tests/test_languages.py
- [[test_groovy_finds_imports()]] - code - tests/test_languages.py
- [[test_groovy_finds_methods()]] - code - tests/test_languages.py
- [[test_groovy_implements_edge()]] - code - tests/test_languages.py
- [[test_groovy_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_groovy_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_groovy_no_error()]] - code - tests/test_languages.py
- [[test_groovy_spock_finds_class()]] - code - tests/test_languages.py
- [[test_groovy_spock_finds_feature_methods()]] - code - tests/test_languages.py
- [[test_groovy_spock_finds_method_with_apostrophe()]] - code - tests/test_languages.py
- [[test_groovy_spock_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_groovy_spock_preserves_import_edges()]] - code - tests/test_languages.py
- [[test_java_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_julia_abstract_concrete_hierarchy_inherits()]] - code - tests/test_languages.py
- [[test_julia_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_julia_finds_abstract_type()]] - code - tests/test_languages.py
- [[test_julia_finds_calls()]] - code - tests/test_languages.py
- [[test_julia_finds_functions()]] - code - tests/test_languages.py
- [[test_julia_finds_imports()]] - code - tests/test_languages.py
- [[test_julia_finds_inherits()]] - code - tests/test_languages.py
- [[test_julia_finds_module()]] - code - tests/test_languages.py
- [[test_julia_finds_short_function()]] - code - tests/test_languages.py
- [[test_julia_finds_structs()]] - code - tests/test_languages.py
- [[test_julia_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_julia_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_julia_qualified_and_relative_imports()]] - code - tests/test_languages.py
- [[test_julia_struct_field_type_context()]] - code - tests/test_languages.py
- [[test_languages.py]] - code - tests/test_languages.py
- [[test_metal_finds_kernel_function_and_struct()]] - code - tests/test_languages.py
- [[test_metal_is_code_extension()]] - code - tests/test_languages.py
- [[test_metal_no_error()]] - code - tests/test_languages.py
- [[test_objc_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_objc_quoted_import_edges_resolve_to_real_nodes()]] - code - tests/test_languages.py
- [[test_php_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_php_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_powershell_dot_source_backslash_emits_edge()]] - code - tests/test_languages.py
- [[test_powershell_dot_source_forward_slash_emits_edge()]] - code - tests/test_languages.py
- [[test_powershell_dot_source_inside_function_emits_edge()]] - code - tests/test_languages.py
- [[test_powershell_finds_class_and_method()]] - code - tests/test_languages.py
- [[test_powershell_import_module_emits_edge()]] - code - tests/test_languages.py
- [[test_powershell_import_module_inside_function_emits_edge()]] - code - tests/test_languages.py
- [[test_powershell_import_module_not_a_raw_call()]] - code - tests/test_languages.py
- [[test_powershell_import_module_with_name_param()]] - code - tests/test_languages.py
- [[test_powershell_no_error()]] - code - tests/test_languages.py
- [[test_ruby_inherits_edge()]] - code - tests/test_languages.py
- [[test_swift_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_swift_extension_across_files_merges_into_canonical_type()]] - code - tests/test_languages.py
- [[test_swift_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_ts_constructor_injection_calls_edge()]] - code - tests/test_languages.py
- [[test_ts_injected_field_ambiguous_type_emits_no_edge()]] - code - tests/test_languages.py
- [[test_ts_injected_field_resolves_to_typed_class_not_same_named_collision()]] - code - tests/test_languages.py
- [[this.repo.findById() in a class with constructor(private repo IUserRepository)]] - rationale - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_languagespy
SORT file.name ASC
```

## Connections to other communities
- 69 edges to [[_COMMUNITY__edge_labels]]
- 52 edges to [[_COMMUNITY__labels]]
- 35 edges to [[_COMMUNITY__relations]]
- 30 edges to [[_COMMUNITY_Path]]
- 28 edges to [[_COMMUNITY__read_text]]
- 25 edges to [[_COMMUNITY_extract_objc]]
- 20 edges to [[_COMMUNITY_extract_dm]]
- 14 edges to [[_COMMUNITY_test_dotnet.py]]
- 13 edges to [[_COMMUNITY__corpus]]
- 13 edges to [[_COMMUNITY_extract_fortran]]
- 11 edges to [[_COMMUNITY_extract_markdown]]
- 9 edges to [[_COMMUNITY_extract_js]]
- 8 edges to [[_COMMUNITY_extract_powershell_manifest]]
- 6 edges to [[_COMMUNITY_extract.py]]
- 6 edges to [[_COMMUNITY_extract]]
- 4 edges to [[_COMMUNITY_engine.py]]
- 3 edges to [[_COMMUNITY_test_ruby_resolution.py]]
- 2 edges to [[_COMMUNITY_test_multilang.py]]
- 1 edge to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY__extract_pascal_regex]]
- 1 edge to [[_COMMUNITY_e]]

## Top bridge nodes
- [[test_languages.py]] - degree 364, connects to 18 communities
- [[extract_julia()]] - degree 24, connects to 4 communities
- [[extract_cpp()]] - degree 23, connects to 4 communities
- [[extract_groovy()]] - degree 20, connects to 4 communities
- [[extract_c()]] - degree 13, connects to 3 communities