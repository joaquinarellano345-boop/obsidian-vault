---
type: community
cohesion: 0.13
members: 15
---

# extract_go

**Cohesion:** 0.13 - loosely connected
**Members:** 15 nodes

## Members
- [[Extract functions, methods, type declarations, and imports from a .go file.]] - rationale - graphify/extractors/go.py
- [[Methods on the same receiver type must share one canonical type node.]] - rationale - tests/test_languages.py
- [[Path_21]] - code
- [[Regression review feedback flagged a hypothetical UnboundLocalError in     extr]] - rationale - tests/test_multilang.py
- [[Type node id should be scoped to directory, not file stem.]] - rationale - tests/test_languages.py
- [[_confidences()]] - code - tests/test_multilang.py
- [[extract_go()]] - code - graphify/extractors/go.py
- [[test_go_finds_constructor()]] - code - tests/test_multilang.py
- [[test_go_finds_methods()]] - code - tests/test_multilang.py
- [[test_go_has_extracted_calls()]] - code - tests/test_multilang.py
- [[test_go_method_declaration_emits_refs_only_when_name_present()]] - code - tests/test_multilang.py
- [[test_go_no_dangling_edges()]] - code - tests/test_multilang.py
- [[test_go_receiver_methods_share_type_node()]] - code - tests/test_languages.py
- [[test_go_receiver_uses_pkg_scope()]] - code - tests/test_languages.py
- [[test_go_struct_named_field_emits_field_context()]] - code - tests/test_multilang.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_go
SORT file.name ASC
```

## Connections to other communities
- 10 edges to [[_COMMUNITY_test_multilang.py]]
- 4 edges to [[_COMMUNITY__make_id]]
- 4 edges to [[_COMMUNITY_extract_rust]]
- 3 edges to [[_COMMUNITY__labels_1]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 2 edges to [[_COMMUNITY_test_languages.py]]
- 1 edge to [[_COMMUNITY_e]]

## Top bridge nodes
- [[extract_go()]] - degree 24, connects to 6 communities
- [[test_go_finds_constructor()]] - degree 3, connects to 2 communities
- [[test_go_finds_methods()]] - degree 3, connects to 2 communities
- [[test_go_struct_named_field_emits_field_context()]] - degree 3, connects to 2 communities
- [[test_go_receiver_methods_share_type_node()]] - degree 3, connects to 1 community