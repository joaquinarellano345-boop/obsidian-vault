---
type: community
cohesion: 0.03
members: 119
---

# test_install.py

**Cohesion:** 0.03 - loosely connected
**Members:** 119 nodes

## Members
- [[1403 on Windows, Hermes scans %LOCALAPPDATA%hermesskills, so the global]] - rationale - tests/test_install.py
- [[2062 end-to-end uninstall strips graphify's own H2 section but leaves a     us]] - rationale - tests/test_install.py
- [[2062 a file with only a user ` graphify` H3 (graphify never installed)]] - rationale - tests/test_install.py
- [[2062 the strip helper must match graphify's own ` graphify` heading     exac]] - rationale - tests/test_install.py
- [[2165 the PreToolUse command in .codexhooks.json must be a command the CLI]] - rationale - tests/test_install.py
- [[A pre-fix ~.ampskillsgraphify install is removed on the next install.]] - rationale - tests/test_install.py
- [[All installable platform skill files must be present in the installed package.]] - rationale - tests/test_install.py
- [[Claude platform install writes CLAUDE.md; others do not.]] - rationale - tests/test_install.py
- [[Codex skill file must reference spawn_agent.]] - rationale - tests/test_install.py
- [[Codex skill must keep graph-first orientation in the lean-core split.      The p]] - rationale - tests/test_install.py
- [[Console entry point. Wraps the CLI so that when a downstream consumer closes]] - rationale - graphify/__main__.py
- [[Global `graphify antigravity install` must write to ~.geminiconfigskills (1]] - rationale - tests/test_install.py
- [[Global `graphify antigravity uninstall` must remove from ~.geminiconfigskills]] - rationale - tests/test_install.py
- [[Handle a downstream reader that closed the pipe early. Redirect stdout to     de]] - rationale - graphify/__main__.py
- [[Installing twice does not duplicate the section.]] - rationale - tests/test_install.py
- [[Installs into an existing AGENTS.md without overwriting other content.]] - rationale - tests/test_install.py
- [[Kilo runs snippets through double-quoted python -c strings.]] - rationale - tests/test_install.py
- [[Kilo skill file should use the native Task tool flow.]] - rationale - tests/test_install.py
- [[Non-Windows hermes destination is unchanged (~.hermesskills).]] - rationale - tests/test_install.py
- [[OpenClaw rides the shared Agent-tool disk-collect dispatch.      The consolidate]] - rationale - tests/test_install.py
- [[OpenCode skill file must reference @mention.]] - rationale - tests/test_install.py
- [[OpenCode's dispatch slot uses @mention, not the Claude Agent-tool example.]] - rationale - tests/test_install.py
- [[Project-scope amp install lands in .agentsskills, an Amp project search root.]] - rationale - tests/test_install.py
- [[Subcommand names the CLI actually dispatches.      `graphify`'s dispatcher is an]] - rationale - tests/test_install.py
- [[Tests for graphify install --platform routing.]] - rationale - tests/test_install.py
- [[The bash reminder string must not contain backticks or $(...) (regression test f]] - rationale - tests/test_install.py
- [[The reminder must be joined to the user's command with ';', not '&&'     (1646)]] - rationale - tests/test_install.py
- [[The user-scope `graphify uninstall` enumeration removes the amp skill.]] - rationale - tests/test_install.py
- [[Uninstall keeps pre-existing content.]] - rationale - tests/test_install.py
- [[_agents_install()_1]] - code - tests/test_install.py
- [[_agents_uninstall()_1]] - code - tests/test_install.py
- [[_cli_dispatched_commands()]] - code - tests/test_install.py
- [[_install()]] - code - tests/test_install.py
- [[_kilo_install()_1]] - code - tests/test_install.py
- [[_kilo_uninstall()_1]] - code - tests/test_install.py
- [[_silence_broken_pipe()]] - code - graphify/__main__.py
- [[`graphify amp install` (user scope) must drop the skill into an Amp search     r]] - rationale - tests/test_install.py
- [[`graphify amp uninstall` removes the user-scope skill and AGENTS.md section.]] - rationale - tests/test_install.py
- [[cursor install does not overwrite an existing rule file.]] - rationale - tests/test_install.py
- [[cursor install writes .cursorrulesgraphify.mdc.]] - rationale - tests/test_install.py
- [[cursor uninstall does nothing if rule was never written.]] - rationale - tests/test_install.py
- [[main()]] - code - graphify/__main__.py
- [[opencode install preserves existing .opencodeopencode.json keys.]] - rationale - tests/test_install.py
- [[opencode install registers the plugin in .opencodeopencode.json.]] - rationale - tests/test_install.py
- [[opencode install writes .opencodepluginsgraphify.js.]] - rationale - tests/test_install.py
- [[opencode uninstall removes the plugin file and deregisters from opencode.json.]] - rationale - tests/test_install.py
- [[test_agents_install_appends_to_existing()]] - code - tests/test_install.py
- [[test_agents_install_idempotent()]] - code - tests/test_install.py
- [[test_agents_uninstall_no_op_when_not_installed()]] - code - tests/test_install.py
- [[test_agents_uninstall_preserves_other_content()]] - code - tests/test_install.py
- [[test_agents_uninstall_preserves_user_h3_graphify_heading()]] - code - tests/test_install.py
- [[test_agents_uninstall_removes_section()]] - code - tests/test_install.py
- [[test_all_skill_files_exist_in_package()]] - code - tests/test_install.py
- [[test_amp_install_cleans_legacy_amp_skills_dir()]] - code - tests/test_install.py
- [[test_amp_project_install_lands_in_dot_agents()]] - code - tests/test_install.py
- [[test_amp_user_install_lands_in_config_agents()]] - code - tests/test_install.py
- [[test_amp_user_uninstall_removes_skill_and_agents()]] - code - tests/test_install.py
- [[test_antigravity_global_install_writes_gemini_config_skills()]] - code - tests/test_install.py
- [[test_antigravity_global_uninstall_removes_gemini_config_skill()]] - code - tests/test_install.py
- [[test_antigravity_install_project_writes_project_skill()]] - code - tests/test_install.py
- [[test_antigravity_uninstall_project_removes_project_skill_only()]] - code - tests/test_install.py
- [[test_claude_install_registers_claude_md()]] - code - tests/test_install.py
- [[test_claude_subcommand_project_install_and_uninstall_are_project_scoped()]] - code - tests/test_install.py
- [[test_claw_agents_install_writes_agents_md()]] - code - tests/test_install.py
- [[test_claw_skill_uses_agent_tool_dispatch()]] - code - tests/test_install.py
- [[test_codex_agents_install_mentions_dirty_graph_output()]] - code - tests/test_install.py
- [[test_codex_agents_install_writes_agents_md()]] - code - tests/test_install.py
- [[test_codex_hook_command_is_a_real_cli_subcommand()]] - code - tests/test_install.py
- [[test_codex_install_does_not_write_claude_md()]] - code - tests/test_install.py
- [[test_codex_skill_contains_spawn_agent()]] - code - tests/test_install.py
- [[test_codex_skill_uses_graphify_with_existing_graph()]] - code - tests/test_install.py
- [[test_codex_subcommand_project_install_and_uninstall_are_project_scoped()]] - code - tests/test_install.py
- [[test_cursor_install_idempotent()]] - code - tests/test_install.py
- [[test_cursor_install_writes_rule()]] - code - tests/test_install.py
- [[test_cursor_uninstall_noop_if_not_installed()]] - code - tests/test_install.py
- [[test_gemini_uninstall_noop_if_not_installed()]] - code - tests/test_install.py
- [[test_hermes_skill_destination_posix_uses_home()]] - code - tests/test_install.py
- [[test_hermes_skill_destination_windows_uses_localappdata()]] - code - tests/test_install.py
- [[test_install.py]] - code - tests/test_install.py
- [[test_install_claw()]] - code - tests/test_install.py
- [[test_install_codebuddy()]] - code - tests/test_install.py
- [[test_install_codex()]] - code - tests/test_install.py
- [[test_install_default_claude()]] - code - tests/test_install.py
- [[test_install_droid()]] - code - tests/test_install.py
- [[test_install_help_does_not_install_default()]] - code - tests/test_install.py
- [[test_install_opencode()]] - code - tests/test_install.py
- [[test_install_positional_platform_opencode()]] - code - tests/test_install.py
- [[test_install_project_claude_writes_project_scope()]] - code - tests/test_install.py
- [[test_install_project_codex_writes_skill_and_agents()]] - code - tests/test_install.py
- [[test_install_trae()]] - code - tests/test_install.py
- [[test_install_trae_cn()]] - code - tests/test_install.py
- [[test_install_unknown_platform_exits()]] - code - tests/test_install.py
- [[test_install_windows()]] - code - tests/test_install.py
- [[test_kilo_agents_install_idempotent()]] - code - tests/test_install.py
- [[test_kilo_agents_install_merges_existing_config()]] - code - tests/test_install.py
- [[test_kilo_agents_install_preserves_existing_jsonc_config()]] - code - tests/test_install.py
- [[test_kilo_agents_install_registers_plugin_in_config()]] - code - tests/test_install.py
- [[test_kilo_agents_install_writes_agents_md()]] - code - tests/test_install.py
- [[test_kilo_agents_install_writes_plugin()]] - code - tests/test_install.py
- [[test_kilo_agents_uninstall_preserves_existing_jsonc_config()]] - code - tests/test_install.py
- [[test_kilo_command_file_exists_in_package()]] - code - tests/test_install.py
- [[test_kilo_install_writes_global_and_project_artifacts()]] - code - tests/test_install.py
- [[test_kilo_skill_avoids_double_quoted_python_c_fstring_dict_keys()]] - code - tests/test_install.py
- [[test_kilo_skill_mentions_task_tool()]] - code - tests/test_install.py
- [[test_kilo_uninstall_removes_plugin_registration_and_command()]] - code - tests/test_install.py
- [[test_opencode_agents_install_merges_existing_config()]] - code - tests/test_install.py
- [[test_opencode_agents_install_registers_plugin_in_config()]] - code - tests/test_install.py
- [[test_opencode_agents_install_writes_agents_md()]] - code - tests/test_install.py
- [[test_opencode_agents_install_writes_plugin()]] - code - tests/test_install.py
- [[test_opencode_agents_uninstall_removes_plugin()]] - code - tests/test_install.py
- [[test_opencode_plugin_reminder_has_no_backticks()]] - code - tests/test_install.py
- [[test_opencode_plugin_uses_semicolon_not_ampersand()]] - code - tests/test_install.py
- [[test_opencode_skill_contains_mention()]] - code - tests/test_install.py
- [[test_opencode_skill_uses_opencode_agent_guidance()]] - code - tests/test_install.py
- [[test_remove_marker_section_matches_exact_heading_only()]] - code - tests/test_install.py
- [[test_uninstall_all_removes_amp_user_skill()]] - code - tests/test_install.py
- [[test_uninstall_project_removes_project_skill_only()]] - code - tests/test_install.py
- [[test_uninstall_project_without_platform_removes_project_installs()]] - code - tests/test_install.py
- [[test_uninstall_untouched_when_only_user_h3_present()]] - code - tests/test_install.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_installpy
SORT file.name ASC
```

## Connections to other communities
- 22 edges to [[_COMMUNITY_graphify__main__.py]]
- 12 edges to [[_COMMUNITY_test_codebuddy.py]]
- 10 edges to [[_COMMUNITY_test_extract_cli.py]]
- 9 edges to [[_COMMUNITY_test_devin.py]]
- 9 edges to [[_COMMUNITY_test_incomplete_build_guard.py]]
- 7 edges to [[_COMMUNITY_test_affected_cli.py]]
- 6 edges to [[_COMMUNITY_test_multigraph_diagnostics.py]]
- 5 edges to [[_COMMUNITY_test_query_cli.py]]
- 3 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_test_install_references.py]]
- 2 edges to [[_COMMUNITY_test_path_cli.py]]
- 1 edge to [[_COMMUNITY_test_agents_platform.py]]
- 1 edge to [[_COMMUNITY_test_explain_cli.py]]
- 1 edge to [[_COMMUNITY_test_god_nodes_cli.py]]
- 1 edge to [[_COMMUNITY_test_merge_chunks_validation.py]]

## Top bridge nodes
- [[main()]] - degree 83, connects to 15 communities
- [[test_install.py]] - degree 99, connects to 3 communities
- [[test_codex_hook_command_is_a_real_cli_subcommand()]] - degree 4, connects to 1 community
- [[_silence_broken_pipe()]] - degree 3, connects to 1 community
- [[test_cursor_install_idempotent()]] - degree 3, connects to 1 community