---
type: community
cohesion: 0.10
members: 21
---

# _call_llm

**Cohesion:** 0.10 - loosely connected
**Members:** 21 nodes

## Members
- [[Build Bedrock inferenceConfig, honouring GRAPHIFY_LLM_TEMPERATURE.      Bedrock']] - rationale - graphify/llm.py
- [[Construct an AzureOpenAI client with env-driven api_version and timeout.]] - rationale - graphify/llm.py
- [[Default retry count is generous (so 429s are absorbed, 1523); env overrides.]] - rationale - tests/test_llm_backends.py
- [[How many times the provider SDK retries a transient error (notably HTTP 429]] - rationale - graphify/llm.py
- [[Opt-in (GRAPHIFY_DISABLE_THINKING) to send ``{thinking {type disabled}}`]] - rationale - graphify/llm.py
- [[Parse the JSON returned by `claude -p --output-format json`.      Older Claude C]] - rationale - graphify/llm.py
- [[Same 1442 fix for the OpenAI-compatible branch of _call_llm.]] - rationale - tests/test_llm_backends.py
- [[Send a plain-text prompt to `backend` and return the model's text reply.      Wh]] - rationale - graphify/llm.py
- [[The label_simple_completion path must spawn the resolved claude.cmd on     Wind]] - rationale - tests/test_claude_cli_backend.py
- [[The secondary dispatch path (_call_llm, used by the dedup tiebreaker)     must b]] - rationale - tests/test_llm_backends.py
- [[_azure_client()]] - code - graphify/llm.py
- [[_bedrock_inference_config()]] - code - graphify/llm.py
- [[_call_llm()]] - code - graphify/llm.py
- [[_claude_cli_envelope()]] - code - graphify/llm.py
- [[_resolve_max_retries()]] - code - graphify/llm.py
- [[_thinking_disabled_via_env()]] - code - graphify/llm.py
- [[test_call_llm_claude_cli_branch_honours_timeout()]] - code - tests/test_claude_cli_backend.py
- [[test_call_llm_claude_client_built_with_timeout_and_retries()]] - code - tests/test_llm_backends.py
- [[test_call_llm_openai_compat_client_built_with_timeout_and_retries()]] - code - tests/test_llm_backends.py
- [[test_resolve_max_retries_default_and_env()]] - code - tests/test_llm_backends.py
- [[test_simple_completion_resolves_cmd_shim_on_windows()]] - code - tests/test_claude_cli_backend.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_call_llm
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_test_llm_backends.py]]
- 7 edges to [[_COMMUNITY_llm.py]]
- 5 edges to [[_COMMUNITY__call_claude_cli]]
- 2 edges to [[_COMMUNITY_dedup.py]]
- 2 edges to [[_COMMUNITY__extraction_system]]
- 2 edges to [[_COMMUNITY__call_openai_compat]]
- 1 edge to [[_COMMUNITY_deduplicate_entities]]
- 1 edge to [[_COMMUNITY_test_image_vision.py]]
- 1 edge to [[_COMMUNITY_prs.py]]
- 1 edge to [[_COMMUNITY_test_ollama.py]]

## Top bridge nodes
- [[_call_llm()]] - degree 23, connects to 8 communities
- [[_resolve_max_retries()]] - degree 7, connects to 3 communities
- [[_bedrock_inference_config()]] - degree 5, connects to 3 communities
- [[_azure_client()]] - degree 5, connects to 2 communities
- [[_claude_cli_envelope()]] - degree 4, connects to 2 communities