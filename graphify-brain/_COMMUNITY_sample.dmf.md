---
type: community
cohesion: 0.15
members: 13
---

# sample.dmf

**Cohesion:** 0.15 - loosely connected
**Members:** 13 nodes

## Members
- [[elem info CHILD]] - code - tests/fixtures/sample.dmf
- [[elem infowindow MAIN]] - code - tests/fixtures/sample.dmf
- [[elem map MAP]] - code - tests/fixtures/sample.dmf
- [[elem mapwindow MAIN]] - code - tests/fixtures/sample.dmf
- [[elem output OUTPUT]] - code - tests/fixtures/sample.dmf
- [[elem outputwindow MAIN]] - code - tests/fixtures/sample.dmf
- [[elem stat INFO]] - code - tests/fixtures/sample.dmf
- [[elem statwindow MAIN]] - code - tests/fixtures/sample.dmf
- [[sample.dmf]] - code - tests/fixtures/sample.dmf
- [[window infowindow]] - code - tests/fixtures/sample.dmf
- [[window mapwindow]] - code - tests/fixtures/sample.dmf
- [[window outputwindow]] - code - tests/fixtures/sample.dmf
- [[window statwindow]] - code - tests/fixtures/sample.dmf

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/sampledmf
SORT file.name ASC
```
