---
type: community
cohesion: 0.09
members: 38
---

# e

**Cohesion:** 0.09 - loosely connected
**Members:** 38 nodes

## Members
- [[API module - exposes the document pipeline over HTTP. Thin layer over parser, va]] - rationale - worked/example/raw/api.py
- [[Accept a list of file paths, run the full pipeline on each,     and return a sum]] - rationale - worked/example/raw/api.py
- [[Clean up text fields using the processor.]] - rationale - worked/example/raw/validator.py
- [[Exception]] - code
- [[Extract title, sections, and links from markdown.]] - rationale - worked/example/raw/parser.py
- [[Full pipeline parse, validate, save. Returns the saved record ID.]] - rationale - worked/example/raw/parser.py
- [[Lowercase, strip extra whitespace, remove control characters.]] - rationale - worked/example/raw/processor.py
- [[Parse a JSON document into a structured dict.]] - rationale - worked/example/raw/parser.py
- [[Parse a list of files and return their record IDs.]] - rationale - worked/example/raw/parser.py
- [[Parser module - reads raw input documents and converts them into a structured fo]] - rationale - worked/example/raw/parser.py
- [[Processor_1]] - code
- [[Raise if any required field is missing.]] - rationale - worked/example/raw/validator.py
- [[Raise if the format is not in the allowed list.]] - rationale - worked/example/raw/validator.py
- [[Re-enrich a document to pick up new cross-references.]] - rationale - worked/example/raw/api.py
- [[Read a file from disk and return a structured document.]] - rationale - worked/example/raw/parser.py
- [[Run all validation checks on a parsed document. Raises ValidationError on failur]] - rationale - worked/example/raw/validator.py
- [[Split plaintext into paragraphs.]] - rationale - worked/example/raw/parser.py
- [[Validate a list of documents. Returns (valid_docs, errors).]] - rationale - worked/example/raw/validator.py
- [[ValidationError]] - code - worked/example/raw/validator.py
- [[Validator module - checks that parsed documents meet schema requirements before]] - rationale - worked/example/raw/validator.py
- [[api.py]] - code - worked/example/raw/api.py
- [[batch_parse()]] - code - worked/example/raw/parser.py
- [[check_format()]] - code - worked/example/raw/validator.py
- [[check_required_fields()]] - code - worked/example/raw/validator.py
- [[e()]] - code - scripts/gen_demo_path.py
- [[handle_enrich()]] - code - worked/example/raw/api.py
- [[handle_upload()]] - code - worked/example/raw/api.py
- [[normalize_fields()]] - code - worked/example/raw/validator.py
- [[normalize_text()]] - code - worked/example/raw/processor.py
- [[parse_and_save()]] - code - worked/example/raw/parser.py
- [[parse_file()]] - code - worked/example/raw/parser.py
- [[parse_json()]] - code - worked/example/raw/parser.py
- [[parse_markdown()]] - code - worked/example/raw/parser.py
- [[parse_plaintext()]] - code - worked/example/raw/parser.py
- [[parser.py]] - code - worked/example/raw/parser.py
- [[validate_batch()]] - code - worked/example/raw/validator.py
- [[validate_document()]] - code - worked/example/raw/validator.py
- [[validator.py]] - code - worked/example/raw/validator.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/e
SORT file.name ASC
```

## Connections to other communities
- 18 edges to [[_COMMUNITY_storage.py]]
- 3 edges to [[_COMMUNITY_test_pascal.py]]
- 3 edges to [[_COMMUNITY__read_text]]
- 2 edges to [[_COMMUNITY_test_extract.py]]
- 2 edges to [[_COMMUNITY_test_multilang.py]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_extract_dm]]
- 1 edge to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY_extract_fortran]]
- 1 edge to [[_COMMUNITY_test_languages.py]]
- 1 edge to [[_COMMUNITY_extract_markdown]]
- 1 edge to [[_COMMUNITY_extract_objc]]
- 1 edge to [[_COMMUNITY_extract_powershell_manifest]]
- 1 edge to [[_COMMUNITY_extract_terraform]]
- 1 edge to [[_COMMUNITY__edge_labels]]
- 1 edge to [[_COMMUNITY_gen_demo_path.py]]

## Top bridge nodes
- [[e()]] - degree 24, connects to 15 communities
- [[api.py]] - degree 21, connects to 1 community
- [[parser.py]] - degree 12, connects to 1 community
- [[handle_enrich()]] - degree 6, connects to 1 community
- [[parse_and_save()]] - degree 6, connects to 1 community