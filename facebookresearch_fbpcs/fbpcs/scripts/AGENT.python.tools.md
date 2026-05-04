# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/scripts/gen_config.py

Prompts

```
['run the gen_config CLI tool to generate a config.yml file by replacing TODO placeholders interactively', 'run gen_config with the --from flag to copy values from an existing config into a new one', 'run gen_config with --accept_all to skip re-prompting when a replacement value already exists', 'run gen_config with a new output path to write the generated config to a separate file', 'run gen_config with --replace to specify a custom placeholder key instead of the default TODO', 'run gen_fake_data to generate fake MPC test data CSV from a header string with N records', 'run gen_fake_data to transform an input CSV into fake MPC test data with configurable rates', 'run gen_fake_data with a custom incrementality rate to simulate ad lift in test vs control groups', 'run gen_fake_data with the md5_id flag to generate hashed IDs instead of integer row numbers', 'test the _faked_data function to verify it generates correct random opportunity, test, and purchase flags', 'run the CLI tool to generate a list of IDs from a spine file with sampling', 'run the main entry point that validates CLI args and generates sampled IDs from a spine', 'test the gen_ids_from_spine function to verify it samples lines from a spine file at the given keep rate', 'refactor gen_ids_from_spine to support parallel processing of large spine files', 'review the main function and its docopt-based CLI argument parsing and schema validation']
```

Usage

```
{'run_gen_config_cli': 'run the gen_config CLI tool to generate a config.yml file by replacing TODO placeholders interactively', 'run_gen_config_from_template': 'run gen_config with the --from flag to copy values from an existing config into a new one', 'run_gen_config_accept_all': 'run gen_config with --accept_all to skip re-prompting when a replacement value already exists', 'run_gen_config_output_path': 'run gen_config with a new output path to write the generated config to a separate file', 'run_gen_config_custom_replace': 'run gen_config with --replace to specify a custom placeholder key instead of the default TODO'}
```

## File: facebookresearch_fbpcs/fbpcs/scripts/gen_fake_data.py

Prompts

```
['run the gen_config CLI tool to generate a config.yml file by replacing TODO placeholders interactively', 'run gen_config with the --from flag to copy values from an existing config into a new one', 'run gen_config with --accept_all to skip re-prompting when a replacement value already exists', 'run gen_config with a new output path to write the generated config to a separate file', 'run gen_config with --replace to specify a custom placeholder key instead of the default TODO', 'run gen_fake_data to generate fake MPC test data CSV from a header string with N records', 'run gen_fake_data to transform an input CSV into fake MPC test data with configurable rates', 'run gen_fake_data with a custom incrementality rate to simulate ad lift in test vs control groups', 'run gen_fake_data with the md5_id flag to generate hashed IDs instead of integer row numbers', 'test the _faked_data function to verify it generates correct random opportunity, test, and purchase flags', 'run the CLI tool to generate a list of IDs from a spine file with sampling', 'run the main entry point that validates CLI args and generates sampled IDs from a spine', 'test the gen_ids_from_spine function to verify it samples lines from a spine file at the given keep rate', 'refactor gen_ids_from_spine to support parallel processing of large spine files', 'review the main function and its docopt-based CLI argument parsing and schema validation']
```

Usage

```
{'run_gen_fake_data_from_header': 'run gen_fake_data to generate fake MPC test data CSV from a header string with N records', 'run_gen_fake_data_from_input': 'run gen_fake_data to transform an input CSV into fake MPC test data with configurable rates', 'run_gen_fake_data_with_incrementality': 'run gen_fake_data with a custom incrementality rate to simulate ad lift in test vs control groups', 'run_gen_fake_data_md5_ids': 'run gen_fake_data with the md5_id flag to generate hashed IDs instead of integer row numbers', 'test_faked_data_function': 'test the _faked_data function to verify it generates correct random opportunity, test, and purchase flags'}
```

## File: facebookresearch_fbpcs/fbpcs/scripts/gen_ids_from_spine.py

Prompts

```
['run the gen_config CLI tool to generate a config.yml file by replacing TODO placeholders interactively', 'run gen_config with the --from flag to copy values from an existing config into a new one', 'run gen_config with --accept_all to skip re-prompting when a replacement value already exists', 'run gen_config with a new output path to write the generated config to a separate file', 'run gen_config with --replace to specify a custom placeholder key instead of the default TODO', 'run gen_fake_data to generate fake MPC test data CSV from a header string with N records', 'run gen_fake_data to transform an input CSV into fake MPC test data with configurable rates', 'run gen_fake_data with a custom incrementality rate to simulate ad lift in test vs control groups', 'run gen_fake_data with the md5_id flag to generate hashed IDs instead of integer row numbers', 'test the _faked_data function to verify it generates correct random opportunity, test, and purchase flags', 'run the CLI tool to generate a list of IDs from a spine file with sampling', 'run the main entry point that validates CLI args and generates sampled IDs from a spine', 'test the gen_ids_from_spine function to verify it samples lines from a spine file at the given keep rate', 'refactor gen_ids_from_spine to support parallel processing of large spine files', 'review the main function and its docopt-based CLI argument parsing and schema validation']
```

Usage

```
{'run_gen_ids_from_spine': 'run the CLI tool to generate a list of IDs from a spine file with sampling', 'run_main': 'run the main entry point that validates CLI args and generates sampled IDs from a spine', 'test_gen_ids_from_spine': 'test the gen_ids_from_spine function to verify it samples lines from a spine file at the given keep rate', 'refactor_gen_ids_from_spine': 'refactor gen_ids_from_spine to support parallel processing of large spine files', 'review_main': 'review the main function and its docopt-based CLI argument parsing and schema validation'}
```

