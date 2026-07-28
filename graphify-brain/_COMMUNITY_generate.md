---
type: community
cohesion: 0.10
members: 43
---

# generate

**Cohesion:** 0.10 - loosely connected
**Members:** 43 nodes

## Members
- [[AMBIGUOUS edges must have confidence_score = 0.4.]] - rationale - tests/test_confidence.py
- [[Append the `` Work-memory lessons`` section, or nothing when empty.]] - rationale - graphify/report.py
- [[EXTRACTED edges must have confidence_score == 1.0.]] - rationale - tests/test_confidence.py
- [[INFERRED edges must have confidence_score between 0.0 and 1.0.]] - rationale - tests/test_confidence.py
- [[Mirrors export.safe_name so community hub filenames and report wikilinks always]] - rationale - graphify/report.py
- [[No learning input = no section; report identical to pre-feature.]] - rationale - tests/test_report.py
- [[Report summary line should include avg confidence for INFERRED edges.]] - rationale - tests/test_confidence.py
- [[Return True if this node is a file-level hub node (e.g. 'client', 'models')]] - rationale - graphify/analyze.py
- [[Return a minimal extraction dict with one edge of each confidence type.]] - rationale - tests/test_confidence.py
- [[Surprising connections section shows confidence score next to INFERRED edges.]] - rationale - tests/test_confidence.py
- [[Tests for confidence_score on edges.]] - rationale - tests/test_confidence.py
- [[When a work-memory overlay (preferred sources) and query-scoped dead-ends     ar]] - rationale - tests/test_report.py
- [[_is_file_node()]] - code - graphify/analyze.py
- [[_learning_section()]] - code - graphify/report.py
- [[_make_extraction()]] - code - tests/test_confidence.py
- [[_safe_community_name()]] - code - graphify/report.py
- [[confidence_score survives build_from_json → to_json → JSON parse round-trip.]] - rationale - tests/test_confidence.py
- [[generate()]] - code - graphify/report.py
- [[make_inputs()]] - code - tests/test_report.py
- [[report.py]] - code - graphify/report.py
- [[score_all()]] - code - graphify/cluster.py
- [[test_ambiguous_edges_score_at_most_04()]] - code - tests/test_confidence.py
- [[test_confidence.py]] - code - tests/test_confidence.py
- [[test_confidence_score_round_trip()]] - code - tests/test_confidence.py
- [[test_extracted_edges_have_score_1()]] - code - tests/test_confidence.py
- [[test_import_cycles_section_absent_for_documents_only_corpus()]] - code - tests/test_report.py
- [[test_import_cycles_section_present_for_code_corpus()]] - code - tests/test_report.py
- [[test_inferred_edges_score_in_range()]] - code - tests/test_confidence.py
- [[test_report.py]] - code - tests/test_report.py
- [[test_report_contains_ambiguous_section()]] - code - tests/test_report.py
- [[test_report_contains_communities()]] - code - tests/test_report.py
- [[test_report_contains_corpus_check()]] - code - tests/test_report.py
- [[test_report_contains_god_nodes()]] - code - tests/test_report.py
- [[test_report_contains_header()]] - code - tests/test_report.py
- [[test_report_contains_surprising_connections()]] - code - tests/test_report.py
- [[test_report_hubs_are_plain_text_by_default()]] - code - tests/test_report.py
- [[test_report_hubs_use_wikilinks_when_obsidian()]] - code - tests/test_report.py
- [[test_report_inferred_tag_with_score()]] - code - tests/test_confidence.py
- [[test_report_shows_avg_confidence_for_inferred()]] - code - tests/test_confidence.py
- [[test_report_shows_raw_cohesion_scores()]] - code - tests/test_report.py
- [[test_report_shows_token_cost()]] - code - tests/test_report.py
- [[test_report_work_memory_section_absent_without_overlay()]] - code - tests/test_report.py
- [[test_report_work_memory_section_present_with_overlay_and_dead_ends()]] - code - tests/test_report.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/generate
SORT file.name ASC
```

## Connections to other communities
- 22 edges to [[_COMMUNITY_test_analyze.py]]
- 10 edges to [[_COMMUNITY_build_from_json]]
- 7 edges to [[_COMMUNITY_test_export.py]]
- 6 edges to [[_COMMUNITY__rebuild_code]]
- 6 edges to [[_COMMUNITY_to_json]]
- 5 edges to [[_COMMUNITY_test_pipeline.py]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 4 edges to [[_COMMUNITY_test_semantic_similarity.py]]
- 3 edges to [[_COMMUNITY_graphifycluster.py]]
- 3 edges to [[_COMMUNITY_test_cluster.py]]
- 2 edges to [[_COMMUNITY_graphifybuild.py]]
- 2 edges to [[_COMMUNITY_test_cli_export.py]]
- 2 edges to [[_COMMUNITY_test_reflect.py]]
- 1 edge to [[_COMMUNITY_test_file_label_disambiguation.py]]
- 1 edge to [[_COMMUNITY_export.py]]
- 1 edge to [[_COMMUNITY_load_memory_docs]]
- 1 edge to [[_COMMUNITY_reflect.py]]

## Top bridge nodes
- [[score_all()]] - degree 20, connects to 8 communities
- [[report.py]] - degree 15, connects to 8 communities
- [[test_confidence.py]] - degree 21, connects to 7 communities
- [[generate()]] - degree 35, connects to 6 communities
- [[test_report.py]] - degree 25, connects to 5 communities