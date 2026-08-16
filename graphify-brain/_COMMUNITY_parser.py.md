---
type: community
cohesion: 0.17
members: 16
---

# parser.py

**Cohesion:** 0.17 - loosely connected
**Members:** 16 nodes

## Members
- [[Accept a list of file paths, run the full pipeline on each,     and return a sum]] - rationale - worked/example/raw/api.py
- [[Extract title, sections, and links from markdown.]] - rationale - worked/example/raw/parser.py
- [[Full pipeline parse, validate, save. Returns the saved record ID.]] - rationale - worked/example/raw/parser.py
- [[Parse a JSON document into a structured dict.]] - rationale - worked/example/raw/parser.py
- [[Parse a list of files and return their record IDs.]] - rationale - worked/example/raw/parser.py
- [[Parser module - reads raw input documents and converts them into a structured fo]] - rationale - worked/example/raw/parser.py
- [[Read a file from disk and return a structured document.]] - rationale - worked/example/raw/parser.py
- [[Split plaintext into paragraphs.]] - rationale - worked/example/raw/parser.py
- [[batch_parse()]] - code - worked/example/raw/parser.py
- [[handle_upload()]] - code - worked/example/raw/api.py
- [[parse_and_save()]] - code - worked/example/raw/parser.py
- [[parse_file()]] - code - worked/example/raw/parser.py
- [[parse_json()]] - code - worked/example/raw/parser.py
- [[parse_markdown()]] - code - worked/example/raw/parser.py
- [[parse_plaintext()]] - code - worked/example/raw/parser.py
- [[parser.py]] - code - worked/example/raw/parser.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/parserpy
SORT file.name ASC
```

## Connections to other communities
- 8 edges to [[_COMMUNITY_e]]
- 3 edges to [[_COMMUNITY_storage.py]]

## Top bridge nodes
- [[parser.py]] - degree 12, connects to 2 communities
- [[parse_and_save()]] - degree 6, connects to 2 communities
- [[parse_file()]] - degree 7, connects to 1 community
- [[batch_parse()]] - degree 6, connects to 1 community
- [[handle_upload()]] - degree 3, connects to 1 community