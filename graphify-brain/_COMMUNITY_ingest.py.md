---
type: community
cohesion: 0.18
members: 21
---

# ingest.py

**Cohesion:** 0.18 - loosely connected
**Members:** 21 nodes

## Members
- [[Classify the URL for targeted extraction.]] - rationale - graphify/ingest.py
- [[Convert HTML to clean markdown. Uses markdownify if available, else basic strip.]] - rationale - graphify/ingest.py
- [[Download a binary file (PDF, image) directly.]] - rationale - graphify/ingest.py
- [[Escape a string for embedding in a YAML double-quoted scalar.      Handles every]] - rationale - graphify/ingest.py
- [[Fetch a URL and save it into target_dir as a graphify-ready file.      Returns t]] - rationale - graphify/ingest.py
- [[Fetch a generic webpage and convert to markdown.]] - rationale - graphify/ingest.py
- [[Fetch a tweet URL. Returns (content, filename).]] - rationale - graphify/ingest.py
- [[Fetch arXiv abstract page.]] - rationale - graphify/ingest.py
- [[Path_41]] - code
- [[Turn a URL into a safe filename.]] - rationale - graphify/ingest.py
- [[_detect_url_type()]] - code - graphify/ingest.py
- [[_download_binary()]] - code - graphify/ingest.py
- [[_fetch_arxiv()]] - code - graphify/ingest.py
- [[_fetch_html()]] - code - graphify/ingest.py
- [[_fetch_tweet()]] - code - graphify/ingest.py
- [[_fetch_webpage()]] - code - graphify/ingest.py
- [[_html_to_markdown()]] - code - graphify/ingest.py
- [[_safe_filename()]] - code - graphify/ingest.py
- [[_yaml_str()_1]] - code - graphify/ingest.py
- [[ingest()]] - code - graphify/ingest.py
- [[ingest.py]] - code - graphify/ingest.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/ingestpy
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_safe_fetch]]
- 4 edges to [[_COMMUNITY_save_query_result]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_validate_url]]
- 2 edges to [[_COMMUNITY_test_transcribe.py]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_reflect.py]]
- 1 edge to [[_COMMUNITY_test_reflect.py]]

## Top bridge nodes
- [[ingest.py]] - degree 19, connects to 7 communities
- [[ingest()]] - degree 12, connects to 3 communities
- [[_download_binary()]] - degree 6, connects to 1 community
- [[_fetch_tweet()]] - degree 6, connects to 1 community
- [[_yaml_str()_1]] - degree 6, connects to 1 community