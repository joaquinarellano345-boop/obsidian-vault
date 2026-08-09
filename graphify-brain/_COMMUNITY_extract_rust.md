---
type: community
cohesion: 0.14
members: 18
---

# extract_rust

**Cohesion:** 0.14 - loosely connected
**Members:** 18 nodes

## Members
- [[Enum variant payload types must emit `references` edges.      Tuple variants (`C]] - rationale - tests/test_multilang.py
- [[Extract functions, structs, enums, traits, impl methods, and use declarations fr]] - rationale - graphify/extractors/rust.py
- [[Path_31]] - code
- [[Tuple struct fields (`struct Wrapper(A, B);`) nest their positional types     un]] - rationale - tests/test_multilang.py
- [[_edge_labels()_1]] - code - tests/test_multilang.py
- [[_normalize_symbol_label()_1]] - code - tests/test_multilang.py
- [[extract_rust()]] - code - graphify/extractors/rust.py
- [[test_go_embeds_struct_field()]] - code - tests/test_multilang.py
- [[test_go_interface_embedding_emits_embeds()]] - code - tests/test_multilang.py
- [[test_go_method_parameter_return_contexts()]] - code - tests/test_multilang.py
- [[test_rust_calls_are_extracted()]] - code - tests/test_multilang.py
- [[test_rust_enum_variant_references()]] - code - tests/test_multilang.py
- [[test_rust_method_parameter_return_and_generic_contexts()]] - code - tests/test_multilang.py
- [[test_rust_no_dangling_edges()]] - code - tests/test_multilang.py
- [[test_rust_struct_field_emits_field_context()]] - code - tests/test_multilang.py
- [[test_rust_supertrait_emits_inherits()]] - code - tests/test_multilang.py
- [[test_rust_trait_impl_emits_implements()]] - code - tests/test_multilang.py
- [[test_rust_tuple_struct_field_references()]] - code - tests/test_multilang.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_rust
SORT file.name ASC
```

## Connections to other communities
- 16 edges to [[_COMMUNITY_test_multilang.py]]
- 4 edges to [[_COMMUNITY__make_id]]
- 4 edges to [[_COMMUNITY_extract_go]]
- 3 edges to [[_COMMUNITY__labels_1]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_e]]

## Top bridge nodes
- [[extract_rust()]] - degree 23, connects to 5 communities
- [[_edge_labels()_1]] - degree 12, connects to 2 communities
- [[test_go_embeds_struct_field()]] - degree 3, connects to 2 communities
- [[test_go_interface_embedding_emits_embeds()]] - degree 3, connects to 2 communities
- [[test_go_method_parameter_return_contexts()]] - degree 3, connects to 2 communities