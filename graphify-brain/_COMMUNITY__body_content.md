---
type: community
cohesion: 0.12
members: 16
---

# _body_content

**Cohesion:** 0.12 - loosely connected
**Members:** 16 nodes

## Members
- [[A ``--- text`` line is skipped; the next whole ``---`` line closes.]] - rationale - tests/test_cache.py
- [[A document opening with a ``----`` thematic break has no frontmatter;     a late]] - rationale - tests/test_cache.py
- [[For well-formed frontmatter the stripped body must stay byte-identical     to th]] - rationale - tests/test_cache.py
- [[Strip YAML frontmatter from Markdown content, returning only the body.]] - rationale - graphify/cache.py
- [[_body_content correctly strips YAML frontmatter.]] - rationale - tests/test_cache.py
- [[_body_content returns content unchanged when no frontmatter present.]] - rationale - tests/test_cache.py
- [[_body_content()]] - code - graphify/cache.py
- [[``--- text`` and ``----`` lines inside opened frontmatter are not the     close;]] - rationale - tests/test_cache.py
- [[``--- title`` on the first line is prose, not an open delimiter.]] - rationale - tests/test_cache.py
- [[test_body_content_dash_text_line_is_not_close_delimiter()]] - code - tests/test_cache.py
- [[test_body_content_dash_title_start_is_not_frontmatter()]] - code - tests/test_cache.py
- [[test_body_content_hr_start_is_not_frontmatter()]] - code - tests/test_cache.py
- [[test_body_content_later_proper_close_skips_dash_text_lines()]] - code - tests/test_cache.py
- [[test_body_content_no_frontmatter()]] - code - tests/test_cache.py
- [[test_body_content_strips_frontmatter()]] - code - tests/test_cache.py
- [[test_body_content_well_formed_output_byte_identical()]] - code - tests/test_cache.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_body_content
SORT file.name ASC
```

## Connections to other communities
- 9 edges to [[_COMMUNITY_test_cache.py]]
- 1 edge to [[_COMMUNITY_file_hash]]

## Top bridge nodes
- [[_body_content()]] - degree 11, connects to 2 communities
- [[test_body_content_dash_text_line_is_not_close_delimiter()]] - degree 3, connects to 1 community
- [[test_body_content_dash_title_start_is_not_frontmatter()]] - degree 3, connects to 1 community
- [[test_body_content_hr_start_is_not_frontmatter()]] - degree 3, connects to 1 community
- [[test_body_content_later_proper_close_skips_dash_text_lines()]] - degree 3, connects to 1 community