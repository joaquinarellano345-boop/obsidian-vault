---
type: community
cohesion: 0.10
members: 28
---

# test_symbol_resolution.py

**Cohesion:** 0.10 - loosely connected
**Members:** 28 nodes

## Members
- [[A non-dict per_file entry (e.g. junk fragment) must be silently skipped.]] - rationale - tests/test_symbol_resolution.py
- [[A real cross-file call must resolve to the SRC definition even when a     same-n]] - rationale - tests/test_symbol_resolution.py
- [[A test file calling save() with both a src def and a test-local def present]] - rationale - tests/test_symbol_resolution.py
- [[Items inside `raw_calls` list that aren't dicts must be dropped.]] - rationale - tests/test_symbol_resolution.py
- [[One src def plus many same-named test stubs exactly one edge to src.]] - rationale - tests/test_symbol_resolution.py
- [[Resolve unqualified raw calls conservatively after all files are known.      Thi]] - rationale - graphify/symbol_resolution.py
- [[Return raw calls from all per-file extraction fragments.      Parameter is ``Seq]] - rationale - graphify/symbol_resolution.py
- [[Tests for graphify.symbol_resolution.]] - rationale - tests/test_symbol_resolution.py
- [[The python cross-file resolver returns  (not crash) on bad raw_calls.]] - rationale - tests/test_symbol_resolution.py
- [[Two genuine NON-test defs of the same name the god-node guard must still     ho]] - rationale - tests/test_symbol_resolution.py
- [[_bash_make_id must produce identical output to _make_id for Unicode inputs.]] - rationale - tests/test_symbol_resolution.py
- [[`raw_calls` that isn't a list must yield empty.]] - rationale - tests/test_symbol_resolution.py
- [[iter_raw_calls()]] - code - graphify/symbol_resolution.py
- [[resolve_cross_file_raw_calls()]] - code - graphify/symbol_resolution.py
- [[test_bash_make_id_identical_to_make_id()]] - code - tests/test_symbol_resolution.py
- [[test_bash_make_id_unicode_matches_make_id()]] - code - tests/test_symbol_resolution.py
- [[test_iter_raw_calls_drops_non_dict_items_in_list()]] - code - tests/test_symbol_resolution.py
- [[test_iter_raw_calls_skips_non_dict_per_file_entries()]] - code - tests/test_symbol_resolution.py
- [[test_iter_raw_calls_skips_non_list_raw_calls()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_cross_file_raw_calls_call_site_is_test_prefers_test_local()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_cross_file_raw_calls_emits_unique_unqualified_call()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_cross_file_raw_calls_n_mock_scale()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_cross_file_raw_calls_real_edge_survives_test_mock()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_cross_file_raw_calls_skips_ambiguous_duplicate_labels()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_cross_file_raw_calls_skips_existing_pair()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_cross_file_raw_calls_skips_member_calls()]] - code - tests/test_symbol_resolution.py
- [[test_resolve_cross_file_raw_calls_survives_malformed_raw_calls()]] - code - tests/test_symbol_resolution.py
- [[test_symbol_resolution.py]] - code - tests/test_symbol_resolution.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_symbol_resolutionpy
SORT file.name ASC
```

## Connections to other communities
- 17 edges to [[_COMMUNITY_symbol_resolution.py]]
- 13 edges to [[_COMMUNITY_resolve_bash_source_edges]]
- 8 edges to [[_COMMUNITY_resolve_python_import_guided_calls]]
- 6 edges to [[_COMMUNITY_parse_python_import_aliases]]
- 3 edges to [[_COMMUNITY_make_id]]
- 1 edge to [[_COMMUNITY_disambiguate_ambiguous_candidates]]

## Top bridge nodes
- [[test_symbol_resolution.py]] - degree 55, connects to 5 communities
- [[resolve_cross_file_raw_calls()]] - degree 16, connects to 2 communities
- [[iter_raw_calls()]] - degree 8, connects to 1 community
- [[test_bash_make_id_unicode_matches_make_id()]] - degree 3, connects to 1 community
- [[test_bash_make_id_identical_to_make_id()]] - degree 2, connects to 1 community