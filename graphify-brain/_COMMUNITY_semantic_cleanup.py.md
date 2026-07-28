---
type: community
cohesion: 0.25
members: 8
---

# semantic_cleanup.py

**Cohesion:** 0.25 - loosely connected
**Members:** 8 nodes

## Members
- [[Append one or more rationale strings to node's ``rationale`` attribute.      I]] - rationale - graphify/semantic_cleanup.py
- [[Canonicalize a hyperedge's member list onto the `nodes` key, in place.      If `]] - rationale - graphify/build.py
- [[Return True if label looks like prose  rationale text rather than an     enti]] - rationale - graphify/semantic_cleanup.py
- [[_append_rationale_attr()]] - code - graphify/semantic_cleanup.py
- [[_is_sentence_like_rationale_label()]] - code - graphify/semantic_cleanup.py
- [[_normalize_hyperedge_members()]] - code - graphify/build.py
- [[_validate_semantic_id()]] - code - graphify/semantic_cleanup.py
- [[semantic_cleanup.py]] - code - graphify/semantic_cleanup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/semantic_cleanuppy
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_sanitize_semantic_fragment]]
- 4 edges to [[_COMMUNITY_test_semantic_cleanup.py]]
- 2 edges to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_build_from_json]]
- 1 edge to [[_COMMUNITY_load_validated_semantic_fragment]]

## Top bridge nodes
- [[semantic_cleanup.py]] - degree 9, connects to 4 communities
- [[_normalize_hyperedge_members()]] - degree 6, connects to 4 communities
- [[_append_rationale_attr()]] - degree 3, connects to 1 community
- [[_is_sentence_like_rationale_label()]] - degree 3, connects to 1 community
- [[_validate_semantic_id()]] - degree 2, connects to 1 community