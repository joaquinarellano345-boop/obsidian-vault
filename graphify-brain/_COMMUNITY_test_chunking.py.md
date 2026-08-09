---
type: community
cohesion: 0.03
members: 84
---

# test_chunking.py

**Cohesion:** 0.03 - loosely connected
**Members:** 84 nodes

## Members
- [[1632 merged nodeedge order must be deterministic (submission order),     not]] - rationale - tests/test_chunking.py
- [[1757 the per-chunk incremental checkpoint must not let a chunk's     mis-attri]] - rationale - tests/test_chunking.py
- [[1870 the checkpoint's allowlist must resolve a FileSlice to its parent     pat]] - rationale - tests/test_chunking.py
- [[1890 a chunk can return a clean, non-empty response that omits some of the]] - rationale - tests/test_chunking.py
- [[1894 the per-chunk checkpoint must follow the run's mode — a     deep_mode=Tru]] - rationale - tests/test_chunking.py
- [[1895 the 1757 cache guard skips the CACHE write for a node attributed     to]] - rationale - tests/test_chunking.py
- [[A doc containing a literal tiktoken special token (e.g. endoftext)     must]] - rationale - tests/test_chunking.py
- [[A file larger than the budget can't be split — it goes alone in a chunk.]] - rationale - tests/test_chunking.py
- [[A non-splittable single-file truncation keeps its partial result but     marks e]] - rationale - tests/test_chunking.py
- [[A single chunk raising should be logged but not abort the run.     Other chunks']] - rationale - tests/test_chunking.py
- [[A single file that truncates can't be split further — surface a     warning and]] - rationale - tests/test_chunking.py
- [[A single-file chunk that stays truncated is checkpointed as a PARTIAL     entry,]] - rationale - tests/test_chunking.py
- [[A truncation that IS recovered by splitting yields a complete result —     it mu]] - rationale - tests/test_chunking.py
- [[Build a deterministic fake extraction result for a chunk.]] - rationale - tests/test_chunking.py
- [[Build a stub extraction result with a controllable finish_reason.]] - rationale - tests/test_chunking.py
- [[Counter-test a clean run records out_of_scope_dropped == 0 and no warning.]] - rationale - tests/test_chunking.py
- [[End to end packing a corpus that includes a special-token doc must not     rais]] - rationale - tests/test_chunking.py
- [[End-to-end extract_corpus_parallel routes through adaptive retry,     so a chun]] - rationale - tests/test_chunking.py
- [[Estimate the prompt-token cost of a file or slice under `_read_files` rules.]] - rationale - graphify/llm.py
- [[Extract a chunk; if the response is truncated (`finish_reason=length`)     or]] - rationale - graphify/llm.py
- [[Extract a corpus in chunks, merging results.      Chunking strategy         - I]] - rationale - graphify/llm.py
- [[Files in the same directory should land in the same chunk when they fit.]] - rationale - tests/test_chunking.py
- [[Greedily pack filesslices into chunks that fit a token budget.      Units are f]] - rationale - graphify/llm.py
- [[If everything truncates, retries stop at max_depth — partial result     kept wit]] - rationale - tests/test_chunking.py
- [[Many small files should land in a single chunk, not one chunk per file.]] - rationale - tests/test_chunking.py
- [[No retry when finish_reason='stop' — single call, result passes through.]] - rationale - tests/test_chunking.py
- [[Return the semantic-extraction system prompt, optionally in deep mode.]] - rationale - graphify/llm.py
- [[Tests for token-aware chunking and parallel chunk execution in graphify.llm.]] - rationale - tests/test_chunking.py
- [[When even the half-chunk truncates, split again. With 8 files and a     truncati]] - rationale - tests/test_chunking.py
- [[When recursion caps at max_depth with everything still truncated, the     merged]] - rationale - tests/test_chunking.py
- [[When the next file would push the chunk past the budget, start a new chunk.]] - rationale - tests/test_chunking.py
- [[When tiktoken is installed, the estimator should call into it for     accurate c]] - rationale - tests/test_chunking.py
- [[With max_concurrency  1, total wall time should be ~max(chunk times),     not t]] - rationale - tests/test_chunking.py
- [[With the default token_budget, many tiny files pack into one chunk.]] - rationale - tests/test_chunking.py
- [[Without tiktoken installed, the estimator falls back to chars4.]] - rationale - tests/test_chunking.py
- [[_estimate_file_tokens()]] - code - graphify/llm.py
- [[_extract_with_adaptive_retry()]] - code - graphify/llm.py
- [[_extraction_system()]] - code - graphify/llm.py
- [[_is_vision_image()]] - code - graphify/llm.py
- [[_pack_chunks_by_tokens()]] - code - graphify/llm.py
- [[_stub_chunk_result()]] - code - tests/test_chunking.py
- [[_stub_with_finish()]] - code - tests/test_chunking.py
- [[extract_corpus_parallel()]] - code - graphify/llm.py
- [[finish_reason='length' triggers split-in-half. Both halves succeed     on the se]] - rationale - tests/test_chunking.py
- [[max_concurrency=1 should run sequentially (no thread pool).]] - rationale - tests/test_chunking.py
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
- [[test_checkpoint_caches_sliced_document_chunks()]] - code - tests/test_chunking.py
- [[test_checkpoint_scopes_cache_writes_to_chunk_files()]] - code - tests/test_chunking.py
- [[test_checkpoint_writes_deep_namespace_in_deep_mode()]] - code - tests/test_chunking.py
- [[test_chunk_packing_caps_images_per_chunk()]] - code - tests/test_image_vision.py
- [[test_chunking.py]] - code - tests/test_chunking.py
- [[test_corpus_parallel_continues_after_chunk_failure()]] - code - tests/test_chunking.py
- [[test_corpus_parallel_legacy_mode_when_token_budget_is_none()]] - code - tests/test_chunking.py
- [[test_corpus_parallel_merge_order_is_submission_order_not_completion()]] - code - tests/test_chunking.py
- [[test_corpus_parallel_runs_chunks_concurrently()]] - code - tests/test_chunking.py
- [[test_corpus_parallel_sequential_when_max_concurrency_is_one()]] - code - tests/test_chunking.py
- [[test_corpus_parallel_token_budget_default_packs_files()]] - code - tests/test_chunking.py
- [[test_corpus_parallel_uses_adaptive_retry()]] - code - tests/test_chunking.py
- [[test_estimate_file_tokens_falls_back_to_chars_when_no_tokenizer()]] - code - tests/test_chunking.py
- [[test_estimate_file_tokens_handles_tiktoken_special_token()]] - code - tests/test_chunking.py
- [[test_estimate_file_tokens_uses_tiktoken_when_available()]] - code - tests/test_chunking.py
- [[test_image_token_estimate_is_flat()]] - code - tests/test_image_vision.py
- [[test_omitted_documents_are_reconciled_and_warned()]] - code - tests/test_chunking.py
- [[test_out_of_scope_drop_count_is_zero_when_all_in_scope()]] - code - tests/test_chunking.py
- [[test_out_of_scope_nodes_are_dropped_from_merged_result()]] - code - tests/test_chunking.py
- [[test_pack_chunks_groups_by_directory()]] - code - tests/test_chunking.py
- [[test_pack_chunks_oversized_file_gets_its_own_chunk()]] - code - tests/test_chunking.py
- [[test_pack_chunks_packs_small_files_together()]] - code - tests/test_chunking.py
- [[test_pack_chunks_rejects_non_positive_budget()]] - code - tests/test_chunking.py
- [[test_pack_chunks_starts_new_chunk_when_budget_would_overflow()]] - code - tests/test_chunking.py
- [[test_pack_chunks_with_special_token_doc_does_not_crash()]] - code - tests/test_chunking.py
- [[test_truncated_chunk_is_cached_partial_and_missed_on_reload()]] - code - tests/test_chunking.py
- [[token_budget=None should fall back to legacy fixed-count chunking.]] - rationale - tests/test_chunking.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_chunkingpy
SORT file.name ASC
```

## Connections to other communities
- 13 edges to [[_COMMUNITY_test_file_slice.py]]
- 12 edges to [[_COMMUNITY_llm.py]]
- 12 edges to [[_COMMUNITY_test_llm_backends.py]]
- 9 edges to [[_COMMUNITY_save_semantic_cache]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 4 edges to [[_COMMUNITY_test_image_vision.py]]
- 2 edges to [[_COMMUNITY__call_llm]]
- 2 edges to [[_COMMUNITY_test_semantic_cache_out_root.py]]
- 1 edge to [[_COMMUNITY__call_claude_cli]]
- 1 edge to [[_COMMUNITY_multigraph_compat.py]]
- 1 edge to [[_COMMUNITY_no_tokenizer]]

## Top bridge nodes
- [[extract_corpus_parallel()]] - degree 32, connects to 6 communities
- [[_extraction_system()]] - degree 15, connects to 5 communities
- [[test_chunking.py]] - degree 43, connects to 4 communities
- [[_extract_with_adaptive_retry()]] - degree 23, connects to 4 communities
- [[_is_vision_image()]] - degree 6, connects to 3 communities