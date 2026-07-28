---
type: community
cohesion: 0.29
members: 10
---

# test_file_path_allowlist_accepts_windows_backslash_path

**Cohesion:** 0.29 - loosely connected
**Members:** 10 nodes

## Members
- [[2126 the .graphify_python FILE allowlist must accept real Windows paths     at]] - rationale - tests/test_hooks.py
- [[2126 the shebang-parsed launcher allowlist had no `` or `` at all, so     a]] - rationale - tests/test_hooks.py
- [[Guard against a naive fix (backslash right before ``) that forms a     ``-to-`]] - rationale - tests/test_hooks.py
- [[Pull the `!...` glob portion of a real case arm out of _PYTHON_DETECT     by]] - rationale - tests/test_hooks.py
- [[_extract_case_pattern()]] - code - tests/test_hooks.py
- [[_shell_verdict()]] - code - tests/test_hooks.py
- [[skipif_1]] - code
- [[test_file_path_allowlist_accepts_windows_backslash_path()]] - code - tests/test_hooks.py
- [[test_python_detect_allowlists_still_reject_shell_metacharacters()]] - code - tests/test_hooks.py
- [[test_shebang_allowlist_accepts_windows_backslash_path()]] - code - tests/test_hooks.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_file_path_allowlist_accepts_windows_backslash_path
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_test_hooks.py]]
- 3 edges to [[_COMMUNITY_parametrize]]

## Top bridge nodes
- [[test_file_path_allowlist_accepts_windows_backslash_path()]] - degree 6, connects to 2 communities
- [[test_python_detect_allowlists_still_reject_shell_metacharacters()]] - degree 6, connects to 2 communities
- [[test_shebang_allowlist_accepts_windows_backslash_path()]] - degree 6, connects to 2 communities
- [[_extract_case_pattern()]] - degree 5, connects to 1 community
- [[_shell_verdict()]] - degree 4, connects to 1 community