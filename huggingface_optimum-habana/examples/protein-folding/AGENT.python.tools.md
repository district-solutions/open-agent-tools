# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/examples/protein-folding/run_esmfold.py

Prompts

```
['run ESMFold protein folding inference on a Habana Gaudi HPU device using the facebook/esmfold_v1 model', 'convert ESMFold model outputs including atom positions and masks into PDB format strings', 'tokenize a protein amino acid sequence using the facebook/esmfold_v1 tokenizer for inference input', 'measure protein folding inference step duration on HPU using HabanaGenerationTime context manager', 'save a predicted protein structure from ESMFold outputs to a PDB file on disk', 'run protein sequence classification training on Habana GAI using GaudiTrainer and a pretrained model', 'create an optimizer with differential learning rates for classifier head and backbone parameters', 'create a learning rate scheduler from training arguments and an optimizer', 'compute accuracy and Matthews correlation coefficient metrics from model predictions and labels', 'tokenize a protein sequence string into input IDs and attention mask using a tokenizer', 'run zero-shot evaluation of the ProtST model for protein subcellular localization on Intel Gaudi', 'tokenize protein sequences using the ESM-1b tokenizer with max length padding and truncation', 'embed text label descriptions using the PubMedBERT text model and normalize the features', 'compute zero-shot classification accuracy by matching protein features against label embeddings', 'wrap the protein and text models in HPU graphs for optimized inference on Intel Gaudi']
```

Usage

```
{'run_esmfold_protein_folding_hpu': 'run ESMFold protein folding inference on a Habana Gaudi HPU device using the facebook/esmfold_v1 model', 'convert_esmfold_outputs_to_pdb': 'convert ESMFold model outputs including atom positions and masks into PDB format strings', 'tokenize_protein_sequence_esmfold': 'tokenize a protein amino acid sequence using the facebook/esmfold_v1 tokenizer for inference input', 'time_habana_protein_folding_inference': 'measure protein folding inference step duration on HPU using HabanaGenerationTime context manager', 'save_protein_structure_pdb_file': 'save a predicted protein structure from ESMFold outputs to a PDB file on disk'}
```

## File: huggingface_optimum-habana/examples/protein-folding/run_sequence_classification.py

Prompts

```
['run ESMFold protein folding inference on a Habana Gaudi HPU device using the facebook/esmfold_v1 model', 'convert ESMFold model outputs including atom positions and masks into PDB format strings', 'tokenize a protein amino acid sequence using the facebook/esmfold_v1 tokenizer for inference input', 'measure protein folding inference step duration on HPU using HabanaGenerationTime context manager', 'save a predicted protein structure from ESMFold outputs to a PDB file on disk', 'run protein sequence classification training on Habana GAI using GaudiTrainer and a pretrained model', 'create an optimizer with differential learning rates for classifier head and backbone parameters', 'create a learning rate scheduler from training arguments and an optimizer', 'compute accuracy and Matthews correlation coefficient metrics from model predictions and labels', 'tokenize a protein sequence string into input IDs and attention mask using a tokenizer', 'run zero-shot evaluation of the ProtST model for protein subcellular localization on Intel Gaudi', 'tokenize protein sequences using the ESM-1b tokenizer with max length padding and truncation', 'embed text label descriptions using the PubMedBERT text model and normalize the features', 'compute zero-shot classification accuracy by matching protein features against label embeddings', 'wrap the protein and text models in HPU graphs for optimized inference on Intel Gaudi']
```

Usage

```
{'run_protein_sequence_classification': 'run protein sequence classification training on Habana GAI using GaudiTrainer and a pretrained model', 'create_optimizer_differential_lr': 'create an optimizer with differential learning rates for classifier head and backbone parameters', 'create_scheduler_lr': 'create a learning rate scheduler from training arguments and an optimizer', 'compute_metrics_accuracy_mcc': 'compute accuracy and Matthews correlation coefficient metrics from model predictions and labels', 'tokenize_protein_sequence': 'tokenize a protein sequence string into input IDs and attention mask using a tokenizer'}
```

## File: huggingface_optimum-habana/examples/protein-folding/run_zero_shot_eval.py

Prompts

```
['run ESMFold protein folding inference on a Habana Gaudi HPU device using the facebook/esmfold_v1 model', 'convert ESMFold model outputs including atom positions and masks into PDB format strings', 'tokenize a protein amino acid sequence using the facebook/esmfold_v1 tokenizer for inference input', 'measure protein folding inference step duration on HPU using HabanaGenerationTime context manager', 'save a predicted protein structure from ESMFold outputs to a PDB file on disk', 'run protein sequence classification training on Habana GAI using GaudiTrainer and a pretrained model', 'create an optimizer with differential learning rates for classifier head and backbone parameters', 'create a learning rate scheduler from training arguments and an optimizer', 'compute accuracy and Matthews correlation coefficient metrics from model predictions and labels', 'tokenize a protein sequence string into input IDs and attention mask using a tokenizer', 'run zero-shot evaluation of the ProtST model for protein subcellular localization on Intel Gaudi', 'tokenize protein sequences using the ESM-1b tokenizer with max length padding and truncation', 'embed text label descriptions using the PubMedBERT text model and normalize the features', 'compute zero-shot classification accuracy by matching protein features against label embeddings', 'wrap the protein and text models in HPU graphs for optimized inference on Intel Gaudi']
```

Usage

```
{'run_zero_shot_protein_eval': 'run zero-shot evaluation of the ProtST model for protein subcellular localization on Intel Gaudi', 'tokenize_protein_sequences': 'tokenize protein sequences using the ESM-1b tokenizer with max length padding and truncation', 'embed_label_descriptions': 'embed text label descriptions using the PubMedBERT text model and normalize the features', 'compute_zero_shot_accuracy': 'compute zero-shot classification accuracy by matching protein features against label embeddings', 'wrap_models_in_hpu_graph': 'wrap the protein and text models in HPU graphs for optimized inference on Intel Gaudi'}
```

