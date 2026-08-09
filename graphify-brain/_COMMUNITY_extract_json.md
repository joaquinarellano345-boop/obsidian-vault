---
type: community
cohesion: 0.10
members: 21
---

# extract_json

**Cohesion:** 0.10 - loosely connected
**Members:** 21 nodes

## Members
- [[A JSON file whose root is an array is data, never a configmanifest.]] - rationale - tests/test_extract.py
- [[A data-shaped .json (eval fixture  dataset) must NOT emit per-key nodes.]] - rationale - tests/test_extract.py
- [[An arbitrarily-named JSON with config keys (dependencies) is still extracted.]] - rationale - tests/test_extract.py
- [[Extract structure and dependency edges from a configmanifest .json file.]] - rationale - graphify/extractors/json_config.py
- [[Path_22]] - code
- [[True if a .json file is a recognized configmanifest worth AST-extracting.]] - rationale - graphify/extractors/json_config.py
- [[_is_config_json()]] - code - graphify/extractors/json_config.py
- [[extract_json()]] - code - graphify/extractors/json_config.py
- [[test_extract_json_config_by_filename_still_extracted()]] - code - tests/test_extract.py
- [[test_extract_json_config_by_key_probe()]] - code - tests/test_extract.py
- [[test_extract_json_data_file_skipped()]] - code - tests/test_extract.py
- [[test_extract_json_dependencies_become_imports()]] - code - tests/test_extract.py
- [[test_extract_json_extends_resolved()]] - code - tests/test_extract.py
- [[test_extract_json_handles_invalid_json()]] - code - tests/test_extract.py
- [[test_extract_json_import_and_extends_targets_are_real_nodes()]] - code - tests/test_extract.py
- [[test_extract_json_large_file_skipped()]] - code - tests/test_extract.py
- [[test_extract_json_nested_contains()]] - code - tests/test_extract.py
- [[test_extract_json_no_self_loops()]] - code - tests/test_extract.py
- [[test_extract_json_top_level_array_skipped()]] - code - tests/test_extract.py
- [[test_extract_json_top_level_keys()]] - code - tests/test_extract.py
- [[tsconfig.json must still be AST-extracted even without telltale keys.]] - rationale - tests/test_extract.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_json
SORT file.name ASC
```

## Connections to other communities
- 12 edges to [[_COMMUNITY_test_extract.py]]
- 5 edges to [[_COMMUNITY__make_id]]
- 3 edges to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY_extract]]
- 1 edge to [[_COMMUNITY_make_id]]
- 1 edge to [[_COMMUNITY_e]]

## Top bridge nodes
- [[extract_json()]] - degree 23, connects to 4 communities
- [[test_extract_json_import_and_extends_targets_are_real_nodes()]] - degree 4, connects to 3 communities
- [[_is_config_json()]] - degree 5, connects to 2 communities
- [[test_extract_json_config_by_filename_still_extracted()]] - degree 3, connects to 1 community
- [[test_extract_json_config_by_key_probe()]] - degree 3, connects to 1 community