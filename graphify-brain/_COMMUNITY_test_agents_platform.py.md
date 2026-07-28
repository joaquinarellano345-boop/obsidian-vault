---
type: community
cohesion: 0.10
members: 28
---

# test_agents_platform.py

**Cohesion:** 0.10 - loosely connected
**Members:** 28 nodes

## Members
- [[Bare `graphify uninstall` clears the ~.agentsskills skill the AGENTS.md and]] - rationale - tests/test_agents_platform.py
- [[Drive main() with argv, cwd at tmp_path, and Path.home redirected.]] - rationale - tests/test_agents_platform.py
- [[Global agents skill lands at ~.agentsskills (the spec's user-global dir),]] - rationale - tests/test_agents_platform.py
- [[Project agents skill lands at ..agentsskills.]] - rationale - tests/test_agents_platform.py
- [[Running `graphify agents install` twice leaves a single AGENTS.md section.]] - rationale - tests/test_agents_platform.py
- [[Tests for the generic `agents` platform and its `skills` alias (1432).  `graphi]] - rationale - tests/test_agents_platform.py
- [[_run()]] - code - tests/test_agents_platform.py
- [[`graphify agents install` is the amp-twin skill at ~.agentsskills PLUS a]] - rationale - tests/test_agents_platform.py
- [[`graphify install --platform agentsskills` writes ~.agentsskills...     SKIL]] - rationale - tests/test_agents_platform.py
- [[`graphify install --project --platform agents` writes ..agentsskills and     l]] - rationale - tests/test_agents_platform.py
- [[`graphify install` (no platform) stays single-platform claudewindows and     ne]] - rationale - tests/test_agents_platform.py
- [[`graphify skills install``uninstall` behaves exactly like the agents form]] - rationale - tests/test_agents_platform.py
- [[`graphify uninstall --platform agentsskills` (global) clears ~.agentsskills.]] - rationale - tests/test_agents_platform.py
- [[`graphify uninstall --project` (no platform) removes the agents project skill]] - rationale - tests/test_agents_platform.py
- [[parametrize]] - code
- [[test_agents_platform.py]] - code - tests/test_agents_platform.py
- [[test_agents_project_destination_is_dot_agents()]] - code - tests/test_agents_platform.py
- [[test_agents_subcommand_install_also_wires_agents_md()]] - code - tests/test_agents_platform.py
- [[test_agents_subcommand_install_is_idempotent()]] - code - tests/test_agents_platform.py
- [[test_agents_user_destination_is_user_global_dot_agents()]] - code - tests/test_agents_platform.py
- [[test_bare_install_does_not_touch_dot_agents()]] - code - tests/test_agents_platform.py
- [[test_install_platform_agents_project_writes_dot_agents()]] - code - tests/test_agents_platform.py
- [[test_install_platform_agents_writes_user_global_skill_only()]] - code - tests/test_agents_platform.py
- [[test_project_uninstall_all_removes_agents_skill()]] - code - tests/test_agents_platform.py
- [[test_skills_alias_resolves_to_agents()]] - code - tests/test_agents_platform.py
- [[test_skills_subcommand_is_the_agents_subcommand()]] - code - tests/test_agents_platform.py
- [[test_uninstall_platform_agents_removes_user_global_skill()]] - code - tests/test_agents_platform.py
- [[test_uninstall_platform_flag_global_removes_skill()]] - code - tests/test_agents_platform.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_agents_platformpy
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_graphify__main__.py]]
- 1 edge to [[_COMMUNITY_test_install.py]]

## Top bridge nodes
- [[test_agents_platform.py]] - degree 15, connects to 1 community
- [[_run()]] - degree 12, connects to 1 community