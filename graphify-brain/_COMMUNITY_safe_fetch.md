---
type: community
cohesion: 0.21
members: 12
---

# safe_fetch

**Cohesion:** 0.21 - loosely connected
**Members:** 12 nodes

## Members
- [[Fetch url and return decoded text (UTF-8, replacing bad bytes).      Wraps saf]] - rationale - graphify/security.py
- [[Fetch url and return raw bytes.      Protections applied     - URL scheme val]] - rationale - graphify/security.py
- [[_make_mock_response()]] - code - tests/test_security.py
- [[safe_fetch()]] - code - graphify/security.py
- [[safe_fetch_text()]] - code - graphify/security.py
- [[test_safe_fetch_raises_on_non_2xx()]] - code - tests/test_security.py
- [[test_safe_fetch_raises_on_size_exceeded()]] - code - tests/test_security.py
- [[test_safe_fetch_rejects_file_url()]] - code - tests/test_security.py
- [[test_safe_fetch_rejects_ftp_url()]] - code - tests/test_security.py
- [[test_safe_fetch_returns_bytes()]] - code - tests/test_security.py
- [[test_safe_fetch_text_decodes_utf8()]] - code - tests/test_security.py
- [[test_safe_fetch_text_replaces_bad_bytes()]] - code - tests/test_security.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/safe_fetch
SORT file.name ASC
```

## Connections to other communities
- 10 edges to [[_COMMUNITY_test_security.py]]
- 5 edges to [[_COMMUNITY_ingest.py]]
- 3 edges to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_validate_url]]

## Top bridge nodes
- [[safe_fetch()]] - degree 13, connects to 4 communities
- [[safe_fetch_text()]] - degree 9, connects to 3 communities
- [[_make_mock_response()]] - degree 5, connects to 1 community
- [[test_safe_fetch_raises_on_non_2xx()]] - degree 3, connects to 1 community
- [[test_safe_fetch_returns_bytes()]] - degree 3, connects to 1 community