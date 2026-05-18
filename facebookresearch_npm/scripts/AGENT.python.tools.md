# Agent Python Tools

- repo: facebookresearch/npm
- repo_uri: https://github.com/facebookresearch/npm

## File: facebookresearch_npm/scripts/clm_prompt.py

Prompts

```
['run the CLM prompt evaluation script with a specified model and dataset using argparse CLI', 'generate text completions from a list of prompts using the Model class generate method', 'load a pretrained causal language model like GPT-Neo or OPT and convert it to int8 on GPU', 'normalize answer text by lowercasing, removing punctuation, articles, and extra whitespace', 'calculate exact match accuracy between model predictions and reference answers with optional ngram grouping', 'run the script with --closed to generate a closed-book QA accuracy comparison table', 'run the script with --open to generate an open-book QA exact match comparison table', 'load predictions from a JSONL output file into a list of dictionaries', 'compute the macro exact match score grouped by n-gram categories with optional filtering', 'compute per-dataset accuracy metrics for open QA datasets using normalized answers', 'run the NPMDemo predict method to fill in masked text spans using the NPM model', 'run the NPMDemo generate method to autoregressively generate text from a prompt using NPM', 'run the NPMDemo bm25_search method to retrieve relevant text blocks matching a query', 'run the NPMDemo class to initialize an NPM model with a DataStore and stopword mask', 'run the main demo script to predict, generate, and search text using NPM via argparse CLI', 'run NPM model evaluation on a dataset with a specified corpus datastore and k nearest neighbors', 'run open-set NPM evaluation on a task dataset and save predictions to a results file', 'run restricted NPM evaluation with a limited datastore and custom temperature settings', 'run NPMSingle model evaluation on a dataset using the single model variant', 'run NPM evaluation in debug mode filtering to examples where BM25 retrieval is successful', 'quantize a PyTorch model to int8 and move it to a CUDA GPU device', 'get the memory footprint in bytes of a PyTorch model including optional buffer tensors', 'assert two PyTorch tensors are approximately close within a tolerance and allowed mismatch count', 'create an Int8 quantized linear layer that dequantizes weights to fp16 during the forward pass', 'recursively replace all nn.Linear layers in a model with Int8 quantized versions except lm_head']
```

Usage

```
{'run_clm_prompt_evaluation': 'run the CLM prompt evaluation script with a specified model and dataset using argparse CLI', 'generate_text_with_model': 'generate text completions from a list of prompts using the Model class generate method', 'load_model_with_int8': 'load a pretrained causal language model like GPT-Neo or OPT and convert it to int8 on GPU', 'normalize_answer_text': 'normalize answer text by lowercasing, removing punctuation, articles, and extra whitespace', 'calc_accuracy_for_predictions': 'calculate exact match accuracy between model predictions and reference answers with optional ngram grouping'}
```

## File: facebookresearch_npm/scripts/create_table.py

Prompts

```
['run the CLM prompt evaluation script with a specified model and dataset using argparse CLI', 'generate text completions from a list of prompts using the Model class generate method', 'load a pretrained causal language model like GPT-Neo or OPT and convert it to int8 on GPU', 'normalize answer text by lowercasing, removing punctuation, articles, and extra whitespace', 'calculate exact match accuracy between model predictions and reference answers with optional ngram grouping', 'run the script with --closed to generate a closed-book QA accuracy comparison table', 'run the script with --open to generate an open-book QA exact match comparison table', 'load predictions from a JSONL output file into a list of dictionaries', 'compute the macro exact match score grouped by n-gram categories with optional filtering', 'compute per-dataset accuracy metrics for open QA datasets using normalized answers', 'run the NPMDemo predict method to fill in masked text spans using the NPM model', 'run the NPMDemo generate method to autoregressively generate text from a prompt using NPM', 'run the NPMDemo bm25_search method to retrieve relevant text blocks matching a query', 'run the NPMDemo class to initialize an NPM model with a DataStore and stopword mask', 'run the main demo script to predict, generate, and search text using NPM via argparse CLI', 'run NPM model evaluation on a dataset with a specified corpus datastore and k nearest neighbors', 'run open-set NPM evaluation on a task dataset and save predictions to a results file', 'run restricted NPM evaluation with a limited datastore and custom temperature settings', 'run NPMSingle model evaluation on a dataset using the single model variant', 'run NPM evaluation in debug mode filtering to examples where BM25 retrieval is successful', 'quantize a PyTorch model to int8 and move it to a CUDA GPU device', 'get the memory footprint in bytes of a PyTorch model including optional buffer tensors', 'assert two PyTorch tensors are approximately close within a tolerance and allowed mismatch count', 'create an Int8 quantized linear layer that dequantizes weights to fp16 during the forward pass', 'recursively replace all nn.Linear layers in a model with Int8 quantized versions except lm_head']
```

Usage

```
{'run_closed_table': 'run the script with --closed to generate a closed-book QA accuracy comparison table', 'run_open_table': 'run the script with --open to generate an open-book QA exact match comparison table', 'load_output_file': 'load predictions from a JSONL output file into a list of dictionaries', 'compute_macro_em': 'compute the macro exact match score grouped by n-gram categories with optional filtering', 'get_row': 'compute per-dataset accuracy metrics for open QA datasets using normalized answers'}
```

## File: facebookresearch_npm/scripts/demo.py

Prompts

```
['run the CLM prompt evaluation script with a specified model and dataset using argparse CLI', 'generate text completions from a list of prompts using the Model class generate method', 'load a pretrained causal language model like GPT-Neo or OPT and convert it to int8 on GPU', 'normalize answer text by lowercasing, removing punctuation, articles, and extra whitespace', 'calculate exact match accuracy between model predictions and reference answers with optional ngram grouping', 'run the script with --closed to generate a closed-book QA accuracy comparison table', 'run the script with --open to generate an open-book QA exact match comparison table', 'load predictions from a JSONL output file into a list of dictionaries', 'compute the macro exact match score grouped by n-gram categories with optional filtering', 'compute per-dataset accuracy metrics for open QA datasets using normalized answers', 'run the NPMDemo predict method to fill in masked text spans using the NPM model', 'run the NPMDemo generate method to autoregressively generate text from a prompt using NPM', 'run the NPMDemo bm25_search method to retrieve relevant text blocks matching a query', 'run the NPMDemo class to initialize an NPM model with a DataStore and stopword mask', 'run the main demo script to predict, generate, and search text using NPM via argparse CLI', 'run NPM model evaluation on a dataset with a specified corpus datastore and k nearest neighbors', 'run open-set NPM evaluation on a task dataset and save predictions to a results file', 'run restricted NPM evaluation with a limited datastore and custom temperature settings', 'run NPMSingle model evaluation on a dataset using the single model variant', 'run NPM evaluation in debug mode filtering to examples where BM25 retrieval is successful', 'quantize a PyTorch model to int8 and move it to a CUDA GPU device', 'get the memory footprint in bytes of a PyTorch model including optional buffer tensors', 'assert two PyTorch tensors are approximately close within a tolerance and allowed mismatch count', 'create an Int8 quantized linear layer that dequantizes weights to fp16 during the forward pass', 'recursively replace all nn.Linear layers in a model with Int8 quantized versions except lm_head']
```

Usage

```
{'run_NPMDemo_predict': 'run the NPMDemo predict method to fill in masked text spans using the NPM model', 'run_NPMDemo_generate': 'run the NPMDemo generate method to autoregressively generate text from a prompt using NPM', 'run_NPMDemo_bm25_search': 'run the NPMDemo bm25_search method to retrieve relevant text blocks matching a query', 'run_NPMDemo_init': 'run the NPMDemo class to initialize an NPM model with a DataStore and stopword mask', 'run_main_demo': 'run the main demo script to predict, generate, and search text using NPM via argparse CLI'}
```

## File: facebookresearch_npm/scripts/prompt.py

Prompts

```
['run the CLM prompt evaluation script with a specified model and dataset using argparse CLI', 'generate text completions from a list of prompts using the Model class generate method', 'load a pretrained causal language model like GPT-Neo or OPT and convert it to int8 on GPU', 'normalize answer text by lowercasing, removing punctuation, articles, and extra whitespace', 'calculate exact match accuracy between model predictions and reference answers with optional ngram grouping', 'run the script with --closed to generate a closed-book QA accuracy comparison table', 'run the script with --open to generate an open-book QA exact match comparison table', 'load predictions from a JSONL output file into a list of dictionaries', 'compute the macro exact match score grouped by n-gram categories with optional filtering', 'compute per-dataset accuracy metrics for open QA datasets using normalized answers', 'run the NPMDemo predict method to fill in masked text spans using the NPM model', 'run the NPMDemo generate method to autoregressively generate text from a prompt using NPM', 'run the NPMDemo bm25_search method to retrieve relevant text blocks matching a query', 'run the NPMDemo class to initialize an NPM model with a DataStore and stopword mask', 'run the main demo script to predict, generate, and search text using NPM via argparse CLI', 'run NPM model evaluation on a dataset with a specified corpus datastore and k nearest neighbors', 'run open-set NPM evaluation on a task dataset and save predictions to a results file', 'run restricted NPM evaluation with a limited datastore and custom temperature settings', 'run NPMSingle model evaluation on a dataset using the single model variant', 'run NPM evaluation in debug mode filtering to examples where BM25 retrieval is successful', 'quantize a PyTorch model to int8 and move it to a CUDA GPU device', 'get the memory footprint in bytes of a PyTorch model including optional buffer tensors', 'assert two PyTorch tensors are approximately close within a tolerance and allowed mismatch count', 'create an Int8 quantized linear layer that dequantizes weights to fp16 during the forward pass', 'recursively replace all nn.Linear layers in a model with Int8 quantized versions except lm_head']
```

Usage

```
{'run_npm_evaluation': 'run NPM model evaluation on a dataset with a specified corpus datastore and k nearest neighbors', 'run_open_set_evaluation': 'run open-set NPM evaluation on a task dataset and save predictions to a results file', 'run_restricted_evaluation': 'run restricted NPM evaluation with a limited datastore and custom temperature settings', 'run_single_model_evaluation': 'run NPMSingle model evaluation on a dataset using the single model variant', 'run_debug_evaluation': 'run NPM evaluation in debug mode filtering to examples where BM25 retrieval is successful'}
```

## File: facebookresearch_npm/scripts/util_clm.py

Prompts

```
['run the CLM prompt evaluation script with a specified model and dataset using argparse CLI', 'generate text completions from a list of prompts using the Model class generate method', 'load a pretrained causal language model like GPT-Neo or OPT and convert it to int8 on GPU', 'normalize answer text by lowercasing, removing punctuation, articles, and extra whitespace', 'calculate exact match accuracy between model predictions and reference answers with optional ngram grouping', 'run the script with --closed to generate a closed-book QA accuracy comparison table', 'run the script with --open to generate an open-book QA exact match comparison table', 'load predictions from a JSONL output file into a list of dictionaries', 'compute the macro exact match score grouped by n-gram categories with optional filtering', 'compute per-dataset accuracy metrics for open QA datasets using normalized answers', 'run the NPMDemo predict method to fill in masked text spans using the NPM model', 'run the NPMDemo generate method to autoregressively generate text from a prompt using NPM', 'run the NPMDemo bm25_search method to retrieve relevant text blocks matching a query', 'run the NPMDemo class to initialize an NPM model with a DataStore and stopword mask', 'run the main demo script to predict, generate, and search text using NPM via argparse CLI', 'run NPM model evaluation on a dataset with a specified corpus datastore and k nearest neighbors', 'run open-set NPM evaluation on a task dataset and save predictions to a results file', 'run restricted NPM evaluation with a limited datastore and custom temperature settings', 'run NPMSingle model evaluation on a dataset using the single model variant', 'run NPM evaluation in debug mode filtering to examples where BM25 retrieval is successful', 'quantize a PyTorch model to int8 and move it to a CUDA GPU device', 'get the memory footprint in bytes of a PyTorch model including optional buffer tensors', 'assert two PyTorch tensors are approximately close within a tolerance and allowed mismatch count', 'create an Int8 quantized linear layer that dequantizes weights to fp16 during the forward pass', 'recursively replace all nn.Linear layers in a model with Int8 quantized versions except lm_head']
```

Usage

```
{'convert_model_to_int8_on_gpu': 'quantize a PyTorch model to int8 and move it to a CUDA GPU device', 'get_memory_footprint': 'get the memory footprint in bytes of a PyTorch model including optional buffer tensors', 'assert_all_approx_close': 'assert two PyTorch tensors are approximately close within a tolerance and allowed mismatch count', 'QuantizedLinearInt8': 'create an Int8 quantized linear layer that dequantizes weights to fp16 during the forward pass', 'replace_linear_with_int8linear': 'recursively replace all nn.Linear layers in a model with Int8 quantized versions except lm_head'}
```

