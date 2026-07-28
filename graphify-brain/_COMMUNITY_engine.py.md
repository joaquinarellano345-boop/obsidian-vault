---
type: community
cohesion: 0.02
members: 123
---

# engine.py

**Cohesion:** 0.02 - loosely connected
**Members:** 123 nodes

## Members
- [[Add TSJS receiver bindings to ``table`` (name - TypeName), for member-call]] - rationale - graphify/extractors/engine.py
- [[Build the receiver type table visible to one Java method.      Current-class fie]] - rationale - graphify/extractors/engine.py
- [[Classify a Swift inheritance_specifier entry as `inherits` or `implements`.]] - rationale - graphify/extractors/engine.py
- [[Collect ``name - TypeName`` for C receiver typing (1609) class fields,     p]] - rationale - graphify/extractors/engine.py
- [[Collect ``var - Type`` from local ``let````var`` bindings in a Swift     funct]] - rationale - graphify/extractors/engine.py
- [[Collect `decorator` nodes under `node` (e.g. parameter decorators inside a     m]] - rationale - graphify/extractors/engine.py
- [[Collect annotation names from a Java declaration's `modifiers` child.]] - rationale - graphify/extractors/engine.py
- [[Collect attribute names from a C methoddeclaration's attribute_list children.]] - rationale - graphify/extractors/engine.py
- [[Collect binding identifier names from a JSTS pattern (a parameter, or a     dec]] - rationale - graphify/extractors/engine.py
- [[Collect type refs from each typed parameter under a `parameters` node.]] - rationale - graphify/extractors/engine.py
- [[Emit `references` edges (context=decorator) from a class and its members     t]] - rationale - graphify/extractors/engine.py
- [[Extract functions, methods, require() imports, and calls from a .lua file.]] - rationale - graphify/extract.py
- [[Find the body node using config.body_field, falling back to child types.]] - rationale - graphify/extractors/engine.py
- [[Find the return-type node of a Kotlin function_declaration (the type after ` `]] - rationale - graphify/extractors/engine.py
- [[Find the user_type node within a Kotlin property_declaration.]] - rationale - graphify/extractors/engine.py
- [[Generic AST extractor driven by LanguageConfig.      ``source_override`` parses]] - rationale - graphify/extractors/engine.py
- [[Handle enum_entry for Swift. Returns True if handled.]] - rationale - graphify/extractors/engine.py
- [[Handle namespace declarations for C. Returns True if handled.]] - rationale - graphify/extractors/engine.py
- [[Identifiers bound as `pattern` targets under a Python AST subtree.      Recurses]] - rationale - graphify/extractors/engine.py
- [[If a Swift call expression is a constructor (``Foo()``), return the type name.]] - rationale - graphify/extractors/engine.py
- [[Map ``local_var - ClassName`` for ``var = ClassName.new`` within one Ruby     m]] - rationale - graphify/extractors/engine.py
- [[Module-scope names rebound to NON-function data (`const X = {...}`, `let y = 5`)]] - rationale - graphify/extractors/engine.py
- [[Name of a `method_definition`, matching the id the function-types branch     bui]] - rationale - graphify/extractors/engine.py
- [[Names bound LOCALLY inside a Python function parameters plus assignment,     `f]] - rationale - graphify/extractors/engine.py
- [[Names bound locally inside a JSTS function parameters plus `const``let`]] - rationale - graphify/extractors/engine.py
- [[Names rebound by assignment at MODULE scope (top-level `x = ...`, `for`, walrus)]] - rationale - graphify/extractors/engine.py
- [[Path_19]] - code
- [[Plain parameter identifiers declared on a Python `parameters` node.      Covers]] - rationale - graphify/extractors/engine.py
- [[Pre-scan a Swift compilation unit and return (protocol_names, class_like_names).]] - rationale - graphify/extractors/engine.py
- [[Recursively unwrap declarator to find the innermost identifier (C++).]] - rationale - graphify/extractors/engine.py
- [[Resolve a C type name, whether it was qualified, and its qualifier prefix.]] - rationale - graphify/extractors/engine.py
- [[Return C type-parameter names visible from ``node``.]] - rationale - graphify/extractors/engine.py
- [[Return ``ClassName`` if ``node`` is a ``ClassName.new(...)`` call, else None.]] - rationale - graphify/extractors/engine.py
- [[Return names declared as `interface` in this C compilation unit.]] - rationale - graphify/extractors/engine.py
- [[Return the bound name of a Swift property (``let x````var x = ...``).]] - rationale - graphify/extractors/engine.py
- [[Return the call_expression node if `value_node` is a `require(...)` call     or]] - rationale - graphify/extractors/engine.py
- [[Return the concrete declared type usable for Java receiver resolution.]] - rationale - graphify/extractors/engine.py
- [[Return the depth-1 receiver name of a Swift member call (``recv.method()``).]] - rationale - graphify/extractors/engine.py
- [[Return the head identifier text from a Kotlin user_type node (without generics).]] - rationale - graphify/extractors/engine.py
- [[Return the head symbol of a Python `decorator` node.      The Python twin of `_t]] - rationale - graphify/extractors/engine.py
- [[Return the head symbol of a TS `decorator` node.      `@Injectable` - the ident]] - rationale - graphify/extractors/engine.py
- [[Return the head type_identifier text from a Swift user_type node (without generi]] - rationale - graphify/extractors/engine.py
- [[Return the leading kind token for a Swift class_declaration classstructenume]] - rationale - graphify/extractors/engine.py
- [[Return the named_typeprimitive_type node sitting after formal_parameters.]] - rationale - graphify/extractors/engine.py
- [[Return the type_annotation child of a Swift property_declaration, if any.]] - rationale - graphify/extractors/engine.py
- [[Return the unqualified name text from a PHP `name``qualified_name` node.]] - rationale - graphify/extractors/engine.py
- [[Walk a C type expression; append (name, role) tuples for user-defined types.]] - rationale - graphify/extractors/engine.py
- [[Walk a C type expression; append (name, role, qualified, qualifier) tuples.]] - rationale - graphify/extractors/engine.py
- [[Walk a Java type expression; append (name, role) tuples.]] - rationale - graphify/extractors/engine.py
- [[Walk a Kotlin type expression; append (name, role) tuples.]] - rationale - graphify/extractors/engine.py
- [[Walk a PHP type expression; append (name, role) tuples.]] - rationale - graphify/extractors/engine.py
- [[Walk a Python type annotation; append (name, role) where role is 'type' or 'gene]] - rationale - graphify/extractors/engine.py
- [[Walk a Scala type expression; append (name, role) tuples.     Handles type_ident]] - rationale - graphify/extractors/engine.py
- [[Walk a Swift type expression; append (name, role) tuples (role 'type' or 'generi]] - rationale - graphify/extractors/engine.py
- [[When Language() raises TypeError (e.g. old tree-sitter binding meets a     new t]] - rationale - tests/test_extract.py
- [[Yield identifier value-nodes of a JSTS objectarray literal that are     functi]] - rationale - graphify/extractors/engine.py
- [[_c_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_cpp_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_csharp_attribute_names()]] - code - graphify/extractors/engine.py
- [[_csharp_classify_base()]] - code - graphify/extractors/engine.py
- [[_csharp_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_csharp_extra_walk()]] - code - graphify/extractors/engine.py
- [[_csharp_member_type_table()]] - code - graphify/extractors/engine.py
- [[_csharp_namespace_id()]] - code - graphify/extractors/engine.py
- [[_csharp_namespace_name()]] - code - graphify/extractors/engine.py
- [[_csharp_pre_scan_interfaces()]] - code - graphify/extractors/engine.py
- [[_csharp_type_parameters_in_scope()]] - code - graphify/extractors/engine.py
- [[_extract_generic()]] - code - graphify/extractors/engine.py
- [[_find_body()]] - code - graphify/extractors/engine.py
- [[_find_require_call()]] - code - graphify/extractors/engine.py
- [[_get_cpp_func_name()]] - code - graphify/extractors/engine.py
- [[_java_annotation_names()]] - code - graphify/extractors/engine.py
- [[_java_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_java_declarator_names()]] - code - graphify/extractors/engine.py
- [[_java_lambda_parameters()]] - code - graphify/extractors/engine.py
- [[_java_method_receiver_types()]] - code - graphify/extractors/engine.py
- [[_java_receiver_type_name()]] - code - graphify/extractors/engine.py
- [[_java_type_parameters_in_scope()]] - code - graphify/extractors/engine.py
- [[_js_collect_pattern_idents()]] - code - graphify/extractors/engine.py
- [[_js_dispatch_value_idents()]] - code - graphify/extractors/engine.py
- [[_js_local_bound_names()]] - code - graphify/extractors/engine.py
- [[_js_module_bound_names()]] - code - graphify/extractors/engine.py
- [[_kotlin_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_kotlin_function_return_type_node()]] - code - graphify/extractors/engine.py
- [[_kotlin_property_type_node()]] - code - graphify/extractors/engine.py
- [[_kotlin_user_type_name()]] - code - graphify/extractors/engine.py
- [[_php_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_php_method_return_type_node()]] - code - graphify/extractors/engine.py
- [[_php_name_text()]] - code - graphify/extractors/engine.py
- [[_python_collect_assignment_targets()]] - code - graphify/extractors/engine.py
- [[_python_collect_param_refs()]] - code - graphify/extractors/engine.py
- [[_python_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_python_decorator_name()]] - code - graphify/extractors/engine.py
- [[_python_local_bound_names()]] - code - graphify/extractors/engine.py
- [[_python_module_bound_names()]] - code - graphify/extractors/engine.py
- [[_python_param_names()]] - code - graphify/extractors/engine.py
- [[_read_csharp_type_name()]] - code - graphify/extractors/engine.py
- [[_ruby_local_class_bindings()]] - code - graphify/extractors/engine.py
- [[_ruby_new_class_name()]] - code - graphify/extractors/engine.py
- [[_scala_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_semantic_reference_edge()]] - code - graphify/extractors/engine.py
- [[_source_location()]] - code - graphify/extractors/engine.py
- [[_swift_classify_base()]] - code - graphify/extractors/engine.py
- [[_swift_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_swift_constructor_type()]] - code - graphify/extractors/engine.py
- [[_swift_declaration_keyword()]] - code - graphify/extractors/engine.py
- [[_swift_extra_walk()]] - code - graphify/extractors/engine.py
- [[_swift_local_var_types()]] - code - graphify/extractors/engine.py
- [[_swift_pre_scan()]] - code - graphify/extractors/engine.py
- [[_swift_property_name()]] - code - graphify/extractors/engine.py
- [[_swift_property_type_node()]] - code - graphify/extractors/engine.py
- [[_swift_receiver_name()]] - code - graphify/extractors/engine.py
- [[_swift_user_type_name()]] - code - graphify/extractors/engine.py
- [[_ts_decorator_name()]] - code - graphify/extractors/engine.py
- [[_ts_descendant_decorators()]] - code - graphify/extractors/engine.py
- [[_ts_emit_decorator_edges()]] - code - graphify/extractors/engine.py
- [[_ts_method_name()]] - code - graphify/extractors/engine.py
- [[_ts_receiver_type_table()]] - code - graphify/extractors/engine.py
- [[`implements` if the base name is an interface (declared or by I-prefix conventio]] - rationale - graphify/extractors/engine.py
- [[engine — moved verbatim from graphifyextract.py.]] - rationale - graphify/extractors/engine.py
- [[engine.py]] - code - graphify/extractors/engine.py
- [[extract_lua()]] - code - graphify/extract.py
- [[test_extract_generic_surfaces_tree_sitter_version_mismatch_hint()]] - code - tests/test_extract.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/enginepy
SORT file.name ASC
```

## Connections to other communities
- 65 edges to [[_COMMUNITY_extract.py]]
- 62 edges to [[_COMMUNITY__read_text]]
- 4 edges to [[_COMMUNITY_test_languages.py]]
- 3 edges to [[_COMMUNITY__edge_labels]]
- 3 edges to [[_COMMUNITY__cpp_declarator_name]]
- 3 edges to [[_COMMUNITY_make_id]]
- 2 edges to [[_COMMUNITY_Path]]
- 2 edges to [[_COMMUNITY_extract_astro]]
- 2 edges to [[_COMMUNITY__resolve_js_import_target]]
- 2 edges to [[_COMMUNITY_sanitize_metadata]]
- 2 edges to [[_COMMUNITY_test_extract.py]]
- 1 edge to [[_COMMUNITY_extract_python]]
- 1 edge to [[_COMMUNITY_extract_js]]
- 1 edge to [[_COMMUNITY_test_vue_extraction.py]]
- 1 edge to [[_COMMUNITY_test_ruby_resolution.py]]
- 1 edge to [[_COMMUNITY__relations]]
- 1 edge to [[_COMMUNITY__labels]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_extract_objc]]
- 1 edge to [[_COMMUNITY_e]]

## Top bridge nodes
- [[_extract_generic()]] - degree 38, connects to 16 communities
- [[engine.py]] - degree 89, connects to 7 communities
- [[_semantic_reference_edge()]] - degree 8, connects to 5 communities
- [[_swift_local_var_types()]] - degree 7, connects to 2 communities
- [[_csharp_type_parameters_in_scope()]] - degree 6, connects to 2 communities