---
type: community
cohesion: 0.05
members: 40
---

# main

**Cohesion:** 0.05 - loosely connected
**Members:** 40 nodes

## Members
- [[--timing prints per-stage `graphify timing` lines to stderr (1490); omitting]] - rationale - tests/test_extract_cli.py
- [[A pre-fix ~.ampskillsgraphify install is removed on the next install.]] - rationale - tests/test_install.py
- [[Console entry point. Wraps the CLI so that when a downstream consumer closes]] - rationale - graphify/__main__.py
- [[Global `graphify antigravity install` must write to ~.geminiconfigskills (1]] - rationale - tests/test_install.py
- [[Global `graphify antigravity uninstall` must remove from ~.geminiconfigskills]] - rationale - tests/test_install.py
- [[Handle a downstream reader that closed the pipe early. Redirect stdout to     de]] - rationale - graphify/__main__.py
- [[Project-scope amp install lands in .agentsskills, an Amp project search root.]] - rationale - tests/test_install.py
- [[Project-scope install prints a git add hint covering .devin and .windsurf.]] - rationale - tests/test_devin.py
- [[Project-scoped install via CLI prints a git add hint.]] - rationale - tests/test_codebuddy.py
- [[The user-scope `graphify uninstall` enumeration removes the amp skill.]] - rationale - tests/test_install.py
- [[User-scope uninstall prints an appropriate message when nothing is installed.]] - rationale - tests/test_devin.py
- [[_silence_broken_pipe()]] - code - graphify/__main__.py
- [[`graphify --help` must list codebuddy in the platform list and per-platform sect]] - rationale - tests/test_codebuddy.py
- [[`graphify --help` must list devin in the platform list and in the per-platform s]] - rationale - tests/test_devin.py
- [[`graphify amp install` (user scope) must drop the skill into an Amp search     r]] - rationale - tests/test_install.py
- [[`graphify amp uninstall` removes the user-scope skill and AGENTS.md section.]] - rationale - tests/test_install.py
- [[main()]] - code - graphify/__main__.py
- [[test_amp_install_cleans_legacy_amp_skills_dir()]] - code - tests/test_install.py
- [[test_amp_project_install_lands_in_dot_agents()]] - code - tests/test_install.py
- [[test_amp_user_install_lands_in_config_agents()]] - code - tests/test_install.py
- [[test_amp_user_uninstall_removes_skill_and_agents()]] - code - tests/test_install.py
- [[test_antigravity_global_install_writes_gemini_config_skills()]] - code - tests/test_install.py
- [[test_antigravity_global_uninstall_removes_gemini_config_skill()]] - code - tests/test_install.py
- [[test_antigravity_install_project_writes_project_skill()]] - code - tests/test_install.py
- [[test_antigravity_uninstall_project_removes_project_skill_only()]] - code - tests/test_install.py
- [[test_claude_subcommand_project_install_and_uninstall_are_project_scoped()]] - code - tests/test_install.py
- [[test_codebuddy_in_main_help_text()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_hint_git_add()]] - code - tests/test_codebuddy.py
- [[test_codex_subcommand_project_install_and_uninstall_are_project_scoped()]] - code - tests/test_install.py
- [[test_devin_in_main_help_text()]] - code - tests/test_devin.py
- [[test_devin_install_project_hints_git_add()]] - code - tests/test_devin.py
- [[test_devin_uninstall_user_noop_when_not_installed()]] - code - tests/test_devin.py
- [[test_extract_timing_flag_emits_stage_timings()]] - code - tests/test_extract_cli.py
- [[test_install_help_does_not_install_default()]] - code - tests/test_install.py
- [[test_install_positional_platform_opencode()]] - code - tests/test_install.py
- [[test_install_project_claude_writes_project_scope()]] - code - tests/test_install.py
- [[test_install_project_codex_writes_skill_and_agents()]] - code - tests/test_install.py
- [[test_uninstall_all_removes_amp_user_skill()]] - code - tests/test_install.py
- [[test_uninstall_project_removes_project_skill_only()]] - code - tests/test_install.py
- [[test_uninstall_project_without_platform_removes_project_installs()]] - code - tests/test_install.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/main
SORT file.name ASC
```

## Connections to other communities
- 18 edges to [[_COMMUNITY_test_install.py]]
- 10 edges to [[_COMMUNITY_test_extract_cli.py]]
- 9 edges to [[_COMMUNITY_test_devin.py]]
- 9 edges to [[_COMMUNITY_test_incomplete_build_guard.py]]
- 7 edges to [[_COMMUNITY_test_affected_cli.py]]
- 6 edges to [[_COMMUNITY_test_multigraph_diagnostics.py]]
- 5 edges to [[_COMMUNITY_test_codebuddy.py]]
- 5 edges to [[_COMMUNITY_test_query_cli.py]]
- 3 edges to [[_COMMUNITY_graphify__main__.py]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_test_install_references.py]]
- 2 edges to [[_COMMUNITY_test_path_cli.py]]
- 1 edge to [[_COMMUNITY_test_agents_platform.py]]
- 1 edge to [[_COMMUNITY_test_explain_cli.py]]
- 1 edge to [[_COMMUNITY_test_god_nodes_cli.py]]
- 1 edge to [[_COMMUNITY_test_merge_chunks_validation.py]]

## Top bridge nodes
- [[main()]] - degree 83, connects to 16 communities
- [[_silence_broken_pipe()]] - degree 3, connects to 1 community
- [[test_codebuddy_in_main_help_text()]] - degree 3, connects to 1 community
- [[test_codebuddy_install_hint_git_add()]] - degree 3, connects to 1 community
- [[test_devin_in_main_help_text()]] - degree 3, connects to 1 community