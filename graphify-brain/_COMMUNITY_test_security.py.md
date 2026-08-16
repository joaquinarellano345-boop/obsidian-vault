---
type: community
cohesion: 0.08
members: 45
---

# test_security.py

**Cohesion:** 0.08 - loosely connected
**Members:** 45 nodes

## Members
- [[Any_10]] - code
- [[Reject path if its size exceeds the configured graph-file cap.      Protects c]] - rationale - graphify/security.py
- [[Return a control-character-free, HTML-escaped, bounded string.]] - rationale - graphify/security.py
- [[Return the graph.json size cap in bytes.      Honors the ``GRAPHIFY_MAX_GRAPH_BY]] - rationale - graphify/security.py
- [[Sanitize a metadata value while preserving simple JSON-compatible types.]] - rationale - graphify/security.py
- [[Sanitize metadata keys and values before graph export.      Metadata is less con]] - rationale - graphify/security.py
- [[Tests for graphifysecurity.py - URL validation, safe fetch, path guards, label]] - rationale - tests/test_security.py
- [[_max_graph_file_bytes()]] - code - graphify/security.py
- [[_sanitize_metadata_string()]] - code - graphify/security.py
- [[_sanitize_metadata_value()]] - code - graphify/security.py
- [[check_graph_file_size_cap()]] - code - graphify/security.py
- [[parametrize_21]] - code
- [[sanitize_metadata()]] - code - graphify/security.py
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
- [[test_sanitize_metadata_bool_not_coerced_to_int()]] - code - tests/test_security.py
- [[test_sanitize_metadata_drops_empty_key()]] - code - tests/test_security.py
- [[test_sanitize_metadata_none_returns_empty_dict()]] - code - tests/test_security.py
- [[test_sanitize_metadata_recursive_nested()]] - code - tests/test_security.py
- [[test_sanitize_metadata_sanitizes_keys()]] - code - tests/test_security.py
- [[test_sanitize_metadata_string_caps_length()]] - code - tests/test_security.py
- [[test_sanitize_metadata_string_coerces_non_string()]] - code - tests/test_security.py
- [[test_sanitize_metadata_string_escapes_html()]] - code - tests/test_security.py
- [[test_sanitize_metadata_string_escapes_quotes()]] - code - tests/test_security.py
- [[test_sanitize_metadata_string_strips_control_chars()]] - code - tests/test_security.py
- [[test_sanitize_metadata_value_caps_list_length()]] - code - tests/test_security.py
- [[test_sanitize_metadata_value_converts_tuple_to_list()]] - code - tests/test_security.py
- [[test_sanitize_metadata_value_preserves_simple_types()]] - code - tests/test_security.py
- [[test_sanitize_metadata_value_recurses_into_dict()]] - code - tests/test_security.py
- [[test_sanitize_metadata_value_recurses_into_list()]] - code - tests/test_security.py
- [[test_security.py]] - code - tests/test_security.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_securitypy
SORT file.name ASC
```

## Connections to other communities
- 10 edges to [[_COMMUNITY_safe_fetch]]
- 8 edges to [[_COMMUNITY_validate_graph_path]]
- 7 edges to [[_COMMUNITY_cli.py]]
- 7 edges to [[_COMMUNITY_validate_url]]
- 6 edges to [[_COMMUNITY_security.py]]
- 6 edges to [[_COMMUNITY_sanitize_label]]
- 3 edges to [[_COMMUNITY_test_global_graph.py]]
- 3 edges to [[_COMMUNITY_scip_ingest.py]]
- 2 edges to [[_COMMUNITY_graphifybuild.py]]
- 2 edges to [[_COMMUNITY_test_multigraph_diagnostics.py]]
- 2 edges to [[_COMMUNITY__make_id]]
- 2 edges to [[_COMMUNITY_engine.py]]
- 2 edges to [[_COMMUNITY_test_file_label_disambiguation.py]]
- 1 edge to [[_COMMUNITY_callflow_html.py]]
- 1 edge to [[_COMMUNITY_load_graph]]
- 1 edge to [[_COMMUNITY_export.py]]
- 1 edge to [[_COMMUNITY_test_export.py]]
- 1 edge to [[_COMMUNITY_to_json]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_extract_bash]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_prs.py]]
- 1 edge to [[_COMMUNITY_attach_graph_impact]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__load_graph]]
- 1 edge to [[_COMMUNITY_symbol_resolution.py]]
- 1 edge to [[_COMMUNITY_resolve_python_import_guided_calls]]

## Top bridge nodes
- [[check_graph_file_size_cap()]] - degree 37, connects to 17 communities
- [[sanitize_metadata()]] - degree 22, connects to 8 communities
- [[test_security.py]] - degree 68, connects to 5 communities
- [[_max_graph_file_bytes()]] - degree 13, connects to 1 community
- [[_sanitize_metadata_string()]] - degree 10, connects to 1 community