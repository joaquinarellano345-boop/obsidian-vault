---
type: community
cohesion: 0.33
members: 7
---

# Foo

**Cohesion:** 0.33 - loosely connected
**Members:** 7 nodes

## Members
- [[Foo]] - code - tests/fixtures/cpp_paired/Foo.h
- [[Foo.cpp]] - code - tests/fixtures/cpp_paired/Foo.cpp
- [[Foo.h]] - code - tests/fixtures/cpp_paired/Foo.h
- [[Main.cpp]] - code - tests/fixtures/cpp_paired/Main.cpp
- [[bar]] - code - tests/fixtures/cpp_paired/Foo.h
- [[main()_4]] - code - tests/fixtures/cpp_paired/Main.cpp
- [[value]] - code - tests/fixtures/cpp_paired/Foo.h

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Foo
SORT file.name ASC
```
