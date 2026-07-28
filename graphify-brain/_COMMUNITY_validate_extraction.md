---
type: community
cohesion: 0.07
members: 51
---

# validate_extraction

**Cohesion:** 0.07 - loosely connected
**Members:** 51 nodes

## Members
- [[1746 information_schema.referential_constraints only shows constraints     whe]] - rationale - tests/test_pg_introspect.py
- [[1854 FK edges must survive routines whose reconstructed DDL the SQL     gramma]] - rationale - tests/test_pg_introspect.py
- [[A 2-column composite FK must produce exactly ONE references edge, not two.]] - rationale - tests/test_pg_introspect.py
- [[A psycopg.OperationalError must be re-raised as ConnectionError with a     sanit]] - rationale - tests/test_pg_introspect.py
- [[Assert that the virtual path in postgresql introspection output uses forward sla]] - rationale - tests/test_pg_introspect.py
- [[Baseline tables, views, routines, and a single-column FK all survive.]] - rationale - tests/test_pg_introspect.py
- [[Connect to PostgreSQL, reconstruct DDL, and extract via extract_sql().]] - rationale - graphify/pg_introspect.py
- [[Double-quote a PostgreSQL identifier, escaping embedded double-quotes.]] - rationale - graphify/pg_introspect.py
- [[If psycopg is missing, introspect_postgres raises ImportError.]] - rationale - tests/test_pg_introspect.py
- [[Merge multiple extraction results into one graph.]] - rationale - worked/mixed-corpus/raw/build.py
- [[Raise ValueError with all errors if extraction is invalid.]] - rationale - graphify/validate.py
- [[Reserved-word and special-character table names must survive DDL round-trip.]] - rationale - tests/test_pg_introspect.py
- [[Return a mock psycopg module wired to the provided catalog data.      ``routines]] - rationale - tests/test_pg_introspect.py
- [[Return the label form that tree-sitter produces for a quoted identifier.      pg]] - rationale - tests/test_pg_introspect.py
- [[Validate an extraction JSON dict against the graphify schema.     Returns a list]] - rationale - graphify/validate.py
- [[_make_mock_psycopg()]] - code - tests/test_pg_introspect.py
- [[_q()]] - code - tests/test_pg_introspect.py
- [[_quote_ident()]] - code - graphify/pg_introspect.py
- [[assert_valid()]] - code - graphify/validate.py
- [[build()_2]] - code - worked/mixed-corpus/raw/build.py
- [[build_from_json()_1]] - code - worked/mixed-corpus/raw/build.py
- [[introspect_postgres()]] - code - graphify/pg_introspect.py
- [[pg_introspect.py]] - code - graphify/pg_introspect.py
- [[rawbuild.py]] - code - worked/mixed-corpus/raw/build.py
- [[test_assert_valid_passes_silently()]] - code - tests/test_validate.py
- [[test_assert_valid_raises_on_errors()]] - code - tests/test_validate.py
- [[test_dangling_edge_source()]] - code - tests/test_validate.py
- [[test_dangling_edge_target()]] - code - tests/test_validate.py
- [[test_invalid_confidence()]] - code - tests/test_validate.py
- [[test_invalid_file_type()]] - code - tests/test_validate.py
- [[test_legacy_aliases_valid_after_build_canonicalization()]] - code - tests/test_validate.py
- [[test_missing_edges_key()]] - code - tests/test_validate.py
- [[test_missing_node_field()]] - code - tests/test_validate.py
- [[test_missing_nodes_key()]] - code - tests/test_validate.py
- [[test_non_hashable_edge_endpoint_reported_not_raised()]] - code - tests/test_validate.py
- [[test_non_hashable_node_id_does_not_mask_valid_ids()]] - code - tests/test_validate.py
- [[test_non_hashable_node_id_reported_not_raised()]] - code - tests/test_validate.py
- [[test_not_a_dict()]] - code - tests/test_validate.py
- [[test_pg_introspect.py]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_composite_fk()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_connection_error()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_fk_edges_survive_unparseable_function_stubs()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_fk_query_avoids_privilege_filtered_view()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_import_error()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_quoted_identifiers()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_success()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_uri_forward_slashes()]] - code - tests/test_pg_introspect.py
- [[test_valid_passes()]] - code - tests/test_validate.py
- [[test_validate.py]] - code - tests/test_validate.py
- [[validate.py]] - code - graphify/validate.py
- [[validate_extraction()]] - code - graphify/validate.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/validate_extraction
SORT file.name ASC
```

## Connections to other communities
- 5 edges to [[_COMMUNITY_build_from_json]]
- 2 edges to [[_COMMUNITY_graphifybuild.py]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 2 edges to [[_COMMUNITY_test_evidence_binding.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY__read_text]]
- 1 edge to [[_COMMUNITY_test_scip_ingest.py]]
- 1 edge to [[_COMMUNITY_ingest_scip_json]]
- 1 edge to [[_COMMUNITY_Graph]]

## Top bridge nodes
- [[validate_extraction()]] - degree 31, connects to 5 communities
- [[introspect_postgres()]] - degree 15, connects to 2 communities
- [[test_validate.py]] - degree 19, connects to 1 community
- [[validate.py]] - degree 5, connects to 1 community
- [[pg_introspect.py]] - degree 4, connects to 1 community