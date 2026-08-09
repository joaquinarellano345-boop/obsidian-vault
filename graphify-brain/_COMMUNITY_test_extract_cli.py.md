---
type: community
cohesion: 0.06
members: 55
---

# test_extract_cli.py

**Cohesion:** 0.06 - loosely connected
**Members:** 55 nodes

## Members
- [[1894 repro over a warm manifest + warm standard semantic cache,     `extract -]] - rationale - tests/test_extract_cli.py
- [[1897 fresh extraction returns nodes with ROOT-RELATIVE source_file,     while]] - rationale - tests/test_extract_cli.py
- [[1920 end-to-end a fresh extraction whose only output for a doc is a     hypere]] - rationale - tests/test_extract_cli.py
- [[1920 a doc whose only chunk output is a hyperedge (3+ nodes sharing a     conc]] - rationale - tests/test_extract_cli.py
- [[1925 `graphify extract --code-only` with a MISSING manifest.json must     not]] - rationale - tests/test_extract_cli.py
- [[1939 cache-check --prompt-file only counts entries produced by that same     e]] - rationale - tests/test_extract_cli.py
- [[1948 caller-side guard an incremental run that only re-dispatches the     CHAN]] - rationale - tests/test_extract_cli.py
- [[1948 x 1950 interaction a doc stamped complete on a prior run that     TRUNCA]] - rationale - tests/test_extract_cli.py
- [[--no-cluster's exclusion-only early exit must still scrub the excluded     file']] - rationale - tests/test_extract_cli.py
- [[A code-only corpus must run with no LLM API key.      Regression graphify extra]] - rationale - tests/test_extract_cli.py
- [[A corpus with only code — no docspapersimages.]] - rationale - tests/test_extract_cli.py
- [[Clear every env var that detect_backend() or _get_backend_api_key() reads.]] - rationale - tests/test_extract_cli.py
- [[GRAPHIFY_FORCE=1 behaves like --force (env parity with `update`).]] - rationale - tests/test_extract_cli.py
- [[Key requirement still fires when semantic work is needed.      A corpus with a M]] - rationale - tests/test_extract_cli.py
- [[Minimal corpus one Go code file + one Markdown doc.      Both file types are ne]] - rationale - tests/test_extract_cli.py
- [[Post-1897 state the excluded file IS manifest-listed. It must be     pruned fr]] - rationale - tests/test_extract_cli.py
- [[Sanity counter-test a successful chunk run keeps exit 0. Confirms the     new g]] - rationale - tests/test_extract_cli.py
- [[Seed a graph with nodes for x.py, drop x.py from the manifest (pre-1897     man]] - rationale - tests/test_extract_cli.py
- [[Tests for `graphify extract` CLI dispatch path in graphify.__main__.]] - rationale - tests/test_extract_cli.py
- [[Unit test for the 1897 helper relative (fresh) and absolute (cache-hit)     so]] - rationale - tests/test_extract_cli.py
- [[When every semantic chunk errors (e.g. backend SDK not installed),     the CLI m]] - rationale - tests/test_extract_cli.py
- [[_clear_backend_keys()]] - code - tests/test_extract_cli.py
- [[_code_only_corpus()]] - code - tests/test_extract_cli.py
- [[_make_corpus()_1]] - code - tests/test_extract_cli.py
- [[_node_sources()]] - code - tests/test_extract_cli.py
- [[_recording_extractor()]] - code - tests/test_extract_cli.py
- [[_run_extract()]] - code - tests/test_extract_cli.py
- [[_two_file_corpus()]] - code - tests/test_extract_cli.py
- [[`extract --out DIR` routes every artifact to DIRgraphify-out and the     scann]] - rationale - tests/test_extract_cli.py
- [[cache-check --mode deep consults cachesemantic-deep; without the flag     it k]] - rationale - tests/test_extract_cli.py
- [[extract accepts --force a warm tree re-dispatches every semantic file     (cach]] - rationale - tests/test_extract_cli.py
- [[extract_corpus_parallel stand-in that records each dispatch.]] - rationale - tests/test_extract_cli.py
- [[parametrize_5]] - code
- [[test_cache_check_mode_deep_reads_deep_namespace()]] - code - tests/test_extract_cli.py
- [[test_cache_check_prompt_file_scopes_hits_to_that_prompt()]] - code - tests/test_extract_cli.py
- [[test_extract_cli.py]] - code - tests/test_extract_cli.py
- [[test_extract_codeonly_succeeds_without_api_key()]] - code - tests/test_extract_cli.py
- [[test_extract_exits_nonzero_when_all_semantic_chunks_fail()]] - code - tests/test_extract_cli.py
- [[test_extract_force_flag_redispatches_and_stamps_manifest()]] - code - tests/test_extract_cli.py
- [[test_extract_graphify_force_env_redispatches()]] - code - tests/test_extract_cli.py
- [[test_extract_mode_deep_dispatches_over_warm_cache()]] - code - tests/test_extract_cli.py
- [[test_extract_out_keeps_project_root_clean()]] - code - tests/test_extract_cli.py
- [[test_extract_succeeds_when_at_least_one_chunk_completes()]] - code - tests/test_extract_cli.py
- [[test_extract_without_key_still_errors_when_docs_present()]] - code - tests/test_extract_cli.py
- [[test_incremental_extract_prunes_excluded_file_listed_in_manifest()]] - code - tests/test_extract_cli.py
- [[test_incremental_extract_prunes_newly_excluded_file_not_in_manifest()]] - code - tests/test_extract_cli.py
- [[test_incremental_partial_run_preserves_untouched_semantic_hash()]] - code - tests/test_extract_cli.py
- [[test_manifest_stamps_freshly_extracted_semantic_docs()]] - code - tests/test_extract_cli.py
- [[test_manifest_stamps_hyperedge_only_docs()]] - code - tests/test_extract_cli.py
- [[test_missing_manifest_code_only_preserves_semantic_layer()]] - code - tests/test_extract_cli.py
- [[test_no_cluster_incremental_prunes_newly_excluded_file()]] - code - tests/test_extract_cli.py
- [[test_pathless_postgres_extract_initializes_empty_detection()]] - code - tests/test_extract_cli.py
- [[test_stamped_manifest_files_counts_hyperedge_only_docs()]] - code - tests/test_extract_cli.py
- [[test_stamped_manifest_files_normalizes_both_sides()]] - code - tests/test_extract_cli.py
- [[test_truncated_doc_semantic_hash_is_cleared_for_requeue()]] - code - tests/test_extract_cli.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_extract_clipy
SORT file.name ASC
```

## Connections to other communities
- 10 edges to [[_COMMUNITY_main]]
- 3 edges to [[_COMMUNITY_save_semantic_cache]]
- 3 edges to [[_COMMUNITY_cli.py]]
- 1 edge to [[_COMMUNITY_graphify__main__.py]]
- 1 edge to [[_COMMUNITY_test_extract_code_only_cli.py]]

## Top bridge nodes
- [[test_extract_cli.py]] - degree 33, connects to 4 communities
- [[_run_extract()]] - degree 12, connects to 2 communities
- [[test_no_cluster_incremental_prunes_newly_excluded_file()]] - degree 6, connects to 1 community
- [[test_extract_codeonly_succeeds_without_api_key()]] - degree 5, connects to 1 community
- [[test_extract_out_keeps_project_root_clean()]] - degree 5, connects to 1 community