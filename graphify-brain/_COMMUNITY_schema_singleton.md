---
type: community
cohesion: 0.25
members: 8
---

# schema_singleton

**Cohesion:** 0.25 - loosely connected
**Members:** 8 nodes

## Members
- [[Assert the file_type enum block is byte-identical across every platform.      Ev]] - rationale - tools/skillgen/gen.py
- [[Return lines carrying a legacy (sub-superset) file_type enum.      A line counts]] - rationale - tools/skillgen/gen.py
- [[The file_type enum is the six-value superset in every rendered artifact.]] - rationale - tests/test_skillgen.py
- [[The guard's line scanner flags 4- and 5-value pipe enums, not the superset.]] - rationale - tests/test_skillgen.py
- [[legacy_enum_lines()]] - code - tools/skillgen/gen.py
- [[schema_singleton()]] - code - tools/skillgen/gen.py
- [[test_schema_singleton_catches_legacy_enums()]] - code - tests/test_skillgen.py
- [[test_schema_singleton_passes_across_all_platforms()]] - code - tests/test_skillgen.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/schema_singleton
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_gen.py]]
- 2 edges to [[_COMMUNITY_test_skillgen.py]]
- 2 edges to [[_COMMUNITY_render]]
- 1 edge to [[_COMMUNITY_load_platforms]]

## Top bridge nodes
- [[schema_singleton()]] - degree 7, connects to 2 communities
- [[test_schema_singleton_passes_across_all_platforms()]] - degree 4, connects to 2 communities
- [[legacy_enum_lines()]] - degree 4, connects to 1 community
- [[test_schema_singleton_catches_legacy_enums()]] - degree 3, connects to 1 community