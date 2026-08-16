---
type: community
cohesion: 0.12
members: 17
---

# extract_groovy

**Cohesion:** 0.12 - loosely connected
**Members:** 17 nodes

## Members
- [[Extract classes, methods, constructors, and imports from a .groovy.gradle file.]] - rationale - graphify/extract.py
- [[`class X extends Base` must emit an inherits edge.      tree-sitter-groovy expos]] - rationale - tests/test_languages.py
- [[`class X implements Iface` must emit an implements edge.]] - rationale - tests/test_languages.py
- [[extract_groovy()]] - code - graphify/extract.py
- [[test_groovy_extends_edge()]] - code - tests/test_languages.py
- [[test_groovy_finds_class()]] - code - tests/test_languages.py
- [[test_groovy_finds_imports()]] - code - tests/test_languages.py
- [[test_groovy_finds_methods()]] - code - tests/test_languages.py
- [[test_groovy_implements_edge()]] - code - tests/test_languages.py
- [[test_groovy_import_edges_have_import_context()]] - code - tests/test_languages.py
- [[test_groovy_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_groovy_no_error()]] - code - tests/test_languages.py
- [[test_groovy_spock_finds_class()]] - code - tests/test_languages.py
- [[test_groovy_spock_finds_feature_methods()]] - code - tests/test_languages.py
- [[test_groovy_spock_finds_method_with_apostrophe()]] - code - tests/test_languages.py
- [[test_groovy_spock_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_groovy_spock_preserves_import_edges()]] - code - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_groovy
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_test_languages.py]]
- 5 edges to [[_COMMUNITY__labels]]
- 2 edges to [[_COMMUNITY_Path]]
- 2 edges to [[_COMMUNITY__relations]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY__make_id]]
- 1 edge to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY__edges_with_relation]]

## Top bridge nodes
- [[extract_groovy()]] - degree 20, connects to 5 communities
- [[test_groovy_finds_class()]] - degree 3, connects to 2 communities
- [[test_groovy_finds_imports()]] - degree 3, connects to 2 communities
- [[test_groovy_finds_methods()]] - degree 3, connects to 2 communities
- [[test_groovy_import_edges_have_import_context()]] - degree 3, connects to 2 communities