---
type: community
cohesion: 0.09
members: 50
---

# test_reflect.py

**Cohesion:** 0.09 - loosely connected
**Members:** 50 nodes

## Members
- [[A cited node no longer in the graph is dropped from lessons entirely.]] - rationale - tests/test_reflect.py
- [[A doc whose source nodes split evenly across communities lands in the     lexico]] - rationale - tests/test_reflect.py
- [[A fresh dead_end outweighs a stale useful (30d half-life), so the contested]] - rationale - tests/test_reflect.py
- [[A mixed-signal node appears in a single Contested line, not silently in both]] - rationale - tests/test_reflect.py
- [[A node cited twice within one doc counts as ONE corroborating result, so it]] - rationale - tests/test_reflect.py
- [[A node seen only in dead_end docs never appears as a source bucket entry, but]] - rationale - tests/test_reflect.py
- [[A same-date useful + dead_end on one node cancel to score 0 - 'evenly split'.]] - rationale - tests/test_reflect.py
- [[Aggregate parsed memory docs into a deterministic lessons structure.      ``now`]] - rationale - graphify/reflect.py
- [[Corroboration (k=2) + sign decide the bucket, not raw frequency     A is usefu]] - rationale - tests/test_reflect.py
- [[One save can't mint a 'preferred' lesson; a second distinct result promotes it.]] - rationale - tests/test_reflect.py
- [[Regression guard the LESSONS.md output must never be re-ingested as a memory]] - rationale - tests/test_reflect.py
- [[Render the aggregate into the deterministic LESSONS.md markdown body.]] - rationale - graphify/reflect.py
- [[Saving the same Q&A more than once must not duplicate lines in the dead-ends]] - rationale - tests/test_reflect.py
- [[Tests for `graphify reflect` and the work-memory reflection layer.  `graphify re]] - rationale - tests/test_reflect.py
- [[The header nudges verification, not blind reuse.]] - rationale - tests/test_reflect.py
- [[The headline guarantee identical memory contents + same `now` - byte-identica]] - rationale - tests/test_reflect.py
- [[Topic headers render alphabetically, with Uncategorized always last.]] - rationale - tests/test_reflect.py
- [[Two distinct useful results - preferred at k=2, but only tentative at k=3.]] - rationale - tests/test_reflect.py
- [[Two stale useful + one fresh dead_end a long half-life (≈no decay) lets the 2]] - rationale - tests/test_reflect.py
- [[_days_before()]] - code - tests/test_reflect.py
- [[_doc()_1]] - code - tests/test_reflect.py
- [[aggregate_lessons()]] - code - graphify/reflect.py
- [[half_life=0 turns decay off (full weight), so a stale useful and a fresh     de]] - rationale - tests/test_reflect.py
- [[render_lessons_md()]] - code - graphify/reflect.py
- [[test_aggregate_counts_each_outcome()]] - code - tests/test_reflect.py
- [[test_community_grouping_uses_plurality_community()]] - code - tests/test_reflect.py
- [[test_contested_node_renders_once_under_contested()]] - code - tests/test_reflect.py
- [[test_corroboration_counts_distinct_docs_not_citations()]] - code - tests/test_reflect.py
- [[test_corroboration_threshold_promotes_only_repeated_nodes()]] - code - tests/test_reflect.py
- [[test_dead_ends_and_corrections_collected()]] - code - tests/test_reflect.py
- [[test_dead_ends_and_corrections_dedupe_by_question()]] - code - tests/test_reflect.py
- [[test_doc_community_tie_breaks_to_smallest_label()]] - code - tests/test_reflect.py
- [[test_evenly_split_verdict_when_signals_cancel()]] - code - tests/test_reflect.py
- [[test_half_life_actually_feeds_decay()]] - code - tests/test_reflect.py
- [[test_header_is_cautious()]] - code - tests/test_reflect.py
- [[test_lessons_artifact_cannot_be_globbed_back_into_memory()]] - code - tests/test_reflect.py
- [[test_min_corroboration_is_honored_not_hardcoded()]] - code - tests/test_reflect.py
- [[test_negative_only_node_absent_from_sources()]] - code - tests/test_reflect.py
- [[test_no_community_grouping_without_graph()]] - code - tests/test_reflect.py
- [[test_node_existence_gate_drops_stale_nodes()]] - code - tests/test_reflect.py
- [[test_nonpositive_half_life_disables_decay()]] - code - tests/test_reflect.py
- [[test_recency_decides_contested_verdict()]] - code - tests/test_reflect.py
- [[test_reflect.py]] - code - tests/test_reflect.py
- [[test_render_byte_stable_across_independent_aggregations()]] - code - tests/test_reflect.py
- [[test_render_empty_memory_is_graceful()]] - code - tests/test_reflect.py
- [[test_render_has_summary_and_sections()]] - code - tests/test_reflect.py
- [[test_render_includes_by_topic_when_graph_present()]] - code - tests/test_reflect.py
- [[test_render_is_deterministic()]] - code - tests/test_reflect.py
- [[test_sources_split_into_preferred_tentative_contested()]] - code - tests/test_reflect.py
- [[test_topic_sections_alpha_with_uncategorized_last()]] - code - tests/test_reflect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_reflectpy
SORT file.name ASC
```

## Connections to other communities
- 19 edges to [[_COMMUNITY_reflect.py]]
- 11 edges to [[_COMMUNITY__write_raw_doc]]
- 11 edges to [[_COMMUNITY__run]]
- 8 edges to [[_COMMUNITY_load_memory_docs]]
- 6 edges to [[_COMMUNITY_parse_memory_doc]]
- 6 edges to [[_COMMUNITY_lessons_fresh]]
- 4 edges to [[_COMMUNITY_generate]]
- 4 edges to [[_COMMUNITY_save_query_result]]
- 1 edge to [[_COMMUNITY_test_analyze.py]]
- 1 edge to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY_test_export.py]]
- 1 edge to [[_COMMUNITY_to_json]]
- 1 edge to [[_COMMUNITY_ingest.py]]
- 1 edge to [[_COMMUNITY__doc_community]]
- 1 edge to [[_COMMUNITY_cli.py]]

## Top bridge nodes
- [[test_reflect.py]] - degree 84, connects to 13 communities
- [[aggregate_lessons()]] - degree 40, connects to 5 communities
- [[test_lessons_artifact_cannot_be_globbed_back_into_memory()]] - degree 8, connects to 3 communities
- [[test_render_byte_stable_across_independent_aggregations()]] - degree 6, connects to 2 communities
- [[render_lessons_md()]] - degree 16, connects to 1 community