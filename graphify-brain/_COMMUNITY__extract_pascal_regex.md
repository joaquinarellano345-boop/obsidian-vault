---
type: community
cohesion: 0.10
members: 31
---

# _extract_pascal_regex

**Cohesion:** 0.10 - loosely connected
**Members:** 31 nodes

## Members
- [[Any_6]] - code
- [[Append a node if not already present. ``kind`` is metadata, not file_type.]] - rationale - graphify/mcp_ingest.py
- [[Append an edge if (source, target, relation) is not already present.]] - rationale - graphify/mcp_ingest.py
- [[Build a scoped call resolver for a single PascalDelphi file.      ``records`` i]] - rationale - graphify/extractors/pascal.py
- [[Drop the ``@version`` suffix from an npm package id, preserving the scope.]] - rationale - graphify/mcp_ingest.py
- [[Emit nodesedges for one entry under ``mcpServers``.]] - rationale - graphify/mcp_ingest.py
- [[Find balanced begin..end after start. Returns (body_start, body_end).     Return]] - rationale - graphify/extractors/pascal.py
- [[Regex fallback for PascalDelphi extraction when tree-sitter-pascal     is unava]] - rationale - graphify/extractors/pascal.py
- [[Regex-based fallback for Spock spec files where tree-sitter-groovy cannot parse]] - rationale - graphify/extract.py
- [[Return the first arg that looks like an npm or pypi package id, else None.]] - rationale - graphify/mcp_ingest.py
- [[Split a uses list string, handling 'Foo in ''bar.pas''' syntax.]] - rationale - graphify/extractors/pascal.py
- [[Split inheritance list, handling generics like TListT, U.]] - rationale - graphify/extractors/pascal.py
- [[Split into (iface_text, iface_offset, impl_text, impl_offset).     Files without]] - rationale - graphify/extractors/pascal.py
- [[Strip Pascal comments ({}, ( ), ) while preserving newlines.]] - rationale - graphify/extractors/pascal.py
- [[_add_edge()]] - code - graphify/mcp_ingest.py
- [[_add_node()]] - code - graphify/mcp_ingest.py
- [[_detect_package_from_args()]] - code - graphify/mcp_ingest.py
- [[_emit_server()]] - code - graphify/mcp_ingest.py
- [[_extract_pascal_regex()]] - code - graphify/extractors/pascal.py
- [[_extract_spock_fallback()]] - code - graphify/extract.py
- [[_pascal_find_body()]] - code - graphify/extractors/pascal.py
- [[_pascal_split_bases()]] - code - graphify/extractors/pascal.py
- [[_pascal_split_sections()]] - code - graphify/extractors/pascal.py
- [[_pascal_split_uses()]] - code - graphify/extractors/pascal.py
- [[_pascal_strip_comments()]] - code - graphify/extractors/pascal.py
- [[_resolve_pascal_callee_factory()]] - code - graphify/extractors/pascal.py
- [[_strip_version()]] - code - graphify/mcp_ingest.py
- [[mcp_ingest.py]] - code - graphify/mcp_ingest.py
- [[mcp_ingest.py — Extract MCP (Model Context Protocol) server configuration files.]] - rationale - graphify/mcp_ingest.py
- [[pascal — moved verbatim from graphifyextract.py.]] - rationale - graphify/extractors/pascal.py
- [[pascal.py]] - code - graphify/extractors/pascal.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_extract_pascal_regex
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_extract.py]]
- 12 edges to [[_COMMUNITY__read_text]]
- 6 edges to [[_COMMUNITY_test_mcp_ingest.py]]
- 5 edges to [[_COMMUNITY_test_pascal.py]]
- 4 edges to [[_COMMUNITY_make_id]]
- 2 edges to [[_COMMUNITY_test_security.py]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_test_languages.py]]
- 1 edge to [[_COMMUNITY_test_pascal_call_scoping.py]]
- 1 edge to [[_COMMUNITY_extract_terraform]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_run_language_resolvers]]

## Top bridge nodes
- [[mcp_ingest.py]] - degree 17, connects to 6 communities
- [[_extract_pascal_regex()]] - degree 19, connects to 4 communities
- [[_add_node()]] - degree 10, connects to 4 communities
- [[_extract_spock_fallback()]] - degree 8, connects to 4 communities
- [[pascal.py]] - degree 17, connects to 3 communities