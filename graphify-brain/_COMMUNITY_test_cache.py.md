---
type: community
cohesion: 0.04
members: 96
---

# test_cache.py

**Cohesion:** 0.04 - loosely connected
**Members:** 96 nodes

## Members
- [[1656 — word counts are cached against each file's stat signature so detect() do]] - rationale - tests/test_word_count_cache.py
- [[1894 follow-up to 1527 prune must sweep cachesemantic AND     cachesemanti]] - rationale - tests/test_cache.py
- [[1916 guard-rail unscoped callers (allowed_source_files=None) must stay     byt]] - rationale - tests/test_cache.py
- [[1989 the stat-index memo must be keyed by the salt (path relative to     root)]] - rationale - tests/test_word_count_cache.py
- [[A .md file with no frontmatter is hashed by its full content.]] - rationale - tests/test_cache.py
- [[A CRLF checkout of the same spec must not look like a prompt change —     otherw]] - rationale - tests/test_cache.py
- [[A glob that stopped at the top level would leave every fingerprinted     entry u]] - rationale - tests/test_cache.py
- [[A pre-1989 entry carrying a bare hash (no salt) is never trusted.]] - rationale - tests/test_word_count_cache.py
- [[After file content changes, load_cached returns None.]] - rationale - tests/test_cache.py
- [[An entry for a file that no longer exists (dropped from the live set) is     pru]] - rationale - tests/test_cache.py
- [[Cache entries written by an older graphify (with absolute source_file     inside]] - rationale - tests/test_cache.py
- [[Changing a file's content leaves the old content-hash entry orphaned;     prunin]] - rationale - tests/test_cache.py
- [[Changing only frontmatter fields in a .md file does not change the hash.]] - rationale - tests/test_cache.py
- [[Changing the body of a .md file produces a different hash.]] - rationale - tests/test_cache.py
- [[Different file contents give different hashes.]] - rationale - tests/test_cache.py
- [[Editing content above a mid-document ``----`` break must change the     hash --]] - rationale - tests/test_cache.py
- [[Fingerprint the caller's extraction prompt, or None when it supplied none.]] - rationale - graphify/cache.py
- [[Fingerprinted entries live under cachesemanticp{fp}, never flat.]] - rationale - tests/test_cache.py
- [[Inverse of func`_relativize_source_files_in`.      Re-anchor relative ``source]] - rationale - graphify/cache.py
- [[Inverse of func`_stat_key_to_relative`.      Re-anchor a stored relative key a]] - rationale - graphify/cache.py
- [[Mutate ``payload`` to rewrite absolute ``source_file`` fields as     forward-sla]] - rationale - graphify/cache.py
- [[Non-.md files are still hashed by their full content.]] - rationale - tests/test_cache.py
- [[Normalize path for consistent cache keys across Windows path spellings.]] - rationale - graphify/cache.py
- [[Path_3]] - code
- [[Prune touches only cachesemantic.json AST entries and atomic-write     .tmp]] - rationale - tests/test_cache.py
- [[Pruning against the FULL live set must keep every live entry — guards     the tr]] - rationale - tests/test_cache.py
- [[Remove AST cache entries left behind by other graphify versions.      Sweeps sib]] - rationale - graphify/cache.py
- [[Remove orphaned semantic cache entries, returning the count pruned.      The sem]] - rationale - graphify/cache.py
- [[Return ``key`` as a forward-slash relative path from ``anchor``.      Local dupl]] - rationale - graphify/cache.py
- [[Return ``src`` in portable form backslashes flipped to forward slashes,     the]] - rationale - graphify/cache.py
- [[Return a short stable fingerprint of an extraction prompt.      ``prompt`` is ei]] - rationale - graphify/cache.py
- [[Return set of file hashes that have a valid cache entry (any kind).]] - rationale - graphify/cache.py
- [[Returns the cache directory for ``kind`` - creates it if needed.      kind is a]] - rationale - graphify/cache.py
- [[SHA256 of file contents + path relative to root.      Uses a stat-based fastpath]] - rationale - graphify/cache.py
- [[Same file gives same hash on repeated calls.]] - rationale - tests/test_cache.py
- [[Save extraction result for this file.      Stores as graphify-outcache{kind}{]] - rationale - graphify/cache.py
- [[Tests for graphifycache.py.]] - rationale - tests/test_cache.py
- [[The fingerprint is stable for identical prompts and differs when the     prompt]] - rationale - tests/test_cache.py
- [[The on-disk cache JSON contains forward-slash relative source_file     entries —]] - rationale - tests/test_cache.py
- [[The semantic cache is deliberately not versioned entries are produced     by th]] - rationale - tests/test_cache.py
- [[Upgrading removes AST entries left behind by previous versions so the     cache]] - rationale - tests/test_cache.py
- [[Word count with the same (size, mtime_ns) stat-fastpath cache as     func`file]] - rationale - graphify/cache.py
- [[_absolutize_source_files_in()]] - code - graphify/cache.py
- [[_cleanup_stale_ast_entries()]] - code - graphify/cache.py
- [[_ensure_stat_index()]] - code - graphify/cache.py
- [[_normalize_path()]] - code - graphify/cache.py
- [[_normalize_source_file_value()]] - code - graphify/cache.py
- [[_relativize_source_files_in()]] - code - graphify/cache.py
- [[_resolve_prompt_fp()]] - code - graphify/cache.py
- [[_stat_index_file()]] - code - graphify/cache.py
- [[_stat_key_to_absolute()]] - code - graphify/cache.py
- [[_stat_key_to_relative()]] - code - graphify/cache.py
- [[``load_cached`` returns the same absolute-path shape that a fresh     extraction]] - rationale - tests/test_cache.py
- [[``source_file`` for an in-root symlink must be stored under the     symlink's ow]] - rationale - tests/test_cache.py
- [[cache.py]] - code - graphify/cache.py
- [[cache_dir()]] - code - graphify/cache.py
- [[cached_files reports deep-namespace entries too.]] - rationale - tests/test_cache.py
- [[cached_files returns the set of cached hashes.]] - rationale - tests/test_cache.py
- [[cached_files()]] - code - graphify/cache.py
- [[cached_word_count()]] - code - graphify/cache.py
- [[file_hash()]] - code - graphify/cache.py
- [[prompt_fingerprint()]] - code - graphify/cache.py
- [[prune_semantic_cache()]] - code - graphify/cache.py
- [[save_cached()]] - code - graphify/cache.py
- [[test_ast_cache_version_bump_cleans_stale_entries()]] - code - tests/test_cache.py
- [[test_cache.py]] - code - tests/test_cache.py
- [[test_cache_miss_on_change()]] - code - tests/test_cache.py
- [[test_cached_files()]] - code - tests/test_cache.py
- [[test_cached_files_includes_deep_namespace()]] - code - tests/test_cache.py
- [[test_file_hash_changes()]] - code - tests/test_cache.py
- [[test_file_hash_consistent()]] - code - tests/test_cache.py
- [[test_file_hash_ignores_legacy_unsalted_entry()]] - code - tests/test_word_count_cache.py
- [[test_file_hash_is_order_independent_across_roots()]] - code - tests/test_word_count_cache.py
- [[test_load_cached_absolutizes_source_file()]] - code - tests/test_cache.py
- [[test_load_cached_passes_through_legacy_absolute_source_file()]] - code - tests/test_cache.py
- [[test_md_body_change_different_hash()]] - code - tests/test_cache.py
- [[test_md_edit_above_hr_changes_hash()]] - code - tests/test_cache.py
- [[test_md_frontmatter_only_change_same_hash()]] - code - tests/test_cache.py
- [[test_md_no_frontmatter_hashed_normally()]] - code - tests/test_cache.py
- [[test_non_md_file_hashed_fully()]] - code - tests/test_cache.py
- [[test_prompt_fingerprint_ignores_line_endings()]] - code - tests/test_cache.py
- [[test_prompt_fingerprint_stable_and_prompt_sensitive()]] - code - tests/test_cache.py
- [[test_save_cached_in_root_symlink_keeps_symlink_name()]] - code - tests/test_cache.py
- [[test_save_cached_relativizes_source_file()]] - code - tests/test_cache.py
- [[test_save_semantic_cache_unscoped_preserves_dangling_refs_verbatim()]] - code - tests/test_cache.py
- [[test_semantic_cache_prompt_namespaced_layout()]] - code - tests/test_cache.py
- [[test_semantic_cache_survives_version_bump()]] - code - tests/test_cache.py
- [[test_semantic_prune_and_clear_reach_fingerprint_subdirs()]] - code - tests/test_cache.py
- [[test_semantic_prune_handles_deleted_file()]] - code - tests/test_cache.py
- [[test_semantic_prune_ignores_ast_and_tmp()]] - code - tests/test_cache.py
- [[test_semantic_prune_keeps_live_unchanged_entries()]] - code - tests/test_cache.py
- [[test_semantic_prune_removes_orphan_entries()]] - code - tests/test_cache.py
- [[test_semantic_prune_sweeps_both_namespaces_against_same_live_set()]] - code - tests/test_cache.py
- [[test_word_count_augments_existing_hash_entry()]] - code - tests/test_word_count_cache.py
- [[test_word_count_cache.py]] - code - tests/test_word_count_cache.py
- [[test_word_count_cached_until_file_changes()]] - code - tests/test_word_count_cache.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_cachepy
SORT file.name ASC
```

## Connections to other communities
- 35 edges to [[_COMMUNITY_save_semantic_cache]]
- 17 edges to [[_COMMUNITY_check_semantic_cache]]
- 11 edges to [[_COMMUNITY_test_stat_index_portability.py]]
- 10 edges to [[_COMMUNITY__body_content]]
- 8 edges to [[_COMMUNITY_clear_cache]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 3 edges to [[_COMMUNITY_test_extract_cache_location.py]]
- 2 edges to [[_COMMUNITY_detect.py]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 2 edges to [[_COMMUNITY_test_semantic_cache_out_root.py]]
- 2 edges to [[_COMMUNITY_Path]]
- 2 edges to [[_COMMUNITY__fixture]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_test_detect.py]]

## Top bridge nodes
- [[cache.py]] - degree 34, connects to 10 communities
- [[file_hash()]] - degree 43, connects to 7 communities
- [[save_cached()]] - degree 29, connects to 6 communities
- [[test_cache.py]] - degree 71, connects to 5 communities
- [[Path_3]] - degree 20, connects to 3 communities