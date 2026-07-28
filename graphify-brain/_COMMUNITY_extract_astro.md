---
type: community
cohesion: 0.19
members: 19
---

# extract_astro

**Cohesion:** 0.19 - loosely connected
**Members:** 19 nodes

## Members
- [[Astro permits frontmatter-less files (pure-HTML pages). Must not raise.]] - rationale - tests/test_astro_extraction.py
- [[Extract imports from .astro files frontmatter (TS) + template regex fallback.]] - rationale - graphify/extract.py
- [[Extract imports from .svelte files script-block via JS AST + template regex fal]] - rationale - graphify/extract.py
- [[Path_59]] - code
- [[Shared edgestub emit for the SvelteAstroVue regex-rescue import passes.]] - rationale - graphify/extract.py
- [[Tests for `.astro` extraction (850).  Astro files have a TypeScript frontmatter]] - rationale - tests/test_astro_extraction.py
- [[Without this, detect.py silently drops `.astro` from the AST pass (850).]] - rationale - tests/test_astro_extraction.py
- [[_emit_rescued_import()]] - code - graphify/extract.py
- [[_import_targets()]] - code - tests/test_astro_extraction.py
- [[_write()]] - code - tests/test_astro_extraction.py
- [[extract_astro()]] - code - graphify/extract.py
- [[extract_svelte()]] - code - graphify/extract.py
- [[test_astro_extraction.py]] - code - tests/test_astro_extraction.py
- [[test_astro_is_in_code_extensions()]] - code - tests/test_astro_extraction.py
- [[test_extract_astro_handles_dynamic_import_in_frontmatter()]] - code - tests/test_astro_extraction.py
- [[test_extract_astro_handles_tsconfig_path_alias()]] - code - tests/test_astro_extraction.py
- [[test_extract_astro_no_frontmatter_does_not_crash()]] - code - tests/test_astro_extraction.py
- [[test_extract_astro_picks_up_client_side_script_imports()]] - code - tests/test_astro_extraction.py
- [[test_extract_astro_picks_up_frontmatter_static_imports()]] - code - tests/test_astro_extraction.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_astro
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_extract.py]]
- 3 edges to [[_COMMUNITY_Path]]
- 3 edges to [[_COMMUNITY__read_text]]
- 3 edges to [[_COMMUNITY_test_import_extension_resolution.py]]
- 2 edges to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY_test_vue_extraction.py]]

## Top bridge nodes
- [[extract_svelte()]] - degree 10, connects to 5 communities
- [[_emit_rescued_import()]] - degree 9, connects to 5 communities
- [[extract_astro()]] - degree 14, connects to 4 communities
- [[test_astro_extraction.py]] - degree 12, connects to 2 communities