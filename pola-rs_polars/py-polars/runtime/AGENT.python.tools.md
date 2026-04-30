# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/runtime/template.py

Prompts

```
['run the template.py CLI to generate polars-runtime-32, polars-runtime-64, and polars-runtime-compat directories', 'build polars-runtime directories by copying templates and substituting runtime suffixes into Cargo.toml and pyproject.toml', 'test the template function to replace {{%RT_SUFFIX%}} placeholders with runtime suffixes in a string', 'refactor the template function to support additional placeholder substitutions beyond {{%RT_SUFFIX%}}', 'review the template.py CLI script that generates runtime packages for 32-bit, 64-bit, and compat builds']
```

Usage

```
{'run_template_cli': 'run the template.py CLI to generate polars-runtime-32, polars-runtime-64, and polars-runtime-compat directories', 'build_runtime_directories': 'build polars-runtime directories by copying templates and substituting runtime suffixes into Cargo.toml and pyproject.toml', 'test_template_function': 'test the template function to replace {{%RT_SUFFIX%}} placeholders with runtime suffixes in a string', 'refactor_template_substitution': 'refactor the template function to support additional placeholder substitutions beyond {{%RT_SUFFIX%}}', 'review_template_cli': 'review the template.py CLI script that generates runtime packages for 32-bit, 64-bit, and compat builds'}
```

