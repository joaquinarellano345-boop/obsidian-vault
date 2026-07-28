---
type: community
cohesion: 0.12
members: 33
---

# test_querylog.py

**Cohesion:** 0.12 - loosely connected
**Members:** 33 nodes

## Members
- [[Any_7]] - code
- [[Append one JSONL record to the query log. Never raises.]] - rationale - graphify/querylog.py
- [[End-to-end with no opt-in, log_query must not create the default log.]] - rationale - tests/test_querylog.py
- [[Path_48]] - code
- [[Query logging for graphify — append-only JSONL, fail-silent.]] - rationale - graphify/querylog.py
- [[Tests for graphify.querylog.]] - rationale - tests/test_querylog.py
- [[_clear_log_env()]] - code - tests/test_querylog.py
- [[_log_path()]] - code - graphify/querylog.py
- [[_log_responses()]] - code - graphify/querylog.py
- [[log_query()]] - code - graphify/querylog.py
- [[nodes_from_result()]] - code - graphify/querylog.py
- [[querylog.py]] - code - graphify/querylog.py
- [[test_disable_env()]] - code - tests/test_querylog.py
- [[test_disable_env_true()]] - code - tests/test_querylog.py
- [[test_explicit_nodes_returned_takes_precedence()]] - code - tests/test_querylog.py
- [[test_kind_mcp_query()]] - code - tests/test_querylog.py
- [[test_log_creates_parent_dirs()]] - code - tests/test_querylog.py
- [[test_log_never_raises()]] - code - tests/test_querylog.py
- [[test_log_query_appends()]] - code - tests/test_querylog.py
- [[test_log_query_writes_jsonl()]] - code - tests/test_querylog.py
- [[test_log_query_writes_nothing_by_default()]] - code - tests/test_querylog.py
- [[test_nodes_from_result_empty()]] - code - tests/test_querylog.py
- [[test_nodes_from_result_missing()]] - code - tests/test_querylog.py
- [[test_nodes_from_result_parses_header()]] - code - tests/test_querylog.py
- [[test_nodes_from_result_singular()]] - code - tests/test_querylog.py
- [[test_nodes_returned_inferred_from_result()]] - code - tests/test_querylog.py
- [[test_query_log_disable_wins()]] - code - tests/test_querylog.py
- [[test_query_log_enabled_by_explicit_flag()]] - code - tests/test_querylog.py
- [[test_query_log_enabled_by_explicit_path()]] - code - tests/test_querylog.py
- [[test_query_log_off_by_default()]] - code - tests/test_querylog.py
- [[test_querylog.py]] - code - tests/test_querylog.py
- [[test_responses_not_logged_by_default()]] - code - tests/test_querylog.py
- [[test_responses_optin()]] - code - tests/test_querylog.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_querylogpy
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_cli.py]]
- 1 edge to [[_COMMUNITY_serve.py]]

## Top bridge nodes
- [[querylog.py]] - degree 8, connects to 2 communities
- [[log_query()]] - degree 20, connects to 1 community