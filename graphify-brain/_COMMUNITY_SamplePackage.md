---
type: community
cohesion: 0.40
members: 5
---

# SamplePackage

**Cohesion:** 0.40 - moderately connected
**Members:** 5 nodes

## Members
- [[FCL]] - code - tests/fixtures/sample.lpk
- [[LCL]] - code - tests/fixtures/sample.lpk
- [[SamplePackage]] - code - tests/fixtures/sample.lpk
- [[sample]] - code - tests/fixtures/sample.lpk
- [[sampleutils]] - code - tests/fixtures/sample.lpk

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/SamplePackage
SORT file.name ASC
```
