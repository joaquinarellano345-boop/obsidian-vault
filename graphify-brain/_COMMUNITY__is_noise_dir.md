---
type: community
cohesion: 0.50
members: 4
---

# _is_noise_dir

**Cohesion:** 0.50 - moderately connected
**Members:** 4 nodes

## Members
- [[Return True if this directory name looks like a venv, cache, or dep dir.]] - rationale - graphify/detect.py
- [[True only when d has actual virtualenvconda structure on disk.      ``env```]] - rationale - graphify/detect.py
- [[_has_venv_markers()]] - code - graphify/detect.py
- [[_is_noise_dir()]] - code - graphify/detect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_is_noise_dir
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_test_extract.py]]
- 2 edges to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY_test_detect.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_Path]]

## Top bridge nodes
- [[_is_noise_dir()]] - degree 9, connects to 5 communities
- [[_has_venv_markers()]] - degree 3, connects to 1 community