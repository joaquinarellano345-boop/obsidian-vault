---
type: community
cohesion: 0.09
members: 36
---

# test_security.py

**Cohesion:** 0.09 - loosely connected
**Members:** 36 nodes

## Members
- [[Raise ValueError if url is not http or https, or targets a privateinternal IP]] - rationale - graphify/security.py
- [[Return the graph.json size cap in bytes.      Honors the ``GRAPHIFY_MAX_GRAPH_BY]] - rationale - graphify/security.py
- [[Strip control characters and cap length.      Safe for embedding in JSON data (i]] - rationale - graphify/security.py
- [[Tests for graphifysecurity.py - URL validation, safe fetch, path guards, label]] - rationale - tests/test_security.py
- [[_max_graph_file_bytes()]] - code - graphify/security.py
- [[parametrize_21]] - code
- [[sanitize_label()]] - code - graphify/security.py
- [[test_graph_size_cap_at_boundary_passes()]] - code - tests/test_security.py
- [[test_graph_size_cap_default_is_512_mib()]] - code - tests/test_security.py
- [[test_graph_size_cap_error_message_includes_size_and_cap()]] - code - tests/test_security.py
- [[test_graph_size_cap_missing_file_silently_returns()]] - code - tests/test_security.py
- [[test_graph_size_cap_over_limit_raises()]] - code - tests/test_security.py
- [[test_graph_size_cap_under_limit_returns_none()]] - code - tests/test_security.py
- [[test_graph_size_cap_unreadable_directory_silently_returns()]] - code - tests/test_security.py
- [[test_max_graph_bytes_default_when_blank()]] - code - tests/test_security.py
- [[test_max_graph_bytes_default_when_unset()]] - code - tests/test_security.py
- [[test_max_graph_bytes_gb_suffix_is_binary()]] - code - tests/test_security.py
- [[test_max_graph_bytes_mb_suffix_is_binary()]] - code - tests/test_security.py
- [[test_max_graph_bytes_nonpositive_falls_back()]] - code - tests/test_security.py
- [[test_max_graph_bytes_plain_integer()]] - code - tests/test_security.py
- [[test_max_graph_bytes_suffix_is_case_insensitive()]] - code - tests/test_security.py
- [[test_max_graph_bytes_tolerates_space_before_suffix()]] - code - tests/test_security.py
- [[test_max_graph_bytes_unparseable_falls_back()]] - code - tests/test_security.py
- [[test_sanitize_label_caps_at_256()]] - code - tests/test_security.py
- [[test_sanitize_label_none_returns_empty()]] - code - tests/test_security.py
- [[test_sanitize_label_passthrough_html_chars()]] - code - tests/test_security.py
- [[test_sanitize_label_safe_passthrough()]] - code - tests/test_security.py
- [[test_sanitize_label_strips_control_chars()]] - code - tests/test_security.py
- [[test_security.py]] - code - tests/test_security.py
- [[test_validate_url_accepts_http()]] - code - tests/test_security.py
- [[test_validate_url_accepts_https()]] - code - tests/test_security.py
- [[test_validate_url_rejects_data()]] - code - tests/test_security.py
- [[test_validate_url_rejects_empty_scheme()]] - code - tests/test_security.py
- [[test_validate_url_rejects_file()]] - code - tests/test_security.py
- [[test_validate_url_rejects_ftp()]] - code - tests/test_security.py
- [[validate_url()]] - code - graphify/security.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_securitypy
SORT file.name ASC
```

## Connections to other communities
- 18 edges to [[_COMMUNITY_sanitize_metadata]]
- 11 edges to [[_COMMUNITY_safe_fetch]]
- 10 edges to [[_COMMUNITY_cli.py]]
- 7 edges to [[_COMMUNITY_validate_graph_path]]
- 6 edges to [[_COMMUNITY_security.py]]
- 2 edges to [[_COMMUNITY_test_export.py]]
- 2 edges to [[_COMMUNITY_ingest.py]]
- 2 edges to [[_COMMUNITY__extract_pascal_regex]]
- 2 edges to [[_COMMUNITY_test_transcribe.py]]
- 1 edge to [[_COMMUNITY_export.py]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__build_server]]
- 1 edge to [[_COMMUNITY_test_serve.py]]
- 1 edge to [[_COMMUNITY__make_graph]]

## Top bridge nodes
- [[sanitize_label()]] - degree 19, connects to 9 communities
- [[test_security.py]] - degree 68, connects to 5 communities
- [[validate_url()]] - degree 16, connects to 4 communities
- [[_max_graph_file_bytes()]] - degree 13, connects to 2 communities
- [[test_graph_size_cap_at_boundary_passes()]] - degree 2, connects to 1 community