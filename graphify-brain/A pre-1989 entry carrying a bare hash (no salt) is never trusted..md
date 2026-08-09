---
source_file: "tests/test_word_count_cache.py"
type: "rationale"
community: "test_cache.py"
location: "L89"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/test_cachepy
---

# A pre-#1989 entry carrying a bare "hash" (no salt) is never trusted.

## Connections
- [[test_file_hash_ignores_legacy_unsalted_entry()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/test_cachepy