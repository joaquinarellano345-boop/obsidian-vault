---
type: community
cohesion: 0.06
members: 49
---

# test_chunking.py

**Cohesion:** 0.06 - loosely connected
**Members:** 49 nodes

## Members
- [[1632 merged nodeedge order must be deterministic (submission order),     not]] - rationale - tests/test_chunking.py
- [[1870 the checkpoint's allowlist must resolve a FileSlice to its parent     pat]] - rationale - tests/test_chunking.py
- [[1890 a chunk can return a clean, non-empty response that omits some of the]] - rationale - tests/test_chunking.py
- [[1894 the per-chunk checkpoint must follow the run's mode — a     deep_mode=Tru]] - rationale - tests/test_chunking.py
- [[1895 the 1757 cache guard skips the CACHE write for a node attributed     to]] - rationale - tests/test_chunking.py
- [[A file larger than the budget can't be split — it goes alone in a chunk.]] - rationale - tests/test_chunking.py
- [[A single chunk raising should be logged but not abort the run.     Other chunks']] - rationale - tests/test_chunking.py
- [[A single-file chunk that stays truncated is checkpointed as a PARTIAL     entry,]] - rationale - tests/test_chunking.py
- [[Build a deterministic fake extraction result for a chunk.]] - rationale - tests/test_chunking.py
- [[Build a stub extraction result with a controllable finish_reason.]] - rationale - tests/test_chunking.py
- [[Counter-test a clean run records out_of_scope_dropped == 0 and no warning.]] - rationale - tests/test_chunking.py
- [[End to end packing a corpus that includes a special-token doc must not     rais]] - rationale - tests/test_chunking.py
- [[End-to-end extract_corpus_parallel routes through adaptive retry,     so a chun]] - rationale - tests/test_chunking.py
- [[Extract a corpus in chunks, merging results.      Chunking strategy         - I]] - rationale - graphify/llm.py
- [[Files in the same directory should land in the same chunk when they fit.]] - rationale - tests/test_chunking.py
- [[Greedily pack filesslices into chunks that fit a token budget.      Units are f]] - rationale - graphify/llm.py
- [[Many small files should land in a single chunk, not one chunk per file.]] - rationale - tests/test_chunking.py
- [[Tests for token-aware chunking and parallel chunk execution in graphify.llm.]] - rationale - tests/test_chunking.py
- [[When the next file would push the chunk past the budget, start a new chunk.]] - rationale - tests/test_chunking.py
- [[With max_concurrency  1, total wall time should be ~max(chunk times),     not t]] - rationale - tests/test_chunking.py
- [[With the default token_budget, many tiny files pack into one chunk.]] - rationale - tests/test_chunking.py
- [[_is_vision_image()]] - code - graphify/llm.py
- [[_pack_chunks_by_tokens()]] - code - graphify/llm.py
- [[_stub_chunk_result()]] - code - tests/test_chunking.py
- [[_stub_with_finish()]] - code - tests/test_chunking.py
- [[extract_corpus_parallel()]] - code - graphify/llm.py
- [[max_concurrency=1 should run sequentially (no thread pool).]] - rationale - tests/test_chunking.py
- [[test_checkpoint_caches_sliced_document_chunks()]] - code - tests/test_chunking.py
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
- 11 edges to [[_COMMUNITY_test_file_slice.py]]
- 9 edges to [[_COMMUNITY__extract_with_adaptive_retry]]
- 8 edges to [[_COMMUNITY_save_semantic_cache]]
- 7 edges to [[_COMMUNITY_llm.py]]
- 5 edges to [[_COMMUNITY_test_llm_backends.py]]
- 4 edges to [[_COMMUNITY__extraction_system]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_test_image_vision.py]]
- 2 edges to [[_COMMUNITY_test_semantic_cache_out_root.py]]
- 1 edge to [[_COMMUNITY_multigraph_compat.py]]
- 1 edge to [[_COMMUNITY_no_tokenizer]]

## Top bridge nodes
- [[test_chunking.py]] - degree 43, connects to 6 communities
- [[extract_corpus_parallel()]] - degree 32, connects to 6 communities
- [[_is_vision_image()]] - degree 6, connects to 3 communities
- [[test_checkpoint_caches_sliced_document_chunks()]] - degree 6, connects to 3 communities
- [[test_checkpoint_writes_deep_namespace_in_deep_mode()]] - degree 6, connects to 3 communities