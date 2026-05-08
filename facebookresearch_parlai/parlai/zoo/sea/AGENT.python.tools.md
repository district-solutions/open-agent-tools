# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/zoo/sea/bart_base.py

Prompts

```
['download the vanilla BART-Base 400M parameter SEA model to the Parlai model directory', 'check if the BART-Base SEA model is already built before downloading', 'get the model directory path for the BART-Base SEA model using get_model_dir', 'download model files with a specific version using download_models from Parlai build_data', 'review the download function to understand how BART-Base SEA models are fetched and cached', 'download the BART-Large 400m FiD model for search engine augmented dialogue', 'summarize the BART FiD SQSE module that generates search queries to retrieve documents', 'test the download function to verify it downloads the model only when not already built', 'refactor the download function to support configurable model version and file names', 'download the BART-Large 400m parameter model for generating search queries in a conversation', 'summarize the BART search query generation module and its model download logic']
```

Usage

```
{'download_bart_base_model': 'download the vanilla BART-Base 400M parameter SEA model to the Parlai model directory', 'check_model_built': 'check if the BART-Base SEA model is already built before downloading', 'get_model_directory': 'get the model directory path for the BART-Base SEA model using get_model_dir', 'download_models_with_version': 'download model files with a specific version using download_models from Parlai build_data', 'review_download_function': 'review the download function to understand how BART-Base SEA models are fetched and cached'}
```

## File: facebookresearch_parlai/parlai/zoo/sea/bart_fid_sqse.py

Prompts

```
['download the vanilla BART-Base 400M parameter SEA model to the Parlai model directory', 'check if the BART-Base SEA model is already built before downloading', 'get the model directory path for the BART-Base SEA model using get_model_dir', 'download model files with a specific version using download_models from Parlai build_data', 'review the download function to understand how BART-Base SEA models are fetched and cached', 'download the BART-Large 400m FiD model for search engine augmented dialogue', 'summarize the BART FiD SQSE module that generates search queries to retrieve documents', 'test the download function to verify it downloads the model only when not already built', 'refactor the download function to support configurable model version and file names', 'download the BART-Large 400m parameter model for generating search queries in a conversation', 'summarize the BART search query generation module and its model download logic']
```

Usage

```
{'download_bart_fid_model': 'download the BART-Large 400m FiD model for search engine augmented dialogue', 'review_download_function': 'review the download function that checks if the BART FiD model is already built before downloading', 'summarize_bart_fid_module': 'summarize the BART FiD SQSE module that generates search queries to retrieve documents', 'test_download_function': 'test the download function to verify it downloads the model only when not already built', 'refactor_download_function': 'refactor the download function to support configurable model version and file names'}
```

## File: facebookresearch_parlai/parlai/zoo/sea/bart_sq_gen.py

Prompts

```
['download the vanilla BART-Base 400M parameter SEA model to the Parlai model directory', 'check if the BART-Base SEA model is already built before downloading', 'get the model directory path for the BART-Base SEA model using get_model_dir', 'download model files with a specific version using download_models from Parlai build_data', 'review the download function to understand how BART-Base SEA models are fetched and cached', 'download the BART-Large 400m FiD model for search engine augmented dialogue', 'summarize the BART FiD SQSE module that generates search queries to retrieve documents', 'test the download function to verify it downloads the model only when not already built', 'refactor the download function to support configurable model version and file names', 'download the BART-Large 400m parameter model for generating search queries in a conversation', 'summarize the BART search query generation module and its model download logic']
```

Usage

```
{'download_bart_sq_gen_model': 'download the BART-Large 400m parameter model for generating search queries in a conversation', 'review_download_function': 'review the download function to check if the BART model is already built before downloading', 'summarize_bart_sq_gen_module': 'summarize the BART search query generation module and its model download logic', 'test_download_function': 'test the download function with a custom datapath to fetch the BART model', 'refactor_download_function': 'refactor the download function to support multiple model versions or alternative model types'}
```

