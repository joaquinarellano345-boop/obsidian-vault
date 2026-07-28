---
type: community
cohesion: 0.08
members: 47
---

# test_file_slice.py

**Cohesion:** 0.08 - loosely connected
**Members:** 47 nodes

## Members
- [[A contiguous ``start, end)`` character range of a splittable text file.      ``]] - rationale - graphify/file_slice.py
- [[A doc containing a literal tiktoken special token (e.g. endoftext)     must]] - rationale - tests/test_chunking.py
- [[Contiguous ``(start, end)`` ranges covering all of ``text``, each ≤ max_chars.]] - rationale - graphify/file_slice.py
- [[Estimate the prompt-token cost of a file or slice under `_read_files` rules.]] - rationale - graphify/llm.py
- [[FileSlice]] - code - graphify/file_slice.py
- [[Intra-file slicing for oversized text documents (1369).  The extraction packer]] - rationale - graphify/file_slice.py
- [[Path_37]] - code
- [[Path_72]] - code
- [[Read just this slice's characters from its parent file.]] - rationale - graphify/file_slice.py
- [[Replace each oversized splittable-text file with a list of ``FileSlice``s.]] - rationale - graphify/file_slice.py
- [[Return a cut index in ``(start, end`` at the strongest nearby boundary.      Se]] - rationale - graphify/file_slice.py
- [[Split a slice into two halves at a newline near its midpoint, or None.      Used]] - rationale - graphify/file_slice.py
- [[The on-disk path a unit belongs to (the parent file for a slice).]] - rationale - graphify/file_slice.py
- [[True for plain-text document types that may be sliced.]] - rationale - graphify/file_slice.py
- [[When tiktoken is installed, the estimator should call into it for     accurate c]] - rationale - tests/test_chunking.py
- [[Without tiktoken installed, the estimator falls back to chars4.]] - rationale - tests/test_chunking.py
- [[_best_cut()]] - code - graphify/file_slice.py
- [[_estimate_file_tokens()]] - code - graphify/llm.py
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
- [[test_estimate_file_tokens_falls_back_to_chars_when_no_tokenizer()]] - code - tests/test_chunking.py
- [[test_estimate_file_tokens_handles_tiktoken_special_token()]] - code - tests/test_chunking.py
- [[test_estimate_file_tokens_uses_tiktoken_when_available()]] - code - tests/test_chunking.py
- [[test_estimate_tokens_for_slice_scales_with_range()]] - code - tests/test_file_slice.py
- [[test_expand_does_not_slice_code_even_when_oversized()]] - code - tests/test_file_slice.py
- [[test_expand_oversized_markdown_is_sliced_with_full_coverage()]] - code - tests/test_file_slice.py
- [[test_expand_small_file_stays_whole()]] - code - tests/test_file_slice.py
- [[test_expand_unreadable_file_passes_through()]] - code - tests/test_file_slice.py
- [[test_file_slice.py]] - code - tests/test_file_slice.py
- [[test_image_token_estimate_is_flat()]] - code - tests/test_image_vision.py
- [[test_pack_chunks_handles_slices()]] - code - tests/test_file_slice.py
- [[test_partition_keeps_slices_as_text()]] - code - tests/test_file_slice.py
- [[test_read_files_keys_every_slice_to_parent_path()]] - code - tests/test_file_slice.py
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
- 13 edges to [[_COMMUNITY_llm.py]]
- 11 edges to [[_COMMUNITY_test_chunking.py]]
- 4 edges to [[_COMMUNITY_test_image_vision.py]]
- 3 edges to [[_COMMUNITY__extract_with_adaptive_retry]]
- 2 edges to [[_COMMUNITY_test_evidence_binding.py]]

## Top bridge nodes
- [[FileSlice]] - degree 16, connects to 4 communities
- [[unit_path()]] - degree 12, connects to 3 communities
- [[expand_oversized_files()]] - degree 16, connects to 2 communities
- [[_estimate_file_tokens()]] - degree 10, connects to 2 communities
- [[bisect_slice()]] - degree 8, connects to 2 communities