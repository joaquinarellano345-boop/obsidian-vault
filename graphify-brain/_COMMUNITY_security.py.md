---
type: community
cohesion: 0.12
members: 20
---

# security.py

**Cohesion:** 0.12 - loosely connected
**Members:** 20 nodes

## Members
- [[.connect()]] - code - graphify/security.py
- [[.connect()_1]] - code - graphify/security.py
- [[.http_open()]] - code - graphify/security.py
- [[.https_open()]] - code - graphify/security.py
- [[HTTPConnection that resolves + validates DNS once, then connects to the     exac]] - rationale - graphify/security.py
- [[HTTPSConnection variant of _SSRFGuardedHTTPConnection.      Connects to the vali]] - rationale - graphify/security.py
- [[IPv4Address]] - code
- [[IPv6Address]] - code
- [[OpenerDirector]] - code
- [[Resolve host once and return (family, validated_ip) for the first     address]] - rationale - graphify/security.py
- [[Return True if ip falls in a privatereservedinternal range.      Shared by v]] - rationale - graphify/security.py
- [[_SSRFGuardedHTTPConnection]] - code - graphify/security.py
- [[_SSRFGuardedHTTPHandler]] - code - graphify/security.py
- [[_SSRFGuardedHTTPSConnection]] - code - graphify/security.py
- [[_SSRFGuardedHTTPSHandler]] - code - graphify/security.py
- [[_build_opener()]] - code - graphify/security.py
- [[_ip_is_blocked()]] - code - graphify/security.py
- [[_resolve_and_validate()]] - code - graphify/security.py
- [[security.py]] - code - graphify/security.py
- [[urllib handler that routes http through _SSRFGuardedHTTPConnection.]] - rationale - graphify/security.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/securitypy
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_test_security.py]]
- 3 edges to [[_COMMUNITY_validate_url]]
- 3 edges to [[_COMMUNITY_safe_fetch]]
- 2 edges to [[_COMMUNITY_export.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY_ingest.py]]
- 1 edge to [[_COMMUNITY__get_extractor]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_scip_ingest.py]]
- 1 edge to [[_COMMUNITY_sanitize_label]]
- 1 edge to [[_COMMUNITY_validate_graph_path]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY_symbol_resolution.py]]

## Top bridge nodes
- [[security.py]] - degree 29, connects to 14 communities
- [[_ip_is_blocked()]] - degree 6, connects to 1 community
- [[_build_opener()]] - degree 3, connects to 1 community