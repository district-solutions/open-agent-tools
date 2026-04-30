# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/esm/configuration_esm.py

Prompts

```
['create an EsmConfig instance for a standard ESM-1b language model with vocab size 33', 'create an EsmConfig instance configured as a folding model with esmfold_config and vocab_list', 'create a TrunkConfig with custom structure_module settings for the ESMFold backbone', 'create a StructureModuleConfig with custom IPA and resnet dimensions for protein folding', 'get the default amino-acid vocabulary list used by ESM folding models', 'convert an ESM checkpoint from fairseq to a HuggingFace PyTorch model', 'run the ESM-to-Transformers conversion CLI with model name and output path', 'convert an ESMFold v1 model checkpoint to HuggingFace EsmForProteinFolding format', 'convert an ESM model to HuggingFace format with a classification head for sequence classification', 'create an ESMFold-compatible tokenizer with special tokens for amino acid sequences', 'create an EsmModel transformer for protein sequence encoding with optional rotary embeddings', 'run EsmForMaskedLM to predict masked tokens in protein sequences', 'run EsmForSequenceClassification to classify protein sequences into labels', 'run EsmForTokenClassification to predict per-token protein annotations', 'predict protein residue contacts from attention maps using EsmModel', 'run EsmForProteinFolding forward pass on amino acid input sequences to predict 3D protein structures', 'infer protein 3D structure from amino acid sequence string and return PDB format output', 'convert EsmForProteinFolding output dictionary to PDB file string representation', 'fold multiple protein sequences into 3D structures and return list of PDB strings', 'compute per-residue plddt confidence scores and tm-score for predicted protein structures', 'create an EsmTokenizer instance from a vocab file for protein sequence tokenization', 'build inputs with special tokens by wrapping token IDs with CLS and EOS tokens for ESM model', 'get a special tokens mask marking CLS and EOS positions in tokenized ESM sequences', 'save the ESM tokenizer vocabulary to a directory as a newline-separated text file', 'convert an ESM protein token string to its integer ID using the tokenizer vocabulary']
```

Usage

```
{'create_esm_config': 'create an EsmConfig instance for a standard ESM-1b language model with vocab size 33', 'create_esmfold_config': 'create an EsmConfig instance configured as a folding model with esmfold_config and vocab_list', 'create_trunk_config': 'create a TrunkConfig with custom structure_module settings for the ESMFold backbone', 'create_structure_module_config': 'create a StructureModuleConfig with custom IPA and resnet dimensions for protein folding', 'get_default_vocab_list': 'get the default amino-acid vocabulary list used by ESM folding models'}
```

## File: huggingface_transformers/src/transformers/models/esm/convert_esm.py

Prompts

```
['create an EsmConfig instance for a standard ESM-1b language model with vocab size 33', 'create an EsmConfig instance configured as a folding model with esmfold_config and vocab_list', 'create a TrunkConfig with custom structure_module settings for the ESMFold backbone', 'create a StructureModuleConfig with custom IPA and resnet dimensions for protein folding', 'get the default amino-acid vocabulary list used by ESM folding models', 'convert an ESM checkpoint from fairseq to a HuggingFace PyTorch model', 'run the ESM-to-Transformers conversion CLI with model name and output path', 'convert an ESMFold v1 model checkpoint to HuggingFace EsmForProteinFolding format', 'convert an ESM model to HuggingFace format with a classification head for sequence classification', 'create an ESMFold-compatible tokenizer with special tokens for amino acid sequences', 'create an EsmModel transformer for protein sequence encoding with optional rotary embeddings', 'run EsmForMaskedLM to predict masked tokens in protein sequences', 'run EsmForSequenceClassification to classify protein sequences into labels', 'run EsmForTokenClassification to predict per-token protein annotations', 'predict protein residue contacts from attention maps using EsmModel', 'run EsmForProteinFolding forward pass on amino acid input sequences to predict 3D protein structures', 'infer protein 3D structure from amino acid sequence string and return PDB format output', 'convert EsmForProteinFolding output dictionary to PDB file string representation', 'fold multiple protein sequences into 3D structures and return list of PDB strings', 'compute per-residue plddt confidence scores and tm-score for predicted protein structures', 'create an EsmTokenizer instance from a vocab file for protein sequence tokenization', 'build inputs with special tokens by wrapping token IDs with CLS and EOS tokens for ESM model', 'get a special tokens mask marking CLS and EOS positions in tokenized ESM sequences', 'save the ESM tokenizer vocabulary to a directory as a newline-separated text file', 'convert an ESM protein token string to its integer ID using the tokenizer vocabulary']
```

Usage

```
{'convert_esm_checkpoint_to_pytorch': 'convert an ESM checkpoint from fairseq to a HuggingFace PyTorch model', 'run_esm_conversion_cli': 'run the ESM-to-Transformers conversion CLI with model name and output path', 'convert_esmfold_to_pytorch': 'convert an ESMFold v1 model checkpoint to HuggingFace EsmForProteinFolding format', 'convert_esm_classification': 'convert an ESM model to HuggingFace format with a classification head for sequence classification', 'create_esmfold_tokenizer': 'create an ESMFold-compatible tokenizer with special tokens for amino acid sequences'}
```

## File: huggingface_transformers/src/transformers/models/esm/modeling_esm.py

Prompts

```
['create an EsmConfig instance for a standard ESM-1b language model with vocab size 33', 'create an EsmConfig instance configured as a folding model with esmfold_config and vocab_list', 'create a TrunkConfig with custom structure_module settings for the ESMFold backbone', 'create a StructureModuleConfig with custom IPA and resnet dimensions for protein folding', 'get the default amino-acid vocabulary list used by ESM folding models', 'convert an ESM checkpoint from fairseq to a HuggingFace PyTorch model', 'run the ESM-to-Transformers conversion CLI with model name and output path', 'convert an ESMFold v1 model checkpoint to HuggingFace EsmForProteinFolding format', 'convert an ESM model to HuggingFace format with a classification head for sequence classification', 'create an ESMFold-compatible tokenizer with special tokens for amino acid sequences', 'create an EsmModel transformer for protein sequence encoding with optional rotary embeddings', 'run EsmForMaskedLM to predict masked tokens in protein sequences', 'run EsmForSequenceClassification to classify protein sequences into labels', 'run EsmForTokenClassification to predict per-token protein annotations', 'predict protein residue contacts from attention maps using EsmModel', 'run EsmForProteinFolding forward pass on amino acid input sequences to predict 3D protein structures', 'infer protein 3D structure from amino acid sequence string and return PDB format output', 'convert EsmForProteinFolding output dictionary to PDB file string representation', 'fold multiple protein sequences into 3D structures and return list of PDB strings', 'compute per-residue plddt confidence scores and tm-score for predicted protein structures', 'create an EsmTokenizer instance from a vocab file for protein sequence tokenization', 'build inputs with special tokens by wrapping token IDs with CLS and EOS tokens for ESM model', 'get a special tokens mask marking CLS and EOS positions in tokenized ESM sequences', 'save the ESM tokenizer vocabulary to a directory as a newline-separated text file', 'convert an ESM protein token string to its integer ID using the tokenizer vocabulary']
```

Usage

```
{'create_esm_model': 'create an EsmModel transformer for protein sequence encoding with optional rotary embeddings', 'run_masked_lm': 'run EsmForMaskedLM to predict masked tokens in protein sequences', 'run_sequence_classification': 'run EsmForSequenceClassification to classify protein sequences into labels', 'run_token_classification': 'run EsmForTokenClassification to predict per-token protein annotations', 'predict_contacts': 'predict protein residue contacts from attention maps using EsmModel'}
```

## File: huggingface_transformers/src/transformers/models/esm/modeling_esmfold.py

Prompts

```
['create an EsmConfig instance for a standard ESM-1b language model with vocab size 33', 'create an EsmConfig instance configured as a folding model with esmfold_config and vocab_list', 'create a TrunkConfig with custom structure_module settings for the ESMFold backbone', 'create a StructureModuleConfig with custom IPA and resnet dimensions for protein folding', 'get the default amino-acid vocabulary list used by ESM folding models', 'convert an ESM checkpoint from fairseq to a HuggingFace PyTorch model', 'run the ESM-to-Transformers conversion CLI with model name and output path', 'convert an ESMFold v1 model checkpoint to HuggingFace EsmForProteinFolding format', 'convert an ESM model to HuggingFace format with a classification head for sequence classification', 'create an ESMFold-compatible tokenizer with special tokens for amino acid sequences', 'create an EsmModel transformer for protein sequence encoding with optional rotary embeddings', 'run EsmForMaskedLM to predict masked tokens in protein sequences', 'run EsmForSequenceClassification to classify protein sequences into labels', 'run EsmForTokenClassification to predict per-token protein annotations', 'predict protein residue contacts from attention maps using EsmModel', 'run EsmForProteinFolding forward pass on amino acid input sequences to predict 3D protein structures', 'infer protein 3D structure from amino acid sequence string and return PDB format output', 'convert EsmForProteinFolding output dictionary to PDB file string representation', 'fold multiple protein sequences into 3D structures and return list of PDB strings', 'compute per-residue plddt confidence scores and tm-score for predicted protein structures', 'create an EsmTokenizer instance from a vocab file for protein sequence tokenization', 'build inputs with special tokens by wrapping token IDs with CLS and EOS tokens for ESM model', 'get a special tokens mask marking CLS and EOS positions in tokenized ESM sequences', 'save the ESM tokenizer vocabulary to a directory as a newline-separated text file', 'convert an ESM protein token string to its integer ID using the tokenizer vocabulary']
```

Usage

```
{'run_esmfold_protein_folding': 'run EsmForProteinFolding forward pass on amino acid input sequences to predict 3D protein structures', 'infer_protein_structure_pdb': 'infer protein 3D structure from amino acid sequence string and return PDB format output', 'convert_model_output_to_pdb': 'convert EsmForProteinFolding output dictionary to PDB file string representation', 'fold_batch_protein_sequences': 'fold multiple protein sequences into 3D structures and return list of PDB strings', 'compute_protein_confidence_scores': 'compute per-residue plddt confidence scores and tm-score for predicted protein structures'}
```

## File: huggingface_transformers/src/transformers/models/esm/tokenization_esm.py

Prompts

```
['create an EsmConfig instance for a standard ESM-1b language model with vocab size 33', 'create an EsmConfig instance configured as a folding model with esmfold_config and vocab_list', 'create a TrunkConfig with custom structure_module settings for the ESMFold backbone', 'create a StructureModuleConfig with custom IPA and resnet dimensions for protein folding', 'get the default amino-acid vocabulary list used by ESM folding models', 'convert an ESM checkpoint from fairseq to a HuggingFace PyTorch model', 'run the ESM-to-Transformers conversion CLI with model name and output path', 'convert an ESMFold v1 model checkpoint to HuggingFace EsmForProteinFolding format', 'convert an ESM model to HuggingFace format with a classification head for sequence classification', 'create an ESMFold-compatible tokenizer with special tokens for amino acid sequences', 'create an EsmModel transformer for protein sequence encoding with optional rotary embeddings', 'run EsmForMaskedLM to predict masked tokens in protein sequences', 'run EsmForSequenceClassification to classify protein sequences into labels', 'run EsmForTokenClassification to predict per-token protein annotations', 'predict protein residue contacts from attention maps using EsmModel', 'run EsmForProteinFolding forward pass on amino acid input sequences to predict 3D protein structures', 'infer protein 3D structure from amino acid sequence string and return PDB format output', 'convert EsmForProteinFolding output dictionary to PDB file string representation', 'fold multiple protein sequences into 3D structures and return list of PDB strings', 'compute per-residue plddt confidence scores and tm-score for predicted protein structures', 'create an EsmTokenizer instance from a vocab file for protein sequence tokenization', 'build inputs with special tokens by wrapping token IDs with CLS and EOS tokens for ESM model', 'get a special tokens mask marking CLS and EOS positions in tokenized ESM sequences', 'save the ESM tokenizer vocabulary to a directory as a newline-separated text file', 'convert an ESM protein token string to its integer ID using the tokenizer vocabulary']
```

Usage

```
{'create_esm_tokenizer': 'create an EsmTokenizer instance from a vocab file for protein sequence tokenization', 'build_inputs_with_special_tokens': 'build inputs with special tokens by wrapping token IDs with CLS and EOS tokens for ESM model', 'get_special_tokens_mask': 'get a special tokens mask marking CLS and EOS positions in tokenized ESM sequences', 'save_esm_vocabulary': 'save the ESM tokenizer vocabulary to a directory as a newline-separated text file', 'convert_esm_token_to_id': 'convert an ESM protein token string to its integer ID using the tokenizer vocabulary'}
```

