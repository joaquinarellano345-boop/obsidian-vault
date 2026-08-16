---
type: community
cohesion: 0.02
members: 144
---

# test_watch.py

**Cohesion:** 0.02 - loosely connected
**Members:** 144 nodes

## Members
- [[09b33b7 guard a doc with NO semantic layer still gets the AST     quick-scan s]] - rationale - tests/test_watch.py
- [[1007 graphify update (_rebuild_code with no changed_paths) must remove     nod]] - rationale - tests/test_watch.py
- [[1059 after the primary rebuild, the lock-holder must loop and drain     any pa]] - rationale - tests/test_watch.py
- [[1059 the process that acquires the lock must drain .pending_changes     and pa]] - rationale - tests/test_watch.py
- [[1059 when the rebuild lock is held, an incremental hook must queue     its cha]] - rationale - tests/test_watch.py
- [[1116 a symbol removed from a re-extracted file is a legitimate shrink —     ev]] - rationale - tests/test_watch.py
- [[1116 graphify update (_rebuild_code with no changed_paths) must prune a     sy]] - rationale - tests/test_watch.py
- [[1118 backward-compat a graph.json built before 1116 has no `_origin`     mark]] - rationale - tests/test_watch.py
- [[1348 git-hook paths are repo-root-relative even when the graph root is a subdi]] - rationale - tests/test_watch.py
- [[1755 AST-only updates must not drop semantic hyperedges whose members survive.]] - rationale - tests/test_watch.py
- [[1808 `graphify update`  _rebuild_code must forward community_labels to     to]] - rationale - tests/test_watch.py
- [[1837 after an initial build, a plain `graphify update` (full re-scan, no     c]] - rationale - tests/test_watch.py
- [[1865 AST-only updates must not evict semantic edges whose source_file     is a]] - rationale - tests/test_watch.py
- [[1880 `graphify update` must not emit 0 nodes (and then refuse to     overwrite]] - rationale - tests/test_watch.py
- [[1915 a full _rebuild_code must not AST-quick-scan a doc whose semantic     (LL]] - rationale - tests/test_watch.py
- [[1915 a graph already bloated by the bug (semantic doc nodes PLUS stale     _or]] - rationale - tests/test_watch.py
- [[1915 an incremental rebuild whose change set includes a semantic-backed     do]] - rationale - tests/test_watch.py
- [[1954 a doc represented ONLY by conceptrationale nodes (no     file_type==doc]] - rationale - tests/test_watch.py
- [[1954 incremental analogue — a conceptrationale-only semantic doc     must not]] - rationale - tests/test_watch.py
- [[2014 a doc represented ONLY by code-typed semantic nodes (symbols     surfaced]] - rationale - tests/test_watch.py
- [[2051 a full `graphify update` must evict semantic nodes whose non-AST     sour]] - rationale - tests/test_watch.py
- [[2056 an incremental rebuild whose change set names a file that exists but]] - rationale - tests/test_watch.py
- [[777 ``.graphify_root`` stores the user-supplied path (``.``), not the     reso]] - rationale - tests/test_watch.py
- [[A full rebuild of a subdirectory must not prune graph data outside it.]] - rationale - tests/test_watch.py
- [[A hook-style rename list may contain only the destination path.]] - rationale - tests/test_watch.py
- [[A rejected candidate keeps the marker paired with the existing graph.]] - rationale - tests/test_watch.py
- [[An incremental rebuild must not treat .foo.py as a deleted live source.]] - rationale - tests/test_watch.py
- [[Build a code-only graph, then add guide.md represented ONLY semantically.      M]] - rationale - tests/test_watch.py
- [[Build a minimal graph-data dict with n placeholder nodes.]] - rationale - tests/test_watch.py
- [[Caller declared deletions → shrink is expected → guard skipped silently.]] - rationale - tests/test_watch.py
- [[Changed files under followed symlinks retain their watched lexical path.]] - rationale - tests/test_watch.py
- [[Crossing the viz node limit must not leave the project with no graph.html.     _]] - rationale - tests/test_watch.py
- [[Default case smaller new graph + no force + no declared deletions = refuse.]] - rationale - tests/test_watch.py
- [[Deleting the final code file must reconcile the existing graph.]] - rationale - tests/test_watch.py
- [[Destination-only rename reconciliation also covers AST-backed docs.]] - rationale - tests/test_watch.py
- [[Detached hooks can inherit a CWD that no longer exists.      Without GRAPHIFY_RE]] - rationale - tests/test_watch.py
- [[Empty change set must not create an empty .pending_changes file.]] - rationale - tests/test_watch.py
- [[End-to-end probe of the post-commit-delete bug fix.      Build a tiny graph, del]] - rationale - tests/test_watch.py
- [[Fail-closed eviction a file that leaves the scan corpus (newly ignored)     but]] - rationale - tests/test_watch.py
- [[First-run case no existing graph → guard inert.]] - rationale - tests/test_watch.py
- [[GH-858 a non-blocking caller that fails to acquire the lock must not     trunca]] - rationale - tests/test_watch.py
- [[GH-858 each acquisition truncates and rewrites the PID line rather     than app]] - rationale - tests/test_watch.py
- [[GH-858 lock file must be unlinked once the rebuild completes so     downstream]] - rationale - tests/test_watch.py
- [[GRAPHIFY_REPO_ROOT lets detached hook rebuilds recover from a deleted CWD.]] - rationale - tests/test_watch.py
- [[Like ``_seed_semantic_doc_graph``, but guide.md's semantic layer is     ONLY con]] - rationale - tests/test_watch.py
- [[Mirror of the above if the caller declared deletions, the tmp file is NOT unlin]] - rationale - tests/test_watch.py
- [[Per-repo advisory lock around a rebuild.      Yields True if acquired, False if]] - rationale - graphify/watch.py
- [[Persisted source paths keep their meaning when invocation style changes.]] - rationale - tests/test_watch.py
- [[Pre-rebase subdirectory graphs stored source_file relative to watch_root.]] - rationale - tests/test_watch.py
- [[Return True (ok to proceed) or False (shrink refused).      When False, cleans u]] - rationale - graphify/watch.py
- [[Tests for watch.py - file watcher helpers (no watchdog required).]] - rationale - tests/test_watch.py
- [[The fail-closed preserve must not weaken true-deletion eviction once the     ex]] - rationale - tests/test_watch.py
- [[The guard's real job is intact a node lost from a file we did NOT re-extract]] - rationale - tests/test_watch.py
- [[When refusing, the temp graph file gets cleaned up so it can't leak across runs.]] - rationale - tests/test_watch.py
- [[When the caller supplies an absolute path, ``.graphify_root`` stores     that ab]] - rationale - tests/test_watch.py
- [[Write a flag file and print a notification (fallback for non-code-only corpora).]] - rationale - graphify/watch.py
- [[_add_unrelated_semantic_pair()]] - code - tests/test_watch.py
- [[_check_shrink()]] - code - graphify/watch.py
- [[_merge_changed_paths preserves first-seen order and drops dupes.]] - rationale - tests/test_watch.py
- [[_notify_only()]] - code - graphify/watch.py
- [[_rebuild_lock()]] - code - graphify/watch.py
- [[_seed_semantic_doc_graph()]] - code - tests/test_watch.py
- [[_seed_semantic_doc_graph_code_only()]] - code - tests/test_watch.py
- [[_seed_semantic_doc_graph_concept_only()]] - code - tests/test_watch.py
- [[_shrink_payload()]] - code - tests/test_watch.py
- [[_watchdog_available()]] - code - tests/test_watch.py
- [[check_update never removes the needs_update flag (clearing is LLM's job).]] - rationale - tests/test_watch.py
- [[check_update returns True and is silent when needs_update flag is absent.]] - rationale - tests/test_watch.py
- [[check_update returns True and prints notification when flag exists.]] - rationale - tests/test_watch.py
- [[force=True bypasses the guard regardless of node delta.]] - rationale - tests/test_watch.py
- [[gh-928 .graphifyignore must be parsed exactly once at watch() startup,     not]] - rationale - tests/test_watch.py
- [[gh-928 the watch Handler must short-circuit paths matching     .graphifyignore]] - rationale - tests/test_watch.py
- [[new  existing is always fine.]] - rationale - tests/test_watch.py
- [[parametrize_25]] - code
- [[skipif_2]] - code
- [[test_check_shrink_allows_explicit_deletions()]] - code - tests/test_watch.py
- [[test_check_shrink_allows_force_override()]] - code - tests/test_watch.py
- [[test_check_shrink_allows_growth()]] - code - tests/test_watch.py
- [[test_check_shrink_allows_no_existing_data()]] - code - tests/test_watch.py
- [[test_check_shrink_allows_shrink_within_rebuilt_sources()]] - code - tests/test_watch.py
- [[test_check_shrink_blocks_shrink_outside_rebuilt_sources()]] - code - tests/test_watch.py
- [[test_check_shrink_blocks_silent_shrink()]] - code - tests/test_watch.py
- [[test_check_shrink_keeps_tmp_when_deletions_declared()]] - code - tests/test_watch.py
- [[test_check_shrink_unlinks_tmp_on_refuse()]] - code - tests/test_watch.py
- [[test_check_update_does_not_clear_flag()]] - code - tests/test_watch.py
- [[test_check_update_no_flag_returns_true()]] - code - tests/test_watch.py
- [[test_check_update_with_flag_returns_true_and_prints()]] - code - tests/test_watch.py
- [[test_graphify_root_preserves_absolute_when_user_supplied()]] - code - tests/test_watch.py
- [[test_graphify_root_preserves_relative_when_invoked_with_relative_path()]] - code - tests/test_watch.py
- [[test_merge_changed_paths_dedupes_in_order()]] - code - tests/test_watch.py
- [[test_notify_only_creates_flag()]] - code - tests/test_watch.py
- [[test_notify_only_creates_flag_dir()]] - code - tests/test_watch.py
- [[test_notify_only_idempotent()]] - code - tests/test_watch.py
- [[test_queue_pending_noop_on_empty_list()]] - code - tests/test_watch.py
- [[test_rebuild_code_accepts_repo_relative_changed_path_for_subdir_root()]] - code - tests/test_watch.py
- [[test_rebuild_code_code_only_semantic_doc_not_double_represented_on_full_rebuild()]] - code - tests/test_watch.py
- [[test_rebuild_code_concept_only_semantic_doc_not_double_represented_on_full_rebuild()]] - code - tests/test_watch.py
- [[test_rebuild_code_deleted_cwd_uses_graphify_repo_root()]] - code - tests/test_watch.py
- [[test_rebuild_code_deleted_cwd_without_repo_root_returns_false()]] - code - tests/test_watch.py
- [[test_rebuild_code_does_not_update_root_marker_when_write_is_refused()]] - code - tests/test_watch.py
- [[test_rebuild_code_drains_late_arrivals()]] - code - tests/test_watch.py
- [[test_rebuild_code_evicts_nodes_from_deleted_files()]] - code - tests/test_watch.py
- [[test_rebuild_code_evicts_removed_symbol_from_surviving_file()]] - code - tests/test_watch.py
- [[test_rebuild_code_evicts_semantic_nodes_from_deleted_non_ast_source()]] - code - tests/test_watch.py
- [[test_rebuild_code_incremental_preserves_concept_only_semantic_doc_nodes_and_edges()]] - code - tests/test_watch.py
- [[test_rebuild_code_incremental_preserves_present_non_ast_source()]] - code - tests/test_watch.py
- [[test_rebuild_code_incremental_preserves_semantic_doc_nodes_and_edges()]] - code - tests/test_watch.py
- [[test_rebuild_code_incremental_rename_preserves_symlink_source_path()]] - code - tests/test_watch.py
- [[test_rebuild_code_is_idempotent_when_cluster_ids_flap()]] - code - tests/test_watch.py
- [[test_rebuild_code_keeps_a_visualization_when_over_the_viz_cap()]] - code - tests/test_watch.py
- [[test_rebuild_code_merges_pending_on_acquire()]] - code - tests/test_watch.py
- [[test_rebuild_code_normalizes_preserved_source_paths()]] - code - tests/test_watch.py
- [[test_rebuild_code_polluted_graph_self_heals_on_full_rebuild()]] - code - tests/test_watch.py
- [[test_rebuild_code_preserves_hyperedges_for_rebuilt_surviving_source()]] - code - tests/test_watch.py
- [[test_rebuild_code_preserves_nodes_from_excluded_but_alive_file()]] - code - tests/test_watch.py
- [[test_rebuild_code_preserves_semantic_edges_from_reextracted_doc()]] - code - tests/test_watch.py
- [[test_rebuild_code_preupgrade_marker_less_node_one_cycle_lag()]] - code - tests/test_watch.py
- [[test_rebuild_code_prunes_deleted_file_nodes()]] - code - tests/test_watch.py
- [[test_rebuild_code_prunes_final_deleted_file()]] - code - tests/test_watch.py
- [[test_rebuild_code_prunes_legacy_watch_relative_subdir_source()]] - code - tests/test_watch.py
- [[test_rebuild_code_prunes_renamed_ast_backed_document()]] - code - tests/test_watch.py
- [[test_rebuild_code_prunes_renamed_source_not_listed_by_hook()]] - code - tests/test_watch.py
- [[test_rebuild_code_queues_on_lock_contention()]] - code - tests/test_watch.py
- [[test_rebuild_code_quick_scans_doc_without_semantic_nodes()]] - code - tests/test_watch.py
- [[test_rebuild_code_semantic_doc_not_double_represented_on_full_rebuild()]] - code - tests/test_watch.py
- [[test_rebuild_code_skips_cluster_when_topology_unchanged()]] - code - tests/test_watch.py
- [[test_rebuild_code_still_evicts_when_excluded_file_is_also_deleted()]] - code - tests/test_watch.py
- [[test_rebuild_code_subdir_preserves_outside_ast_nodes()]] - code - tests/test_watch.py
- [[test_rebuild_code_subdir_survives_absolute_to_relative_invocation()]] - code - tests/test_watch.py
- [[test_rebuild_code_writes_community_name()]] - code - tests/test_watch.py
- [[test_rebuild_lock_does_not_accumulate_pids_across_runs()]] - code - tests/test_watch.py
- [[test_rebuild_lock_non_blocking_does_not_clobber_holder()]] - code - tests/test_watch.py
- [[test_rebuild_lock_removed_after_release()]] - code - tests/test_watch.py
- [[test_rebuild_lock_writes_pid_with_newline()]] - code - tests/test_watch.py
- [[test_update_discovers_newly_added_files_and_dirs()]] - code - tests/test_watch.py
- [[test_update_rebuilds_with_nested_star_gitignore()]] - code - tests/test_watch.py
- [[test_watch.py]] - code - tests/test_watch.py
- [[test_watch_handler_honors_graphifyignore()]] - code - tests/test_watch.py
- [[test_watch_loads_graphifyignore_once()]] - code - tests/test_watch.py
- [[test_watch_raises_without_watchdog()]] - code - tests/test_watch.py
- [[test_watched_extensions_excludes_noise()]] - code - tests/test_watch.py
- [[test_watched_extensions_includes_code()]] - code - tests/test_watch.py
- [[test_watched_extensions_includes_docs()]] - code - tests/test_watch.py
- [[test_watched_extensions_includes_images()]] - code - tests/test_watch.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_watchpy
SORT file.name ASC
```

## Connections to other communities
- 71 edges to [[_COMMUNITY_cli.py]]
- 3 edges to [[_COMMUNITY_graphifycluster.py]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_detect.py]]

## Top bridge nodes
- [[test_watch.py]] - degree 97, connects to 3 communities
- [[_check_shrink()]] - degree 14, connects to 2 communities
- [[_rebuild_lock()]] - degree 10, connects to 1 community
- [[_notify_only()]] - degree 8, connects to 1 community
- [[_seed_semantic_doc_graph()]] - degree 5, connects to 1 community