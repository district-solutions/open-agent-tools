# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/environment/engine.py

Prompts

```
['implement a concrete Engine subclass and call run_loop to simulate a multi-entity game', 'parse a JSON or legacy-format action spec string into an ActionSpec object', 'convert an ActionSpec object to its JSON string representation', 'parse a legacy-format action spec string with free or choice types into an ActionSpec', 'create a concrete subclass of Engine implementing make_observation next_acting resolve terminate and run_loop', 'test the engine action_spec_parser by parsing a JSON string into an ActionSpec with call_to_action and output_type', 'test the engine action_spec_to_string and action_spec_parser roundtrip serialization for free, choice, and skip output types', 'test the engine action_spec_to_string function outputs valid JSON with correct call_to_action and output_type fields', 'parse a JSON string containing call_to_action, output_type, options, and tag into an ActionSpec object', 'serialize an ActionSpec object with call_to_action and output_type into a JSON string representation', 'create a StepController instance to manage simulation play pause and step execution', 'build a StepData dataclass to capture step number acting entity action and logs', 'run the StepController play method to resume continuous simulation execution', 'test the StepController step method to advance simulation by one step then pause', 'review the StepController wait_for_step_permission method that blocks until play step or stop is called']
```

Usage

```
{'run_engine_loop': 'implement a concrete Engine subclass and call run_loop to simulate a multi-entity game', 'parse_action_spec': 'parse a JSON or legacy-format action spec string into an ActionSpec object', 'serialize_action_spec': 'convert an ActionSpec object to its JSON string representation', 'parse_legacy_action_spec': 'parse a legacy-format action spec string with free or choice types into an ActionSpec', 'create_engine_subclass': 'create a concrete subclass of Engine implementing make_observation next_acting resolve terminate and run_loop'}
```

## File: google-deepmind_concordia/concordia/environment/engine_test.py

Prompts

```
['implement a concrete Engine subclass and call run_loop to simulate a multi-entity game', 'parse a JSON or legacy-format action spec string into an ActionSpec object', 'convert an ActionSpec object to its JSON string representation', 'parse a legacy-format action spec string with free or choice types into an ActionSpec', 'create a concrete subclass of Engine implementing make_observation next_acting resolve terminate and run_loop', 'test the engine action_spec_parser by parsing a JSON string into an ActionSpec with call_to_action and output_type', 'test the engine action_spec_to_string and action_spec_parser roundtrip serialization for free, choice, and skip output types', 'test the engine action_spec_to_string function outputs valid JSON with correct call_to_action and output_type fields', 'parse a JSON string containing call_to_action, output_type, options, and tag into an ActionSpec object', 'serialize an ActionSpec object with call_to_action and output_type into a JSON string representation', 'create a StepController instance to manage simulation play pause and step execution', 'build a StepData dataclass to capture step number acting entity action and logs', 'run the StepController play method to resume continuous simulation execution', 'test the StepController step method to advance simulation by one step then pause', 'review the StepController wait_for_step_permission method that blocks until play step or stop is called']
```

Usage

```
{'test_action_spec_parser_json': 'test the engine action_spec_parser by parsing a JSON string into an ActionSpec with call_to_action and output_type', 'test_action_spec_roundtrip': 'test the engine action_spec_to_string and action_spec_parser roundtrip serialization for free, choice, and skip output types', 'test_action_spec_json_output': 'test the engine action_spec_to_string function outputs valid JSON with correct call_to_action and output_type fields', 'parse_action_spec_from_json': 'parse a JSON string containing call_to_action, output_type, options, and tag into an ActionSpec object', 'serialize_action_spec_to_json': 'serialize an ActionSpec object with call_to_action and output_type into a JSON string representation'}
```

## File: google-deepmind_concordia/concordia/environment/step_controller.py

Prompts

```
['implement a concrete Engine subclass and call run_loop to simulate a multi-entity game', 'parse a JSON or legacy-format action spec string into an ActionSpec object', 'convert an ActionSpec object to its JSON string representation', 'parse a legacy-format action spec string with free or choice types into an ActionSpec', 'create a concrete subclass of Engine implementing make_observation next_acting resolve terminate and run_loop', 'test the engine action_spec_parser by parsing a JSON string into an ActionSpec with call_to_action and output_type', 'test the engine action_spec_to_string and action_spec_parser roundtrip serialization for free, choice, and skip output types', 'test the engine action_spec_to_string function outputs valid JSON with correct call_to_action and output_type fields', 'parse a JSON string containing call_to_action, output_type, options, and tag into an ActionSpec object', 'serialize an ActionSpec object with call_to_action and output_type into a JSON string representation', 'create a StepController instance to manage simulation play pause and step execution', 'build a StepData dataclass to capture step number acting entity action and logs', 'run the StepController play method to resume continuous simulation execution', 'test the StepController step method to advance simulation by one step then pause', 'review the StepController wait_for_step_permission method that blocks until play step or stop is called']
```

Usage

```
{'create_stepcontroller': 'create a StepController instance to manage simulation play pause and step execution', 'build_stepdata': 'build a StepData dataclass to capture step number acting entity action and logs', 'run_stepcontroller_play': 'run the StepController play method to resume continuous simulation execution', 'test_stepcontroller_step': 'test the StepController step method to advance simulation by one step then pause', 'review_stepcontroller_wait': 'review the StepController wait_for_step_permission method that blocks until play step or stop is called'}
```

