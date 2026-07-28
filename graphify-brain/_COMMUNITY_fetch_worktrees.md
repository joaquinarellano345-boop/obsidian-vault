---
type: community
cohesion: 0.16
members: 16
---

# fetch_worktrees

**Cohesion:** 0.16 - loosely connected
**Members:** 16 nodes

## Members
- [[.test_detached_head_does_not_leak_into_next_record()]] - code - tests/test_prs.py
- [[.test_detect_default_branch_decodes_output_as_utf8()]] - code - tests/test_prs.py
- [[.test_empty_output_returns_empty_dict()]] - code - tests/test_prs.py
- [[.test_fetch_worktrees_decodes_output_as_utf8()]] - code - tests/test_prs.py
- [[.test_fixture_is_cp1252_undecodable()]] - code - tests/test_prs.py
- [[.test_gh_decodes_output_as_utf8()]] - code - tests/test_prs.py
- [[.test_nonzero_returncode_returns_empty_dict()]] - code - tests/test_prs.py
- [[.test_normal_case_maps_branch_to_path()]] - code - tests/test_prs.py
- [[.test_subprocess_failure_returns_empty_dict()]] - code - tests/test_prs.py
- [[A detached HEAD (no branch line) must not associate its path with the         ne]] - rationale - tests/test_prs.py
- [[Guard the fixture's UTF-8 bytes must be undecodable as cp1252, else         the]] - rationale - tests/test_prs.py
- [[Returns {branch worktree_path}.]] - rationale - graphify/prs.py
- [[TestFetchWorktrees]] - code - tests/test_prs.py
- [[TestSubprocessOutputEncoding]] - code - tests/test_prs.py
- [[fetch_worktrees()]] - code - graphify/prs.py
- [[prs.py reads ghgitclaude output via subprocess.run(text=True). Without an]] - rationale - tests/test_prs.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/fetch_worktrees
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_test_prs.py]]
- 3 edges to [[_COMMUNITY__build_server]]
- 2 edges to [[_COMMUNITY_prs.py]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY_attach_graph_impact]]

## Top bridge nodes
- [[fetch_worktrees()]] - degree 12, connects to 4 communities
- [[TestSubprocessOutputEncoding]] - degree 8, connects to 2 communities
- [[TestFetchWorktrees]] - degree 7, connects to 1 community
- [[.test_detect_default_branch_decodes_output_as_utf8()]] - degree 2, connects to 1 community
- [[.test_gh_decodes_output_as_utf8()]] - degree 2, connects to 1 community