# Agent Python Tools

- repo: facebookresearch/reasonir
- repo_uri: https://github.com/facebookresearch/reasonir

## File: facebookresearch_reasonir/evaluation/rag/gpqa/src/utils/cache_utils.py

Prompts

```
['create a Cache instance with a config object to load or initialize search and URL caches', 'get the search cache directory path based on the search engine and query rewriting settings', 'get the chain-of-thought query cache directory path for a given model and search engine', 'save the search cache, URL cache, and optional query cache dictionaries to JSON files on disk', 'initialize a Cache object that automatically loads existing JSON cache files or creates empty caches', 'run a Hydra-configured task function using the hydra_runner decorator with config path and name', 'create a structured config schema and register it with hydra_runner for validation and default values', 'register an OmegaConf resolver that detects GPU name from CUDA compute capability using pynvml', 'register an OmegaConf multiply resolver to interpolate two config values together', 'review the hydra_runner decorator that wraps task functions with Hydra config parsing and overrides', 'test if two LaTeX math strings are equivalent after normalization and stripping', 'summarize how _strip_string normalizes LaTeX math expressions by removing units, spaces, and fixing fractions', 'review the _fix_fracs function that normalizes malformed LaTeX fraction notation into proper braces', 'refactor the _fix_a_slash_b function to convert integer slash fractions to LaTeX frac format', 'test the _fix_sqrt function that wraps bare characters in braces for LaTeX square root notation']
```

Usage

```
{'init_cache_class': 'create a Cache instance with a config object to load or initialize search and URL caches', 'get_search_cache_dirname': 'get the search cache directory path based on the search engine and query rewriting settings', 'get_cot_query_cache_dirname': 'get the chain-of-thought query cache directory path for a given model and search engine', 'save_caches': 'save the search cache, URL cache, and optional query cache dictionaries to JSON files on disk', 'load_existing_caches': 'initialize a Cache object that automatically loads existing JSON cache files or creates empty caches'}
```

## File: facebookresearch_reasonir/evaluation/rag/gpqa/src/utils/hydra_runner.py

Prompts

```
['create a Cache instance with a config object to load or initialize search and URL caches', 'get the search cache directory path based on the search engine and query rewriting settings', 'get the chain-of-thought query cache directory path for a given model and search engine', 'save the search cache, URL cache, and optional query cache dictionaries to JSON files on disk', 'initialize a Cache object that automatically loads existing JSON cache files or creates empty caches', 'run a Hydra-configured task function using the hydra_runner decorator with config path and name', 'create a structured config schema and register it with hydra_runner for validation and default values', 'register an OmegaConf resolver that detects GPU name from CUDA compute capability using pynvml', 'register an OmegaConf multiply resolver to interpolate two config values together', 'review the hydra_runner decorator that wraps task functions with Hydra config parsing and overrides', 'test if two LaTeX math strings are equivalent after normalization and stripping', 'summarize how _strip_string normalizes LaTeX math expressions by removing units, spaces, and fixing fractions', 'review the _fix_fracs function that normalizes malformed LaTeX fraction notation into proper braces', 'refactor the _fix_a_slash_b function to convert integer slash fractions to LaTeX frac format', 'test the _fix_sqrt function that wraps bare characters in braces for LaTeX square root notation']
```

Usage

```
{'run_hydra_configured_task': 'run a Hydra-configured task function using the hydra_runner decorator with config path and name', 'create_hydra_config_schema': 'create a structured config schema and register it with hydra_runner for validation and default values', 'register_gpu_name_resolver': 'register an OmegaConf resolver that detects GPU name from CUDA compute capability using pynvml', 'register_multiply_resolver': 'register an OmegaConf multiply resolver to interpolate two config values together', 'review_hydra_runner_decorator': 'review the hydra_runner decorator that wraps task functions with Hydra config parsing and overrides'}
```

## File: facebookresearch_reasonir/evaluation/rag/gpqa/src/utils/math_equivalence.py

Prompts

```
['create a Cache instance with a config object to load or initialize search and URL caches', 'get the search cache directory path based on the search engine and query rewriting settings', 'get the chain-of-thought query cache directory path for a given model and search engine', 'save the search cache, URL cache, and optional query cache dictionaries to JSON files on disk', 'initialize a Cache object that automatically loads existing JSON cache files or creates empty caches', 'run a Hydra-configured task function using the hydra_runner decorator with config path and name', 'create a structured config schema and register it with hydra_runner for validation and default values', 'register an OmegaConf resolver that detects GPU name from CUDA compute capability using pynvml', 'register an OmegaConf multiply resolver to interpolate two config values together', 'review the hydra_runner decorator that wraps task functions with Hydra config parsing and overrides', 'test if two LaTeX math strings are equivalent after normalization and stripping', 'summarize how _strip_string normalizes LaTeX math expressions by removing units, spaces, and fixing fractions', 'review the _fix_fracs function that normalizes malformed LaTeX fraction notation into proper braces', 'refactor the _fix_a_slash_b function to convert integer slash fractions to LaTeX frac format', 'test the _fix_sqrt function that wraps bare characters in braces for LaTeX square root notation']
```

Usage

```
{'test_is_equiv': 'test if two LaTeX math strings are equivalent after normalization and stripping', 'summarize_strip_string': 'summarize how _strip_string normalizes LaTeX math expressions by removing units, spaces, and fixing fractions', 'review_fix_fracs': 'review the _fix_fracs function that normalizes malformed LaTeX fraction notation into proper braces', 'refactor_fix_a_slash_b': 'refactor the _fix_a_slash_b function to convert integer slash fractions to LaTeX frac format', 'test_fix_sqrt': 'test the _fix_sqrt function that wraps bare characters in braces for LaTeX square root notation'}
```

