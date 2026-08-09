---
type: community
cohesion: 0.21
members: 15
---

# disambiguate_ambiguous_candidates

**Cohesion:** 0.21 - loosely connected
**Members:** 15 nodes

## Members
- [[Classify a source path as a test path (case-insensitive, segment-aware).      Sh]] - rationale - graphify/paths.py
- [[Pick the candidate whose source file is closest to the call site.      ``candida]] - rationale - graphify/paths.py
- [[Resolve an ambiguous bare-name call to one candidate, or ``None``.      Shared g]] - rationale - graphify/paths.py
- [[Tests for graphify.paths — the shared test-path classifier (1553).]] - rationale - tests/test_paths.py
- [[_is_test_path()]] - code - graphify/paths.py
- [[_path_proximity_winner()]] - code - graphify/paths.py
- [[disambiguate_ambiguous_candidates()]] - code - graphify/paths.py
- [[parametrize_18]] - code
- [[test_disambiguate_bails_on_two_nontest_candidates()]] - code - tests/test_paths.py
- [[test_disambiguate_drops_test_candidate_for_nontest_call_site()]] - code - tests/test_paths.py
- [[test_disambiguate_path_proximity_same_dir()]] - code - tests/test_paths.py
- [[test_disambiguate_test_call_site_prefers_test_local()]] - code - tests/test_paths.py
- [[test_is_test_path_negative()]] - code - tests/test_paths.py
- [[test_is_test_path_positive()]] - code - tests/test_paths.py
- [[test_paths.py]] - code - tests/test_paths.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/disambiguate_ambiguous_candidates
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_extract]]
- 1 edge to [[_COMMUNITY_symbol_resolution.py]]
- 1 edge to [[_COMMUNITY_test_symbol_resolution.py]]

## Top bridge nodes
- [[disambiguate_ambiguous_candidates()]] - degree 13, connects to 5 communities
- [[test_paths.py]] - degree 10, connects to 1 community
- [[_is_test_path()]] - degree 6, connects to 1 community
- [[_path_proximity_winner()]] - degree 3, connects to 1 community