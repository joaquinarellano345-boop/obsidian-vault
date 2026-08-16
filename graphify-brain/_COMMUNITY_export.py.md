---
type: community
cohesion: 0.06
members: 44
---

# export.py

**Cohesion:** 0.06 - loosely connected
**Members:** 44 nodes

## Members
- [[IMPORTANT resolve endpoints using source_file only; never infer from labelid]] - rationale - graphify/analyze.py
- [[Cap a filename stem to ``limit`` UTF-8 bytes so it stays under the 255-byte]] - rationale - graphify/export.py
- [[Cross-file edges between real codedoc entities, ranked by a composite     surpr]] - rationale - graphify/analyze.py
- [[Escape a string for safe embedding in a Cypher single-quoted literal.      Handl]] - rationale - graphify/export.py
- [[Export graph as an SVG file using matplotlib + spring layout.      Lightweight a]] - rationale - graphify/export.py
- [[For single-source corpora find edges that bridge different communities.     The]] - rationale - graphify/analyze.py
- [[Graph analysis god nodes (most connected), surprising connections (cross-commun]] - rationale - graphify/analyze.py
- [[Invert communities dict node_id - community_id.]] - rationale - graphify/analyze.py
- [[Push graph directly to a running FalkorDB instance via the Python SDK.      Requ]] - rationale - graphify/exporters/graphdb.py
- [[Push graph directly to a running Neo4j instance via the Python driver.      Requ]] - rationale - graphify/exporters/graphdb.py
- [[Remove edges whose source or target node is not in the node set.      Returns th]] - rationale - graphify/export.py
- [[Return True if this node is a manually-injected semantic concept node     rather]] - rationale - graphify/analyze.py
- [[Return True if two source files belong to different language families.]] - rationale - graphify/analyze.py
- [[Return the current git HEAD commit hash, or None if not in a git repo.]] - rationale - graphify/export.py
- [[Return the first path component - used to detect cross-repo edges.]] - rationale - graphify/analyze.py
- [[Sanitise a value used in identifier position (node label  rel type).      Cyphe]] - rationale - graphify/export.py
- [[Shared constantshelpers for the graphify exporters package.  Symbols used by mo]] - rationale - graphify/exporters/base.py
- [[_cap_filename()]] - code - graphify/export.py
- [[_cross_community_surprises()]] - code - graphify/analyze.py
- [[_cross_file_surprises()]] - code - graphify/analyze.py
- [[_cross_language()]] - code - graphify/analyze.py
- [[_cypher_escape()]] - code - graphify/export.py
- [[_cypher_label()]] - code - graphify/export.py
- [[_git_head()]] - code - graphify/export.py
- [[_html_script()]] - code - graphify/exporters/html.py
- [[_html_styles()]] - code - graphify/exporters/html.py
- [[_hyperedge_script()]] - code - graphify/exporters/html.py
- [[_is_concept_node()]] - code - graphify/analyze.py
- [[_node_community_map()]] - code - graphify/analyze.py
- [[_top_level_dir()]] - code - graphify/analyze.py
- [[export.py]] - code - graphify/export.py
- [[exportersbase.py]] - code - graphify/exporters/base.py
- [[graphdb — moved verbatim from graphifyexport.py.]] - rationale - graphify/exporters/graphdb.py
- [[graphdb.py]] - code - graphify/exporters/graphdb.py
- [[graphifyanalyze.py]] - code - graphify/analyze.py
- [[html — moved verbatim from graphifyexport.py.]] - rationale - graphify/exporters/html.py
- [[html.py]] - code - graphify/exporters/html.py
- [[prune_dangling_edges()]] - code - graphify/export.py
- [[push_to_falkordb()]] - code - graphify/exporters/graphdb.py
- [[push_to_neo4j()]] - code - graphify/exporters/graphdb.py
- [[test_is_concept_node_empty_source()]] - code - tests/test_analyze.py
- [[test_is_concept_node_real_file()]] - code - tests/test_analyze.py
- [[to_cypher()]] - code - graphify/export.py
- [[to_svg()]] - code - graphify/export.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/exportpy
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_test_export.py]]
- 11 edges to [[_COMMUNITY_test_analyze.py]]
- 11 edges to [[_COMMUNITY_cli.py]]
- 10 edges to [[_COMMUNITY_generate]]
- 7 edges to [[_COMMUNITY_to_obsidian]]
- 6 edges to [[_COMMUNITY_to_json]]
- 5 edges to [[_COMMUNITY__surprise_score]]
- 5 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_graphifybuild.py]]
- 2 edges to [[_COMMUNITY_test_file_label_disambiguation.py]]
- 2 edges to [[_COMMUNITY_security.py]]
- 2 edges to [[_COMMUNITY_sanitize_label]]
- 2 edges to [[_COMMUNITY_test_falkordb_integration.py]]
- 1 edge to [[_COMMUNITY_test_cluster.py]]
- 1 edge to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY_test_swift_builtin_noise.py]]
- 1 edge to [[_COMMUNITY_callflow_html.py]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_test_security.py]]
- 1 edge to [[_COMMUNITY_test_cross_extension_reexport_self_cycle.py]]
- 1 edge to [[_COMMUNITY_reflect.py]]
- 1 edge to [[_COMMUNITY_CsharpNameResolver]]

## Top bridge nodes
- [[export.py]] - degree 39, connects to 12 communities
- [[graphifyanalyze.py]] - degree 31, connects to 11 communities
- [[html.py]] - degree 16, connects to 8 communities
- [[_node_community_map()]] - degree 15, connects to 4 communities
- [[_is_concept_node()]] - degree 10, connects to 3 communities