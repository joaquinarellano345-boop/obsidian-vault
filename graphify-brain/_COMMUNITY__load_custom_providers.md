---
type: community
cohesion: 0.14
members: 18
---

# _load_custom_providers

**Cohesion:** 0.14 - loosely connected
**Members:** 18 nodes

## Members
- [[A project-local ..graphifyproviders.json is NOT loaded by default (F1).      I]] - rationale - tests/test_provider_registry.py
- [[A provider whose base_url uses a non-http(s) scheme is skipped on load (F1).]] - rationale - tests/test_provider_registry.py
- [[Built-in provider names are protected from being overridden.]] - rationale - tests/test_provider_registry.py
- [[Custom providers appear after all built-ins in detect_backend() priority.]] - rationale - tests/test_provider_registry.py
- [[Full round-trip add → list → show → remove via providers.json.]] - rationale - tests/test_provider_registry.py
- [[Missing pricing field defaults to zero so estimate_cost doesn't blow up.]] - rationale - tests/test_provider_registry.py
- [[With explicit opt-in the project-local file is honoured (F1).]] - rationale - tests/test_provider_registry.py
- [[_load_custom_providers()]] - code - graphify/llm.py
- [[provider_base_url_ok rejects bad schemes and warns on plaintext-http egress (F1)]] - rationale - tests/test_provider_registry.py
- [[test_custom_provider_add_list_show_remove()]] - code - tests/test_provider_registry.py
- [[test_custom_provider_cannot_shadow_builtin()]] - code - tests/test_provider_registry.py
- [[test_custom_provider_pricing_defaults_to_zero()]] - code - tests/test_provider_registry.py
- [[test_detect_backend_custom_provider_after_builtins()]] - code - tests/test_provider_registry.py
- [[test_non_http_provider_base_url_rejected()]] - code - tests/test_provider_registry.py
- [[test_project_local_providers_ignored_without_optin()]] - code - tests/test_provider_registry.py
- [[test_project_local_providers_loaded_with_optin()]] - code - tests/test_provider_registry.py
- [[test_provider_base_url_ok_scheme_and_warnings()]] - code - tests/test_provider_registry.py
- [[test_provider_registry.py]] - code - tests/test_provider_registry.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_load_custom_providers
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_llm.py]]
- 1 edge to [[_COMMUNITY_test_llm_backends.py]]

## Top bridge nodes
- [[_load_custom_providers()]] - degree 9, connects to 2 communities
- [[test_provider_registry.py]] - degree 9, connects to 1 community
- [[test_detect_backend_custom_provider_after_builtins()]] - degree 3, connects to 1 community
- [[test_provider_base_url_ok_scheme_and_warnings()]] - degree 3, connects to 1 community