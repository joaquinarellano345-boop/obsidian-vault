---
type: community
cohesion: 0.07
members: 40
---

# deduplicate_entities

**Cohesion:** 0.07 - loosely connected
**Members:** 40 nodes

## Members
- [[(fix C) An LLM survivor must not inherit _origin='ast' from a dropped     same-s]] - rationale - tests/test_dedup.py
- [[.__init__()_4]] - code - graphify/dedup.py
- [[.components()]] - code - graphify/dedup.py
- [[.find()]] - code - graphify/dedup.py
- [[.union()]] - code - graphify/dedup.py
- [[Batch-resolve ambiguous pairs (score in low, high)) via LLM.]] - rationale - graphify/dedup.py
- [[Block fuzzy merge for short labels unless it's a same-length single-char substit]] - rationale - graphify/dedup.py
- [[Block label-based merging of file-anchored non-code nodes across files (1284).]] - rationale - graphify/dedup.py
- [[Cross-file labels sharing a long prefix but diverging in a distinguishing     to]] - rationale - tests/test_dedup.py
- [[Deduplicate near-identical entities in a knowledge graph.      Args         nod]] - rationale - graphify/dedup.py
- [[Distinct symbols whose name is a strict prefix-extension of another must not]] - rationale - tests/test_dedup.py
- [[Document nodes are file-anchored too near-identical headings in different     f]] - rationale - tests/test_dedup.py
- [[Exact cross-file matches and a punctuation variant collapse to one     survivor]] - rationale - tests/test_dedup.py
- [[Pass 2's winner selection must consider only the verified pair (1247).      Pic]] - rationale - tests/test_dedup.py
- [[Pick the canonical survivor prefer no chunk suffix, then shorter ID.]] - rationale - graphify/dedup.py
- [[Rationale nodes are file-anchored like code (1205) parallel modules'     boile]] - rationale - tests/test_dedup.py
- [[The 1243 guard only drops the prefix bonus — a genuine cross-file     duplicate]] - rationale - tests/test_dedup.py
- [[The file-anchored guard only blocks cross-file pairs — near-identical     ration]] - rationale - tests/test_dedup.py
- [[Three identical-norm concepts across three files every input order must     yie]] - rationale - tests/test_dedup.py
- [[True when two labels carry different embedded numbers (1284).      Long labels]] - rationale - graphify/dedup.py
- [[Two `concept` nodes whose labels are byte-identical after _norm() but     live i]] - rationale - tests/test_dedup.py
- [[_UF]] - code - graphify/dedup.py
- [[_crossfile_fileanchored_blocked()]] - code - graphify/dedup.py
- [[_llm_tiebreak()]] - code - graphify/dedup.py
- [[_numeric_tokens_differ()]] - code - graphify/dedup.py
- [[_pick_winner()]] - code - graphify/dedup.py
- [[_short_label_blocked()]] - code - graphify/dedup.py
- [[deduplicate_entities()]] - code - graphify/dedup.py
- [[test_crossfile_concept_merge_is_order_independent()]] - code - tests/test_dedup.py
- [[test_crossfile_concept_merge_is_transitive()]] - code - tests/test_dedup.py
- [[test_crossfile_identical_concepts_merge_and_rewire()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_crossfile_document_headings()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_crossfile_rationale_boilerplate()]] - code - tests/test_dedup.py
- [[test_dedup_does_not_merge_crossfile_shared_prefix_divergence()]] - code - tests/test_dedup.py
- [[test_dedup_still_merges_crossfile_true_duplicates()]] - code - tests/test_dedup.py
- [[test_dedup_still_merges_samefile_rationale_duplicates()]] - code - tests/test_dedup.py
- [[test_dedup_survivor_does_not_inherit_false_origin_ast()]] - code - tests/test_dedup.py
- [[test_empty_inputs()]] - code - tests/test_dedup.py
- [[test_pass2_winner_union_does_not_pull_in_uncompared_same_label_nodes()]] - code - tests/test_dedup.py
- [[test_prefix_extension_symbols_not_merged()]] - code - tests/test_dedup.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/deduplicate_entities
SORT file.name ASC
```

## Connections to other communities
- 34 edges to [[_COMMUNITY_test_dedup.py]]
- 16 edges to [[_COMMUNITY_dedup.py]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 3 edges to [[_COMMUNITY_test_minhash.py]]
- 3 edges to [[_COMMUNITY__is_variant_pair]]
- 3 edges to [[_COMMUNITY_test_crossfile_identical_labels_stay_distinct_for_guarded_types]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]
- 1 edge to [[_COMMUNITY_build]]
- 1 edge to [[_COMMUNITY_test_numeric_tokens_differ_helper]]
- 1 edge to [[_COMMUNITY_test_collision_survivor_is_order_independent]]
- 1 edge to [[_COMMUNITY_test_cross_chunk_id_collision_emits_warning]]
- 1 edge to [[_COMMUNITY_test_cross_repo_guard_still_raises]]
- 1 edge to [[_COMMUNITY_test_crossfile_one_char_typo_concepts_still_merge]]
- 1 edge to [[_COMMUNITY_test_dedup_gapfill_is_order_independent_with_multiple_losers]]
- 1 edge to [[_COMMUNITY_test_dedup_no_attribute_merge_when_source_file_missing]]
- 1 edge to [[_COMMUNITY_test_dedup_summary_still_reports_exact_only]]
- 1 edge to [[_COMMUNITY_test_same_file_relabel_is_noted]]
- 1 edge to [[_COMMUNITY_test_same_id_same_source_file_no_warning]]
- 1 edge to [[_COMMUNITY__call_llm]]
- 1 edge to [[_COMMUNITY_test_llm_backends.py]]

## Top bridge nodes
- [[deduplicate_entities()]] - degree 70, connects to 17 communities
- [[_llm_tiebreak()]] - degree 15, connects to 4 communities
- [[_numeric_tokens_differ()]] - degree 6, connects to 3 communities
- [[_short_label_blocked()]] - degree 6, connects to 3 communities
- [[_UF]] - degree 9, connects to 2 communities