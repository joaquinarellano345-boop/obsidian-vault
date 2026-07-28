---
type: community
cohesion: 0.17
members: 24
---

# test_prs.py

**Cohesion:** 0.17 - loosely connected
**Members:** 24 nodes

## Members
- [[.blast_radius()]] - code - graphify/prs.py
- [[.days_old()]] - code - graphify/prs.py
- [[.status()]] - code - graphify/prs.py
- [[.test_changes_req()]] - code - tests/test_prs.py
- [[.test_ci_fail()]] - code - tests/test_prs.py
- [[.test_contains_pr_metadata_and_count_header()]] - code - tests/test_prs.py
- [[.test_draft()]] - code - tests/test_prs.py
- [[.test_draft_not_marked_stale()]] - code - tests/test_prs.py
- [[.test_empty_pr_list()]] - code - tests/test_prs.py
- [[.test_pending()]] - code - tests/test_prs.py
- [[.test_ready()]] - code - tests/test_prs.py
- [[.test_stale()]] - code - tests/test_prs.py
- [[.test_wrong_base()]] - code - tests/test_prs.py
- [[Build a minimal PRInfo with sensible defaults.]] - rationale - tests/test_prs.py
- [[PRInfo]] - code - graphify/prs.py
- [[Plain-text PR summary for MCP output (no ANSI).]] - rationale - graphify/prs.py
- [[TestClassify]] - code - tests/test_prs.py
- [[TestFormatPrsText]] - code - tests/test_prs.py
- [[Tests for graphifyprs.py.]] - rationale - tests/test_prs.py
- [[_classify()]] - code - graphify/prs.py
- [[datetime_1]] - code
- [[format_prs_text()]] - code - graphify/prs.py
- [[make_pr()]] - code - tests/test_prs.py
- [[test_prs.py]] - code - tests/test_prs.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_prspy
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_prs.py]]
- 6 edges to [[_COMMUNITY__build_server]]
- 5 edges to [[_COMMUNITY_attach_graph_impact]]
- 5 edges to [[_COMMUNITY_fetch_worktrees]]
- 3 edges to [[_COMMUNITY_build_community_labels]]
- 3 edges to [[_COMMUNITY_compute_pr_impact]]
- 3 edges to [[_COMMUNITY__parse_ci]]
- 1 edge to [[_COMMUNITY_serve.py]]

## Top bridge nodes
- [[test_prs.py]] - degree 24, connects to 7 communities
- [[PRInfo]] - degree 22, connects to 7 communities
- [[format_prs_text()]] - degree 7, connects to 3 communities
- [[_classify()]] - degree 11, connects to 1 community