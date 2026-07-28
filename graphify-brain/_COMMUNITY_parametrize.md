---
type: community
cohesion: 0.08
members: 27
---

# parametrize

**Cohesion:** 0.08 - loosely connected
**Members:** 27 nodes

## Members
- [[2166 a space must not empty the pin.      The install-time allowlist had no sp]] - rationale - tests/test_hooks.py
- [[Both hooks must short-circuit in a linked worktree (git-dir != common-dir),]] - rationale - tests/test_hooks.py
- [[Both the launcher and the rebuild body it re-executes must parse, so a     quoti]] - rationale - tests/test_hooks.py
- [[Extract the `python -c payload` the hook hands to GRAPHIFY_PYTHON.      The]] - rationale - tests/test_hooks.py
- [[GRAPHIFY_SKIP_HOOK=1 must suppress BOTH hooks. post-checkout previously     lack]] - rationale - tests/test_hooks.py
- [[Git for Windows' bundled shell ships no `nohup``setsid`, so the old     `nohup]] - rationale - tests/test_hooks.py
- [[Git for WindowsMSYS hooks can expose fragile pipe handles to spawned     Proces]] - rationale - tests/test_hooks.py
- [[The launcher is carried inside a shell double-quoted `-c ...` argument,     so]] - rationale - tests/test_hooks.py
- [[The rebuild must honour the persisted scan root rather than hardcoding the     r]] - rationale - tests/test_hooks.py
- [[The replacement detaches via Python start_new_session on POSIX and     DETACHED]] - rationale - tests/test_hooks.py
- [[Widening the allowlist for spaces (2166) must not admit anything that can     s]] - rationale - tests/test_hooks.py
- [[Windows has no signal.SIGALRM, so the 791 rebuild timeout never armed     there]] - rationale - tests/test_hooks.py
- [[_launcher_payload()]] - code - tests/test_hooks.py
- [[git exports GIT_DIR to hooks, so the rev-parse fallback should only run     when]] - rationale - tests/test_hooks.py
- [[parametrize_9]] - code
- [[test_hooks_do_not_use_nohup()]] - code - tests/test_hooks.py
- [[test_hooks_honor_skip_env()]] - code - tests/test_hooks.py
- [[test_hooks_limit_windows_workers_by_default()]] - code - tests/test_hooks.py
- [[test_hooks_reuse_git_dir_from_env()]] - code - tests/test_hooks.py
- [[test_hooks_skip_linked_worktrees()]] - code - tests/test_hooks.py
- [[test_hooks_use_cross_platform_detach()]] - code - tests/test_hooks.py
- [[test_launcher_and_rebuild_body_are_valid_python()]] - code - tests/test_hooks.py
- [[test_launcher_payload_is_shell_quote_safe()]] - code - tests/test_hooks.py
- [[test_pinned_python_accepts_paths_containing_spaces()]] - code - tests/test_hooks.py
- [[test_pinned_python_still_rejects_shell_metacharacters()]] - code - tests/test_hooks.py
- [[test_rebuild_bodies_arm_a_timeout_without_sigalrm()]] - code - tests/test_hooks.py
- [[test_rebuild_bodies_read_graphify_root()]] - code - tests/test_hooks.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/parametrize
SORT file.name ASC
```

## Connections to other communities
- 13 edges to [[_COMMUNITY_test_hooks.py]]
- 3 edges to [[_COMMUNITY_test_file_path_allowlist_accepts_windows_backslash_path]]
- 2 edges to [[_COMMUNITY_hooks.py]]
- 1 edge to [[_COMMUNITY_test_hooks_dir_duplicate_config_keys_honor_custom_hookspath]]

## Top bridge nodes
- [[parametrize_9]] - degree 16, connects to 2 communities
- [[test_pinned_python_accepts_paths_containing_spaces()]] - degree 4, connects to 2 communities
- [[test_pinned_python_still_rejects_shell_metacharacters()]] - degree 4, connects to 2 communities
- [[_launcher_payload()]] - degree 4, connects to 1 community
- [[test_launcher_and_rebuild_body_are_valid_python()]] - degree 4, connects to 1 community