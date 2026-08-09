---
type: community
cohesion: 0.11
members: 32
---

# test_manifest_ingest.py

**Cohesion:** 0.11 - loosely connected
**Members:** 32 nodes

## Members
- [[A dependency block may be a list of names or a name-spec map.]] - rationale - graphify/manifest_ingest.py
- [[Any_5]] - code
- [[Canonical package node id, keyed by package NAME so every reference to the     s]] - rationale - graphify/manifest_ingest.py
- [[Deterministic package-manifest ingestion (1377).  Package manifests (``apm.yml`]] - rationale - graphify/manifest_ingest.py
- [[Minimal line parser for apm.yml when PyYAML is unavailable a top-level     ``na]] - rationale - graphify/manifest_ingest.py
- [[Parse a package manifest into a canonical package node + ``depends_on`` edges.]] - rationale - graphify/manifest_ingest.py
- [[Path_44]] - code
- [[Path_81]] - code
- [[True if ``path`` is a recognized package manifest (by filename).]] - rationale - graphify/manifest_ingest.py
- [[_coerce_deps()]] - code - graphify/manifest_ingest.py
- [[_parse_apm()]] - code - graphify/manifest_ingest.py
- [[_parse_apm_fallback()]] - code - graphify/manifest_ingest.py
- [[_parse_gomod()]] - code - graphify/manifest_ingest.py
- [[_parse_pom()]] - code - graphify/manifest_ingest.py
- [[_parse_pyproject()]] - code - graphify/manifest_ingest.py
- [[_pep508_name()]] - code - graphify/manifest_ingest.py
- [[_pkg_id()]] - code - graphify/manifest_ingest.py
- [[_pkg_nodes()]] - code - tests/test_manifest_ingest.py
- [[_write()_12]] - code - tests/test_manifest_ingest.py
- [[`requests=2.0` - `requests`; `pkgextra==1; python_version'3.9'` - `pkg`.]] - rationale - graphify/manifest_ingest.py
- [[extract_package_manifest()]] - code - graphify/manifest_ingest.py
- [[is_package_manifest_path()]] - code - graphify/manifest_ingest.py
- [[manifest_ingest.py]] - code - graphify/manifest_ingest.py
- [[test_apm_dependency_collapses_to_single_canonical_node()]] - code - tests/test_manifest_ingest.py
- [[test_apm_parses_name_and_deps()]] - code - tests/test_manifest_ingest.py
- [[test_external_dependency_edge_pruned_not_orphaned()]] - code - tests/test_manifest_ingest.py
- [[test_gomod_parses_module_and_requires()]] - code - tests/test_manifest_ingest.py
- [[test_malformed_manifest_does_not_crash()]] - code - tests/test_manifest_ingest.py
- [[test_manifest_ingest.py]] - code - tests/test_manifest_ingest.py
- [[test_manifests_classify_as_code_not_document()]] - code - tests/test_manifest_ingest.py
- [[test_pom_parses_artifact_and_deps()]] - code - tests/test_manifest_ingest.py
- [[test_pyproject_parses_pep508_deps()]] - code - tests/test_manifest_ingest.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_manifest_ingestpy
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_extract.py]]
- 3 edges to [[_COMMUNITY_build_from_json]]
- 3 edges to [[_COMMUNITY_detect.py]]
- 3 edges to [[_COMMUNITY_classify_file]]
- 3 edges to [[_COMMUNITY_extract]]
- 3 edges to [[_COMMUNITY_make_id]]
- 2 edges to [[_COMMUNITY__get_extractor]]
- 1 edge to [[_COMMUNITY_graphifybuild.py]]

## Top bridge nodes
- [[test_manifest_ingest.py]] - degree 20, connects to 6 communities
- [[is_package_manifest_path()]] - degree 9, connects to 4 communities
- [[manifest_ingest.py]] - degree 15, connects to 2 communities
- [[extract_package_manifest()]] - degree 13, connects to 2 communities
- [[test_apm_dependency_collapses_to_single_canonical_node()]] - degree 4, connects to 2 communities