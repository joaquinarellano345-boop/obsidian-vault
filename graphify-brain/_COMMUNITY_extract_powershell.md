---
type: community
cohesion: 0.09
members: 22
---

# extract_powershell

**Cohesion:** 0.09 - loosely connected
**Members:** 22 nodes

## Members
- [[Dot-source `. .Shared.psm1` emits an imports_from edge.]] - rationale - tests/test_languages.py
- [[Dot-source `. .Utils.ps1` (backslash path) emits an imports_from edge.]] - rationale - tests/test_languages.py
- [[Dot-source inside a function body still produces an imports_from edge.]] - rationale - tests/test_languages.py
- [[Extract functions, classes, methods, and using statements from a .ps1 file.]] - rationale - graphify/extractors/powershell.py
- [[Import-Module -Name Bar.psm1 resolves to module stem 'bar'.]] - rationale - tests/test_languages.py
- [[Import-Module Foo at top level emits an imports_from edge.]] - rationale - tests/test_languages.py
- [[Import-Module inside a function body still produces an imports_from edge.]] - rationale - tests/test_languages.py
- [[Import-Module must not appear in raw_calls (it is an import, not a function call]] - rationale - tests/test_languages.py
- [[extract_powershell()]] - code - graphify/extractors/powershell.py
- [[test_powershell_class_base_type_emits_inherits_edge()]] - code - tests/test_languages.py
- [[test_powershell_dot_source_backslash_emits_edge()]] - code - tests/test_languages.py
- [[test_powershell_dot_source_forward_slash_emits_edge()]] - code - tests/test_languages.py
- [[test_powershell_dot_source_inside_function_emits_edge()]] - code - tests/test_languages.py
- [[test_powershell_finds_class_and_method()]] - code - tests/test_languages.py
- [[test_powershell_import_module_emits_edge()]] - code - tests/test_languages.py
- [[test_powershell_import_module_inside_function_emits_edge()]] - code - tests/test_languages.py
- [[test_powershell_import_module_not_a_raw_call()]] - code - tests/test_languages.py
- [[test_powershell_import_module_with_name_param()]] - code - tests/test_languages.py
- [[test_powershell_method_parameter_and_return_type_contexts()]] - code - tests/test_languages.py
- [[test_powershell_no_error()]] - code - tests/test_languages.py
- [[test_powershell_property_field_type_context()]] - code - tests/test_languages.py
- [[test_powershell_psm1_dispatched_and_extracted()]] - code - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_powershell
SORT file.name ASC
```

## Connections to other communities
- 16 edges to [[_COMMUNITY_test_languages.py]]
- 4 edges to [[_COMMUNITY__make_id]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY__get_extractor]]
- 1 edge to [[_COMMUNITY_extract_powershell_manifest]]

## Top bridge nodes
- [[extract_powershell()]] - degree 21, connects to 3 communities
- [[test_powershell_psm1_dispatched_and_extracted()]] - degree 3, connects to 2 communities
- [[test_powershell_class_base_type_emits_inherits_edge()]] - degree 3, connects to 1 community
- [[test_powershell_dot_source_backslash_emits_edge()]] - degree 3, connects to 1 community
- [[test_powershell_dot_source_forward_slash_emits_edge()]] - degree 3, connects to 1 community