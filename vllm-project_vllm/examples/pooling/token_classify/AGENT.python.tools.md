# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/pooling/token_classify/forced_alignment_offline.py

Prompts

```
['run the forced alignment CLI with vLLM to align audio and reference text', 'build a forced alignment prompt from a list of words with timestamp tokens', 'parse command line arguments for vLLM forced alignment with model and engine defaults', 'encode audio and text input using vLLM LLM with pooling_task token_classify', 'extract word-level start and end timestamps from model logits and predictions', 'create an LLM instance for token classification using vLLM with pooling runner and NeuroBERT-NER model', 'run offline named entity recognition inference on sample prompts using token classification pooling task', 'parse command-line arguments with FlexibleArgumentParser and EngineArgs defaults for vLLM model configuration', 'tokenize input prompts and map model logits to named entity labels using id2label mapping', 'retrieve tokenizer and model configuration including id2label map from the vLLM LLM engine instance', 'post an HTTP request to the vLLM pooling API endpoint with a model name and input text', 'run the NER online example script to classify tokens in a sentence using a vLLM pooling server']
```

Usage

```
{'run_forced_alignment_cli': 'run the forced alignment CLI with vLLM to align audio and reference text', 'build_prompt_for_alignment': 'build a forced alignment prompt from a list of words with timestamp tokens', 'parse_cli_args_for_vllm': 'parse command line arguments for vLLM forced alignment with model and engine defaults', 'encode_audio_with_token_classification': 'encode audio and text input using vLLM LLM with pooling_task token_classify', 'extract_word_timestamps_from_logits': 'extract word-level start and end timestamps from model logits and predictions'}
```

## File: vllm-project_vllm/examples/pooling/token_classify/ner_offline.py

Prompts

```
['run the forced alignment CLI with vLLM to align audio and reference text', 'build a forced alignment prompt from a list of words with timestamp tokens', 'parse command line arguments for vLLM forced alignment with model and engine defaults', 'encode audio and text input using vLLM LLM with pooling_task token_classify', 'extract word-level start and end timestamps from model logits and predictions', 'create an LLM instance for token classification using vLLM with pooling runner and NeuroBERT-NER model', 'run offline named entity recognition inference on sample prompts using token classification pooling task', 'parse command-line arguments with FlexibleArgumentParser and EngineArgs defaults for vLLM model configuration', 'tokenize input prompts and map model logits to named entity labels using id2label mapping', 'retrieve tokenizer and model configuration including id2label map from the vLLM LLM engine instance', 'post an HTTP request to the vLLM pooling API endpoint with a model name and input text', 'run the NER online example script to classify tokens in a sentence using a vLLM pooling server']
```

Usage

```
{'create_llm_token_classifier': 'create an LLM instance for token classification using vLLM with pooling runner and NeuroBERT-NER model', 'run_ner_inference': 'run offline named entity recognition inference on sample prompts using token classification pooling task', 'parse_cli_args': 'parse command-line arguments with FlexibleArgumentParser and EngineArgs defaults for vLLM model configuration', 'tokenize_and_predict': 'tokenize input prompts and map model logits to named entity labels using id2label mapping', 'get_tokenizer_and_config': 'retrieve tokenizer and model configuration including id2label map from the vLLM LLM engine instance'}
```

## File: vllm-project_vllm/examples/pooling/token_classify/ner_online.py

Prompts

```
['run the forced alignment CLI with vLLM to align audio and reference text', 'build a forced alignment prompt from a list of words with timestamp tokens', 'parse command line arguments for vLLM forced alignment with model and engine defaults', 'encode audio and text input using vLLM LLM with pooling_task token_classify', 'extract word-level start and end timestamps from model logits and predictions', 'create an LLM instance for token classification using vLLM with pooling runner and NeuroBERT-NER model', 'run offline named entity recognition inference on sample prompts using token classification pooling task', 'parse command-line arguments with FlexibleArgumentParser and EngineArgs defaults for vLLM model configuration', 'tokenize input prompts and map model logits to named entity labels using id2label mapping', 'retrieve tokenizer and model configuration including id2label map from the vLLM LLM engine instance', 'post an HTTP request to the vLLM pooling API endpoint with a model name and input text', 'run the NER online example script to classify tokens in a sentence using a vLLM pooling server']
```

Usage

```
{'run_ner_inference': 'run a vLLM pooling server and send an HTTP POST request to perform named entity recognition', 'post_http_request': 'post an HTTP request to the vLLM pooling API endpoint with a model name and input text', 'parse_cli_args': 'parse command line arguments for host, port, and model name for the NER inference script', 'tokenize_and_predict': 'tokenize input text and map model predictions to named entity labels using a label map', 'run_ner_online': 'run the NER online example script to classify tokens in a sentence using a vLLM pooling server'}
```

