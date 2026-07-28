---
type: community
cohesion: 0.11
members: 22
---

# test_ollama.py

**Cohesion:** 0.11 - loosely connected
**Members:** 22 nodes

## Members
- [[A hostname that RESOLVES to a link-local IP is blocked, not just literals (F3).]] - rationale - tests/test_ollama.py
- [[Link-local  cloud-metadata Ollama targets fail closed (F3).]] - rationale - tests/test_ollama.py
- [[Loopback is silent; a general LAN host warns but is allowed (F3).]] - rationale - tests/test_ollama.py
- [[Tests for the Ollama backend additions in graphifyllm.py.]] - rationale - tests/test_ollama.py
- [[True if host is, or resolves to, a link-local  cloud-metadata address.      R]] - rationale - graphify/llm.py
- [[Warn if OLLAMA_BASE_URL looks unsafe; hard-block link-localmetadata (F3).]] - rationale - graphify/llm.py
- [[_ollama_host_is_link_local_or_metadata()]] - code - graphify/llm.py
- [[_validate_ollama_base_url()]] - code - graphify/llm.py
- [[extract_files_direct with backend=ollama and no OLLAMA_API_KEY should use sentin]] - rationale - tests/test_ollama.py
- [[parametrize_16]] - code
- [[test_detect_backend_claude_beats_ollama()]] - code - tests/test_ollama.py
- [[test_detect_backend_kimi_beats_ollama()]] - code - tests/test_ollama.py
- [[test_detect_backend_none_without_envvars()]] - code - tests/test_ollama.py
- [[test_detect_backend_ollama()]] - code - tests/test_ollama.py
- [[test_ollama.py]] - code - tests/test_ollama.py
- [[test_ollama_alias_resolving_to_link_local_blocked()]] - code - tests/test_ollama.py
- [[test_ollama_api_key_sentinel()]] - code - tests/test_ollama.py
- [[test_ollama_blocks_link_local_and_metadata()]] - code - tests/test_ollama.py
- [[test_ollama_in_backends()]] - code - tests/test_ollama.py
- [[test_ollama_loopback_and_lan_do_not_raise()]] - code - tests/test_ollama.py
- [[test_ollama_warn_false_still_hard_blocks_but_stays_quiet()]] - code - tests/test_ollama.py
- [[warn=False suppresses the LAN warning but never the metadata hard-block (F3).]] - rationale - tests/test_ollama.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_ollamapy
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_test_llm_backends.py]]
- 3 edges to [[_COMMUNITY_llm.py]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 1 edge to [[_COMMUNITY__call_llm]]

## Top bridge nodes
- [[_validate_ollama_base_url()]] - degree 13, connects to 4 communities
- [[test_ollama.py]] - degree 15, connects to 2 communities
- [[_ollama_host_is_link_local_or_metadata()]] - degree 3, connects to 1 community
- [[test_ollama_api_key_sentinel()]] - degree 3, connects to 1 community
- [[test_detect_backend_claude_beats_ollama()]] - degree 2, connects to 1 community