# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/evolla/test_modeling_evolla.py

Prompts

```
['create an EvollaModelTester instance to generate test configs and input tensors for the Evolla model', 'run prepare_config_and_inputs to generate EvollaConfig and protein plus text input tensors', 'test the EvollaModel forward pass by creating the model and verifying output hidden state shapes', 'test the EvollaForProteinText2Text generate method with protein and text inputs', 'run end-to-end protein reasoning inference using EvollaForProteinText2Text with BitsAndBytes 4-bit quantization', 'test the EvollaProcessor class to verify protein input tokenization with messages and amino acid sequences', 'run the EvollaProcessorTest suite to validate processor output keys match expected protein and text input tensors', 'prepare protein input dictionaries with amino acid and foldseek sequences for single, pair, long, short, or empty types', 'prepare a protein dictionary and chat messages with expected tokenized output tensors for the EvollaProcessor', 'get the protein tokenizer from an AutoProcessor loaded from a pretrained model directory with fix_mistral_regex enabled']
```

Usage

```
{'create_EvollaModelTester': 'create an EvollaModelTester instance to generate test configs and input tensors for the Evolla model', 'run_prepare_config_and_inputs': 'run prepare_config_and_inputs to generate EvollaConfig and protein plus text input tensors', 'test_create_and_check_model': 'test the EvollaModel forward pass by creating the model and verifying output hidden state shapes', 'test_create_and_check_model_gen': 'test the EvollaForProteinText2Text generate method with protein and text inputs', 'run_inference_natural_language_protein_reasoning': 'run end-to-end protein reasoning inference using EvollaForProteinText2Text with BitsAndBytes 4-bit quantization'}
```

## File: huggingface_transformers/tests/models/evolla/test_processing_evolla.py

Prompts

```
['create an EvollaModelTester instance to generate test configs and input tensors for the Evolla model', 'run prepare_config_and_inputs to generate EvollaConfig and protein plus text input tensors', 'test the EvollaModel forward pass by creating the model and verifying output hidden state shapes', 'test the EvollaForProteinText2Text generate method with protein and text inputs', 'run end-to-end protein reasoning inference using EvollaForProteinText2Text with BitsAndBytes 4-bit quantization', 'test the EvollaProcessor class to verify protein input tokenization with messages and amino acid sequences', 'run the EvollaProcessorTest suite to validate processor output keys match expected protein and text input tensors', 'prepare protein input dictionaries with amino acid and foldseek sequences for single, pair, long, short, or empty types', 'prepare a protein dictionary and chat messages with expected tokenized output tensors for the EvollaProcessor', 'get the protein tokenizer from an AutoProcessor loaded from a pretrained model directory with fix_mistral_regex enabled']
```

Usage

```
{'test_EvollaProcessor': 'test the EvollaProcessor class to verify protein input tokenization with messages and amino acid sequences', 'run_EvollaProcessorTest': 'run the EvollaProcessorTest suite to validate processor output keys match expected protein and text input tensors', 'prepare_protein_inputs': 'prepare protein input dictionaries with amino acid and foldseek sequences for single, pair, long, short, or empty types', 'prepare_input_and_expected_output': 'prepare a protein dictionary and chat messages with expected tokenized output tensors for the EvollaProcessor', 'get_protein_tokenizer': 'get the protein tokenizer from an AutoProcessor loaded from a pretrained model directory with fix_mistral_regex enabled'}
```

