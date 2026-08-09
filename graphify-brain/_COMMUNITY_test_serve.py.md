---
type: community
cohesion: 0.08
members: 46
---

# test_serve.py

**Cohesion:** 0.08 - loosely connected
**Members:** 46 nodes

## Members
- [[A graph large enough that the selectivity guard lets the fast-path fire for]] - rationale - tests/test_serve.py
- [[Character trigrams of `text`; for 3-char text the whole string is the key.]] - rationale - graphify/serve.py
- [[Disable the prefilter so a call exercises the original full-node scan.]] - rationale - tests/test_serve.py
- [[Japanese kana and Hangul are kept as terms but not segmented as Chinese.]] - rationale - tests/test_serve.py
- [[Lazily build and cache a trigram - node-position postings map on the graph.]] - rationale - graphify/serve.py
- [[Node IDs whose text could contain any `needle` as a substring, via the     trigr]] - rationale - graphify/serve.py
- [[Reconstruct community dict from community property stored on nodes.]] - rationale - graphify/serve.py
- [[Render pre-built lines under the same ~3-charstoken budget rule as     _subgrap]] - rationale - graphify/serve.py
- [[Return node IDs whose label or ID matches the search term (diacritic-insensitive]] - rationale - graphify/serve.py
- [[Tests for serve.py - MCP graph query helpers (no mcp package required).]] - rationale - tests/test_serve.py
- [[When jieba is not installed, fallback to character bigrams.]] - rationale - tests/test_serve.py
- [[_communities_from_graph()]] - code - graphify/serve.py
- [[_community_header()]] - code - graphify/serve.py
- [[_cut_lines_to_budget()]] - code - graphify/serve.py
- [[_find_node()]] - code - graphify/serve.py
- [[_force_full_scan()]] - code - tests/test_serve.py
- [[_get_trigram_index()]] - code - graphify/serve.py
- [[_make_big_graph()]] - code - tests/test_serve.py
- [[_trigram_candidates()]] - code - graphify/serve.py
- [[_trigrams()]] - code - graphify/serve.py
- [[test_communities_from_graph_basic()]] - code - tests/test_serve.py
- [[test_communities_from_graph_isolated()]] - code - tests/test_serve.py
- [[test_communities_from_graph_no_community_attr()]] - code - tests/test_serve.py
- [[test_community_header_falls_back_when_no_name()]] - code - tests/test_serve.py
- [[test_community_header_sanitizes_name()]] - code - tests/test_serve.py
- [[test_community_header_shows_real_name()]] - code - tests/test_serve.py
- [[test_community_header_skips_placeholder_name()]] - code - tests/test_serve.py
- [[test_cut_lines_to_budget_over_budget_announces_at_top()]] - code - tests/test_serve.py
- [[test_cut_lines_to_budget_under_budget_is_byte_identical()]] - code - tests/test_serve.py
- [[test_find_node_ignores_trailing_punctuation()]] - code - tests/test_serve.py
- [[test_find_node_label_tokens_branch_covered_by_index()]] - code - tests/test_serve.py
- [[test_find_node_matches_full_punctuated_unicode_label()]] - code - tests/test_serve.py
- [[test_find_node_matches_punctuated_file_label_exactly()]] - code - tests/test_serve.py
- [[test_find_node_prefilter_is_identical_to_full_scan()]] - code - tests/test_serve.py
- [[test_find_node_resolves_when_label_and_norm_label_diverge()]] - code - tests/test_serve.py
- [[test_find_node_source_file_path_prefers_file_level_node()]] - code - tests/test_serve.py
- [[test_node_search_text_includes_all_matched_fields()]] - code - tests/test_serve.py
- [[test_query_terms_chinese_no_jieba_fallback()]] - code - tests/test_serve.py
- [[test_query_terms_non_chinese_scripts_are_not_segmented()]] - code - tests/test_serve.py
- [[test_score_nodes_prefilter_is_identical_to_full_scan()]] - code - tests/test_serve.py
- [[test_serve.py]] - code - tests/test_serve.py
- [[test_trigram_candidates_falls_back_on_common_term()]] - code - tests/test_serve.py
- [[test_trigram_candidates_falls_back_on_short_token()]] - code - tests/test_serve.py
- [[test_trigram_candidates_fast_path_fires_for_rare_term()]] - code - tests/test_serve.py
- [[test_trigram_index_cached_and_rebuilt_per_graph()]] - code - tests/test_serve.py
- [[test_trigrams_basic()]] - code - tests/test_serve.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_servepy
SORT file.name ASC
```

## Connections to other communities
- 33 edges to [[_COMMUNITY__make_graph]]
- 23 edges to [[_COMMUNITY_serve.py]]
- 21 edges to [[_COMMUNITY__score_nodes]]
- 13 edges to [[_COMMUNITY__pick_seeds]]
- 10 edges to [[_COMMUNITY__load_graph]]
- 10 edges to [[_COMMUNITY__query_terms]]
- 10 edges to [[_COMMUNITY_Graph]]
- 4 edges to [[_COMMUNITY_bench_query_scoring.py]]
- 3 edges to [[_COMMUNITY__make_noisy_graph]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_test_file_label_disambiguation.py]]
- 1 edge to [[_COMMUNITY_sanitize_label]]

## Top bridge nodes
- [[test_serve.py]] - degree 138, connects to 9 communities
- [[_find_node()]] - degree 17, connects to 4 communities
- [[_get_trigram_index()]] - degree 9, connects to 2 communities
- [[_community_header()]] - degree 7, connects to 2 communities
- [[test_score_nodes_prefilter_is_identical_to_full_scan()]] - degree 5, connects to 2 communities