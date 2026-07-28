---
type: community
cohesion: 0.04
members: 59
---

# Path

**Cohesion:** 0.04 - loosely connected
**Members:** 59 nodes

## Members
- [[2040 for C the nested type now gets a real `contains` edge from its     enclo]] - rationale - tests/test_languages.py
- [[A `.h` with a C++ class must route to extract_cpp, not extract_c (which has]] - rationale - tests/test_languages.py
- [[A bridging header that is only `import X.h` (no @interface) must route to]] - rationale - tests/test_languages.py
- [[A plain C header (no C++ signal) must keep its extract_c routing.]] - rationale - tests/test_languages.py
- [[An ObjC `.h` (has @interface) routes to extract_objc; a plain C `.h` stays     o]] - rationale - tests/test_languages.py
- [[Any_2]] - code
- [[Extensionless CLIs resolve their extractor from the shebang, mirroring     detec]] - rationale - tests/test_extract.py
- [[Extract C type declarations, methods, namespaces, and usings from a .cs file.]] - rationale - graphify/extract.py
- [[Extract uncached files sequentially (fallback for small batches).]] - rationale - graphify/extract.py
- [[Path_10]] - code
- [[Return True when the file contains Spock-style ``def feature()`` methods     t]] - rationale - graphify/extract.py
- [[Return the correct extractor function for a file, or None if unsupported.]] - rationale - graphify/extract.py
- [[Whether a `.h` file is C++ rather than plain C (1547).      Mirrors `_is_objc_h]] - rationale - graphify/extract.py
- [[Whether a `.h` file is Objective-C rather than CC++ (1475).      `.h` is share]] - rationale - graphify/extract.py
- [[Whether a `.m` file is Objective-C rather than MATLABOctave (1702).      `.m`]] - rationale - graphify/extract.py
- [[Worker function for parallel extraction. Runs in a subprocess.      Must be at m]] - rationale - graphify/extract.py
- [[_extract_sequential()]] - code - graphify/extract.py
- [[_extract_single_file()]] - code - graphify/extract.py
- [[_get_extractor should route .psd1 to extract_powershell_manifest.]] - rationale - tests/test_languages.py
- [[_get_extractor()]] - code - graphify/extract.py
- [[_is_cpp_header()]] - code - graphify/extract.py
- [[_is_objc_header()]] - code - graphify/extract.py
- [[_is_objc_source()]] - code - graphify/extract.py
- [[_is_spock_file()]] - code - graphify/extract.py
- [[_raise_recursion_limit()]] - code - graphify/extract.py
- [[_references()]] - code - tests/test_languages.py
- [[_safe_extract()]] - code - graphify/extract.py
- [[_safe_extract_with_xaml_root()]] - code - graphify/extract.py
- [[_xaml_codebehind_path()]] - code - graphify/extract.py
- [[_xaml_codebehind_symbols()]] - code - graphify/extract.py
- [[_xaml_csharp_class_nodes()]] - code - graphify/extract.py
- [[_xaml_project_root()]] - code - graphify/extract.py
- [[extract_csharp()]] - code - graphify/extract.py
- [[test_cpp_header_routes_to_cpp_extractor()]] - code - tests/test_languages.py
- [[test_csharp_call_edges_have_call_context()]] - code - tests/test_languages.py
- [[test_csharp_field_type_references_have_field_context()]] - code - tests/test_languages.py
- [[test_csharp_finds_class()]] - code - tests/test_languages.py
- [[test_csharp_finds_interface()]] - code - tests/test_languages.py
- [[test_csharp_finds_methods()]] - code - tests/test_languages.py
- [[test_csharp_finds_usings()]] - code - tests/test_languages.py
- [[test_csharp_implements_iprocessor()]] - code - tests/test_languages.py
- [[test_csharp_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_csharp_inherits_edge()]] - code - tests/test_languages.py
- [[test_csharp_nested_type_gets_containment_edge()]] - code - tests/test_languages.py
- [[test_csharp_no_error()]] - code - tests/test_languages.py
- [[test_csharp_parameter_return_and_generic_contexts()]] - code - tests/test_languages.py
- [[test_csharp_property_type_references_have_field_context()]] - code - tests/test_languages.py
- [[test_csharp_splits_inherits_and_implements_edges()]] - code - tests/test_languages.py
- [[test_dispatch_table()]] - code - tests/test_dotnet.py
- [[test_extensionless_shebang_via_dispatch()]] - code - tests/test_extract.py
- [[test_extensionless_without_usable_shebang_stays_unsupported()]] - code - tests/test_extract.py
- [[test_extract_bash_via_dispatch()]] - code - tests/test_extract.py
- [[test_extract_json_via_dispatch()]] - code - tests/test_extract.py
- [[test_get_extractor_routes_matlab_m_away_from_objc()]] - code - tests/test_extract.py
- [[test_objc_header_dispatch_routes_objc_not_c()]] - code - tests/test_languages.py
- [[test_objc_header_with_import_routes_to_objc()]] - code - tests/test_languages.py
- [[test_plain_c_header_stays_on_c_extractor()]] - code - tests/test_languages.py
- [[test_powershell_psd1_dispatched()]] - code - tests/test_languages.py
- [[test_powershell_psm1_dispatched_and_extracted()]] - code - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Path
SORT file.name ASC
```

## Connections to other communities
- 30 edges to [[_COMMUNITY_test_languages.py]]
- 17 edges to [[_COMMUNITY_extract.py]]
- 8 edges to [[_COMMUNITY__edge_labels]]
- 7 edges to [[_COMMUNITY_test_extract.py]]
- 7 edges to [[_COMMUNITY_test_dotnet.py]]
- 5 edges to [[_COMMUNITY__read_text]]
- 5 edges to [[_COMMUNITY_test_mcp_ingest.py]]
- 4 edges to [[_COMMUNITY_extract]]
- 4 edges to [[_COMMUNITY__labels]]
- 3 edges to [[_COMMUNITY_extract_astro]]
- 3 edges to [[_COMMUNITY__rebuild_code]]
- 2 edges to [[_COMMUNITY_test_cache.py]]
- 2 edges to [[_COMMUNITY__load_graphifyignore]]
- 2 edges to [[_COMMUNITY_engine.py]]
- 2 edges to [[_COMMUNITY__extract_parallel]]
- 2 edges to [[_COMMUNITY__relations]]
- 2 edges to [[_COMMUNITY__rewire_unique_stub_nodes]]
- 2 edges to [[_COMMUNITY_test_manifest_ingest.py]]
- 1 edge to [[_COMMUNITY_save_semantic_cache]]
- 1 edge to [[_COMMUNITY_classify_file]]
- 1 edge to [[_COMMUNITY__is_noise_dir]]
- 1 edge to [[_COMMUNITY_e]]
- 1 edge to [[_COMMUNITY_extract_js]]
- 1 edge to [[_COMMUNITY_test_pascal.py]]
- 1 edge to [[_COMMUNITY_extract_python]]
- 1 edge to [[_COMMUNITY__extract_python_rationale]]
- 1 edge to [[_COMMUNITY_test_ruby_resolution.py]]
- 1 edge to [[_COMMUNITY__extract_pascal_regex]]
- 1 edge to [[_COMMUNITY_test_vue_extraction.py]]
- 1 edge to [[_COMMUNITY_test_js_import_resolution.py]]
- 1 edge to [[_COMMUNITY_extract_objc]]

## Top bridge nodes
- [[Path_10]] - degree 47, connects to 21 communities
- [[_get_extractor()]] - degree 39, connects to 11 communities
- [[_extract_single_file()]] - degree 9, connects to 4 communities
- [[_xaml_csharp_class_nodes()]] - degree 8, connects to 4 communities
- [[extract_csharp()]] - degree 21, connects to 3 communities