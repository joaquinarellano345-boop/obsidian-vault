---
type: community
cohesion: 0.07
members: 29
---

# _is_ignored

**Cohesion:** 0.07 - loosely connected
**Members:** 29 nodes

## Members
- [[build must not match srcbuild.]] - rationale - tests/test_detect.py
- [[inbox must not match srcinbox — only inbox at the anchor root.]] - rationale - tests/test_detect.py
- [[inbox must still match inbox at the anchor root (positive case).]] - rationale - tests/test_detect.py
- [[srcinbox must match srcinbox but not xsrcinbox.]] - rationale - tests/test_detect.py
- [[A ! re-include cannot un-ignore a file whose parent dir is excluded (882).]] - rationale - tests/test_detect.py
- [[A ! re-include must still un-ignore a file when no ancestor is excluded (882).]] - rationale - tests/test_detect.py
- [[A shared _cache must not change _is_ignored results, including negation.      Bu]] - rationale - tests/test_detect.py
- [[If the ancestor dir itself is re-included, its children should not be blocked (]] - rationale - tests/test_detect.py
- [[Return True if the path should be ignored per .graphifyignore patterns.      Use]] - rationale - graphify/detect.py
- [[Return True if this directory name looks like a venv, cache, or dep dir.]] - rationale - graphify/detect.py
- [[Siblings under the same subtree must share the cached parent result (1235).]] - rationale - tests/test_detect.py
- [[True only when d has actual virtualenvconda structure on disk.      ``env```]] - rationale - graphify/detect.py
- [[_has_venv_markers()]] - code - graphify/detect.py
- [[_is_ignored()]] - code - graphify/detect.py
- [[_is_noise_dir()]] - code - graphify/detect.py
- [[_xaml_csharp_class_nodes()]] - code - graphify/extract.py
- [[inbox (no leading ) must still match srcinbox anywhere in the tree.]] - rationale - tests/test_detect.py
- [[infoexclude is loaded at lowest priority, so a later .gitignore `!` negation]] - rationale - tests/test_detect.py
- [[test_anchored_dir_matches_at_root()]] - code - tests/test_detect.py
- [[test_anchored_dir_not_matched_at_depth()]] - code - tests/test_detect.py
- [[test_anchored_file_not_matched_at_depth()]] - code - tests/test_detect.py
- [[test_anchored_multi_segment_pattern()]] - code - tests/test_detect.py
- [[test_git_info_exclude_ranks_below_gitignore_negation()]] - code - tests/test_detect.py
- [[test_is_ignored_cache_evaluates_each_dir_once()]] - code - tests/test_detect.py
- [[test_is_ignored_cache_matches_uncached_results()]] - code - tests/test_detect.py
- [[test_negation_ancestor_itself_reincluded()]] - code - tests/test_detect.py
- [[test_negation_cannot_rescue_file_under_excluded_dir()]] - code - tests/test_detect.py
- [[test_negation_works_when_no_ancestor_excluded()]] - code - tests/test_detect.py
- [[test_unanchored_dir_still_matches_at_depth()]] - code - tests/test_detect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_is_ignored
SORT file.name ASC
```

## Connections to other communities
- 15 edges to [[_COMMUNITY_detect.py]]
- 14 edges to [[_COMMUNITY_test_detect.py]]
- 6 edges to [[_COMMUNITY_test_extract.py]]
- 3 edges to [[_COMMUNITY_extract.py]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_test_languages.py]]
- 1 edge to [[_COMMUNITY_test_dotnet.py]]

## Top bridge nodes
- [[_is_ignored()]] - degree 23, connects to 5 communities
- [[_xaml_csharp_class_nodes()]] - degree 8, connects to 5 communities
- [[_is_noise_dir()]] - degree 9, connects to 4 communities
- [[test_anchored_dir_matches_at_root()]] - degree 4, connects to 2 communities
- [[test_anchored_dir_not_matched_at_depth()]] - degree 4, connects to 2 communities