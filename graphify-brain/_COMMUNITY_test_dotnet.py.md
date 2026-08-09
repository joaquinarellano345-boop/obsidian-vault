---
type: community
cohesion: 0.05
members: 77
---

# test_dotnet.py

**Cohesion:** 0.05 - loosely connected
**Members:** 77 nodes

## Members
- [[1899 a ProjectReference to a project OUTSIDE the scan root must not leak     t]] - rationale - tests/test_dotnet.py
- [[A ViewModel .cs with invalid UTF-8 bytes must not abort extract_xaml the     Co]] - rationale - tests/test_dotnet.py
- [[A property value that matches an ordinary method's name must not become an     e]] - rationale - tests/test_dotnet.py
- [[Content=Tag= holding a string that equals a real handler's name must not     cr]] - rationale - tests/test_dotnet.py
- [[Extract WPFXAML structure, bindings, xClass, and event handler references.]] - rationale - graphify/extract.py
- [[Extract directives, component refs, and @code methods from .razor.cshtml.]] - rationale - graphify/extractors/razor.py
- [[Extract packages, project refs, and target framework from a .csproj.fsproj.vbp]] - rationale - graphify/extract.py
- [[Extract projects and inter-project dependencies from a .slnx file.      .slnx is]] - rationale - graphify/extract.py
- [[Path_29]] - code
- [[Reject XML that declares DTDs or entities.      Stdlib ``xml.etree.ElementTree``]] - rationale - graphify/extract.py
- [[Tests for .NET project file extraction (.sln, .csproj, .xaml, .razor).]] - rationale - tests/test_dotnet.py
- [[The code-behind.cs scan prunes noise dirs (node_modules.venv.git...)     dur]] - rationale - tests/test_dotnet.py
- [[_event_targets()]] - code - tests/test_dotnet.py
- [[_labels()_2]] - code - tests/test_dotnet.py
- [[_project_xml_is_safe()]] - code - graphify/extract.py
- [[_relations()]] - code - tests/test_dotnet.py
- [[_view_model_edges()]] - code - tests/test_dotnet.py
- [[_xaml_explicit_viewmodel_names()]] - code - graphify/extract.py
- [[_xaml_inferred_viewmodel_names()]] - code - graphify/extract.py
- [[_xaml_prism_autowire_viewmodel()]] - code - graphify/extract.py
- [[_xaml_type_simple_name()]] - code - graphify/extract.py
- [[_xml_local_name()]] - code - graphify/extract.py
- [[extract_csproj()]] - code - graphify/extract.py
- [[extract_razor()]] - code - graphify/extractors/razor.py
- [[extract_slnx()]] - code - graphify/extract.py
- [[extract_xaml()]] - code - graphify/extract.py
- [[test_code_extensions()]] - code - tests/test_dotnet.py
- [[test_csproj_finds_packages()]] - code - tests/test_languages.py
- [[test_csproj_finds_project_references()]] - code - tests/test_languages.py
- [[test_csproj_finds_sdk()]] - code - tests/test_languages.py
- [[test_csproj_finds_target_framework()]] - code - tests/test_languages.py
- [[test_csproj_invalid_xml()]] - code - tests/test_dotnet.py
- [[test_csproj_no_error()]] - code - tests/test_languages.py
- [[test_csproj_out_of_root_reference_id_is_portable()]] - code - tests/test_dotnet.py
- [[test_csproj_packages()]] - code - tests/test_dotnet.py
- [[test_csproj_project_references()]] - code - tests/test_dotnet.py
- [[test_csproj_sdk()]] - code - tests/test_dotnet.py
- [[test_csproj_target_framework()]] - code - tests/test_dotnet.py
- [[test_dotnet.py]] - code - tests/test_dotnet.py
- [[test_extract_preserves_xaml_viewmodel_edge_after_id_remap()]] - code - tests/test_dotnet.py
- [[test_extract_xaml_viewmodel_resolution_stays_inside_cache_root()]] - code - tests/test_dotnet.py
- [[test_razor_code_methods()]] - code - tests/test_dotnet.py
- [[test_razor_components()]] - code - tests/test_dotnet.py
- [[test_razor_finds_code_block_methods()]] - code - tests/test_languages.py
- [[test_razor_finds_component_references()]] - code - tests/test_languages.py
- [[test_razor_finds_inherits()]] - code - tests/test_languages.py
- [[test_razor_finds_using_directives()]] - code - tests/test_languages.py
- [[test_razor_inherits()]] - code - tests/test_dotnet.py
- [[test_razor_missing_file()]] - code - tests/test_dotnet.py
- [[test_razor_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_razor_no_error()]] - code - tests/test_languages.py
- [[test_razor_page_route()]] - code - tests/test_dotnet.py
- [[test_razor_using_and_inject()]] - code - tests/test_dotnet.py
- [[test_sln_extracts_projects()]] - code - tests/test_dotnet.py
- [[test_sln_project_dependency()]] - code - tests/test_dotnet.py
- [[test_slnx_contains_edges()]] - code - tests/test_dotnet.py
- [[test_slnx_extracts_projects()]] - code - tests/test_dotnet.py
- [[test_slnx_invalid_xml()]] - code - tests/test_dotnet.py
- [[test_slnx_missing_file()]] - code - tests/test_dotnet.py
- [[test_slnx_project_dependency()]] - code - tests/test_dotnet.py
- [[test_xaml_ambiguous_viewmodel_names_emit_no_edge()]] - code - tests/test_dotnet.py
- [[test_xaml_class_resolves_to_codebehind_partial_class()]] - code - tests/test_dotnet.py
- [[test_xaml_cs_scan_prunes_noise_dirs_and_stays_bounded()]] - code - tests/test_dotnet.py
- [[test_xaml_design_instance_datacontext_links_real_viewmodel_class()]] - code - tests/test_dotnet.py
- [[test_xaml_element_datacontext_links_real_viewmodel_class()]] - code - tests/test_dotnet.py
- [[test_xaml_event_match_requires_handler_signature()]] - code - tests/test_dotnet.py
- [[test_xaml_events_resolve_to_codebehind_methods()]] - code - tests/test_dotnet.py
- [[test_xaml_extracts_binding_paths_commands_and_converters()]] - code - tests/test_dotnet.py
- [[test_xaml_finds_class_and_event_references()]] - code - tests/test_languages.py
- [[test_xaml_infers_viewmodel_by_name_only_without_datacontext()]] - code - tests/test_dotnet.py
- [[test_xaml_links_communitytoolkit_generated_members_and_event_to_command()]] - code - tests/test_dotnet.py
- [[test_xaml_named_controls_and_bindings()]] - code - tests/test_dotnet.py
- [[test_xaml_non_event_attribute_value_does_not_fabricate_event()]] - code - tests/test_dotnet.py
- [[test_xaml_prism_autowire_false_does_not_infer_from_filename()]] - code - tests/test_dotnet.py
- [[test_xaml_prism_autowire_infers_viewmodel_from_filename()]] - code - tests/test_dotnet.py
- [[test_xaml_viewmodel_resolution_respects_graphifyignore()]] - code - tests/test_dotnet.py
- [[test_xaml_viewmodel_with_non_utf8_codebehind_does_not_crash()]] - code - tests/test_dotnet.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_dotnetpy
SORT file.name ASC
```

## Connections to other communities
- 14 edges to [[_COMMUNITY_test_languages.py]]
- 13 edges to [[_COMMUNITY_extract.py]]
- 8 edges to [[_COMMUNITY__make_id]]
- 7 edges to [[_COMMUNITY__relations]]
- 6 edges to [[_COMMUNITY__labels]]
- 5 edges to [[_COMMUNITY_Path]]
- 4 edges to [[_COMMUNITY_extract]]
- 2 edges to [[_COMMUNITY__get_extractor]]
- 1 edge to [[_COMMUNITY_test_pascal.py]]
- 1 edge to [[_COMMUNITY__is_ignored]]

## Top bridge nodes
- [[extract_xaml()]] - degree 34, connects to 5 communities
- [[test_dotnet.py]] - degree 52, connects to 4 communities
- [[extract_csproj()]] - degree 17, connects to 4 communities
- [[extract_slnx()]] - degree 11, connects to 3 communities
- [[extract_razor()]] - degree 19, connects to 2 communities