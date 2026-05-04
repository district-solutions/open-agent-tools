# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/contrib/data/questionnaires/base_questionnaire.py

Prompts

```
['create a subclass of QuestionnaireBase that implements aggregate_results and plot_results methods', 'create a Question dataclass instance with a statement, dimension, and optional choices list', 'process a player answer text against a Question to get the dimension and numeric answer value', 'get the questionnaire configuration dictionary with name, description, type, preprompt, and questions', 'aggregate raw player answers by computing the mean numeric value per dimension using _default_aggregate_results', 'create a DASSQuestionnaire instance to measure depression anxiety and stress scores for players', 'aggregate raw player answers into mean scores per dimension using DASSQuestionnaire aggregate_results', 'get the valid score ranges for anxiety depression and stress dimensions via get_dimension_ranges', 'configure the 42 DASS questions with agreement scale choices across anxiety depression and stress dimensions', 'process a single player answer text against a DASS question using the base class process_answer method']
```

Usage

```
{'create_questionnaire_subclass': 'create a subclass of QuestionnaireBase that implements aggregate_results and plot_results methods', 'create_question_dataclass': 'create a Question dataclass instance with a statement, dimension, and optional choices list', 'process_answer_questionnaire': 'process a player answer text against a Question to get the dimension and numeric answer value', 'get_questionnaire_config': 'get the questionnaire configuration dictionary with name, description, type, preprompt, and questions', 'aggregate_questionnaire_results': 'aggregate raw player answers by computing the mean numeric value per dimension using _default_aggregate_results'}
```

## File: google-deepmind_concordia/concordia/contrib/data/questionnaires/depression_anxiety_stress_scale.py

Prompts

```
['create a subclass of QuestionnaireBase that implements aggregate_results and plot_results methods', 'create a Question dataclass instance with a statement, dimension, and optional choices list', 'process a player answer text against a Question to get the dimension and numeric answer value', 'get the questionnaire configuration dictionary with name, description, type, preprompt, and questions', 'aggregate raw player answers by computing the mean numeric value per dimension using _default_aggregate_results', 'create a DASSQuestionnaire instance to measure depression anxiety and stress scores for players', 'aggregate raw player answers into mean scores per dimension using DASSQuestionnaire aggregate_results', 'get the valid score ranges for anxiety depression and stress dimensions via get_dimension_ranges', 'configure the 42 DASS questions with agreement scale choices across anxiety depression and stress dimensions', 'process a single player answer text against a DASS question using the base class process_answer method']
```

Usage

```
{'create_dass_questionnaire': 'create a DASSQuestionnaire instance to measure depression anxiety and stress scores for players', 'aggregate_dass_results': 'aggregate raw player answers into mean scores per dimension using DASSQuestionnaire aggregate_results', 'get_dass_dimension_ranges': 'get the valid score ranges for anxiety depression and stress dimensions via get_dimension_ranges', 'configure_dass_questions': 'configure the 42 DASS questions with agreement scale choices across anxiety depression and stress dimensions', 'process_dass_answer': 'process a single player answer text against a DASS question using the base class process_answer method'}
```

