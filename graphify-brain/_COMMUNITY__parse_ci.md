---
type: community
cohesion: 0.39
members: 9
---

# _parse_ci

**Cohesion:** 0.39 - loosely connected
**Members:** 9 nodes

## Members
- [[.test_cancelled_is_failure()]] - code - tests/test_prs.py
- [[.test_empty_rollup_returns_none()]] - code - tests/test_prs.py
- [[.test_failure_conclusion()]] - code - tests/test_prs.py
- [[.test_in_progress_is_pending()]] - code - tests/test_prs.py
- [[.test_mixed_success_and_failure_is_failure()]] - code - tests/test_prs.py
- [[.test_success()]] - code - tests/test_prs.py
- [[.test_timed_out_is_failure()]] - code - tests/test_prs.py
- [[TestParseCi]] - code - tests/test_prs.py
- [[_parse_ci()]] - code - graphify/prs.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_parse_ci
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_test_prs.py]]
- 2 edges to [[_COMMUNITY__build_server]]
- 1 edge to [[_COMMUNITY_prs.py]]
- 1 edge to [[_COMMUNITY_serve.py]]

## Top bridge nodes
- [[_parse_ci()]] - degree 12, connects to 4 communities
- [[TestParseCi]] - degree 9, connects to 1 community