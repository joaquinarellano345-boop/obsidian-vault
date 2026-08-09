---
type: community
cohesion: 0.29
members: 7
---

# test_home_sandbox.py

**Cohesion:** 0.29 - loosely connected
**Members:** 7 nodes

## Members
- [[Global skill deletes land inside the sandbox home, never the real one.      Sinc]] - rationale - tests/test_home_sandbox.py
- [[Regression tests for the repo-wide HOME sandbox (issue 2168).  The autouse ``_s]] - rationale - tests/test_home_sandbox.py
- [[test_claude_config_dir_escape_hatch_is_cleared()]] - code - tests/test_home_sandbox.py
- [[test_expanduser_is_sandboxed()]] - code - tests/test_home_sandbox.py
- [[test_global_uninstall_is_captured_by_sandbox()]] - code - tests/test_home_sandbox.py
- [[test_home_sandbox.py]] - code - tests/test_home_sandbox.py
- [[test_path_home_is_sandboxed()]] - code - tests/test_home_sandbox.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_home_sandboxpy
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_graphify__main__.py]]
- 1 edge to [[_COMMUNITY_claude_install]]

## Top bridge nodes
- [[test_home_sandbox.py]] - degree 6, connects to 1 community
- [[test_global_uninstall_is_captured_by_sandbox()]] - degree 3, connects to 1 community