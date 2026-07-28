---
type: community
cohesion: 0.50
members: 4
---

# _resolve_js_import_target

**Cohesion:** 0.50 - moderately connected
**Members:** 4 nodes

## Members
- [[Detect dynamic import() calls in JSTS and emit imports_from edges.      Handles]] - rationale - graphify/extractors/engine.py
- [[Resolve a JSTS import path string to (target_nid, resolved_path).      Handles]] - rationale - graphify/extractors/resolution.py
- [[_dynamic_import_js()]] - code - graphify/extractors/engine.py
- [[_resolve_js_import_target()]] - code - graphify/extractors/resolution.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_resolve_js_import_target
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_extract.py]]
- 4 edges to [[_COMMUNITY__read_text]]
- 2 edges to [[_COMMUNITY_engine.py]]
- 2 edges to [[_COMMUNITY_test_phantom_external_import.py]]
- 1 edge to [[_COMMUNITY_test_import_extension_resolution.py]]

## Top bridge nodes
- [[_resolve_js_import_target()]] - degree 12, connects to 5 communities
- [[_dynamic_import_js()]] - degree 5, connects to 3 communities