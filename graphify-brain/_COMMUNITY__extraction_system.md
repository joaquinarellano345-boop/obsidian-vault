---
type: community
cohesion: 0.18
members: 14
---

# _extraction_system

**Cohesion:** 0.18 - loosely connected
**Members:** 14 nodes

## Members
- [[Call Anthropic Claude directly (not via OpenAI compat layer).]] - rationale - graphify/llm.py
- [[Package-missing message that works for the recommended `uv tool` install.      `]] - rationale - graphify/llm.py
- [[Return the semantic-extraction system prompt, optionally in deep mode.]] - rationale - graphify/llm.py
- [[The claude backend must be installable via an extra, and the missing-package mes]] - rationale - tests/test_backend_extras.py
- [[The native-backend prompt must request hyperedges, like the skill's     extracti]] - rationale - tests/test_llm_backends.py
- [[_backend_pkg_hint()]] - code - graphify/llm.py
- [[_call_claude()]] - code - graphify/llm.py
- [[_extraction_system()]] - code - graphify/llm.py
- [[_extras()]] - code - tests/test_backend_extras.py
- [[test_anthropic_extra_exists()]] - code - tests/test_backend_extras.py
- [[test_anthropic_in_all_extra()]] - code - tests/test_backend_extras.py
- [[test_backend_extras.py]] - code - tests/test_backend_extras.py
- [[test_backend_pkg_hint_points_at_uv_tool_and_extra()]] - code - tests/test_backend_extras.py
- [[test_native_extraction_prompt_requests_hyperedges()]] - code - tests/test_llm_backends.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_extraction_system
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_llm.py]]
- 4 edges to [[_COMMUNITY_test_llm_backends.py]]
- 4 edges to [[_COMMUNITY_test_image_vision.py]]
- 4 edges to [[_COMMUNITY_test_chunking.py]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY__call_claude_cli]]
- 2 edges to [[_COMMUNITY__call_llm]]
- 2 edges to [[_COMMUNITY__call_openai_compat]]
- 1 edge to [[_COMMUNITY_save_semantic_cache]]
- 1 edge to [[_COMMUNITY__parse_llm_json]]

## Top bridge nodes
- [[_extraction_system()]] - degree 15, connects to 8 communities
- [[_call_claude()]] - degree 12, connects to 6 communities
- [[_backend_pkg_hint()]] - degree 7, connects to 3 communities
- [[test_backend_extras.py]] - degree 7, connects to 1 community
- [[test_native_extraction_prompt_requests_hyperedges()]] - degree 3, connects to 1 community