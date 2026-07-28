---
type: community
cohesion: 0.39
members: 9
---

# sample_calls.py

**Cohesion:** 0.39 - loosely connected
**Members:** 9 nodes

## Members
- [[.full_pipeline()]] - code - tests/fixtures/sample_calls.py
- [[.process()_6]] - code - tests/fixtures/sample_calls.py
- [[.score()]] - code - tests/fixtures/sample_calls.py
- [[Analyzer]] - code - tests/fixtures/sample_calls.py
- [[Fixture functions and methods that call each other - for call-graph extraction]] - rationale - tests/fixtures/sample_calls.py
- [[compute_score()]] - code - tests/fixtures/sample_calls.py
- [[normalize()]] - code - tests/fixtures/sample_calls.py
- [[run_analysis()]] - code - tests/fixtures/sample_calls.py
- [[sample_calls.py]] - code - tests/fixtures/sample_calls.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/sample_callspy
SORT file.name ASC
```
