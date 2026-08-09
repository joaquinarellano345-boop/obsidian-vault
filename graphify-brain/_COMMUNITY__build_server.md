---
type: community
cohesion: 0.24
members: 13
---

# _build_server

**Cohesion:** 0.24 - loosely connected
**Members:** 13 nodes

## Members
- [[.test_both_fail_returns_main()]] - code - tests/test_prs.py
- [[.test_falls_back_to_git_symbolic_ref()]] - code - tests/test_prs.py
- [[.test_gh_returns_empty_dict_falls_back()]] - code - tests/test_prs.py
- [[.test_gh_returns_main()]] - code - tests/test_prs.py
- [[.test_git_timeout_returns_main()]] - code - tests/test_prs.py
- [[Auto-detect the repo's default branch via gh, then git, then fall back to 'main']] - rationale - graphify/prs.py
- [[Build the configured low-level MCP Server (shared by every transport).      All]] - rationale - graphify/serve.py
- [[TestDetectDefaultBranch]] - code - tests/test_prs.py
- [[_build_server()]] - code - graphify/serve.py
- [[_detect_default_branch()]] - code - graphify/prs.py
- [[_gh()]] - code - graphify/prs.py
- [[fetch_prs()]] - code - graphify/prs.py
- [[gh returns data but with no defaultBranchRef — should still fall back.]] - rationale - tests/test_prs.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_build_server
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_test_prs.py]]
- 5 edges to [[_COMMUNITY_prs.py]]
- 4 edges to [[_COMMUNITY_serve.py]]
- 3 edges to [[_COMMUNITY_fetch_worktrees]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY__parse_ci]]
- 1 edge to [[_COMMUNITY_generate]]
- 1 edge to [[_COMMUNITY_test_analyze.py]]
- 1 edge to [[_COMMUNITY_attach_graph_impact]]
- 1 edge to [[_COMMUNITY_compute_pr_impact]]
- 1 edge to [[_COMMUNITY_sanitize_label]]
- 1 edge to [[_COMMUNITY_test_serve_http.py]]
- 1 edge to [[_COMMUNITY_default_graph_json]]

## Top bridge nodes
- [[_build_server()]] - degree 18, connects to 13 communities
- [[_gh()]] - degree 8, connects to 5 communities
- [[_detect_default_branch()]] - degree 14, connects to 4 communities
- [[fetch_prs()]] - degree 8, connects to 4 communities
- [[TestDetectDefaultBranch]] - degree 7, connects to 1 community