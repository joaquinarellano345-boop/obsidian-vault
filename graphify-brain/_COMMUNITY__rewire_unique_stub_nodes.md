---
type: community
cohesion: 0.12
members: 17
---

# _rewire_unique_stub_nodes

**Cohesion:** 0.12 - loosely connected
**Members:** 17 nodes

## Members
- [[1781 safety a Python reference stub must not bind to a unique Go     function]] - rationale - tests/test_extract.py
- [[1781 safety a stub used as a base type must never resolve to a     same-named,]] - rationale - tests/test_extract.py
- [[1781 safety two same-named functions leave the reference on the stub.]] - rationale - tests/test_extract.py
- [[1781 a cross-module reference to a function must land on the real     definiti]] - rationale - tests/test_extract.py
- [[A freetop-level function def (label ``name()``), not a method or type.      Met]] - rationale - graphify/extract.py
- [[Interop family of the file's language, or None when unknownnot code.]] - rationale - graphify/extract.py
- [[Map unresolved no-source stubs to a unique real definition with the same label.]] - rationale - graphify/extract.py
- [[True when the file's language resolves identifiers case-insensitively (1581).]] - rationale - graphify/extract.py
- [[_is_top_level_function_definition()]] - code - graphify/extract.py
- [[_lang_family()]] - code - graphify/extract.py
- [[_lang_is_case_insensitive()]] - code - graphify/extract.py
- [[_node_label_key()]] - code - graphify/extract.py
- [[_rewire_unique_stub_nodes()]] - code - graphify/extract.py
- [[test_rewire_binds_cross_module_function_reference_to_definition()]] - code - tests/test_extract.py
- [[test_rewire_does_not_bind_ambiguous_function_reference()]] - code - tests/test_extract.py
- [[test_rewire_does_not_bind_function_reference_across_language()]] - code - tests/test_extract.py
- [[test_rewire_does_not_bind_supertype_stub_to_function()]] - code - tests/test_extract.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_rewire_unique_stub_nodes
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_extract.py]]
- 5 edges to [[_COMMUNITY_test_extract.py]]
- 3 edges to [[_COMMUNITY_extract]]
- 2 edges to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY__is_type_like_definition]]

## Top bridge nodes
- [[_rewire_unique_stub_nodes()]] - degree 13, connects to 4 communities
- [[_lang_family()]] - degree 5, connects to 3 communities
- [[_lang_is_case_insensitive()]] - degree 5, connects to 3 communities
- [[_is_top_level_function_definition()]] - degree 3, connects to 1 community
- [[test_rewire_binds_cross_module_function_reference_to_definition()]] - degree 3, connects to 1 community