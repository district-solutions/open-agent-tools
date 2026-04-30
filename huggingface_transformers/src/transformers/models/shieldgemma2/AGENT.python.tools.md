# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/shieldgemma2/convert_shieldgemma2_weights_orbax_to_hf.py

Prompts

```
['run the ShieldGemma2 Orbax-to-HF checkpoint converter CLI with flags for checkpoint paths and precision', 'convert SigLIP vision encoder weights from Orbax format to Hugging Face Transformer format', 'convert transformer decoder and embedder weights from Orbax format to Hugging Face Transformer format', 'convert an Orbax checkpoint to a Hugging Face state tree with configurable target dtype', 'create a ConversionResult dataclass holding the converted state tree and ShieldGemma2 config', 'create a ShieldGemma2ForImageClassification model to classify images as violating or not violating a policy', 'run ShieldGemma2ForImageClassification forward pass to get yes/no violation probabilities for images', 'get the input embeddings from the ShieldGemma2ForImageClassification decoder', 'set the input embeddings on the ShieldGemma2ForImageClassification decoder', 'summarize ShieldGemma2ImageClassifierOutputWithNoAttention containing logits and probabilities for policy violation classification']
```

Usage

```
{'run_convert_shieldgemma2_cli': 'run the ShieldGemma2 Orbax-to-HF checkpoint converter CLI with flags for checkpoint paths and precision', 'convert_siglip_weight': 'convert SigLIP vision encoder weights from Orbax format to Hugging Face Transformer format', 'convert_transformer_weights': 'convert transformer decoder and embedder weights from Orbax format to Hugging Face Transformer format', 'convert_orbax_checkpoint': 'convert an Orbax checkpoint to a Hugging Face state tree with configurable target dtype', 'create_conversion_result': 'create a ConversionResult dataclass holding the converted state tree and ShieldGemma2 config'}
```

## File: huggingface_transformers/src/transformers/models/shieldgemma2/modeling_shieldgemma2.py

Prompts

```
['run the ShieldGemma2 Orbax-to-HF checkpoint converter CLI with flags for checkpoint paths and precision', 'convert SigLIP vision encoder weights from Orbax format to Hugging Face Transformer format', 'convert transformer decoder and embedder weights from Orbax format to Hugging Face Transformer format', 'convert an Orbax checkpoint to a Hugging Face state tree with configurable target dtype', 'create a ConversionResult dataclass holding the converted state tree and ShieldGemma2 config', 'create a ShieldGemma2ForImageClassification model to classify images as violating or not violating a policy', 'run ShieldGemma2ForImageClassification forward pass to get yes/no violation probabilities for images', 'get the input embeddings from the ShieldGemma2ForImageClassification decoder', 'set the input embeddings on the ShieldGemma2ForImageClassification decoder', 'summarize ShieldGemma2ImageClassifierOutputWithNoAttention containing logits and probabilities for policy violation classification']
```

Usage

```
{'create_shieldgemma2_image_classifier': 'create a ShieldGemma2ForImageClassification model to classify images as violating or not violating a policy', 'run_shieldgemma2_classification': 'run ShieldGemma2ForImageClassification forward pass to get yes/no violation probabilities for images', 'get_shieldgemma2_input_embeddings': 'get the input embeddings from the ShieldGemma2ForImageClassification decoder', 'set_shieldgemma2_input_embeddings': 'set the input embeddings on the ShieldGemma2ForImageClassification decoder', 'summarize_shieldgemma2_output': 'summarize ShieldGemma2ImageClassifierOutputWithNoAttention containing logits and probabilities for policy violation classification'}
```

