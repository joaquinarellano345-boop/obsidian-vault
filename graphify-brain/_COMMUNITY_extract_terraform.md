---
type: community
cohesion: 0.26
members: 17
---

# extract_terraform

**Cohesion:** 0.26 - loosely connected
**Members:** 17 nodes

## Members
- [[Extract TerraformHCL blocks and the references between them via tree-sitter.]] - rationale - graphify/extractors/terraform.py
- [[Path_34]] - code
- [[Path_104]] - code
- [[Tests for the TerraformHCL extractor (graphifyextract.py, issue 187).]] - rationale - tests/test_terraform.py
- [[_labels()_10]] - code - tests/test_terraform.py
- [[_rel_pairs()]] - code - tests/test_terraform.py
- [[_write()_25]] - code - tests/test_terraform.py
- [[extract_terraform()]] - code - graphify/extractors/terraform.py
- [[test_cross_file_references_resolve_after_merge()]] - code - tests/test_terraform.py
- [[test_depends_on_edge()]] - code - tests/test_terraform.py
- [[test_empty_and_commentonly_files_are_safe()]] - code - tests/test_terraform.py
- [[test_file_contains_blocks()]] - code - tests/test_terraform.py
- [[test_meta_heads_not_emitted()]] - code - tests/test_terraform.py
- [[test_no_error_and_all_block_types_become_nodes()]] - code - tests/test_terraform.py
- [[test_reference_edges()]] - code - tests/test_terraform.py
- [[test_terraform.py]] - code - tests/test_terraform.py
- [[test_tfvars_key_value_is_safe()]] - code - tests/test_terraform.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_terraform
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY__make_id]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY__get_extractor]]
- 1 edge to [[_COMMUNITY_e]]
- 1 edge to [[_COMMUNITY__fixture]]
- 1 edge to [[_COMMUNITY_test_extractors_registry.py]]

## Top bridge nodes
- [[extract_terraform()]] - degree 18, connects to 6 communities
- [[test_terraform.py]] - degree 15, connects to 3 communities
- [[test_cross_file_references_resolve_after_merge()]] - degree 4, connects to 1 community