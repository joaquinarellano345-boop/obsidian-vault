---
type: community
cohesion: 0.05
members: 64
---

# test_codebuddy.py

**Cohesion:** 0.05 - loosely connected
**Members:** 64 nodes

## Members
- [[graphify skill must mention graphify query (query-first policy).]] - rationale - tests/test_codebuddy.py
- [[Install appends to an existing CODEBUDDY.md, preserving other content.]] - rationale - tests/test_codebuddy.py
- [[Install the graphify skill and CODEBUDDY.md section for CodeBuddy.]] - rationale - graphify/install.py
- [[Install then uninstall leaves no trace of graphify CODEBUDDY.md or hook.]] - rationale - tests/test_codebuddy.py
- [[Installed skill file must include graphify YAML frontmatter.]] - rationale - tests/test_codebuddy.py
- [[Project-scope destination must be project.codebuddyskillsgraphifySKILL.md.]] - rationale - tests/test_codebuddy.py
- [[Project-scope install registers PreToolUse hook in .codebuddysettings.json.]] - rationale - tests/test_codebuddy.py
- [[Project-scope install writes CODEBUDDY.md with graphify section.]] - rationale - tests/test_codebuddy.py
- [[Re-install does not duplicate  graphify sections.]] - rationale - tests/test_codebuddy.py
- [[Re-install replaces an old graphify section with the current template.]] - rationale - tests/test_codebuddy.py
- [[Remove the graphify skill tree (SKILL.md + references) and the graphify     sec]] - rationale - graphify/install.py
- [[Second install prints '(no change)' when content is identical.]] - rationale - tests/test_codebuddy.py
- [[Tests for graphify codebuddy install  uninstall commands.]] - rationale - tests/test_codebuddy.py
- [[The installed hook must include Bash matcher for code search interception.]] - rationale - tests/test_codebuddy.py
- [[The installed hook must include ReadGlob matcher for file-read interception.]] - rationale - tests/test_codebuddy.py
- [[Uninstall preserves non-graphify content in CODEBUDDY.md.]] - rationale - tests/test_codebuddy.py
- [[Uninstall removes the  graphify section from CODEBUDDY.md.]] - rationale - tests/test_codebuddy.py
- [[Uninstall removes the PreToolUse hook from .codebuddysettings.json.]] - rationale - tests/test_codebuddy.py
- [[Uninstall should not error when CODEBUDDY.md exists but no graphify section.]] - rationale - tests/test_codebuddy.py
- [[Uninstall should not raise when CODEBUDDY.md doesn't exist.]] - rationale - tests/test_codebuddy.py
- [[User-scope destination must be ~.codebuddyskillsgraphifySKILL.md.]] - rationale - tests/test_codebuddy.py
- [[User-scope install copies skill to ~.codebuddyskillsgraphifySKILL.md.]] - rationale - tests/test_codebuddy.py
- [[_codebuddy_install_user()]] - code - tests/test_codebuddy.py
- [[_codebuddy_md_path()]] - code - tests/test_codebuddy.py
- [[_settings_path()]] - code - tests/test_codebuddy.py
- [[_skill_path_project()]] - code - tests/test_codebuddy.py
- [[_skill_path_user()]] - code - tests/test_codebuddy.py
- [[codebuddy must be registered in _PLATFORM_CONFIG.]] - rationale - tests/test_codebuddy.py
- [[codebuddy_install()]] - code - graphify/install.py
- [[codebuddy_uninstall()]] - code - graphify/install.py
- [[graphify uninstall must clean up .codebuddysettings.json hooks.]] - rationale - tests/test_codebuddy.py
- [[graphify uninstall must clean up CODEBUDDY.md.]] - rationale - tests/test_codebuddy.py
- [[skill.md must be present in the installed package (shared with claude).]] - rationale - tests/test_codebuddy.py
- [[test_codebuddy.py]] - code - tests/test_codebuddy.py
- [[test_codebuddy_in_platform_config()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_hook_has_bash_matcher()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_hook_has_read_glob_matcher()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_idempotent()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_idempotent()_1]] - code - tests/test_install.py
- [[test_codebuddy_install_merges_existing_codebuddy_md()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_merges_existing_codebuddy_md()_1]] - code - tests/test_install.py
- [[test_codebuddy_install_prints_no_change_on_second_run()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_project_writes_codebuddy_md()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_project_writes_hook()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_upgrades_stale_section()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_user_creates_skill_file()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_install_writes_codebuddy_md()]] - code - tests/test_install.py
- [[test_codebuddy_install_writes_hook()]] - code - tests/test_install.py
- [[test_codebuddy_installation_roundtrip()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_platform_skill_destination_project_scope()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_platform_skill_destination_user_scope()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_skill_file_contains_frontmatter()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_skill_file_exists_in_package()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_skill_file_references_graphify_query()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_uninstall_noop_if_no_section()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_uninstall_noop_if_not_installed()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_uninstall_noop_if_not_installed()_1]] - code - tests/test_install.py
- [[test_codebuddy_uninstall_preserves_other_content()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_uninstall_removes_hook()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_uninstall_removes_hook()_1]] - code - tests/test_install.py
- [[test_codebuddy_uninstall_removes_section()]] - code - tests/test_codebuddy.py
- [[test_codebuddy_uninstall_removes_section()_1]] - code - tests/test_install.py
- [[test_uninstall_all_removes_codebuddy_hook()]] - code - tests/test_codebuddy.py
- [[test_uninstall_all_removes_codebuddy_md()]] - code - tests/test_codebuddy.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_codebuddypy
SORT file.name ASC
```

## Connections to other communities
- 17 edges to [[_COMMUNITY_graphify__main__.py]]
- 7 edges to [[_COMMUNITY_test_install.py]]
- 5 edges to [[_COMMUNITY_main]]
- 1 edge to [[_COMMUNITY__replace_or_append_section]]
- 1 edge to [[_COMMUNITY_claude_install]]
- 1 edge to [[_COMMUNITY_test_settings_merge.py]]
- 1 edge to [[_COMMUNITY_test_uninstall_scope.py]]

## Top bridge nodes
- [[codebuddy_install()]] - degree 27, connects to 3 communities
- [[codebuddy_uninstall()]] - degree 20, connects to 2 communities
- [[test_codebuddy.py]] - degree 32, connects to 1 community
- [[test_uninstall_all_removes_codebuddy_hook()]] - degree 4, connects to 1 community
- [[test_uninstall_all_removes_codebuddy_md()]] - degree 4, connects to 1 community