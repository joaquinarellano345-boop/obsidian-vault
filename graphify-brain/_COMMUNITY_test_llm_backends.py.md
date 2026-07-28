---
type: community
cohesion: 0.06
members: 68
---

# test_llm_backends.py

**Cohesion:** 0.06 - loosely connected
**Members:** 68 nodes

## Members
- [[Both extraction paths share the same hyperedge contract (the '3 or more     node]] - rationale - tests/test_llm_backends.py
- [[Call Azure OpenAI Service via the AzureOpenAI SDK client.]] - rationale - graphify/llm.py
- [[Detect a successful HTTP response that yielded no usable extraction.      A loca]] - rationale - graphify/llm.py
- [[Extract semantic nodesedges from a list of files using the given backend.]] - rationale - graphify/llm.py
- [[Inject a stub openai module with AzureOpenAI so _call_azure and     _azure_clien]] - rationale - tests/test_llm_backends.py
- [[Resolve the Ollama base URL. Honors an explicit OLLAMA_BASE_URL first     (verba]] - rationale - graphify/llm.py
- [[Resolve the temperature to send, honouring GRAPHIFY_LLM_TEMPERATURE.      Preced]] - rationale - graphify/llm.py
- [[Return a minimal claude -p --output-format json envelope.]] - rationale - tests/test_llm_backends.py
- [[Return the first configured API key for backend, or an empty string.]] - rationale - graphify/llm.py
- [[Return the name of whichever backend has an API key set, or None.      Priority]] - rationale - graphify/llm.py
- [[Tests for direct semantic-extraction backend selection.]] - rationale - tests/test_llm_backends.py
- [[True if `model` is a reasoning model that rejects an explicit temperature.]] - rationale - graphify/llm.py
- [[_backend_base_url()]] - code - tests/test_llm_backends.py
- [[_call_azure()]] - code - graphify/llm.py
- [[_clear_backend_env()]] - code - tests/test_llm_backends.py
- [[_get_backend_api_key()]] - code - graphify/llm.py
- [[_install_fake_azure_openai()]] - code - tests/test_llm_backends.py
- [[_make_cli_envelope()]] - code - tests/test_llm_backends.py
- [[_model_requires_default_temperature()]] - code - graphify/llm.py
- [[_ok()]] - code - tests/test_llm_backends.py
- [[_resolve_ollama_base_url()]] - code - graphify/llm.py
- [[_resolve_temperature()]] - code - graphify/llm.py
- [[_response_is_hollow()]] - code - graphify/llm.py
- [[detect_backend()]] - code - graphify/llm.py
- [[extract_files_direct()]] - code - graphify/llm.py
- [[parametrize_14]] - code
- [[subprocess.run must be called with errors='replace' so non-UTF-8 output     byte]] - rationale - tests/test_llm_backends.py
- [[test_backend_detection_prefers_gemini()]] - code - tests/test_llm_backends.py
- [[test_base_url_defaults_without_env()]] - code - tests/test_llm_backends.py
- [[test_base_url_env_overrides()]] - code - tests/test_llm_backends.py
- [[test_call_azure_uses_correct_client_params_and_max_completion_tokens()]] - code - tests/test_llm_backends.py
- [[test_call_claude_cli_passes_errors_replace_to_subprocess()]] - code - tests/test_llm_backends.py
- [[test_corpus_parallel_oversized_markdown_does_not_crash_on_fileslice()]] - code - tests/test_llm_backends.py
- [[test_detect_backend_azure_requires_endpoint_not_just_key()]] - code - tests/test_llm_backends.py
- [[test_detect_backend_returns_azure_when_both_vars_set()]] - code - tests/test_llm_backends.py
- [[test_extract_corpus_parallel_accepts_str_and_mixed_paths()]] - code - tests/test_llm_backends.py
- [[test_extract_corpus_parallel_ollama_parallel_env_restores_concurrency()]] - code - tests/test_llm_backends.py
- [[test_extract_corpus_parallel_ollama_runs_serially()]] - code - tests/test_llm_backends.py
- [[test_extract_files_direct_accepts_str_paths()]] - code - tests/test_llm_backends.py
- [[test_extract_files_direct_routes_gemini_through_openai_compat()]] - code - tests/test_llm_backends.py
- [[test_gemini_accepts_gemini_api_key()]] - code - tests/test_llm_backends.py
- [[test_gemini_accepts_google_api_key()]] - code - tests/test_llm_backends.py
- [[test_gemini_model_can_be_overridden_by_env()]] - code - tests/test_llm_backends.py
- [[test_llm_backends.py]] - code - tests/test_llm_backends.py
- [[test_missing_gemini_key_names_both_supported_env_vars()]] - code - tests/test_llm_backends.py
- [[test_model_requires_default_temperature_false_for_normal_models()]] - code - tests/test_llm_backends.py
- [[test_model_requires_default_temperature_true_for_reasoning_models()]] - code - tests/test_llm_backends.py
- [[test_native_extraction_prompt_matches_skill_spec_on_hyperedges()]] - code - tests/test_llm_backends.py
- [[test_openai_backend_detected()]] - code - tests/test_llm_backends.py
- [[test_openai_compat_backends_resolve_full_output_cap()]] - code - tests/test_llm_backends.py
- [[test_openai_compat_env_var_temperature_applied()]] - code - tests/test_llm_backends.py
- [[test_openai_compat_omits_temperature_for_o3_model()]] - code - tests/test_llm_backends.py
- [[test_openai_compat_sends_temperature_for_normal_model()]] - code - tests/test_llm_backends.py
- [[test_resolve_ollama_base_url_normalizes_host_without_scheme()]] - code - tests/test_llm_backends.py
- [[test_resolve_ollama_base_url_prefers_base_url()]] - code - tests/test_llm_backends.py
- [[test_resolve_ollama_base_url_preserves_normalized_host()]] - code - tests/test_llm_backends.py
- [[test_resolve_ollama_base_url_returns_default_without_env()]] - code - tests/test_llm_backends.py
- [[test_resolve_temperature_default_for_normal_model()]] - code - tests/test_llm_backends.py
- [[test_resolve_temperature_env_var_invalid_falls_back()]] - code - tests/test_llm_backends.py
- [[test_resolve_temperature_env_var_none_omits()]] - code - tests/test_llm_backends.py
- [[test_resolve_temperature_env_var_numeric_overrides()]] - code - tests/test_llm_backends.py
- [[test_resolve_temperature_omitted_for_reasoning_model()]] - code - tests/test_llm_backends.py
- [[test_response_is_hollow_accepts_real_extraction()]] - code - tests/test_llm_backends.py
- [[test_response_is_hollow_flags_empty_string()]] - code - tests/test_llm_backends.py
- [[test_response_is_hollow_flags_none_content()]] - code - tests/test_llm_backends.py
- [[test_response_is_hollow_flags_parsed_but_no_nodes_or_edges()]] - code - tests/test_llm_backends.py
- [[test_response_is_hollow_flags_whitespace_only()]] - code - tests/test_llm_backends.py
- [[test_str_path_entry_points_handle_edge_cases()]] - code - tests/test_llm_backends.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_llm_backendspy
SORT file.name ASC
```

## Connections to other communities
- 25 edges to [[_COMMUNITY__call_openai_compat]]
- 13 edges to [[_COMMUNITY_llm.py]]
- 9 edges to [[_COMMUNITY_test_ollama.py]]
- 8 edges to [[_COMMUNITY__call_llm]]
- 7 edges to [[_COMMUNITY_test_image_vision.py]]
- 7 edges to [[_COMMUNITY__extract_with_adaptive_retry]]
- 6 edges to [[_COMMUNITY__call_claude_cli]]
- 5 edges to [[_COMMUNITY_test_chunking.py]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 4 edges to [[_COMMUNITY__extraction_system]]
- 4 edges to [[_COMMUNITY_prs.py]]
- 2 edges to [[_COMMUNITY_dedup.py]]
- 2 edges to [[_COMMUNITY_test_evidence_binding.py]]
- 1 edge to [[_COMMUNITY_deduplicate_entities]]
- 1 edge to [[_COMMUNITY__parse_llm_json]]
- 1 edge to [[_COMMUNITY_test_labeling.py]]
- 1 edge to [[_COMMUNITY__load_custom_providers]]

## Top bridge nodes
- [[extract_files_direct()]] - degree 37, connects to 10 communities
- [[test_llm_backends.py]] - degree 78, connects to 6 communities
- [[_get_backend_api_key()]] - degree 17, connects to 6 communities
- [[detect_backend()]] - degree 21, connects to 5 communities
- [[_response_is_hollow()]] - degree 12, connects to 5 communities