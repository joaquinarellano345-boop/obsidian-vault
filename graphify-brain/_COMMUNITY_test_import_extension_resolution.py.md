---
type: community
cohesion: 0.05
members: 76
---

# test_import_extension_resolution.py

**Cohesion:** 0.05 - loosely connected
**Members:** 76 nodes

## Members
- [[A directory with no index file should fall through to the     return as-is p]] - rationale - tests/test_import_extension_resolution.py
- [[Alias → bare path → .svelte.ts. Two layers of resolution must     compose correc]] - rationale - tests/test_import_extension_resolution.py
- [[Ambient TS declaration files (foo.d.ts) — bare import `.foo.d`     should resol]] - rationale - tests/test_import_extension_resolution.py
- [[Bare module specifiers (no leading dot, no alias match) must still     fall thro]] - rationale - tests/test_import_extension_resolution.py
- [[Common patterns foo.shared.ts, foo.config.ts, foo.compile.ts,     foo.integrati]] - rationale - tests/test_import_extension_resolution.py
- [[Edge case `.eslintrc` and similar dotfiles. Path('.eslintrc').suffix     return]] - rationale - tests/test_import_extension_resolution.py
- [[End-to-end sanity for the multi-dot pattern via the import handler.]] - rationale - tests/test_import_extension_resolution.py
- [[External  truly missing paths fall back to the input — preserves     pre-716 b]] - rationale - tests/test_import_extension_resolution.py
- [[If `.js` exists and `.ts` does not, keep the `.js` rewrite from     triggering —]] - rationale - tests/test_import_extension_resolution.py
- [[If `foo.svelte` IS a real markup file, importing `.foo.svelte`     must resolve]] - rationale - tests/test_import_extension_resolution.py
- [[JS variant of the rune file pattern a `.svelte.js` file (used in     JavaScript]] - rationale - tests/test_import_extension_resolution.py
- [[Path_74]] - code
- [[Real .svelte file imports must still resolve when the .svelte file     exists (i]] - rationale - tests/test_import_extension_resolution.py
- [[Real-world repro a TS file uses `await import('.foo')` (no extension)     to l]] - rationale - tests/test_import_extension_resolution.py
- [[Real-world repro a project has both `auth.ts` (file) and `auth`     (directory]] - rationale - tests/test_import_extension_resolution.py
- [[Regression guard `from '.foo'` where '.foo' doesn't exist but     '.foo-extr]] - rationale - tests/test_import_extension_resolution.py
- [[Resolve a JSTS module path or specifier to a local source file.      With a Pat]] - rationale - graphify/extractors/resolution.py
- [[Sanity `from '.foo.shared.ts'` (explicit) still wins over implicit.]] - rationale - tests/test_import_extension_resolution.py
- [[Svelte 5 rune file import written as .svelte, real file is .svelte.ts.]] - rationale - tests/test_import_extension_resolution.py
- [[Svelte 5 `from '.foo.svelte'` may actually point at `foo.svelte.ts`     (a run]] - rationale - tests/test_import_extension_resolution.py
- [[TS ESM convention imports written as .js but the actual file is .ts.]] - rationale - tests/test_import_extension_resolution.py
- [[Tests for 716 — TypeScript bare-path imports, Svelte 5 rune file imports (`from]] - rationale - tests/test_import_extension_resolution.py
- [[The 716 reproducer TS file imports a sibling without an extension.]] - rationale - tests/test_import_extension_resolution.py
- [[The most common case — import with explicit .ts extension — must     continue to]] - rationale - tests/test_import_extension_resolution.py
- [[The other branch of the dynamic-import handler — alias resolution —     also nee]] - rationale - tests/test_import_extension_resolution.py
- [[The regex pass for `import('...')` in .svelte files must also use     the new re]] - rationale - tests/test_import_extension_resolution.py
- [[Vite resolver order .ts wins over .svelte for ambiguous bare paths.]] - rationale - tests/test_import_extension_resolution.py
- [[When both `.svelte.ts` and `.svelte.js` exist (hybrid project mid-     migration]] - rationale - tests/test_import_extension_resolution.py
- [[_import_targets()_1]] - code - tests/test_import_extension_resolution.py
- [[_resolve_js_module_path()]] - code - graphify/extractors/resolution.py
- [[_write()_7]] - code - tests/test_import_extension_resolution.py
- [[`$libfoo` (alias + bare path) — both layers must work together.]] - rationale - tests/test_import_extension_resolution.py
- [[`.foosub` where .foosubindex.ts exists — nested subpath.     Common pattern]] - rationale - tests/test_import_extension_resolution.py
- [[`from '$libqueue'` where queue is a directory under srclib.]] - rationale - tests/test_import_extension_resolution.py
- [[`from '.queue'` must resolve to `.queueindex.ts`.]] - rationale - tests/test_import_extension_resolution.py
- [[`import type { X } from '.foo'` — type-only imports must go through     the sam]] - rationale - tests/test_import_extension_resolution.py
- [[`import { foo, bar } from '.module'` should emit per-symbol `imports`     edges]] - rationale - tests/test_import_extension_resolution.py
- [[test_alias_directory_import_resolves_to_index_ts()]] - code - tests/test_import_extension_resolution.py
- [[test_alias_import_with_bare_path_resolves()]] - code - tests/test_import_extension_resolution.py
- [[test_bare_path_import_resolves_in_ts_file()]] - code - tests/test_import_extension_resolution.py
- [[test_directory_import_resolves_to_index_ts()]] - code - tests/test_import_extension_resolution.py
- [[test_dot_svelte_import_resolves_to_dot_svelte_ts()]] - code - tests/test_import_extension_resolution.py
- [[test_dynamic_import_bare_path_resolves()]] - code - tests/test_import_extension_resolution.py
- [[test_end_to_end_multi_dot_import_resolves()]] - code - tests/test_import_extension_resolution.py
- [[test_explicit_svelte_import_still_works()]] - code - tests/test_import_extension_resolution.py
- [[test_explicit_ts_import_still_works()]] - code - tests/test_import_extension_resolution.py
- [[test_external_module_unchanged()]] - code - tests/test_import_extension_resolution.py
- [[test_import_extension_resolution.py]] - code - tests/test_import_extension_resolution.py
- [[test_named_imports_emit_symbol_edges_after_resolution()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_ambient_d_ts_via_bare_path()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_bare_path_to_svelte()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_bare_path_to_ts()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_bare_path_to_tsx()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_chain_alias_and_extension_compose()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_directory_prefers_index_ts_over_index_js()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_directory_to_index_ts()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_directory_without_index_returns_unchanged()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_does_not_match_partial_directory_name()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_does_not_treat_dotfile_as_extension()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_file_wins_over_sibling_directory()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_handles_subpath_into_directory_with_index()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_js_to_ts_when_real_file_is_ts()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_jsx_to_tsx_when_real_file_is_tsx()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_multi_dot_helper_file()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_multi_dot_with_explicit_extension_still_works()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_prefers_ts_over_svelte_when_both_exist()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_real_js_stays_js_when_ts_does_not_exist()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_real_svelte_file_wins_over_svelte_ts_sibling()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_returns_existing_path_unchanged()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_returns_unchanged_when_nothing_matches()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_svelte_prefers_svelte_ts_over_svelte_js()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_svelte_to_svelte_js_for_javascript_rune_files()]] - code - tests/test_import_extension_resolution.py
- [[test_resolve_svelte_to_svelte_ts_for_rune_files()]] - code - tests/test_import_extension_resolution.py
- [[test_ts_dynamic_import_alias_with_bare_path_resolves()]] - code - tests/test_import_extension_resolution.py
- [[test_ts_dynamic_import_bare_path_resolves()]] - code - tests/test_import_extension_resolution.py
- [[test_type_only_import_with_bare_path_resolves()]] - code - tests/test_import_extension_resolution.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_import_extension_resolutionpy
SORT file.name ASC
```

## Connections to other communities
- 15 edges to [[_COMMUNITY_extract_js]]
- 10 edges to [[_COMMUNITY_extract.py]]
- 3 edges to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY__resolve_js_import_target]]

## Top bridge nodes
- [[test_import_extension_resolution.py]] - degree 44, connects to 3 communities
- [[_resolve_js_module_path()]] - degree 35, connects to 3 communities
- [[test_alias_directory_import_resolves_to_index_ts()]] - degree 5, connects to 1 community
- [[test_alias_import_with_bare_path_resolves()]] - degree 5, connects to 1 community
- [[test_bare_path_import_resolves_in_ts_file()]] - degree 5, connects to 1 community