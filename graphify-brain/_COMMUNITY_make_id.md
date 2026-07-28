---
type: community
cohesion: 0.12
members: 27
---

# make_id

**Cohesion:** 0.12 - loosely connected
**Members:** 27 nodes

## Members
- [[811 non-ASCII identifiers must yield distinct, non-empty IDs rather than     c]] - rationale - tests/test_id_normalization_contract.py
- [[Build a canonical node ID from one or more name parts.      Parts are joined wit]] - rationale - graphify/ids.py
- [[Build a stable node ID via the single shared recipe (1378).]] - rationale - graphify/mcp_ingest.py
- [[Drift guard for the node-ID normalization contract.  Three independent producers]] - rationale - tests/test_id_normalization_contract.py
- [[Guard against re-forking the two public callers must resolve to the same     un]] - rationale - tests/test_id_normalization_contract.py
- [[Multi-part make_id == normalize_id of the joined parts (the builder only     eve]] - rationale - tests/test_id_normalization_contract.py
- [[Output is lowercase and contains no pathpunctuation separators.]] - rationale - tests/test_id_normalization_contract.py
- [[Single source of truth for node-ID normalization.  Three independent producers m]] - rationale - graphify/ids.py
- [[The AST id-maker and the builder's reconciler must agree, char for char.]] - rationale - tests/test_id_normalization_contract.py
- [[The collision hash must touch only actual colliders — a path with no collision]] - rationale - tests/test_extract.py
- [[_make_id()_1]] - code - graphify/mcp_ingest.py
- [[given]] - code
- [[ids.py]] - code - graphify/ids.py
- [[make_id()]] - code - graphify/ids.py
- [[normalize_id()]] - code - graphify/ids.py
- [[parametrize_10]] - code
- [[rNormalize a single ID string to its canonical form.      Idempotent ``norma]] - rationale - graphify/ids.py
- [[test_both_callers_share_one_implementation()]] - code - tests/test_id_normalization_contract.py
- [[test_id_normalization_contract.py]] - code - tests/test_id_normalization_contract.py
- [[test_make_id_joins_then_normalizes()]] - code - tests/test_id_normalization_contract.py
- [[test_make_id_matches_normalize_id()]] - code - tests/test_id_normalization_contract.py
- [[test_non_colliding_path_id_is_not_salted()]] - code - tests/test_extract.py
- [[test_normalize_id_is_idempotent()]] - code - tests/test_id_normalization_contract.py
- [[test_normalized_ids_are_safe_node_ids()]] - code - tests/test_id_normalization_contract.py
- [[test_property_make_id_equals_normalize_id()]] - code - tests/test_id_normalization_contract.py
- [[test_property_normalize_id_idempotent()]] - code - tests/test_id_normalization_contract.py
- [[test_unicode_identifiers_do_not_collapse_to_empty()]] - code - tests/test_id_normalization_contract.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/make_id
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_graphifybuild.py]]
- 7 edges to [[_COMMUNITY__read_text]]
- 5 edges to [[_COMMUNITY_build_from_json]]
- 4 edges to [[_COMMUNITY__extract_pascal_regex]]
- 3 edges to [[_COMMUNITY_engine.py]]
- 3 edges to [[_COMMUNITY_test_extract.py]]
- 3 edges to [[_COMMUNITY_test_manifest_ingest.py]]
- 3 edges to [[_COMMUNITY__bash_make_id]]
- 2 edges to [[_COMMUNITY_symbol_resolution.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_extract]]
- 1 edge to [[_COMMUNITY_test_mcp_ingest.py]]

## Top bridge nodes
- [[make_id()]] - degree 24, connects to 8 communities
- [[ids.py]] - degree 11, connects to 6 communities
- [[normalize_id()]] - degree 18, connects to 5 communities
- [[test_id_normalization_contract.py]] - degree 16, connects to 3 communities
- [[test_non_colliding_path_id_is_not_salted()]] - degree 5, connects to 3 communities