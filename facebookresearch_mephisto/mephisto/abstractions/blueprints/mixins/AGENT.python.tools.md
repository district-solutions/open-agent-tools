# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/mixins/onboarding_required.py

Prompts

```
['initialize onboarding configuration for a task run with qualification names and shared state', 'validate onboarding data from an onboarding agent and return whether the worker passed qualification', 'get the failed qualification name by appending a suffix to the base qualification name', 'get the list of required qualifications for the onboarding mixin from blueprint args', 'clear onboarding qualifications by revoking both worker and crowd qualifications for a worker', 'initialize screening task configuration with qualification names and data factory for a Mephisto blueprint task run', 'create a wrapped validation function that grants or blocks worker qualifications based on screening unit submission results', 'get the next screening unit data dict from the screening data factory generator and track units launched', 'check if a Mephisto worker needs screening by verifying they lack the passed qualification name', 'validate screening task mixin arguments including qualification names, max screening units, and data factory requirements', 'create a gold factory function that distributes random gold units to workers from a list', 'check if a worker needs a gold unit based on completion stats and minimum golds', 'check if a worker qualifies to continue based on incorrect gold count and max allowed', 'use the UseGoldUnit blueprint mixin to inject gold units into worker task queues', 'create a validation function that updates worker qualifications when gold units are submitted']
```

Usage

```
{'init_onboarding_config': 'initialize onboarding configuration for a task run with qualification names and shared state', 'validate_onboarding': 'validate onboarding data from an onboarding agent and return whether the worker passed qualification', 'get_failed_qual': 'get the failed qualification name by appending a suffix to the base qualification name', 'get_mixin_qualifications': 'get the list of required qualifications for the onboarding mixin from blueprint args', 'clear_onboarding': 'clear onboarding qualifications by revoking both worker and crowd qualifications for a worker'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/mixins/screen_task_required.py

Prompts

```
['initialize onboarding configuration for a task run with qualification names and shared state', 'validate onboarding data from an onboarding agent and return whether the worker passed qualification', 'get the failed qualification name by appending a suffix to the base qualification name', 'get the list of required qualifications for the onboarding mixin from blueprint args', 'clear onboarding qualifications by revoking both worker and crowd qualifications for a worker', 'initialize screening task configuration with qualification names and data factory for a Mephisto blueprint task run', 'create a wrapped validation function that grants or blocks worker qualifications based on screening unit submission results', 'get the next screening unit data dict from the screening data factory generator and track units launched', 'check if a Mephisto worker needs screening by verifying they lack the passed qualification name', 'validate screening task mixin arguments including qualification names, max screening units, and data factory requirements', 'create a gold factory function that distributes random gold units to workers from a list', 'check if a worker needs a gold unit based on completion stats and minimum golds', 'check if a worker qualifies to continue based on incorrect gold count and max allowed', 'use the UseGoldUnit blueprint mixin to inject gold units into worker task queues', 'create a validation function that updates worker qualifications when gold units are submitted']
```

Usage

```
{'init_screening_config': 'initialize screening task configuration with qualification names and data factory for a Mephisto blueprint task run', 'create_validation_function': 'create a wrapped validation function that grants or blocks worker qualifications based on screening unit submission results', 'get_screening_unit_data': 'get the next screening unit data dict from the screening data factory generator and track units launched', 'worker_needs_screening': 'check if a Mephisto worker needs screening by verifying they lack the passed qualification name', 'assert_mixin_args': 'validate screening task mixin arguments including qualification names, max screening units, and data factory requirements'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/mixins/use_gold_unit.py

Prompts

```
['initialize onboarding configuration for a task run with qualification names and shared state', 'validate onboarding data from an onboarding agent and return whether the worker passed qualification', 'get the failed qualification name by appending a suffix to the base qualification name', 'get the list of required qualifications for the onboarding mixin from blueprint args', 'clear onboarding qualifications by revoking both worker and crowd qualifications for a worker', 'initialize screening task configuration with qualification names and data factory for a Mephisto blueprint task run', 'create a wrapped validation function that grants or blocks worker qualifications based on screening unit submission results', 'get the next screening unit data dict from the screening data factory generator and track units launched', 'check if a Mephisto worker needs screening by verifying they lack the passed qualification name', 'validate screening task mixin arguments including qualification names, max screening units, and data factory requirements', 'create a gold factory function that distributes random gold units to workers from a list', 'check if a worker needs a gold unit based on completion stats and minimum golds', 'check if a worker qualifies to continue based on incorrect gold count and max allowed', 'use the UseGoldUnit blueprint mixin to inject gold units into worker task queues', 'create a validation function that updates worker qualifications when gold units are submitted']
```

Usage

```
{'create_gold_factory': 'create a gold factory function that distributes random gold units to workers from a list', 'check_worker_needs_gold': 'check if a worker needs a gold unit based on completion stats and minimum golds', 'check_worker_qualifies': 'check if a worker qualifies to continue based on incorrect gold count and max allowed', 'use_gold_unit_mixin': 'use the UseGoldUnit blueprint mixin to inject gold units into worker task queues', 'create_gold_validation_function': 'create a validation function that updates worker qualifications when gold units are submitted'}
```

