# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/tests/crowdsourcing/tasks/model_chat/test_image_stack.py

Prompts

```
['test the ImageStack class by filling all stack slots with random worker image requests', 'test removing a specific worker from a given stack index in the ImageStack', 'review the ImageStack class that tracks model image chats and prevents duplicate worker assignments', 'test the get_next_image method to assign the next available image to a worker', 'test building a new stack or loading an existing one from a JSON file', 'run the end-to-end test for the model chat crowdsourcing task with a fixed response model', 'test agent states by sending messages and comparing against expected state JSON files', 'test that the final chat data JSON output matches the expected chat data file', 'remove non-deterministic keys like update_id from dialog state for deterministic comparison', 'set up the model chat task configuration with conversation count, chat data folder, and model opt path', 'test the ModelChatResultsCompiler subclass that loads fake JSON task data from date-named folders', 'test the get_task_data method that parses JSON files and extracts worker and assignment IDs', 'test the model chat analysis compiler with basic problem buckets set to None', 'test the model chat analysis compiler with personas and problem buckets enabled', 'test the stdout output of the model chat analysis against expected regression files', 'test the model image chat crowdsourcing task end-to-end with expected agent states and chat data validation', 'create a pickle file containing image context with Message objects including image_id and label_candidates', 'download the Transresnet Multimodal model from ParlAI zoo to a specified data folder path', 'set up a SharedModelImageChatTaskState with the image chat world module for the crowdsourcing server', 'test agent states against expected JSON states and validate final chat data contents match expected values']
```

Usage

```
{'test_ImageStack_fill_stack': 'test the ImageStack class by filling all stack slots with random worker image requests', 'test_ImageStack_remove_worker': 'test removing a specific worker from a given stack index in the ImageStack', 'review_ImageStack_class': 'review the ImageStack class that tracks model image chats and prevents duplicate worker assignments', 'test_ImageStack_get_next_image': 'test the get_next_image method to assign the next available image to a worker', 'test_ImageStack_build_or_load_stack': 'test building a new stack or loading an existing one from a JSON file'}
```

## File: facebookresearch_parlai/tests/crowdsourcing/tasks/model_chat/test_model_chat.py

Prompts

```
['test the ImageStack class by filling all stack slots with random worker image requests', 'test removing a specific worker from a given stack index in the ImageStack', 'review the ImageStack class that tracks model image chats and prevents duplicate worker assignments', 'test the get_next_image method to assign the next available image to a worker', 'test building a new stack or loading an existing one from a JSON file', 'run the end-to-end test for the model chat crowdsourcing task with a fixed response model', 'test agent states by sending messages and comparing against expected state JSON files', 'test that the final chat data JSON output matches the expected chat data file', 'remove non-deterministic keys like update_id from dialog state for deterministic comparison', 'set up the model chat task configuration with conversation count, chat data folder, and model opt path', 'test the ModelChatResultsCompiler subclass that loads fake JSON task data from date-named folders', 'test the get_task_data method that parses JSON files and extracts worker and assignment IDs', 'test the model chat analysis compiler with basic problem buckets set to None', 'test the model chat analysis compiler with personas and problem buckets enabled', 'test the stdout output of the model chat analysis against expected regression files', 'test the model image chat crowdsourcing task end-to-end with expected agent states and chat data validation', 'create a pickle file containing image context with Message objects including image_id and label_candidates', 'download the Transresnet Multimodal model from ParlAI zoo to a specified data folder path', 'set up a SharedModelImageChatTaskState with the image chat world module for the crowdsourcing server', 'test agent states against expected JSON states and validate final chat data contents match expected values']
```

Usage

```
{'test_model_chat_task': 'run the end-to-end test for the model chat crowdsourcing task with a fixed response model', 'test_agent_states': 'test agent states by sending messages and comparing against expected state JSON files', 'test_final_chat_data': 'test that the final chat data JSON output matches the expected chat data file', 'remove_non_deterministic_keys': 'remove non-deterministic keys like update_id from dialog state for deterministic comparison', 'setup_model_chat_config': 'set up the model chat task configuration with conversation count, chat data folder, and model opt path'}
```

## File: facebookresearch_parlai/tests/crowdsourcing/tasks/model_chat/test_model_chat_analysis.py

Prompts

```
['test the ImageStack class by filling all stack slots with random worker image requests', 'test removing a specific worker from a given stack index in the ImageStack', 'review the ImageStack class that tracks model image chats and prevents duplicate worker assignments', 'test the get_next_image method to assign the next available image to a worker', 'test building a new stack or loading an existing one from a JSON file', 'run the end-to-end test for the model chat crowdsourcing task with a fixed response model', 'test agent states by sending messages and comparing against expected state JSON files', 'test that the final chat data JSON output matches the expected chat data file', 'remove non-deterministic keys like update_id from dialog state for deterministic comparison', 'set up the model chat task configuration with conversation count, chat data folder, and model opt path', 'test the ModelChatResultsCompiler subclass that loads fake JSON task data from date-named folders', 'test the get_task_data method that parses JSON files and extracts worker and assignment IDs', 'test the model chat analysis compiler with basic problem buckets set to None', 'test the model chat analysis compiler with personas and problem buckets enabled', 'test the stdout output of the model chat analysis against expected regression files', 'test the model image chat crowdsourcing task end-to-end with expected agent states and chat data validation', 'create a pickle file containing image context with Message objects including image_id and label_candidates', 'download the Transresnet Multimodal model from ParlAI zoo to a specified data folder path', 'set up a SharedModelImageChatTaskState with the image chat world module for the crowdsourcing server', 'test agent states against expected JSON states and validate final chat data contents match expected values']
```

Usage

```
{'test_model_chat_results_compiler': 'test the ModelChatResultsCompiler subclass that loads fake JSON task data from date-named folders', 'test_get_task_data': 'test the get_task_data method that parses JSON files and extracts worker and assignment IDs', 'test_compile_results_basic': 'test the model chat analysis compiler with basic problem buckets set to None', 'test_compile_results_personas_buckets': 'test the model chat analysis compiler with personas and problem buckets enabled', 'test_stdout_regression': 'test the stdout output of the model chat analysis against expected regression files'}
```

## File: facebookresearch_parlai/tests/crowdsourcing/tasks/model_chat/test_model_image_chat.py

Prompts

```
['test the ImageStack class by filling all stack slots with random worker image requests', 'test removing a specific worker from a given stack index in the ImageStack', 'review the ImageStack class that tracks model image chats and prevents duplicate worker assignments', 'test the get_next_image method to assign the next available image to a worker', 'test building a new stack or loading an existing one from a JSON file', 'run the end-to-end test for the model chat crowdsourcing task with a fixed response model', 'test agent states by sending messages and comparing against expected state JSON files', 'test that the final chat data JSON output matches the expected chat data file', 'remove non-deterministic keys like update_id from dialog state for deterministic comparison', 'set up the model chat task configuration with conversation count, chat data folder, and model opt path', 'test the ModelChatResultsCompiler subclass that loads fake JSON task data from date-named folders', 'test the get_task_data method that parses JSON files and extracts worker and assignment IDs', 'test the model chat analysis compiler with basic problem buckets set to None', 'test the model chat analysis compiler with personas and problem buckets enabled', 'test the stdout output of the model chat analysis against expected regression files', 'test the model image chat crowdsourcing task end-to-end with expected agent states and chat data validation', 'create a pickle file containing image context with Message objects including image_id and label_candidates', 'download the Transresnet Multimodal model from ParlAI zoo to a specified data folder path', 'set up a SharedModelImageChatTaskState with the image chat world module for the crowdsourcing server', 'test agent states against expected JSON states and validate final chat data contents match expected values']
```

Usage

```
{'test_model_image_chat_task': 'test the model image chat crowdsourcing task end-to-end with expected agent states and chat data validation', 'create_image_context_pickle': 'create a pickle file containing image context with Message objects including image_id and label_candidates', 'download_transresnet_multimodal_model': 'download the Transresnet Multimodal model from ParlAI zoo to a specified data folder path', 'setup_shared_model_image_chat_state': 'set up a SharedModelImageChatTaskState with the image chat world module for the crowdsourcing server', 'test_agent_states_and_chat_data': 'test agent states against expected JSON states and validate final chat data contents match expected values'}
```

