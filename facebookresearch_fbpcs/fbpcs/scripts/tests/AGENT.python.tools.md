# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/scripts/tests/test_gen_config.py

Prompts

```
['test the prompt function to interactively request config key values with optional replacement defaults', 'test build_replacements_from_config to extract leaf node values from a nested config dictionary', 'test update_dict to recursively replace placeholder values in a nested dictionary with user input', 'test gen_config to load a YAML config, replace placeholders, and write the updated config', 'test the TestGenConfig unittest class covering prompt, build_replacements_from_config, update_dict, and gen_config functions', 'generate fake CSV data for testing MPC by running the CLI tool with output path and options', 'test the adjusted purchase rate calculation for test and control users with incrementality bounds', 'test the faked data generation function with various opportunity, test, and purchase rate combinations', 'test the line generation function that merges input overrides with randomly generated fake data', 'test the CSV generation function with input files, from_header, and num_records arguments', 'test gen_ids_from_spine with a 100 percent keep rate to verify all IDs are written', 'test gen_ids_from_spine with a 0 percent keep rate to verify no IDs are written', 'test gen_ids_from_spine using mock_open to verify file read and write calls', 'test gen_ids_from_spine by asserting the correct write calls were made to the output file', 'test gen_ids_from_spine by asserting no write calls were made when keep rate is zero']
```

Usage

```
{'test_prompt': 'test the prompt function to interactively request config key values with optional replacement defaults', 'test_build_replacements_from_config': 'test build_replacements_from_config to extract leaf node values from a nested config dictionary', 'test_update_dict': 'test update_dict to recursively replace placeholder values in a nested dictionary with user input', 'test_gen_config': 'test gen_config to load a YAML config, replace placeholders, and write the updated config', 'test_TestGenConfig': 'test the TestGenConfig unittest class covering prompt, build_replacements_from_config, update_dict, and gen_config functions'}
```

## File: facebookresearch_fbpcs/fbpcs/scripts/tests/test_gen_fake_data.py

Prompts

```
['test the prompt function to interactively request config key values with optional replacement defaults', 'test build_replacements_from_config to extract leaf node values from a nested config dictionary', 'test update_dict to recursively replace placeholder values in a nested dictionary with user input', 'test gen_config to load a YAML config, replace placeholders, and write the updated config', 'test the TestGenConfig unittest class covering prompt, build_replacements_from_config, update_dict, and gen_config functions', 'generate fake CSV data for testing MPC by running the CLI tool with output path and options', 'test the adjusted purchase rate calculation for test and control users with incrementality bounds', 'test the faked data generation function with various opportunity, test, and purchase rate combinations', 'test the line generation function that merges input overrides with randomly generated fake data', 'test the CSV generation function with input files, from_header, and num_records arguments', 'test gen_ids_from_spine with a 100 percent keep rate to verify all IDs are written', 'test gen_ids_from_spine with a 0 percent keep rate to verify no IDs are written', 'test gen_ids_from_spine using mock_open to verify file read and write calls', 'test gen_ids_from_spine by asserting the correct write calls were made to the output file', 'test gen_ids_from_spine by asserting no write calls were made when keep rate is zero']
```

Usage

```
{'gen_fake_data_main': 'generate fake CSV data for testing MPC by running the CLI tool with output path and options', 'test_gen_adjusted_purchase_rate': 'test the adjusted purchase rate calculation for test and control users with incrementality bounds', 'test_faked_data': 'test the faked data generation function with various opportunity, test, and purchase rate combinations', 'test_generate_line': 'test the line generation function that merges input overrides with randomly generated fake data', 'test_make_input_csv': 'test the CSV generation function with input files, from_header, and num_records arguments'}
```

## File: facebookresearch_fbpcs/fbpcs/scripts/tests/test_gen_ids_from_spine.py

Prompts

```
['test the prompt function to interactively request config key values with optional replacement defaults', 'test build_replacements_from_config to extract leaf node values from a nested config dictionary', 'test update_dict to recursively replace placeholder values in a nested dictionary with user input', 'test gen_config to load a YAML config, replace placeholders, and write the updated config', 'test the TestGenConfig unittest class covering prompt, build_replacements_from_config, update_dict, and gen_config functions', 'generate fake CSV data for testing MPC by running the CLI tool with output path and options', 'test the adjusted purchase rate calculation for test and control users with incrementality bounds', 'test the faked data generation function with various opportunity, test, and purchase rate combinations', 'test the line generation function that merges input overrides with randomly generated fake data', 'test the CSV generation function with input files, from_header, and num_records arguments', 'test gen_ids_from_spine with a 100 percent keep rate to verify all IDs are written', 'test gen_ids_from_spine with a 0 percent keep rate to verify no IDs are written', 'test gen_ids_from_spine using mock_open to verify file read and write calls', 'test gen_ids_from_spine by asserting the correct write calls were made to the output file', 'test gen_ids_from_spine by asserting no write calls were made when keep rate is zero']
```

Usage

```
{'test_gen_ids_from_spine_100_percent': 'test gen_ids_from_spine with a 100 percent keep rate to verify all IDs are written', 'test_gen_ids_from_spine_0_percent': 'test gen_ids_from_spine with a 0 percent keep rate to verify no IDs are written', 'test_gen_ids_from_spine_mock_open': 'test gen_ids_from_spine using mock_open to verify file read and write calls', 'test_gen_ids_from_spine_assert_write_calls': 'test gen_ids_from_spine by asserting the correct write calls were made to the output file', 'test_gen_ids_from_spine_assert_not_in': 'test gen_ids_from_spine by asserting no write calls were made when keep rate is zero'}
```

