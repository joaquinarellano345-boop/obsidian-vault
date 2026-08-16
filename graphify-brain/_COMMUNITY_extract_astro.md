---
type: community
cohesion: 0.28
members: 15
---

# extract_astro

**Cohesion:** 0.28 - loosely connected
**Members:** 15 nodes

## Members
- [[Astro permits frontmatter-less files (pure-HTML pages). Must not raise.]] - rationale - tests/test_astro_extraction.py
- [[Extract imports from .astro files frontmatter (TS) + template regex fallback.]] - rationale - graphify/extract.py
- [[Path_59]] - code
- [[Tests for `.astro` extraction (850).  Astro files have a TypeScript frontmatter]] - rationale - tests/test_astro_extraction.py
- [[Without this, detect.py silently drops `.astro` from the AST pass (850).]] - rationale - tests/test_astro_extraction.py
- [[_import_targets()]] - code - tests/test_astro_extraction.py
- [[_write()]] - code - tests/test_astro_extraction.py
- [[extract_astro()]] - code - graphify/extract.py
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
- 4 edges to [[_COMMUNITY_extract.py]]
- 2 edges to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY__make_id]]
- 1 edge to [[_COMMUNITY_engine.py]]

## Top bridge nodes
- [[extract_astro()]] - degree 14, connects to 4 communities
- [[test_astro_extraction.py]] - degree 12, connects to 2 communities