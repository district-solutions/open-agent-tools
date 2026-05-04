# Agent Python Tools

- repo: facebookresearch/genre
- repo_uri: https://github.com/facebookresearch/genre

## File: facebookresearch_genre/scripts_genre/convert_fairseq_huggingface.py

Prompts

```
['convert a Fairseq GENRE model to a HuggingFace PyTorch BartForConditionalGeneration model', 'convert a Fairseq GENRE model to a HuggingFace Flax BartForConditionalGeneration model', 'convert a Fairseq GENRE model to a HuggingFace TensorFlow TFBartForConditionalGeneration model', 'remove ignore keys like encoder.version and decoder.output_projection.weight from a PyTorch state dict', 'create a Linear layer from an embedding weight tensor with matching vocab and embedding size', 'convert a KILT dataset to Fairseq format by extracting provenance titles with bleu score above 0.5', 'run the script with an input KILT JSONL filename and output directory path to convert datasets', 'create an input representation from a KILT document using START_ENT and END_ENT delimiters with max length 384', 'extract template questions from KILT document metadata and pair them with provenance titles as source-target pairs', 'sanitize carriage returns and newlines in source and target data before writing to output files', 'run the evaluate_kilt_dataset script to evaluate a GENRE model on KILT datasets and compute F1, precision, recall metrics', 'run the evaluate_kilt_dataset function with a trie to constrain GENRE model decoding to candidate entities', 'run the evaluate_kilt_dataset function with free_generation enabled to disable constrained decoding and allow open generation', 'run the evaluate_kilt_dataset function with a custom batch size to process multiple KILT dataset documents at once', 'run the evaluate_kilt_dataset function with candidates enabled to use per-document candidate lists for entity prediction']
```

Usage

```
{'convert_fairseq_to_hf_pytorch': 'convert a Fairseq GENRE model to a HuggingFace PyTorch BartForConditionalGeneration model', 'convert_fairseq_to_hf_flax': 'convert a Fairseq GENRE model to a HuggingFace Flax BartForConditionalGeneration model', 'convert_fairseq_to_hf_tensorflow': 'convert a Fairseq GENRE model to a HuggingFace TensorFlow TFBartForConditionalGeneration model', 'remove_ignore_keys_state_dict': 'remove ignore keys like encoder.version and decoder.output_projection.weight from a PyTorch state dict', 'make_linear_from_emb': 'create a Linear layer from an embedding weight tensor with matching vocab and embedding size'}
```

## File: facebookresearch_genre/scripts_genre/convert_kilt_to_fairseq.py

Prompts

```
['convert a Fairseq GENRE model to a HuggingFace PyTorch BartForConditionalGeneration model', 'convert a Fairseq GENRE model to a HuggingFace Flax BartForConditionalGeneration model', 'convert a Fairseq GENRE model to a HuggingFace TensorFlow TFBartForConditionalGeneration model', 'remove ignore keys like encoder.version and decoder.output_projection.weight from a PyTorch state dict', 'create a Linear layer from an embedding weight tensor with matching vocab and embedding size', 'convert a KILT dataset to Fairseq format by extracting provenance titles with bleu score above 0.5', 'run the script with an input KILT JSONL filename and output directory path to convert datasets', 'create an input representation from a KILT document using START_ENT and END_ENT delimiters with max length 384', 'extract template questions from KILT document metadata and pair them with provenance titles as source-target pairs', 'sanitize carriage returns and newlines in source and target data before writing to output files', 'run the evaluate_kilt_dataset script to evaluate a GENRE model on KILT datasets and compute F1, precision, recall metrics', 'run the evaluate_kilt_dataset function with a trie to constrain GENRE model decoding to candidate entities', 'run the evaluate_kilt_dataset function with free_generation enabled to disable constrained decoding and allow open generation', 'run the evaluate_kilt_dataset function with a custom batch size to process multiple KILT dataset documents at once', 'run the evaluate_kilt_dataset function with candidates enabled to use per-document candidate lists for entity prediction']
```

Usage

```
{'convert_kilt_to_fairseq_dataset': 'convert a KILT dataset to Fairseq format by extracting provenance titles with bleu score above 0.5', 'run_convert_kilt_cli': 'run the script with an input KILT JSONL filename and output directory path to convert datasets', 'create_input_with_delimiters': 'create an input representation from a KILT document using START_ENT and END_ENT delimiters with max length 384', 'extract_template_questions': 'extract template questions from KILT document metadata and pair them with provenance titles as source-target pairs', 'sanitize_newlines_in_output': 'sanitize carriage returns and newlines in source and target data before writing to output files'}
```

## File: facebookresearch_genre/scripts_genre/evaluate_kilt_dataset.py

Prompts

```
['convert a Fairseq GENRE model to a HuggingFace PyTorch BartForConditionalGeneration model', 'convert a Fairseq GENRE model to a HuggingFace Flax BartForConditionalGeneration model', 'convert a Fairseq GENRE model to a HuggingFace TensorFlow TFBartForConditionalGeneration model', 'remove ignore keys like encoder.version and decoder.output_projection.weight from a PyTorch state dict', 'create a Linear layer from an embedding weight tensor with matching vocab and embedding size', 'convert a KILT dataset to Fairseq format by extracting provenance titles with bleu score above 0.5', 'run the script with an input KILT JSONL filename and output directory path to convert datasets', 'create an input representation from a KILT document using START_ENT and END_ENT delimiters with max length 384', 'extract template questions from KILT document metadata and pair them with provenance titles as source-target pairs', 'sanitize carriage returns and newlines in source and target data before writing to output files', 'run the evaluate_kilt_dataset script to evaluate a GENRE model on KILT datasets and compute F1, precision, recall metrics', 'run the evaluate_kilt_dataset function with a trie to constrain GENRE model decoding to candidate entities', 'run the evaluate_kilt_dataset function with free_generation enabled to disable constrained decoding and allow open generation', 'run the evaluate_kilt_dataset function with a custom batch size to process multiple KILT dataset documents at once', 'run the evaluate_kilt_dataset function with candidates enabled to use per-document candidate lists for entity prediction']
```

Usage

```
{'run_kilt_evaluation': 'run the evaluate_kilt_dataset script to evaluate a GENRE model on KILT datasets and compute F1, precision, recall metrics', 'run_constrained_decoding': 'run the evaluate_kilt_dataset function with a trie to constrain GENRE model decoding to candidate entities', 'run_free_generation': 'run the evaluate_kilt_dataset function with free_generation enabled to disable constrained decoding and allow open generation', 'run_batch_evaluation': 'run the evaluate_kilt_dataset function with a custom batch size to process multiple KILT dataset documents at once', 'run_candidate_evaluation': 'run the evaluate_kilt_dataset function with candidates enabled to use per-document candidate lists for entity prediction'}
```

