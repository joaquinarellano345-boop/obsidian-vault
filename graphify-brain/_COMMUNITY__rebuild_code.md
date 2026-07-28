---
type: community
cohesion: 0.05
members: 74
---

# _rebuild_code

**Cohesion:** 0.05 - loosely connected
**Members:** 74 nodes

## Members
- [[1059 changed_paths=None means a full-corpus rebuild — the queue     must not b]] - rationale - tests/test_watch.py
- [[1886 `--exclude` recorded at extract time must survive into updatewatch]] - rationale - tests/test_watch.py
- [[2051 follow-up a node whose source_file is a URLvirtual scheme     (gdoc,]] - rationale - tests/test_watch.py
- [[.__init__()_8]] - code - graphify/watch.py
- [[.absolute_identity()]] - code - graphify/watch.py
- [[.identity()]] - code - graphify/watch.py
- [[.in_watch_root()]] - code - graphify/watch.py
- [[.is_evicted()]] - code - graphify/watch.py
- [[.normalize()]] - code - graphify/watch.py
- [[.rebase_preserved()]] - code - graphify/watch.py
- [[Append ``changed_paths`` to ``out_dir.pending_changes`` (one per line).      Us]] - rationale - graphify/watch.py
- [[Assemble the report's work-memory inputs from sibling artifacts.      Reads the]] - rationale - graphify/report.py
- [[Best-effort nice + memory cap. Called from inline hook scripts.      GRAPHIFY_RE]] - rationale - graphify/watch.py
- [[Collapse exact parallel edges by ``(source, target, relation)``, keeping the]] - rationale - graphify/build.py
- [[Collapse nodes sharing an ``id``, last-writer-wins on attributes.      Mirrors w]] - rationale - graphify/build.py
- [[Concatenate path lists, preserving order and dropping duplicates.      Used to c]] - rationale - graphify/watch.py
- [[Ensure relative rebuild paths have a usable CWD before queuelock setup.      De]] - rationale - graphify/watch.py
- [[Generate questions the graph is uniquely positioned to answer.     Based on AMB]] - rationale - graphify/analyze.py
- [[Merge fresh extraction with preserved graph entries and evict stale sources.]] - rationale - graphify/watch.py
- [[Path_56]] - code
- [[Persist corpus-shaping options under ``out_dir``.      Best effort and non clobb]] - rationale - graphify/watch.py
- [[Re-run AST extraction + build + optional cluster + report for code files. No LLM]] - rationale - graphify/watch.py
- [[Read + unlink ``out_dir.pending_changes`` and return deduplicated paths.      R]] - rationale - graphify/watch.py
- [[Rebase cache-root-relative source paths onto the project root.]] - rationale - graphify/watch.py
- [[Repeated appends across concurrent contenders must dedupe; partial     writes le]] - rationale - tests/test_watch.py
- [[Resolve source_file values across current and legacy graph roots.]] - rationale - graphify/watch.py
- [[Return current git HEAD commit hash, or None outside a repo.]] - rationale - graphify/watch.py
- [[Return plausible absolute locations for a hook-provided changed path.      Git h]] - rationale - graphify/watch.py
- [[Return the effective viz node limit, honoring GRAPHIFY_VIZ_NODE_LIMIT env var.]] - rationale - graphify/exporters/html.py
- [[Return the persisted ``--exclude`` patterns for this graph, or .]] - rationale - graphify/watch.py
- [[Return whether rebuilds should honor VCS ignore files (default True).]] - rationale - graphify/watch.py
- [[Snapshot graph artifacts to a dated subfolder before an overwrite.      Triggers]] - rationale - graphify/export.py
- [[Watch watch_path for new or modified files and auto-update the graph.      For c]] - rationale - graphify/watch.py
- [[_StoredSourcePaths]] - code - graphify/watch.py
- [[_apply_resource_limits()]] - code - graphify/watch.py
- [[_canonical_graph_for_compare()]] - code - graphify/watch.py
- [[_canonical_topology_for_compare()]] - code - graphify/watch.py
- [[_changed_path_candidates()]] - code - graphify/watch.py
- [[_drain_pending()]] - code - graphify/watch.py
- [[_git_head()_1]] - code - graphify/watch.py
- [[_has_non_code()]] - code - graphify/watch.py
- [[_is_relative_to()]] - code - graphify/watch.py
- [[_is_remote_source()]] - code - graphify/watch.py
- [[_json_text()]] - code - graphify/watch.py
- [[_merge_changed_paths()]] - code - graphify/watch.py
- [[_node_community_map()_1]] - code - graphify/watch.py
- [[_queue_pending writes one path per line; _drain_pending reads + unlinks     and]] - rationale - tests/test_watch.py
- [[_queue_pending()]] - code - graphify/watch.py
- [[_read_build_excludes()]] - code - graphify/watch.py
- [[_read_build_gitignore()]] - code - graphify/watch.py
- [[_rebase_relative_source_files()]] - code - graphify/watch.py
- [[_rebuild_code()]] - code - graphify/watch.py
- [[_reconcile_existing_graph()]] - code - graphify/watch.py
- [[_relativize_source_files()]] - code - graphify/watch.py
- [[_report_for_compare()]] - code - graphify/watch.py
- [[_report_root_label()]] - code - graphify/watch.py
- [[_stabilize_rebuild_cwd()]] - code - graphify/watch.py
- [[_topology_from_graph()]] - code - graphify/watch.py
- [[_viz_node_limit()]] - code - graphify/exporters/html.py
- [[_write_build_config()]] - code - graphify/watch.py
- [[backup_if_protected()]] - code - graphify/export.py
- [[dedupe_edges()]] - code - graphify/build.py
- [[dedupe_nodes()]] - code - graphify/build.py
- [[load_learning_for_report()]] - code - graphify/report.py
- [[suggest_questions()]] - code - graphify/analyze.py
- [[test_drain_pending_dedupes_and_skips_blank_lines()]] - code - tests/test_watch.py
- [[test_queue_and_drain_pending_round_trip()]] - code - tests/test_watch.py
- [[test_rebuild_code_full_corpus_skips_pending_queue()]] - code - tests/test_watch.py
- [[test_rebuild_code_preserves_remote_source_across_repeated_updates()]] - code - tests/test_watch.py
- [[test_rebuild_honors_persisted_excludes()]] - code - tests/test_watch.py
- [[test_rebuild_honors_persisted_no_gitignore()]] - code - tests/test_watch.py
- [[test_watch_raises_without_watchdog()]] - code - tests/test_watch.py
- [[watch()]] - code - graphify/watch.py
- [[watch.py]] - code - graphify/watch.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/_rebuild_code
SORT file.name ASC
```

## Connections to other communities
- 62 edges to [[_COMMUNITY_test_watch.py]]
- 24 edges to [[_COMMUNITY_cli.py]]
- 14 edges to [[_COMMUNITY_test_export.py]]
- 8 edges to [[_COMMUNITY_test_analyze.py]]
- 7 edges to [[_COMMUNITY_build_from_json]]
- 7 edges to [[_COMMUNITY_skipif]]
- 6 edges to [[_COMMUNITY_generate]]
- 5 edges to [[_COMMUNITY_graphifycluster.py]]
- 4 edges to [[_COMMUNITY_graphifybuild.py]]
- 4 edges to [[_COMMUNITY__load_graphifyignore]]
- 3 edges to [[_COMMUNITY_export.py]]
- 3 edges to [[_COMMUNITY_test_cluster.py]]
- 3 edges to [[_COMMUNITY_detect.py]]
- 3 edges to [[_COMMUNITY_Path]]
- 2 edges to [[_COMMUNITY_test_pipeline.py]]
- 2 edges to [[_COMMUNITY_write_callflow_html]]
- 2 edges to [[_COMMUNITY_test_detect.py]]
- 2 edges to [[_COMMUNITY_to_json]]
- 2 edges to [[_COMMUNITY_extract]]
- 1 edge to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__build_server]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_load_memory_docs]]
- 1 edge to [[_COMMUNITY_test_reflect.py]]
- 1 edge to [[_COMMUNITY_reflect.py]]

## Top bridge nodes
- [[watch.py]] - degree 58, connects to 18 communities
- [[_rebuild_code()]] - degree 101, connects to 16 communities
- [[suggest_questions()]] - degree 16, connects to 8 communities
- [[load_learning_for_report()]] - degree 9, connects to 5 communities
- [[backup_if_protected()]] - degree 17, connects to 3 communities