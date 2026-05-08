# Agent Python Tools

- repo: facebookresearch/collaborative-reasoner
- repo_uri: https://github.com/facebookresearch/collaborative-reasoner

## File: facebookresearch_collaborative-reasoner/evaluators/base_evaluator.py

Prompts

```
['create a subclass of Evaluator that overrides _eval to score a single chat turn', 'create a subclass of PromptingEvaluator that overrides promptify_eval_response and extract_score for LLM-based rating', 'create a subclass of CorrectnessEvaluator to track n_turns_to_success and final_success_rate metrics', 'run rate_every_turn to evaluate each chat turn immediately with a list of Evaluator raters', 'run rate_whole_conv to asynchronously rate all turns in a conversation and annotate results', 'create a custom extraction evaluator by subclassing ExtractionPromptingEvaluator and implementing promptify_eval_response, normalize_answer, and is_valid_answer', 'run the MATHExtractionPromptingEvaluator to extract boxed math answers from conversation turns using the boxed LaTeX pattern', 'run the MMLUProExtractionPromptingEvaluator to extract multiple choice answers in letter format from MMLU-Pro responses', 'run the GPQAExtractionPromptingEvaluator to extract multiple choice answers from GPQA domain question responses', 'compute persuasion and assertiveness social behavior metrics for a conversation using the compute_social_metrics static method', 'create a MATHMatchEvaluator to grade math answers by parsing boxed content and comparing to the expected answer', 'create a GPQAMatchEvaluator to extract letter answers and compare against a numeric label index', 'create a MMLUProMatchEvaluator to extract letter answers and compare against an expected letter answer', 'create an ExploreTOMMatchEvaluator to evaluate theory of mind answers using keyword and substring matching', 'use extract_letter_answer to parse uppercase letter answers from a model response string']
```

Usage

```
{'create_evaluator_subclass': 'create a subclass of Evaluator that overrides _eval to score a single chat turn', 'create_prompting_evaluator_subclass': 'create a subclass of PromptingEvaluator that overrides promptify_eval_response and extract_score for LLM-based rating', 'create_correctness_evaluator_subclass': 'create a subclass of CorrectnessEvaluator to track n_turns_to_success and final_success_rate metrics', 'run_rate_every_turn': 'run rate_every_turn to evaluate each chat turn immediately with a list of Evaluator raters', 'run_rate_whole_conv': 'run rate_whole_conv to asynchronously rate all turns in a conversation and annotate results'}
```

## File: facebookresearch_collaborative-reasoner/evaluators/extraction_evaluators.py

Prompts

```
['create a subclass of Evaluator that overrides _eval to score a single chat turn', 'create a subclass of PromptingEvaluator that overrides promptify_eval_response and extract_score for LLM-based rating', 'create a subclass of CorrectnessEvaluator to track n_turns_to_success and final_success_rate metrics', 'run rate_every_turn to evaluate each chat turn immediately with a list of Evaluator raters', 'run rate_whole_conv to asynchronously rate all turns in a conversation and annotate results', 'create a custom extraction evaluator by subclassing ExtractionPromptingEvaluator and implementing promptify_eval_response, normalize_answer, and is_valid_answer', 'run the MATHExtractionPromptingEvaluator to extract boxed math answers from conversation turns using the boxed LaTeX pattern', 'run the MMLUProExtractionPromptingEvaluator to extract multiple choice answers in letter format from MMLU-Pro responses', 'run the GPQAExtractionPromptingEvaluator to extract multiple choice answers from GPQA domain question responses', 'compute persuasion and assertiveness social behavior metrics for a conversation using the compute_social_metrics static method', 'create a MATHMatchEvaluator to grade math answers by parsing boxed content and comparing to the expected answer', 'create a GPQAMatchEvaluator to extract letter answers and compare against a numeric label index', 'create a MMLUProMatchEvaluator to extract letter answers and compare against an expected letter answer', 'create an ExploreTOMMatchEvaluator to evaluate theory of mind answers using keyword and substring matching', 'use extract_letter_answer to parse uppercase letter answers from a model response string']
```

Usage

```
{'create_extraction_evaluator': 'create a custom extraction evaluator by subclassing ExtractionPromptingEvaluator and implementing promptify_eval_response, normalize_answer, and is_valid_answer', 'run_MATH_extraction_eval': 'run the MATHExtractionPromptingEvaluator to extract boxed math answers from conversation turns using the boxed LaTeX pattern', 'run_MMLUPro_extraction_eval': 'run the MMLUProExtractionPromptingEvaluator to extract multiple choice answers in letter format from MMLU-Pro responses', 'run_GPQA_extraction_eval': 'run the GPQAExtractionPromptingEvaluator to extract multiple choice answers from GPQA domain question responses', 'compute_social_metrics': 'compute persuasion and assertiveness social behavior metrics for a conversation using the compute_social_metrics static method'}
```

## File: facebookresearch_collaborative-reasoner/evaluators/match_evaluators.py

Prompts

```
['create a subclass of Evaluator that overrides _eval to score a single chat turn', 'create a subclass of PromptingEvaluator that overrides promptify_eval_response and extract_score for LLM-based rating', 'create a subclass of CorrectnessEvaluator to track n_turns_to_success and final_success_rate metrics', 'run rate_every_turn to evaluate each chat turn immediately with a list of Evaluator raters', 'run rate_whole_conv to asynchronously rate all turns in a conversation and annotate results', 'create a custom extraction evaluator by subclassing ExtractionPromptingEvaluator and implementing promptify_eval_response, normalize_answer, and is_valid_answer', 'run the MATHExtractionPromptingEvaluator to extract boxed math answers from conversation turns using the boxed LaTeX pattern', 'run the MMLUProExtractionPromptingEvaluator to extract multiple choice answers in letter format from MMLU-Pro responses', 'run the GPQAExtractionPromptingEvaluator to extract multiple choice answers from GPQA domain question responses', 'compute persuasion and assertiveness social behavior metrics for a conversation using the compute_social_metrics static method', 'create a MATHMatchEvaluator to grade math answers by parsing boxed content and comparing to the expected answer', 'create a GPQAMatchEvaluator to extract letter answers and compare against a numeric label index', 'create a MMLUProMatchEvaluator to extract letter answers and compare against an expected letter answer', 'create an ExploreTOMMatchEvaluator to evaluate theory of mind answers using keyword and substring matching', 'use extract_letter_answer to parse uppercase letter answers from a model response string']
```

Usage

```
{'create_MATHMatchEvaluator': 'create a MATHMatchEvaluator to grade math answers by parsing boxed content and comparing to the expected answer', 'create_GPQAMatchEvaluator': 'create a GPQAMatchEvaluator to extract letter answers and compare against a numeric label index', 'create_MMLUProMatchEvaluator': 'create a MMLUProMatchEvaluator to extract letter answers and compare against an expected letter answer', 'create_ExploreTOMMatchEvaluator': 'create an ExploreTOMMatchEvaluator to evaluate theory of mind answers using keyword and substring matching', 'use_extract_letter_answer': 'use extract_letter_answer to parse uppercase letter answers from a model response string'}
```

