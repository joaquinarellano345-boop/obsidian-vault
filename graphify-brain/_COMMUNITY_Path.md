---
type: community
cohesion: 0.05
members: 49
---

# Path

**Cohesion:** 0.05 - loosely connected
**Members:** 49 nodes

## Members
- [[A freetop-level function def (label ``name()``), not a method or type.      Met]] - rationale - graphify/extract.py
- [[Cross-file resolution for PascalDelphi calls to inherited methods.  The per-fil]] - rationale - graphify/pascal_resolution.py
- [[Extract functions, methods, require() imports, and calls from a .lua file.]] - rationale - graphify/extract.py
- [[Extract imports from .svelte files script-block via JS AST + template regex fal]] - rationale - graphify/extract.py
- [[Extract uncached files in parallel using ProcessPoolExecutor.      Returns True]] - rationale - graphify/extract.py
- [[Extract uncached files sequentially (fallback for small batches).]] - rationale - graphify/extract.py
- [[Interop family of the file's language, or None when unknownnot code.]] - rationale - graphify/extract.py
- [[Map unresolved no-source stubs to a unique real definition with the same label.]] - rationale - graphify/extract.py
- [[Path_10]] - code
- [[Repoint Python absolute-import edges to the real file node under a nested     (e]] - rationale - graphify/extract.py
- [[Resolve PascalDelphi calls to a method inherited across file boundaries.      P]] - rationale - graphify/pascal_resolution.py
- [[Return True when the file contains Spock-style ``def feature()`` methods     t]] - rationale - graphify/extract.py
- [[Shared edgestub emit for the SvelteAstroVue regex-rescue import passes.]] - rationale - graphify/extract.py
- [[The Fortran C-preprocessor path is hardened against argument injection (F5).  A]] - rationale - tests/test_cpp_preprocess.py
- [[True when the file's language resolves identifiers case-insensitively (1581).]] - rationale - graphify/extract.py
- [[Whether a `.h` file is C++ rather than plain C (1547).      Mirrors `_is_objc_h]] - rationale - graphify/extract.py
- [[Whether a `.h` file is Objective-C rather than CC++ (1475).      `.h` is share]] - rationale - graphify/extract.py
- [[Whether a `.m` file is Objective-C rather than MATLABOctave (1702).      `.m`]] - rationale - graphify/extract.py
- [[Worker function for parallel extraction. Runs in a subprocess.      Must be at m]] - rationale - graphify/extract.py
- [[_emit_rescued_import()]] - code - graphify/extract.py
- [[_extract_parallel()]] - code - graphify/extract.py
- [[_extract_sequential()]] - code - graphify/extract.py
- [[_extract_single_file()]] - code - graphify/extract.py
- [[_import_python()]] - code - graphify/extract.py
- [[_is_cpp_header()]] - code - graphify/extract.py
- [[_is_objc_header()]] - code - graphify/extract.py
- [[_is_objc_source()]] - code - graphify/extract.py
- [[_is_spock_file()]] - code - graphify/extract.py
- [[_is_top_level_function_definition()]] - code - graphify/extract.py
- [[_lang_family()]] - code - graphify/extract.py
- [[_lang_is_case_insensitive()]] - code - graphify/extract.py
- [[_node_label_key()]] - code - graphify/extract.py
- [[_pascal_raw_calls()]] - code - graphify/pascal_resolution.py
- [[_raise_recursion_limit()]] - code - graphify/extract.py
- [[_repoint_python_package_imports()]] - code - graphify/extract.py
- [[_rewire_unique_stub_nodes()]] - code - graphify/extract.py
- [[_safe_extract()]] - code - graphify/extract.py
- [[_safe_extract_with_xaml_root()]] - code - graphify/extract.py
- [[_xaml_codebehind_path()]] - code - graphify/extract.py
- [[_xaml_codebehind_symbols()]] - code - graphify/extract.py
- [[_xaml_communitytoolkit_members()]] - code - graphify/extract.py
- [[_xaml_pascal_name()]] - code - graphify/extract.py
- [[_xaml_project_root()]] - code - graphify/extract.py
- [[extract_lua()]] - code - graphify/extract.py
- [[extract_svelte()]] - code - graphify/extract.py
- [[pascal_resolution.py]] - code - graphify/pascal_resolution.py
- [[resolve_pascal_inherited_calls()]] - code - graphify/pascal_resolution.py
- [[test_cpp_preprocess.py]] - code - tests/test_cpp_preprocess.py
- [[test_cpp_preprocess_passes_absolute_path()]] - code - tests/test_cpp_preprocess.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Path
SORT file.name ASC
```

## Connections to other communities
- 33 edges to [[_COMMUNITY_extract.py]]
- 9 edges to [[_COMMUNITY_test_extract.py]]
- 9 edges to [[_COMMUNITY__get_extractor]]
- 8 edges to [[_COMMUNITY_extract]]
- 8 edges to [[_COMMUNITY__make_id]]
- 7 edges to [[_COMMUNITY_test_languages.py]]
- 5 edges to [[_COMMUNITY_test_dotnet.py]]
- 3 edges to [[_COMMUNITY_test_import_extension_resolution.py]]
- 2 edges to [[_COMMUNITY_test_cache.py]]
- 2 edges to [[_COMMUNITY_extract_astro]]
- 2 edges to [[_COMMUNITY_extract_groovy]]
- 2 edges to [[_COMMUNITY_test_vue_extraction.py]]
- 2 edges to [[_COMMUNITY_test_js_import_resolution.py]]
- 2 edges to [[_COMMUNITY__is_ignored]]
- 2 edges to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY_save_semantic_cache]]
- 1 edge to [[_COMMUNITY_e]]
- 1 edge to [[_COMMUNITY__edges_with_relation]]
- 1 edge to [[_COMMUNITY_extract_cpp]]
- 1 edge to [[_COMMUNITY_extract_js]]
- 1 edge to [[_COMMUNITY_test_pascal.py]]
- 1 edge to [[_COMMUNITY__relations]]
- 1 edge to [[_COMMUNITY_extract_python]]
- 1 edge to [[_COMMUNITY_test_ruby_resolution.py]]
- 1 edge to [[_COMMUNITY__labels]]
- 1 edge to [[_COMMUNITY__is_type_like_definition]]

## Top bridge nodes
- [[Path_10]] - degree 47, connects to 20 communities
- [[_emit_rescued_import()]] - degree 9, connects to 5 communities
- [[_rewire_unique_stub_nodes()]] - degree 13, connects to 4 communities
- [[extract_svelte()]] - degree 10, connects to 4 communities
- [[_extract_single_file()]] - degree 9, connects to 4 communities