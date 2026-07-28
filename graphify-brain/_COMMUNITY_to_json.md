---
type: community
cohesion: 0.06
members: 43
---

# to_json

**Cohesion:** 0.06 - loosely connected
**Members:** 43 nodes

## Members
- [[479 refuse to silently overwrite an existing graph with fewer nodes.]] - rationale - tests/test_export.py
- [[A non-empty but unparseable existing graph.json (corrupt or mid-write)     must]] - rationale - tests/test_export.py
- [[Alias normalization must run BEFORE the semantic id-remap loop so a     `members]] - rationale - tests/test_hypergraph.py
- [[An emptywhitespace existing file has no nodes to lose, so it is not a     shrin]] - rationale - tests/test_export.py
- [[Edges lacking confidence_score get sensible defaults in to_json.]] - rationale - tests/test_confidence.py
- [[Return the current git HEAD commit hash, or None if not in a git repo.]] - rationale - graphify/export.py
- [[Store hyperedges in the graph's metadata dict.]] - rationale - graphify/export.py
- [[Tests for hyperedge support in graphify.]] - rationale - tests/test_hypergraph.py
- [[Three hyperedges, one per member-key spelling nodes  members  node_ids.]] - rationale - tests/test_hypergraph.py
- [[Write graph.json then reload it - hyperedges must survive.]] - rationale - tests/test_hypergraph.py
- [[_alias_extraction()]] - code - tests/test_hypergraph.py
- [[_git_head()]] - code - graphify/export.py
- [[_make_report()]] - code - tests/test_hypergraph.py
- [[_mkG()]] - code - tests/test_export.py
- [[_strip_diacritics()]] - code - graphify/export.py
- [[attach_hyperedges()]] - code - graphify/export.py
- [[build_from_json(root=...) must relativize hyperedge source_file like it     alre]] - rationale - tests/test_hypergraph.py
- [[test_attach_hyperedges_adds_new()]] - code - tests/test_hypergraph.py
- [[test_attach_hyperedges_deduplicates()]] - code - tests/test_hypergraph.py
- [[test_attach_hyperedges_multiple_different_ids()]] - code - tests/test_hypergraph.py
- [[test_attach_hyperedges_skips_entry_without_id()]] - code - tests/test_hypergraph.py
- [[test_build_canonical_nodes_wins_over_alias()]] - code - tests/test_hypergraph.py
- [[test_build_dedups_alias_members_preserving_order()]] - code - tests/test_hypergraph.py
- [[test_build_from_json_missing_hyperedges_key()]] - code - tests/test_hypergraph.py
- [[test_build_from_json_no_hyperedges()]] - code - tests/test_hypergraph.py
- [[test_build_from_json_relativizes_hyperedge_source_file()]] - code - tests/test_hypergraph.py
- [[test_build_from_json_stores_hyperedges()]] - code - tests/test_hypergraph.py
- [[test_build_normalizes_member_aliases_to_nodes()]] - code - tests/test_hypergraph.py
- [[test_build_rekeys_alias_keyed_hyperedge_members()]] - code - tests/test_hypergraph.py
- [[test_build_warns_once_per_aliased_hyperedge()]] - code - tests/test_hypergraph.py
- [[test_hyperedges_roundtrip_via_json_file()]] - code - tests/test_hypergraph.py
- [[test_hypergraph.py]] - code - tests/test_hypergraph.py
- [[test_report_includes_hyperedge_node_list()]] - code - tests/test_hypergraph.py
- [[test_report_includes_hyperedges_section()]] - code - tests/test_hypergraph.py
- [[test_report_skips_hyperedges_section_when_empty()]] - code - tests/test_hypergraph.py
- [[test_report_skips_hyperedges_section_when_key_missing()]] - code - tests/test_hypergraph.py
- [[test_to_json_defaults_missing_confidence_score()]] - code - tests/test_confidence.py
- [[test_to_json_fails_safe_on_corrupt_existing()]] - code - tests/test_export.py
- [[test_to_json_hyperedges_empty_when_none()]] - code - tests/test_hypergraph.py
- [[test_to_json_includes_hyperedges()]] - code - tests/test_hypergraph.py
- [[test_to_json_proceeds_on_empty_existing()]] - code - tests/test_export.py
- [[test_to_json_refuses_shrink()]] - code - tests/test_export.py
- [[to_json()]] - code - graphify/export.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/to_json
SORT file.name ASC
```

## Connections to other communities
- 21 edges to [[_COMMUNITY_build_from_json]]
- 9 edges to [[_COMMUNITY_test_export.py]]
- 7 edges to [[_COMMUNITY_export.py]]
- 6 edges to [[_COMMUNITY_generate]]
- 5 edges to [[_COMMUNITY_cli.py]]
- 3 edges to [[_COMMUNITY_graphifybuild.py]]
- 3 edges to [[_COMMUNITY_paths.py]]
- 3 edges to [[_COMMUNITY_test_cross_extension_reexport_self_cycle.py]]
- 2 edges to [[_COMMUNITY__rebuild_code]]
- 2 edges to [[_COMMUNITY_test_cli_export.py]]
- 2 edges to [[_COMMUNITY_test_pipeline.py]]
- 1 edge to [[_COMMUNITY_extract_js]]
- 1 edge to [[_COMMUNITY_test_reflect.py]]
- 1 edge to [[_COMMUNITY_test_analyze.py]]

## Top bridge nodes
- [[to_json()]] - degree 40, connects to 13 communities
- [[test_hypergraph.py]] - degree 30, connects to 4 communities
- [[test_to_json_defaults_missing_confidence_score()]] - degree 5, connects to 3 communities
- [[attach_hyperedges()]] - degree 9, connects to 2 communities
- [[_git_head()]] - degree 5, connects to 2 communities