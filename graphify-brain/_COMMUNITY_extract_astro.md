---
type: community
cohesion: 0.11
members: 31
---

# extract_astro

**Cohesion:** 0.11 - loosely connected
**Members:** 31 nodes

## Members
- [[Astro permits frontmatter-less files (pure-HTML pages). Must not raise.]] - rationale - tests/test_astro_extraction.py
- [[Extract imports from .astro files frontmatter (TS) + template regex fallback.]] - rationale - graphify/extract.py
- [[Extract imports from .svelte files script-block via JS AST + template regex fal]] - rationale - graphify/extract.py
- [[Nearest tsconfig.jsonjsconfig.json walking up from start_dir.      `jsconfig.js]] - rationale - graphify/extractors/resolution.py
- [[Parse a tsconfigjsconfig as JSON, falling back to JSONC (2153).      Mirrors t]] - rationale - graphify/extractors/resolution.py
- [[Path_59]] - code
- [[Recursively read path aliases from a tsconfig, following extends chains.      Ch]] - rationale - graphify/extractors/resolution.py
- [[Shared edgestub emit for the SvelteAstroVue regex-rescue import passes.]] - rationale - graphify/extract.py
- [[Strip  line comments,   block comments, and trailing commas from JSONC.]] - rationale - graphify/extractors/resolution.py
- [[Tests for `.astro` extraction (850).  Astro files have a TypeScript frontmatter]] - rationale - tests/test_astro_extraction.py
- [[Walk up from start_dir to find tsconfigjsconfig.json and return compilerOptions]] - rationale - graphify/extractors/resolution.py
- [[Without this, detect.py silently drops `.astro` from the AST pass (850).]] - rationale - tests/test_astro_extraction.py
- [[_emit_rescued_import()]] - code - graphify/extract.py
- [[_find_js_config()]] - code - graphify/extractors/resolution.py
- [[_import_targets()]] - code - tests/test_astro_extraction.py
- [[_load_tsconfig_aliases()]] - code - graphify/extractors/resolution.py
- [[_load_tsconfig_base_url()]] - code - graphify/extractors/resolution.py
- [[_read_json_config()]] - code - graphify/extractors/resolution.py
- [[_read_tsconfig_aliases()]] - code - graphify/extractors/resolution.py
- [[_strip_jsonc()]] - code - graphify/extractors/resolution.py
- [[_write()]] - code - tests/test_astro_extraction.py
- [[`compilerOptions.baseUrl` of the nearest config, as an absolute directory.]] - rationale - graphify/extractors/resolution.py
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
- 20 edges to [[_COMMUNITY_extract.py]]
- 5 edges to [[_COMMUNITY_test_import_extension_resolution.py]]
- 3 edges to [[_COMMUNITY_Path]]
- 3 edges to [[_COMMUNITY__make_id]]
- 3 edges to [[_COMMUNITY_test_vue_extraction.py]]
- 2 edges to [[_COMMUNITY__extract_generic]]
- 1 edge to [[_COMMUNITY_detect.py]]

## Top bridge nodes
- [[extract_svelte()]] - degree 10, connects to 5 communities
- [[_emit_rescued_import()]] - degree 9, connects to 5 communities
- [[extract_astro()]] - degree 14, connects to 4 communities
- [[_load_tsconfig_aliases()]] - degree 10, connects to 3 communities
- [[_load_tsconfig_base_url()]] - degree 10, connects to 3 communities