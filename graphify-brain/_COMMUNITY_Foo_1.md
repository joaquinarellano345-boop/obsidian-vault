---
type: community
cohesion: 0.67
members: 3
---

# Foo

**Cohesion:** 0.67 - moderately connected
**Members:** 3 nodes

## Members
- [[.one()]] - code - tests/fixtures/swift_cross_file/Foo.swift
- [[Foo_2]] - code - tests/fixtures/swift_cross_file/Foo.swift
- [[Foo.swift]] - code - tests/fixtures/swift_cross_file/Foo.swift

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Foo
SORT file.name ASC
```
