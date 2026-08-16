---
type: community
cohesion: 0.08
members: 40
---

# claude_install

**Cohesion:** 0.08 - loosely connected
**Members:** 40 nodes

## Members
- [[A hook relocated to .claudesettings.local.json is removed on uninstall.]] - rationale - tests/test_claude_md.py
- [[A non-UTF-8 CLAUDE.local.md must not abort uninstall (it has no marker to strip)]] - rationale - tests/test_claude_md.py
- [[Appends to an existing CLAUDE.md without clobbering it.]] - rationale - tests/test_claude_md.py
- [[Creates CLAUDE.md when none exists.]] - rationale - tests/test_claude_md.py
- [[Instructions relocated to .claudeCLAUDE.local.md are removed on uninstall.]] - rationale - tests/test_claude_md.py
- [[Removes the graphify section after it was installed.]] - rationale - tests/test_claude_md.py
- [[Running claude_install twice does not duplicate the PreToolUse hook.]] - rationale - tests/test_claude_md.py
- [[Running install twice does not duplicate the section.]] - rationale - tests/test_claude_md.py
- [[Second install prints the 'already configured' message.]] - rationale - tests/test_claude_md.py
- [[Tests for graphify claude install  uninstall commands.]] - rationale - tests/test_claude_md.py
- [[Uninstall keeps non-graphify content in CLAUDE.local.md.]] - rationale - tests/test_claude_md.py
- [[Uninstall keeps pre-existing content outside the graphify section.]] - rationale - tests/test_claude_md.py
- [[Uninstall on a CLAUDE.md without graphify section prints a message and exits cle]] - rationale - tests/test_claude_md.py
- [[Uninstall when no CLAUDE.md exists prints a message and exits cleanly.]] - rationale - tests/test_claude_md.py
- [[When the section lives in both CLAUDE.md and a local variant, both are cleaned.]] - rationale - tests/test_claude_md.py
- [[Write the graphify section to the local CLAUDE.md.]] - rationale - graphify/install.py
- [[Written section includes the three rules.]] - rationale - tests/test_claude_md.py
- [[claude_install also writes .claudesettings.json with PreToolUse hook.]] - rationale - tests/test_claude_md.py
- [[claude_install()]] - code - graphify/install.py
- [[claude_uninstall removes the PreToolUse hook from settings.json.]] - rationale - tests/test_claude_md.py
- [[claude_uninstall()]] - code - graphify/install.py
- [[test_claude_md.py]] - code - tests/test_claude_md.py
- [[test_install_appends_to_existing_claude_md()]] - code - tests/test_claude_md.py
- [[test_install_contains_expected_rules()]] - code - tests/test_claude_md.py
- [[test_install_creates_claude_md()]] - code - tests/test_claude_md.py
- [[test_install_creates_settings_json()]] - code - tests/test_claude_md.py
- [[test_install_idempotent_message()]] - code - tests/test_claude_md.py
- [[test_install_is_idempotent()]] - code - tests/test_claude_md.py
- [[test_install_settings_json_idempotent()]] - code - tests/test_claude_md.py
- [[test_uninstall_cleans_both_standard_and_local()]] - code - tests/test_claude_md.py
- [[test_uninstall_no_op_when_no_file()]] - code - tests/test_claude_md.py
- [[test_uninstall_no_op_when_not_installed()]] - code - tests/test_claude_md.py
- [[test_uninstall_preserves_other_content()]] - code - tests/test_claude_md.py
- [[test_uninstall_preserves_other_content_in_local_md()]] - code - tests/test_claude_md.py
- [[test_uninstall_removes_hook_from_settings_local_json()]] - code - tests/test_claude_md.py
- [[test_uninstall_removes_section()]] - code - tests/test_claude_md.py
- [[test_uninstall_removes_section_from_dot_claude_local_md()]] - code - tests/test_claude_md.py
- [[test_uninstall_removes_section_from_root_claude_local_md()]] - code - tests/test_claude_md.py
- [[test_uninstall_removes_settings_hook()]] - code - tests/test_claude_md.py
- [[test_uninstall_tolerates_unreadable_local_md()]] - code - tests/test_claude_md.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/claude_install
SORT file.name ASC
```

## Connections to other communities
- 16 edges to [[_COMMUNITY_graphify__main__.py]]
- 1 edge to [[_COMMUNITY__replace_or_append_section]]
- 1 edge to [[_COMMUNITY__install_claude_hook]]
- 1 edge to [[_COMMUNITY_test_codebuddy.py]]
- 1 edge to [[_COMMUNITY_test_home_sandbox.py]]
- 1 edge to [[_COMMUNITY_test_uninstall_scope.py]]

## Top bridge nodes
- [[claude_uninstall()]] - degree 23, connects to 4 communities
- [[claude_install()]] - degree 25, connects to 3 communities
- [[test_claude_md.py]] - degree 20, connects to 1 community