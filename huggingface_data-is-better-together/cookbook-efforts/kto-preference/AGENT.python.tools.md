# Agent Python Tools

- repo: huggingface/data-is-better-together
- repo_uri: https://github.com/huggingface/data-is-better-together

## File: huggingface_data-is-better-together/cookbook-efforts/kto-preference/preference_gen.py

Prompts

```
['create a function that loads the haiku_prompts dataset from HuggingFace and renames the instructions column to input', 'build an InferenceEndpointsLLM instance for the Llama-2-70b-chat model with a given task and token', 'build an InferenceEndpointsLLM instance for the Mistral-7B-Instruct model with a given task and token', 'create a TextGenerationTask with a system prompt for generating haiku poetry with specific syllable structure', 'run the distilabel pipeline to generate multiple haiku outputs from a pool of LLMs on a dataset']
```

Usage

```
{'prepare_data': 'create a function that loads the haiku_prompts dataset from HuggingFace and renames the instructions column to input', 'load_llama2': 'build an InferenceEndpointsLLM instance for the Llama-2-70b-chat model with a given task and token', 'load_mistral': 'build an InferenceEndpointsLLM instance for the Mistral-7B-Instruct model with a given task and token', 'TextGenerationTask': 'create a TextGenerationTask with a system prompt for generating haiku poetry with specific syllable structure', 'pipeline_generate': 'run the distilabel pipeline to generate multiple haiku outputs from a pool of LLMs on a dataset'}
```

