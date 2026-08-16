---
type: community
cohesion: 0.12
members: 25
---

# to_json

**Cohesion:** 0.12 - loosely connected
**Members:** 25 nodes

## Members
- [[479 refuse to silently overwrite an existing graph with fewer nodes.]] - rationale - tests/test_export.py
- [[A non-empty but unparseable existing graph.json (corrupt or mid-write)     must]] - rationale - tests/test_export.py
- [[An emptywhitespace existing file has no nodes to lose, so it is not a     shrin]] - rationale - tests/test_export.py
- [[Edges lacking confidence_score get sensible defaults in to_json.]] - rationale - tests/test_confidence.py
- [[End-to-end pipeline test detect → extract → build → cluster → analyze → report]] - rationale - tests/test_pipeline.py
- [[Path_89]] - code
- [[Run the full pipeline on the fixtures directory. Returns a dict of outputs.]] - rationale - tests/test_pipeline.py
- [[Second run on unchanged corpus should produce identical nodeedge counts.]] - rationale - tests/test_pipeline.py
- [[_mkG()]] - code - tests/test_export.py
- [[_strip_diacritics()]] - code - graphify/export.py
- [[run_pipeline()]] - code - tests/test_pipeline.py
- [[test_pipeline.py]] - code - tests/test_pipeline.py
- [[test_pipeline_all_nodes_have_community()]] - code - tests/test_pipeline.py
- [[test_pipeline_detection_finds_code_and_docs()]] - code - tests/test_pipeline.py
- [[test_pipeline_extraction_confidence_labels()]] - code - tests/test_pipeline.py
- [[test_pipeline_graph_has_edges()]] - code - tests/test_pipeline.py
- [[test_pipeline_incremental_update()]] - code - tests/test_pipeline.py
- [[test_pipeline_no_self_loops()]] - code - tests/test_pipeline.py
- [[test_pipeline_report_mentions_top_god_node()]] - code - tests/test_pipeline.py
- [[test_pipeline_runs_end_to_end()]] - code - tests/test_pipeline.py
- [[test_to_json_defaults_missing_confidence_score()]] - code - tests/test_confidence.py
- [[test_to_json_fails_safe_on_corrupt_existing()]] - code - tests/test_export.py
- [[test_to_json_proceeds_on_empty_existing()]] - code - tests/test_export.py
- [[test_to_json_refuses_shrink()]] - code - tests/test_export.py
- [[to_json()]] - code - graphify/export.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/to_json
SORT file.name ASC
```

## Connections to other communities
- 13 edges to [[_COMMUNITY_test_export.py]]
- 11 edges to [[_COMMUNITY_generate]]
- 10 edges to [[_COMMUNITY_build_from_json]]
- 6 edges to [[_COMMUNITY_export.py]]
- 6 edges to [[_COMMUNITY_cli.py]]
- 3 edges to [[_COMMUNITY_paths.py]]
- 3 edges to [[_COMMUNITY_test_cross_extension_reexport_self_cycle.py]]
- 2 edges to [[_COMMUNITY_test_analyze.py]]
- 2 edges to [[_COMMUNITY_graphifybuild.py]]
- 2 edges to [[_COMMUNITY_test_detect.py]]
- 2 edges to [[_COMMUNITY_test_cli_export.py]]
- 2 edges to [[_COMMUNITY_to_obsidian]]
- 2 edges to [[_COMMUNITY_extract]]
- 1 edge to [[_COMMUNITY_graphifycluster.py]]
- 1 edge to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY_test_security.py]]
- 1 edge to [[_COMMUNITY_test_reflect.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_test_extract.py]]

## Top bridge nodes
- [[test_pipeline.py]] - degree 29, connects to 14 communities
- [[to_json()]] - degree 40, connects to 11 communities
- [[run_pipeline()]] - degree 23, connects to 8 communities
- [[test_to_json_defaults_missing_confidence_score()]] - degree 5, connects to 3 communities
- [[_mkG()]] - degree 4, connects to 1 community