---
type: community
cohesion: 0.05
members: 43
---

# extract_objc

**Cohesion:** 0.05 - loosely connected
**Members:** 43 nodes

## Members
- [[@selector(doThing) must resolve to `-doThing` exactly, not be suppressed by]] - rationale - tests/test_languages.py
- [[@selector(doThing) with two doThing methods must emit zero calls edges.]] - rationale - tests/test_languages.py
- [[@selector(uniqueMethod) with exactly one match produces a calls edge.]] - rationale - tests/test_languages.py
- [[A compound message `self ax by` resolves to the compound method def (1475).]] - rationale - tests/test_languages.py
- [[A macro-free header still parses exactly as before (regression).]] - rationale - tests/test_languages.py
- [[A substring-colliding sibling must neither be falsely matched nor suppress     t]] - rationale - tests/test_languages.py
- [[Accessing a property not defined in the current class produces zero accesses edg]] - rationale - tests/test_languages.py
- [[Extract interfaces, implementations, protocols, methods, and imports from .m.mm]] - rationale - graphify/extractors/objc.py
- [[Path_25]] - code
- [[Two classes each declaring -name self.name in A must NOT fan out to B's -name.]] - rationale - tests/test_languages.py
- [[`+ (…)shared` is a class method and must be labeled +shared, not -shared (1475)]] - rationale - tests/test_languages.py
- [[`@import Foundation;`  `@import UIKit.UIView;` produce imports edges (1475).]] - rationale - tests/test_languages.py
- [[`@protocol Derived Base` must emit an implements edge Derived-Base.     Proto]] - rationale - tests/test_languages.py
- [[`NSArrayProduct  ` must reference the element type Product (and the     cont]] - rationale - tests/test_languages.py
- [[`NS_ASSUME_NONNULL_BEGIN` before `@interface` made tree-sitter-objc fail to]] - rationale - tests/test_languages.py
- [[`Unknown alloc init` with no such class must not produce a resolved     refe]] - rationale - tests/test_languages.py
- [[`self speak` inside Dog.fetch must produce a calls edge. The method-body     s]] - rationale - tests/test_languages.py
- [[extract_objc()]] - code - graphify/extractors/objc.py
- [[self.name dot-syntax resolves to an accesses edge within the same class.]] - rationale - tests/test_languages.py
- [[test_objc_alloc_init_unknown_class_no_resolved_edge()]] - code - tests/test_languages.py
- [[test_objc_class_method_labeled_with_plus()]] - code - tests/test_languages.py
- [[test_objc_compound_selector_call_resolves()]] - code - tests/test_languages.py
- [[test_objc_dot_syntax_no_fanout_two_same_named_properties()]] - code - tests/test_languages.py
- [[test_objc_dot_syntax_property_accesses_edge()]] - code - tests/test_languages.py
- [[test_objc_dot_syntax_substring_sibling_exact_match()]] - code - tests/test_languages.py
- [[test_objc_dot_syntax_unresolvable_property_zero_edges()]] - code - tests/test_languages.py
- [[test_objc_finds_imports()]] - code - tests/test_languages.py
- [[test_objc_finds_interface()]] - code - tests/test_languages.py
- [[test_objc_finds_methods()]] - code - tests/test_languages.py
- [[test_objc_finds_subclass()]] - code - tests/test_languages.py
- [[test_objc_generic_property_type_extracted()]] - code - tests/test_languages.py
- [[test_objc_inherits_edge()]] - code - tests/test_languages.py
- [[test_objc_macro_free_header_unchanged()]] - code - tests/test_languages.py
- [[test_objc_module_import_edge()]] - code - tests/test_languages.py
- [[test_objc_no_dangling_edges()]] - code - tests/test_languages.py
- [[test_objc_ns_assume_nonnull_macro_does_not_break_parsing()]] - code - tests/test_languages.py
- [[test_objc_property_type_context()]] - code - tests/test_languages.py
- [[test_objc_protocol_adopts_protocol()]] - code - tests/test_languages.py
- [[test_objc_resolves_self_method_calls()]] - code - tests/test_languages.py
- [[test_objc_selector_expression_calls_edge()]] - code - tests/test_languages.py
- [[test_objc_selector_no_fanout_two_same_named_methods()]] - code - tests/test_languages.py
- [[test_objc_selector_substring_method_exact_match()]] - code - tests/test_languages.py
- [[test_objc_splits_inherits_and_implements()]] - code - tests/test_languages.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/extract_objc
SORT file.name ASC
```

## Connections to other communities
- 25 edges to [[_COMMUNITY_test_languages.py]]
- 6 edges to [[_COMMUNITY__edge_labels]]
- 4 edges to [[_COMMUNITY__read_text]]
- 2 edges to [[_COMMUNITY_extract.py]]
- 1 edge to [[_COMMUNITY_Path]]
- 1 edge to [[_COMMUNITY_engine.py]]
- 1 edge to [[_COMMUNITY__cpp_declarator_name]]
- 1 edge to [[_COMMUNITY_e]]

## Top bridge nodes
- [[extract_objc()]] - degree 37, connects to 7 communities
- [[test_objc_generic_property_type_extracted()]] - degree 4, connects to 2 communities
- [[test_objc_macro_free_header_unchanged()]] - degree 4, connects to 2 communities
- [[test_objc_ns_assume_nonnull_macro_does_not_break_parsing()]] - degree 4, connects to 2 communities
- [[test_objc_protocol_adopts_protocol()]] - degree 4, connects to 2 communities