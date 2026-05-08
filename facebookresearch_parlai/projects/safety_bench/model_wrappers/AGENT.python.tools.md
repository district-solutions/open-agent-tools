# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/safety_bench/model_wrappers/example_wrapper.py

Prompts

```
['create a model wrapper class that replies hello to every input text', 'register a model wrapper using the register_model_wrapper decorator with a name', 'implement the get_response method to return a string response from input text', 'initialize an ExampleWrapper instance for loading a model in the constructor', 'use the ExampleWrapper as a template for building custom model wrappers', 'create a subclass of GPTWrapper that defines model_name, model_size, and additional_opts properties', 'get a text response from the GPT2LargeWrapper model by calling get_response with input text', 'get a text response from the DialoGPTMediumWrapper model by calling get_response with input text', 'register a new model wrapper class using the register_model_wrapper decorator with a unique key', 'configure beam search inference options like beam_size and beam_min_length in additional_opts', 'use get_response on a BlenderBot90MWrapper to get a text reply from the model', 'subclass ParlAIModelZooWrapper and define a zoo_path property to wrap a new ParlAI model', 'instantiate SeekerDialogue3BWrapper to load the Seeker 3B dialogue model with RAG search overrides', 'review how ParlAIModelZooWrapper uses create_agent_from_model_file with skip_generation and interactive_mode overrides']
```

Usage

```
{'create_example_wrapper_class': 'create a model wrapper class that replies hello to every input text', 'register_model_wrapper_decorator': 'register a model wrapper using the register_model_wrapper decorator with a name', 'implement_get_response_method': 'implement the get_response method to return a string response from input text', 'initialize_example_wrapper': 'initialize an ExampleWrapper instance for loading a model in the constructor', 'use_example_wrapper_template': 'use the ExampleWrapper as a template for building custom model wrappers'}
```

## File: facebookresearch_parlai/projects/safety_bench/model_wrappers/gpt_wrappers.py

Prompts

```
['create a model wrapper class that replies hello to every input text', 'register a model wrapper using the register_model_wrapper decorator with a name', 'implement the get_response method to return a string response from input text', 'initialize an ExampleWrapper instance for loading a model in the constructor', 'use the ExampleWrapper as a template for building custom model wrappers', 'create a subclass of GPTWrapper that defines model_name, model_size, and additional_opts properties', 'get a text response from the GPT2LargeWrapper model by calling get_response with input text', 'get a text response from the DialoGPTMediumWrapper model by calling get_response with input text', 'register a new model wrapper class using the register_model_wrapper decorator with a unique key', 'configure beam search inference options like beam_size and beam_min_length in additional_opts', 'use get_response on a BlenderBot90MWrapper to get a text reply from the model', 'subclass ParlAIModelZooWrapper and define a zoo_path property to wrap a new ParlAI model', 'instantiate SeekerDialogue3BWrapper to load the Seeker 3B dialogue model with RAG search overrides', 'review how ParlAIModelZooWrapper uses create_agent_from_model_file with skip_generation and interactive_mode overrides']
```

Usage

```
{'create_gpt_wrapper_subclass': 'create a subclass of GPTWrapper that defines model_name, model_size, and additional_opts properties', 'get_response_from_gpt2_large': 'get a text response from the GPT2LargeWrapper model by calling get_response with input text', 'get_response_from_dialogpt_medium': 'get a text response from the DialoGPTMediumWrapper model by calling get_response with input text', 'register_new_model_wrapper': 'register a new model wrapper class using the register_model_wrapper decorator with a unique key', 'configure_beam_inference_opts': 'configure beam search inference options like beam_size and beam_min_length in additional_opts'}
```

## File: facebookresearch_parlai/projects/safety_bench/model_wrappers/parlai_model_zoo_wrappers.py

Prompts

```
['create a model wrapper class that replies hello to every input text', 'register a model wrapper using the register_model_wrapper decorator with a name', 'implement the get_response method to return a string response from input text', 'initialize an ExampleWrapper instance for loading a model in the constructor', 'use the ExampleWrapper as a template for building custom model wrappers', 'create a subclass of GPTWrapper that defines model_name, model_size, and additional_opts properties', 'get a text response from the GPT2LargeWrapper model by calling get_response with input text', 'get a text response from the DialoGPTMediumWrapper model by calling get_response with input text', 'register a new model wrapper class using the register_model_wrapper decorator with a unique key', 'configure beam search inference options like beam_size and beam_min_length in additional_opts', 'use get_response on a BlenderBot90MWrapper to get a text reply from the model', 'subclass ParlAIModelZooWrapper and define a zoo_path property to wrap a new ParlAI model', 'instantiate SeekerDialogue3BWrapper to load the Seeker 3B dialogue model with RAG search overrides', 'review how ParlAIModelZooWrapper uses create_agent_from_model_file with skip_generation and interactive_mode overrides']
```

Usage

```
{'get_response_from_blenderbot': 'use get_response on a BlenderBot90MWrapper to get a text reply from the model', 'create_custom_parlai_wrapper': 'subclass ParlAIModelZooWrapper and define a zoo_path property to wrap a new ParlAI model', 'load_seeker_dialogue_model': 'instantiate SeekerDialogue3BWrapper to load the Seeker 3B dialogue model with RAG search overrides', 'register_new_model_wrapper': 'decorate a wrapper class with register_model_wrapper to make it available by name in safety_bench', 'review_wrapper_initialization': 'review how ParlAIModelZooWrapper uses create_agent_from_model_file with skip_generation and interactive_mode overrides'}
```

