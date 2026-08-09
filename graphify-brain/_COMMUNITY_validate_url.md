---
type: community
cohesion: 0.18
members: 11
---

# validate_url

**Cohesion:** 0.18 - loosely connected
**Members:** 11 nodes

## Members
- [[.redirect_request()]] - code - graphify/security.py
- [[Raise ValueError if url is not http or https, or targets a privateinternal IP]] - rationale - graphify/security.py
- [[Redirect handler that re-validates every redirect target.      Prevents open-red]] - rationale - graphify/security.py
- [[_NoFileRedirectHandler]] - code - graphify/security.py
- [[test_validate_url_accepts_http()]] - code - tests/test_security.py
- [[test_validate_url_accepts_https()]] - code - tests/test_security.py
- [[test_validate_url_rejects_data()]] - code - tests/test_security.py
- [[test_validate_url_rejects_empty_scheme()]] - code - tests/test_security.py
- [[test_validate_url_rejects_file()]] - code - tests/test_security.py
- [[test_validate_url_rejects_ftp()]] - code - tests/test_security.py
- [[validate_url()]] - code - graphify/security.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/validate_url
SORT file.name ASC
```

## Connections to other communities
- 7 edges to [[_COMMUNITY_test_security.py]]
- 3 edges to [[_COMMUNITY_security.py]]
- 2 edges to [[_COMMUNITY_ingest.py]]
- 2 edges to [[_COMMUNITY_test_transcribe.py]]
- 1 edge to [[_COMMUNITY_safe_fetch]]

## Top bridge nodes
- [[validate_url()]] - degree 16, connects to 5 communities
- [[_NoFileRedirectHandler]] - degree 3, connects to 1 community
- [[test_validate_url_accepts_http()]] - degree 2, connects to 1 community
- [[test_validate_url_accepts_https()]] - degree 2, connects to 1 community
- [[test_validate_url_rejects_data()]] - degree 2, connects to 1 community