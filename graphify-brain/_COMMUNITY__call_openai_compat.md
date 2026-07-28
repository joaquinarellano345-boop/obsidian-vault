---
type: community
cohesion: 0.11
members: 32
---

# _call_openai_compat

**Cohesion:** 0.11 - loosely connected
**Members:** 32 nodes

## Members
- [[1686 - a wedged local Ollama request must not multiply --api-timeout by the SDK]] - rationale - tests/test_ollama_retry_cap.py
- [[Build a minimal stand-in for an `openai` SDK ChatCompletion response.]] - rationale - tests/test_llm_backends.py
- [[Call any OpenAI-compatible API (Kimi, OpenAI, etc.) and return parsed JSON.]] - rationale - graphify/llm.py
- [[Inject a stub `openai` module so `_call_openai_compat` can run without     the r]] - rationale - tests/test_llm_backends.py
- [[Like _install_fake_openai but records kwargs passed to create().]] - rationale - tests/test_llm_backends.py
- [[The OpenAI-compatible client (kimiopenaigeminideepseekollama) is built with]] - rationale - tests/test_llm_backends.py
- [[_call_openai_compat()]] - code - graphify/llm.py
- [[_capture_client_kwargs()]] - code - tests/test_ollama_retry_cap.py
- [[_fake_openai_response()]] - code - tests/test_llm_backends.py
- [[_install_capturing_openai()]] - code - tests/test_llm_backends.py
- [[_install_fake_openai()]] - code - tests/test_llm_backends.py
- [[test_api_timeout_is_passed_to_client()]] - code - tests/test_ollama_retry_cap.py
- [[test_call_openai_compat_explicit_extra_body_skips_ollama_auto_derive()]] - code - tests/test_llm_backends.py
- [[test_call_openai_compat_extra_body_wins_over_moonshot_default()]] - code - tests/test_llm_backends.py
- [[test_call_openai_compat_preserves_real_finish_reason()]] - code - tests/test_llm_backends.py
- [[test_call_openai_compat_relabels_empty_content_as_length()]] - code - tests/test_llm_backends.py
- [[test_call_openai_compat_relabels_none_content_as_length()]] - code - tests/test_llm_backends.py
- [[test_call_openai_compat_relabels_unparseable_json_as_length()]] - code - tests/test_llm_backends.py
- [[test_call_openai_compat_uses_explicit_extra_body()]] - code - tests/test_llm_backends.py
- [[test_cloud_backend_keeps_default_retries()]] - code - tests/test_ollama_retry_cap.py
- [[test_deepseek_thinking_disabled_via_env()]] - code - tests/test_llm_backends.py
- [[test_deepseek_thinking_on_by_default()]] - code - tests/test_llm_backends.py
- [[test_explicit_extra_body_wins_over_thinking_env()]] - code - tests/test_llm_backends.py
- [[test_non_ollama_backend_gets_no_num_ctx_extra_body()]] - code - tests/test_llm_backends.py
- [[test_ollama_defaults_to_zero_sdk_retries()]] - code - tests/test_ollama_retry_cap.py
- [[test_ollama_extra_body_sets_num_ctx_and_keep_alive()]] - code - tests/test_llm_backends.py
- [[test_ollama_honors_explicit_max_retries()]] - code - tests/test_ollama_retry_cap.py
- [[test_ollama_num_ctx_env_override()]] - code - tests/test_llm_backends.py
- [[test_ollama_num_ctx_scales_with_small_token_budget()]] - code - tests/test_llm_backends.py
- [[test_ollama_retry_cap.py]] - code - tests/test_ollama_retry_cap.py
- [[test_openai_compat_client_built_with_retries()]] - code - tests/test_llm_backends.py
- [[test_openai_compat_forces_non_streaming_response()]] - code - tests/test_llm_backends.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_call_openai_compat
SORT file.name ASC
```

## Connections to other communities
- 25 edges to [[_COMMUNITY_test_llm_backends.py]]
- 4 edges to [[_COMMUNITY_test_image_vision.py]]
- 2 edges to [[_COMMUNITY_llm.py]]
- 2 edges to [[_COMMUNITY__call_llm]]
- 2 edges to [[_COMMUNITY__extraction_system]]
- 1 edge to [[_COMMUNITY__call_claude_cli]]
- 1 edge to [[_COMMUNITY__parse_llm_json]]

## Top bridge nodes
- [[_call_openai_compat()]] - degree 34, connects to 7 communities
- [[_install_capturing_openai()]] - degree 16, connects to 1 community
- [[_fake_openai_response()]] - degree 7, connects to 1 community
- [[test_ollama_retry_cap.py]] - degree 7, connects to 1 community
- [[_install_fake_openai()]] - degree 6, connects to 1 community