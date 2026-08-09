---
type: community
cohesion: 0.16
members: 24
---

# CsharpNameResolver

**Cohesion:** 0.16 - loosely connected
**Members:** 24 nodes

## Members
- [[.__init__()_5]] - code - graphify/extractors/csharp.py
- [[._namespace()]] - code - graphify/extractors/csharp.py
- [[._resolve_alias()]] - code - graphify/extractors/csharp.py
- [[._scope_chain()]] - code - graphify/extractors/csharp.py
- [[._scopes_for()]] - code - graphify/extractors/csharp.py
- [[._using_in_scope()]] - code - graphify/extractors/csharp.py
- [[.resolve_label()]] - code - graphify/extractors/csharp.py
- [[.resolve_qualified()]] - code - graphify/extractors/csharp.py
- [[.resolve_type_name()]] - code - graphify/extractors/csharp.py
- [[Arbitrate all C ``inherits````implements````references`` targets.      The ex]] - rationale - graphify/extractors/csharp.py
- [[C cross-file resolution.  The config-driven C extractor (``extract_csharp``]] - rationale - graphify/extractors/csharp.py
- [[CsharpNameResolver]] - code - graphify/extractors/csharp.py
- [[Namespaceusingalias-aware C simple-name resolution.      Factored out of ``_r]] - rationale - graphify/extractors/csharp.py
- [[Path_15]] - code
- [[Re-point resolvable C ``using`` import edges to canonical internal nodes.]] - rationale - graphify/extractors/csharp.py
- [[Resolve a simple type name to a definition node id, with a verdict.          Ret]] - rationale - graphify/extractors/csharp.py
- [[Return deterministic ``(namespace, name) - node_id`` C type definitions.]] - rationale - graphify/extractors/csharp.py
- [[_build_csharp_type_def_index()]] - code - graphify/extractors/csharp.py
- [[_is_cs_file()]] - code - graphify/extractors/csharp.py
- [[_metadata()]] - code - graphify/extractors/csharp.py
- [[_resolve_cross_file_csharp_imports()]] - code - graphify/extractors/csharp.py
- [[_resolve_csharp_type_references()]] - code - graphify/extractors/csharp.py
- [[_strip_trailing_csharp_generic_args()]] - code - graphify/extractors/csharp.py
- [[csharp.py]] - code - graphify/extractors/csharp.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/CsharpNameResolver
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_extract.py]]
- 2 edges to [[_COMMUNITY_extract]]
- 2 edges to [[_COMMUNITY__make_id]]
- 1 edge to [[_COMMUNITY_export.py]]
- 1 edge to [[_COMMUNITY__is_type_like_definition]]
- 1 edge to [[_COMMUNITY_engine.py]]

## Top bridge nodes
- [[csharp.py]] - degree 12, connects to 4 communities
- [[_resolve_csharp_type_references()]] - degree 9, connects to 3 communities
- [[CsharpNameResolver]] - degree 14, connects to 2 communities
- [[_resolve_cross_file_csharp_imports()]] - degree 7, connects to 2 communities