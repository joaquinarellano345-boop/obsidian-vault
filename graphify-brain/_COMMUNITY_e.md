---
type: community
cohesion: 0.29
members: 7
---

# e

**Cohesion:** 0.29 - loosely connected
**Members:** 7 nodes

## Members
- [[Accept a list of file paths, run the full pipeline on each,     and return a sum]] - rationale - worked/example/raw/api.py
- [[Parse a list of files and return their record IDs.]] - rationale - worked/example/raw/parser.py
- [[Validate a list of documents. Returns (valid_docs, errors).]] - rationale - worked/example/raw/validator.py
- [[batch_parse()]] - code - worked/example/raw/parser.py
- [[e()]] - code - scripts/gen_demo_path.py
- [[handle_upload()]] - code - worked/example/raw/api.py
- [[validate_batch()]] - code - worked/example/raw/validator.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/e
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_api.py]]
- 3 edges to [[_COMMUNITY_test_pascal.py]]
- 3 edges to [[_COMMUNITY__make_id]]
- 2 edges to [[_COMMUNITY_test_languages.py]]
- 2 edges to [[_COMMUNITY_parser.py]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_extract_bash]]
- 1 edge to [[_COMMUNITY_extract_dm]]
- 1 edge to [[_COMMUNITY__extract_generic]]
- 1 edge to [[_COMMUNITY_extract_fortran]]
- 1 edge to [[_COMMUNITY_extract_go]]
- 1 edge to [[_COMMUNITY_extract_json]]
- 1 edge to [[_COMMUNITY_extract_markdown]]
- 1 edge to [[_COMMUNITY_extract_objc]]
- 1 edge to [[_COMMUNITY_extract_powershell_manifest]]
- 1 edge to [[_COMMUNITY_extract_rust]]
- 1 edge to [[_COMMUNITY_extract_terraform]]
- 1 edge to [[_COMMUNITY_gen_demo_path.py]]
- 1 edge to [[_COMMUNITY_handle_enrich]]

## Top bridge nodes
- [[e()]] - degree 24, connects to 17 communities
- [[batch_parse()]] - degree 6, connects to 2 communities
- [[validate_batch()]] - degree 4, connects to 1 community
- [[handle_upload()]] - degree 3, connects to 1 community