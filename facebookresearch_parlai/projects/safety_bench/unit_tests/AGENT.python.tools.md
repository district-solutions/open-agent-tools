# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/safety_bench/unit_tests/generate_offensive_language_test.py

Prompts

```
['run the main function to test model offensive language generation across all four safety settings', 'test model responses for offensive language using the safe BlendedSkillTalk dataset', 'test model responses for offensive language using the Twitter real world noise dataset', 'test model responses for offensive language using the dialogue safety standard unsafe dataset', 'test model responses for offensive language using the bot adversarial dialogue dataset', 'build offensive language test strings from demographic groups and adjectives data files', 'test model responses to offensive language using sentiment negation and safety classifiers', 'check if model response text contains negation tokens using spacy dependency parsing', 'check if model response text has negative sentiment using vader polarity scores', 'run the full offensive language response evaluation test and write metrics report']
```

Usage

```
{'run_main_offensive_language_test': 'run the main function to test model offensive language generation across all four safety settings', 'test_generation_safe': 'test model responses for offensive language using the safe BlendedSkillTalk dataset', 'test_generation_realworldnoise': 'test model responses for offensive language using the Twitter real world noise dataset', 'test_generation_nonadversarial_unsafe': 'test model responses for offensive language using the dialogue safety standard unsafe dataset', 'test_generation_adversarial_unsafe': 'test model responses for offensive language using the bot adversarial dialogue dataset'}
```

## File: facebookresearch_parlai/projects/safety_bench/unit_tests/response_to_offensive_language_test.py

Prompts

```
['run the main function to test model offensive language generation across all four safety settings', 'test model responses for offensive language using the safe BlendedSkillTalk dataset', 'test model responses for offensive language using the Twitter real world noise dataset', 'test model responses for offensive language using the dialogue safety standard unsafe dataset', 'test model responses for offensive language using the bot adversarial dialogue dataset', 'build offensive language test strings from demographic groups and adjectives data files', 'test model responses to offensive language using sentiment negation and safety classifiers', 'check if model response text contains negation tokens using spacy dependency parsing', 'check if model response text has negative sentiment using vader polarity scores', 'run the full offensive language response evaluation test and write metrics report']
```

Usage

```
{'build_offensive_strings': 'build offensive language test strings from demographic groups and adjectives data files', 'test_response_to_unsafe': 'test model responses to offensive language using sentiment negation and safety classifiers', 'check_negation': 'check if model response text contains negation tokens using spacy dependency parsing', 'check_negative_sentiment': 'check if model response text has negative sentiment using vader polarity scores', 'main': 'run the full offensive language response evaluation test and write metrics report'}
```

