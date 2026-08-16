---
type: community
cohesion: 0.12
members: 17
---

# _resolve_js_import_target

**Cohesion:** 0.12 - loosely connected
**Members:** 17 nodes

## Members
- [[Classify the symbol an `assignment_expression` LHS defines when its RHS     is a]] - rationale - graphify/extractors/engine.py
- [[Collect binding identifier names from a JSTS pattern (a parameter, or a     dec]] - rationale - graphify/extractors/engine.py
- [[Detect CommonJS require imports inside lexical_declaration  variable_declaratio]] - rationale - graphify/extractors/engine.py
- [[Detect dynamic import() calls in JSTS and emit imports_from edges.      Handles]] - rationale - graphify/extractors/engine.py
- [[Handle lexical_declaration (arrow functions, CJS requires, module-level const li]] - rationale - graphify/extractors/engine.py
- [[Names bound locally inside a JSTS function parameters plus `const``let`]] - rationale - graphify/extractors/engine.py
- [[Resolve a JSTS import path string to (target_nid, resolved_path).      Handles]] - rationale - graphify/extractors/resolution.py
- [[Return the call_expression node if `value_node` is a `require(...)` call     or]] - rationale - graphify/extractors/engine.py
- [[_dynamic_import_js()]] - code - graphify/extractors/engine.py
- [[_find_require_call()]] - code - graphify/extractors/engine.py
- [[_import_js()]] - code - graphify/extract.py
- [[_js_collect_pattern_idents()]] - code - graphify/extractors/engine.py
- [[_js_extra_walk()]] - code - graphify/extractors/engine.py
- [[_js_local_bound_names()]] - code - graphify/extractors/engine.py
- [[_js_member_assignment_target()]] - code - graphify/extractors/engine.py
- [[_require_imports_js()]] - code - graphify/extractors/engine.py
- [[_resolve_js_import_target()]] - code - graphify/extractors/resolution.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_resolve_js_import_target
SORT file.name ASC
```

## Connections to other communities
- 17 edges to [[_COMMUNITY_extract.py]]
- 8 edges to [[_COMMUNITY_engine.py]]
- 6 edges to [[_COMMUNITY__make_id]]
- 2 edges to [[_COMMUNITY_test_phantom_external_import.py]]
- 1 edge to [[_COMMUNITY_make_id]]
- 1 edge to [[_COMMUNITY_test_import_extension_resolution.py]]

## Top bridge nodes
- [[_resolve_js_import_target()]] - degree 12, connects to 5 communities
- [[_js_extra_walk()]] - degree 9, connects to 4 communities
- [[_require_imports_js()]] - degree 9, connects to 3 communities
- [[_import_js()]] - degree 5, connects to 2 communities
- [[_dynamic_import_js()]] - degree 5, connects to 2 communities