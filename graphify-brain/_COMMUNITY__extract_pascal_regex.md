---
type: community
cohesion: 0.12
members: 23
---

# _extract_pascal_regex

**Cohesion:** 0.12 - loosely connected
**Members:** 23 nodes

## Members
- [[Build a scoped call resolver for a single PascalDelphi file.      ``records`` i]] - rationale - graphify/extractors/pascal.py
- [[Find balanced begin..end after start. Returns (body_start, body_end).     Return]] - rationale - graphify/extractors/pascal.py
- [[Path_26]] - code
- [[Regex fallback for PascalDelphi extraction when tree-sitter-pascal     is unava]] - rationale - graphify/extractors/pascal.py
- [[Resolve a Pascal classinterface name to the node ID of its defining file's clas]] - rationale - graphify/extractors/resolution.py
- [[Resolve a Pascal unit name to the graphify node ID of its source file.      Scan]] - rationale - graphify/extractors/resolution.py
- [[Return the highest ancestor directory that looks like a Pascal project root.]] - rationale - graphify/extractors/resolution.py
- [[Split a uses list string, handling 'Foo in ''bar.pas''' syntax.]] - rationale - graphify/extractors/pascal.py
- [[Split inheritance list, handling generics like TListT, U.]] - rationale - graphify/extractors/pascal.py
- [[Split into (iface_text, iface_offset, impl_text, impl_offset).     Files without]] - rationale - graphify/extractors/pascal.py
- [[Strip Pascal comments ({}, ( ), ) while preserving newlines.]] - rationale - graphify/extractors/pascal.py
- [[_extract_pascal_regex()]] - code - graphify/extractors/pascal.py
- [[_pascal_find_body()]] - code - graphify/extractors/pascal.py
- [[_pascal_project_root()]] - code - graphify/extractors/resolution.py
- [[_pascal_resolve_class()]] - code - graphify/extractors/resolution.py
- [[_pascal_resolve_unit()]] - code - graphify/extractors/resolution.py
- [[_pascal_split_bases()]] - code - graphify/extractors/pascal.py
- [[_pascal_split_sections()]] - code - graphify/extractors/pascal.py
- [[_pascal_split_uses()]] - code - graphify/extractors/pascal.py
- [[_pascal_strip_comments()]] - code - graphify/extractors/pascal.py
- [[_resolve_pascal_callee_factory()]] - code - graphify/extractors/pascal.py
- [[pascal — moved verbatim from graphifyextract.py.]] - rationale - graphify/extractors/pascal.py
- [[pascal.py]] - code - graphify/extractors/pascal.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_extract_pascal_regex
SORT file.name ASC
```

## Connections to other communities
- 17 edges to [[_COMMUNITY_extract.py]]
- 8 edges to [[_COMMUNITY_test_pascal.py]]
- 8 edges to [[_COMMUNITY__make_id]]
- 2 edges to [[_COMMUNITY__get_extractor]]
- 1 edge to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY_test_pascal_call_scoping.py]]

## Top bridge nodes
- [[_extract_pascal_regex()]] - degree 19, connects to 5 communities
- [[pascal.py]] - degree 17, connects to 4 communities
- [[_pascal_resolve_class()]] - degree 10, connects to 3 communities
- [[_pascal_resolve_unit()]] - degree 10, connects to 3 communities
- [[_pascal_project_root()]] - degree 6, connects to 1 community