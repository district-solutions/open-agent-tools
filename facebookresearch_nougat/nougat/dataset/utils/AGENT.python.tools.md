# Agent Python Tools

- repo: facebookresearch/nougat
- repo_uri: https://github.com/facebookresearch/nougat.git

## File: facebookresearch_nougat/nougat/dataset/utils/latex_conversion.py

Prompts

```
['normalize a TeX math expression by stripping delimiters, removing line breaks, replacing synonyms, and removing style commands', 'convert a Unicode string to LaTeX by encoding non-ASCII characters, handling umlauts, and replacing duplicate definitions', 'remove LaTeX style commands like displaystyle, scriptstyle, scriptscriptstyle, and textstyle from a string', 'replace interchangeable LaTeX commands with their canonical equivalents using a predefined synonym list', 'remove LaTeX comments and line breaks from a string by replacing them with spaces', 'extract text from each page of a PDF file using pdfminer and return a list of strings', 'extract paragraphs from a PDF file by splitting page text on double newlines', 'replace typographic ligatures like fi and fl with their plain text equivalents in a string', 'remove line-breaking hyphens from text by joining split words across consecutive lines', 'merge a hyphenated word split across two lines by removing the hyphen and concatenating', 'create a function that replaces linebreaks with spaces when there would be no difference in markdown format', 'test the remove_pretty_linebreaks function with a multiline string containing markdown formatting', 'refactor remove_pretty_linebreaks to also handle linebreaks before list markers and headers', 'review the remove_pretty_linebreaks regex pattern to ensure it correctly preserves intentional linebreaks', 'summarize how remove_pretty_linebreaks uses a negative lookbehind to avoid collapsing double linebreaks']
```

Usage

```
{'normalize_tex': 'normalize a TeX math expression by stripping delimiters, removing line breaks, replacing synonyms, and removing style commands', 'unicode_to_latex': 'convert a Unicode string to LaTeX by encoding non-ASCII characters, handling umlauts, and replacing duplicate definitions', 'remove_style': 'remove LaTeX style commands like displaystyle, scriptstyle, scriptscriptstyle, and textstyle from a string', 'replace_duplicate_definitions': 'replace interchangeable LaTeX commands with their canonical equivalents using a predefined synonym list', 'remove_line_breaks': 'remove LaTeX comments and line breaks from a string by replacing them with spaces'}
```

## File: facebookresearch_nougat/nougat/dataset/utils/pdf_text_extract.py

Prompts

```
['normalize a TeX math expression by stripping delimiters, removing line breaks, replacing synonyms, and removing style commands', 'convert a Unicode string to LaTeX by encoding non-ASCII characters, handling umlauts, and replacing duplicate definitions', 'remove LaTeX style commands like displaystyle, scriptstyle, scriptscriptstyle, and textstyle from a string', 'replace interchangeable LaTeX commands with their canonical equivalents using a predefined synonym list', 'remove LaTeX comments and line breaks from a string by replacing them with spaces', 'extract text from each page of a PDF file using pdfminer and return a list of strings', 'extract paragraphs from a PDF file by splitting page text on double newlines', 'replace typographic ligatures like fi and fl with their plain text equivalents in a string', 'remove line-breaking hyphens from text by joining split words across consecutive lines', 'merge a hyphenated word split across two lines by removing the hyphen and concatenating', 'create a function that replaces linebreaks with spaces when there would be no difference in markdown format', 'test the remove_pretty_linebreaks function with a multiline string containing markdown formatting', 'refactor remove_pretty_linebreaks to also handle linebreaks before list markers and headers', 'review the remove_pretty_linebreaks regex pattern to ensure it correctly preserves intentional linebreaks', 'summarize how remove_pretty_linebreaks uses a negative lookbehind to avoid collapsing double linebreaks']
```

Usage

```
{'extract_pdf_pages': 'extract text from each page of a PDF file using pdfminer and return a list of strings', 'extract_pdf_paragraphs': 'extract paragraphs from a PDF file by splitting page text on double newlines', 'replace_ligatures': 'replace typographic ligatures like fi and fl with their plain text equivalents in a string', 'remove_hyphens': 'remove line-breaking hyphens from text by joining split words across consecutive lines', 'dehyphenate_lines': 'merge a hyphenated word split across two lines by removing the hyphen and concatenating'}
```

## File: facebookresearch_nougat/nougat/dataset/utils/utils.py

Prompts

```
['normalize a TeX math expression by stripping delimiters, removing line breaks, replacing synonyms, and removing style commands', 'convert a Unicode string to LaTeX by encoding non-ASCII characters, handling umlauts, and replacing duplicate definitions', 'remove LaTeX style commands like displaystyle, scriptstyle, scriptscriptstyle, and textstyle from a string', 'replace interchangeable LaTeX commands with their canonical equivalents using a predefined synonym list', 'remove LaTeX comments and line breaks from a string by replacing them with spaces', 'extract text from each page of a PDF file using pdfminer and return a list of strings', 'extract paragraphs from a PDF file by splitting page text on double newlines', 'replace typographic ligatures like fi and fl with their plain text equivalents in a string', 'remove line-breaking hyphens from text by joining split words across consecutive lines', 'merge a hyphenated word split across two lines by removing the hyphen and concatenating', 'create a function that replaces linebreaks with spaces when there would be no difference in markdown format', 'test the remove_pretty_linebreaks function with a multiline string containing markdown formatting', 'refactor remove_pretty_linebreaks to also handle linebreaks before list markers and headers', 'review the remove_pretty_linebreaks regex pattern to ensure it correctly preserves intentional linebreaks', 'summarize how remove_pretty_linebreaks uses a negative lookbehind to avoid collapsing double linebreaks']
```

Usage

```
{'remove_pretty_linebreaks': 'create a function that replaces linebreaks with spaces when there would be no difference in markdown format', 'test_remove_pretty_linebreaks': 'test the remove_pretty_linebreaks function with a multiline string containing markdown formatting', 'refactor_remove_pretty_linebreaks': 'refactor remove_pretty_linebreaks to also handle linebreaks before list markers and headers', 'review_remove_pretty_linebreaks': 'review the remove_pretty_linebreaks regex pattern to ensure it correctly preserves intentional linebreaks', 'summarize_remove_pretty_linebreaks': 'summarize how remove_pretty_linebreaks uses a negative lookbehind to avoid collapsing double linebreaks'}
```

