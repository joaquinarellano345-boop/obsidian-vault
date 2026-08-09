---
type: community
cohesion: 0.02
members: 120
---

# engine.py

**Cohesion:** 0.02 - loosely connected
**Members:** 120 nodes

## Members
- [[Build the receiver type table visible to one Java method.      Current-class fie]] - rationale - graphify/extractors/engine.py
- [[Classify a Swift inheritance_specifier entry as `inherits` or `implements`.]] - rationale - graphify/extractors/engine.py
- [[Classify the symbol an `assignment_expression` LHS defines when its RHS     is a]] - rationale - graphify/extractors/engine.py
- [[Collect ``var - ClassName`` from ObjC local declarations (``Foo f = ...;``)]] - rationale - graphify/extractors/objc.py
- [[Collect ``var - ClassName`` from local variable declarations in a C++     funct]] - rationale - graphify/extractors/engine.py
- [[Collect `decorator` nodes under `node` (e.g. parameter decorators inside a     m]] - rationale - graphify/extractors/engine.py
- [[Collect annotation names from a Java declaration's `modifiers` child.]] - rationale - graphify/extractors/engine.py
- [[Collect binding identifier names from a JSTS pattern (a parameter, or a     dec]] - rationale - graphify/extractors/engine.py
- [[Collect type refs from each typed parameter under a `parameters` node.]] - rationale - graphify/extractors/engine.py
- [[Detect CommonJS require imports inside lexical_declaration  variable_declaratio]] - rationale - graphify/extractors/engine.py
- [[Detect dynamic import() calls in JSTS and emit imports_from edges.      Handles]] - rationale - graphify/extractors/engine.py
- [[Emit `references` edges (context=decorator) from a class and its members     t]] - rationale - graphify/extractors/engine.py
- [[Emit a container node for a TS `namespace``module` declaration.      `namespace]] - rationale - graphify/extractors/engine.py
- [[Find the body node using config.body_field, falling back to child types.]] - rationale - graphify/extractors/engine.py
- [[Find the return-type node of a Kotlin function_declaration (the type after ` `]] - rationale - graphify/extractors/engine.py
- [[Find the user_type node within a Kotlin property_declaration.]] - rationale - graphify/extractors/engine.py
- [[Handle enum_constant for Java. Returns True if handled.]] - rationale - graphify/extractors/engine.py
- [[Handle enum_entry for Kotlin. Returns True if handled (1700 Kotlin half).]] - rationale - graphify/extractors/engine.py
- [[Handle enum_entry for Swift. Returns True if handled.]] - rationale - graphify/extractors/engine.py
- [[Handle lexical_declaration (arrow functions, CJS requires, module-level const li]] - rationale - graphify/extractors/engine.py
- [[Handle namespace declarations for C. Returns True if handled.]] - rationale - graphify/extractors/engine.py
- [[Identifiers bound as `pattern` targets under a Python AST subtree.      Recurses]] - rationale - graphify/extractors/engine.py
- [[Last constant of a ``constant`` or ``scope_resolution`` (``ABC`` - ``C``).]] - rationale - graphify/extractors/engine.py
- [[Name of a `method_definition`, matching the id the function-types branch     bui]] - rationale - graphify/extractors/engine.py
- [[Names bound LOCALLY inside a Python function parameters plus assignment,     `f]] - rationale - graphify/extractors/engine.py
- [[Names bound locally inside a JSTS function parameters plus `const``let`]] - rationale - graphify/extractors/engine.py
- [[Plain parameter identifiers declared on a Python `parameters` node.      Covers]] - rationale - graphify/extractors/engine.py
- [[Recursively unwrap declarator to find the innermost identifier (C++).]] - rationale - graphify/extractors/engine.py
- [[Resolve a C type name, whether it was qualified, and its qualifier prefix.]] - rationale - graphify/extractors/engine.py
- [[Resolve a JSTS import path string to (target_nid, resolved_path).      Handles]] - rationale - graphify/extractors/resolution.py
- [[Return C type-parameter names visible from ``node``.]] - rationale - graphify/extractors/engine.py
- [[Return ``ClassName`` if ``node`` is a ``ClassName.new(...)`` call, else None.]] - rationale - graphify/extractors/engine.py
- [[Return the bare variable name from a C++ declaration declarator, unwrapping]] - rationale - graphify/extractors/engine.py
- [[Return the call_expression node if `value_node` is a `require(...)` call     or]] - rationale - graphify/extractors/engine.py
- [[Return the concrete declared type usable for Java receiver resolution.]] - rationale - graphify/extractors/engine.py
- [[Return the depth-1 receiver name of a Swift member call (``recv.method()``).]] - rationale - graphify/extractors/engine.py
- [[Return the head identifier text from a Kotlin user_type node (without generics).]] - rationale - graphify/extractors/engine.py
- [[Return the head symbol of a Python `decorator` node.      The Python twin of `_t]] - rationale - graphify/extractors/engine.py
- [[Return the head symbol of a TS `decorator` node.      `@Injectable` - the ident]] - rationale - graphify/extractors/engine.py
- [[Return the head type_identifier text from a Swift user_type node (without generi]] - rationale - graphify/extractors/engine.py
- [[Return the named_typeprimitive_type node sitting after formal_parameters.]] - rationale - graphify/extractors/engine.py
- [[Return the type_annotation child of a Swift property_declaration, if any.]] - rationale - graphify/extractors/engine.py
- [[Return the unqualified name text from a PHP `name``qualified_name` node.]] - rationale - graphify/extractors/engine.py
- [[Ruby a constant assignment whose RHS is ``Struct.new(...)``,     ``Class.new(Su]] - rationale - graphify/extractors/engine.py
- [[Walk a C type expression; append (name, role) tuples for user-defined types.]] - rationale - graphify/extractors/engine.py
- [[Walk a Java type expression; append (name, role) tuples.]] - rationale - graphify/extractors/engine.py
- [[Walk a Kotlin type expression; append (name, role) tuples.]] - rationale - graphify/extractors/engine.py
- [[Walk a PHP type expression; append (name, role) tuples.]] - rationale - graphify/extractors/engine.py
- [[Walk a Python type annotation; append (name, role) where role is 'type' or 'gene]] - rationale - graphify/extractors/engine.py
- [[Walk a Scala type expression; append (name, role) tuples.     Handles type_ident]] - rationale - graphify/extractors/engine.py
- [[Walk a Swift type expression; append (name, role) tuples (role 'type' or 'generi]] - rationale - graphify/extractors/engine.py
- [[Yield identifier value-nodes of a JSTS objectarray literal that are     functi]] - rationale - graphify/extractors/engine.py
- [[_c_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_cpp_declarator_name()]] - code - graphify/extractors/engine.py
- [[_cpp_local_var_types()]] - code - graphify/extractors/engine.py
- [[_csharp_classify_base()]] - code - graphify/extractors/engine.py
- [[_csharp_extra_walk()]] - code - graphify/extractors/engine.py
- [[_csharp_namespace_id()]] - code - graphify/extractors/engine.py
- [[_csharp_namespace_name()]] - code - graphify/extractors/engine.py
- [[_dynamic_import_js()]] - code - graphify/extractors/engine.py
- [[_find_body()]] - code - graphify/extractors/engine.py
- [[_find_require_call()]] - code - graphify/extractors/engine.py
- [[_get_cpp_func_name()]] - code - graphify/extractors/engine.py
- [[_import_js()]] - code - graphify/extract.py
- [[_java_annotation_names()]] - code - graphify/extractors/engine.py
- [[_java_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_java_declarator_names()]] - code - graphify/extractors/engine.py
- [[_java_extra_walk()]] - code - graphify/extractors/engine.py
- [[_java_lambda_parameters()]] - code - graphify/extractors/engine.py
- [[_java_method_receiver_types()]] - code - graphify/extractors/engine.py
- [[_java_receiver_type_name()]] - code - graphify/extractors/engine.py
- [[_java_type_parameters_in_scope()]] - code - graphify/extractors/engine.py
- [[_js_collect_pattern_idents()]] - code - graphify/extractors/engine.py
- [[_js_dispatch_value_idents()]] - code - graphify/extractors/engine.py
- [[_js_extra_walk()]] - code - graphify/extractors/engine.py
- [[_js_local_bound_names()]] - code - graphify/extractors/engine.py
- [[_js_member_assignment_target()]] - code - graphify/extractors/engine.py
- [[_kotlin_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_kotlin_extra_walk()]] - code - graphify/extractors/engine.py
- [[_kotlin_function_return_type_node()]] - code - graphify/extractors/engine.py
- [[_kotlin_property_type_node()]] - code - graphify/extractors/engine.py
- [[_kotlin_user_type_name()]] - code - graphify/extractors/engine.py
- [[_objc_local_var_types()]] - code - graphify/extractors/objc.py
- [[_php_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_php_method_return_type_node()]] - code - graphify/extractors/engine.py
- [[_php_name_text()]] - code - graphify/extractors/engine.py
- [[_python_collect_assignment_targets()]] - code - graphify/extractors/engine.py
- [[_python_collect_param_refs()]] - code - graphify/extractors/engine.py
- [[_python_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_python_decorator_name()]] - code - graphify/extractors/engine.py
- [[_python_local_bound_names()]] - code - graphify/extractors/engine.py
- [[_python_param_names()]] - code - graphify/extractors/engine.py
- [[_read_csharp_type_name()]] - code - graphify/extractors/engine.py
- [[_require_imports_js()]] - code - graphify/extractors/engine.py
- [[_resolve_js_import_target()]] - code - graphify/extractors/resolution.py
- [[_ruby_const_last_name()]] - code - graphify/extractors/engine.py
- [[_ruby_extra_walk()]] - code - graphify/extractors/engine.py
- [[_ruby_new_class_name()]] - code - graphify/extractors/engine.py
- [[_scala_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_semantic_reference_edge()]] - code - graphify/extractors/engine.py
- [[_source_location()]] - code - graphify/extractors/engine.py
- [[_swift_classify_base()]] - code - graphify/extractors/engine.py
- [[_swift_collect_type_refs()]] - code - graphify/extractors/engine.py
- [[_swift_extra_walk()]] - code - graphify/extractors/engine.py
- [[_swift_property_type_node()]] - code - graphify/extractors/engine.py
- [[_swift_receiver_name()]] - code - graphify/extractors/engine.py
- [[_swift_user_type_name()]] - code - graphify/extractors/engine.py
- [[_ts_decorator_name()]] - code - graphify/extractors/engine.py
- [[_ts_descendant_decorators()]] - code - graphify/extractors/engine.py
- [[_ts_emit_decorator_edges()]] - code - graphify/extractors/engine.py
- [[_ts_extra_walk()]] - code - graphify/extractors/engine.py
- [[_ts_method_name()]] - code - graphify/extractors/engine.py
- [[`implements` if the base name is an interface (declared or by I-prefix conventio]] - rationale - graphify/extractors/engine.py
- [[engine — moved verbatim from graphifyextract.py.]] - rationale - graphify/extractors/engine.py
- [[engine.py]] - code - graphify/extractors/engine.py
- [[extractorsbase.py]] - code - graphify/extractors/base.py
- [[julia — moved verbatim from graphifyextract.py.]] - rationale - graphify/extractors/julia.py
- [[julia.py]] - code - graphify/extractors/julia.py
- [[objc — moved verbatim from graphifyextract.py.]] - rationale - graphify/extractors/objc.py
- [[objc.py]] - code - graphify/extractors/objc.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/enginepy
SORT file.name ASC
```

## Connections to other communities
- 116 edges to [[_COMMUNITY_extract.py]]
- 41 edges to [[_COMMUNITY__make_id]]
- 14 edges to [[_COMMUNITY__extract_generic]]
- 5 edges to [[_COMMUNITY_make_id]]
- 3 edges to [[_COMMUNITY_extract_objc]]
- 2 edges to [[_COMMUNITY_test_languages.py]]
- 2 edges to [[_COMMUNITY_test_phantom_external_import.py]]
- 1 edge to [[_COMMUNITY_CsharpNameResolver]]
- 1 edge to [[_COMMUNITY__extract_pascal_regex]]
- 1 edge to [[_COMMUNITY__get_extractor]]
- 1 edge to [[_COMMUNITY_symbol_resolution.py]]
- 1 edge to [[_COMMUNITY__semantic_id_remap]]
- 1 edge to [[_COMMUNITY_security.py]]
- 1 edge to [[_COMMUNITY_test_security.py]]
- 1 edge to [[_COMMUNITY_test_extract.py]]
- 1 edge to [[_COMMUNITY_test_import_extension_resolution.py]]

## Top bridge nodes
- [[extractorsbase.py]] - degree 34, connects to 8 communities
- [[engine.py]] - degree 89, connects to 6 communities
- [[_resolve_js_import_target()]] - degree 12, connects to 4 communities
- [[_semantic_reference_edge()]] - degree 8, connects to 4 communities
- [[objc.py]] - degree 14, connects to 3 communities