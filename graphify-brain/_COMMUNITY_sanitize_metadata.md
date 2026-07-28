---
type: community
cohesion: 0.10
members: 22
---

# sanitize_metadata

**Cohesion:** 0.10 - loosely connected
**Members:** 22 nodes

## Members
- [[Any_10]] - code
- [[Return a control-character-free, HTML-escaped, bounded string.]] - rationale - graphify/security.py
- [[Sanitize a metadata value while preserving simple JSON-compatible types.]] - rationale - graphify/security.py
- [[Sanitize metadata keys and values before graph export.      Metadata is less con]] - rationale - graphify/security.py
- [[_sanitize_metadata_string()]] - code - graphify/security.py
- [[_sanitize_metadata_value()]] - code - graphify/security.py
- [[sanitize_metadata()]] - code - graphify/security.py
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

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/sanitize_metadata
SORT file.name ASC
```

## Connections to other communities
- 18 edges to [[_COMMUNITY_test_security.py]]
- 3 edges to [[_COMMUNITY_scip_ingest.py]]
- 3 edges to [[_COMMUNITY_security.py]]
- 2 edges to [[_COMMUNITY__read_text]]
- 2 edges to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_test_extract.py]]
- 1 edge to [[_COMMUNITY_symbol_resolution.py]]
- 1 edge to [[_COMMUNITY_test_symbol_resolution.py]]

## Top bridge nodes
- [[sanitize_metadata()]] - degree 22, connects to 9 communities
- [[_sanitize_metadata_string()]] - degree 10, connects to 2 communities
- [[_sanitize_metadata_value()]] - degree 10, connects to 2 communities
- [[test_sanitize_metadata_bool_not_coerced_to_int()]] - degree 2, connects to 1 community
- [[test_sanitize_metadata_drops_empty_key()]] - degree 2, connects to 1 community