---
type: community
cohesion: 0.07
members: 39
---

# llm.py

**Cohesion:** 0.07 - loosely connected
**Members:** 39 nodes

## Members
- [[Append a chunk result into the running merged accumulator.]] - rationale - graphify/llm.py
- [[Defang known chat-template  jailbreak control tokens in untrusted text.      In]] - rationale - graphify/llm.py
- [[Demonstrates the bug fix.      The full batch of 4 communities triggers malforme]] - rationale - tests/test_label_retry.py
- [[Honour GRAPHIFY_MAX_OUTPUT_TOKENS env var override, else use backend default.]] - rationale - graphify/llm.py
- [[Label a batch of communities, splitting in half and retrying on parse failure.]] - rationale - graphify/llm.py
- [[Map each dispatched text unit's resolved path to the (lower-cased, capped)     s]] - rationale - graphify/llm.py
- [[Parse the backend's JSON ``{cid name}`` reply. Raises on non-JSON or a     non-]] - rationale - graphify/llm.py
- [[Path_43]] - code
- [[Return a text-like file's content for the extraction prompt.      Most files are]] - rationale - graphify/llm.py
- [[Return a tiktoken encoder for accurate token counts, or None if tiktoken     is]] - rationale - graphify/llm.py
- [[Return accepted API-key environment variables for a backend.]] - rationale - graphify/llm.py
- [[Return fileslice contents formatted for the extraction prompt.      Each unit i]] - rationale - graphify/llm.py
- [[Return the resolved path only when it stays inside ``root``.]] - rationale - graphify/llm.py
- [[Tests for ANTHROPIC_BASE_URL  ANTHROPIC_MODEL overrides on the claude backend.]] - rationale - tests/test_anthropic_custom_endpoint.py
- [[Tests for OPENAI_BASE_URL  OPENAI_MODEL overrides on the openai backend.  These]] - rationale - tests/test_openai_custom_endpoint.py
- [[Tests for graphify.llm._label_batch_with_retry — adaptive split-and-retry on JSO]] - rationale - tests/test_label_retry.py
- [[Wrap one file's content in a labelled, hash-stamped untrusted-data block.      T]] - rationale - graphify/llm.py
- [[_backend_env_keys()]] - code - graphify/llm.py
- [[_dispatched_source_text()]] - code - graphify/llm.py
- [[_file_to_text()]] - code - graphify/llm.py
- [[_get_tokenizer()]] - code - graphify/llm.py
- [[_label_batch_with_retry()]] - code - graphify/llm.py
- [[_merge_into()]] - code - graphify/llm.py
- [[_neutralise_injection_sentinels()]] - code - graphify/llm.py
- [[_parse_label_response()]] - code - graphify/llm.py
- [[_read_files()]] - code - graphify/llm.py
- [[_resolve_max_tokens()]] - code - graphify/llm.py
- [[_resolve_under_root()]] - code - graphify/llm.py
- [[_wrap_untrusted()]] - code - graphify/llm.py
- [[llm.py]] - code - graphify/llm.py
- [[test_anthropic_custom_endpoint.py]] - code - tests/test_anthropic_custom_endpoint.py
- [[test_claude_base_url_and_model_env_override()]] - code - tests/test_anthropic_custom_endpoint.py
- [[test_claude_defaults_without_env()]] - code - tests/test_anthropic_custom_endpoint.py
- [[test_graphify_openai_model_wins_over_openai_model()]] - code - tests/test_openai_custom_endpoint.py
- [[test_label_batch_recovers_via_split_on_invalid_json()]] - code - tests/test_label_retry.py
- [[test_label_retry.py]] - code - tests/test_label_retry.py
- [[test_openai_base_url_and_model_env_override()]] - code - tests/test_openai_custom_endpoint.py
- [[test_openai_custom_endpoint.py]] - code - tests/test_openai_custom_endpoint.py
- [[test_openai_defaults_without_env()]] - code - tests/test_openai_custom_endpoint.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/llmpy
SORT file.name ASC
```

## Connections to other communities
- 18 edges to [[_COMMUNITY_test_image_vision.py]]
- 13 edges to [[_COMMUNITY_test_file_slice.py]]
- 13 edges to [[_COMMUNITY_test_llm_backends.py]]
- 7 edges to [[_COMMUNITY__call_llm]]
- 7 edges to [[_COMMUNITY_test_chunking.py]]
- 6 edges to [[_COMMUNITY__call_claude_cli]]
- 5 edges to [[_COMMUNITY_test_evidence_binding.py]]
- 5 edges to [[_COMMUNITY__extract_with_adaptive_retry]]
- 5 edges to [[_COMMUNITY_test_labeling.py]]
- 4 edges to [[_COMMUNITY_save_semantic_cache]]
- 4 edges to [[_COMMUNITY__extraction_system]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 4 edges to [[_COMMUNITY__parse_llm_json]]
- 3 edges to [[_COMMUNITY_test_ollama.py]]
- 2 edges to [[_COMMUNITY_detect.py]]
- 2 edges to [[_COMMUNITY__call_openai_compat]]
- 2 edges to [[_COMMUNITY_dedup.py]]
- 2 edges to [[_COMMUNITY__load_custom_providers]]
- 1 edge to [[_COMMUNITY_prs.py]]
- 1 edge to [[_COMMUNITY_TestSubprocessEncoding]]

## Top bridge nodes
- [[llm.py]] - degree 98, connects to 20 communities
- [[Path_43]] - degree 12, connects to 6 communities
- [[_read_files()]] - degree 12, connects to 3 communities
- [[_dispatched_source_text()]] - degree 8, connects to 2 communities
- [[_file_to_text()]] - degree 7, connects to 2 communities