---
type: community
cohesion: 0.04
members: 59
---

# llm.py

**Cohesion:** 0.04 - loosely connected
**Members:** 59 nodes

## Members
- [[.b64()]] - code - graphify/llm.py
- [[.bedrock_format()]] - code - graphify/llm.py
- [[A single image destined for a vision request.      `raw` is None when the image]] - rationale - graphify/llm.py
- [[Append a chunk result into the running merged accumulator.]] - rationale - graphify/llm.py
- [[BaseException]] - code
- [[Build Bedrock inferenceConfig, honouring GRAPHIFY_LLM_TEMPERATURE.      Bedrock']] - rationale - graphify/llm.py
- [[Build the Bedrock Converse user content list (raw bytes, not base64).]] - rationale - graphify/llm.py
- [[Call AWS Bedrock via boto3 Converse API using the standard AWS credential chain.]] - rationale - graphify/llm.py
- [[Defang known chat-template  jailbreak control tokens in untrusted text.      In]] - rationale - graphify/llm.py
- [[Demonstrates the bug fix.      The full batch of 4 communities triggers malforme]] - rationale - tests/test_label_retry.py
- [[Estimate USD cost for a given token count using published pricing.]] - rationale - graphify/llm.py
- [[Heuristically classify an exception as a context-window overflow.      Different]] - rationale - graphify/llm.py
- [[Honour GRAPHIFY_MAX_OUTPUT_TOKENS env var override, else use backend default.]] - rationale - graphify/llm.py
- [[Label a batch of communities, splitting in half and retrying on parse failure.]] - rationale - graphify/llm.py
- [[Parse the backend's JSON ``{cid name}`` reply. Raises on non-JSON or a     non-]] - rationale - graphify/llm.py
- [[Return a tiktoken encoder for accurate token counts, or None if tiktoken     is]] - rationale - graphify/llm.py
- [[Return accepted API-key environment variables for a backend.]] - rationale - graphify/llm.py
- [[Return user-facing accepted API-key variable names.]] - rationale - graphify/llm.py
- [[Source paths covered by a chunk, for marking a chunk that truncated to an     EM]] - rationale - graphify/llm.py
- [[Tests for ANTHROPIC_BASE_URL  ANTHROPIC_MODEL overrides on the claude backend.]] - rationale - tests/test_anthropic_custom_endpoint.py
- [[Tests for OPENAI_BASE_URL  OPENAI_MODEL overrides on the openai backend.  These]] - rationale - tests/test_openai_custom_endpoint.py
- [[Tests for graphify.llm._label_batch_with_retry — adaptive split-and-retry on JSO]] - rationale - tests/test_label_retry.py
- [[Text block listing the images so the model emits one node per image.      Always]] - rationale - graphify/llm.py
- [[Union of the ``_partial_files`` carried by each result (survives merges).]] - rationale - graphify/llm.py
- [[Wrap one file's content in a labelled, hash-stamped untrusted-data block.      T]] - rationale - graphify/llm.py
- [[_ImageRef]] - code - graphify/llm.py
- [[_backend_env_keys()]] - code - graphify/llm.py
- [[_bedrock_content()]] - code - graphify/llm.py
- [[_bedrock_inference_config()]] - code - graphify/llm.py
- [[_call_bedrock()]] - code - graphify/llm.py
- [[_chunk_partial_files()]] - code - graphify/llm.py
- [[_format_backend_env_keys()]] - code - graphify/llm.py
- [[_get_tokenizer()]] - code - graphify/llm.py
- [[_image_notes()]] - code - graphify/llm.py
- [[_label_batch_with_retry()]] - code - graphify/llm.py
- [[_looks_like_context_exceeded()]] - code - graphify/llm.py
- [[_merge_into()]] - code - graphify/llm.py
- [[_merged_partial_files()]] - code - graphify/llm.py
- [[_neutralise_injection_sentinels()]] - code - graphify/llm.py
- [[_parse_label_response()]] - code - graphify/llm.py
- [[_resolve_max_tokens()]] - code - graphify/llm.py
- [[_with_image_notes()]] - code - graphify/llm.py
- [[_wrap_untrusted()]] - code - graphify/llm.py
- [[estimate_cost()]] - code - graphify/llm.py
- [[llm.py]] - code - graphify/llm.py
- [[test_anthropic_custom_endpoint.py]] - code - tests/test_anthropic_custom_endpoint.py
- [[test_backend_registered_with_zero_cost()]] - code - tests/test_claude_cli_backend.py
- [[test_bedrock_content_uses_raw_bytes()]] - code - tests/test_image_vision.py
- [[test_claude_base_url_and_model_env_override()]] - code - tests/test_anthropic_custom_endpoint.py
- [[test_claude_defaults_without_env()]] - code - tests/test_anthropic_custom_endpoint.py
- [[test_estimate_cost_azure_no_keyerror()]] - code - tests/test_llm_backends.py
- [[test_graphify_openai_model_wins_over_openai_model()]] - code - tests/test_openai_custom_endpoint.py
- [[test_label_batch_recovers_via_split_on_invalid_json()]] - code - tests/test_label_retry.py
- [[test_label_retry.py]] - code - tests/test_label_retry.py
- [[test_looks_like_context_exceeded_ignores_unrelated_errors()]] - code - tests/test_llm_backends.py
- [[test_looks_like_context_exceeded_matches_common_messages()]] - code - tests/test_llm_backends.py
- [[test_openai_base_url_and_model_env_override()]] - code - tests/test_openai_custom_endpoint.py
- [[test_openai_custom_endpoint.py]] - code - tests/test_openai_custom_endpoint.py
- [[test_openai_defaults_without_env()]] - code - tests/test_openai_custom_endpoint.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/llmpy
SORT file.name ASC
```

## Connections to other communities
- 17 edges to [[_COMMUNITY_test_image_vision.py]]
- 16 edges to [[_COMMUNITY_test_llm_backends.py]]
- 14 edges to [[_COMMUNITY_test_file_slice.py]]
- 13 edges to [[_COMMUNITY__call_llm]]
- 12 edges to [[_COMMUNITY_test_chunking.py]]
- 8 edges to [[_COMMUNITY__call_claude_cli]]
- 7 edges to [[_COMMUNITY_cli.py]]
- 6 edges to [[_COMMUNITY_detect_backend]]
- 5 edges to [[_COMMUNITY_test_labeling.py]]
- 5 edges to [[_COMMUNITY__parse_llm_json]]
- 4 edges to [[_COMMUNITY_save_semantic_cache]]
- 3 edges to [[_COMMUNITY_test_evidence_binding.py]]
- 2 edges to [[_COMMUNITY__load_custom_providers]]
- 1 edge to [[_COMMUNITY_dedup.py]]
- 1 edge to [[_COMMUNITY__llm_tiebreak]]
- 1 edge to [[_COMMUNITY_detect.py]]
- 1 edge to [[_COMMUNITY_prs.py]]
- 1 edge to [[_COMMUNITY_TestSubprocessEncoding]]
- 1 edge to [[_COMMUNITY_test_ollama_retry_cap.py]]

## Top bridge nodes
- [[llm.py]] - degree 98, connects to 17 communities
- [[_ImageRef]] - degree 16, connects to 5 communities
- [[_format_backend_env_keys()]] - degree 9, connects to 5 communities
- [[_call_bedrock()]] - degree 10, connects to 4 communities
- [[_with_image_notes()]] - degree 7, connects to 2 communities