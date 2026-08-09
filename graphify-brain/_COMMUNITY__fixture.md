---
type: community
cohesion: 0.26
members: 25
---

# _fixture

**Cohesion:** 0.26 - loosely connected
**Members:** 25 nodes

## Members
- [[A project with graphify-outgraph.json + manifest and one source file.     ``fre]] - rationale - tests/test_hook_strict.py
- [[Strict-mode hook-guard opt-in block-then-nudge + 1840 gating.  The strict guar]] - rationale - tests/test_hook_strict.py
- [[_fixture()]] - code - tests/test_hook_strict.py
- [[_invoke()_1]] - code - tests/test_hook_strict.py
- [[_is_deny()]] - code - tests/test_hook_strict.py
- [[_read()]] - code - tests/test_hook_strict.py
- [[cache_root()]] - code - tests/test_cache.py
- [[test_env_forces_strict_on()]] - code - tests/test_hook_strict.py
- [[test_env_kills_strict()]] - code - tests/test_hook_strict.py
- [[test_expired_query_stamp_still_denies()]] - code - tests/test_hook_strict.py
- [[test_fail_open_on_malformed_stdin()]] - code - tests/test_hook_strict.py
- [[test_fresh_query_stamp_suppresses_deny()]] - code - tests/test_hook_strict.py
- [[test_glob_never_denies()]] - code - tests/test_hook_strict.py
- [[test_hook_strict.py]] - code - tests/test_hook_strict.py
- [[test_install_hook_carries_strict_flag()]] - code - tests/test_hook_strict.py
- [[test_needs_update_flag_softens()]] - code - tests/test_hook_strict.py
- [[test_no_session_id_never_denies()]] - code - tests/test_hook_strict.py
- [[test_not_indexed_file_not_denied()]] - code - tests/test_hook_strict.py
- [[test_out_of_project_read_silenced()]] - code - tests/test_hook_strict.py
- [[test_search_never_denies()]] - code - tests/test_hook_strict.py
- [[test_soft_mode_never_denies()]] - code - tests/test_hook_strict.py
- [[test_stale_graph_softens_never_denies()]] - code - tests/test_hook_strict.py
- [[test_strict_first_read_denies_then_nudges()]] - code - tests/test_hook_strict.py
- [[test_strict_new_session_denies_again()]] - code - tests/test_hook_strict.py
- [[tmp_file()]] - code - tests/test_cache.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_fixture
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_test_settings_merge.py]]
- 2 edges to [[_COMMUNITY_test_cache.py]]
- 1 edge to [[_COMMUNITY_extract_terraform]]
- 1 edge to [[_COMMUNITY__sandbox_home]]
- 1 edge to [[_COMMUNITY_no_tokenizer]]
- 1 edge to [[_COMMUNITY__call_claude_cli]]
- 1 edge to [[_COMMUNITY_test_falkordb_integration.py]]
- 1 edge to [[_COMMUNITY_test_install_references.py]]
- 1 edge to [[_COMMUNITY_test_install_roundtrip.py]]
- 1 edge to [[_COMMUNITY_test_wheel_packaging.py]]

## Top bridge nodes
- [[_fixture()]] - degree 26, connects to 7 communities
- [[test_hook_strict.py]] - degree 24, connects to 2 communities
- [[_invoke()_1]] - degree 17, connects to 1 community
- [[_read()]] - degree 12, connects to 1 community
- [[cache_root()]] - degree 2, connects to 1 community