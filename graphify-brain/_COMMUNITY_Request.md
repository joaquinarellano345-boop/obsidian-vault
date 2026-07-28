---
type: community
cohesion: 0.18
members: 16
---

# Request

**Cohesion:** 0.18 - loosely connected
**Members:** 16 nodes

## Members
- [[.__init__()_25]] - code - worked/httpx/raw/transport.py
- [[.__init__()_26]] - code - worked/httpx/raw/transport.py
- [[.__repr__()_1]] - code - worked/httpx/raw/models.py
- [[._get_connection_key()]] - code - worked/httpx/raw/transport.py
- [[._send()]] - code - worked/httpx/raw/transport.py
- [[.auth_flow()]] - code - worked/httpx/raw/auth.py
- [[.close()_2]] - code - worked/httpx/raw/transport.py
- [[.get_connection()]] - code - worked/httpx/raw/transport.py
- [[.handle_request()]] - code - worked/httpx/raw/transport.py
- [[.handle_request()_1]] - code - worked/httpx/raw/transport.py
- [[.handle_request()_2]] - code - worked/httpx/raw/transport.py
- [[.return_connection()]] - code - worked/httpx/raw/transport.py
- [[ConnectionPool]] - code - worked/httpx/raw/transport.py
- [[Manages a pool of persistent HTTP connections.     Keys connections by (scheme,]] - rationale - worked/httpx/raw/transport.py
- [[Modify the request. May yield to inspect the response.]] - rationale - worked/httpx/raw/auth.py
- [[Request]] - code - worked/httpx/raw/models.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Request
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_BaseTransport]]
- 7 edges to [[_COMMUNITY_Response]]
- 6 edges to [[_COMMUNITY_client.py]]
- 3 edges to [[_COMMUNITY_Cookies]]
- 2 edges to [[_COMMUNITY_DigestAuth]]

## Top bridge nodes
- [[Request]] - degree 26, connects to 5 communities
- [[.handle_request()_1]] - degree 7, connects to 2 communities
- [[._send()]] - degree 4, connects to 2 communities
- [[.handle_request()]] - degree 3, connects to 2 communities
- [[.handle_request()_2]] - degree 3, connects to 2 communities