---
type: community
cohesion: 0.11
members: 20
---

# utils.py

**Cohesion:** 0.11 - loosely connected
**Members:** 20 nodes

## Members
- [[Append query parameters to a URL string.]] - rationale - worked/httpx/raw/utils.py
- [[Check if a character encoding label is recognized by Python's codec system.]] - rationale - worked/httpx/raw/utils.py
- [[Clear all cookies from a cookie jar in place.]] - rationale - worked/httpx/raw/utils.py
- [[Convert a header key to its canonical Title-Case form.]] - rationale - worked/httpx/raw/utils.py
- [[Convert a primitive value to its string representation.]] - rationale - worked/httpx/raw/utils.py
- [[Expand a params dict into a flat list of (key, value) pairs.     List values bec]] - rationale - worked/httpx/raw/utils.py
- [[Invoke-Main()]] - code - tests/fixtures/sample_import.ps1
- [[Parse a Content-Type header value.     Returns (media_type, params_dict).     Ex]] - rationale - worked/httpx/raw/utils.py
- [[Return a copy of headers with sensitive values replaced by obfuscated.]] - rationale - worked/httpx/raw/utils.py
- [[Utility functions shared across the library. Small helpers that don't belong in]] - rationale - worked/httpx/raw/utils.py
- [[build_url_with_params()]] - code - worked/httpx/raw/utils.py
- [[flatten_queryparams()]] - code - worked/httpx/raw/utils.py
- [[is_known_encoding()]] - code - worked/httpx/raw/utils.py
- [[normalize_header_key()]] - code - worked/httpx/raw/utils.py
- [[obfuscate_sensitive_headers()]] - code - worked/httpx/raw/utils.py
- [[parse_content_type()]] - code - worked/httpx/raw/utils.py
- [[primitive_value_to_str()]] - code - worked/httpx/raw/utils.py
- [[sample_import.ps1]] - code - tests/fixtures/sample_import.ps1
- [[unset_all_cookies()]] - code - worked/httpx/raw/utils.py
- [[utils.py]] - code - worked/httpx/raw/utils.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/utilspy
SORT file.name ASC
```

## Connections to other communities
- 3 edges to [[_COMMUNITY_client.py]]
- 2 edges to [[_COMMUNITY_Cookies]]
- 1 edge to [[_COMMUNITY_string]]
- 1 edge to [[_COMMUNITY_Response]]

## Top bridge nodes
- [[utils.py]] - degree 12, connects to 2 communities
- [[build_url_with_params()]] - degree 5, connects to 2 communities
- [[obfuscate_sensitive_headers()]] - degree 3, connects to 1 community
- [[unset_all_cookies()]] - degree 3, connects to 1 community
- [[Invoke-Main()]] - degree 2, connects to 1 community