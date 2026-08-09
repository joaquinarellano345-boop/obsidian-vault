---
type: community
cohesion: 0.09
members: 42
---

# test_settings_merge.py

**Cohesion:** 0.09 - loosely connected
**Members:** 42 nodes

## Members
- [[2167 core case every key graphify does not own must survive install.]] - rationale - tests/test_settings_merge.py
- [[A UTF-8 BOM must not trigger the parse-error path that used to clobber.]] - rationale - tests/test_settings_merge.py
- [[A legacy non-dict entry in the managed section must not crash the filter     (th]] - rationale - tests/test_settings_merge.py
- [[A malformed hooks value (not a dict) refuses instead of raisingclobbering.]] - rationale - tests/test_settings_merge.py
- [[ALL_INSTALLERS]] - code
- [[Abort a hook install rather than clobber a config file we can't parse (2167).]] - rationale - graphify/install.py
- [[Add graphify PreToolUse hook to .claudesettings.json.]] - rationale - graphify/install.py
- [[Add graphify PreToolUse hook to .codexhooks.json.]] - rationale - graphify/install.py
- [[An unparseable existing file must abort the install, byte-identical on disk.]] - rationale - tests/test_settings_merge.py
- [[Gemini CLI BeforeTool hook, resolved to a shell-agnostic `graphify` call.]] - rationale - graphify/install.py
- [[Load an existing settingshooks JSON file for a read-modify-write merge.      A]] - rationale - graphify/install.py
- [[Path_97]] - code
- [[Regression tests for issue 2167 hook installers must merge into existing setti]] - rationale - tests/test_settings_merge.py
- [[Return the absolute path to the graphify executable, with forward slashes.]] - rationale - graphify/install.py
- [[Serialize ``settings`` to ``settings_path``, backing up the previous file.]] - rationale - graphify/install.py
- [[Valid JSON that is not an object (e.g. a list) must also refuse, not crash.]] - rationale - tests/test_settings_merge.py
- [[_claude_pretooluse_hooks()]] - code - graphify/install.py
- [[_gemini_hook()]] - code - graphify/install.py
- [[_install_claude_hook()]] - code - graphify/install.py
- [[_install_codebuddy_hook()]] - code - graphify/install.py
- [[_install_codex_hook()]] - code - graphify/install.py
- [[_install_gemini_hook()]] - code - graphify/install.py
- [[_read_settings_for_merge()]] - code - graphify/install.py
- [[_refuse_to_modify()]] - code - graphify/install.py
- [[_resolve_graphify_exe()]] - code - graphify/install.py
- [[_run()_13]] - code - tests/test_settings_merge.py
- [[_seed()]] - code - tests/test_settings_merge.py
- [[_write_settings_with_backup()]] - code - graphify/install.py
- [[graphify's ClaudeCodebuddy PreToolUse hooks, resolved at install time.      The]] - rationale - graphify/install.py
- [[test_backup_written_before_modify_and_stable_on_reinstall()]] - code - tests/test_settings_merge.py
- [[test_bom_settings_are_merged_not_clobbered()]] - code - tests/test_settings_merge.py
- [[test_claude_hook_install_idempotent_and_replaces_old_bash_hook()]] - code - tests/test_install.py
- [[test_claude_hook_is_shell_agnostic()]] - code - tests/test_install.py
- [[test_claude_install_preserves_existing_settings()]] - code - tests/test_settings_merge.py
- [[test_hook_command_has_no_backslashes()]] - code - tests/test_search_hook.py
- [[test_invalid_json_aborts_without_clobbering()]] - code - tests/test_settings_merge.py
- [[test_matcher_and_command_shape()]] - code - tests/test_gemini_hook.py
- [[test_no_backup_on_fresh_install()]] - code - tests/test_settings_merge.py
- [[test_non_dict_hook_entry_is_preserved_not_fatal()]] - code - tests/test_settings_merge.py
- [[test_non_dict_hooks_section_aborts()]] - code - tests/test_settings_merge.py
- [[test_non_object_top_level_aborts_without_clobbering()]] - code - tests/test_settings_merge.py
- [[test_settings_merge.py]] - code - tests/test_settings_merge.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_settings_mergepy
SORT file.name ASC
```

## Connections to other communities
- 27 edges to [[_COMMUNITY_graphify__main__.py]]
- 5 edges to [[_COMMUNITY_test_install.py]]
- 2 edges to [[_COMMUNITY__fixture]]
- 2 edges to [[_COMMUNITY_test_search_hook.py]]
- 1 edge to [[_COMMUNITY_test_read_hook.py]]
- 1 edge to [[_COMMUNITY_claude_install]]
- 1 edge to [[_COMMUNITY_test_codebuddy.py]]
- 1 edge to [[_COMMUNITY_test_gemini_hook.py]]

## Top bridge nodes
- [[_claude_pretooluse_hooks()]] - degree 11, connects to 4 communities
- [[_install_claude_hook()]] - degree 12, connects to 2 communities
- [[_install_codex_hook()]] - degree 12, connects to 2 communities
- [[_install_codebuddy_hook()]] - degree 10, connects to 2 communities
- [[_install_gemini_hook()]] - degree 9, connects to 2 communities