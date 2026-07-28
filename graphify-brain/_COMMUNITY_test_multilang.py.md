---
type: community
cohesion: 0.07
members: 59
---

# test_multilang.py

**Cohesion:** 0.07 - loosely connected
**Members:** 59 nodes

## Members
- [[Enum variant payload types must emit `references` edges.      Tuple variants (`C]] - rationale - tests/test_multilang.py
- [[Extract functions, methods, type declarations, and imports from a .go file.]] - rationale - graphify/extractors/go.py
- [[Extract functions, structs, enums, traits, impl methods, and use declarations fr]] - rationale - graphify/extractors/rust.py
- [[Methods on the same receiver type must share one canonical type node.]] - rationale - tests/test_languages.py
- [[Path_21]] - code
- [[Path_31]] - code
- [[Regression review feedback flagged a hypothetical UnboundLocalError in     extr]] - rationale - tests/test_multilang.py
- [[Scoped calls (Typemethod) and blocklisted names must not produce     INFERRED]] - rationale - tests/test_multilang.py
- [[Tests for multi-language AST extraction JSTS, Go, Rust, SQL.]] - rationale - tests/test_multilang.py
- [[Tuple struct fields (`struct Wrapper(A, B);`) nest their positional types     un]] - rationale - tests/test_multilang.py
- [[Type node id should be scoped to directory, not file stem.]] - rationale - tests/test_languages.py
- [[_call_pairs()]] - code - tests/test_multilang.py
- [[_confidences()]] - code - tests/test_multilang.py
- [[_edge_labels()_1]] - code - tests/test_multilang.py
- [[_edges_with_relation()_1]] - code - tests/test_multilang.py
- [[_labels()_5]] - code - tests/test_multilang.py
- [[_normalize_symbol_label()_1]] - code - tests/test_multilang.py
- [[extract_go()]] - code - graphify/extractors/go.py
- [[extract_rust()]] - code - graphify/extractors/rust.py
- [[test_cache_hit_returns_same_result()]] - code - tests/test_multilang.py
- [[test_cache_miss_after_file_change()]] - code - tests/test_multilang.py
- [[test_extract_dispatches_all_languages()]] - code - tests/test_multilang.py
- [[test_go_call_edges_have_call_context()]] - code - tests/test_multilang.py
- [[test_go_embeds_struct_field()]] - code - tests/test_multilang.py
- [[test_go_emits_calls()]] - code - tests/test_multilang.py
- [[test_go_finds_constructor()]] - code - tests/test_multilang.py
- [[test_go_finds_methods()]] - code - tests/test_multilang.py
- [[test_go_finds_struct()]] - code - tests/test_multilang.py
- [[test_go_has_extracted_calls()]] - code - tests/test_multilang.py
- [[test_go_import_edges_have_import_context()]] - code - tests/test_multilang.py
- [[test_go_interface_embedding_emits_embeds()]] - code - tests/test_multilang.py
- [[test_go_method_declaration_emits_refs_only_when_name_present()]] - code - tests/test_multilang.py
- [[test_go_method_parameter_return_contexts()]] - code - tests/test_multilang.py
- [[test_go_no_dangling_edges()]] - code - tests/test_multilang.py
- [[test_go_receiver_methods_share_type_node()]] - code - tests/test_languages.py
- [[test_go_receiver_uses_pkg_scope()]] - code - tests/test_languages.py
- [[test_go_struct_named_field_emits_field_context()]] - code - tests/test_multilang.py
- [[test_multilang.py]] - code - tests/test_multilang.py
- [[test_rust_call_edges_have_call_context()]] - code - tests/test_multilang.py
- [[test_rust_calls_are_extracted()]] - code - tests/test_multilang.py
- [[test_rust_emits_calls()]] - code - tests/test_multilang.py
- [[test_rust_enum_variant_references()]] - code - tests/test_multilang.py
- [[test_rust_finds_function()]] - code - tests/test_multilang.py
- [[test_rust_finds_impl_methods()]] - code - tests/test_multilang.py
- [[test_rust_finds_struct()]] - code - tests/test_multilang.py
- [[test_rust_import_edges_have_import_context()]] - code - tests/test_multilang.py
- [[test_rust_method_parameter_return_and_generic_contexts()]] - code - tests/test_multilang.py
- [[test_rust_no_cross_crate_spurious_edges()]] - code - tests/test_multilang.py
- [[test_rust_no_dangling_edges()]] - code - tests/test_multilang.py
- [[test_rust_struct_field_emits_field_context()]] - code - tests/test_multilang.py
- [[test_rust_supertrait_emits_inherits()]] - code - tests/test_multilang.py
- [[test_rust_trait_impl_emits_implements()]] - code - tests/test_multilang.py
- [[test_rust_tuple_struct_field_references()]] - code - tests/test_multilang.py
- [[test_ts_call_edges_have_call_context()]] - code - tests/test_multilang.py
- [[test_ts_emits_calls()]] - code - tests/test_multilang.py
- [[test_ts_finds_class()]] - code - tests/test_multilang.py
- [[test_ts_finds_function()]] - code - tests/test_multilang.py
- [[test_ts_finds_methods()]] - code - tests/test_multilang.py
- [[test_ts_import_edges_have_import_context()]] - code - tests/test_multilang.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_multilangpy
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY__extract_sql_or_skip]]
- 10 edges to [[_COMMUNITY__read_text]]
- 9 edges to [[_COMMUNITY_extract_js]]
- 5 edges to [[_COMMUNITY_extract]]
- 3 edges to [[_COMMUNITY_extract.py]]
- 2 edges to [[_COMMUNITY_e]]
- 2 edges to [[_COMMUNITY_test_languages.py]]

## Top bridge nodes
- [[test_multilang.py]] - degree 63, connects to 4 communities
- [[extract_go()]] - degree 24, connects to 3 communities
- [[extract_rust()]] - degree 23, connects to 3 communities
- [[test_go_receiver_methods_share_type_node()]] - degree 3, connects to 1 community
- [[test_go_receiver_uses_pkg_scope()]] - degree 3, connects to 1 community