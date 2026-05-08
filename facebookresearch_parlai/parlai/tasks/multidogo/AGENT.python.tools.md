# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/multidogo/agents.py

Prompts

```
['setup MultiDoGo dialog episodes from conversation JSON files across multiple domains', 'add command-line arguments for multidogo-domains and intent-type to a ParlAI parser', 'iterate over MultiDoGo conversation data files yielding conversation IDs, domains, and turn data', 'run the MultiDoGo system teacher for training a goal-oriented dialogue agent', 'run the MultiDoGo user simulator teacher for training a user simulation model', 'build the MultiDoGo dataset by downloading and preprocessing multi-domain goal-oriented dialogue data for all domains', 'preprocess MultiDoGo conversations for a specific domain and datatype with turn or sentence intent labels', 'build a conversation ID to line span map from unannotated TSV data for fast lookup', 'aggregate annotated and unannotated MultiDoGo conversations into JSON files with intent labels and slots', 'extract slot-value pairs from an utterance and its corresponding slot-label string']
```

Usage

```
{'setup_multidogo_episodes': 'setup MultiDoGo dialog episodes from conversation JSON files across multiple domains', 'add_multidogo_cmdline_args': 'add command-line arguments for multidogo-domains and intent-type to a ParlAI parser', 'iterate_multidogo_conversations': 'iterate over MultiDoGo conversation data files yielding conversation IDs, domains, and turn data', 'run_system_teacher': 'run the MultiDoGo system teacher for training a goal-oriented dialogue agent', 'run_user_simulator': 'run the MultiDoGo user simulator teacher for training a user simulation model'}
```

## File: facebookresearch_parlai/parlai/tasks/multidogo/build.py

Prompts

```
['setup MultiDoGo dialog episodes from conversation JSON files across multiple domains', 'add command-line arguments for multidogo-domains and intent-type to a ParlAI parser', 'iterate over MultiDoGo conversation data files yielding conversation IDs, domains, and turn data', 'run the MultiDoGo system teacher for training a goal-oriented dialogue agent', 'run the MultiDoGo user simulator teacher for training a user simulation model', 'build the MultiDoGo dataset by downloading and preprocessing multi-domain goal-oriented dialogue data for all domains', 'preprocess MultiDoGo conversations for a specific domain and datatype with turn or sentence intent labels', 'build a conversation ID to line span map from unannotated TSV data for fast lookup', 'aggregate annotated and unannotated MultiDoGo conversations into JSON files with intent labels and slots', 'extract slot-value pairs from an utterance and its corresponding slot-label string']
```

Usage

```
{'build_multidogo_dataset': 'build the MultiDoGo dataset by downloading and preprocessing multi-domain goal-oriented dialogue data for all domains', 'preprocess_multidogo_conversations': 'preprocess MultiDoGo conversations for a specific domain and datatype with turn or sentence intent labels', 'build_conversation_span_map': 'build a conversation ID to line span map from unannotated TSV data for fast lookup', 'aggregate_and_write_conversations': 'aggregate annotated and unannotated MultiDoGo conversations into JSON files with intent labels and slots', 'get_slots_map': 'extract slot-value pairs from an utterance and its corresponding slot-label string'}
```

