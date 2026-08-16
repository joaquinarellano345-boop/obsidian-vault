---
type: community
cohesion: 0.02
members: 127
---

# test_extract.py

**Cohesion:** 0.02 - loosely connected
**Members:** 127 nodes

## Members
- [[1402 (Go) the sourceless-stub fix landed in six extractors but the Go copy]] - rationale - tests/test_extract.py
- [[1402 a class defined once but referenced via type annotations in N other     f]] - rationale - tests/test_extract.py
- [[1462 (dedicated extractors) the imported-type-stub disambiguation (the     ``o]] - rationale - tests/test_extract.py
- [[1462 imported stdlibtype stubs with the same label are distinct uses     when]] - rationale - tests/test_extract.py
- [[1522 two distinct paths whose only difference is a separator-vs-punctuation]] - rationale - tests/test_extract.py
- [[1781 safety a Python reference stub must not bind to a unique Go     function]] - rationale - tests/test_extract.py
- [[1781 safety a stub used as a base type must never resolve to a     same-named,]] - rationale - tests/test_extract.py
- [[1781 safety two same-named functions leave the reference on the stub.]] - rationale - tests/test_extract.py
- [[1781 a cross-module reference to a function must land on the real     definiti]] - rationale - tests/test_extract.py
- [[1899 variant B a symbol whose name normalizes to nothing (a minified `$`     f]] - rationale - tests/test_extract.py
- [[1941 `--out far-away-dir` must not basename every in-root node.      The CLI]] - rationale - tests/test_extract.py
- [[2082 must not over-resolve an aliased import of an EXTERNALuncorpus     modul]] - rationale - tests/test_extract.py
- [[2082 the aliased `calls` edge must survive a warm (cache-hit) re-extract.]] - rationale - tests/test_extract.py
- [[2141 repro a call to a function defined in a sourced file must produce a     r]] - rationale - tests/test_extract.py
- [[2171 `source lib.sh` with no . prefix must bind to the sibling file.      Onl]] - rationale - tests/test_extract.py
- [[2171 a sourced lib with a bash shebang but no extension must resolve.      _SH]] - rationale - tests/test_extract.py
- [[2173 a resolved worker count of 1 must not spawn a ProcessPoolExecutor.      T]] - rationale - tests/test_extract.py
- [[A JSTS call with no local definition and no import must NOT bind to a     same-]] - rationale - tests/test_extract.py
- [[A `module.func()` call must resolve only against a module the caller's own     f]] - rationale - tests/test_extract.py
- [[A call to a command that is not a function in any sourced file (an external]] - rationale - tests/test_extract.py
- [[A cross-file `calls` edge must be EXTRACTED when the caller's file has     an `i]] - rationale - tests/test_extract.py
- [[A lowercase-receiver member call (`obj.run()`, `self.run()`) must NOT be     res]] - rationale - tests/test_extract.py
- [[A real cross-file call must NOT be erased by a same-named test mock.      srcca]] - rationale - tests/test_extract.py
- [[A shebang-only bash CLI must contribute nodes with the same ID scheme     as a .]] - rationale - tests/test_extract.py
- [[After merging multiple files, no internal edges should be dangling.]] - rationale - tests/test_extract.py
- [[End-to-end integration of 2079 + 2141 (21572139) a library sourced     via]] - rationale - tests/test_extract.py
- [[Guard the 2173 skip 1 worker must still take the pool path.]] - rationale - tests/test_extract.py
- [[One src def + many same-named test stubs + caller = exactly one src edge.]] - rationale - tests/test_extract.py
- [[Same input always produces same output.]] - rationale - tests/test_extract.py
- [[The collision hash must touch only actual colliders — a path with no collision]] - rationale - tests/test_extract.py
- [[The issue's own motivating shape (2082) `from pkg import mod as alias`     gua]] - rationale - tests/test_extract.py
- [[The pre-1261 rglob-per-extension implementation, kept as a parity oracle.]] - rationale - tests/test_extract.py
- [[The real 1446 shape a viewset action `approve()` delegates to a SERVICE     ac]] - rationale - tests/test_extract.py
- [[Two different files' same-named, otherwise-undefined base class must not     col]] - rationale - tests/test_extract.py
- [[Two genuine NON-test defs of the same name + one caller = ZERO edges.      Prov]] - rationale - tests/test_extract.py
- [[Unqualified cross-file calls must not guess between duplicate helper names.]] - rationale - tests/test_extract.py
- [[When the class name is defined in 2+ files, the qualified call must not     reso]] - rationale - tests/test_extract.py
- [[Wiring check the .tsx config must use tree-sitter's `language_tsx`.]] - rationale - tests/test_extract.py
- [[Wiring the source-backed call resolver must not re-emit the ``imports_from``]] - rationale - tests/test_extract.py
- [[_extract_parallel must catch BrokenProcessPool internally and return False.]] - rationale - tests/test_extract.py
- [[_legacy_collect_files()]] - code - tests/test_extract.py
- [[`ClassName.method()` across files resolves to the class-qualified method     nod]] - rationale - tests/test_extract.py
- [[`from . import mod as alias` -- a relative sibling-module import with an     ali]] - rationale - tests/test_extract.py
- [[`from pkg import mod as alias` must resolve `alias.func()` the same way the]] - rationale - tests/test_extract.py
- [[`import mod as alias` must resolve `alias.func()` the same way `import mod`]] - rationale - tests/test_extract.py
- [[`import pkg.mod as alias` -- the dotted absolute-import form the issue     flagg]] - rationale - tests/test_extract.py
- [[`module.func()` where `module` is imported resolves to the callable that     mod]] - rationale - tests/test_extract.py
- [[collect_files must scan every directory at most once and never descend     into]] - rationale - tests/test_extract.py
- [[collect_files()]] - code - graphify/extract.py
- [[extract() must run sequential when _extract_parallel signals failure (returns Fa]] - rationale - tests/test_extract.py
- [[origin_file is an internal disambiguation hint (1462) consumed only by the]] - rationale - tests/test_extract.py
- [[test_bash_var_sourced_function_call_resolves()]] - code - tests/test_extract.py
- [[test_case_insensitive_suffix_filtering()]] - code - tests/test_extract.py
- [[test_collect_files_follows_symlinked_directory()]] - code - tests/test_extract.py
- [[test_collect_files_from_dir()]] - code - tests/test_extract.py
- [[test_collect_files_handles_circular_symlinks()]] - code - tests/test_extract.py
- [[test_collect_files_parity_with_legacy_on_fixtures()]] - code - tests/test_extract.py
- [[test_collect_files_parity_with_legacy_synthetic()]] - code - tests/test_extract.py
- [[test_collect_files_skips_hidden()]] - code - tests/test_extract.py
- [[test_collect_files_skips_out_of_root_symlinked_directory()]] - code - tests/test_extract.py
- [[test_collect_files_skips_out_of_root_symlinked_file_by_default()]] - code - tests/test_extract.py
- [[test_collect_files_walks_each_directory_once()]] - code - tests/test_extract.py
- [[test_cpp_unresolved_base_class_stubs_stay_disambiguated_by_file()]] - code - tests/test_extract.py
- [[test_cross_file_call_god_node_guard_two_real_defs()]] - code - tests/test_extract.py
- [[test_cross_file_call_promoted_to_extracted_with_import_evidence()]] - code - tests/test_extract.py
- [[test_cross_file_call_survives_many_test_mocks()]] - code - tests/test_extract.py
- [[test_cross_file_call_survives_same_named_test_mock()]] - code - tests/test_extract.py
- [[test_cross_file_calls_skip_ambiguous_duplicate_labels()]] - code - tests/test_extract.py
- [[test_cross_file_type_annotation_refs_resolve_to_single_node()]] - code - tests/test_extract.py
- [[test_degenerate_symbol_name_does_not_leak_absolute_id()]] - code - tests/test_extract.py
- [[test_dispatch_includes_sh_and_json()]] - code - tests/test_extract.py
- [[test_extract.py]] - code - tests/test_extract.py
- [[test_extract_bash_bare_source_name_resolves_to_sibling()]] - code - tests/test_extract.py
- [[test_extract_bash_call_into_extensionless_sourced_lib_resolves()]] - code - tests/test_extract.py
- [[test_extract_bash_call_to_external_command_stays_unlinked()]] - code - tests/test_extract.py
- [[test_extract_bash_call_to_sourced_function_resolves()]] - code - tests/test_extract.py
- [[test_extract_bash_relative_script_invocation_targets_existing_entrypoint()]] - code - tests/test_extract.py
- [[test_extract_bash_sourced_call_does_not_duplicate_source_edge()]] - code - tests/test_extract.py
- [[test_extract_disambiguates_duplicate_symbol_ids_by_source_path()]] - code - tests/test_extract.py
- [[test_extract_does_not_rewire_constructor_method_to_same_named_class()]] - code - tests/test_extract.py
- [[test_extract_does_not_rewire_inheritance_stub_to_same_named_function()]] - code - tests/test_extract.py
- [[test_extract_extensionless_bash_cli_end_to_end()]] - code - tests/test_extract.py
- [[test_extract_falls_back_to_sequential_when_parallel_returns_false()]] - code - tests/test_extract.py
- [[test_extract_keeps_stub_when_multiple_real_definitions_match()]] - code - tests/test_extract.py
- [[test_extract_merges_multiple_files()]] - code - tests/test_extract.py
- [[test_extract_no_missing_dep_warning_when_sql_installed()]] - code - tests/test_extract.py
- [[test_extract_no_warning_when_all_code_has_extractors()]] - code - tests/test_extract.py
- [[test_extract_parallel_returns_false_on_broken_pool()]] - code - tests/test_extract.py
- [[test_extract_parallel_skips_pool_when_max_workers_is_one()]] - code - tests/test_extract.py
- [[test_extract_parallel_still_spawns_pool_for_multiple_workers()]] - code - tests/test_extract.py
- [[test_extract_progress_final_line_uses_consistent_denominator()]] - code - tests/test_extract.py
- [[test_extract_rewires_unique_inheritance_stub_to_real_definition()]] - code - tests/test_extract.py
- [[test_extract_tsx_uses_tsx_grammar()]] - code - tests/test_extract.py
- [[test_extract_updates_raw_call_callers_after_duplicate_id_disambiguation()]] - code - tests/test_extract.py
- [[test_extract_warns_on_code_files_with_no_ast_extractor()]] - code - tests/test_extract.py
- [[test_extract_warns_when_sql_extra_missing()]] - code - tests/test_extract.py
- [[test_go_cross_file_type_refs_resolve_to_single_node()]] - code - tests/test_extract.py
- [[test_go_imported_type_stubs_do_not_collide_across_source_files()]] - code - tests/test_extract.py
- [[test_imported_type_stubs_do_not_collide_across_source_files()]] - code - tests/test_extract.py
- [[test_js_cross_file_call_without_import_emits_no_edge()]] - code - tests/test_extract.py
- [[test_make_id_consistent()]] - code - tests/test_extract.py
- [[test_make_id_no_leading_trailing_underscores()]] - code - tests/test_extract.py
- [[test_make_id_strips_dots_and_underscores()]] - code - tests/test_extract.py
- [[test_matlab_m_not_extracted_as_garbage()]] - code - tests/test_extract.py
- [[test_no_dangling_edges_on_extract()]] - code - tests/test_extract.py
- [[test_non_colliding_path_id_is_not_salted()]] - code - tests/test_extract.py
- [[test_origin_file_is_not_serialized_into_extract_output()]] - code - tests/test_extract.py
- [[test_out_of_tree_cache_root_keeps_source_file_relative_to_scan_root()]] - code - tests/test_extract.py
- [[test_python_aliased_call_survives_warm_cache()]] - code - tests/test_extract.py
- [[test_python_dotted_import_alias_module_call_resolves()]] - code - tests/test_extract.py
- [[test_python_external_aliased_import_fabricates_no_call_edge()]] - code - tests/test_extract.py
- [[test_python_from_import_alias_module_call_resolves()]] - code - tests/test_extract.py
- [[test_python_import_as_alias_module_call_resolves()]] - code - tests/test_extract.py
- [[test_python_instance_member_call_not_overconnected()]] - code - tests/test_extract.py
- [[test_python_module_qualified_call_requires_the_import()]] - code - tests/test_extract.py
- [[test_python_module_qualified_call_resolves_extracted()]] - code - tests/test_extract.py
- [[test_python_qualified_call_ambiguous_class_bails()]] - code - tests/test_extract.py
- [[test_python_qualified_call_resolves_when_method_name_collides_with_caller()]] - code - tests/test_extract.py
- [[test_python_qualified_class_method_call_resolves_extracted()]] - code - tests/test_extract.py
- [[test_python_relative_from_import_alias_module_call_resolves()]] - code - tests/test_extract.py
- [[test_python_try_except_from_import_alias_module_call_resolves()]] - code - tests/test_extract.py
- [[test_rewire_binds_cross_module_function_reference_to_definition()]] - code - tests/test_extract.py
- [[test_rewire_does_not_bind_ambiguous_function_reference()]] - code - tests/test_extract.py
- [[test_rewire_does_not_bind_function_reference_across_language()]] - code - tests/test_extract.py
- [[test_rewire_does_not_bind_supertype_stub_to_function()]] - code - tests/test_extract.py
- [[test_semantic_reference_edges_carry_context_and_source()]] - code - tests/test_extract.py
- [[test_separator_collision_paths_get_distinct_ids()]] - code - tests/test_extract.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_extractpy
SORT file.name ASC
```

## Connections to other communities
- 54 edges to [[_COMMUNITY_extract]]
- 32 edges to [[_COMMUNITY_extract_bash]]
- 20 edges to [[_COMMUNITY_extract_js]]
- 13 edges to [[_COMMUNITY_extract_python]]
- 12 edges to [[_COMMUNITY_extract_json]]
- 9 edges to [[_COMMUNITY_Path]]
- 6 edges to [[_COMMUNITY__is_ignored]]
- 6 edges to [[_COMMUNITY__get_extractor]]
- 4 edges to [[_COMMUNITY_detect.py]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 2 edges to [[_COMMUNITY_clear_cache]]
- 2 edges to [[_COMMUNITY__make_id]]
- 2 edges to [[_COMMUNITY_engine.py]]
- 2 edges to [[_COMMUNITY_make_id]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY_to_json]]
- 1 edge to [[_COMMUNITY_extract_dart]]

## Top bridge nodes
- [[test_extract.py]] - degree 172, connects to 16 communities
- [[collect_files()]] - degree 20, connects to 6 communities
- [[test_non_colliding_path_id_is_not_salted()]] - degree 5, connects to 3 communities
- [[_legacy_collect_files()]] - degree 7, connects to 2 communities
- [[test_bash_var_sourced_function_call_resolves()]] - degree 3, connects to 1 community