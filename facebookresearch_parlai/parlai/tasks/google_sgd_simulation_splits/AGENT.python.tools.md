# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/google_sgd_simulation_splits/agents.py

Prompts

```
['review the GoogleSgdInDomainParser class that loads custom in-domain SGD splits for ParlAI dialogue training', 'review the GoogleSgdOutDomainParser class that loads out-domain SGD splits with goal filtering and custom evaluation metrics', 'refactor the filter_goals method to filter goals by a custom list of valid out-domain API names', 'run the generate_episodes method to filter SGD episodes to only those with single goals', 'review the custom_evaluation method that tracks out-domain API prediction accuracy using AverageMetric', 'run the build function to download and split Google SGD data into train dev and test sets', 'build a custom model model split from Google SGD dialogues containing homes rental cars messaging and payment domains', 'review the list of holdout domains including Homes RentalCars Messaging and Payment services', 'refactor the build function to add new holdout domains or change the train dev test split ratios', 'summarize the nested save_model_model function that chunks conversations into files of 64 dialogues each']
```

Usage

```
{'review_GoogleSgdInDomainParser': 'review the GoogleSgdInDomainParser class that loads custom in-domain SGD splits for ParlAI dialogue training', 'review_GoogleSgdOutDomainParser': 'review the GoogleSgdOutDomainParser class that loads out-domain SGD splits with goal filtering and custom evaluation metrics', 'refactor_filter_goals': 'refactor the filter_goals method to filter goals by a custom list of valid out-domain API names', 'run_generate_episodes': 'run the generate_episodes method to filter SGD episodes to only those with single goals', 'review_custom_evaluation': 'review the custom_evaluation method that tracks out-domain API prediction accuracy using AverageMetric'}
```

## File: facebookresearch_parlai/parlai/tasks/google_sgd_simulation_splits/build.py

Prompts

```
['review the GoogleSgdInDomainParser class that loads custom in-domain SGD splits for ParlAI dialogue training', 'review the GoogleSgdOutDomainParser class that loads out-domain SGD splits with goal filtering and custom evaluation metrics', 'refactor the filter_goals method to filter goals by a custom list of valid out-domain API names', 'run the generate_episodes method to filter SGD episodes to only those with single goals', 'review the custom_evaluation method that tracks out-domain API prediction accuracy using AverageMetric', 'run the build function to download and split Google SGD data into train dev and test sets', 'build a custom model model split from Google SGD dialogues containing homes rental cars messaging and payment domains', 'review the list of holdout domains including Homes RentalCars Messaging and Payment services', 'refactor the build function to add new holdout domains or change the train dev test split ratios', 'summarize the nested save_model_model function that chunks conversations into files of 64 dialogues each']
```

Usage

```
{'build_google_sgd_rl_splits': 'run the build function to download and split Google SGD data into train dev and test sets', 'build_model_model_holdout': 'build a custom model model split from Google SGD dialogues containing homes rental cars messaging and payment domains', 'review_MODEL_MODEL_HOLDOUT_DOMAINS': 'review the list of holdout domains including Homes RentalCars Messaging and Payment services', 'refactor_build_function': 'refactor the build function to add new holdout domains or change the train dev test split ratios', 'summarize_save_model_model': 'summarize the nested save_model_model function that chunks conversations into files of 64 dialogues each'}
```

