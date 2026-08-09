---
type: community
cohesion: 0.17
members: 26
---

# test_vue_extraction.py

**Cohesion:** 0.17 - loosely connected
**Members:** 26 nodes

## Members
- [[A Vue 3.3+ generic= attribute containing '' (e.g. Recordstring, unknown)]] - rationale - tests/test_vue_extraction.py
- [[A ``.vue`` calling an imported function wires to the real symbol across files.]] - rationale - tests/test_vue_extraction.py
- [[Blank everything outside ``script`` bodies, keeping ``r````n``.      Repl]] - rationale - graphify/extractors/resolution.py
- [[Extract imports, symbols, and type refs from a ``.vue`` SFC.      Masks the non-]] - rationale - graphify/extract.py
- [[Path_112]] - code
- [[Tests for ``.vue`` SFC extraction.  Feeding a whole SFC to the JS grammar produc]] - rationale - tests/test_vue_extraction.py
- [[The SFC must not be parsed as one JS blob.      With the bug, a real SFC yields]] - rationale - tests/test_vue_extraction.py
- [[Vue allows a classic ``script`` plus ``script setup``; both are TS.]] - rationale - tests/test_vue_extraction.py
- [[_labels()_12]] - code - tests/test_vue_extraction.py
- [[_targets()_2]] - code - tests/test_vue_extraction.py
- [[_vue_mask_non_script()]] - code - graphify/extractors/resolution.py
- [[_write()_31]] - code - tests/test_vue_extraction.py
- [[extract_vue()]] - code - graphify/extract.py
- [[test_dynamic_import_recovered()]] - code - tests/test_vue_extraction.py
- [[test_generic_component_open_tag_with_angle_brackets()]] - code - tests/test_vue_extraction.py
- [[test_mask_preserves_line_numbers_and_blanks_markup()]] - code - tests/test_vue_extraction.py
- [[test_plain_js_script_block()]] - code - tests/test_vue_extraction.py
- [[test_script_setup_extracts_symbols_with_correct_lines()]] - code - tests/test_vue_extraction.py
- [[test_script_setup_ts_static_imports_resolve()]] - code - tests/test_vue_extraction.py
- [[test_template_only_file_does_not_crash()]] - code - tests/test_vue_extraction.py
- [[test_two_script_blocks_both_parsed()]] - code - tests/test_vue_extraction.py
- [[test_typed_props_reference_imported_type()]] - code - tests/test_vue_extraction.py
- [[test_vue_extraction.py]] - code - tests/test_vue_extraction.py
- [[test_vue_is_in_code_extensions()]] - code - tests/test_vue_extraction.py
- [[test_vue_joins_cross_file_symbol_resolution()]] - code - tests/test_vue_extraction.py
- [[test_whole_file_to_js_grammar_would_extract_nothing()]] - code - tests/test_vue_extraction.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_vue_extractionpy
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_extract.py]]
- 3 edges to [[_COMMUNITY_extract_astro]]
- 2 edges to [[_COMMUNITY_extract]]
- 1 edge to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY__make_id]]
- 1 edge to [[_COMMUNITY__extract_generic]]

## Top bridge nodes
- [[extract_vue()]] - degree 19, connects to 5 communities
- [[test_vue_extraction.py]] - degree 20, connects to 3 communities
- [[_vue_mask_non_script()]] - degree 7, connects to 1 community
- [[test_vue_joins_cross_file_symbol_resolution()]] - degree 4, connects to 1 community