---
type: community
cohesion: 0.10
members: 31
---

# install

**Cohesion:** 0.10 - loosely connected
**Members:** 31 nodes

## Members
- [[2166 end to end the emitted hooks must carry the real interpreter, not ''.]] - rationale - tests/test_hooks.py
- [[2166 git runs the merge driver through a shell, so a pinned path with a     sp]] - rationale - tests/test_hooks.py
- [[A pre-existing .gitattributes entry must survive install (no clobber).]] - rationale - tests/test_hooks.py
- [[End-to-end the files written to .githooks must be nohup-free (1161).]] - rationale - tests/test_hooks.py
- [[Hook scripts must embed sys.executable so the hook works without the     graphif]] - rationale - tests/test_hooks.py
- [[Install graphify post-commit and post-checkout hooks in the nearest git repo.]] - rationale - graphify/hooks.py
- [[No core.hooksPath - normal .githooks install, no rejection.]] - rationale - tests/test_hooks.py
- [[Running install twice must not duplicate the .gitattributes line.]] - rationale - tests/test_hooks.py
- [[_make_git_repo()]] - code - tests/test_hooks.py
- [[install()]] - code - graphify/hooks.py
- [[install() must set merge.graphify. via git config and add the     .gitattribute]] - rationale - tests/test_hooks.py
- [[test_default_hooks_dir_unaffected()]] - code - tests/test_hooks.py
- [[test_install_appends_to_existing_hook()]] - code - tests/test_hooks.py
- [[test_install_creates_hook()]] - code - tests/test_hooks.py
- [[test_install_creates_post_checkout_hook()]] - code - tests/test_hooks.py
- [[test_install_embeds_pinned_interpreter()]] - code - tests/test_hooks.py
- [[test_install_idempotent()]] - code - tests/test_hooks.py
- [[test_install_is_executable()]] - code - tests/test_hooks.py
- [[test_install_merge_driver_idempotent()]] - code - tests/test_hooks.py
- [[test_install_pins_interpreter_path_with_spaces()]] - code - tests/test_hooks.py
- [[test_install_post_checkout_is_executable()]] - code - tests/test_hooks.py
- [[test_install_preserves_existing_gitattributes()]] - code - tests/test_hooks.py
- [[test_install_registers_merge_driver()]] - code - tests/test_hooks.py
- [[test_installed_hooks_contain_no_nohup()]] - code - tests/test_hooks.py
- [[test_merge_driver_quotes_interpreter_with_spaces()]] - code - tests/test_hooks.py
- [[test_no_git_repo_raises()]] - code - tests/test_hooks.py
- [[test_uninstall_no_hook()]] - code - tests/test_hooks.py
- [[test_uninstall_removes_hook()]] - code - tests/test_hooks.py
- [[test_uninstall_removes_merge_driver_keeps_other_attrs()]] - code - tests/test_hooks.py
- [[test_uninstall_removes_post_checkout_hook()]] - code - tests/test_hooks.py
- [[uninstall() must unset merge.graphify. and remove only the graphify     .gitatt]] - rationale - tests/test_hooks.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/install
SORT file.name ASC
```

## Connections to other communities
- 21 edges to [[_COMMUNITY_test_hooks.py]]
- 16 edges to [[_COMMUNITY_hooks.py]]
- 6 edges to [[_COMMUNITY_test_hooks_dir_duplicate_config_keys_honor_custom_hookspath]]
- 5 edges to [[_COMMUNITY__hooks_dir]]
- 2 edges to [[_COMMUNITY_cli.py]]

## Top bridge nodes
- [[install()]] - degree 34, connects to 5 communities
- [[_make_git_repo()]] - degree 30, connects to 4 communities
- [[test_uninstall_removes_merge_driver_keeps_other_attrs()]] - degree 5, connects to 2 communities
- [[test_uninstall_removes_hook()]] - degree 4, connects to 2 communities
- [[test_uninstall_removes_post_checkout_hook()]] - degree 4, connects to 2 communities