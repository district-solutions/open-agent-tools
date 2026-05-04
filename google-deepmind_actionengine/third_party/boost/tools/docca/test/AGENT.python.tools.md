# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/boost/tools/docca/test/docca_qbk_test.py

Prompts

```
['test the docca quickbook escape helper to escape special characters like double brackets', 'test the docca quickbook text helper for string replacement and code formatting', 'test the docca quickbook link helper to generate entity link names with namespace prefixes', 'test the docca quickbook function declaration helper to render C++ function signatures', 'test the docca quickbook write entity helper to render full documentation sections for C++ entities', 'use docca.make_blocks to parse Doxygen XML elements into Paragraph, Section, CodeBlock, and Table block structures', 'use docca.make_phrase to parse Doxygen XML elements into inline phrase structures like Strong, Emphasised, and Monospaced', 'create a docca.Namespace from Doxygen XML and call resolve_references to resolve scope and member relationships', 'create a docca.Class, Struct, or Union from Doxygen XML and resolve base classes, members, and template parameters', 'create a docca.Function from Doxygen XML and resolve parameters, return types, and overload sets via OverloadSet', 'create a MockXmlElem instance with a custom tag name for testing XML element behavior', 'test the MockXmlElem findall method to find all child elements matching a given tag', 'test the MockXmlElem find method to retrieve the first child element matching a tag', 'test the MockXmlElem itertext method to recursively collect all text content from the element tree', 'build a MockXmlElem tree from a dictionary using make_elem with nested items and attributes']
```

Usage

```
{'test_escape_quickbook': 'test the docca quickbook escape helper to escape special characters like double brackets', 'test_text_helper_quickbook': 'test the docca quickbook text helper for string replacement and code formatting', 'test_link_quickbook': 'test the docca quickbook link helper to generate entity link names with namespace prefixes', 'test_function_declaration_quickbook': 'test the docca quickbook function declaration helper to render C++ function signatures', 'test_write_entity_quickbook': 'test the docca quickbook write entity helper to render full documentation sections for C++ entities'}
```

## File: google-deepmind_actionengine/third_party/boost/tools/docca/test/docca_test.py

Prompts

```
['test the docca quickbook escape helper to escape special characters like double brackets', 'test the docca quickbook text helper for string replacement and code formatting', 'test the docca quickbook link helper to generate entity link names with namespace prefixes', 'test the docca quickbook function declaration helper to render C++ function signatures', 'test the docca quickbook write entity helper to render full documentation sections for C++ entities', 'use docca.make_blocks to parse Doxygen XML elements into Paragraph, Section, CodeBlock, and Table block structures', 'use docca.make_phrase to parse Doxygen XML elements into inline phrase structures like Strong, Emphasised, and Monospaced', 'create a docca.Namespace from Doxygen XML and call resolve_references to resolve scope and member relationships', 'create a docca.Class, Struct, or Union from Doxygen XML and resolve base classes, members, and template parameters', 'create a docca.Function from Doxygen XML and resolve parameters, return types, and overload sets via OverloadSet', 'create a MockXmlElem instance with a custom tag name for testing XML element behavior', 'test the MockXmlElem findall method to find all child elements matching a given tag', 'test the MockXmlElem find method to retrieve the first child element matching a tag', 'test the MockXmlElem itertext method to recursively collect all text content from the element tree', 'build a MockXmlElem tree from a dictionary using make_elem with nested items and attributes']
```

Usage

```
{'parse_doxygen_xml_into_blocks': 'use docca.make_blocks to parse Doxygen XML elements into Paragraph, Section, CodeBlock, and Table block structures', 'parse_doxygen_phrases': 'use docca.make_phrase to parse Doxygen XML elements into inline phrase structures like Strong, Emphasised, and Monospaced', 'build_namespace_entity': 'create a docca.Namespace from Doxygen XML and call resolve_references to resolve scope and member relationships', 'build_class_entity': 'create a docca.Class, Struct, or Union from Doxygen XML and resolve base classes, members, and template parameters', 'build_function_entity': 'create a docca.Function from Doxygen XML and resolve parameters, return types, and overload sets via OverloadSet'}
```

## File: google-deepmind_actionengine/third_party/boost/tools/docca/test/docca_test_helpers.py

Prompts

```
['test the docca quickbook escape helper to escape special characters like double brackets', 'test the docca quickbook text helper for string replacement and code formatting', 'test the docca quickbook link helper to generate entity link names with namespace prefixes', 'test the docca quickbook function declaration helper to render C++ function signatures', 'test the docca quickbook write entity helper to render full documentation sections for C++ entities', 'use docca.make_blocks to parse Doxygen XML elements into Paragraph, Section, CodeBlock, and Table block structures', 'use docca.make_phrase to parse Doxygen XML elements into inline phrase structures like Strong, Emphasised, and Monospaced', 'create a docca.Namespace from Doxygen XML and call resolve_references to resolve scope and member relationships', 'create a docca.Class, Struct, or Union from Doxygen XML and resolve base classes, members, and template parameters', 'create a docca.Function from Doxygen XML and resolve parameters, return types, and overload sets via OverloadSet', 'create a MockXmlElem instance with a custom tag name for testing XML element behavior', 'test the MockXmlElem findall method to find all child elements matching a given tag', 'test the MockXmlElem find method to retrieve the first child element matching a tag', 'test the MockXmlElem itertext method to recursively collect all text content from the element tree', 'build a MockXmlElem tree from a dictionary using make_elem with nested items and attributes']
```

Usage

```
{'create_mockxmlelem_instance': 'create a MockXmlElem instance with a custom tag name for testing XML element behavior', 'test_mockxmlelem_findall': 'test the MockXmlElem findall method to find all child elements matching a given tag', 'test_mockxmlelem_find': 'test the MockXmlElem find method to retrieve the first child element matching a tag', 'test_mockxmlelem_itertext': 'test the MockXmlElem itertext method to recursively collect all text content from the element tree', 'build_make_elem_tree': 'build a MockXmlElem tree from a dictionary using make_elem with nested items and attributes'}
```

