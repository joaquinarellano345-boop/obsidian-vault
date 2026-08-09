---
type: community
cohesion: 0.03
members: 123
---

# test_languages.py

**Cohesion:** 0.03 - loosely connected
**Members:** 123 nodes

## Members
- [[2040 for C the nested type now gets a real `contains` edge from its     enclo]] - rationale - tests/test_languages.py
- [[2040 a nested classobjecttrait's `contains` edge sources from its     ENCLOS]] - rationale - tests/test_languages.py
- [[Class properties with leading qualifiers (randlocalprotectedetc.) must     st]] - rationale - tests/test_languages.py
- [[Extract C type declarations, methods, namespaces, and usings from a .cs file.]] - rationale - graphify/extract.py
- [[Extract classes, interfaces, methods, constructors, and imports from a .java fil]] - rationale - graphify/extract.py
- [[Extract classes, objects, functions, and imports from a .kt.kts file.]] - rationale - graphify/extract.py
- [[Extract modules, functions, tasks, package imports, instantiations, and     Syst]] - rationale - graphify/extractors/verilog.py
- [[Extract modules, structs, functions, imports, and calls from a .jl file.]] - rationale - graphify/extractors/julia.py
- [[If the injected field's type name is ambiguous (two classes named Database),]] - rationale - tests/test_languages.py
- [[Path_23]] - code
- [[Path_35]] - code
- [[Qualified (`using Base.Threads`) and relative (`using ..Mod`) imports     must e]] - rationale - tests/test_languages.py
- [[Quoted `import X.h` edges must target the real (disambiguated) file node id,]] - rationale - tests/test_languages.py
- [[Tests for language extractors Java, C, C++, Ruby, C, Kotlin, Scala, PHP, Swift]] - rationale - tests/test_languages.py
- [[The decisive 1316 guardrail two classes each define `query`, but the     injec]] - rationale - tests/test_languages.py
- [[_edge_labels()]] - code - tests/test_languages.py
- [[_node_by_label()]] - code - tests/test_languages.py
- [[_normalize_symbol_label()]] - code - tests/test_languages.py
- [[_references()]] - code - tests/test_languages.py
- [[_ts_label_calls()]] - code - tests/test_languages.py
- [[`Foo alloc init` must emit a `references` edge to the project class Foo (14]] - rationale - tests/test_languages.py
- [[`class Foo  Bar by baz` wraps the delegated interface in an     `explicit_deleg]] - rationale - tests/test_languages.py
- [[`class Sub  Base` must emit an inherits edge.      Ruby exposes the base class]] - rationale - tests/test_languages.py
- [[`extension Foo` in a separate file from `class Foo` must resolve to a     single]] - rationale - tests/test_languages.py
- [[extract_csharp()]] - code - graphify/extract.py
- [[extract_java()]] - code - graphify/extract.py
- [[extract_julia()]] - code - graphify/extractors/julia.py
- [[extract_kotlin()]] - code - graphify/extract.py
- [[extract_scala()]] - code - graphify/extract.py
- [[extract_verilog()]] - code - graphify/extractors/verilog.py
- [[test_csharp_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_csharp_field_type_references_have_field_context()]] - code - tests/test_languages.py
- [[test_csharp_finds_class()]] - code - tests/test_languages.py
- [[test_csharp_finds_interface()]] - code - tests/test_languages.py
- [[test_csharp_finds_methods()]] - code - tests/test_languages.py
- [[test_csharp_finds_usings()]] - code - tests/test_languages.py
- [[test_csharp_implements_iprocessor()]] - code - tests/test_languages.py
- [[test_csharp_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_csharp_inherits_edge()]] - code - tests/test_languages.py
- [[test_csharp_nested_type_gets_containment_edge()]] - code - tests/test_languages.py
- [[test_csharp_no_error()]] - code - tests/test_languages.py
- [[test_csharp_parameter_return_and_generic_contexts()]] - code - tests/test_languages.py
- [[test_csharp_property_type_references_have_field_context()]] - code - tests/test_languages.py
- [[test_csharp_splits_inherits_and_implements_edges()]] - code - tests/test_languages.py
- [[test_dmf_elem_under_window()]] - code - tests/test_languages.py
- [[test_dmf_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_dmf_no_error()]] - code - tests/test_languages.py
- [[test_dmi_no_error()]] - code - tests/test_languages.py
- [[test_dmi_state_contained_by_file()]] - code - tests/test_languages.py
- [[test_java_enum_and_annotation_declarations_are_type_nodes()]] - code - tests/test_languages.py
- [[test_java_enum_constants_have_case_of_edge()]] - code - tests/test_languages.py
- [[test_java_field_type_references_have_field_context()]] - code - tests/test_languages.py
- [[test_java_finds_class()]] - code - tests/test_languages.py
- [[test_java_finds_interface()]] - code - tests/test_languages.py
- [[test_java_finds_methods()]] - code - tests/test_languages.py
- [[test_java_generic_parents_include_type_argument_references()]] - code - tests/test_languages.py
- [[test_java_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_java_no_error()]] - code - tests/test_languages.py
- [[test_java_normalizes_inherits_and_implements()]] - code - tests/test_languages.py
- [[test_java_parameter_return_generic_and_attribute_contexts()]] - code - tests/test_languages.py
- [[test_java_record_component_type_references()]] - code - tests/test_languages.py
- [[test_java_record_components_skip_type_parameters()]] - code - tests/test_languages.py
- [[test_java_type_annotations_have_attribute_context()]] - code - tests/test_languages.py
- [[test_java_type_parameters_do_not_emit_references()]] - code - tests/test_languages.py
- [[test_julia_abstract_concrete_hierarchy_inherits()]] - code - tests/test_languages.py
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
- [[test_kotlin_builtin_types_not_emitted_as_references()]] - code - tests/test_languages.py
- [[test_kotlin_enum_entries_have_case_of_edge()]] - code - tests/test_languages.py
- [[test_kotlin_finds_class()]] - code - tests/test_languages.py
- [[test_kotlin_finds_data_class()]] - code - tests/test_languages.py
- [[test_kotlin_finds_function()]] - code - tests/test_languages.py
- [[test_kotlin_finds_methods()]] - code - tests/test_languages.py
- [[test_kotlin_interface_delegation_emits_implements()]] - code - tests/test_languages.py
- [[test_kotlin_no_error()]] - code - tests/test_languages.py
- [[test_kotlin_parameter_return_generic_and_field_contexts()]] - code - tests/test_languages.py
- [[test_kotlin_splits_inherits_and_implements()]] - code - tests/test_languages.py
- [[test_kotlin_user_types_still_emit_references()]] - code - tests/test_languages.py
- [[test_languages.py]] - code - tests/test_languages.py
- [[test_metal_is_code_extension()]] - code - tests/test_languages.py
- [[test_nested_types_contained_by_enclosing_type()]] - code - tests/test_languages.py
- [[test_objc_alloc_init_emits_type_reference()]] - code - tests/test_languages.py
- [[test_objc_quoted_import_edges_resolve_to_real_nodes()]] - code - tests/test_languages.py
- [[test_ruby_inherits_edge()]] - code - tests/test_languages.py
- [[test_scala_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_scala_constructor_parameter_field_context()]] - code - tests/test_languages.py
- [[test_scala_finds_class()]] - code - tests/test_languages.py
- [[test_scala_finds_methods()]] - code - tests/test_languages.py
- [[test_scala_finds_object()]] - code - tests/test_languages.py
- [[test_scala_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_scala_method_return_type_context()]] - code - tests/test_languages.py
- [[test_scala_no_error()]] - code - tests/test_languages.py
- [[test_scala_splits_inherits_and_mixes_in()]] - code - tests/test_languages.py
- [[test_scala_val_definition_field_context()]] - code - tests/test_languages.py
- [[test_scala_var_definition_field_context()]] - code - tests/test_languages.py
- [[test_swift_enum_associated_value_type_emits_references()]] - code - tests/test_languages.py
- [[test_swift_extension_across_files_merges_into_canonical_type()]] - code - tests/test_languages.py
- [[test_swift_extension_conformance_emits_implements()]] - code - tests/test_languages.py
- [[test_swift_parameter_return_generic_and_field_contexts()]] - code - tests/test_languages.py
- [[test_swift_protocol_conformance_emits_implements()]] - code - tests/test_languages.py
- [[test_swift_splits_inherits_and_implements()]] - code - tests/test_languages.py
- [[test_systemverilog_does_not_emit_type_parameter_refs()]] - code - tests/test_languages.py
- [[test_systemverilog_field_parameter_return_and_generic_contexts()]] - code - tests/test_languages.py
- [[test_systemverilog_missing_file_returns_empty()]] - code - tests/test_languages.py
- [[test_systemverilog_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_systemverilog_no_error()]] - code - tests/test_languages.py
- [[test_systemverilog_preserves_existing_module_extraction()]] - code - tests/test_languages.py
- [[test_systemverilog_qualified_field_references()]] - code - tests/test_languages.py
- [[test_systemverilog_splits_inherits_and_implements()]] - code - tests/test_languages.py
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
- 61 edges to [[_COMMUNITY__labels]]
- 33 edges to [[_COMMUNITY__relations]]
- 32 edges to [[_COMMUNITY__edges_with_relation]]
- 30 edges to [[_COMMUNITY_extract_objc]]
- 18 edges to [[_COMMUNITY_extract_cpp]]
- 18 edges to [[_COMMUNITY_extract_dm]]
- 18 edges to [[_COMMUNITY__make_id]]
- 16 edges to [[_COMMUNITY_extract_powershell]]
- 14 edges to [[_COMMUNITY_extract_groovy]]
- 14 edges to [[_COMMUNITY_test_dotnet.py]]
- 14 edges to [[_COMMUNITY_extract_fortran]]
- 13 edges to [[_COMMUNITY__corpus]]
- 11 edges to [[_COMMUNITY_extract_markdown]]
- 9 edges to [[_COMMUNITY_extract.py]]
- 9 edges to [[_COMMUNITY_extract_js]]
- 8 edges to [[_COMMUNITY_extract_powershell_manifest]]
- 7 edges to [[_COMMUNITY_Path]]
- 7 edges to [[_COMMUNITY_extract]]
- 6 edges to [[_COMMUNITY__get_extractor]]
- 4 edges to [[_COMMUNITY__extract_generic]]
- 3 edges to [[_COMMUNITY_test_ruby_resolution.py]]
- 2 edges to [[_COMMUNITY_engine.py]]
- 2 edges to [[_COMMUNITY_e]]
- 2 edges to [[_COMMUNITY_extract_go]]
- 1 edge to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY__is_ignored]]

## Top bridge nodes
- [[test_languages.py]] - degree 364, connects to 22 communities
- [[_edge_labels()]] - degree 58, connects to 7 communities
- [[extract_julia()]] - degree 24, connects to 5 communities
- [[extract_java()]] - degree 23, connects to 5 communities
- [[extract_csharp()]] - degree 21, connects to 4 communities