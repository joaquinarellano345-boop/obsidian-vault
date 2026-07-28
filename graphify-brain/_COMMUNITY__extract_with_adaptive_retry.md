---
type: community
cohesion: 0.06
members: 31
---

# _extract_with_adaptive_retry

**Cohesion:** 0.06 - loosely connected
**Members:** 31 nodes

## Members
- [[A non-splittable single-file truncation keeps its partial result but     marks e]] - rationale - tests/test_chunking.py
- [[A single file that truncates can't be split further — surface a     warning and]] - rationale - tests/test_chunking.py
- [[A truncation that IS recovered by splitting yields a complete result —     it mu]] - rationale - tests/test_chunking.py
- [[BaseException]] - code
- [[Extract a chunk; if the response is truncated (`finish_reason=length`)     or]] - rationale - graphify/llm.py
- [[Heuristically classify an exception as a context-window overflow.      Different]] - rationale - graphify/llm.py
- [[If everything truncates, retries stop at max_depth — partial result     kept wit]] - rationale - tests/test_chunking.py
- [[No retry when finish_reason='stop' — single call, result passes through.]] - rationale - tests/test_chunking.py
- [[Source paths covered by a chunk, for marking a chunk that truncated to an     EM]] - rationale - graphify/llm.py
- [[Union of the ``_partial_files`` carried by each result (survives merges).]] - rationale - graphify/llm.py
- [[When even the half-chunk truncates, split again. With 8 files and a     truncati]] - rationale - tests/test_chunking.py
- [[When recursion caps at max_depth with everything still truncated, the     merged]] - rationale - tests/test_chunking.py
- [[_chunk_partial_files()]] - code - graphify/llm.py
- [[_extract_with_adaptive_retry()]] - code - graphify/llm.py
- [[_looks_like_context_exceeded()]] - code - graphify/llm.py
- [[_merged_partial_files()]] - code - graphify/llm.py
- [[finish_reason='length' triggers split-in-half. Both halves succeed     on the se]] - rationale - tests/test_chunking.py
- [[test_adaptive_retry_bisects_on_hollow_ollama_response()]] - code - tests/test_llm_backends.py
- [[test_adaptive_retry_caps_at_max_depth()]] - code - tests/test_chunking.py
- [[test_adaptive_retry_gives_up_on_single_file_overflow()]] - code - tests/test_llm_backends.py
- [[test_adaptive_retry_marks_max_depth_giveup_partial()]] - code - tests/test_chunking.py
- [[test_adaptive_retry_marks_single_file_truncation_partial()]] - code - tests/test_chunking.py
- [[test_adaptive_retry_re_raises_unrelated_errors()]] - code - tests/test_llm_backends.py
- [[test_adaptive_retry_recurses_for_persistent_truncation()]] - code - tests/test_chunking.py
- [[test_adaptive_retry_returns_directly_when_not_truncated()]] - code - tests/test_chunking.py
- [[test_adaptive_retry_single_file_truncation_does_not_recurse()]] - code - tests/test_chunking.py
- [[test_adaptive_retry_splits_on_context_exceeded()]] - code - tests/test_llm_backends.py
- [[test_adaptive_retry_splits_when_finish_reason_length()]] - code - tests/test_chunking.py
- [[test_adaptive_retry_successful_split_is_not_marked_partial()]] - code - tests/test_chunking.py
- [[test_looks_like_context_exceeded_ignores_unrelated_errors()]] - code - tests/test_llm_backends.py
- [[test_looks_like_context_exceeded_matches_common_messages()]] - code - tests/test_llm_backends.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_extract_with_adaptive_retry
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_test_chunking.py]]
- 7 edges to [[_COMMUNITY_test_llm_backends.py]]
- 5 edges to [[_COMMUNITY_llm.py]]
- 3 edges to [[_COMMUNITY_test_file_slice.py]]
- 1 edge to [[_COMMUNITY_save_semantic_cache]]

## Top bridge nodes
- [[_extract_with_adaptive_retry()]] - degree 23, connects to 5 communities
- [[_chunk_partial_files()]] - degree 4, connects to 2 communities
- [[_looks_like_context_exceeded()]] - degree 6, connects to 1 community
- [[_merged_partial_files()]] - degree 3, connects to 1 community
- [[test_adaptive_retry_caps_at_max_depth()]] - degree 3, connects to 1 community