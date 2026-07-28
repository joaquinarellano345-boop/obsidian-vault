---
type: community
cohesion: 0.09
members: 25
---

# test_hooks.py

**Cohesion:** 0.09 - loosely connected
**Members:** 25 nodes

## Members
- [[End-to-end against a real `git worktree` the guard falls through on the     pri]] - rationale - tests/test_hooks.py
- [[Hook script must skip shebang extraction for .exe binaries (Windows).]] - rationale - tests/test_hooks.py
- [[On Windows, `command -v graphify` can return the launcher path WITHOUT its     .]] - rationale - tests/test_hooks.py
- [[Return a POSIX-sh line that runs ``rebuild_body`` as a detached background     P]] - rationale - graphify/hooks.py
- [[Tests for hooks.py - git hook installuninstall.]] - rationale - tests/test_hooks.py
- [[The .graphify_root snippet must parse so a quoting slip can't ship a hook     th]] - rationale - tests/test_hooks.py
- [[The detection fallback must emit a message to stderr rather than bare exit 0.]] - rationale - tests/test_hooks.py
- [[The launcher must run via the resolved $GRAPHIFY_PYTHON, not a bare     `python`]] - rationale - tests/test_hooks.py
- [[The shared rebuild bodies are embedded verbatim into the launcher, so they     t]] - rationale - tests/test_hooks.py
- [[_detached_launch()]] - code - graphify/hooks.py
- [[_worktree_guard_snippet()]] - code - tests/test_hooks.py
- [[`python -c import graphify` executes the FULL package import — 10s+ on a     c]] - rationale - tests/test_hooks.py
- [[graphify hook-check must not emit additionalContext — Codex Desktop rejects it.]] - rationale - tests/test_hooks.py
- [[pip on Windows puts Scriptsgraphify(.exe) beside ..python.exe (or     .pyth]] - rationale - tests/test_hooks.py
- [[test_detached_launch_targets_graphify_python()]] - code - tests/test_hooks.py
- [[test_hook_check_no_additionalContext()]] - code - tests/test_hooks.py
- [[test_hook_skips_head_on_exe()]] - code - tests/test_hooks.py
- [[test_hooks.py]] - code - tests/test_hooks.py
- [[test_install_fallback_is_loud_not_silent()]] - code - tests/test_hooks.py
- [[test_probe_prefers_sibling_python_exe_on_windows_layouts()]] - code - tests/test_hooks.py
- [[test_probes_use_find_spec_not_full_import()]] - code - tests/test_hooks.py
- [[test_rebuild_bodies_are_shell_quote_safe()]] - code - tests/test_hooks.py
- [[test_rebuild_bodies_with_graphify_root_are_valid_python()]] - code - tests/test_hooks.py
- [[test_shebang_read_is_null_byte_safe()]] - code - tests/test_hooks.py
- [[test_worktree_guard_runs_on_primary_skips_linked()]] - code - tests/test_hooks.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_hookspy
SORT file.name ASC
```

## Connections to other communities
- 21 edges to [[_COMMUNITY_install]]
- 13 edges to [[_COMMUNITY_parametrize]]
- 8 edges to [[_COMMUNITY_hooks.py]]
- 5 edges to [[_COMMUNITY__hooks_dir]]
- 5 edges to [[_COMMUNITY_test_hooks_dir_duplicate_config_keys_honor_custom_hookspath]]
- 5 edges to [[_COMMUNITY_test_file_path_allowlist_accepts_windows_backslash_path]]

## Top bridge nodes
- [[test_hooks.py]] - degree 69, connects to 6 communities
- [[_detached_launch()]] - degree 4, connects to 1 community