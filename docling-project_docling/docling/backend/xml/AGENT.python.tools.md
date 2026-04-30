# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/backend/xml/jats_backend.py

Prompts

```
['build a JATS XML parser backend that converts Journal Article Tag Suite XML into DoclingDocument format', 'create a JatsDocumentBackend instance and call convert to parse a JATS XML file into a structured document', 'test the parse_table_data static method to extract table data from HTML-tagged table content', 'refactor the _parse_metadata method to extract title, authors, and abstract from JATS XML metadata', 'review the _parse_element_citation method to parse JATS element-citation nodes into formatted citation strings', 'build a PatentUsptoDocumentBackend to parse USPTO patent XML files into a DoclingDocument', 'create a PatentUsptoIce parser instance to parse USPTO patent grant or application XML v4 documents', 'parse a PatentUsptoGrantV2 XML document from 2002-2004 into a structured DoclingDocument', 'parse a PatentUsptoGrantAps text patent document from 1976-2001 into a DoclingDocument', 'parse an XML table string into a TableData object with TableCell entries and column spans', 'create an XBRL document backend from a file path and taxonomy directory options', 'convert an XBRL instance document to a DoclingDocument with key-value pairs and hierarchy', 'test whether an XBRL document backend loaded a valid XBRL instance file', 'summarize the input formats supported by the XBRL document backend', 'run the XBRL backend unload method to close and release model resources']
```

Usage

```
{'build_jats_xml_parser': 'build a JATS XML parser backend that converts Journal Article Tag Suite XML into DoclingDocument format', 'create_jats_backend_convert': 'create a JatsDocumentBackend instance and call convert to parse a JATS XML file into a structured document', 'test_parse_table_data': 'test the parse_table_data static method to extract table data from HTML-tagged table content', 'refactor_parse_metadata': 'refactor the _parse_metadata method to extract title, authors, and abstract from JATS XML metadata', 'review_parse_element_citation': 'review the _parse_element_citation method to parse JATS element-citation nodes into formatted citation strings'}
```

## File: docling-project_docling/docling/backend/xml/uspto_backend.py

Prompts

```
['build a JATS XML parser backend that converts Journal Article Tag Suite XML into DoclingDocument format', 'create a JatsDocumentBackend instance and call convert to parse a JATS XML file into a structured document', 'test the parse_table_data static method to extract table data from HTML-tagged table content', 'refactor the _parse_metadata method to extract title, authors, and abstract from JATS XML metadata', 'review the _parse_element_citation method to parse JATS element-citation nodes into formatted citation strings', 'build a PatentUsptoDocumentBackend to parse USPTO patent XML files into a DoclingDocument', 'create a PatentUsptoIce parser instance to parse USPTO patent grant or application XML v4 documents', 'parse a PatentUsptoGrantV2 XML document from 2002-2004 into a structured DoclingDocument', 'parse a PatentUsptoGrantAps text patent document from 1976-2001 into a DoclingDocument', 'parse an XML table string into a TableData object with TableCell entries and column spans', 'create an XBRL document backend from a file path and taxonomy directory options', 'convert an XBRL instance document to a DoclingDocument with key-value pairs and hierarchy', 'test whether an XBRL document backend loaded a valid XBRL instance file', 'summarize the input formats supported by the XBRL document backend', 'run the XBRL backend unload method to close and release model resources']
```

Usage

```
{'build_uspto_patent_backend': 'build a PatentUsptoDocumentBackend to parse USPTO patent XML files into a DoclingDocument', 'create_patent_ice_parser': 'create a PatentUsptoIce parser instance to parse USPTO patent grant or application XML v4 documents', 'parse_patent_grant_v2': 'parse a PatentUsptoGrantV2 XML document from 2002-2004 into a structured DoclingDocument', 'parse_patent_grant_aps': 'parse a PatentUsptoGrantAps text patent document from 1976-2001 into a DoclingDocument', 'parse_xml_table': 'parse an XML table string into a TableData object with TableCell entries and column spans'}
```

## File: docling-project_docling/docling/backend/xml/xbrl_backend.py

Prompts

```
['build a JATS XML parser backend that converts Journal Article Tag Suite XML into DoclingDocument format', 'create a JatsDocumentBackend instance and call convert to parse a JATS XML file into a structured document', 'test the parse_table_data static method to extract table data from HTML-tagged table content', 'refactor the _parse_metadata method to extract title, authors, and abstract from JATS XML metadata', 'review the _parse_element_citation method to parse JATS element-citation nodes into formatted citation strings', 'build a PatentUsptoDocumentBackend to parse USPTO patent XML files into a DoclingDocument', 'create a PatentUsptoIce parser instance to parse USPTO patent grant or application XML v4 documents', 'parse a PatentUsptoGrantV2 XML document from 2002-2004 into a structured DoclingDocument', 'parse a PatentUsptoGrantAps text patent document from 1976-2001 into a DoclingDocument', 'parse an XML table string into a TableData object with TableCell entries and column spans', 'create an XBRL document backend from a file path and taxonomy directory options', 'convert an XBRL instance document to a DoclingDocument with key-value pairs and hierarchy', 'test whether an XBRL document backend loaded a valid XBRL instance file', 'summarize the input formats supported by the XBRL document backend', 'run the XBRL backend unload method to close and release model resources']
```

Usage

```
{'create_xbrl_backend': 'create an XBRL document backend from a file path and taxonomy directory options', 'convert_xbrl_to_docling': 'convert an XBRL instance document to a DoclingDocument with key-value pairs and hierarchy', 'test_xbrl_backend_valid': 'test whether an XBRL document backend loaded a valid XBRL instance file', 'summarize_xbrl_supported_formats': 'summarize the input formats supported by the XBRL document backend', 'run_xbrl_backend_unload': 'run the XBRL backend unload method to close and release model resources'}
```

