---
type: community
cohesion: 0.07
members: 39
---

# test_dedup.py

**Cohesion:** 0.07 - loosely connected
**Members:** 39 nodes

## Members
- [[2182 determinism, 17532074 precedent the survivor must not depend on     PY]] - rationale - tests/test_dedup.py
- [[(fix D) An explicit source_location=None on the survivor is treated as     absen]] - rationale - tests/test_dedup.py
- [[A cross-reference rewires silently without importing foreign-file metadata.]] - rationale - tests/test_dedup.py
- [[A fuzzy-only run must still report the fuzzy count (1857).      Two long, high-]] - rationale - tests/test_dedup.py
- [[Chip SKU variants (ASR1603 vs ASR1605) must not be merged (878).]] - rationale - tests/test_dedup.py
- [[Long labels differing only in embedded numbers (ADRsectionissue ids)     must]] - rationale - tests/test_dedup.py
- [[M1 vs M1 Pro must not merge (878).]] - rationale - tests/test_dedup.py
- [[Shannon entropy in bitschar of the normalised label.]] - rationale - graphify/dedup.py
- [[Short labels differing by an insertion (cranel vs cranelr) must not merge (878)]] - rationale - tests/test_dedup.py
- [[Tests for graphifydedup.py entity deduplication pipeline.]] - rationale - tests/test_dedup.py
- [[Two files that both mint one ID remain isolated despite exact-ID dedup.]] - rationale - tests/test_dedup.py
- [[_entropy()]] - code - graphify/dedup.py
- [[_make_edges()]] - code - tests/test_dedup.py
- [[_make_nodes()]] - code - tests/test_dedup.py
- [[deduplicate_entities accepts dedup_llm_backend without crashing when no ambiguou]] - rationale - tests/test_dedup.py
- [[source_file is absolute in some pipelines and repo-relative in others; the     d]] - rationale - tests/test_dedup.py
- [[test_absolute_source_path_still_defines_id()]] - code - tests/test_dedup.py
- [[test_community_boost_aids_merge()]] - code - tests/test_dedup.py
- [[test_cross_file_id_collision_does_not_mix_attributes()]] - code - tests/test_dedup.py
- [[test_crossfile_concept_merge_deterministic_across_hash_seeds()]] - code - tests/test_dedup.py
- [[test_dedup.py]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_model_with_suffix()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_numbered_siblings()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_numeric_variants()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_short_insertion_variants()]] - code - tests/test_dedup.py
- [[test_dedup_fills_explicit_none_attribute()]] - code - tests/test_dedup.py
- [[test_dedup_llm_flag_accepted()]] - code - tests/test_dedup.py
- [[test_dedup_summary_prints_fuzzy_count_when_no_exact_merges()]] - code - tests/test_dedup.py
- [[test_edges_rewired_after_merge()]] - code - tests/test_dedup.py
- [[test_entropy_empty_string()]] - code - tests/test_dedup.py
- [[test_entropy_normal_label_high()]] - code - tests/test_dedup.py
- [[test_entropy_short_label_low()]] - code - tests/test_dedup.py
- [[test_exact_duplicates_merged()]] - code - tests/test_dedup.py
- [[test_reference_collision_is_silent()]] - code - tests/test_dedup.py
- [[test_self_loops_dropped_after_merge()]] - code - tests/test_dedup.py
- [[test_short_low_entropy_not_merged()]] - code - tests/test_dedup.py
- [[test_single_node_no_crash()]] - code - tests/test_dedup.py
- [[test_typo_merged()]] - code - tests/test_dedup.py
- [[test_unrelated_not_merged()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_deduppy
SORT file.name ASC
```

## Connections to other communities
- 34 edges to [[_COMMUNITY_deduplicate_entities]]
- 12 edges to [[_COMMUNITY_dedup.py]]
- 3 edges to [[_COMMUNITY_build]]
- 3 edges to [[_COMMUNITY__is_variant_pair]]
- 3 edges to [[_COMMUNITY_test_crossfile_identical_labels_stay_distinct_for_guarded_types]]
- 1 edge to [[_COMMUNITY_test_collision_survivor_is_order_independent]]
- 1 edge to [[_COMMUNITY_test_cross_chunk_id_collision_emits_warning]]
- 1 edge to [[_COMMUNITY_test_cross_repo_guard_still_raises]]
- 1 edge to [[_COMMUNITY_test_crossfile_one_char_typo_concepts_still_merge]]
- 1 edge to [[_COMMUNITY_test_dedup_gapfill_is_order_independent_with_multiple_losers]]
- 1 edge to [[_COMMUNITY_test_dedup_no_attribute_merge_when_source_file_missing]]
- 1 edge to [[_COMMUNITY_test_dedup_summary_still_reports_exact_only]]
- 1 edge to [[_COMMUNITY_test_numeric_tokens_differ_helper]]
- 1 edge to [[_COMMUNITY_test_same_file_relabel_is_noted]]
- 1 edge to [[_COMMUNITY_test_same_id_same_source_file_no_warning]]

## Top bridge nodes
- [[test_dedup.py]] - degree 70, connects to 15 communities
- [[_entropy()]] - degree 8, connects to 2 communities
- [[test_dedup_does_not_merge_model_with_suffix()]] - degree 4, connects to 1 community
- [[test_dedup_does_not_merge_numeric_variants()]] - degree 4, connects to 1 community
- [[test_dedup_does_not_merge_short_insertion_variants()]] - degree 4, connects to 1 community