---
type: community
cohesion: 0.07
members: 30
---

# TestSubprocessEncoding

**Cohesion:** 0.07 - loosely connected
**Members:** 30 nodes

## Members
- [[._make_completed()]] - code - tests/test_charmap_encoding.py
- [[.test_call_llm_claude_cli_subprocess_encoding()]] - code - tests/test_charmap_encoding.py
- [[.test_cp1252_would_fail_but_utf8_succeeds()]] - code - tests/test_charmap_encoding.py
- [[.test_failure_count_in_merged_result()]] - code - tests/test_charmap_encoding.py
- [[.test_no_false_alarm_when_all_chunks_succeed()]] - code - tests/test_charmap_encoding.py
- [[.test_read_files_produces_utf8_safe_prompt()]] - code - tests/test_charmap_encoding.py
- [[.test_subprocess_called_with_utf8_encoding()]] - code - tests/test_charmap_encoding.py
- [[.test_subprocess_does_not_use_text_true_without_encoding()]] - code - tests/test_charmap_encoding.py
- [[.test_subprocess_encoding_kwarg_in_extract_files_direct()]] - code - tests/test_charmap_encoding.py
- [[.test_summary_printed_when_chunks_fail()]] - code - tests/test_charmap_encoding.py
- [[.test_unicode_chars_survive_subprocess_roundtrip()]] - code - tests/test_charmap_encoding.py
- [[A summary line must appear on stderr when ≥1 chunk fails.]] - rationale - tests/test_charmap_encoding.py
- [[Build a mock CompletedProcess with a valid JSON envelope.]] - rationale - tests/test_charmap_encoding.py
- [[Demonstrate the exact failure mode that is now fixed.          The prompt string]] - rationale - tests/test_charmap_encoding.py
- [[End-to-end path write unicode file → extract_files_direct → subprocess.]] - rationale - tests/test_charmap_encoding.py
- [[Exercises the same code path as the rsl-siege-manager reproduction     without r]] - rationale - tests/test_charmap_encoding.py
- [[Regression tests for UnicodeEncodeError on Windows cp1252 console.  On Windows w]] - rationale - tests/test_charmap_encoding.py
- [[TestLoudChunkFailure]] - code - tests/test_charmap_encoding.py
- [[TestSubprocessEncoding]] - code - tests/test_charmap_encoding.py
- [[TestSubstitutionValidation]] - code - tests/test_charmap_encoding.py
- [[When all chunks succeed, failed_chunks must be 0 and no failure         summary]] - rationale - tests/test_charmap_encoding.py
- [[When chunks fail, extract_corpus_parallel must record failed_chunks  0]] - rationale - tests/test_charmap_encoding.py
- [[Writing a file with → ✅ ≥ then passing its content through         _call_claude_]] - rationale - tests/test_charmap_encoding.py
- [[_call_claude_cli must pass encoding=utf-8 to subprocess.run so that     non-AS]] - rationale - tests/test_charmap_encoding.py
- [[_call_llm with backend='claude-cli' must also use encoding='utf-8'.]] - rationale - tests/test_charmap_encoding.py
- [[_read_files must return a string that encodes cleanly to UTF-8.]] - rationale - tests/test_charmap_encoding.py
- [[extract_corpus_parallel must surface chunk failures loudly — either via     non-]] - rationale - tests/test_charmap_encoding.py
- [[subprocess.run must be invoked with encoding='utf-8'.]] - rationale - tests/test_charmap_encoding.py
- [[test_charmap_encoding.py]] - code - tests/test_charmap_encoding.py
- [[text=True without encoding= relies on the locale codec (cp1252 on Windows).]] - rationale - tests/test_charmap_encoding.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/TestSubprocessEncoding
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_llm.py]]

## Top bridge nodes
- [[test_charmap_encoding.py]] - degree 5, connects to 1 community