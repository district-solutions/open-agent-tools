# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/otb/generate.py

Prompts

```
['run generate.py to produce LLM responses for the OTBench dataset using a specified model', 'run generate.py with --run_locally to auto-start a vLLM server and generate responses', 'run generate.py with --enable_nothink to disable reasoning mode for Qwen3 models', 'run generate.py with --temperature to control response randomness for the LLM model', 'run generate.py with --multiprocessing to parallelize LLM response generation across dataset rows', 'install the otbench package and its dependencies using pip from the setup.py configuration', 'read a requirements.txt file and return a list of dependency strings skipping comments and blank lines', 'discover and include the otbench and otb_creation packages and their subpackages using setuptools find_packages', 'register the otbench console script entry point that maps to the otbench.cli main function', 'review the setup.py configuration for the otbench package including version, packages, and entry points', 'call an LLM model with a prompt, temperature, and max tokens using the call_llm function', 'get an OpenAI client for a given model name using the get_client function', 'load a HuggingFace tokenizer for a model name using the model_to_tokenizer function', 'compute overthinking and underthinking macro accuracy, score, tokens, and F1 from a results DataFrame', 'use the MAGISTRAL_PROMPT system prompt template to enforce a thinking process with <think> tags']
```

Usage

```
{'run_generate_llm_responses': 'run generate.py to produce LLM responses for the OTBench dataset using a specified model', 'run_generate_locally_with_vllm': 'run generate.py with --run_locally to auto-start a vLLM server and generate responses', 'run_generate_nothink_mode': 'run generate.py with --enable_nothink to disable reasoning mode for Qwen3 models', 'run_generate_custom_temperature': 'run generate.py with --temperature to control response randomness for the LLM model', 'run_generate_multiprocessed': 'run generate.py with --multiprocessing to parallelize LLM response generation across dataset rows'}
```

## File: facebookresearch_ram/projects/otb/setup.py

Prompts

```
['run generate.py to produce LLM responses for the OTBench dataset using a specified model', 'run generate.py with --run_locally to auto-start a vLLM server and generate responses', 'run generate.py with --enable_nothink to disable reasoning mode for Qwen3 models', 'run generate.py with --temperature to control response randomness for the LLM model', 'run generate.py with --multiprocessing to parallelize LLM response generation across dataset rows', 'install the otbench package and its dependencies using pip from the setup.py configuration', 'read a requirements.txt file and return a list of dependency strings skipping comments and blank lines', 'discover and include the otbench and otb_creation packages and their subpackages using setuptools find_packages', 'register the otbench console script entry point that maps to the otbench.cli main function', 'review the setup.py configuration for the otbench package including version, packages, and entry points', 'call an LLM model with a prompt, temperature, and max tokens using the call_llm function', 'get an OpenAI client for a given model name using the get_client function', 'load a HuggingFace tokenizer for a model name using the model_to_tokenizer function', 'compute overthinking and underthinking macro accuracy, score, tokens, and F1 from a results DataFrame', 'use the MAGISTRAL_PROMPT system prompt template to enforce a thinking process with <think> tags']
```

Usage

```
{'install_otbench_package': 'install the otbench package and its dependencies using pip from the setup.py configuration', 'read_requirements_file': 'read a requirements.txt file and return a list of dependency strings skipping comments and blank lines', 'discover_otbench_packages': 'discover and include the otbench and otb_creation packages and their subpackages using setuptools find_packages', 'register_otbench_cli': 'register the otbench console script entry point that maps to the otbench.cli main function', 'review_setup_config': 'review the setup.py configuration for the otbench package including version, packages, and entry points'}
```

## File: facebookresearch_ram/projects/otb/utils.py

Prompts

```
['run generate.py to produce LLM responses for the OTBench dataset using a specified model', 'run generate.py with --run_locally to auto-start a vLLM server and generate responses', 'run generate.py with --enable_nothink to disable reasoning mode for Qwen3 models', 'run generate.py with --temperature to control response randomness for the LLM model', 'run generate.py with --multiprocessing to parallelize LLM response generation across dataset rows', 'install the otbench package and its dependencies using pip from the setup.py configuration', 'read a requirements.txt file and return a list of dependency strings skipping comments and blank lines', 'discover and include the otbench and otb_creation packages and their subpackages using setuptools find_packages', 'register the otbench console script entry point that maps to the otbench.cli main function', 'review the setup.py configuration for the otbench package including version, packages, and entry points', 'call an LLM model with a prompt, temperature, and max tokens using the call_llm function', 'get an OpenAI client for a given model name using the get_client function', 'load a HuggingFace tokenizer for a model name using the model_to_tokenizer function', 'compute overthinking and underthinking macro accuracy, score, tokens, and F1 from a results DataFrame', 'use the MAGISTRAL_PROMPT system prompt template to enforce a thinking process with <think> tags']
```

Usage

```
{'call_llm': 'call an LLM model with a prompt, temperature, and max tokens using the call_llm function', 'get_client': 'get an OpenAI client for a given model name using the get_client function', 'model_to_tokenizer': 'load a HuggingFace tokenizer for a model name using the model_to_tokenizer function', 'format_metrics': 'compute overthinking and underthinking macro accuracy, score, tokens, and F1 from a results DataFrame', 'MAGISTRAL_PROMPT': 'use the MAGISTRAL_PROMPT system prompt template to enforce a thinking process with <think> tags'}
```

