---
type: community
cohesion: 0.12
members: 33
---

# BaseTransport

**Cohesion:** 0.12 - loosely connected
**Members:** 33 nodes

## Members
- [[.__init__()_17]] - code - worked/httpx/raw/client.py
- [[.__init__()_16]] - code - worked/httpx/raw/client.py
- [[.__init__()_27]] - code - worked/httpx/raw/transport.py
- [[.__init__()_28]] - code - worked/httpx/raw/transport.py
- [[.__init__()_29]] - code - worked/httpx/raw/transport.py
- [[.aclose()_1]] - code - worked/httpx/raw/transport.py
- [[.aclose()_2]] - code - worked/httpx/raw/transport.py
- [[.close()_1]] - code - worked/httpx/raw/transport.py
- [[.close()_3]] - code - worked/httpx/raw/transport.py
- [[.close()_4]] - code - worked/httpx/raw/transport.py
- [[.handle_async_request()]] - code - worked/httpx/raw/transport.py
- [[.handle_async_request()_1]] - code - worked/httpx/raw/transport.py
- [[.handle_request()_3]] - code - worked/httpx/raw/transport.py
- [[A network error occurred.]] - rationale - worked/httpx/raw/exceptions.py
- [[A transport for testing that returns predefined responses.     Pass a handler fu]] - rationale - worked/httpx/raw/transport.py
- [[An error occurred at the transport layer.]] - rationale - worked/httpx/raw/exceptions.py
- [[AsyncBaseTransport]] - code - worked/httpx/raw/transport.py
- [[AsyncHTTPTransport]] - code - worked/httpx/raw/transport.py
- [[BaseTransport]] - code - worked/httpx/raw/transport.py
- [[ConnectError]] - code - worked/httpx/raw/exceptions.py
- [[Failed to establish a connection.]] - rationale - worked/httpx/raw/exceptions.py
- [[HTTPTransport]] - code - worked/httpx/raw/transport.py
- [[MockTransport]] - code - worked/httpx/raw/transport.py
- [[NetworkError_1]] - code - worked/httpx/raw/exceptions.py
- [[ProxyTransport]] - code - worked/httpx/raw/transport.py
- [[Routes requests through an HTTPHTTPS proxy.     Wraps an inner transport and pr]] - rationale - worked/httpx/raw/transport.py
- [[Sync transport interface.]] - rationale - worked/httpx/raw/transport.py
- [[The async variant of HTTPTransport.]] - rationale - worked/httpx/raw/transport.py
- [[The main sync HTTP transport.     Uses a ConnectionPool for connection reuse.]] - rationale - worked/httpx/raw/transport.py
- [[TimeoutException]] - code - worked/httpx/raw/exceptions.py
- [[Transport layer connection management and low-level HTTP sending. HTTPTransport]] - rationale - worked/httpx/raw/transport.py
- [[TransportError]] - code - worked/httpx/raw/exceptions.py
- [[transport.py]] - code - worked/httpx/raw/transport.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/BaseTransport
SORT file.name ASC
```

## Connections to other communities
- 15 edges to [[_COMMUNITY_exceptions.py]]
- 14 edges to [[_COMMUNITY_Request]]
- 13 edges to [[_COMMUNITY_client.py]]
- 12 edges to [[_COMMUNITY_Response]]

## Top bridge nodes
- [[transport.py]] - degree 15, connects to 4 communities
- [[BaseTransport]] - degree 18, connects to 3 communities
- [[HTTPTransport]] - degree 18, connects to 3 communities
- [[TransportError]] - degree 16, connects to 2 communities
- [[AsyncHTTPTransport]] - degree 16, connects to 2 communities