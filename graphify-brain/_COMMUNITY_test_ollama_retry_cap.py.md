---
type: community
cohesion: 0.48
members: 7
---

# test_ollama_retry_cap.py

**Cohesion:** 0.48 - moderately connected
**Members:** 7 nodes

## Members
- [[1686 - a wedged local Ollama request must not multiply --api-timeout by the SDK]] - rationale - tests/test_ollama_retry_cap.py
- [[_capture_client_kwargs()]] - code - tests/test_ollama_retry_cap.py
- [[test_api_timeout_is_passed_to_client()]] - code - tests/test_ollama_retry_cap.py
- [[test_cloud_backend_keeps_default_retries()]] - code - tests/test_ollama_retry_cap.py
- [[test_ollama_defaults_to_zero_sdk_retries()]] - code - tests/test_ollama_retry_cap.py
- [[test_ollama_honors_explicit_max_retries()]] - code - tests/test_ollama_retry_cap.py
- [[test_ollama_retry_cap.py]] - code - tests/test_ollama_retry_cap.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_ollama_retry_cappy
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_test_llm_backends.py]]
- 1 edge to [[_COMMUNITY_llm.py]]

## Top bridge nodes
- [[test_ollama_retry_cap.py]] - degree 7, connects to 1 community
- [[test_api_timeout_is_passed_to_client()]] - degree 3, connects to 1 community
- [[test_cloud_backend_keeps_default_retries()]] - degree 3, connects to 1 community
- [[test_ollama_defaults_to_zero_sdk_retries()]] - degree 3, connects to 1 community
- [[test_ollama_honors_explicit_max_retries()]] - degree 3, connects to 1 community