# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mra/convert_mra_pytorch_to_pytorch.py

Prompts

```
['convert an MRA checkpoint from the original repository to a HuggingFace PyTorch model', 'rename model checkpoint keys from the original MRA repository format to HuggingFace Transformers format', 'transform an original MRA state dict into a HuggingFace-compatible state dict with renamed keys', 'create a MraForMaskedLM model by loading a converted checkpoint from the original MRA repository', 'run the MRA checkpoint conversion CLI with a pytorch model path, config file, and output path', 'build an MraModel instance from MraConfig for base transformer encoding', 'create MraForMaskedLM for masked language modeling with vocab prediction', 'create MraForSequenceClassification for GLUE-style text classification tasks', 'create MraForTokenClassification for NER and token-level labeling', 'create MraForQuestionAnswering for extractive QA with start and end logits']
```

Usage

```
{'convert_mra_checkpoint': 'convert an MRA checkpoint from the original repository to a HuggingFace PyTorch model', 'rename_key': 'rename model checkpoint keys from the original MRA repository format to HuggingFace Transformers format', 'convert_checkpoint_helper': 'transform an original MRA state dict into a HuggingFace-compatible state dict with renamed keys', 'create_mra_model_from_checkpoint': 'create a MraForMaskedLM model by loading a converted checkpoint from the original MRA repository', 'run_mra_checkpoint_conversion_cli': 'run the MRA checkpoint conversion CLI with a pytorch model path, config file, and output path'}
```

## File: huggingface_transformers/src/transformers/models/mra/modeling_mra.py

Prompts

```
['convert an MRA checkpoint from the original repository to a HuggingFace PyTorch model', 'rename model checkpoint keys from the original MRA repository format to HuggingFace Transformers format', 'transform an original MRA state dict into a HuggingFace-compatible state dict with renamed keys', 'create a MraForMaskedLM model by loading a converted checkpoint from the original MRA repository', 'run the MRA checkpoint conversion CLI with a pytorch model path, config file, and output path', 'build an MraModel instance from MraConfig for base transformer encoding', 'create MraForMaskedLM for masked language modeling with vocab prediction', 'create MraForSequenceClassification for GLUE-style text classification tasks', 'create MraForTokenClassification for NER and token-level labeling', 'create MraForQuestionAnswering for extractive QA with start and end logits']
```

Usage

```
{'build_mra_model': 'build an MraModel instance from MraConfig for base transformer encoding', 'create_mra_masked_lm': 'create MraForMaskedLM for masked language modeling with vocab prediction', 'create_mra_sequence_classification': 'create MraForSequenceClassification for GLUE-style text classification tasks', 'create_mra_token_classification': 'create MraForTokenClassification for NER and token-level labeling', 'create_mra_question_answering': 'create MraForQuestionAnswering for extractive QA with start and end logits'}
```

