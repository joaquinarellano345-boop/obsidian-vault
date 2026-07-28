---
type: community
cohesion: 0.35
members: 11
---

# compute_pr_impact

**Cohesion:** 0.35 - loosely connected
**Members:** 11 nodes

## Members
- [[._make_graph()]] - code - tests/test_prs.py
- [[.test_empty_files_returns_empty()]] - code - tests/test_prs.py
- [[.test_matching_both_files()]] - code - tests/test_prs.py
- [[.test_matching_files_returns_correct_communities_and_count()]] - code - tests/test_prs.py
- [[.test_no_double_counting_same_graph_file_matched_by_two_pr_files()]] - code - tests/test_prs.py
- [[.test_no_double_counting_when_basename_matches_multiple_paths()]] - code - tests/test_prs.py
- [[.test_no_matching_files_returns_empty()]] - code - tests/test_prs.py
- [[3 nodes across 2 communities, 2 distinct source files.]] - rationale - tests/test_prs.py
- [[Return (communities_touched, nodes_affected) for a set of changed files.      Bu]] - rationale - graphify/prs.py
- [[TestComputePrImpact]] - code - tests/test_prs.py
- [[compute_pr_impact()]] - code - graphify/prs.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/compute_pr_impact
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_test_prs.py]]
- 3 edges to [[_COMMUNITY_Graph]]
- 1 edge to [[_COMMUNITY_prs.py]]
- 1 edge to [[_COMMUNITY_attach_graph_impact]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__build_server]]

## Top bridge nodes
- [[compute_pr_impact()]] - degree 12, connects to 5 communities
- [[TestComputePrImpact]] - degree 9, connects to 1 community
- [[._make_graph()]] - degree 7, connects to 1 community
- [[.test_no_double_counting_same_graph_file_matched_by_two_pr_files()]] - degree 3, connects to 1 community
- [[.test_no_double_counting_when_basename_matches_multiple_paths()]] - degree 3, connects to 1 community