---
type: community
cohesion: 0.14
members: 26
---

# introspect_postgres

**Cohesion:** 0.14 - loosely connected
**Members:** 26 nodes

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
- [[Reserved-word and special-character table names must survive DDL round-trip.]] - rationale - tests/test_pg_introspect.py
- [[Return a mock psycopg module wired to the provided catalog data.      ``routines]] - rationale - tests/test_pg_introspect.py
- [[Return the label form that tree-sitter produces for a quoted identifier.      pg]] - rationale - tests/test_pg_introspect.py
- [[_make_mock_psycopg()]] - code - tests/test_pg_introspect.py
- [[_q()]] - code - tests/test_pg_introspect.py
- [[_quote_ident()]] - code - graphify/pg_introspect.py
- [[introspect_postgres()]] - code - graphify/pg_introspect.py
- [[pg_introspect.py]] - code - graphify/pg_introspect.py
- [[test_pg_introspect.py]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_composite_fk()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_connection_error()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_fk_edges_survive_unparseable_function_stubs()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_fk_query_avoids_privilege_filtered_view()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_import_error()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_quoted_identifiers()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_success()]] - code - tests/test_pg_introspect.py
- [[test_pg_introspect_uri_forward_slashes()]] - code - tests/test_pg_introspect.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/introspect_postgres
SORT file.name ASC
```

## Connections to other communities
- 6 edges to [[_COMMUNITY_validate_extraction]]
- 2 edges to [[_COMMUNITY_cli.py]]
- 1 edge to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY__make_id]]

## Top bridge nodes
- [[introspect_postgres()]] - degree 15, connects to 2 communities
- [[test_pg_introspect.py]] - degree 14, connects to 1 community
- [[test_pg_introspect_composite_fk()]] - degree 6, connects to 1 community
- [[test_pg_introspect_fk_edges_survive_unparseable_function_stubs()]] - degree 6, connects to 1 community
- [[test_pg_introspect_quoted_identifiers()]] - degree 6, connects to 1 community