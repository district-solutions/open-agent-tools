# Agent Python Tools

- repo: huggingface/audio-transformers-course
- repo_uri: https://github.com/huggingface/audio-transformers-course

## File: huggingface_audio-transformers-course/utils/code_formatter.py

Prompts

```
['format all python code blocks in a markdown mdx file using black with line length 90', 'check if python code blocks in an mdx file are properly formatted without modifying the file', 'format all mdx files in the chapters directory by applying black to embedded python code blocks', 'check all mdx files in the chapters directory for proper python code formatting and report failures', 'run the code formatter cli with check only mode to validate formatting across all chapter mdx files', 'build a Jupyter notebook from an MDX file with framework-specific code cells and installation instructions', 'extract Python code and output cells from MDX content using fenced code block markers', 'read an MDX file and split content into separate PyTorch and TensorFlow versions using framework conditionals', 'convert a code cell or code-output tuple into a proper nbformat notebook cell with outputs', 'create Jupyter notebooks for all course sections in a given language from MDX source files', 'run the translation validator to check missing sections for a given language', 'run load_sections to extract section names from a language toctree YAML file', 'review the load_sections function that parses _toctree.yml and returns sorted section names', 'refactor the translation validator to support additional comparison languages beyond English', 'test the translation validation script with a specific language code via the CLI']
```

Usage

```
{'format_python_code_blocks_in_mdx': 'format all python code blocks in a markdown mdx file using black with line length 90', 'check_code_formatting_in_mdx': 'check if python code blocks in an mdx file are properly formatted without modifying the file', 'format_all_chapter_files': 'format all mdx files in the chapters directory by applying black to embedded python code blocks', 'check_all_chapter_files_formatting': 'check all mdx files in the chapters directory for proper python code formatting and report failures', 'run_code_formatter_cli': 'run the code formatter cli with check only mode to validate formatting across all chapter mdx files'}
```

## File: huggingface_audio-transformers-course/utils/generate_notebooks.py

Prompts

```
['format all python code blocks in a markdown mdx file using black with line length 90', 'check if python code blocks in an mdx file are properly formatted without modifying the file', 'format all mdx files in the chapters directory by applying black to embedded python code blocks', 'check all mdx files in the chapters directory for proper python code formatting and report failures', 'run the code formatter cli with check only mode to validate formatting across all chapter mdx files', 'build a Jupyter notebook from an MDX file with framework-specific code cells and installation instructions', 'extract Python code and output cells from MDX content using fenced code block markers', 'read an MDX file and split content into separate PyTorch and TensorFlow versions using framework conditionals', 'convert a code cell or code-output tuple into a proper nbformat notebook cell with outputs', 'create Jupyter notebooks for all course sections in a given language from MDX source files', 'run the translation validator to check missing sections for a given language', 'run load_sections to extract section names from a language toctree YAML file', 'review the load_sections function that parses _toctree.yml and returns sorted section names', 'refactor the translation validator to support additional comparison languages beyond English', 'test the translation validation script with a specific language code via the CLI']
```

Usage

```
{'build_notebook_from_mdx': 'build a Jupyter notebook from an MDX file with framework-specific code cells and installation instructions', 'extract_cells_from_content': 'extract Python code and output cells from MDX content using fenced code block markers', 'read_and_split_frameworks': 'read an MDX file and split content into separate PyTorch and TensorFlow versions using framework conditionals', 'convert_to_nb_cell': 'convert a code cell or code-output tuple into a proper nbformat notebook cell with outputs', 'create_notebooks_for_language': 'create Jupyter notebooks for all course sections in a given language from MDX source files'}
```

## File: huggingface_audio-transformers-course/utils/validate_translation.py

Prompts

```
['format all python code blocks in a markdown mdx file using black with line length 90', 'check if python code blocks in an mdx file are properly formatted without modifying the file', 'format all mdx files in the chapters directory by applying black to embedded python code blocks', 'check all mdx files in the chapters directory for proper python code formatting and report failures', 'run the code formatter cli with check only mode to validate formatting across all chapter mdx files', 'build a Jupyter notebook from an MDX file with framework-specific code cells and installation instructions', 'extract Python code and output cells from MDX content using fenced code block markers', 'read an MDX file and split content into separate PyTorch and TensorFlow versions using framework conditionals', 'convert a code cell or code-output tuple into a proper nbformat notebook cell with outputs', 'create Jupyter notebooks for all course sections in a given language from MDX source files', 'run the translation validator to check missing sections for a given language', 'run load_sections to extract section names from a language toctree YAML file', 'review the load_sections function that parses _toctree.yml and returns sorted section names', 'refactor the translation validator to support additional comparison languages beyond English', 'test the translation validation script with a specific language code via the CLI']
```

Usage

```
{'run_validate_translation': 'run the translation validator to check missing sections for a given language', 'run_load_sections': 'run load_sections to extract section names from a language toctree YAML file', 'review_load_sections': 'review the load_sections function that parses _toctree.yml and returns sorted section names', 'refactor_validate_translation': 'refactor the translation validator to support additional comparison languages beyond English', 'test_validate_translation': 'test the translation validation script with a specific language code via the CLI'}
```

