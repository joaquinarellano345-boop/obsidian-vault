---
type: community
cohesion: 0.12
members: 17
---

# extract_powershell_manifest

**Cohesion:** 0.12 - loosely connected
**Members:** 17 nodes

## Members
- [[All imports_from edge sources must exist in the node set.]] - rationale - tests/test_languages.py
- [[Extract module dependency edges from a PowerShell .psd1 manifest file.      .psd]] - rationale - graphify/extractors/powershell.py
- [[ModuleVersion values ('5.0', '1.0.0') must NOT appear as import targets.]] - rationale - tests/test_languages.py
- [[NestedModules = @('Helpers.psm1', 'Logger.psm1') produces edges for both.]] - rationale - tests/test_languages.py
- [[Path_28]] - code
- [[RequiredModules hashtable form @{{ ModuleName='Pester' }} produces an imports_fr]] - rationale - tests/test_languages.py
- [[RequiredModules string form 'PSReadLine' produces an imports_from edge.]] - rationale - tests/test_languages.py
- [[RootModule = 'MyModule.psm1' produces an imports_from edge to 'mymodule'.]] - rationale - tests/test_languages.py
- [[extract_powershell_manifest()]] - code - graphify/extractors/powershell.py
- [[test_powershell_psd1_has_file_node()]] - code - tests/test_languages.py
- [[test_powershell_psd1_nested_modules()]] - code - tests/test_languages.py
- [[test_powershell_psd1_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_powershell_psd1_no_error()]] - code - tests/test_languages.py
- [[test_powershell_psd1_no_moduleversion_as_edge()]] - code - tests/test_languages.py
- [[test_powershell_psd1_required_modules_hashtable()]] - code - tests/test_languages.py
- [[test_powershell_psd1_required_modules_string()]] - code - tests/test_languages.py
- [[test_powershell_psd1_root_module()]] - code - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_powershell_manifest
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_test_languages.py]]
- 4 edges to [[_COMMUNITY__read_text]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_e]]

## Top bridge nodes
- [[extract_powershell_manifest()]] - degree 15, connects to 3 communities
- [[test_powershell_psd1_nested_modules()]] - degree 3, connects to 1 community
- [[test_powershell_psd1_no_dangling_edges()]] - degree 3, connects to 1 community
- [[test_powershell_psd1_no_moduleversion_as_edge()]] - degree 3, connects to 1 community
- [[test_powershell_psd1_required_modules_hashtable()]] - degree 3, connects to 1 community