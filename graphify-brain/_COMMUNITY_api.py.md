---
type: community
cohesion: 0.18
members: 17
---

# api.py

**Cohesion:** 0.18 - loosely connected
**Members:** 17 nodes

## Members
- [[API module - exposes the document pipeline over HTTP. Thin layer over parser, va]] - rationale - worked/example/raw/api.py
- [[Clean up text fields using the processor.]] - rationale - worked/example/raw/validator.py
- [[Exception]] - code
- [[Processor_1]] - code
- [[Raise if any required field is missing.]] - rationale - worked/example/raw/validator.py
- [[Raise if the format is not in the allowed list.]] - rationale - worked/example/raw/validator.py
- [[Run all validation checks on a parsed document. Raises ValidationError on failur]] - rationale - worked/example/raw/validator.py
- [[Simple keyword search over the index.     Returns documents whose keyword list o]] - rationale - worked/example/raw/api.py
- [[ValidationError]] - code - worked/example/raw/validator.py
- [[Validator module - checks that parsed documents meet schema requirements before]] - rationale - worked/example/raw/validator.py
- [[api.py]] - code - worked/example/raw/api.py
- [[check_format()]] - code - worked/example/raw/validator.py
- [[check_required_fields()]] - code - worked/example/raw/validator.py
- [[handle_search()]] - code - worked/example/raw/api.py
- [[normalize_fields()]] - code - worked/example/raw/validator.py
- [[validate_document()]] - code - worked/example/raw/validator.py
- [[validator.py]] - code - worked/example/raw/validator.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/apipy
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_storage.py]]
- 5 edges to [[_COMMUNITY_parser.py]]
- 4 edges to [[_COMMUNITY_handle_enrich]]
- 4 edges to [[_COMMUNITY_e]]
- 4 edges to [[_COMMUNITY_processor.py]]
- 2 edges to [[_COMMUNITY_list_records]]

## Top bridge nodes
- [[api.py]] - degree 21, connects to 6 communities
- [[validator.py]] - degree 11, connects to 3 communities
- [[validate_document()]] - degree 10, connects to 3 communities
- [[normalize_fields()]] - degree 4, connects to 1 community
- [[handle_search()]] - degree 3, connects to 1 community