---
type: community
cohesion: 0.09
members: 44
---

# reflect.py

**Cohesion:** 0.09 - loosely connected
**Members:** 44 nodes

## Members
- [[Any_8]] - code
- [[Build a lookup from node id AND node label - community label, or None if the]] - rationale - graphify/reflect.py
- [[Collapse repeated questions to one entry. Docs are processed oldest-first, so]] - rationale - graphify/reflect.py
- [[Content hash of the node's ``source_file``, or '' if unavailable.      Coarse on]] - rationale - graphify/reflect.py
- [[Deterministic work memory reflection over graphify-outmemory.  `graphify ref]] - rationale - graphify/reflect.py
- [[From graph.json build      - ``id_set`` id - id (every node id, so an id-form]] - rationale - graphify/reflect.py
- [[In a flat layout (graph.json at the project root), the resolver must use the]] - rationale - tests/test_reflect.py
- [[Load the sidecar next to ``graph_path`` and return ``{node_id - entry}``     wi]] - rationale - graphify/reflect.py
- [[Locate a node's ``source_file`` on disk, returning an existing file or None.]] - rationale - graphify/reflect.py
- [[Most-recent-first, capped provenance entries for a node.      ``prov_map`` is th]] - rationale - graphify/reflect.py
- [[Parse an ISO datedatetime to an aware UTC datetime, or None if unparseable.]] - rationale - graphify/reflect.py
- [[Path_49]] - code
- [[Project the reflect aggregate into the sidecar's ``{version, generated_at,     n]] - rationale - graphify/reflect.py
- [[Resolve a cited node (a label OR an id) to a single canonical node id.      Retu]] - rationale - graphify/reflect.py
- [[SHA256 of file CONTENT only (no path mixed in), so the fingerprint is     indepe]] - rationale - graphify/reflect.py
- [[Scan ``memory_dir``, write the lessons doc to ``out_path``, return (path, agg).]] - rationale - graphify/reflect.py
- [[Split a bucket's scored nodes into preferred  tentative  contested lists.]] - rationale - graphify/reflect.py
- [[The set of node ids AND labels in the current graph, or None if unavailable.]] - rationale - graphify/reflect.py
- [[Time-decay weight in (0, 1 halves every ``half_life_days``.      Undatedunpar]] - rationale - graphify/reflect.py
- [[True if the node's source file changed (or vanished) since the fingerprint     w]] - rationale - graphify/reflect.py
- [[Write ``.graphify_learning.json`` next to ``graph_path`` deterministically.]] - rationale - graphify/reflect.py
- [[_build_id_label_maps()]] - code - graphify/reflect.py
- [[_code_fingerprint()]] - code - graphify/reflect.py
- [[_content_hash()]] - code - graphify/reflect.py
- [[_decay()]] - code - graphify/reflect.py
- [[_dedupe_by_question()]] - code - graphify/reflect.py
- [[_empty_bucket()]] - code - graphify/reflect.py
- [[_finalize_sources()]] - code - graphify/reflect.py
- [[_is_stale()]] - code - graphify/reflect.py
- [[_load_known_nodes()]] - code - graphify/reflect.py
- [[_load_node_community()]] - code - graphify/reflect.py
- [[_parse_dt()]] - code - graphify/reflect.py
- [[_provenance_for()]] - code - graphify/reflect.py
- [[_record_node()]] - code - graphify/reflect.py
- [[_render_bucket()]] - code - graphify/reflect.py
- [[_resolve_canonical_id()]] - code - graphify/reflect.py
- [[_resolve_source_path()]] - code - graphify/reflect.py
- [[build_learning_overlay()]] - code - graphify/reflect.py
- [[datetime]] - code
- [[load_learning_overlay()]] - code - graphify/reflect.py
- [[reflect()]] - code - graphify/reflect.py
- [[reflect.py]] - code - graphify/reflect.py
- [[test_flat_layout_does_not_match_same_named_file_one_dir_up()]] - code - tests/test_reflect.py
- [[write_learning_sidecar()]] - code - graphify/reflect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/reflectpy
SORT file.name ASC
```

## Connections to other communities
- 19 edges to [[_COMMUNITY_test_reflect.py]]
- 11 edges to [[_COMMUNITY__write_raw_doc]]
- 4 edges to [[_COMMUNITY_cli.py]]
- 4 edges to [[_COMMUNITY_load_memory_docs]]
- 3 edges to [[_COMMUNITY_parse_memory_doc]]
- 2 edges to [[_COMMUNITY_test_export.py]]
- 2 edges to [[_COMMUNITY_lessons_fresh]]
- 2 edges to [[_COMMUNITY_save_query_result]]
- 1 edge to [[_COMMUNITY_ingest.py]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY__doc_community]]
- 1 edge to [[_COMMUNITY_generate]]
- 1 edge to [[_COMMUNITY__rebuild_code]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__load_graph]]

## Top bridge nodes
- [[load_learning_overlay()]] - degree 18, connects to 8 communities
- [[reflect.py]] - degree 32, connects to 7 communities
- [[reflect()]] - degree 24, connects to 5 communities
- [[Any_8]] - degree 16, connects to 3 communities
- [[Path_49]] - degree 13, connects to 2 communities