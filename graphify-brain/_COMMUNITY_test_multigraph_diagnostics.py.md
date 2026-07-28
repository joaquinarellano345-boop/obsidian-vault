---
type: community
cohesion: 0.08
members: 61
---

# test_multigraph_diagnostics.py

**Cohesion:** 0.08 - loosely connected
**Members:** 61 nodes

## Members
- [[Any_1]] - code
- [[Corrupt graph.json produces an actionable error, not a raw traceback (1536153]] - rationale - tests/test_corrupt_graph_json.py
- [[Counter_1]] - code
- [[Diagnose a graphextraction JSON file without mutating it.      When `directed`]] - rationale - graphify/diagnostics.py
- [[Find likely `seen_` producer-suppression sets in an extractor file.]] - rationale - graphify/diagnostics.py
- [[Happy path unchanged a well-formed graph.json loads without raising.]] - rationale - tests/test_corrupt_graph_json.py
- [[Path_8]] - code
- [[Path_84]] - code
- [[Read a JSON graph after applying Graphify's graph-load size cap.]] - rationale - graphify/diagnostics.py
- [[Read-only diagnostics for MultiDiGraph readiness.]] - rationale - graphify/diagnostics.py
- [[Summarize same-endpoint edge-collapse risk for one JSON graphextraction dict.]] - rationale - graphify/diagnostics.py
- [[_canonical_edge()]] - code - graphify/diagnostics.py
- [[_corrupt()]] - code - tests/test_corrupt_graph_json.py
- [[_count_extra()]] - code - graphify/diagnostics.py
- [[_diagnostic_fixture()]] - code - tests/test_multigraph_diagnostics.py
- [[_edge_list()]] - code - graphify/diagnostics.py
- [[_exact_signature()]] - code - graphify/diagnostics.py
- [[_node_ids()]] - code - graphify/diagnostics.py
- [[_read_json_file()]] - code - graphify/diagnostics.py
- [[_safe_text()]] - code - graphify/diagnostics.py
- [[_tuple_arity_from_annotation()]] - code - graphify/diagnostics.py
- [[_variant_group_count()]] - code - graphify/diagnostics.py
- [[diagnose_extraction()]] - code - graphify/diagnostics.py
- [[diagnose_file()]] - code - graphify/diagnostics.py
- [[diagnostics.py]] - code - graphify/diagnostics.py
- [[format_diagnostic_json()]] - code - graphify/diagnostics.py
- [[format_diagnostic_report()]] - code - graphify/diagnostics.py
- [[load_graph()]] - code - graphify/affected.py
- [[parametrize_15]] - code
- [[scan_producer_suppression_sites()]] - code - graphify/diagnostics.py
- [[test_affected_load_graph_corrupt_raises_runtimeerror()]] - code - tests/test_corrupt_graph_json.py
- [[test_build_merge_corrupt_graph_raises_runtimeerror()]] - code - tests/test_corrupt_graph_json.py
- [[test_corrupt_graph_json.py]] - code - tests/test_corrupt_graph_json.py
- [[test_diagnose_extraction_accepts_node_link_links_key()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_extraction_bounds_examples()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_extraction_categorizes_same_endpoint_collapse()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_extraction_defaults_raw_inputs_to_directed()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_extraction_does_not_mutate_input()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_extraction_handles_malformed_shapes_without_crashing()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_extraction_handles_non_list_nodes_and_edges()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_extraction_stops_examples_at_requested_limit()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_file_defaults_to_json_directed_flag()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_file_explicit_directed_override()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_file_reads_json_and_formats_report()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_file_rejects_non_object_json()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_file_rejects_oversized_graph()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_multigraph_cli_human_output()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_multigraph_cli_json_output()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_multigraph_cli_max_examples_zero()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_multigraph_cli_rejects_conflicting_direction_flags()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_multigraph_cli_undirected_override()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnose_multigraph_cli_usage_errors()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnostic_json_report_is_serializable()]] - code - tests/test_multigraph_diagnostics.py
- [[test_diagnostics_read_corrupt_raises_runtimeerror()]] - code - tests/test_corrupt_graph_json.py
- [[test_diagnostics_reports_unverified_node_count()]] - code - tests/test_evidence_binding.py
- [[test_format_diagnostic_report_includes_build_and_suppression_errors()]] - code - tests/test_multigraph_diagnostics.py
- [[test_multigraph_diagnostics.py]] - code - tests/test_multigraph_diagnostics.py
- [[test_scan_producer_suppression_sites_finds_seen_sets()]] - code - tests/test_multigraph_diagnostics.py
- [[test_scan_producer_suppression_sites_handles_unknown_tuple_arity()]] - code - tests/test_multigraph_diagnostics.py
- [[test_scan_producer_suppression_sites_reports_missing_file()]] - code - tests/test_multigraph_diagnostics.py
- [[test_valid_graph_still_loads()]] - code - tests/test_corrupt_graph_json.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_multigraph_diagnosticspy
SORT file.name ASC
```

## Connections to other communities
- 10 edges to [[_COMMUNITY_cli.py]]
- 6 edges to [[_COMMUNITY_test_install.py]]
- 4 edges to [[_COMMUNITY_graphifybuild.py]]
- 3 edges to [[_COMMUNITY_affected.py]]
- 3 edges to [[_COMMUNITY_test_evidence_binding.py]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY_graphify__main__.py]]

## Top bridge nodes
- [[diagnose_extraction()]] - degree 25, connects to 2 communities
- [[diagnostics.py]] - degree 19, connects to 2 communities
- [[test_corrupt_graph_json.py]] - degree 12, connects to 2 communities
- [[format_diagnostic_report()]] - degree 9, connects to 2 communities
- [[load_graph()]] - degree 7, connects to 2 communities