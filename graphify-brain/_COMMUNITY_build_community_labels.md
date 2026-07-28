---
type: community
cohesion: 0.43
members: 7
---

# build_community_labels

**Cohesion:** 0.43 - moderately connected
**Members:** 7 nodes

## Members
- [[.test_basic_grouping()]] - code - tests/test_prs.py
- [[.test_empty_nodes()]] - code - tests/test_prs.py
- [[.test_no_community_field_skipped()]] - code - tests/test_prs.py
- [[.test_top_n_capped()]] - code - tests/test_prs.py
- [[Return {community_id top_labels} extracted from graph node data.]] - rationale - graphify/prs.py
- [[TestBuildCommunityLabels]] - code - tests/test_prs.py
- [[build_community_labels()]] - code - graphify/prs.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/build_community_labels
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_test_prs.py]]
- 1 edge to [[_COMMUNITY_prs.py]]
- 1 edge to [[_COMMUNITY_attach_graph_impact]]

## Top bridge nodes
- [[build_community_labels()]] - degree 8, connects to 3 communities
- [[TestBuildCommunityLabels]] - degree 6, connects to 1 community