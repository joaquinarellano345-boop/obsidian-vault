---
type: community
cohesion: 0.50
members: 4
---

# _env_command_args

**Cohesion:** 0.50 - moderately connected
**Members:** 4 nodes

## Members
- [[Re-tokenize an `env -S``--split-string` packed command, prepending the     oper]] - rationale - graphify/detect.py
- [[Strip leading env(1) options and var assignments, return the trailing     comman]] - rationale - graphify/detect.py
- [[_env_command_args()]] - code - graphify/detect.py
- [[_split_env_s()]] - code - graphify/detect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_env_command_args
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY_classify_file]]

## Top bridge nodes
- [[_env_command_args()]] - degree 4, connects to 2 communities
- [[_split_env_s()]] - degree 3, connects to 1 community