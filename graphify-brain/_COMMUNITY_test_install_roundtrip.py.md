---
type: community
cohesion: 0.08
members: 29
---

# test_install_roundtrip.py

**Cohesion:** 0.08 - loosely connected
**Members:** 29 nodes

## Members
- [[A leftover references.tmp from a crashed install is cleared on the next install.]] - rationale - tests/test_install_roundtrip.py
- [[A pre-progressive install (SKILL.md, no references) gains references on upgrad]] - rationale - tests/test_install_roundtrip.py
- [[Drive the high-level install() entry point with home + cwd in tmp_path.]] - rationale - tests/test_install_roundtrip.py
- [[Full per-platform install + uninstall round-trip suite.  Every platform graphify]] - rationale - tests/test_install_roundtrip.py
- [[If a host loses its bundle, the next install clears the orphan references.]] - rationale - tests/test_install_roundtrip.py
- [[If copytree blows up mid-stage, no half-written references is left visible.]] - rationale - tests/test_install_roundtrip.py
- [[Install then uninstall every platform's SKILL.md at its real destination.      I]] - rationale - tests/test_install_roundtrip.py
- [[Run _copy_skill_file with home + cwd redirected into tmp_path, restoring cwd.]] - rationale - tests/test_install_roundtrip.py
- [[Stage a controllable references bundle in claude's slot.      Lets a test flip a]] - rationale - tests/test_install_roundtrip.py
- [[The public install() entry point round-trips a progressive and a monolith host.]] - rationale - tests/test_install_roundtrip.py
- [[True if this platform's references bundle ships in the package right now.]] - rationale - tests/test_install_roundtrip.py
- [[VS Code Copilot Chat round trip at ~.copilotskillsgraphify + instructions fil]] - rationale - tests/test_install_roundtrip.py
- [[_copy_in_tmp()]] - code - tests/test_install_roundtrip.py
- [[_has_real_bundle()]] - code - tests/test_install_roundtrip.py
- [[_install_via_entrypoint()]] - code - tests/test_install_roundtrip.py
- [[amp's project-scope skill lands under .agentsskills, an Amp search root.]] - rationale - tests/test_install_roundtrip.py
- [[amp's user-scope skill lands under ~.configagentsskills (the fix), not ~.amp]] - rationale - tests/test_install_roundtrip.py
- [[fake_progressive_bundle()]] - code - tests/test_install_roundtrip.py
- [[parametrize_12]] - code
- [[test_amp_project_install_at_agents_path()]] - code - tests/test_install_roundtrip.py
- [[test_amp_user_install_at_corrected_agents_path()]] - code - tests/test_install_roundtrip.py
- [[test_failed_copytree_leaves_no_partial_references()]] - code - tests/test_install_roundtrip.py
- [[test_install_entrypoint_roundtrip_for_progressive_and_monolith()]] - code - tests/test_install_roundtrip.py
- [[test_install_roundtrip.py]] - code - tests/test_install_roundtrip.py
- [[test_interrupted_references_staging_self_heals()]] - code - tests/test_install_roundtrip.py
- [[test_monolith_to_progressive_upgrade()]] - code - tests/test_install_roundtrip.py
- [[test_progressive_to_monolith_downgrade_clears_references()]] - code - tests/test_install_roundtrip.py
- [[test_skill_roundtrip_at_real_destination()]] - code - tests/test_install_roundtrip.py
- [[test_vscode_install_uninstall_roundtrip()]] - code - tests/test_install_roundtrip.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_install_roundtrippy
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_graphify__main__.py]]
- 1 edge to [[_COMMUNITY__fixture]]

## Top bridge nodes
- [[test_install_roundtrip.py]] - degree 15, connects to 1 community
- [[fake_progressive_bundle()]] - degree 3, connects to 1 community