---
type: community
cohesion: 0.06
members: 46
---

# _surprise_score

**Cohesion:** 0.06 - loosely connected
**Members:** 46 nodes

## Members
- [[AMBIGUOUS edge should score higher than an otherwise identical EXTRACTED edge.]] - rationale - tests/test_analyze.py
- [[Code→doc INFERRED calls edge should score lower than same-language EXTRACTED.]] - rationale - tests/test_analyze.py
- [[Code↔paper INFERRED calls should still surface — it is a meaningful link.]] - rationale - tests/test_analyze.py
- [[Code↔paper edge should score higher than code↔code edge.]] - rationale - tests/test_analyze.py
- [[Cross-language INFERRED calls edge should score lower than same-language EXTRACT]] - rationale - tests/test_analyze.py
- [[Cross-language INFERRED uses edge (the exact rsl-siege-manager false positive) s]] - rationale - tests/test_analyze.py
- [[EXTRACTED code↔doc edges are real facts — must not be penalised.]] - rationale - tests/test_analyze.py
- [[EXTRACTED cross-language edges are real structural facts — must not be penalised]] - rationale - tests/test_analyze.py
- [[Graph with one semantically_similar_to edge and one references edge, both cross-]] - rationale - tests/test_semantic_similarity.py
- [[Helper Python node in backend, TypeScript node in frontend, different communi]] - rationale - tests/test_analyze.py
- [[INFERRED calls within the same language family must not be affected.]] - rationale - tests/test_analyze.py
- [[Non-semantic edges must not get the semantically similar tag.]] - rationale - tests/test_semantic_similarity.py
- [[Score how surprising a cross-file edge is. Returns (score, reasons).]] - rationale - graphify/analyze.py
- [[Tests for semantically_similar_to edge support.]] - rationale - tests/test_semantic_similarity.py
- [[Two nodes in separate files connected by a semantically_similar_to edge.]] - rationale - tests/test_semantic_similarity.py
- [[_make_code_doc_graph()]] - code - tests/test_analyze.py
- [[_make_cross_lang_graph()]] - code - tests/test_analyze.py
- [[_make_extraction_with_semantic_edge()]] - code - tests/test_semantic_similarity.py
- [[_make_graph_with_semantic_edge()]] - code - tests/test_semantic_similarity.py
- [[_make_report_with_semantic_surprise()]] - code - tests/test_semantic_similarity.py
- [[_make_two_edge_graph()]] - code - tests/test_semantic_similarity.py
- [[_surprise_score()]] - code - graphify/analyze.py
- [[`semantically_similar_to` across code↔doc is explicit LLM insight — must not be]] - rationale - tests/test_analyze.py
- [[`semantically_similar_to` across languages is a genuine insight — must not be su]] - rationale - tests/test_analyze.py
- [[test_code_doc_extracted_calls_not_suppressed()]] - code - tests/test_analyze.py
- [[test_code_doc_inferred_calls_suppressed()]] - code - tests/test_analyze.py
- [[test_code_doc_inferred_semantically_similar_not_suppressed()]] - code - tests/test_analyze.py
- [[test_code_doc_inferred_uses_suppressed()]] - code - tests/test_analyze.py
- [[test_code_paper_inferred_calls_not_suppressed()]] - code - tests/test_analyze.py
- [[test_cross_language_extracted_calls_not_suppressed()]] - code - tests/test_analyze.py
- [[test_cross_language_inferred_calls_suppressed()]] - code - tests/test_analyze.py
- [[test_cross_language_inferred_uses_suppressed()]] - code - tests/test_analyze.py
- [[test_cross_language_semantically_similar_not_suppressed()]] - code - tests/test_analyze.py
- [[test_report_no_semantic_tag_for_other_relations()]] - code - tests/test_semantic_similarity.py
- [[test_report_renders_semantically_similar_tag()]] - code - tests/test_semantic_similarity.py
- [[test_report_semantic_tag_on_correct_line()]] - code - tests/test_semantic_similarity.py
- [[test_same_language_inferred_calls_not_suppressed()]] - code - tests/test_analyze.py
- [[test_semantic_edge_confidence_score_preserved()]] - code - tests/test_semantic_similarity.py
- [[test_semantic_edge_nodes_present()]] - code - tests/test_semantic_similarity.py
- [[test_semantic_edge_reason_mentions_similarity()]] - code - tests/test_semantic_similarity.py
- [[test_semantic_edge_scores_higher_than_references()]] - code - tests/test_semantic_similarity.py
- [[test_semantic_edge_survives_build_from_json()]] - code - tests/test_semantic_similarity.py
- [[test_semantic_similarity.py]] - code - tests/test_semantic_similarity.py
- [[test_surprise_score_accepts_precomputed_degrees()]] - code - tests/test_analyze.py
- [[test_surprising_connections_ambiguous_scores_higher_than_extracted()]] - code - tests/test_analyze.py
- [[test_surprising_connections_cross_type_scores_higher()]] - code - tests/test_analyze.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_surprise_score
SORT file.name ASC
```

## Connections to other communities
- 19 edges to [[_COMMUNITY_test_analyze.py]]
- 5 edges to [[_COMMUNITY_export.py]]
- 4 edges to [[_COMMUNITY_generate]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]

## Top bridge nodes
- [[test_semantic_similarity.py]] - degree 20, connects to 5 communities
- [[_surprise_score()]] - degree 24, connects to 2 communities
- [[_make_graph_with_semantic_edge()]] - degree 7, connects to 1 community
- [[_make_cross_lang_graph()]] - degree 6, connects to 1 community
- [[_make_code_doc_graph()]] - degree 5, connects to 1 community