---
type: community
cohesion: 0.05
members: 54
---

# _call_claude_cli

**Cohesion:** 0.05 - loosely connected
**Members:** 54 nodes

## Members
- [[2076 review with --json-schema the CLI puts the constrained object in     `str]] - rationale - tests/test_claude_cli_backend.py
- [[--system-prompt must NOT be used the CLI ignores its 'raw JSON only'     direct]] - rationale - tests/test_claude_cli_backend.py
- [[A probe that fails to run is treated as unsupported (safe fallback) and     cach]] - rationale - tests/test_claude_cli_backend.py
- [[Call Claude via the locally-installed Claude Code CLI (`claude -p`).      Routes]] - rationale - graphify/llm.py
- [[Honour GRAPHIFY_API_TIMEOUT env var override, else use default (seconds).]] - rationale - graphify/llm.py
- [[If `claude.cmd` is somehow unavailable but `claude` resolves     (e.g. WSL-style]] - rationale - tests/test_claude_cli_backend.py
- [[If neither `claude.cmd` nor `claude` are on PATH on Windows,     raise the stand]] - rationale - tests/test_claude_cli_backend.py
- [[Older CLIs without --json-schema must not receive the flag (it would be     an u]] - rationale - tests/test_claude_cli_backend.py
- [[On Windows, npm installs `claude.ps1` alongside `claude.cmd`.     `CreateProcess]] - rationale - tests/test_claude_cli_backend.py
- [[On non-Windows platforms, behaviour is unchanged bare `claude`     is passed to]] - rationale - tests/test_claude_cli_backend.py
- [[Return True if this Claude Code CLI accepts ``--json-schema``.      Structured o]] - rationale - graphify/llm.py
- [[Return a minimal claude -p --output-format json envelope.]] - rationale - tests/test_llm_backends.py
- [[Tests for the `claude-cli` backend (855856).  Mocks subprocess.run + shutil.w]] - rationale - tests/test_claude_cli_backend.py
- [[The untrusted_source guardrails from _extraction_system must survive     the m]] - rationale - tests/test_claude_cli_backend.py
- [[The full extraction schema, an explicit imperative, and the source must     all]] - rationale - tests/test_claude_cli_backend.py
- [[When errors='replace' is set, non-UTF-8 bytes in stderr produce replacement]] - rationale - tests/test_llm_backends.py
- [[When the CLI advertises --json-schema, it is passed with a schema that     pins]] - rationale - tests/test_claude_cli_backend.py
- [[_call_claude_cli()]] - code - graphify/llm.py
- [[_claude_cli_supports_json_schema()]] - code - graphify/llm.py
- [[_make_cli_envelope()]] - code - tests/test_llm_backends.py
- [[_no_window_kwargs()]] - code - graphify/llm.py
- [[_resolve_api_timeout()]] - code - graphify/llm.py
- [[fake_claude()]] - code - tests/test_claude_cli_backend.py
- [[subprocess kwargs that suppress the console window claude.cmd would     otherwis]] - rationale - graphify/llm.py
- [[subprocess.run must be called with errors='replace' so non-UTF-8 output     byte]] - rationale - tests/test_llm_backends.py
- [[test_call_claude_cli_passes_errors_replace_to_subprocess()]] - code - tests/test_llm_backends.py
- [[test_call_claude_cli_tolerates_non_utf8_in_stderr()]] - code - tests/test_llm_backends.py
- [[test_claude_cli_backend.py]] - code - tests/test_claude_cli_backend.py
- [[test_claude_cli_extraction_honours_timeout()]] - code - tests/test_claude_cli_backend.py
- [[test_extract_files_direct_dispatches_to_claude_cli()]] - code - tests/test_claude_cli_backend.py
- [[test_extraction_instructions_ride_in_user_turn()]] - code - tests/test_claude_cli_backend.py
- [[test_finish_reason_length_on_max_tokens()]] - code - tests/test_claude_cli_backend.py
- [[test_json_schema_flag_absent_when_cli_lacks_it()]] - code - tests/test_claude_cli_backend.py
- [[test_json_schema_flag_added_when_cli_supports_it()]] - code - tests/test_claude_cli_backend.py
- [[test_no_session_persistence_flag_in_subprocess()]] - code - tests/test_claude_cli_backend.py
- [[test_no_system_prompt_flag_in_subprocess()]] - code - tests/test_claude_cli_backend.py
- [[test_non_windows_uses_bare_claude()]] - code - tests/test_claude_cli_backend.py
- [[test_prefers_structured_output_over_prose_result()]] - code - tests/test_claude_cli_backend.py
- [[test_raises_on_garbage_envelope()]] - code - tests/test_claude_cli_backend.py
- [[test_raises_on_nonzero_exit()]] - code - tests/test_claude_cli_backend.py
- [[test_raises_when_cli_missing()]] - code - tests/test_claude_cli_backend.py
- [[test_resolve_api_timeout_default()]] - code - tests/test_claude_cli_backend.py
- [[test_resolve_api_timeout_env_override()]] - code - tests/test_claude_cli_backend.py
- [[test_resolve_api_timeout_ignores_invalid()]] - code - tests/test_claude_cli_backend.py
- [[test_resolve_api_timeout_ignores_nonpositive()]] - code - tests/test_claude_cli_backend.py
- [[test_returns_parsed_nodes_and_edges()]] - code - tests/test_claude_cli_backend.py
- [[test_supports_json_schema_detects_flag_in_help()]] - code - tests/test_claude_cli_backend.py
- [[test_supports_json_schema_false_and_cached_on_probe_error()]] - code - tests/test_claude_cli_backend.py
- [[test_supports_json_schema_false_when_flag_absent()]] - code - tests/test_claude_cli_backend.py
- [[test_token_accounting_includes_cache()]] - code - tests/test_claude_cli_backend.py
- [[test_user_turn_preserves_untrusted_source_guardrails()]] - code - tests/test_claude_cli_backend.py
- [[test_windows_falls_back_to_bare_claude_when_cmd_missing()]] - code - tests/test_claude_cli_backend.py
- [[test_windows_prefers_claude_cmd_over_bare_claude()]] - code - tests/test_claude_cli_backend.py
- [[test_windows_raises_when_neither_cmd_nor_bare_claude_present()]] - code - tests/test_claude_cli_backend.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_call_claude_cli
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_llm.py]]
- 7 edges to [[_COMMUNITY_test_llm_backends.py]]
- 6 edges to [[_COMMUNITY__call_llm]]
- 4 edges to [[_COMMUNITY__parse_llm_json]]
- 2 edges to [[_COMMUNITY_test_image_vision.py]]
- 1 edge to [[_COMMUNITY_test_chunking.py]]
- 1 edge to [[_COMMUNITY__fixture]]

## Top bridge nodes
- [[_call_claude_cli()]] - degree 37, connects to 6 communities
- [[_resolve_api_timeout()]] - degree 10, connects to 3 communities
- [[test_claude_cli_backend.py]] - degree 32, connects to 2 communities
- [[_no_window_kwargs()]] - degree 5, connects to 2 communities
- [[_claude_cli_supports_json_schema()]] - degree 7, connects to 1 community