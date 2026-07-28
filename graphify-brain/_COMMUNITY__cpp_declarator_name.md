---
type: community
cohesion: 0.33
members: 6
---

# _cpp_declarator_name

**Cohesion:** 0.33 - loosely connected
**Members:** 6 nodes

## Members
- [[Collect ``var - ClassName`` from ObjC local declarations (``Foo f = ...;``)]] - rationale - graphify/extractors/objc.py
- [[Collect ``var - ClassName`` from local variable declarations in a C++     funct]] - rationale - graphify/extractors/engine.py
- [[Return the bare variable name from a C++ declaration declarator, unwrapping]] - rationale - graphify/extractors/engine.py
- [[_cpp_declarator_name()]] - code - graphify/extractors/engine.py
- [[_cpp_local_var_types()]] - code - graphify/extractors/engine.py
- [[_objc_local_var_types()]] - code - graphify/extractors/objc.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_cpp_declarator_name
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY__read_text]]
- 3 edges to [[_COMMUNITY_extract.py]]
- 3 edges to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY_extract_objc]]

## Top bridge nodes
- [[_cpp_declarator_name()]] - degree 7, connects to 3 communities
- [[_cpp_local_var_types()]] - degree 6, connects to 3 communities
- [[_objc_local_var_types()]] - degree 6, connects to 3 communities