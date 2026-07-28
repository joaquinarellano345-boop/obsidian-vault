---
type: community
cohesion: 0.33
members: 6
---

# SampleSpec

**Cohesion:** 0.33 - loosely connected
**Members:** 6 nodes

## Members
- [[should handle input and return expected]] - code - tests/fixtures/sample_spock.groovy
- [[should not change value when it's already correct]] - code - tests/fixtures/sample_spock.groovy
- [[should process valid input]] - code - tests/fixtures/sample_spock.groovy
- [[.setup()]] - code - tests/fixtures/sample_spock.groovy
- [[SampleSpec]] - code - tests/fixtures/sample_spock.groovy
- [[sample_spock.groovy]] - code - tests/fixtures/sample_spock.groovy

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/SampleSpec
SORT file.name ASC
```
