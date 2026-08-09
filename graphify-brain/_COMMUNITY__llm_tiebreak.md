---
type: community
cohesion: 0.11
members: 23
---

# _llm_tiebreak

**Cohesion:** 0.11 - loosely connected
**Members:** 23 nodes

## Members
- [[.__init__()_4]] - code - graphify/dedup.py
- [[.components()]] - code - graphify/dedup.py
- [[.find()]] - code - graphify/dedup.py
- [[.union()]] - code - graphify/dedup.py
- [[Batch-resolve ambiguous pairs (score in low, high)) via LLM.]] - rationale - graphify/dedup.py
- [[Block fuzzy merge for short labels unless it's a same-length single-char substit]] - rationale - graphify/dedup.py
- [[Block label-based merging of file-anchored non-code nodes across files (1284).]] - rationale - graphify/dedup.py
- [[Genuine same-length single-char typos should still merge (878 non-regression).]] - rationale - tests/test_dedup.py
- [[Pick the canonical survivor prefer no chunk suffix, then shorter ID.]] - rationale - graphify/dedup.py
- [[True if a and b are sibling modelSKU variants (same stem, different suffix).]] - rationale - graphify/dedup.py
- [[True when two labels carry different embedded numbers (1284).      Long labels]] - rationale - graphify/dedup.py
- [[_UF]] - code - graphify/dedup.py
- [[_crossfile_fileanchored_blocked()]] - code - graphify/dedup.py
- [[_is_variant_pair correctly identifies chip-model variant pairs (878).]] - rationale - tests/test_dedup.py
- [[_is_variant_pair()]] - code - graphify/dedup.py
- [[_llm_tiebreak()]] - code - graphify/dedup.py
- [[_numeric_tokens_differ compares digit runs as zero-padding-insensitive     multi]] - rationale - tests/test_dedup.py
- [[_numeric_tokens_differ()]] - code - graphify/dedup.py
- [[_pick_winner()]] - code - graphify/dedup.py
- [[_short_label_blocked()]] - code - graphify/dedup.py
- [[test_dedup_still_merges_real_typos()]] - code - tests/test_dedup.py
- [[test_numeric_tokens_differ_helper()]] - code - tests/test_dedup.py
- [[test_variant_pair_helper()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_llm_tiebreak
SORT file.name ASC
```

## Connections to other communities
- 16 edges to [[_COMMUNITY_deduplicate_entities]]
- 9 edges to [[_COMMUNITY_dedup.py]]
- 1 edge to [[_COMMUNITY__norm]]
- 1 edge to [[_COMMUNITY__call_llm]]
- 1 edge to [[_COMMUNITY_llm.py]]
- 1 edge to [[_COMMUNITY_detect_backend]]

## Top bridge nodes
- [[_llm_tiebreak()]] - degree 15, connects to 6 communities
- [[_UF]] - degree 9, connects to 2 communities
- [[_is_variant_pair()]] - degree 7, connects to 2 communities
- [[_numeric_tokens_differ()]] - degree 6, connects to 2 communities
- [[_short_label_blocked()]] - degree 6, connects to 2 communities