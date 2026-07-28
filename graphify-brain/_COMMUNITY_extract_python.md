---
type: community
cohesion: 0.07
members: 49
---

# extract_python

**Cohesion:** 0.07 - loosely connected
**Members:** 49 nodes

## Members
- [[NOTE must run before compile() or linker will fail]] - rationale - tests/test_rationale.py
- [[A file with a `revision` variable but no Alembic markers keeps its docstring.]] - rationale - tests/test_rationale.py
- [[AST-resolved call edges are deterministic and should be EXTRACTED1.0.]] - rationale - tests/test_extract.py
- [[All edge sources must reference a known node (targets may be external imports).]] - rationale - tests/test_extract.py
- [[Analyzer.process() calls run_analysis() - cross class→function calls edge.]] - rationale - tests/test_extract.py
- [[Call-graph pass must produce INFERRED calls edges.]] - rationale - tests/test_extract.py
- [[Extract classes, functions, and imports from a .py file via tree-sitter AST.]] - rationale - graphify/extract.py
- [[Function docstrings inside upgradedowngrade should still be captured.]] - rationale - tests/test_rationale.py
- [[Path_92]] - code
- [[Regression for 1050 @property  @staticmethod  @classmethod methods     were]] - rationale - tests/test_rationale.py
- [[Same caller→callee pair must appear only once even if called multiple times.]] - rationale - tests/test_extract.py
- [[Tests for rationaledocstring extraction in extract.py.]] - rationale - tests/test_rationale.py
- [[Trivial docstrings under 20 chars should not become rationale nodes.]] - rationale - tests/test_rationale.py
- [[_write_py()]] - code - tests/test_rationale.py
- [[_write_ts()]] - code - tests/test_rationale.py
- [[contains  method  inherits  imports edges must always be EXTRACTED.]] - rationale - tests/test_extract.py
- [[extract_python()]] - code - graphify/extract.py
- [[run_analysis() calls compute_score() - must appear as a calls edge.]] - rationale - tests/test_extract.py
- [[test_alembic_function_docstrings_still_extracted()]] - code - tests/test_rationale.py
- [[test_alembic_module_docstring_suppressed()]] - code - tests/test_rationale.py
- [[test_calls_deduplication()]] - code - tests/test_extract.py
- [[test_calls_edges_are_extracted()]] - code - tests/test_extract.py
- [[test_calls_edges_emitted()]] - code - tests/test_extract.py
- [[test_calls_no_self_loops()]] - code - tests/test_extract.py
- [[test_class_docstring_extracted()]] - code - tests/test_rationale.py
- [[test_decorated_method_node_id_is_class_qualified()]] - code - tests/test_rationale.py
- [[test_django_migration_module_docstring_suppressed()]] - code - tests/test_rationale.py
- [[test_extract_python_finds_class()]] - code - tests/test_extract.py
- [[test_extract_python_finds_methods()]] - code - tests/test_extract.py
- [[test_extract_python_no_dangling_edges()]] - code - tests/test_extract.py
- [[test_function_docstring_extracted()]] - code - tests/test_rationale.py
- [[test_generated_file_module_docstring_suppressed()]] - code - tests/test_rationale.py
- [[test_js_adr_in_string_literal_not_extracted()]] - code - tests/test_rationale.py
- [[test_js_adr_reference_extracted()]] - code - tests/test_rationale.py
- [[test_js_adr_reference_normalized_and_deduped()]] - code - tests/test_rationale.py
- [[test_js_block_comment_rationale_extracted()]] - code - tests/test_rationale.py
- [[test_js_rationale_comment_extracted()]] - code - tests/test_rationale.py
- [[test_method_calls_module_function()]] - code - tests/test_extract.py
- [[test_module_docstring_extracted()]] - code - tests/test_rationale.py
- [[test_non_migration_revision_var_not_suppressed()]] - code - tests/test_rationale.py
- [[test_python_call_edges_have_call_context()]] - code - tests/test_extract.py
- [[test_rationale.py]] - code - tests/test_rationale.py
- [[test_rationale_comment_extracted()]] - code - tests/test_rationale.py
- [[test_rationale_confidence_is_extracted()]] - code - tests/test_rationale.py
- [[test_rationale_for_edges_present()]] - code - tests/test_rationale.py
- [[test_run_analysis_calls_compute_score()]] - code - tests/test_extract.py
- [[test_run_analysis_calls_normalize()]] - code - tests/test_extract.py
- [[test_short_docstring_ignored()]] - code - tests/test_rationale.py
- [[test_structural_edges_are_extracted()]] - code - tests/test_extract.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_python
SORT file.name ASC
```

## Connections to other communities
- 13 edges to [[_COMMUNITY_test_extract.py]]
- 6 edges to [[_COMMUNITY_extract_js]]
- 4 edges to [[_COMMUNITY_test_indirect_dispatch.py]]
- 2 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 2 edges to [[_COMMUNITY_test_indirect_dispatch_assign_return.py]]
- 2 edges to [[_COMMUNITY_test_indirect_dispatch_getattr.py]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY__extract_python_rationale]]
- 1 edge to [[_COMMUNITY_engine.py]]

## Top bridge nodes
- [[extract_python()]] - degree 40, connects to 8 communities
- [[test_rationale.py]] - degree 27, connects to 4 communities
- [[test_decorated_method_node_id_is_class_qualified()]] - degree 5, connects to 1 community
- [[test_calls_deduplication()]] - degree 3, connects to 1 community
- [[test_calls_edges_are_extracted()]] - degree 3, connects to 1 community