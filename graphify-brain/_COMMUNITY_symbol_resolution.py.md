---
type: community
cohesion: 0.13
members: 23
---

# symbol_resolution.py

**Cohesion:** 0.13 - loosely connected
**Members:** 23 nodes

## Members
- [[Any_11]] - code
- [[Build ``(module_stem, normalized_symbol_name) - node_ids``.      This index is]] - rationale - graphify/symbol_resolution.py
- [[Build label - node id list for conservative cross-file resolution.]] - rationale - graphify/symbol_resolution.py
- [[Deterministic symbol indexing and conservative cross-file resolution helpers.]] - rationale - graphify/symbol_resolution.py
- [[Documentpaperimageconcept nodes MUST NOT be indexed as call targets,     even]] - rationale - tests/test_symbol_resolution.py
- [[Normalize a node label into the key used for call resolution.]] - rationale - graphify/symbol_resolution.py
- [[Return True when a node is suitable for deterministic symbol lookup.      Requir]] - rationale - graphify/symbol_resolution.py
- [[Return all existing sourcetargetrelation edge triples.      Includes relation]] - rationale - graphify/symbol_resolution.py
- [[Return the stem of a node's source file.]] - rationale - graphify/symbol_resolution.py
- [[_node_source_stem()]] - code - graphify/symbol_resolution.py
- [[build_label_index()]] - code - graphify/symbol_resolution.py
- [[build_python_symbol_index()]] - code - graphify/symbol_resolution.py
- [[existing_edge_pairs()]] - code - graphify/symbol_resolution.py
- [[label index must not include documentpaperimage nodes even when     label and]] - rationale - tests/test_symbol_resolution.py
- [[node_is_resolvable_symbol()]] - code - graphify/symbol_resolution.py
- [[normalise_callable_label()]] - code - graphify/symbol_resolution.py
- [[symbol_resolution.py]] - code - graphify/symbol_resolution.py
- [[test_build_label_index_collects_unique_symbols()]] - code - tests/test_symbol_resolution.py
- [[test_build_label_index_excludes_non_code_nodes()]] - code - tests/test_symbol_resolution.py
- [[test_build_python_symbol_index_uses_module_stem_and_label()]] - code - tests/test_symbol_resolution.py
- [[test_node_is_resolvable_symbol_requires_code_file_type()]] - code - tests/test_symbol_resolution.py
- [[test_node_is_resolvable_symbol_skips_rationale_and_doc_tags()]] - code - tests/test_symbol_resolution.py
- [[test_normalise_callable_label_strips_function_punctuation()]] - code - tests/test_symbol_resolution.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/symbol_resolutionpy
SORT file.name ASC
```

## Connections to other communities
- 17 edges to [[_COMMUNITY_test_symbol_resolution.py]]
- 4 edges to [[_COMMUNITY_resolve_bash_source_edges]]
- 4 edges to [[_COMMUNITY_parse_python_import_aliases]]
- 4 edges to [[_COMMUNITY_resolve_python_import_guided_calls]]
- 3 edges to [[_COMMUNITY_make_id]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY__make_id]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_disambiguate_ambiguous_candidates]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_test_security.py]]

## Top bridge nodes
- [[symbol_resolution.py]] - degree 27, connects to 12 communities
- [[existing_edge_pairs()]] - degree 6, connects to 3 communities
- [[build_python_symbol_index()]] - degree 9, connects to 2 communities
- [[Any_11]] - degree 8, connects to 2 communities
- [[build_label_index()]] - degree 9, connects to 1 community