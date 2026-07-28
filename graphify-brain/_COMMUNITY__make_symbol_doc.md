---
type: community
cohesion: 0.07
members: 28
---

# _make_symbol_doc

**Cohesion:** 0.07 - loosely connected
**Members:** 28 nodes

## Members
- [[A symbol with multiple relationships emits one edge per relationship.]] - rationale - tests/test_scip_ingest.py
- [[Helper to build a minimal SCIP document with one symbol.]] - rationale - tests/test_scip_ingest.py
- [[Implementation  TypeDefinition  Definition  Reference.]] - rationale - tests/test_scip_ingest.py
- [[Node id is derived from source_file and symbol suffix.]] - rationale - tests/test_scip_ingest.py
- [[Non-dict entries in the relationships list are silently skipped.]] - rationale - tests/test_scip_ingest.py
- [[Relationship with empty or missing symbol field is ignored.]] - rationale - tests/test_scip_ingest.py
- [[Same input produces the same node id.]] - rationale - tests/test_scip_ingest.py
- [[The same source→target→relation→location edge is only emitted once.]] - rationale - tests/test_scip_ingest.py
- [[Verify every field in the emitted edge dict.]] - rationale - tests/test_scip_ingest.py
- [[When none of is_ flags are set, relation defaults to 'scip_ref'.]] - rationale - tests/test_scip_ingest.py
- [[_make_symbol_doc()]] - code - tests/test_scip_ingest.py
- [[is_definition → relation 'scip_def'.]] - rationale - tests/test_scip_ingest.py
- [[is_implementation → relation 'scip_impl' (takes priority over is_definition).]] - rationale - tests/test_scip_ingest.py
- [[is_reference → relation 'scip_ref'.]] - rationale - tests/test_scip_ingest.py
- [[is_type_definition → relation 'scip_typed'.]] - rationale - tests/test_scip_ingest.py
- [[test_ingest_duplicate_edges_are_deduplicated()]] - code - tests/test_scip_ingest.py
- [[test_ingest_edge_structure_complete()]] - code - tests/test_scip_ingest.py
- [[test_ingest_is_definition_emits_scip_def_edge()]] - code - tests/test_scip_ingest.py
- [[test_ingest_is_implementation_emits_scip_impl_edge()]] - code - tests/test_scip_ingest.py
- [[test_ingest_is_reference_emits_scip_ref_edge()]] - code - tests/test_scip_ingest.py
- [[test_ingest_is_type_definition_emits_scip_typed_edge()]] - code - tests/test_scip_ingest.py
- [[test_ingest_multiple_relationships_on_one_symbol()]] - code - tests/test_scip_ingest.py
- [[test_ingest_node_id_contains_source_file_and_symbol_suffix()]] - code - tests/test_scip_ingest.py
- [[test_ingest_node_id_is_deterministic()]] - code - tests/test_scip_ingest.py
- [[test_ingest_relationship_item_not_a_dict_is_skipped()]] - code - tests/test_scip_ingest.py
- [[test_ingest_relationship_no_boolean_flags_defaults_to_ref()]] - code - tests/test_scip_ingest.py
- [[test_ingest_relationship_priority_order()]] - code - tests/test_scip_ingest.py
- [[test_ingest_relationship_without_target_symbol_is_skipped()]] - code - tests/test_scip_ingest.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_make_symbol_doc
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_test_scip_ingest.py]]
- 13 edges to [[_COMMUNITY_ingest_scip_json]]

## Top bridge nodes
- [[test_ingest_duplicate_edges_are_deduplicated()]] - degree 4, connects to 2 communities
- [[test_ingest_edge_structure_complete()]] - degree 4, connects to 2 communities
- [[test_ingest_is_definition_emits_scip_def_edge()]] - degree 4, connects to 2 communities
- [[test_ingest_is_implementation_emits_scip_impl_edge()]] - degree 4, connects to 2 communities
- [[test_ingest_is_reference_emits_scip_ref_edge()]] - degree 4, connects to 2 communities