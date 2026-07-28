---
type: community
cohesion: 0.27
members: 10
---

# ExtendedService

**Cohesion:** 0.27 - loosely connected
**Members:** 10 nodes

## Members
- [[.ExtendedService()]] - code - tests/fixtures/sample.groovy
- [[.SampleService()]] - code - tests/fixtures/sample.groovy
- [[.process()_2]] - code - tests/fixtures/sample.groovy
- [[.reset()_2]] - code - tests/fixtures/sample.groovy
- [[.reset()_1]] - code - tests/fixtures/sample.groovy
- [[.reset()]] - code - tests/fixtures/sample.groovy
- [[ExtendedService]] - code - tests/fixtures/sample.groovy
- [[Resettable]] - code - tests/fixtures/sample.groovy
- [[SampleService]] - code - tests/fixtures/sample.groovy
- [[sample.groovy]] - code - tests/fixtures/sample.groovy

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/ExtendedService
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_DataProcessor]]

## Top bridge nodes
- [[sample.groovy]] - degree 4, connects to 1 community