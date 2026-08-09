---
type: community
cohesion: 0.13
members: 27
---

# validate_extraction

**Cohesion:** 0.13 - loosely connected
**Members:** 27 nodes

## Members
- [[2194 nodes carrying `name``path` instead of `label``source_file` must     be]] - rationale - tests/test_build.py
- [[Merge multiple extraction results into one graph.]] - rationale - worked/mixed-corpus/raw/build.py
- [[Raise ValueError with all errors if extraction is invalid.]] - rationale - graphify/validate.py
- [[Validate an extraction JSON dict against the graphify schema.     Returns a list]] - rationale - graphify/validate.py
- [[assert_valid()]] - code - graphify/validate.py
- [[build()_2]] - code - worked/mixed-corpus/raw/build.py
- [[build_from_json()_1]] - code - worked/mixed-corpus/raw/build.py
- [[rawbuild.py]] - code - worked/mixed-corpus/raw/build.py
- [[test_assert_valid_passes_silently()]] - code - tests/test_validate.py
- [[test_assert_valid_raises_on_errors()]] - code - tests/test_validate.py
- [[test_dangling_edge_source()]] - code - tests/test_validate.py
- [[test_dangling_edge_target()]] - code - tests/test_validate.py
- [[test_invalid_confidence()]] - code - tests/test_validate.py
- [[test_invalid_file_type()]] - code - tests/test_validate.py
- [[test_legacy_aliases_valid_after_build_canonicalization()]] - code - tests/test_validate.py
- [[test_legacy_node_name_path_aliases_folded()]] - code - tests/test_build.py
- [[test_missing_edges_key()]] - code - tests/test_validate.py
- [[test_missing_node_field()]] - code - tests/test_validate.py
- [[test_missing_nodes_key()]] - code - tests/test_validate.py
- [[test_non_hashable_edge_endpoint_reported_not_raised()]] - code - tests/test_validate.py
- [[test_non_hashable_node_id_does_not_mask_valid_ids()]] - code - tests/test_validate.py
- [[test_non_hashable_node_id_reported_not_raised()]] - code - tests/test_validate.py
- [[test_not_a_dict()]] - code - tests/test_validate.py
- [[test_valid_passes()]] - code - tests/test_validate.py
- [[test_validate.py]] - code - tests/test_validate.py
- [[validate.py]] - code - graphify/validate.py
- [[validate_extraction()]] - code - graphify/validate.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/validate_extraction
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_build_from_json]]
- 6 edges to [[_COMMUNITY_introspect_postgres]]
- 2 edges to [[_COMMUNITY_graphifybuild.py]]
- 2 edges to [[_COMMUNITY_test_evidence_binding.py]]
- 1 edge to [[_COMMUNITY_test_scip_ingest.py]]
- 1 edge to [[_COMMUNITY_ingest_scip_json]]
- 1 edge to [[_COMMUNITY_Graph]]

## Top bridge nodes
- [[validate_extraction()]] - degree 31, connects to 6 communities
- [[validate.py]] - degree 5, connects to 2 communities
- [[test_validate.py]] - degree 19, connects to 1 community
- [[test_legacy_node_name_path_aliases_folded()]] - degree 4, connects to 1 community
- [[build_from_json()_1]] - degree 4, connects to 1 community