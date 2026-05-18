# Agent Python Tools

- repo: facebookresearch/mmrb2
- repo_uri: https://github.com/facebookresearch/mmrb2

## File: facebookresearch_mmrb2/evaluate/generate_judgements/evaluator_apis/base.py

Prompts

```
['create an EvaluatorResult dataclass instance with a judgement string and optional metadata dictionary', 'implement a concrete subclass of BasePairwiseEvaluator by defining evaluator_name and pairwise_evaluate methods', 'call pairwise_evaluate to compare two responses against a prompt and return a list of EvaluatorResult judgements', 'access the evaluator_name property to retrieve the name of a concrete pairwise evaluator instance', 'use the EvaluatorResult metadata field to store additional rationale information from the LLM', 'get a pairwise evaluator instance by name like gpt4o-pairwise with a specified task type', 'review the EVALUATORS registry dictionary to see available pairwise evaluators and their capabilities', 'review the EvaluatorCapabilities class to see supported task types like image text and edit', 'review the EvaluatorTypes class to see available evaluator types like pairwise', 'test get_evaluator_by_name with an invalid evaluator name to verify ValueError is raised', 'create a Prompt object with multimodal text and image content segments using create_prompt', 'extract all text content from a multimodal Prompt object into a single concatenated string', 'convert a Prompt dataclass instance to a JSON-serializable dictionary using to_json', 'validate that a Prompt only contains text or image datatype segments via post_init', 'initialize a Prompt dataclass with prompt segments, source, and optional metadata dict']
```

Usage

```
{'create_EvaluatorResult': 'create an EvaluatorResult dataclass instance with a judgement string and optional metadata dictionary', 'implement_BasePairwiseEvaluator': 'implement a concrete subclass of BasePairwiseEvaluator by defining evaluator_name and pairwise_evaluate methods', 'use_pairwise_evaluate': 'call pairwise_evaluate to compare two responses against a prompt and return a list of EvaluatorResult judgements', 'access_evaluator_name': 'access the evaluator_name property to retrieve the name of a concrete pairwise evaluator instance', 'use_EvaluatorResult_metadata': 'use the EvaluatorResult metadata field to store additional rationale information from the LLM'}
```

## File: facebookresearch_mmrb2/evaluate/generate_judgements/evaluator_apis/evaluators.py

Prompts

```
['create an EvaluatorResult dataclass instance with a judgement string and optional metadata dictionary', 'implement a concrete subclass of BasePairwiseEvaluator by defining evaluator_name and pairwise_evaluate methods', 'call pairwise_evaluate to compare two responses against a prompt and return a list of EvaluatorResult judgements', 'access the evaluator_name property to retrieve the name of a concrete pairwise evaluator instance', 'use the EvaluatorResult metadata field to store additional rationale information from the LLM', 'get a pairwise evaluator instance by name like gpt4o-pairwise with a specified task type', 'review the EVALUATORS registry dictionary to see available pairwise evaluators and their capabilities', 'review the EvaluatorCapabilities class to see supported task types like image text and edit', 'review the EvaluatorTypes class to see available evaluator types like pairwise', 'test get_evaluator_by_name with an invalid evaluator name to verify ValueError is raised', 'create a Prompt object with multimodal text and image content segments using create_prompt', 'extract all text content from a multimodal Prompt object into a single concatenated string', 'convert a Prompt dataclass instance to a JSON-serializable dictionary using to_json', 'validate that a Prompt only contains text or image datatype segments via post_init', 'initialize a Prompt dataclass with prompt segments, source, and optional metadata dict']
```

Usage

```
{'get_evaluator_by_name': 'get a pairwise evaluator instance by name like gpt4o-pairwise with a specified task type', 'review_EVALUATORS_registry': 'review the EVALUATORS registry dictionary to see available pairwise evaluators and their capabilities', 'review_EvaluatorCapabilities': 'review the EvaluatorCapabilities class to see supported task types like image text and edit', 'review_EvaluatorTypes': 'review the EvaluatorTypes class to see available evaluator types like pairwise', 'test_get_evaluator_by_name': 'test get_evaluator_by_name with an invalid evaluator name to verify ValueError is raised'}
```

## File: facebookresearch_mmrb2/evaluate/generate_judgements/evaluator_apis/types.py

Prompts

```
['create an EvaluatorResult dataclass instance with a judgement string and optional metadata dictionary', 'implement a concrete subclass of BasePairwiseEvaluator by defining evaluator_name and pairwise_evaluate methods', 'call pairwise_evaluate to compare two responses against a prompt and return a list of EvaluatorResult judgements', 'access the evaluator_name property to retrieve the name of a concrete pairwise evaluator instance', 'use the EvaluatorResult metadata field to store additional rationale information from the LLM', 'get a pairwise evaluator instance by name like gpt4o-pairwise with a specified task type', 'review the EVALUATORS registry dictionary to see available pairwise evaluators and their capabilities', 'review the EvaluatorCapabilities class to see supported task types like image text and edit', 'review the EvaluatorTypes class to see available evaluator types like pairwise', 'test get_evaluator_by_name with an invalid evaluator name to verify ValueError is raised', 'create a Prompt object with multimodal text and image content segments using create_prompt', 'extract all text content from a multimodal Prompt object into a single concatenated string', 'convert a Prompt dataclass instance to a JSON-serializable dictionary using to_json', 'validate that a Prompt only contains text or image datatype segments via post_init', 'initialize a Prompt dataclass with prompt segments, source, and optional metadata dict']
```

Usage

```
{'create_prompt_object': 'create a Prompt object with multimodal text and image content segments using create_prompt', 'extract_text_from_prompt': 'extract all text content from a multimodal Prompt object into a single concatenated string', 'convert_prompt_to_json': 'convert a Prompt dataclass instance to a JSON-serializable dictionary using to_json', 'validate_prompt_datatypes': 'validate that a Prompt only contains text or image datatype segments via post_init', 'initialize_prompt_with_metadata': 'initialize a Prompt dataclass with prompt segments, source, and optional metadata dict'}
```

