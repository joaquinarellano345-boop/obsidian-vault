---
type: community
cohesion: 0.17
members: 32
---

# test_serve_http.py

**Cohesion:** 0.17 - loosely connected
**Members:** 32 nodes

## Members
- [[A full initialize - toolslist round trip works over the HTTP transport.]] - rationale - tests/test_serve_http.py
- [[A missing project graph is a tool error, not a process exit — the server     kee]] - rationale - tests/test_serve_http.py
- [[Build the Starlette ASGI app for the Streamable HTTP transport.      Split out f]] - rationale - graphify/serve.py
- [[Create ``projgraphify-outgraph.json`` and return the project dir.]] - rationale - tests/test_serve_http.py
- [[Multi-project support is additive every tool gains an optional     project_path]] - rationale - tests/test_serve_http.py
- [[One running server answers against the default graph when project_path is     om]] - rationale - tests/test_serve_http.py
- [[Path_96]] - code
- [[TestClient]] - code
- [[Tests for the Streamable HTTP transport on the MCP server (issue 1143).  These]] - rationale - tests/test_serve_http.py
- [[_build_http_app()]] - code - graphify/serve.py
- [[_call_tool()]] - code - tests/test_serve_http.py
- [[_client()]] - code - tests/test_serve_http.py
- [[_graph_file()]] - code - tests/test_serve_http.py
- [[_init_session()]] - code - tests/test_serve_http.py
- [[_project_with_graph()]] - code - tests/test_serve_http.py
- [[test_api_key_bearer_ok()]] - code - tests/test_serve_http.py
- [[test_api_key_bearer_scheme_case_insensitive()]] - code - tests/test_serve_http.py
- [[test_api_key_missing_is_401()]] - code - tests/test_serve_http.py
- [[test_api_key_wrong_is_401()]] - code - tests/test_serve_http.py
- [[test_api_key_x_api_key_header_ok()]] - code - tests/test_serve_http.py
- [[test_app_builds_and_initialize_succeeds()]] - code - tests/test_serve_http.py
- [[test_bad_project_path_errors_without_killing_server()]] - code - tests/test_serve_http.py
- [[test_blank_api_key_means_no_auth()]] - code - tests/test_serve_http.py
- [[test_custom_mount_path()]] - code - tests/test_serve_http.py
- [[test_project_path_is_optional_on_every_tool()]] - code - tests/test_serve_http.py
- [[test_project_path_routes_to_that_projects_graph()]] - code - tests/test_serve_http.py
- [[test_serve_http.py]] - code - tests/test_serve_http.py
- [[test_session_timeout_zero_disables()]] - code - tests/test_serve_http.py
- [[test_stateless_mode_initialize()]] - code - tests/test_serve_http.py
- [[test_stateless_with_timeout_does_not_raise()]] - code - tests/test_serve_http.py
- [[test_tools_list_over_http()]] - code - tests/test_serve_http.py
- [[test_unknown_path_is_404()]] - code - tests/test_serve_http.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_serve_httppy
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_default_graph_json]]
- 2 edges to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__build_server]]
- 1 edge to [[_COMMUNITY__MCPASGIApp]]

## Top bridge nodes
- [[_build_http_app()]] - degree 21, connects to 4 communities
- [[test_serve_http.py]] - degree 26, connects to 2 communities