---
type: community
cohesion: 0.21
members: 13
---

# attach_graph_impact

**Cohesion:** 0.21 - loosely connected
**Members:** 13 nodes

## Members
- [[.test_both_directions_work()]] - code - tests/test_prs.py
- [[.test_exact_match()]] - code - tests/test_prs.py
- [[.test_fetch_pr_files_decodes_output_as_utf8()]] - code - tests/test_prs.py
- [[.test_graph_path_longer_with_boundary()]] - code - tests/test_prs.py
- [[.test_no_false_positive_on_partial_filename()]] - code - tests/test_prs.py
- [[Fetch PR file lists concurrently, compute graph impact, return community labels.]] - rationale - graphify/prs.py
- [[Path_47]] - code
- [[TestPathMatch]] - code - tests/test_prs.py
- [[True if graph_src and pr_file refer to the same file (path-boundary safe).]] - rationale - graphify/prs.py
- [[_load_graph_json()]] - code - graphify/prs.py
- [[_path_match()]] - code - graphify/prs.py
- [[attach_graph_impact()]] - code - graphify/prs.py
- [[fetch_pr_files()]] - code - graphify/prs.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/attach_graph_impact
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_prs.py]]
- 5 edges to [[_COMMUNITY_test_prs.py]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__build_server]]
- 1 edge to [[_COMMUNITY_compute_pr_impact]]
- 1 edge to [[_COMMUNITY_cli.py]]
- 1 edge to [[_COMMUNITY_build_community_labels]]
- 1 edge to [[_COMMUNITY_fetch_worktrees]]

## Top bridge nodes
- [[fetch_pr_files()]] - degree 6, connects to 4 communities
- [[attach_graph_impact()]] - degree 9, connects to 3 communities
- [[_path_match()]] - degree 9, connects to 3 communities
- [[_load_graph_json()]] - degree 4, connects to 2 communities
- [[TestPathMatch]] - degree 6, connects to 1 community