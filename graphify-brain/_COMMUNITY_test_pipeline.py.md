---
type: community
cohesion: 0.23
members: 14
---

# test_pipeline.py

**Cohesion:** 0.23 - loosely connected
**Members:** 14 nodes

## Members
- [[End-to-end pipeline test detect → extract → build → cluster → analyze → report]] - rationale - tests/test_pipeline.py
- [[Path_89]] - code
- [[Run the full pipeline on the fixtures directory. Returns a dict of outputs.]] - rationale - tests/test_pipeline.py
- [[Second run on unchanged corpus should produce identical nodeedge counts.]] - rationale - tests/test_pipeline.py
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

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_pipelinepy
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_test_analyze.py]]
- 5 edges to [[_COMMUNITY_generate]]
- 3 edges to [[_COMMUNITY_test_export.py]]
- 3 edges to [[_COMMUNITY_export.py]]
- 2 edges to [[_COMMUNITY__rebuild_code]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_test_detect.py]]
- 2 edges to [[_COMMUNITY_to_json]]
- 2 edges to [[_COMMUNITY_extract]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_graphifycluster.py]]
- 1 edge to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_test_extract.py]]

## Top bridge nodes
- [[test_pipeline.py]] - degree 29, connects to 14 communities
- [[run_pipeline()]] - degree 23, connects to 9 communities