# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/mrp/tests/cmd/test_autocomplete.py

Prompts

```
['test the union function that merges completion suggestions from multiple autocomplete sources into one sorted list', 'test the intersection function that returns only completion suggestions common across multiple autocomplete sources', 'test the conditional function that returns different completion suggestions based on a predicate checking CLI context params', 'test the defined_processes autocomplete that suggests process names from process_def.defined_processes matching the incomplete input', 'test the running_processes autocomplete that suggests only STARTED process names from the current system state', 'test that mrp.cmd.down() tells all defined processes to go down', 'test that mrp.cmd.down(local=True) stops only locally defined processes', "test that mrp.cmd.down('proc') stops a specific named process", "test that mrp.cmd.down('proc', wait=False) returns immediately without waiting", "test that mrp.cmd.wait('proc') blocks until the process reaches State.STOPPED"]
```

Usage

```
{'test_autocomplete_union': 'test the union function that merges completion suggestions from multiple autocomplete sources into one sorted list', 'test_autocomplete_intersection': 'test the intersection function that returns only completion suggestions common across multiple autocomplete sources', 'test_autocomplete_conditional': 'test the conditional function that returns different completion suggestions based on a predicate checking CLI context params', 'test_autocomplete_defined_processes': 'test the defined_processes autocomplete that suggests process names from process_def.defined_processes matching the incomplete input', 'test_autocomplete_running_processes': 'test the running_processes autocomplete that suggests only STARTED process names from the current system state'}
```

## File: facebookresearch_fairo/mrp/tests/cmd/test_down.py

Prompts

```
['test the union function that merges completion suggestions from multiple autocomplete sources into one sorted list', 'test the intersection function that returns only completion suggestions common across multiple autocomplete sources', 'test the conditional function that returns different completion suggestions based on a predicate checking CLI context params', 'test the defined_processes autocomplete that suggests process names from process_def.defined_processes matching the incomplete input', 'test the running_processes autocomplete that suggests only STARTED process names from the current system state', 'test that mrp.cmd.down() tells all defined processes to go down', 'test that mrp.cmd.down(local=True) stops only locally defined processes', "test that mrp.cmd.down('proc') stops a specific named process", "test that mrp.cmd.down('proc', wait=False) returns immediately without waiting", "test that mrp.cmd.wait('proc') blocks until the process reaches State.STOPPED"]
```

Usage

```
{'test_mrp_cmd_down_all_processes': 'test that mrp.cmd.down() tells all defined processes to go down', 'test_mrp_cmd_down_local_only': 'test that mrp.cmd.down(local=True) stops only locally defined processes', 'test_mrp_cmd_down_specific_process': "test that mrp.cmd.down('proc') stops a specific named process", 'test_mrp_cmd_down_no_wait': "test that mrp.cmd.down('proc', wait=False) returns immediately without waiting", 'test_mrp_cmd_wait_for_stop': "test that mrp.cmd.wait('proc') blocks until the process reaches State.STOPPED"}
```

