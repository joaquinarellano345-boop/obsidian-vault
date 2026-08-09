---
type: community
cohesion: 0.09
members: 29
---

# export.py

**Cohesion:** 0.09 - loosely connected
**Members:** 29 nodes

## Members
- [[Cap a filename stem to ``limit`` UTF-8 bytes so it stays under the 255-byte]] - rationale - graphify/export.py
- [[Escape a string for safe embedding in a Cypher single-quoted literal.      Handl]] - rationale - graphify/export.py
- [[Export graph as an SVG file using matplotlib + spring layout.      Lightweight a]] - rationale - graphify/export.py
- [[Invert communities dict node_id - community_id.]] - rationale - graphify/analyze.py
- [[Push graph directly to a running FalkorDB instance via the Python SDK.      Requ]] - rationale - graphify/exporters/graphdb.py
- [[Push graph directly to a running Neo4j instance via the Python driver.      Requ]] - rationale - graphify/exporters/graphdb.py
- [[Remove edges whose source or target node is not in the node set.      Returns th]] - rationale - graphify/export.py
- [[Return the current git HEAD commit hash, or None if not in a git repo.]] - rationale - graphify/export.py
- [[Sanitise a value used in identifier position (node label  rel type).      Cyphe]] - rationale - graphify/export.py
- [[Shared constantshelpers for the graphify exporters package.  Symbols used by mo]] - rationale - graphify/exporters/base.py
- [[_cap_filename()]] - code - graphify/export.py
- [[_cypher_escape()]] - code - graphify/export.py
- [[_cypher_label()]] - code - graphify/export.py
- [[_git_head()]] - code - graphify/export.py
- [[_html_script()]] - code - graphify/exporters/html.py
- [[_html_styles()]] - code - graphify/exporters/html.py
- [[_hyperedge_script()]] - code - graphify/exporters/html.py
- [[_node_community_map()]] - code - graphify/analyze.py
- [[export.py]] - code - graphify/export.py
- [[exportersbase.py]] - code - graphify/exporters/base.py
- [[graphdb — moved verbatim from graphifyexport.py.]] - rationale - graphify/exporters/graphdb.py
- [[graphdb.py]] - code - graphify/exporters/graphdb.py
- [[html — moved verbatim from graphifyexport.py.]] - rationale - graphify/exporters/html.py
- [[html.py]] - code - graphify/exporters/html.py
- [[prune_dangling_edges()]] - code - graphify/export.py
- [[push_to_falkordb()]] - code - graphify/exporters/graphdb.py
- [[push_to_neo4j()]] - code - graphify/exporters/graphdb.py
- [[to_cypher()]] - code - graphify/export.py
- [[to_svg()]] - code - graphify/export.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/exportpy
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_test_export.py]]
- 9 edges to [[_COMMUNITY_cli.py]]
- 7 edges to [[_COMMUNITY_to_obsidian]]
- 6 edges to [[_COMMUNITY_test_analyze.py]]
- 5 edges to [[_COMMUNITY_to_json]]
- 3 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_security.py]]
- 2 edges to [[_COMMUNITY_sanitize_label]]
- 2 edges to [[_COMMUNITY_test_falkordb_integration.py]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_callflow_html.py]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_test_security.py]]
- 1 edge to [[_COMMUNITY_generate]]
- 1 edge to [[_COMMUNITY_test_cross_extension_reexport_self_cycle.py]]
- 1 edge to [[_COMMUNITY_reflect.py]]
- 1 edge to [[_COMMUNITY_CsharpNameResolver]]
- 1 edge to [[_COMMUNITY_test_file_label_disambiguation.py]]

## Top bridge nodes
- [[export.py]] - degree 39, connects to 13 communities
- [[html.py]] - degree 16, connects to 9 communities
- [[_node_community_map()]] - degree 15, connects to 5 communities
- [[to_cypher()]] - degree 8, connects to 2 communities
- [[_git_head()]] - degree 5, connects to 2 communities