---
type: community
cohesion: 0.15
members: 21
---

# save_query_result

**Cohesion:** 0.15 - loosely connected
**Members:** 21 nodes

## Members
- [[An outcome signal is written to both frontmatter (for `reflect`) and an      O]] - rationale - tests/test_ingest.py
- [[Backward compatible a result without an outcome looks exactly as before.]] - rationale - tests/test_ingest.py
- [[Save a Q&A result as markdown so it gets extracted into the graph on next --upda]] - rationale - graphify/ingest.py
- [[Tests for graphify.ingest.save_query_result]] - rationale - tests/test_ingest.py
- [[The issue's worked example session 1 records a win and a dead end; session 2]] - rationale - tests/test_reflect.py
- [[save_query_result()]] - code - graphify/ingest.py
- [[test_answer_in_body()]] - code - tests/test_ingest.py
- [[test_correction_in_frontmatter_and_body()]] - code - tests/test_ingest.py
- [[test_file_created()]] - code - tests/test_ingest.py
- [[test_filename_format()]] - code - tests/test_ingest.py
- [[test_frontmatter_question()]] - code - tests/test_ingest.py
- [[test_frontmatter_type()]] - code - tests/test_ingest.py
- [[test_ingest.py]] - code - tests/test_ingest.py
- [[test_invalid_outcome_rejected()]] - code - tests/test_ingest.py
- [[test_memory_dir_created()]] - code - tests/test_ingest.py
- [[test_no_outcome_means_no_outcome_section()]] - code - tests/test_ingest.py
- [[test_outcome_in_frontmatter_and_body()]] - code - tests/test_ingest.py
- [[test_reflect_writes_lessons_file()]] - code - tests/test_reflect.py
- [[test_second_session_benefits_from_the_first()]] - code - tests/test_reflect.py
- [[test_source_nodes_capped_at_10()]] - code - tests/test_ingest.py
- [[test_source_nodes_included()]] - code - tests/test_ingest.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/save_query_result
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_ingest.py]]
- 4 edges to [[_COMMUNITY_test_reflect.py]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_parse_memory_doc]]
- 2 edges to [[_COMMUNITY_reflect.py]]
- 1 edge to [[_COMMUNITY_load_memory_docs]]

## Top bridge nodes
- [[save_query_result()]] - degree 26, connects to 5 communities
- [[test_second_session_benefits_from_the_first()]] - degree 4, connects to 2 communities
- [[test_reflect_writes_lessons_file()]] - degree 3, connects to 2 communities
- [[test_ingest.py]] - degree 15, connects to 1 community