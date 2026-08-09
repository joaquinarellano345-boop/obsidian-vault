---
source_file: "tests/test_word_count_cache.py"
type: "code"
community: "test_cache.py"
location: "L1"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/test_cachepy
---

# test_word_count_cache.py

## Connections
- [[1656 — word counts are cached against each file's stat signature so detect() do]] - `rationale_for` [EXTRACTED]
- [[cache.py]] - `imports_from` [EXTRACTED]
- [[test_file_hash_ignores_legacy_unsalted_entry()]] - `contains` [EXTRACTED]
- [[test_file_hash_is_order_independent_across_roots()]] - `contains` [EXTRACTED]
- [[test_word_count_augments_existing_hash_entry()]] - `contains` [EXTRACTED]
- [[test_word_count_cached_until_file_changes()]] - `contains` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/test_cachepy