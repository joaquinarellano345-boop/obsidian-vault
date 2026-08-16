---
type: community
cohesion: 0.16
members: 20
---

# e

**Cohesion:** 0.16 - loosely connected
**Members:** 20 nodes

## Members
- [[API module - exposes the document pipeline over HTTP. Thin layer over parser, va]] - rationale - worked/example/raw/api.py
- [[Clean up text fields using the processor.]] - rationale - worked/example/raw/validator.py
- [[Exception]] - code
- [[Processor_1]] - code
- [[Raise if any required field is missing.]] - rationale - worked/example/raw/validator.py
- [[Raise if the format is not in the allowed list.]] - rationale - worked/example/raw/validator.py
- [[Re-enrich a document to pick up new cross-references.]] - rationale - worked/example/raw/api.py
- [[Run all validation checks on a parsed document. Raises ValidationError on failur]] - rationale - worked/example/raw/validator.py
- [[Validate a list of documents. Returns (valid_docs, errors).]] - rationale - worked/example/raw/validator.py
- [[ValidationError]] - code - worked/example/raw/validator.py
- [[Validator module - checks that parsed documents meet schema requirements before]] - rationale - worked/example/raw/validator.py
- [[api.py]] - code - worked/example/raw/api.py
- [[check_format()]] - code - worked/example/raw/validator.py
- [[check_required_fields()]] - code - worked/example/raw/validator.py
- [[e()]] - code - scripts/gen_demo_path.py
- [[handle_enrich()]] - code - worked/example/raw/api.py
- [[normalize_fields()]] - code - worked/example/raw/validator.py
- [[validate_batch()]] - code - worked/example/raw/validator.py
- [[validate_document()]] - code - worked/example/raw/validator.py
- [[validator.py]] - code - worked/example/raw/validator.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/e
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_parser.py]]
- 7 edges to [[_COMMUNITY_storage.py]]
- 5 edges to [[_COMMUNITY_processor.py]]
- 3 edges to [[_COMMUNITY_test_pascal.py]]
- 3 edges to [[_COMMUNITY__make_id]]
- 2 edges to [[_COMMUNITY_test_languages.py]]
- 2 edges to [[_COMMUNITY_list_records]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_extract_bash]]
- 1 edge to [[_COMMUNITY_extract_dm]]
- 1 edge to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY_extract_fortran]]
- 1 edge to [[_COMMUNITY_extract_go]]
- 1 edge to [[_COMMUNITY_extract_json]]
- 1 edge to [[_COMMUNITY_extract_markdown]]
- 1 edge to [[_COMMUNITY_extract_objc]]
- 1 edge to [[_COMMUNITY_extract_powershell_manifest]]
- 1 edge to [[_COMMUNITY_extract_rust]]
- 1 edge to [[_COMMUNITY_extract_terraform]]
- 1 edge to [[_COMMUNITY_gen_demo_path.py]]
- 1 edge to [[_COMMUNITY_handle_get]]

## Top bridge nodes
- [[e()]] - degree 24, connects to 17 communities
- [[api.py]] - degree 21, connects to 5 communities
- [[validator.py]] - degree 11, connects to 2 communities
- [[handle_enrich()]] - degree 6, connects to 2 communities
- [[validate_document()]] - degree 10, connects to 1 community