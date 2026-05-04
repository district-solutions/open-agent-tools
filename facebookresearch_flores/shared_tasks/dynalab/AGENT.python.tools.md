# Agent Python Tools

- repo: facebookresearch/flores
- repo_uri: https://github.com/facebookresearch/flores

## File: facebookresearch_flores/shared_tasks/dynalab/handler.py

Prompts

```
['run the handle function to translate a batch of text samples via TorchServe', 'initialize the Handler to load a Fairseq translation model and SentencePiece tokenizer', 'preprocess translation samples into tensors with source tokens and target language prefix', 'run inference on preprocessed samples using the Fairseq sequence generator', 'postprocess inference output into signed JSON responses with translated text']
```

Usage

```
{'run_handle_translation': 'run the handle function to translate a batch of text samples via TorchServe', 'initialize_Handler_model': 'initialize the Handler to load a Fairseq translation model and SentencePiece tokenizer', 'preprocess_samples_for_inference': 'preprocess translation samples into tensors with source tokens and target language prefix', 'run_Handler_inference': 'run inference on preprocessed samples using the Fairseq sequence generator', 'postprocess_translation_output': 'postprocess inference output into signed JSON responses with translated text'}
```

