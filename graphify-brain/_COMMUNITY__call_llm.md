---
type: community
cohesion: 0.07
members: 34
---

# _call_llm

**Cohesion:** 0.07 - loosely connected
**Members:** 34 nodes

## Members
- [[Call Anthropic Claude directly (not via OpenAI compat layer).]] - rationale - graphify/llm.py
- [[Call Azure OpenAI Service via the AzureOpenAI SDK client.]] - rationale - graphify/llm.py
- [[Construct an AzureOpenAI client with env-driven api_version and timeout.]] - rationale - graphify/llm.py
- [[Default retry count is generous (so 429s are absorbed, 1523); env overrides.]] - rationale - tests/test_llm_backends.py
- [[How many times the provider SDK retries a transient error (notably HTTP 429]] - rationale - graphify/llm.py
- [[Inject a stub openai module with AzureOpenAI so _call_azure and     _azure_clien]] - rationale - tests/test_llm_backends.py
- [[Opt-in (GRAPHIFY_DISABLE_THINKING) to send ``{thinking {type disabled}}`]] - rationale - graphify/llm.py
- [[Package-missing message that works for the recommended `uv tool` install.      `]] - rationale - graphify/llm.py
- [[Parse the JSON returned by `claude -p --output-format json`.      Older Claude C]] - rationale - graphify/llm.py
- [[Same 1442 fix for the OpenAI-compatible branch of _call_llm.]] - rationale - tests/test_llm_backends.py
- [[Send a plain-text prompt to `backend` and return the model's text reply.      Wh]] - rationale - graphify/llm.py
- [[The claude backend must be installable via an extra, and the missing-package mes]] - rationale - tests/test_backend_extras.py
- [[The label_simple_completion path must spawn the resolved claude.cmd on     Wind]] - rationale - tests/test_claude_cli_backend.py
- [[The secondary dispatch path (_call_llm, used by the dedup tiebreaker)     must b]] - rationale - tests/test_llm_backends.py
- [[_azure_client()]] - code - graphify/llm.py
- [[_backend_pkg_hint()]] - code - graphify/llm.py
- [[_call_azure()]] - code - graphify/llm.py
- [[_call_claude()]] - code - graphify/llm.py
- [[_call_llm()]] - code - graphify/llm.py
- [[_claude_cli_envelope()]] - code - graphify/llm.py
- [[_extras()]] - code - tests/test_backend_extras.py
- [[_install_fake_azure_openai()]] - code - tests/test_llm_backends.py
- [[_resolve_max_retries()]] - code - graphify/llm.py
- [[_thinking_disabled_via_env()]] - code - graphify/llm.py
- [[test_anthropic_extra_exists()]] - code - tests/test_backend_extras.py
- [[test_anthropic_in_all_extra()]] - code - tests/test_backend_extras.py
- [[test_backend_extras.py]] - code - tests/test_backend_extras.py
- [[test_backend_pkg_hint_points_at_uv_tool_and_extra()]] - code - tests/test_backend_extras.py
- [[test_call_azure_uses_correct_client_params_and_max_completion_tokens()]] - code - tests/test_llm_backends.py
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
- 15 edges to [[_COMMUNITY_test_llm_backends.py]]
- 13 edges to [[_COMMUNITY_llm.py]]
- 6 edges to [[_COMMUNITY__call_claude_cli]]
- 2 edges to [[_COMMUNITY_test_chunking.py]]
- 2 edges to [[_COMMUNITY_test_image_vision.py]]
- 2 edges to [[_COMMUNITY__parse_llm_json]]
- 2 edges to [[_COMMUNITY_detect_backend]]
- 1 edge to [[_COMMUNITY_dedup.py]]
- 1 edge to [[_COMMUNITY__llm_tiebreak]]
- 1 edge to [[_COMMUNITY_prs.py]]

## Top bridge nodes
- [[_call_llm()]] - degree 23, connects to 7 communities
- [[_call_claude()]] - degree 12, connects to 6 communities
- [[_call_azure()]] - degree 8, connects to 4 communities
- [[_backend_pkg_hint()]] - degree 7, connects to 2 communities
- [[_resolve_max_retries()]] - degree 7, connects to 2 communities