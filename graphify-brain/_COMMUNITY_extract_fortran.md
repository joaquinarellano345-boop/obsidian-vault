---
type: community
cohesion: 0.11
members: 19
---

# extract_fortran

**Cohesion:** 0.11 - loosely connected
**Members:** 19 nodes

## Members
- [[Extract programs, modules, subroutines, functions, use statements, and calls fro]] - rationale - graphify/extractors/fortran.py
- [[Path_20]] - code
- [[Run cpp -w -P on a capital-F Fortran file and return preprocessed bytes.      Fa]] - rationale - graphify/extractors/fortran.py
- [[_cpp_preprocess()]] - code - graphify/extractors/fortran.py
- [[`y = f(x)` function invocations must emit a calls edge.      Function calls are]] - rationale - tests/test_languages.py
- [[extract_fortran()]] - code - graphify/extractors/fortran.py
- [[test_fortran_capital_F_parses_preprocessed()]] - code - tests/test_languages.py
- [[test_fortran_case_insensitive_names()]] - code - tests/test_languages.py
- [[test_fortran_finds_calls()]] - code - tests/test_languages.py
- [[test_fortran_finds_derived_type()]] - code - tests/test_languages.py
- [[test_fortran_finds_function()]] - code - tests/test_languages.py
- [[test_fortran_finds_function_call()]] - code - tests/test_languages.py
- [[test_fortran_finds_module()]] - code - tests/test_languages.py
- [[test_fortran_finds_program()]] - code - tests/test_languages.py
- [[test_fortran_finds_subroutines()]] - code - tests/test_languages.py
- [[test_fortran_finds_use_imports()]] - code - tests/test_languages.py
- [[test_fortran_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_fortran_parameter_and_return_type_contexts()]] - code - tests/test_languages.py
- [[test_fortran_use_edges_have_use_context()]] - code - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_fortran
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_test_languages.py]]
- 5 edges to [[_COMMUNITY__make_id]]
- 3 edges to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_e]]

## Top bridge nodes
- [[extract_fortran()]] - degree 23, connects to 3 communities
- [[_cpp_preprocess()]] - degree 5, connects to 2 communities
- [[test_fortran_finds_function_call()]] - degree 3, connects to 1 community
- [[test_fortran_parameter_and_return_type_contexts()]] - degree 3, connects to 1 community
- [[test_fortran_capital_F_parses_preprocessed()]] - degree 2, connects to 1 community