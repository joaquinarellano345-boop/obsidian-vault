---
type: community
cohesion: 0.17
members: 15
---

# load_graph

**Cohesion:** 0.17 - loosely connected
**Members:** 15 nodes

## Members
- [[F4 callflow_html.load_graph must refuse to read a graph.json that     exceeds]] - rationale - tests/test_callflow_html.py
- [[Load graph.json. Returns normalized (nodes, edges, hyperedges, metadata).]] - rationale - graphify/callflow_html.py
- [[Path_62]] - code
- [[Read current graphify graph.json via NetworkX's node-link parser.]] - rationale - graphify/callflow_html.py
- [[Return the first list from a set of possible schema locations.]] - rationale - graphify/callflow_html.py
- [[_make_graphify_out()]] - code - tests/test_callflow_html.py
- [[_node_link_payload()]] - code - graphify/callflow_html.py
- [[first_list()]] - code - graphify/callflow_html.py
- [[load_graph()_1]] - code - graphify/callflow_html.py
- [[test_callflow_html.py]] - code - tests/test_callflow_html.py
- [[test_derive_sections_groups_by_architecture_keywords()]] - code - tests/test_callflow_html.py
- [[test_export_callflow_html_cli_accepts_positional_graph_path()]] - code - tests/test_callflow_html.py
- [[test_export_callflow_html_cli_creates_file()]] - code - tests/test_callflow_html.py
- [[test_load_graph_rejects_oversized_file()]] - code - tests/test_callflow_html.py
- [[test_write_callflow_html_creates_file_and_uses_report()]] - code - tests/test_callflow_html.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/load_graph
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_callflow_html.py]]
- 5 edges to [[_COMMUNITY_write_callflow_html]]
- 2 edges to [[_COMMUNITY_first_present]]
- 2 edges to [[_COMMUNITY_cli.py]]

## Top bridge nodes
- [[load_graph()_1]] - degree 12, connects to 4 communities
- [[test_callflow_html.py]] - degree 10, connects to 2 communities
- [[_node_link_payload()]] - degree 4, connects to 2 communities
- [[first_list()]] - degree 3, connects to 1 community
- [[test_write_callflow_html_creates_file_and_uses_report()]] - degree 3, connects to 1 community