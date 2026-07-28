---
type: community
cohesion: 0.22
members: 9
---

# _hooks_dir

**Cohesion:** 0.22 - loosely connected
**Members:** 9 nodes

## Members
- [[Raise if a hooks path looks like a Windows absolute path (1385).      On POSIX]] - rationale - graphify/hooks.py
- [[Return the git hooks directory, respecting core.hooksPath if set (e.g. Husky).]] - rationale - graphify/hooks.py
- [[_hooks_dir()]] - code - graphify/hooks.py
- [[_reject_windows_path()]] - code - graphify/hooks.py
- [[git legally allows duplicate keys and repeated sections in .gitconfig;     a st]] - rationale - tests/test_hooks.py
- [[test_hooks_dir_accepts_absolute_git_hooks_path()]] - code - tests/test_hooks.py
- [[test_hooks_dir_no_warning_on_duplicate_config_keys()]] - code - tests/test_hooks.py
- [[test_hooks_dir_rejects_multiline_git_output()]] - code - tests/test_hooks.py
- [[test_hooks_dir_resolves_relative_git_hooks_path()]] - code - tests/test_hooks.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_hooks_dir
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_hooks.py]]
- 5 edges to [[_COMMUNITY_install]]
- 5 edges to [[_COMMUNITY_test_hooks.py]]
- 2 edges to [[_COMMUNITY_test_hooks_dir_duplicate_config_keys_honor_custom_hookspath]]

## Top bridge nodes
- [[_hooks_dir()]] - degree 13, connects to 4 communities
- [[test_hooks_dir_no_warning_on_duplicate_config_keys()]] - degree 5, connects to 3 communities
- [[test_hooks_dir_accepts_absolute_git_hooks_path()]] - degree 3, connects to 2 communities
- [[test_hooks_dir_rejects_multiline_git_output()]] - degree 3, connects to 2 communities
- [[test_hooks_dir_resolves_relative_git_hooks_path()]] - degree 3, connects to 2 communities