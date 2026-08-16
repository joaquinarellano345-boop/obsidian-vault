---
type: community
cohesion: 0.11
members: 26
---

# _install_claude_hook

**Cohesion:** 0.11 - loosely connected
**Members:** 26 nodes

## Members
- [[2165 the PreToolUse command in .codexhooks.json must be a command the CLI]] - rationale - tests/test_install.py
- [[Abort a hook install rather than clobber a config file we can't parse (2167).]] - rationale - graphify/install.py
- [[Add graphify PreToolUse hook to .claudesettings.json.]] - rationale - graphify/install.py
- [[Add graphify PreToolUse hook to .codexhooks.json.]] - rationale - graphify/install.py
- [[Gemini CLI BeforeTool hook, resolved to a shell-agnostic `graphify` call.]] - rationale - graphify/install.py
- [[Load an existing settingshooks JSON file for a read-modify-write merge.      A]] - rationale - graphify/install.py
- [[Return the absolute path to the graphify executable, with forward slashes.]] - rationale - graphify/install.py
- [[Serialize ``settings`` to ``settings_path``, backing up the previous file.]] - rationale - graphify/install.py
- [[Subcommand names the CLI actually dispatches.      `graphify`'s dispatcher is an]] - rationale - tests/test_install.py
- [[_claude_pretooluse_hooks()]] - code - graphify/install.py
- [[_cli_dispatched_commands()]] - code - tests/test_install.py
- [[_gemini_hook()]] - code - graphify/install.py
- [[_install_claude_hook()]] - code - graphify/install.py
- [[_install_codebuddy_hook()]] - code - graphify/install.py
- [[_install_codex_hook()]] - code - graphify/install.py
- [[_install_gemini_hook()]] - code - graphify/install.py
- [[_read_settings_for_merge()]] - code - graphify/install.py
- [[_refuse_to_modify()]] - code - graphify/install.py
- [[_resolve_graphify_exe()]] - code - graphify/install.py
- [[_write_settings_with_backup()]] - code - graphify/install.py
- [[graphify's ClaudeCodebuddy PreToolUse hooks, resolved at install time.      The]] - rationale - graphify/install.py
- [[test_claude_hook_install_idempotent_and_replaces_old_bash_hook()]] - code - tests/test_install.py
- [[test_claude_hook_is_shell_agnostic()]] - code - tests/test_install.py
- [[test_codex_hook_command_is_a_real_cli_subcommand()]] - code - tests/test_install.py
- [[test_hook_command_has_no_backslashes()]] - code - tests/test_search_hook.py
- [[test_matcher_and_command_shape()]] - code - tests/test_gemini_hook.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_install_claude_hook
SORT file.name ASC
```

## Connections to other communities
- 26 edges to [[_COMMUNITY_graphify__main__.py]]
- 6 edges to [[_COMMUNITY_test_install.py]]
- 4 edges to [[_COMMUNITY_test_settings_merge.py]]
- 2 edges to [[_COMMUNITY__fixture]]
- 2 edges to [[_COMMUNITY_test_search_hook.py]]
- 1 edge to [[_COMMUNITY_test_read_hook.py]]
- 1 edge to [[_COMMUNITY_claude_install]]
- 1 edge to [[_COMMUNITY_test_codebuddy.py]]
- 1 edge to [[_COMMUNITY_test_gemini_hook.py]]

## Top bridge nodes
- [[_claude_pretooluse_hooks()]] - degree 11, connects to 4 communities
- [[_install_claude_hook()]] - degree 12, connects to 3 communities
- [[_install_codex_hook()]] - degree 12, connects to 3 communities
- [[_install_codebuddy_hook()]] - degree 10, connects to 3 communities
- [[_install_gemini_hook()]] - degree 9, connects to 3 communities