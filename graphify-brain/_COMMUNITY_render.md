---
type: community
cohesion: 0.09
members: 30
---

# render

**Cohesion:** 0.09 - loosely connected
**Members:** 30 nodes

## Members
- [[1757 generated monoliths pass the dispatched-file allowlist when     replacing]] - rationale - tests/test_skillgen.py
- [[.hooks_target()]] - code - tools/skillgen/gen.py
- [[.reference_sources()]] - code - tools/skillgen/gen.py
- [[Every platform now carries one unified frontmatter description, byte for byte.]] - rationale - tests/test_skillgen.py
- [[Fill the agents-md hooks template's per-host slots for this platform.      The f]] - rationale - tools/skillgen/gen.py
- [[Fill the shared core template's per-platform slots for this platform.]] - rationale - tools/skillgen/gen.py
- [[Force LF newlines and exactly one trailing newline.]] - rationale - tools/skillgen/gen.py
- [[One render unit parsed from platforms.toml.]] - rationale - tools/skillgen/gen.py
- [[Platform]] - code - tools/skillgen/gen.py
- [[Read a fragment file under fragments, normalised to LF newlines.]] - rationale - tools/skillgen/gen.py
- [[Render every committed artifact for one platform.      A split platform yields t]] - rationale - tools/skillgen/gen.py
- [[Render the YAML frontmatter from the platform's name and description.      Only]] - rationale - tools/skillgen/gen.py
- [[Resolve the rendered-name - source-fragment map for this split platform.]] - rationale - tools/skillgen/gen.py
- [[The agents skill body is amp's body verbatim (it re-homes amp's bundle).      Th]] - rationale - tests/test_skillgen.py
- [[The four 1392 data-losscorrectness fixes are present in both monoliths.      T]] - rationale - tests/test_skillgen.py
- [[The prose file name the lean-core hooks pointer names for this host.]] - rationale - tools/skillgen/gen.py
- [[_normalise()]] - code - tools/skillgen/gen.py
- [[_read_fragment()]] - code - tools/skillgen/gen.py
- [[_render_agents_md_hooks()]] - code - tools/skillgen/gen.py
- [[_render_core()]] - code - tools/skillgen/gen.py
- [[_render_frontmatter()]] - code - tools/skillgen/gen.py
- [[aider and devin render one inline body, no split and no references dir.]] - rationale - tests/test_skillgen.py
- [[devin renders inline, so its 4+-field frontmatter is preserved verbatim.]] - rationale - tests/test_skillgen.py
- [[render()]] - code - tools/skillgen/gen.py
- [[test_agents_body_matches_amp_modulo_hooks_wording()]] - code - tests/test_skillgen.py
- [[test_descriptions_are_unified()]] - code - tests/test_skillgen.py
- [[test_devin_keeps_its_multi_field_frontmatter()]] - code - tests/test_skillgen.py
- [[test_monoliths_carry_the_1392_runbook_fixes()]] - code - tests/test_skillgen.py
- [[test_monoliths_render_inline_single_file_no_references()]] - code - tests/test_skillgen.py
- [[test_monoliths_scope_semantic_cache_writes_to_uncached_files()]] - code - tests/test_skillgen.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/render
SORT file.name ASC
```

## Connections to other communities
- 10 edges to [[_COMMUNITY_load_platforms]]
- 7 edges to [[_COMMUNITY_gen.py]]
- 6 edges to [[_COMMUNITY_test_skillgen.py]]
- 4 edges to [[_COMMUNITY_monolith_roundtrip]]
- 4 edges to [[_COMMUNITY_audit_coverage]]
- 2 edges to [[_COMMUNITY_schema_singleton]]
- 1 edge to [[_COMMUNITY_render_always_on]]

## Top bridge nodes
- [[render()]] - degree 20, connects to 5 communities
- [[Platform]] - degree 13, connects to 5 communities
- [[_read_fragment()]] - degree 7, connects to 2 communities
- [[_normalise()]] - degree 6, connects to 2 communities
- [[test_agents_body_matches_amp_modulo_hooks_wording()]] - degree 4, connects to 2 communities