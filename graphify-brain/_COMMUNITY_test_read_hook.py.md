---
type: community
cohesion: 0.12
members: 28
---

# test_read_hook.py

**Cohesion:** 0.12 - loosely connected
**Members:** 28 nodes

## Members
- [[.astro.vue.svelte are real source types and must nudge (regression).]] - rationale - tests/test_read_hook.py
- [[A nudge is additionalContext only - the guard must exit 0, never deny.]] - rationale - tests/test_read_hook.py
- [[A real trailing extension must win on multi-dot names (the segment split)     a]] - rationale - tests/test_read_hook.py
- [[An extension that sits on a directory component, not the final segment,     must]] - rationale - tests/test_read_hook.py
- [[Backslash-separated paths split on the real final segment, then its ext.]] - rationale - tests/test_read_hook.py
- [[Config files must stay silent '.json' must not match the '.js' extension.]] - rationale - tests/test_read_hook.py
- [[Reading the graph's own report must not start a go-read-the-graph loop.]] - rationale - tests/test_read_hook.py
- [[The ReadGlob PreToolUse guard nudges toward the graph instead of raw reads.  Cl]] - rationale - tests/test_read_hook.py
- [[_env()_2]] - code - tests/test_read_hook.py
- [[_read_matcher()]] - code - tests/test_read_hook.py
- [[_run()_10]] - code - tests/test_read_hook.py
- [[test_astro_glob_nudges()]] - code - tests/test_read_hook.py
- [[test_command_has_no_shell_syntax()]] - code - tests/test_read_hook.py
- [[test_fails_open_on_malformed_stdin()]] - code - tests/test_read_hook.py
- [[test_glob_pattern_nudges()]] - code - tests/test_read_hook.py
- [[test_matcher_targets_read_and_glob()]] - code - tests/test_read_hook.py
- [[test_never_blocks()_1]] - code - tests/test_read_hook.py
- [[test_nudge_payload_is_valid_pretooluse_json()]] - code - tests/test_read_hook.py
- [[test_nudges_on_framework_source()]] - code - tests/test_read_hook.py
- [[test_nudges_on_multi_dot_source()]] - code - tests/test_read_hook.py
- [[test_nudges_on_source_read_with_graph()]] - code - tests/test_read_hook.py
- [[test_read_hook.py]] - code - tests/test_read_hook.py
- [[test_silent_on_graphify_out_targets()]] - code - tests/test_read_hook.py
- [[test_silent_on_json_config()]] - code - tests/test_read_hook.py
- [[test_silent_on_non_source_files()]] - code - tests/test_read_hook.py
- [[test_silent_when_extension_is_on_a_directory_segment()]] - code - tests/test_read_hook.py
- [[test_silent_without_graph()]] - code - tests/test_read_hook.py
- [[test_windows_path_nudges()]] - code - tests/test_read_hook.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_read_hookpy
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_graphify__main__.py]]
- 1 edge to [[_COMMUNITY_test_settings_merge.py]]

## Top bridge nodes
- [[test_read_hook.py]] - degree 21, connects to 1 community
- [[_read_matcher()]] - degree 4, connects to 1 community