---
type: community
cohesion: 0.29
members: 7
---

# sanitize_label

**Cohesion:** 0.29 - loosely connected
**Members:** 7 nodes

## Members
- [[Strip control characters and cap length.      Safe for embedding in JSON data (i]] - rationale - graphify/security.py
- [[sanitize_label()]] - code - graphify/security.py
- [[test_sanitize_label_caps_at_256()]] - code - tests/test_security.py
- [[test_sanitize_label_none_returns_empty()]] - code - tests/test_security.py
- [[test_sanitize_label_passthrough_html_chars()]] - code - tests/test_security.py
- [[test_sanitize_label_safe_passthrough()]] - code - tests/test_security.py
- [[test_sanitize_label_strips_control_chars()]] - code - tests/test_security.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/sanitize_label
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_test_security.py]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_export.py]]
- 2 edges to [[_COMMUNITY__get_extractor]]
- 1 edge to [[_COMMUNITY_test_export.py]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__build_server]]
- 1 edge to [[_COMMUNITY_test_serve.py]]
- 1 edge to [[_COMMUNITY__make_graph]]

## Top bridge nodes
- [[sanitize_label()]] - degree 19, connects to 10 communities
- [[test_sanitize_label_caps_at_256()]] - degree 2, connects to 1 community
- [[test_sanitize_label_none_returns_empty()]] - degree 2, connects to 1 community
- [[test_sanitize_label_passthrough_html_chars()]] - degree 2, connects to 1 community
- [[test_sanitize_label_safe_passthrough()]] - degree 2, connects to 1 community