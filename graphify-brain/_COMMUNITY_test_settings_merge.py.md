---
type: community
cohesion: 0.21
members: 20
---

# test_settings_merge.py

**Cohesion:** 0.21 - loosely connected
**Members:** 20 nodes

## Members
- [[2167 core case every key graphify does not own must survive install.]] - rationale - tests/test_settings_merge.py
- [[A UTF-8 BOM must not trigger the parse-error path that used to clobber.]] - rationale - tests/test_settings_merge.py
- [[A legacy non-dict entry in the managed section must not crash the filter     (th]] - rationale - tests/test_settings_merge.py
- [[A malformed hooks value (not a dict) refuses instead of raisingclobbering.]] - rationale - tests/test_settings_merge.py
- [[ALL_INSTALLERS]] - code
- [[An unparseable existing file must abort the install, byte-identical on disk.]] - rationale - tests/test_settings_merge.py
- [[Path_97]] - code
- [[Regression tests for issue 2167 hook installers must merge into existing setti]] - rationale - tests/test_settings_merge.py
- [[Valid JSON that is not an object (e.g. a list) must also refuse, not crash.]] - rationale - tests/test_settings_merge.py
- [[_run()_13]] - code - tests/test_settings_merge.py
- [[_seed()]] - code - tests/test_settings_merge.py
- [[test_backup_written_before_modify_and_stable_on_reinstall()]] - code - tests/test_settings_merge.py
- [[test_bom_settings_are_merged_not_clobbered()]] - code - tests/test_settings_merge.py
- [[test_claude_install_preserves_existing_settings()]] - code - tests/test_settings_merge.py
- [[test_invalid_json_aborts_without_clobbering()]] - code - tests/test_settings_merge.py
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
- 5 edges to [[_COMMUNITY_graphify__main__.py]]

## Top bridge nodes
- [[test_settings_merge.py]] - degree 16, connects to 1 community