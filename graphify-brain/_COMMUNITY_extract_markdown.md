---
type: community
cohesion: 0.09
members: 24
---

# extract_markdown

**Cohesion:** 0.09 - loosely connected
**Members:** 24 nodes

## Members
- [[Database Migration is nested under  Full Deploy.]] - rationale - tests/test_languages.py
- [[A ' heading' inside a fenced block must not produce a heading node (1077).]] - rationale - tests/test_languages.py
- [[A hub doc linking to sibling docs, plus those docs (1376).]] - rationale - tests/test_languages.py
- [[End-to-end after extract()'s ID remap, link targets are real doc nodes,     so]] - rationale - tests/test_languages.py
- [[External URLs, in-page anchors and images must not produce edges (1376).]] - rationale - tests/test_languages.py
- [[Extract structural nodes and edges from a Markdown file.      Produces nodes for]] - rationale - graphify/extractors/markdown.py
- [[Fenced code blocks should NOT emit nodes (1077).      They were always orphans]] - rationale - tests/test_languages.py
- [[Headings should be connected via 'contains' edges (file-h, h-h).]] - rationale - tests/test_languages.py
- [[Inlinewikilink markdown links to sibling docs become references edges (1376).]] - rationale - tests/test_languages.py
- [[Path_24]] - code
- [[Resolve a markdown link target to the absolute path of a sibling document.]] - rationale - graphify/extractors/markdown.py
- [[_md_link_fixture()]] - code - tests/test_languages.py
- [[_resolve_markdown_link()]] - code - graphify/extractors/markdown.py
- [[extract_markdown()]] - code - graphify/extractors/markdown.py
- [[test_markdown_contains_edges()]] - code - tests/test_languages.py
- [[test_markdown_fenced_heading_not_parsed()]] - code - tests/test_languages.py
- [[test_markdown_finds_headings()]] - code - tests/test_languages.py
- [[test_markdown_finds_nested_heading()]] - code - tests/test_languages.py
- [[test_markdown_link_edges_emitted()]] - code - tests/test_languages.py
- [[test_markdown_link_edges_resolve_to_real_nodes()]] - code - tests/test_languages.py
- [[test_markdown_link_skips_external_and_images()]] - code - tests/test_languages.py
- [[test_markdown_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_markdown_no_error()]] - code - tests/test_languages.py
- [[test_markdown_skips_fenced_code_blocks()]] - code - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_markdown
SORT file.name ASC
```

## Connections to other communities
- 11 edges to [[_COMMUNITY_test_languages.py]]
- 5 edges to [[_COMMUNITY__read_text]]
- 4 edges to [[_COMMUNITY__labels]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_extract]]
- 1 edge to [[_COMMUNITY_e]]
- 1 edge to [[_COMMUNITY__relations]]

## Top bridge nodes
- [[extract_markdown()]] - degree 17, connects to 3 communities
- [[test_markdown_contains_edges()]] - degree 4, connects to 2 communities
- [[test_markdown_fenced_heading_not_parsed()]] - degree 4, connects to 2 communities
- [[test_markdown_finds_nested_heading()]] - degree 4, connects to 2 communities
- [[test_markdown_link_edges_resolve_to_real_nodes()]] - degree 4, connects to 2 communities