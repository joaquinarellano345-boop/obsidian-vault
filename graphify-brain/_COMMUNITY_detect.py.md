---
type: community
cohesion: 0.03
members: 107
---

# detect.py

**Cohesion:** 0.03 - loosely connected
**Members:** 107 nodes

## Members
- [[NOTE aws_credentialsgcloud_credentialsservice_account moved to the]] - rationale - graphify/detect.py
- [[1948 a file stamped in an earlier run, then omitted from ``files`` on     a la]] - rationale - tests/test_detect.py
- [[2221 (portablerelative-key manifest) a manifest whose keys were     written i]] - rationale - tests/test_detect.py
- [[2221 exact repro legacy manifest saved WITHOUT root (absolute keys),     then]] - rationale - tests/test_detect.py
- [[A previously-indexed file that becomes excluded (still on disk) must     land in]] - rationale - tests/test_detect.py
- [[A prosenote file (.md.rst...) whose stem is a multi-word topic slug is     ex]] - rationale - graphify/detect.py
- [[A row for a file that still exists on disk but left the scan corpus     (newly e]] - rationale - tests/test_detect.py
- [[A schema-drifted manifest whose entry stores mtime as a nested dict     (instead]] - rationale - tests/test_detect.py
- [[After a full-scan save prunes the excluded row, later incremental runs     repor]] - rationale - tests/test_detect.py
- [[Back-compat callers that don't pass ``root`` still get the legacy     absolute-]] - rationale - tests/test_detect.py
- [[Code files must be stamped in the manifest regardless of semantic cache.]] - rationale - tests/test_detect.py
- [[Convert a .docx file to markdown text using python-docx.]] - rationale - graphify/detect.py
- [[Convert an .xlsx file to markdown text using openpyxl.]] - rationale - graphify/detect.py
- [[Counterpart a manifest row whose file is gone from disk stays in     deleted_fi]] - rationale - tests/test_detect.py
- [[End-to-end a manifest written at one root must be readable from a     different]] - rationale - tests/test_detect.py
- [[Extract plain text from a PDF file using pypdf.]] - rationale - graphify/detect.py
- [[Extract structural nodes (sheets, named tables, column headers) from an .xlsx fi]] - rationale - graphify/detect.py
- [[Files in failed chunks have no semantic cache entry; save_manifest must     leav]] - rationale - tests/test_detect.py
- [[Files outside ``root`` (e.g. symlinked external corpora) are stored     absolute]] - rationale - tests/test_detect.py
- [[Genuine deletions keep being pruned when scan_corpus is passed.]] - rationale - tests/test_detect.py
- [[Heuristic does this text file read like an academic paper]] - rationale - graphify/detect.py
- [[In-root symlinks must store under the symlink's own name, not the     resolved t]] - rationale - tests/test_detect.py
- [[Inverse of func`_to_relative_for_storage`.      Re-anchor a stored key against]] - rationale - graphify/detect.py
- [[Legacy absolute-keyed manifests still load correctly when ``root``     is suppli]] - rationale - tests/test_detect.py
- [[Legacy float manifests must re-extract when mtime moves BACKWARDS (1859).]] - rationale - tests/test_detect.py
- [[Like detect(), but returns only new or modified files since the last run.      k]] - rationale - graphify/detect.py
- [[Load the manifest from a previous run. Returns {} on any error.      When ``root]] - rationale - graphify/detect.py
- [[MD5 of file contents streamed in 64KB chunks — for change detection only.]] - rationale - graphify/detect.py
- [[Match an anchored gitignore pattern without letting ```` cross ````.]] - rationale - graphify/detect.py
- [[NFC-normalize a path string used as a manifest key.      On macOS, ``os.walk``]] - rationale - graphify/detect.py
- [[Non-regression for the fix above legacy float branch still skips when     the s]] - rationale - tests/test_detect.py
- [[Out-of-root entries (--include sources, symlinked corpora) are never     walked]] - rationale - tests/test_detect.py
- [[Parse one raw line from a .graphifyignore file per gitignore spec.      - Strip]] - rationale - graphify/detect.py
- [[Path_7]] - code
- [[Read .gitignore.graphifyignore directly inside d (not its ancestors).      Me]] - rationale - graphify/detect.py
- [[Resolve ``$GIT_DIRinfoexclude`` for the repo rooted at ``vcs_root``.      ``in]] - rationale - graphify/detect.py
- [[Return ``key`` as a forward-slash relative path from ``root``.      Keys outside]] - rationale - graphify/detect.py
- [[Return whether ``root`` has any direct symlinked child.      Kept for callers th]] - rationale - graphify/detect.py
- [[Rewrite a saved manifest so every key is in NFD form, simulating a     manifest]] - rationale - tests/test_detect.py
- [[Save current file mtimes + content hashes for change detection.      kind=ast]] - rationale - graphify/detect.py
- [[Stat + MD5 a single file; returns None on OSError (e.g. deleted mid-run).]] - rationale - graphify/detect.py
- [[True for genuine programming-language source — the only category exempt     from]] - rationale - graphify/detect.py
- [[True if a generic secret keyword appears load-bearing in the filename.      Secr]] - rationale - graphify/detect.py
- [[True when ``path`` resolves to a target inside ``root``.]] - rationale - graphify/detect.py
- [[Walk upward from start; return the first directory containing a VCS marker.]] - rationale - graphify/detect.py
- [[Without scan_corpus (changed_paths hooks, skill runbooks, 917) a     subset sav]] - rationale - tests/test_detect.py
- [[_auto_follow_symlinks()]] - code - graphify/detect.py
- [[_find_vcs_root()]] - code - graphify/detect.py
- [[_generic_keyword_hit()]] - code - graphify/detect.py
- [[_git_info_exclude()]] - code - graphify/detect.py
- [[_is_graphable_source()]] - code - graphify/detect.py
- [[_is_prose_note()]] - code - graphify/detect.py
- [[_load_dir_own_ignore()]] - code - graphify/detect.py
- [[_looks_like_paper()]] - code - graphify/detect.py
- [[_match_anchored_ignore_pattern()]] - code - graphify/detect.py
- [[_md5_file()]] - code - graphify/detect.py
- [[_nfc()]] - code - graphify/detect.py
- [[_os_path()]] - code - graphify/detect.py
- [[_parse_gitignore_line()]] - code - graphify/detect.py
- [[_resolves_under_root()]] - code - graphify/detect.py
- [[_rewrite_manifest_keys_nfd()]] - code - tests/test_detect.py
- [[_stat_and_hash()]] - code - graphify/detect.py
- [[_to_absolute_from_storage()]] - code - graphify/detect.py
- [[_to_relative_for_storage()]] - code - graphify/detect.py
- [[``load_manifest(root=...)`` re-anchors stored relative keys so the     in-memory]] - rationale - tests/test_detect.py
- [[``save_manifest(root=...)`` writes forward-slash relative keys.]] - rationale - tests/test_detect.py
- [[count_words()]] - code - graphify/detect.py
- [[detect.py]] - code - graphify/detect.py
- [[detect_incremental must forward follow_symlinks so symlinked sub-trees     appea]] - rationale - tests/test_detect.py
- [[detect_incremental()]] - code - graphify/detect.py
- [[docx_to_markdown()]] - code - graphify/detect.py
- [[extract_pdf_text()]] - code - graphify/detect.py
- [[load_manifest()]] - code - graphify/detect.py
- [[manifest.py]] - code - graphify/manifest.py
- [[r1655 — files whose absolute path exceeds Windows MAX_PATH (260) must still]] - rationale - tests/test_long_path_hashing.py
- [[rReturn an OS path string safe for open()stat() on Windows long paths.]] - rationale - graphify/detect.py
- [[save_manifest()]] - code - graphify/detect.py
- [[test_detect_incremental_exclusion_stable_across_runs()]] - code - tests/test_detect.py
- [[test_detect_incremental_legacy_float_reextracts_on_backwards_mtime()]] - code - tests/test_detect.py
- [[test_detect_incremental_legacy_float_skips_when_mtime_matches()]] - code - tests/test_detect.py
- [[test_detect_incremental_portable_across_paths()]] - code - tests/test_detect.py
- [[test_detect_incremental_propagates_follow_symlinks()]] - code - tests/test_detect.py
- [[test_detect_incremental_reports_excluded_not_deleted()]] - code - tests/test_detect.py
- [[test_detect_incremental_still_reports_real_deletions()]] - code - tests/test_detect.py
- [[test_detect_incremental_survives_dict_valued_mtime()]] - code - tests/test_detect.py
- [[test_hashing_still_works_and_stabilizes()]] - code - tests/test_long_path_hashing.py
- [[test_load_manifest_absolutizes_relative_keys()]] - code - tests/test_detect.py
- [[test_load_manifest_passes_through_legacy_absolute_keys()]] - code - tests/test_detect.py
- [[test_long_path_hashing.py]] - code - tests/test_long_path_hashing.py
- [[test_manifest_nfc_keys_legacy_absolute()]] - code - tests/test_detect.py
- [[test_manifest_nfc_keys_survive_macos_path_forms()]] - code - tests/test_detect.py
- [[test_os_path_adds_prefix_on_win32()]] - code - tests/test_long_path_hashing.py
- [[test_os_path_idempotent_on_win32()]] - code - tests/test_long_path_hashing.py
- [[test_os_path_noop_on_posix()]] - code - tests/test_long_path_hashing.py
- [[test_save_manifest_clear_semantic_erases_stale_hash_for_omitted_file()]] - code - tests/test_detect.py
- [[test_save_manifest_full_scan_keeps_out_of_root_rows()]] - code - tests/test_detect.py
- [[test_save_manifest_full_scan_prunes_excluded_but_alive_row()]] - code - tests/test_detect.py
- [[test_save_manifest_full_scan_still_prunes_missing_file()]] - code - tests/test_detect.py
- [[test_save_manifest_in_root_symlink_roundtrips()]] - code - tests/test_detect.py
- [[test_save_manifest_out_of_root_keeps_absolute()]] - code - tests/test_detect.py
- [[test_save_manifest_relativizes_keys_when_root_given()]] - code - tests/test_detect.py
- [[test_save_manifest_skips_semantic_hash_for_files_without_cache()]] - code - tests/test_detect.py
- [[test_save_manifest_subset_save_preserves_untouched_rows()]] - code - tests/test_detect.py
- [[test_save_manifest_without_filter_unchanged_for_code()]] - code - tests/test_detect.py
- [[test_save_manifest_without_root_keeps_absolute_keys()]] - code - tests/test_detect.py
- [[xlsx_extract_structure()]] - code - graphify/detect.py
- [[xlsx_to_markdown()]] - code - graphify/detect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/detectpy
SORT file.name ASC
```

## Connections to other communities
- 48 edges to [[_COMMUNITY_test_detect.py]]
- 11 edges to [[_COMMUNITY__zip_within_caps]]
- 10 edges to [[_COMMUNITY_classify_file]]
- 8 edges to [[_COMMUNITY__load_graphifyignore]]
- 6 edges to [[_COMMUNITY_convert_office_file]]
- 5 edges to [[_COMMUNITY_cli.py]]
- 5 edges to [[_COMMUNITY_paths.py]]
- 4 edges to [[_COMMUNITY_google_workspace.py]]
- 3 edges to [[_COMMUNITY__rebuild_code]]
- 2 edges to [[_COMMUNITY_test_cache.py]]
- 2 edges to [[_COMMUNITY__env_command_args]]
- 2 edges to [[_COMMUNITY__is_noise_dir]]
- 2 edges to [[_COMMUNITY_test_manifest_ingest.py]]
- 2 edges to [[_COMMUNITY_llm.py]]
- 1 edge to [[_COMMUNITY_test_analyze.py]]
- 1 edge to [[_COMMUNITY_extract_astro]]
- 1 edge to [[_COMMUNITY_test_pipeline.py]]
- 1 edge to [[_COMMUNITY__stale_graph_sources]]
- 1 edge to [[_COMMUNITY_test_vue_extraction.py]]
- 1 edge to [[_COMMUNITY_test_watch.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_test_extract.py]]

## Top bridge nodes
- [[detect.py]] - degree 63, connects to 19 communities
- [[Path_7]] - degree 32, connects to 5 communities
- [[save_manifest()]] - degree 34, connects to 4 communities
- [[xlsx_to_markdown()]] - degree 9, connects to 4 communities
- [[_resolves_under_root()]] - degree 6, connects to 3 communities