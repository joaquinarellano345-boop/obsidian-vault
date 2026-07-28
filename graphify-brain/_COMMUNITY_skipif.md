---
type: community
cohesion: 0.10
members: 24
---

# skipif

**Cohesion:** 0.10 - loosely connected
**Members:** 24 nodes

## Members
- [[1059 after the primary rebuild, the lock-holder must loop and drain     any pa]] - rationale - tests/test_watch.py
- [[1059 the process that acquires the lock must drain .pending_changes     and pa]] - rationale - tests/test_watch.py
- [[1059 when the rebuild lock is held, an incremental hook must queue     its cha]] - rationale - tests/test_watch.py
- [[Changed files under followed symlinks retain their watched lexical path.]] - rationale - tests/test_watch.py
- [[End-to-end probe of the post-commit-delete bug fix.      Build a tiny graph, del]] - rationale - tests/test_watch.py
- [[GH-858 a non-blocking caller that fails to acquire the lock must not     trunca]] - rationale - tests/test_watch.py
- [[GH-858 each acquisition truncates and rewrites the PID line rather     than app]] - rationale - tests/test_watch.py
- [[GH-858 lock file must be unlinked once the rebuild completes so     downstream]] - rationale - tests/test_watch.py
- [[Per-repo advisory lock around a rebuild.      Yields True if acquired, False if]] - rationale - graphify/watch.py
- [[_rebuild_lock()]] - code - graphify/watch.py
- [[gh-928 .graphifyignore must be parsed exactly once at watch() startup,     not]] - rationale - tests/test_watch.py
- [[gh-928 the watch Handler must short-circuit paths matching     .graphifyignore]] - rationale - tests/test_watch.py
- [[skipif_2]] - code
- [[test_rebuild_code_drains_late_arrivals()]] - code - tests/test_watch.py
- [[test_rebuild_code_incremental_rename_preserves_symlink_source_path()]] - code - tests/test_watch.py
- [[test_rebuild_code_merges_pending_on_acquire()]] - code - tests/test_watch.py
- [[test_rebuild_code_prunes_deleted_file_nodes()]] - code - tests/test_watch.py
- [[test_rebuild_code_queues_on_lock_contention()]] - code - tests/test_watch.py
- [[test_rebuild_lock_does_not_accumulate_pids_across_runs()]] - code - tests/test_watch.py
- [[test_rebuild_lock_non_blocking_does_not_clobber_holder()]] - code - tests/test_watch.py
- [[test_rebuild_lock_removed_after_release()]] - code - tests/test_watch.py
- [[test_rebuild_lock_writes_pid_with_newline()]] - code - tests/test_watch.py
- [[test_watch_handler_honors_graphifyignore()]] - code - tests/test_watch.py
- [[test_watch_loads_graphifyignore_once()]] - code - tests/test_watch.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/skipif
SORT file.name ASC
```

## Connections to other communities
- 12 edges to [[_COMMUNITY_test_watch.py]]
- 7 edges to [[_COMMUNITY__rebuild_code]]

## Top bridge nodes
- [[_rebuild_lock()]] - degree 10, connects to 2 communities
- [[test_rebuild_code_queues_on_lock_contention()]] - degree 5, connects to 2 communities
- [[test_rebuild_code_incremental_rename_preserves_symlink_source_path()]] - degree 4, connects to 2 communities
- [[test_rebuild_code_merges_pending_on_acquire()]] - degree 4, connects to 2 communities
- [[test_rebuild_code_prunes_deleted_file_nodes()]] - degree 4, connects to 2 communities