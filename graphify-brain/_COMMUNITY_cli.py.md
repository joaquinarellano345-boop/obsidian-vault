---
type: community
cohesion: 0.05
members: 96
---

# cli.py

**Cohesion:** 0.05 - loosely connected
**Members:** 96 nodes

## Members
- [[F4 global_add must refuse to read a source graph.json that     exceeds the siz]] - rationale - tests/test_global_graph.py
- [[.__init__()_3]] - code - graphify/cli.py
- [[.mark()]] - code - graphify/cli.py
- [[.total()]] - code - graphify/cli.py
- [[A path inside the configured output dir, e.g. ``out_path(cache)``.      ``Path]] - rationale - graphify/paths.py
- [[Add or update a project graph in the global graph.      Returns a summary dict w]] - rationale - graphify/global_graph.py
- [[Atomically claim a one-time strict block for this session. Returns True only]] - rationale - graphify/cli.py
- [[Build a simple nx.Graph from node dicts.]] - rationale - tests/test_global_graph.py
- [[Clone a GitHub repo to a local cache dir and return the path.      Clones into ~]] - rationale - graphify/cli.py
- [[Drop nodesedgeshyperedges owned by ``stale_sources`` from graph.json     in pl]] - rationale - graphify/cli.py
- [[Edges incident to an external node that gets deduplicated against an     already]] - rationale - tests/test_global_graph.py
- [[Guard the strict deny only block a read of a file the graph actually indexes.]] - rationale - graphify/cli.py
- [[Load a graphify graph.json into a networkx graph, accepting both writers.      T]] - rationale - graphify/paths.py
- [[Manifest-safe files dict only stamp semantic files that actually     produced o]] - rationale - graphify/cli.py
- [[Node count of an existing graph.json.      Returns       - an ``int`` node coun]] - rationale - graphify/export.py
- [[Path_6]] - code
- [[Path_38]] - code
- [[Path_46]] - code
- [[Pick a path endpoint from a _score_nodes result, preferring full-token matches.]] - rationale - graphify/serve.py
- [[Print per-stage wall-clock timings to stderr when --timing is set (1490).]] - rationale - graphify/cli.py
- [[Record that graphify oriented the agent recently, next to the queried graph.]] - rationale - graphify/cli.py
- [[Reject path if its size exceeds the configured graph-file cap.      Protects c]] - rationale - graphify/security.py
- [[Reject oversized graph files before parsing (CLI exit-on-fail flavor).      Dele]] - rationale - graphify/cli.py
- [[Relabel colliding-basename file nodes on a raw node-dict list, in place     (20]] - rationale - graphify/build.py
- [[Remove all nodes for repo_tag from the global graph. Returns count removed.]] - rationale - graphify/global_graph.py
- [[Remove all nodes tagged with repo_tag from G in-place. Returns count removed.]] - rationale - graphify/build.py
- [[Remove the internal ``_partial`` marker from every item in ``result``.      Call]] - rationale - graphify/llm.py
- [[Resolve strict mode GRAPHIFY_HOOK_STRICT env overrides the baked-in flag     (t]] - rationale - graphify/cli.py
- [[Return a copy of G with all node IDs prefixed with repo_tag.      Labels are p]] - rationale - graphify/build.py
- [[Return a unique, human-meaningful repo tag per input graph for merge-graphs.]] - rationale - graphify/build.py
- [[Return the manifest repos dict.]] - rationale - graphify/global_graph.py
- [[Shell-agnostic PreToolUse guard (522).      Reads the tool-call JSON from stdin]] - rationale - graphify/cli.py
- [[Structural safety check for a custom-provider base_url.      A custom provider r]] - rationale - graphify/llm.py
- [[Tests for the global graph infrastructure (graphifyglobal_graph.py), prefixpru]] - rationale - tests/test_global_graph.py
- [[True if a queryexplainpath ran within GRAPHIFY_HOOK_STRICT_TTL (default     18]] - rationale - graphify/cli.py
- [[_StageTimer]] - code - graphify/cli.py
- [[_clone_repo()]] - code - graphify/cli.py
- [[_custom_providers_path()]] - code - graphify/llm.py
- [[_default_graph_path()]] - code - graphify/cli.py
- [[_enforce_graph_size_cap_or_exit()]] - code - graphify/cli.py
- [[_file_hash()]] - code - graphify/global_graph.py
- [[_graph_to_json()]] - code - tests/test_global_graph.py
- [[_hook_strict_enabled()]] - code - graphify/cli.py
- [[_load_global_graph()]] - code - graphify/global_graph.py
- [[_load_manifest()]] - code - graphify/global_graph.py
- [[_make_graph()_2]] - code - tests/test_global_graph.py
- [[_mark_session_denied()]] - code - graphify/cli.py
- [[_pick_scored_endpoint()]] - code - graphify/serve.py
- [[_prune_graph_json_sources()]] - code - graphify/cli.py
- [[_query_stamp_fresh()]] - code - graphify/cli.py
- [[_reenter_main()]] - code - graphify/cli.py
- [[_run_hook_guard()]] - code - graphify/cli.py
- [[_save_global_graph()]] - code - graphify/global_graph.py
- [[_save_manifest()]] - code - graphify/global_graph.py
- [[_stamped_manifest_files()]] - code - graphify/cli.py
- [[_strip_partial_markers()]] - code - graphify/llm.py
- [[_target_is_indexed()]] - code - graphify/cli.py
- [[_touch_query_stamp()]] - code - graphify/cli.py
- [[check_graph_file_size_cap()]] - code - graphify/security.py
- [[cli.py]] - code - graphify/cli.py
- [[disambiguate_file_labels_in_nodes()]] - code - graphify/build.py
- [[dispatch_command()]] - code - graphify/cli.py
- [[distinct_repo_tags()]] - code - graphify/build.py
- [[existing_graph_node_count()]] - code - graphify/export.py
- [[global_add()]] - code - graphify/global_graph.py
- [[global_graph.py]] - code - graphify/global_graph.py
- [[global_list()]] - code - graphify/global_graph.py
- [[global_path()]] - code - graphify/global_graph.py
- [[global_remove()]] - code - graphify/global_graph.py
- [[graphify command dispatch — every non-install subcommand.  Extracted verbatim fr]] - rationale - graphify/cli.py
- [[load_node_link_graph()]] - code - graphify/paths.py
- [[merge-graphs should prefix node IDs with repo name to avoid silent collision.]] - rationale - tests/test_global_graph.py
- [[out_path()]] - code - graphify/paths.py
- [[prefix_graph_for_global()]] - code - graphify/build.py
- [[provider_base_url_ok()]] - code - graphify/llm.py
- [[prune_repo_from_graph()]] - code - graphify/build.py
- [[test_dedup_ok_with_no_repo_attr()]] - code - tests/test_global_graph.py
- [[test_dedup_ok_with_single_repo()]] - code - tests/test_global_graph.py
- [[test_dedup_raises_on_cross_repo_nodes()]] - code - tests/test_global_graph.py
- [[test_global_add_collision_warning()]] - code - tests/test_global_graph.py
- [[test_global_add_creates_global_graph()]] - code - tests/test_global_graph.py
- [[test_global_add_rejects_oversized_source_graph()]] - code - tests/test_global_graph.py
- [[test_global_add_rewires_edges_to_deduplicated_externals()]] - code - tests/test_global_graph.py
- [[test_global_add_skip_on_unchanged_hash()]] - code - tests/test_global_graph.py
- [[test_global_add_two_repos_no_collision()]] - code - tests/test_global_graph.py
- [[test_global_graph.py]] - code - tests/test_global_graph.py
- [[test_global_remove()]] - code - tests/test_global_graph.py
- [[test_global_remove_unknown_tag_raises()]] - code - tests/test_global_graph.py
- [[test_merge_graphs_prefixes_ids()]] - code - tests/test_global_graph.py
- [[test_prefix_graph_preserves_label()]] - code - tests/test_global_graph.py
- [[test_prefix_graph_rewrites_edges()]] - code - tests/test_global_graph.py
- [[test_prefix_graph_sets_repo_and_local_id()]] - code - tests/test_global_graph.py
- [[test_prune_repo_removes_correct_nodes()]] - code - tests/test_global_graph.py
- [[test_prune_repo_returns_zero_if_not_present()]] - code - tests/test_global_graph.py
- [[test_strict_enabled_env_precedence()]] - code - tests/test_hook_strict.py
- [[test_strip_partial_markers_removes_internal_key()]] - code - tests/test_partial_cache.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/clipy
SORT file.name ASC
```

## Connections to other communities
- 24 edges to [[_COMMUNITY__rebuild_code]]
- 14 edges to [[_COMMUNITY_paths.py]]
- 12 edges to [[_COMMUNITY_graphifybuild.py]]
- 10 edges to [[_COMMUNITY_test_multigraph_diagnostics.py]]
- 10 edges to [[_COMMUNITY_test_security.py]]
- 9 edges to [[_COMMUNITY_test_export.py]]
- 9 edges to [[_COMMUNITY_export.py]]
- 8 edges to [[_COMMUNITY_graphify__main__.py]]
- 7 edges to [[_COMMUNITY_test_file_label_disambiguation.py]]
- 7 edges to [[_COMMUNITY_save_semantic_cache]]
- 6 edges to [[_COMMUNITY_test_benchmark.py]]
- 6 edges to [[_COMMUNITY_build_from_json]]
- 5 edges to [[_COMMUNITY_detect.py]]
- 5 edges to [[_COMMUNITY_to_json]]
- 4 edges to [[_COMMUNITY_test_analyze.py]]
- 4 edges to [[_COMMUNITY__stale_graph_sources]]
- 4 edges to [[_COMMUNITY_graphifycluster.py]]
- 4 edges to [[_COMMUNITY_generate]]
- 4 edges to [[_COMMUNITY_hooks.py]]
- 4 edges to [[_COMMUNITY_test_llm_backends.py]]
- 4 edges to [[_COMMUNITY_reflect.py]]
- 4 edges to [[_COMMUNITY_deduplicate_entities]]
- 4 edges to [[_COMMUNITY_llm.py]]
- 3 edges to [[_COMMUNITY_test_install.py]]
- 3 edges to [[_COMMUNITY_test_detect.py]]
- 3 edges to [[_COMMUNITY_prs.py]]
- 3 edges to [[_COMMUNITY__fixture]]
- 3 edges to [[_COMMUNITY_test_extract_cli.py]]
- 3 edges to [[_COMMUNITY__load_custom_providers]]
- 2 edges to [[_COMMUNITY_affected.py]]
- 2 edges to [[_COMMUNITY_build]]
- 2 edges to [[_COMMUNITY_test_merge_graphs_cli.py]]
- 2 edges to [[_COMMUNITY_file_hash]]
- 2 edges to [[_COMMUNITY_test_cache.py]]
- 2 edges to [[_COMMUNITY_check_semantic_cache]]
- 2 edges to [[_COMMUNITY_callflow_html.py]]
- 2 edges to [[_COMMUNITY_load_graph]]
- 2 edges to [[_COMMUNITY_write_callflow_html]]
- 2 edges to [[_COMMUNITY_introspect_cargo]]
- 2 edges to [[_COMMUNITY_test_cluster.py]]
- 2 edges to [[_COMMUNITY_extract]]
- 2 edges to [[_COMMUNITY_install]]
- 2 edges to [[_COMMUNITY_ingest.py]]
- 2 edges to [[_COMMUNITY_save_query_result]]
- 2 edges to [[_COMMUNITY__call_claude_cli]]
- 2 edges to [[_COMMUNITY_test_chunking.py]]
- 2 edges to [[_COMMUNITY__extraction_system]]
- 2 edges to [[_COMMUNITY_dedup.py]]
- 2 edges to [[_COMMUNITY_test_labeling.py]]
- 2 edges to [[_COMMUNITY_test_ollama.py]]
- 2 edges to [[_COMMUNITY_validate_extraction]]
- 2 edges to [[_COMMUNITY_test_querylog.py]]
- 2 edges to [[_COMMUNITY_lessons_fresh]]
- 2 edges to [[_COMMUNITY_load_validated_semantic_fragment]]
- 2 edges to [[_COMMUNITY_test_serve.py]]
- 2 edges to [[_COMMUNITY__make_graph]]
- 2 edges to [[_COMMUNITY__score_nodes]]
- 2 edges to [[_COMMUNITY_test_watch.py]]
- 2 edges to [[_COMMUNITY_to_wiki]]
- 2 edges to [[_COMMUNITY__load_graph]]
- 2 edges to [[_COMMUNITY_serve.py]]
- 1 edge to [[_COMMUNITY__build_server]]
- 1 edge to [[_COMMUNITY_test_indirect_dispatch.py]]
- 1 edge to [[_COMMUNITY_Graph]]
- 1 edge to [[_COMMUNITY_default_graph_json]]
- 1 edge to [[_COMMUNITY_test_transcribe.py]]
- 1 edge to [[_COMMUNITY_attach_graph_impact]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_validate_graph_path]]
- 1 edge to [[_COMMUNITY_bench_query_scoring.py]]

## Top bridge nodes
- [[dispatch_command()]] - degree 114, connects to 53 communities
- [[cli.py]] - degree 118, connects to 52 communities
- [[check_graph_file_size_cap()]] - degree 37, connects to 16 communities
- [[out_path()]] - degree 11, connects to 4 communities
- [[load_node_link_graph()]] - degree 10, connects to 4 communities