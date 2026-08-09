---
type: community
cohesion: 0.08
members: 49
---

# test_file_slice.py

**Cohesion:** 0.08 - loosely connected
**Members:** 49 nodes

## Members
- [[A contiguous ``start, end)`` character range of a splittable text file.      ``]] - rationale - graphify/file_slice.py
- [[Contiguous ``(start, end)`` ranges covering all of ``text``, each ≤ max_chars.]] - rationale - graphify/file_slice.py
- [[FileSlice]] - code - graphify/file_slice.py
- [[Intra-file slicing for oversized text documents (1369).  The extraction packer]] - rationale - graphify/file_slice.py
- [[Map each dispatched text unit's resolved path to the (lower-cased, capped)     s]] - rationale - graphify/llm.py
- [[Path_37]] - code
- [[Path_43]] - code
- [[Path_72]] - code
- [[Read just this slice's characters from its parent file.]] - rationale - graphify/file_slice.py
- [[Replace each oversized splittable-text file with a list of ``FileSlice``s.]] - rationale - graphify/file_slice.py
- [[Return a cut index in ``(start, end`` at the strongest nearby boundary.      Se]] - rationale - graphify/file_slice.py
- [[Return a text-like file's content for the extraction prompt.      Most files are]] - rationale - graphify/llm.py
- [[Return fileslice contents formatted for the extraction prompt.      Each unit i]] - rationale - graphify/llm.py
- [[Return the resolved path only when it stays inside ``root``.]] - rationale - graphify/llm.py
- [[Split a slice into two halves at a newline near its midpoint, or None.      Used]] - rationale - graphify/file_slice.py
- [[The on-disk path a unit belongs to (the parent file for a slice).]] - rationale - graphify/file_slice.py
- [[True for plain-text document types that may be sliced.]] - rationale - graphify/file_slice.py
- [[_best_cut()]] - code - graphify/file_slice.py
- [[_dispatched_source_text()]] - code - graphify/llm.py
- [[_file_to_text()]] - code - graphify/llm.py
- [[_read_files()]] - code - graphify/llm.py
- [[_resolve_under_root()]] - code - graphify/llm.py
- [[_write()_6]] - code - tests/test_file_slice.py
- [[bisect_slice()]] - code - graphify/file_slice.py
- [[expand_oversized_files()]] - code - graphify/file_slice.py
- [[file_slice.py]] - code - graphify/file_slice.py
- [[is_splittable_text()]] - code - graphify/file_slice.py
- [[parametrize_7]] - code
- [[read_slice_text()]] - code - graphify/file_slice.py
- [[slice_boundaries()]] - code - graphify/file_slice.py
- [[test_bisect_slice_returns_none_for_tiny()]] - code - tests/test_file_slice.py
- [[test_bisect_slice_splits_at_newline()]] - code - tests/test_file_slice.py
- [[test_estimate_tokens_for_slice_scales_with_range()]] - code - tests/test_file_slice.py
- [[test_expand_does_not_slice_code_even_when_oversized()]] - code - tests/test_file_slice.py
- [[test_expand_oversized_markdown_is_sliced_with_full_coverage()]] - code - tests/test_file_slice.py
- [[test_expand_small_file_stays_whole()]] - code - tests/test_file_slice.py
- [[test_expand_unreadable_file_passes_through()]] - code - tests/test_file_slice.py
- [[test_file_slice.py]] - code - tests/test_file_slice.py
- [[test_non_pdf_still_read_as_plain_text()]] - code - tests/test_image_vision.py
- [[test_pack_chunks_handles_slices()]] - code - tests/test_file_slice.py
- [[test_pdf_routed_through_pypdf_not_readtext()]] - code - tests/test_image_vision.py
- [[test_read_files_keys_every_slice_to_parent_path()]] - code - tests/test_file_slice.py
- [[test_read_files_skips_out_of_root_symlink()]] - code - tests/test_image_vision.py
- [[test_slice_boundaries_full_coverage_and_bounds()]] - code - tests/test_file_slice.py
- [[test_slice_boundaries_prefers_heading_boundary()]] - code - tests/test_file_slice.py
- [[test_slice_boundaries_single_huge_line_still_progresses()]] - code - tests/test_file_slice.py
- [[test_slice_boundaries_small_text_is_one_range()]] - code - tests/test_file_slice.py
- [[test_unit_path_resolves_slice_and_path()]] - code - tests/test_file_slice.py
- [[unit_path()]] - code - graphify/file_slice.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_file_slicepy
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_llm.py]]
- 13 edges to [[_COMMUNITY_test_chunking.py]]
- 8 edges to [[_COMMUNITY_test_image_vision.py]]
- 4 edges to [[_COMMUNITY_test_evidence_binding.py]]
- 2 edges to [[_COMMUNITY_test_llm_backends.py]]
- 1 edge to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY_test_detect.py]]
- 1 edge to [[_COMMUNITY_cli.py]]

## Top bridge nodes
- [[Path_43]] - degree 12, connects to 5 communities
- [[FileSlice]] - degree 16, connects to 4 communities
- [[test_file_slice.py]] - degree 25, connects to 2 communities
- [[expand_oversized_files()]] - degree 16, connects to 2 communities
- [[unit_path()]] - degree 12, connects to 2 communities