# Agent Python Tools

- repo: facebookresearch/mils
- repo_uri: https://github.com/facebookresearch/mils

## File: facebookresearch_mils/optimization_utils/generator.py

Prompts

```
['create a Generator instance with a text pipeline and model name to generate new text from scored pairs', 'run the Generator on a task dictionary mapping filenames to lists of score text tuples', 'strip line counters and special tokens from generated text output using strip_line_counters', 'sort a list of values by score while sampling a fraction for exploration using sort_with_exploration', 'build prompt descriptions from a list of score text pairs using _get_descriptions for model input', 'run a CLIP-like model to extract normalized text embeddings for zero-shot classification from a list of class names', 'run a CLIP-like model to extract normalized image embeddings from a list of image file paths', 'run the Scorer class on batched inputs to compute scores and track best and average values per key', 'retrieve the best-scoring PIL image per key from the Scorer after running a scoring pass', 'run a registered scoring function on a batch of data for a given key using the Scorer class']
```

Usage

```
{'create_generator_for_llm_text_generation': 'create a Generator instance with a text pipeline and model name to generate new text from scored pairs', 'run_generator_on_task_dict': 'run the Generator on a task dictionary mapping filenames to lists of score text tuples', 'strip_line_counters_from_text': 'strip line counters and special tokens from generated text output using strip_line_counters', 'sort_values_with_exploration': 'sort a list of values by score while sampling a fraction for exploration using sort_with_exploration', 'build_prompt_descriptions_from_pairs': 'build prompt descriptions from a list of score text pairs using _get_descriptions for model input'}
```

## File: facebookresearch_mils/optimization_utils/scorer.py

Prompts

```
['create a Generator instance with a text pipeline and model name to generate new text from scored pairs', 'run the Generator on a task dictionary mapping filenames to lists of score text tuples', 'strip line counters and special tokens from generated text output using strip_line_counters', 'sort a list of values by score while sampling a fraction for exploration using sort_with_exploration', 'build prompt descriptions from a list of score text pairs using _get_descriptions for model input', 'run a CLIP-like model to extract normalized text embeddings for zero-shot classification from a list of class names', 'run a CLIP-like model to extract normalized image embeddings from a list of image file paths', 'run the Scorer class on batched inputs to compute scores and track best and average values per key', 'retrieve the best-scoring PIL image per key from the Scorer after running a scoring pass', 'run a registered scoring function on a batch of data for a given key using the Scorer class']
```

Usage

```
{'get_text_features': 'run a CLIP-like model to extract normalized text embeddings for zero-shot classification from a list of class names', 'get_image_features': 'run a CLIP-like model to extract normalized image embeddings from a list of image file paths', 'scorer_call': 'run the Scorer class on batched inputs to compute scores and track best and average values per key', 'scorer_get_best': 'retrieve the best-scoring PIL image per key from the Scorer after running a scoring pass', 'scorer_score': 'run a registered scoring function on a batch of data for a given key using the Scorer class'}
```

