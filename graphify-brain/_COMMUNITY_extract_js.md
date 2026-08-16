---
type: community
cohesion: 0.03
members: 61
---

# extract_js

**Cohesion:** 0.03 - loosely connected
**Members:** 61 nodes

## Members
- [[A class field initialised with an arrow function (`x = () = {}`) must be     ca]] - rationale - tests/test_extract.py
- [[All re_exports edges should have confidence=EXTRACTED.]] - rationale - tests/test_extract.py
- [[Barrel file must emit file-level imports_from edges to source modules.]] - rationale - tests/test_extract.py
- [[Calls inside JSX expressions like `{fmtDate(now)}` must yield call edges.      R]] - rationale - tests/test_extract.py
- [[Destructured CJS requires must emit symbol-level `imports` edges per binder.]] - rationale - tests/test_extract.py
- [[Dynamic import edge source should be the enclosing function, not the file.]] - rationale - tests/test_languages.py
- [[Dynamic import() calls inside functions should produce imports_from edges.]] - rationale - tests/test_languages.py
- [[Dynamic imports should have EXTRACTED confidence (they are deterministic string]] - rationale - tests/test_languages.py
- [[Dynamic template literals (with ${}) must not produce an imports_from edge.]] - rationale - tests/test_languages.py
- [[Extract classes, functions, arrow functions, and imports from a .js.ts.tsx.mt]] - rationale - graphify/extract.py
- [[Functions defined alongside a JSX-returning component must be captured.]] - rationale - tests/test_extract.py
- [[Functions without dynamic imports should not get spurious imports_from edges.]] - rationale - tests/test_languages.py
- [[Guard against the phantom-god-node class (1077) an arbitrary     `obj.x = fn`]] - rationale - tests/test_extract.py
- [[Path_92]] - code
- [[Regression arrow functions in lexical_declaration must still produce nodes.]] - rationale - tests/test_extract.py
- [[Static template literals (no ${}) should resolve the same as a plain string.]] - rationale - tests/test_languages.py
- [[_write_ts()]] - code - tests/test_rationale.py
- [[`Foo.prototype.bar = fn` must be captured as a method owned by Foo.]] - rationale - tests/test_extract.py
- [[`const f = function(){}` (function expression, not arrow) must be captured.]] - rationale - tests/test_extract.py
- [[`const x = require('.m').y` must emit symbol edge for `y`.]] - rationale - tests/test_extract.py
- [[`const { foo } = require('.mod')` must emit imports_from to the resolved module]] - rationale - tests/test_extract.py
- [[`exports.X = fn` and `module.exports.X = fn` must produce function nodes.]] - rationale - tests/test_extract.py
- [[`this.X = () = {}`  `this.X = function(){}` in a constructor-style     functio]] - rationale - tests/test_extract.py
- [[by_label_by_id()]] - code - tests/test_extract.py
- [[export functionconst in a barrel file must still create nodes.]] - rationale - tests/test_extract.py
- [[export { X } from '.mod' must emit re_exports edges for each named specifier.]] - rationale - tests/test_extract.py
- [[export { localVar } without 'from' should NOT create re_exports edges.]] - rationale - tests/test_extract.py
- [[extract_js()]] - code - graphify/extract.py
- [[re_exports edges should have context='re-export'.]] - rationale - tests/test_extract.py
- [[test_barrel_local_exports_still_extracted()]] - code - tests/test_extract.py
- [[test_barrel_reexport_confidence_extracted()]] - code - tests/test_extract.py
- [[test_barrel_reexport_context_tagged()]] - code - tests/test_extract.py
- [[test_barrel_reexport_emits_imports_from()]] - code - tests/test_extract.py
- [[test_barrel_reexport_emits_re_exports_edges()]] - code - tests/test_extract.py
- [[test_extract_js_arbitrary_member_assignment_not_captured()]] - code - tests/test_extract.py
- [[test_extract_js_arrow_function_still_extracted()]] - code - tests/test_extract.py
- [[test_extract_js_commonjs_exports_assignment()]] - code - tests/test_extract.py
- [[test_extract_js_const_function_expression()]] - code - tests/test_extract.py
- [[test_extract_js_destructured_require_imports_from()]] - code - tests/test_extract.py
- [[test_extract_js_destructured_require_named_symbols()]] - code - tests/test_extract.py
- [[test_extract_js_member_require_emits_property_symbol()]] - code - tests/test_extract.py
- [[test_extract_js_prototype_method_assignment()]] - code - tests/test_extract.py
- [[test_extract_js_this_assigned_methods()]] - code - tests/test_extract.py
- [[test_extract_ts_class_arrow_field()]] - code - tests/test_extract.py
- [[test_extract_tsx_finds_helpers_and_component()]] - code - tests/test_extract.py
- [[test_extract_tsx_jsx_expression_calls_resolve()]] - code - tests/test_extract.py
- [[test_js_adr_in_string_literal_not_extracted()]] - code - tests/test_rationale.py
- [[test_js_adr_reference_extracted()]] - code - tests/test_rationale.py
- [[test_js_adr_reference_normalized_and_deduped()]] - code - tests/test_rationale.py
- [[test_js_block_comment_rationale_extracted()]] - code - tests/test_rationale.py
- [[test_js_rationale_comment_extracted()]] - code - tests/test_rationale.py
- [[test_pure_export_no_from_not_treated_as_reexport()]] - code - tests/test_extract.py
- [[test_ts_dynamic_import_confidence()]] - code - tests/test_languages.py
- [[test_ts_dynamic_import_extracts_edges()]] - code - tests/test_languages.py
- [[test_ts_dynamic_import_no_error()]] - code - tests/test_languages.py
- [[test_ts_dynamic_import_source_is_function()]] - code - tests/test_languages.py
- [[test_ts_dynamic_template_literal_skipped()]] - code - tests/test_languages.py
- [[test_ts_no_dynamic_import_in_sync_fn()]] - code - tests/test_languages.py
- [[test_ts_static_template_literal_resolved()]] - code - tests/test_languages.py
- [[test_ts_this_field_receiver_not_same_file_collision()]] - code - tests/test_languages.py
- [[this.db.query() should NOT match an unrelated query() in the same file (1316).]] - rationale - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_js
SORT file.name ASC
```

## Connections to other communities
- 20 edges to [[_COMMUNITY_test_extract.py]]
- 15 edges to [[_COMMUNITY_test_import_extension_resolution.py]]
- 9 edges to [[_COMMUNITY_test_languages.py]]
- 8 edges to [[_COMMUNITY_extract_python]]
- 6 edges to [[_COMMUNITY_test_multilang.py]]
- 3 edges to [[_COMMUNITY__make_id]]
- 3 edges to [[_COMMUNITY__labels_1]]
- 2 edges to [[_COMMUNITY_test_cjs_module_extension.py]]
- 2 edges to [[_COMMUNITY__labels]]
- 2 edges to [[_COMMUNITY_test_typescript_module_extensions.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY__relations]]

## Top bridge nodes
- [[extract_js()]] - degree 72, connects to 16 communities
- [[test_extract_js_destructured_require_named_symbols()]] - degree 4, connects to 2 communities
- [[test_extract_js_member_require_emits_property_symbol()]] - degree 4, connects to 2 communities
- [[_write_ts()]] - degree 7, connects to 1 community
- [[test_extract_js_this_assigned_methods()]] - degree 4, connects to 1 community