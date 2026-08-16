---
type: community
cohesion: 0.39
members: 8
---

# test_phantom_external_import.py

**Cohesion:** 0.39 - loosely connected
**Members:** 8 nodes

## Members
- [[1638 — an unresolved bare npm import must not alias onto an unrelated same-name]] - rationale - tests/test_phantom_external_import.py
- [[Path_87]] - code
- [[_write()_17]] - code - tests/test_phantom_external_import.py
- [[test_multiple_tsx_files_do_not_all_alias_onto_one_python_file()]] - code - tests/test_phantom_external_import.py
- [[test_no_phantom_edge_from_tsx_to_unrelated_python_file()]] - code - tests/test_phantom_external_import.py
- [[test_phantom_external_import.py]] - code - tests/test_phantom_external_import.py
- [[test_scoped_package_import_is_ref_namespaced()]] - code - tests/test_phantom_external_import.py
- [[test_unresolved_bare_import_is_ref_namespaced()]] - code - tests/test_phantom_external_import.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_phantom_external_importpy
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_build_from_json]]
- 3 edges to [[_COMMUNITY_extract]]
- 2 edges to [[_COMMUNITY__resolve_js_import_target]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_extract.py]]

## Top bridge nodes
- [[test_phantom_external_import.py]] - degree 10, connects to 4 communities
- [[test_multiple_tsx_files_do_not_all_alias_onto_one_python_file()]] - degree 5, connects to 2 communities
- [[test_no_phantom_edge_from_tsx_to_unrelated_python_file()]] - degree 5, connects to 2 communities
- [[test_scoped_package_import_is_ref_namespaced()]] - degree 2, connects to 1 community
- [[test_unresolved_bare_import_is_ref_namespaced()]] - degree 2, connects to 1 community