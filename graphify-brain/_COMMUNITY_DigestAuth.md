---
type: community
cohesion: 0.32
members: 8
---

# DigestAuth

**Cohesion:** 0.32 - loosely connected
**Members:** 8 nodes

## Members
- [[.__init__()_12]] - code - worked/httpx/raw/auth.py
- [[._build_credentials()]] - code - worked/httpx/raw/auth.py
- [[._parse_challenge()]] - code - worked/httpx/raw/auth.py
- [[.auth_flow()_3]] - code - worked/httpx/raw/auth.py
- [[Compute the Authorization header value for a digest challenge.]] - rationale - worked/httpx/raw/auth.py
- [[DigestAuth]] - code - worked/httpx/raw/auth.py
- [[Extract digest parameters from the WWW-Authenticate header.]] - rationale - worked/httpx/raw/auth.py
- [[HTTP Digest Authentication.     Requires a full requestresponse cycle sends th]] - rationale - worked/httpx/raw/auth.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/DigestAuth
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_client.py]]
- 2 edges to [[_COMMUNITY_Request]]
- 1 edge to [[_COMMUNITY_Response]]

## Top bridge nodes
- [[DigestAuth]] - degree 7, connects to 1 community
- [[.auth_flow()_3]] - degree 4, connects to 1 community
- [[._build_credentials()]] - degree 4, connects to 1 community
- [[._parse_challenge()]] - degree 4, connects to 1 community