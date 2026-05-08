# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/pointer_generator/postprocess.py

Prompts

```
['run the postprocess CLI to replace unk-N tokens in target sequences with source words', 'run the replace_oovs function to substitute unk-N tokens using source sequence position lookup', 'create an OOVIndexError exception when a target unk-N tag points past the source sequence end', 'review the replace_oovs function that maps unk-N tokens to source words by position index', 'review the OOVIndexError class that tracks out-of-vocabulary index mismatches between source and target', 'run the preprocess script to replace out-of-vocabulary words with position-based unk tokens in source and target sequences', 'run the CLI tool with --source, --vocab, and --source-out args to preprocess text for pointer generator models', 'run the preprocess script with --target and --target-out to also replace matching OOV tokens in target sequences', 'refactor the replace_oovs function to use a set for vocabulary lookups instead of a list for better performance']
```

Usage

```
{'run_replace_oovs_cli': 'run the postprocess CLI to replace unk-N tokens in target sequences with source words', 'run_replace_oovs_function': 'run the replace_oovs function to substitute unk-N tokens using source sequence position lookup', 'create_OOVIndexError': 'create an OOVIndexError exception when a target unk-N tag points past the source sequence end', 'review_replace_oovs': 'review the replace_oovs function that maps unk-N tokens to source words by position index', 'review_OOVIndexError': 'review the OOVIndexError class that tracks out-of-vocabulary index mismatches between source and target'}
```

## File: facebookresearch_fairseq/examples/pointer_generator/preprocess.py

Prompts

```
['run the postprocess CLI to replace unk-N tokens in target sequences with source words', 'run the replace_oovs function to substitute unk-N tokens using source sequence position lookup', 'create an OOVIndexError exception when a target unk-N tag points past the source sequence end', 'review the replace_oovs function that maps unk-N tokens to source words by position index', 'review the OOVIndexError class that tracks out-of-vocabulary index mismatches between source and target', 'run the preprocess script to replace out-of-vocabulary words with position-based unk tokens in source and target sequences', 'run the CLI tool with --source, --vocab, and --source-out args to preprocess text for pointer generator models', 'run the preprocess script with --target and --target-out to also replace matching OOV tokens in target sequences', 'refactor the replace_oovs function to use a set for vocabulary lookups instead of a list for better performance']
```

Usage

```
{'run_replace_oovs': 'run the preprocess script to replace out-of-vocabulary words with position-based unk tokens in source and target sequences', 'run_preprocess_cli': 'run the CLI tool with --source, --vocab, and --source-out args to preprocess text for pointer generator models', 'run_preprocess_with_target': 'run the preprocess script with --target and --target-out to also replace matching OOV tokens in target sequences', 'review_replace_oovs': 'review the replace_oovs function that maps OOV words to their source sequence positions using angle bracket tokens', 'refactor_replace_oovs': 'refactor the replace_oovs function to use a set for vocabulary lookups instead of a list for better performance'}
```

