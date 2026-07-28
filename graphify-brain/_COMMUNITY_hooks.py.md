---
type: community
cohesion: 0.11
members: 30
---

# hooks.py

**Cohesion:** 0.11 - loosely connected
**Members:** 30 nodes

## Members
- [[NOTE do NOT pass --path-format=absolute — added in git 2.31; older git]] - rationale - graphify/hooks.py
- [[Check if graphify hooks are installed.]] - rationale - graphify/hooks.py
- [[Install a single git hook, appending if an existing hook is present.]] - rationale - graphify/hooks.py
- [[Path_40]] - code
- [[Register the graph.json union merge driver in git config + .gitattributes (1902]] - rationale - graphify/hooks.py
- [[Remove graphify post-commit and post-checkout hooks.]] - rationale - graphify/hooks.py
- [[Remove graphify section from a git hook using startend markers.]] - rationale - graphify/hooks.py
- [[Remove the merge-driver git config keys and the .gitattributes line.]] - rationale - graphify/hooks.py
- [[Report whether the merge driver is registered (config + gitattributes).]] - rationale - graphify/hooks.py
- [[Return sys.executable if its path is shell-safe, else an empty string.      Appl]] - rationale - graphify/hooks.py
- [[Return the user-editable hooks directory.      Husky 9 sets core.hooksPath to .h]] - rationale - graphify/hooks.py
- [[The .gitattributes line assigning the graphify merge driver to graph.json.]] - rationale - graphify/hooks.py
- [[True if a (non-comment) `...graph.json ... merge=graphify` line exists.]] - rationale - graphify/hooks.py
- [[Walk up to find .git directory.]] - rationale - graphify/hooks.py
- [[_git_root()]] - code - graphify/hooks.py
- [[_has_merge_attr()]] - code - graphify/hooks.py
- [[_install_hook()]] - code - graphify/hooks.py
- [[_merge_attr_line()]] - code - graphify/hooks.py
- [[_merge_driver_status()]] - code - graphify/hooks.py
- [[_pinned_python()]] - code - graphify/hooks.py
- [[_register_merge_driver()]] - code - graphify/hooks.py
- [[_uninstall_hook()]] - code - graphify/hooks.py
- [[_unregister_merge_driver()]] - code - graphify/hooks.py
- [[_user_hooks_dir()]] - code - graphify/hooks.py
- [[hooks.py]] - code - graphify/hooks.py
- [[status()]] - code - graphify/hooks.py
- [[test_status_installed()]] - code - tests/test_hooks.py
- [[test_status_not_installed()]] - code - tests/test_hooks.py
- [[test_status_shows_both_hooks()]] - code - tests/test_hooks.py
- [[uninstall()]] - code - graphify/hooks.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/hookspy
SORT file.name ASC
```

## Connections to other communities
- 16 edges to [[_COMMUNITY_install]]
- 8 edges to [[_COMMUNITY_test_hooks.py]]
- 5 edges to [[_COMMUNITY__hooks_dir]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_parametrize]]
- 2 edges to [[_COMMUNITY_graphify__main__.py]]
- 1 edge to [[_COMMUNITY_multigraph_compat.py]]

## Top bridge nodes
- [[uninstall()]] - degree 17, connects to 5 communities
- [[status()]] - degree 14, connects to 4 communities
- [[hooks.py]] - degree 18, connects to 3 communities
- [[_pinned_python()]] - degree 7, connects to 3 communities
- [[Path_40]] - degree 12, connects to 2 communities