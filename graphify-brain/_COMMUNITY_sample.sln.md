---
type: community
cohesion: 0.70
members: 5
---

# sample.sln

**Cohesion:** 0.70 - tightly connected
**Members:** 5 nodes

## Members
- [[Domain]] - code - tests/fixtures/src/Domain/Domain.csproj
- [[Tests]] - code - tests/fixtures/tests/Tests/Tests.csproj
- [[WebApi]] - code - tests/fixtures/src/WebApi/WebApi.csproj
- [[sample.sln]] - code - tests/fixtures/sample.sln
- [[sample.slnx]] - code - tests/fixtures/sample.slnx

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/samplesln
SORT file.name ASC
```
