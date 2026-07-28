---
type: community
cohesion: 0.10
members: 20
---

# _run

**Cohesion:** 0.10 - loosely connected
**Members:** 20 nodes

## Members
- [[--answer-file lets callers pass a longmultiline answer via a file instead     o]] - rationale - tests/test_reflect.py
- [[A label refresh changes LESSONS.md topic headings, so --if-stale must rebuild.]] - rationale - tests/test_reflect.py
- [[CompletedProcess_2]] - code
- [[First run with no graphify-outmemory still succeeds and writes a valid doc.]] - rationale - tests/test_reflect.py
- [[Neither --answer nor --answer-file - clean argparse error, not a crash.]] - rationale - tests/test_reflect.py
- [[Through reflect()CLI with a real graph.json a cited node that isn't in the]] - rationale - tests/test_reflect.py
- [[With a real graph.json present, reflect auto-detects it and groups lessons     u]] - rationale - tests/test_reflect.py
- [[_run()_11]] - code - tests/test_reflect.py
- [[`reflect --if-stale` skips the rebuild when LESSONS.md is already current,     a]] - rationale - tests/test_reflect.py
- [[argparse `choices` rejects an unknown outcome before save_query_result runs.]] - rationale - tests/test_reflect.py
- [[test_cli_node_existence_gate_drops_stale_node_end_to_end()]] - code - tests/test_reflect.py
- [[test_cli_reflect_cold_start_writes_empty_lessons()]] - code - tests/test_reflect.py
- [[test_cli_reflect_end_to_end()]] - code - tests/test_reflect.py
- [[test_cli_reflect_groups_by_community_when_graph_present()]] - code - tests/test_reflect.py
- [[test_cli_reflect_if_stale_reruns_when_labels_newer()]] - code - tests/test_reflect.py
- [[test_cli_reflect_if_stale_skips_when_fresh()]] - code - tests/test_reflect.py
- [[test_cli_reflect_respects_out_flag()]] - code - tests/test_reflect.py
- [[test_cli_save_result_reads_answer_from_file()]] - code - tests/test_reflect.py
- [[test_cli_save_result_rejects_bad_outcome()]] - code - tests/test_reflect.py
- [[test_cli_save_result_requires_answer_or_answer_file()]] - code - tests/test_reflect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_run
SORT file.name ASC
```

## Connections to other communities
- 11 edges to [[_COMMUNITY_test_reflect.py]]
- 4 edges to [[_COMMUNITY_test_analyze.py]]
- 1 edge to [[_COMMUNITY__write_raw_doc]]

## Top bridge nodes
- [[_run()_11]] - degree 13, connects to 2 communities
- [[test_cli_node_existence_gate_drops_stale_node_end_to_end()]] - degree 4, connects to 2 communities
- [[test_cli_reflect_groups_by_community_when_graph_present()]] - degree 4, connects to 2 communities
- [[test_cli_reflect_if_stale_reruns_when_labels_newer()]] - degree 4, connects to 2 communities
- [[test_cli_reflect_if_stale_skips_when_fresh()]] - degree 4, connects to 2 communities