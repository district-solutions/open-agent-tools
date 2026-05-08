# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/docs/source/conf.py

Prompts

```
['review the linkcode_resolve function that generates GitHub source links for Sphinx autodoc', 'summarize the linkcode_resolve function used by sphinx.ext.linkcode to resolve source URLs', 'refactor the linkcode_resolve function to use a different git library or URL format', 'review the autodoc_default_options dict that configures Sphinx autodoc member exclusion and ordering', 'review the extensions list that enables autodoc, githubpages, myst_parser, and linkcode', 'run the script to generate README docs for all Parlai agents into agent_refs directory', 'run write_all_agents to generate markdown docs for each Parlai agent module', 'run prepare_agent_readme to load an agent README and append its CLI argument options', 'run _make_argparse_table to build a reStructuredText table of CLI args for an agent class', 'review _make_argparse_table to understand how it extracts and formats ParlaiParser argument groups into markdown tables', 'run the generate_cli script to produce cli_usage.inc and cli_advanced.inc documentation files', "render a ParlAI script's CLI arguments as a markdown table with descriptions and defaults", 'setup the script registry and generate documentation for all registered ParlAI scripts', 'review the render_script function to understand how hidden and suppressed argparse actions are filtered', 'refactor render_script to customize how default values and recommended values are formatted in docs', 'run the generate_zoo_list script to produce the zoo_list.inc markdown documentation file', 'review the example_to_code function that formats example invocations and results into markdown code blocks', "review the model_text function that writes a single model's markdown documentation section to a file", 'refactor the example_to_code function to support additional code block language identifiers beyond none', 'summarize how the category_zoo_list dictionary groups model entries by their task category']
```

Usage

```
{'review_linkcode_resolve': 'review the linkcode_resolve function that generates GitHub source links for Sphinx autodoc', 'summarize_linkcode_resolve': 'summarize the linkcode_resolve function used by sphinx.ext.linkcode to resolve source URLs', 'refactor_linkcode_resolve': 'refactor the linkcode_resolve function to use a different git library or URL format', 'review_autodoc_default_options': 'review the autodoc_default_options dict that configures Sphinx autodoc member exclusion and ordering', 'review_sphinx_extensions': 'review the extensions list that enables autodoc, githubpages, myst_parser, and linkcode'}
```

## File: facebookresearch_parlai/docs/source/generate_agent_list.py

Prompts

```
['review the linkcode_resolve function that generates GitHub source links for Sphinx autodoc', 'summarize the linkcode_resolve function used by sphinx.ext.linkcode to resolve source URLs', 'refactor the linkcode_resolve function to use a different git library or URL format', 'review the autodoc_default_options dict that configures Sphinx autodoc member exclusion and ordering', 'review the extensions list that enables autodoc, githubpages, myst_parser, and linkcode', 'run the script to generate README docs for all Parlai agents into agent_refs directory', 'run write_all_agents to generate markdown docs for each Parlai agent module', 'run prepare_agent_readme to load an agent README and append its CLI argument options', 'run _make_argparse_table to build a reStructuredText table of CLI args for an agent class', 'review _make_argparse_table to understand how it extracts and formats ParlaiParser argument groups into markdown tables', 'run the generate_cli script to produce cli_usage.inc and cli_advanced.inc documentation files', "render a ParlAI script's CLI arguments as a markdown table with descriptions and defaults", 'setup the script registry and generate documentation for all registered ParlAI scripts', 'review the render_script function to understand how hidden and suppressed argparse actions are filtered', 'refactor render_script to customize how default values and recommended values are formatted in docs', 'run the generate_zoo_list script to produce the zoo_list.inc markdown documentation file', 'review the example_to_code function that formats example invocations and results into markdown code blocks', "review the model_text function that writes a single model's markdown documentation section to a file", 'refactor the example_to_code function to support additional code block language identifiers beyond none', 'summarize how the category_zoo_list dictionary groups model entries by their task category']
```

Usage

```
{'run_generate_agent_list': 'run the script to generate README docs for all Parlai agents into agent_refs directory', 'run_write_all_agents': 'run write_all_agents to generate markdown docs for each Parlai agent module', 'run_prepare_agent_readme': 'run prepare_agent_readme to load an agent README and append its CLI argument options', 'run_make_argparse_table': 'run _make_argparse_table to build a reStructuredText table of CLI args for an agent class', 'review_make_argparse_table': 'review _make_argparse_table to understand how it extracts and formats ParlaiParser argument groups into markdown tables'}
```

## File: facebookresearch_parlai/docs/source/generate_cli.py

Prompts

```
['review the linkcode_resolve function that generates GitHub source links for Sphinx autodoc', 'summarize the linkcode_resolve function used by sphinx.ext.linkcode to resolve source URLs', 'refactor the linkcode_resolve function to use a different git library or URL format', 'review the autodoc_default_options dict that configures Sphinx autodoc member exclusion and ordering', 'review the extensions list that enables autodoc, githubpages, myst_parser, and linkcode', 'run the script to generate README docs for all Parlai agents into agent_refs directory', 'run write_all_agents to generate markdown docs for each Parlai agent module', 'run prepare_agent_readme to load an agent README and append its CLI argument options', 'run _make_argparse_table to build a reStructuredText table of CLI args for an agent class', 'review _make_argparse_table to understand how it extracts and formats ParlaiParser argument groups into markdown tables', 'run the generate_cli script to produce cli_usage.inc and cli_advanced.inc documentation files', "render a ParlAI script's CLI arguments as a markdown table with descriptions and defaults", 'setup the script registry and generate documentation for all registered ParlAI scripts', 'review the render_script function to understand how hidden and suppressed argparse actions are filtered', 'refactor render_script to customize how default values and recommended values are formatted in docs', 'run the generate_zoo_list script to produce the zoo_list.inc markdown documentation file', 'review the example_to_code function that formats example invocations and results into markdown code blocks', "review the model_text function that writes a single model's markdown documentation section to a file", 'refactor the example_to_code function to support additional code block language identifiers beyond none', 'summarize how the category_zoo_list dictionary groups model entries by their task category']
```

Usage

```
{'run_generate_cli_docs': 'run the generate_cli script to produce cli_usage.inc and cli_advanced.inc documentation files', 'render_script_render_script': "render a ParlAI script's CLI arguments as a markdown table with descriptions and defaults", 'main_setup_and_generate': 'setup the script registry and generate documentation for all registered ParlAI scripts', 'review_render_script_filtering': 'review the render_script function to understand how hidden and suppressed argparse actions are filtered', 'refactor_render_script_defaults': 'refactor render_script to customize how default values and recommended values are formatted in docs'}
```

## File: facebookresearch_parlai/docs/source/generate_zoo_list.py

Prompts

```
['review the linkcode_resolve function that generates GitHub source links for Sphinx autodoc', 'summarize the linkcode_resolve function used by sphinx.ext.linkcode to resolve source URLs', 'refactor the linkcode_resolve function to use a different git library or URL format', 'review the autodoc_default_options dict that configures Sphinx autodoc member exclusion and ordering', 'review the extensions list that enables autodoc, githubpages, myst_parser, and linkcode', 'run the script to generate README docs for all Parlai agents into agent_refs directory', 'run write_all_agents to generate markdown docs for each Parlai agent module', 'run prepare_agent_readme to load an agent README and append its CLI argument options', 'run _make_argparse_table to build a reStructuredText table of CLI args for an agent class', 'review _make_argparse_table to understand how it extracts and formats ParlaiParser argument groups into markdown tables', 'run the generate_cli script to produce cli_usage.inc and cli_advanced.inc documentation files', "render a ParlAI script's CLI arguments as a markdown table with descriptions and defaults", 'setup the script registry and generate documentation for all registered ParlAI scripts', 'review the render_script function to understand how hidden and suppressed argparse actions are filtered', 'refactor render_script to customize how default values and recommended values are formatted in docs', 'run the generate_zoo_list script to produce the zoo_list.inc markdown documentation file', 'review the example_to_code function that formats example invocations and results into markdown code blocks', "review the model_text function that writes a single model's markdown documentation section to a file", 'refactor the example_to_code function to support additional code block language identifiers beyond none', 'summarize how the category_zoo_list dictionary groups model entries by their task category']
```

Usage

```
{'run_generate_zoo_list': 'run the generate_zoo_list script to produce the zoo_list.inc markdown documentation file', 'review_example_to_code': 'review the example_to_code function that formats example invocations and results into markdown code blocks', 'review_model_text': "review the model_text function that writes a single model's markdown documentation section to a file", 'refactor_example_to_code': 'refactor the example_to_code function to support additional code block language identifiers beyond none', 'summarize_category_zoo_list': 'summarize how the category_zoo_list dictionary groups model entries by their task category'}
```

