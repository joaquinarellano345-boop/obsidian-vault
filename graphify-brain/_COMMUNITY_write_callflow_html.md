---
type: community
cohesion: 0.09
members: 29
---

# write_callflow_html

**Cohesion:** 0.09 - loosely connected
**Members:** 29 nodes

## Members
- [[.__init__()_2]] - code - graphify/callflow_html.py
- [[CallflowOptions]] - code - graphify/callflow_html.py
- [[Classify edges as intra-section or inter-section.      Returns         {]] - rationale - graphify/callflow_html.py
- [[Create a conservative filename stem from a project name.]] - rationale - graphify/callflow_html.py
- [[Generate call-flow architecture HTML from graphify output files.]] - rationale - graphify/callflow_html.py
- [[Infer a display project name when graph metadata does not include one.]] - rationale - graphify/callflow_html.py
- [[Keep generated HTML comments well-formed.]] - rationale - graphify/callflow_html.py
- [[Load GRAPH_REPORT.md if it exists.]] - rationale - graphify/callflow_html.py
- [[Load community labels from .graphify_labels.json, tolerating wrapper keys.]] - rationale - graphify/callflow_html.py
- [[Load section definitions from JSON file.]] - rationale - graphify/callflow_html.py
- [[Map section_id - list of nodes belonging to its communities.]] - rationale - graphify/callflow_html.py
- [[Options for call-flow architecture HTML generation.]] - rationale - graphify/callflow_html.py
- [[Path_4]] - code
- [[Read JSON with a useful error message.]] - rationale - graphify/callflow_html.py
- [[Resolve auto language from labels and node names.]] - rationale - graphify/callflow_html.py
- [[Resolve project root, graphify output dir, and optional files.]] - rationale - graphify/callflow_html.py
- [[build_section_node_map()]] - code - graphify/callflow_html.py
- [[classify_edges()]] - code - graphify/callflow_html.py
- [[detect_lang()]] - code - graphify/callflow_html.py
- [[html_comment_text()]] - code - graphify/callflow_html.py
- [[infer_project_name()]] - code - graphify/callflow_html.py
- [[load_labels()]] - code - graphify/callflow_html.py
- [[load_report()]] - code - graphify/callflow_html.py
- [[load_sections()]] - code - graphify/callflow_html.py
- [[main()_1]] - code - graphify/callflow_html.py
- [[read_json()]] - code - graphify/callflow_html.py
- [[resolve_graphify_paths()]] - code - graphify/callflow_html.py
- [[safe_filename()]] - code - graphify/callflow_html.py
- [[write_callflow_html()]] - code - graphify/callflow_html.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/write_callflow_html
SORT file.name ASC
```

## Connections to other communities
- 17 edges to [[_COMMUNITY_callflow_html.py]]
- 5 edges to [[_COMMUNITY_load_graph]]
- 5 edges to [[_COMMUNITY_pick_text]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 3 edges to [[_COMMUNITY_generate_section_flowchart]]
- 2 edges to [[_COMMUNITY_first_present]]
- 1 edge to [[_COMMUNITY_humanize_label]]
- 1 edge to [[_COMMUNITY_normalize_sections]]
- 1 edge to [[_COMMUNITY_Counter]]

## Top bridge nodes
- [[write_callflow_html()]] - degree 34, connects to 7 communities
- [[Path_4]] - degree 12, connects to 4 communities
- [[load_labels()]] - degree 6, connects to 2 communities
- [[read_json()]] - degree 6, connects to 2 communities
- [[load_sections()]] - degree 5, connects to 1 community