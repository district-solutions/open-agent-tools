# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/models/stages/code_formula/code_formula_model.py

Prompts

```
['create CodeFormulaModelOptions config with code and formula enrichment enabled', 'create CodeFormulaModel with enabled flag, artifacts path, options, and accelerator options', 'test CodeFormulaModel.is_processable to check if a document element can be processed', 'run CodeFormulaModel.__call__ to process a batch of code and formula elements and enrich them', 'summarize CodeFormulaModel._extract_code_language to parse language tags from code output strings', 'create a CodeFormulaVlmModel stage with options and accelerator for code and formula extraction', 'run the model on a batch of code and formula elements to extract text content', 'refactor the code language extraction to parse language tags from model output', 'summarize the post-processing that removes unwanted tokens from model outputs']
```

Usage

```
{'create_CodeFormulaModelOptions': 'create CodeFormulaModelOptions config with code and formula enrichment enabled', 'create_CodeFormulaModel': 'create CodeFormulaModel with enabled flag, artifacts path, options, and accelerator options', 'test_is_processable': 'test CodeFormulaModel.is_processable to check if a document element can be processed', 'run_CodeFormulaModel_call': 'run CodeFormulaModel.__call__ to process a batch of code and formula elements and enrich them', 'summarize_extract_code_language': 'summarize CodeFormulaModel._extract_code_language to parse language tags from code output strings'}
```

## File: docling-project_docling/docling/models/stages/code_formula/code_formula_vlm_model.py

Prompts

```
['create CodeFormulaModelOptions config with code and formula enrichment enabled', 'create CodeFormulaModel with enabled flag, artifacts path, options, and accelerator options', 'test CodeFormulaModel.is_processable to check if a document element can be processed', 'run CodeFormulaModel.__call__ to process a batch of code and formula elements and enrich them', 'summarize CodeFormulaModel._extract_code_language to parse language tags from code output strings', 'create a CodeFormulaVlmModel stage with options and accelerator for code and formula extraction', 'run the model on a batch of code and formula elements to extract text content', 'refactor the code language extraction to parse language tags from model output', 'summarize the post-processing that removes unwanted tokens from model outputs']
```

Usage

```
{'create_CodeFormulaVlmModel': 'create a CodeFormulaVlmModel stage with options and accelerator for code and formula extraction', 'test_is_processable': 'test if a document element is a code block or formula that can be processed', 'run_CodeFormulaVlmModel_call': 'run the model on a batch of code and formula elements to extract text content', 'refactor__extract_code_language': 'refactor the code language extraction to parse language tags from model output', 'summarize__post_process': 'summarize the post-processing that removes unwanted tokens from model outputs'}
```

