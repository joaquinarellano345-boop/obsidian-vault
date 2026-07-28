---
type: community
cohesion: 0.19
members: 23
---

# test_semantic_cleanup.py

**Cohesion:** 0.19 - loosely connected
**Members:** 23 nodes

## Members
- [[1561 an alias-keyed hyperedge must not be rejected for a missing     `nodes` l]] - rationale - tests/test_semantic_cleanup.py
- [[An unknownsynonym file_type is NOT a validation failure build_from_json     co]] - rationale - tests/test_semantic_cleanup.py
- [[LLM output with file_type='concept' must pass validation for the same reason.]] - rationale - tests/test_semantic_cleanup.py
- [[LLM output with file_type='rationale' must pass validation so the cleanup     pa]] - rationale - tests/test_semantic_cleanup.py
- [[Return validation errors for an untrusted semantic extraction fragment.      Emp]] - rationale - graphify/semantic_cleanup.py
- [[Tests for graphify.semantic_cleanup.validate_semantic_fragment (825).]] - rationale - tests/test_semantic_cleanup.py
- [[_valid_fragment()]] - code - tests/test_semantic_cleanup.py
- [[test_semantic_cleanup.py]] - code - tests/test_semantic_cleanup.py
- [[test_validate_accepts_node_ids_keyed_hyperedge()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_hyperedge_caps_count()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_hyperedge_rejects_bad_id()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_hyperedge_rejects_bad_node_ref()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_hyperedge_requires_list()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_semantic_fragment_accepts_concept_file_type()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_semantic_fragment_accepts_rationale_file_type()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_semantic_fragment_accepts_unknown_file_type()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_semantic_fragment_accepts_valid()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_semantic_fragment_rejects_non_object()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_semantic_fragment_rejects_oversize_payload()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_semantic_fragment_rejects_path_separator_in_id()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_semantic_fragment_rejects_too_many_edges()]] - code - tests/test_semantic_cleanup.py
- [[test_validate_semantic_fragment_rejects_too_many_nodes()]] - code - tests/test_semantic_cleanup.py
- [[validate_semantic_fragment()]] - code - graphify/semantic_cleanup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_semantic_cleanuppy
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_sanitize_semantic_fragment]]
- 5 edges to [[_COMMUNITY_load_validated_semantic_fragment]]
- 4 edges to [[_COMMUNITY_semantic_cleanup.py]]
- 3 edges to [[_COMMUNITY_test_merge_chunks_validation.py]]

## Top bridge nodes
- [[test_semantic_cleanup.py]] - degree 29, connects to 3 communities
- [[validate_semantic_fragment()]] - degree 22, connects to 3 communities
- [[_valid_fragment()]] - degree 15, connects to 1 community