# Agent Python Tools

- repo: google-deepmind/formal-conjectures
- repo_uri: https://github.com/google-deepmind/formal-conjectures

## File: google-deepmind_formal-conjectures/site/extract_verso_fragments.py

Prompts

```
['run the script to extract module docstrings and constant links from Verso literate HTML files into a JSON file', 'create a function that walks a directory tree and yields all index.html file paths', 'build a parser that extracts module docstrings and constant binding links from a single Verso HTML file', 'review the extract_from_html function to understand how it matches docstrings to constant definitions using sibling traversal', 'summarize the main function which scans HTML files and writes moduleDocs and constLinks to a JSON output file', 'run the script to post-process Verso literate HTML output and fix deployment issues in a directory', 'inject KaTeX CSS and JS into a Verso HTML file to enable LaTeX rendering in docstrings', 'create stub JavaScript files for missing Verso search infrastructure in the -verso-search directory', 'fix domain-mappers.js by removing export statements that cause syntax errors when loaded without type module', 'walk a directory tree and inject KaTeX into all index.html files that are missing it']
```

Usage

```
{'extract_verso_fragments': 'run the script to extract module docstrings and constant links from Verso literate HTML files into a JSON file', 'walk_html_files': 'create a function that walks a directory tree and yields all index.html file paths', 'extract_from_html': 'build a parser that extracts module docstrings and constant binding links from a single Verso HTML file', 'review_extract_from_html': 'review the extract_from_html function to understand how it matches docstrings to constant definitions using sibling traversal', 'summarize_main': 'summarize the main function which scans HTML files and writes moduleDocs and constLinks to a JSON output file'}
```

## File: google-deepmind_formal-conjectures/site/fix_literate_html.py

Prompts

```
['run the script to extract module docstrings and constant links from Verso literate HTML files into a JSON file', 'create a function that walks a directory tree and yields all index.html file paths', 'build a parser that extracts module docstrings and constant binding links from a single Verso HTML file', 'review the extract_from_html function to understand how it matches docstrings to constant definitions using sibling traversal', 'summarize the main function which scans HTML files and writes moduleDocs and constLinks to a JSON output file', 'run the script to post-process Verso literate HTML output and fix deployment issues in a directory', 'inject KaTeX CSS and JS into a Verso HTML file to enable LaTeX rendering in docstrings', 'create stub JavaScript files for missing Verso search infrastructure in the -verso-search directory', 'fix domain-mappers.js by removing export statements that cause syntax errors when loaded without type module', 'walk a directory tree and inject KaTeX into all index.html files that are missing it']
```

Usage

```
{'run_fix_literate_html': 'run the script to post-process Verso literate HTML output and fix deployment issues in a directory', 'inject_katex_into_html': 'inject KaTeX CSS and JS into a Verso HTML file to enable LaTeX rendering in docstrings', 'create_stub_js_files': 'create stub JavaScript files for missing Verso search infrastructure in the -verso-search directory', 'fix_domain_mappers_js': 'fix domain-mappers.js by removing export statements that cause syntax errors when loaded without type module', 'fix_all_html_files': 'walk a directory tree and inject KaTeX into all index.html files that are missing it'}
```

