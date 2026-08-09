---
type: community
cohesion: 0.04
members: 79
---

# deduplicate_entities

**Cohesion:** 0.04 - loosely connected
**Members:** 79 nodes

## Members
- [[1851 definer + same-file relabel + cross-file reference. Across every     inse]] - rationale - tests/test_dedup.py
- [[(fix A) With 3+ same-ID same-source records, the merged attributes must not]] - rationale - tests/test_dedup.py
- [[(fix B) Two provenance-less records sharing an ID must NOT cross-pollinate     a]] - rationale - tests/test_dedup.py
- [[(fix C) An LLM survivor must not inherit _origin='ast' from a dropped     same-s]] - rationale - tests/test_dedup.py
- [[(fix D) An explicit source_location=None on the survivor is treated as     absen]] - rationale - tests/test_dedup.py
- [[A cross-reference rewires silently without importing foreign-file metadata.]] - rationale - tests/test_dedup.py
- [[A fuzzy-only run must still report the fuzzy count (1857).      Two long, high-]] - rationale - tests/test_dedup.py
- [[Chip SKU variants (ASR1603 vs ASR1605) must not be merged (878).]] - rationale - tests/test_dedup.py
- [[Cross-file labels sharing a long prefix but diverging in a distinguishing     to]] - rationale - tests/test_dedup.py
- [[Deduplicate near-identical entities in a knowledge graph.      Args         nod]] - rationale - graphify/dedup.py
- [[Distinct symbols whose name is a strict prefix-extension of another must not]] - rationale - tests/test_dedup.py
- [[Document nodes are file-anchored too near-identical headings in different     f]] - rationale - tests/test_dedup.py
- [[Exact cross-file matches and a punctuation variant collapse to one     survivor]] - rationale - tests/test_dedup.py
- [[Long labels differing only in embedded numbers (ADRsectionissue ids)     must]] - rationale - tests/test_dedup.py
- [[M1 vs M1 Pro must not merge (878).]] - rationale - tests/test_dedup.py
- [[Non-regression an exact-only run still prints `(N exact)` and no fuzzy.]] - rationale - tests/test_dedup.py
- [[Non-regression the near-identical (one-char-different) cross-file pair     that]] - rationale - tests/test_dedup.py
- [[Pass 2's winner selection must consider only the verified pair (1247).      Pic]] - rationale - tests/test_dedup.py
- [[Rationale nodes are file-anchored like code (1205) parallel modules'     boile]] - rationale - tests/test_dedup.py
- [[Return k-gram character shingles of text.]] - rationale - graphify/dedup.py
- [[Short labels differing by an insertion (cranel vs cranelr) must not merge (878)]] - rationale - tests/test_dedup.py
- [[Tests for graphifydedup.py entity deduplication pipeline.]] - rationale - tests/test_dedup.py
- [[The 1243 guard only drops the prefix bonus — a genuine cross-file     duplicate]] - rationale - tests/test_dedup.py
- [[The cross-repo guard is untouched by 2182 identical concepts from     differen]] - rationale - tests/test_dedup.py
- [[The file-anchored guard only blocks cross-file pairs — near-identical     ration]] - rationale - tests/test_dedup.py
- [[Three identical-norm concepts across three files every input order must     yie]] - rationale - tests/test_dedup.py
- [[Two `concept` nodes whose labels are byte-identical after _norm() but     live i]] - rationale - tests/test_dedup.py
- [[Two files that both mint one ID remain isolated despite exact-ID dedup.]] - rationale - tests/test_dedup.py
- [[Two labels for one ID from one file the loser's label is discarded, which is]] - rationale - tests/test_dedup.py
- [[When two nodes share both ID and source_file (same-file dedup),     no collision]] - rationale - tests/test_dedup.py
- [[When two nodes share the same ID but come from different source files     (a cro]] - rationale - tests/test_dedup.py
- [[_make_edges()]] - code - tests/test_dedup.py
- [[_make_nodes()]] - code - tests/test_dedup.py
- [[_shingles()]] - code - graphify/dedup.py
- [[deduplicate_entities accepts dedup_llm_backend without crashing when no ambiguou]] - rationale - tests/test_dedup.py
- [[deduplicate_entities()]] - code - graphify/dedup.py
- [[source_file is absolute in some pipelines and repo-relative in others; the     d]] - rationale - tests/test_dedup.py
- [[test_absolute_source_path_still_defines_id()]] - code - tests/test_dedup.py
- [[test_collision_survivor_is_order_independent()]] - code - tests/test_dedup.py
- [[test_community_boost_aids_merge()]] - code - tests/test_dedup.py
- [[test_cross_chunk_id_collision_emits_warning()]] - code - tests/test_dedup.py
- [[test_cross_file_id_collision_does_not_mix_attributes()]] - code - tests/test_dedup.py
- [[test_cross_repo_guard_still_raises()]] - code - tests/test_dedup.py
- [[test_crossfile_concept_merge_is_order_independent()]] - code - tests/test_dedup.py
- [[test_crossfile_concept_merge_is_transitive()]] - code - tests/test_dedup.py
- [[test_crossfile_identical_concepts_merge_and_rewire()]] - code - tests/test_dedup.py
- [[test_crossfile_one_char_typo_concepts_still_merge()]] - code - tests/test_dedup.py
- [[test_dedup.py]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_crossfile_document_headings()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_crossfile_rationale_boilerplate()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_crossfile_shared_prefix_divergence()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_model_with_suffix()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_numbered_siblings()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_numeric_variants()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_short_insertion_variants()]] - code - tests/test_dedup.py
- [[test_dedup_fills_explicit_none_attribute()]] - code - tests/test_dedup.py
- [[test_dedup_gapfill_is_order_independent_with_multiple_losers()]] - code - tests/test_dedup.py
- [[test_dedup_llm_flag_accepted()]] - code - tests/test_dedup.py
- [[test_dedup_no_attribute_merge_when_source_file_missing()]] - code - tests/test_dedup.py
- [[test_dedup_still_merges_crossfile_true_duplicates()]] - code - tests/test_dedup.py
- [[test_dedup_still_merges_samefile_rationale_duplicates()]] - code - tests/test_dedup.py
- [[test_dedup_summary_prints_fuzzy_count_when_no_exact_merges()]] - code - tests/test_dedup.py
- [[test_dedup_summary_still_reports_exact_only()]] - code - tests/test_dedup.py
- [[test_dedup_survivor_does_not_inherit_false_origin_ast()]] - code - tests/test_dedup.py
- [[test_edges_rewired_after_merge()]] - code - tests/test_dedup.py
- [[test_empty_inputs()]] - code - tests/test_dedup.py
- [[test_exact_duplicates_merged()]] - code - tests/test_dedup.py
- [[test_pass2_winner_union_does_not_pull_in_uncompared_same_label_nodes()]] - code - tests/test_dedup.py
- [[test_prefix_extension_symbols_not_merged()]] - code - tests/test_dedup.py
- [[test_reference_collision_is_silent()]] - code - tests/test_dedup.py
- [[test_same_file_relabel_is_noted()]] - code - tests/test_dedup.py
- [[test_same_id_same_source_file_no_warning()]] - code - tests/test_dedup.py
- [[test_self_loops_dropped_after_merge()]] - code - tests/test_dedup.py
- [[test_shingles_produces_trigrams()]] - code - tests/test_dedup.py
- [[test_shingles_short_string()]] - code - tests/test_dedup.py
- [[test_short_low_entropy_not_merged()]] - code - tests/test_dedup.py
- [[test_single_node_no_crash()]] - code - tests/test_dedup.py
- [[test_typo_merged()]] - code - tests/test_dedup.py
- [[test_unrelated_not_merged()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/deduplicate_entities
SORT file.name ASC
```

## Connections to other communities
- 16 edges to [[_COMMUNITY__llm_tiebreak]]
- 9 edges to [[_COMMUNITY_dedup.py]]
- 9 edges to [[_COMMUNITY__norm]]
- 6 edges to [[_COMMUNITY_test_crossfile_identical_labels_stay_distinct_for_guarded_types]]
- 5 edges to [[_COMMUNITY__defines_id]]
- 4 edges to [[_COMMUNITY_test_global_graph.py]]
- 3 edges to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_test_build_calls_dedup]]
- 1 edge to [[_COMMUNITY_test_build_dedup_preserves_semantic_attributes]]
- 1 edge to [[_COMMUNITY_test_crossfile_concept_merge_deterministic_across_hash_seeds]]

## Top bridge nodes
- [[test_dedup.py]] - degree 70, connects to 9 communities
- [[deduplicate_entities()]] - degree 70, connects to 7 communities
- [[_shingles()]] - degree 6, connects to 1 community