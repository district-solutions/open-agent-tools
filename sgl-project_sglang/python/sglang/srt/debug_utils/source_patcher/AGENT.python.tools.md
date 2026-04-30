# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/debug_utils/source_patcher/code_patcher.py

Prompts

```
['apply patches from a YAML config string with optional extra imports', 'create a CodePatcher context manager that patches functions on enter and restores on exit', 'patch a function by modifying its source and replacing its code object', 'test that CodePatcher restores original function code after exiting the context', 'review the patch_function edits list to modify function source text safely', 'apply edits to source text by replacing matched lines with replacement text', 'apply edits to source text by prepending lines before matched text', 'apply edits to source text by appending lines after matched text', 'find the start index of matched lines in source lines with strip comparison', 'realign replacement lines to the original indentation level of matched text', 'create an EditSpec that replaces matched source text with new content', 'create an EditSpec that prepends lines before matched source text', 'create a PatchSpec with target file path, list of edits, and optional preamble', 'create a PatchConfig containing a list of PatchSpec objects for source patching', 'build a PatchState from a target function and its original bytecode to restore it later']
```

Usage

```
{'apply_patches_from_config': 'apply patches from a YAML config string with optional extra imports', 'create_CodePatcher_context_manager': 'create a CodePatcher context manager that patches functions on enter and restores on exit', 'patch_function_source': 'patch a function by modifying its source and replacing its code object', 'test_CodePatcher_restore': 'test that CodePatcher restores original function code after exiting the context', 'review_patch_function_edits': 'review the patch_function edits list to modify function source text safely'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/source_patcher/source_editor.py

Prompts

```
['apply patches from a YAML config string with optional extra imports', 'create a CodePatcher context manager that patches functions on enter and restores on exit', 'patch a function by modifying its source and replacing its code object', 'test that CodePatcher restores original function code after exiting the context', 'review the patch_function edits list to modify function source text safely', 'apply edits to source text by replacing matched lines with replacement text', 'apply edits to source text by prepending lines before matched text', 'apply edits to source text by appending lines after matched text', 'find the start index of matched lines in source lines with strip comparison', 'realign replacement lines to the original indentation level of matched text', 'create an EditSpec that replaces matched source text with new content', 'create an EditSpec that prepends lines before matched source text', 'create a PatchSpec with target file path, list of edits, and optional preamble', 'create a PatchConfig containing a list of PatchSpec objects for source patching', 'build a PatchState from a target function and its original bytecode to restore it later']
```

Usage

```
{'apply_edits_source_replacement': 'apply edits to source text by replacing matched lines with replacement text', 'apply_edits_source_prepend': 'apply edits to source text by prepending lines before matched text', 'apply_edits_source_append': 'apply edits to source text by appending lines after matched text', 'find_match_source_lines': 'find the start index of matched lines in source lines with strip comparison', 'realign_replacement_lines': 'realign replacement lines to the original indentation level of matched text'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/source_patcher/types.py

Prompts

```
['apply patches from a YAML config string with optional extra imports', 'create a CodePatcher context manager that patches functions on enter and restores on exit', 'patch a function by modifying its source and replacing its code object', 'test that CodePatcher restores original function code after exiting the context', 'review the patch_function edits list to modify function source text safely', 'apply edits to source text by replacing matched lines with replacement text', 'apply edits to source text by prepending lines before matched text', 'apply edits to source text by appending lines after matched text', 'find the start index of matched lines in source lines with strip comparison', 'realign replacement lines to the original indentation level of matched text', 'create an EditSpec that replaces matched source text with new content', 'create an EditSpec that prepends lines before matched source text', 'create a PatchSpec with target file path, list of edits, and optional preamble', 'create a PatchConfig containing a list of PatchSpec objects for source patching', 'build a PatchState from a target function and its original bytecode to restore it later']
```

Usage

```
{'create_edit_spec_replace': 'create an EditSpec that replaces matched source text with new content', 'create_edit_spec_prepend': 'create an EditSpec that prepends lines before matched source text', 'create_patch_spec': 'create a PatchSpec with target file path, list of edits, and optional preamble', 'create_patch_config': 'create a PatchConfig containing a list of PatchSpec objects for source patching', 'build_patch_state_restore': 'build a PatchState from a target function and its original bytecode to restore it later'}
```

