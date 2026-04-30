# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/siglip/convert_siglip_to_hf.py

Prompts

```
['convert a SigLIP checkpoint from the original repository to HuggingFace transformers format', 'get a SiglipConfig object for a given model name with correct text and vision architecture parameters', 'get a tokenizer (GemmaTokenizerFast for siglip2 or SiglipTokenizer for v1) configured for the model', 'get a SiglipImageProcessor configured with the correct image size and resampling settings', 'create a list of key rename mappings to transform original checkpoint keys to HuggingFace naming conventions', 'run the SiglipModel forward pass with image and text inputs to compute contrastive loss and similarity scores', 'create text embeddings using SiglipTextModel from tokenized input IDs with bidirectional attention masking', 'create image embeddings using SiglipVisionModel from pixel values with optional position encoding interpolation', 'build a SiglipForImageClassification model with a linear classifier head on top of the vision encoder for ImageNet-style classification', 'test image-text similarity by computing logits_per_image and logits_per_text from normalized embeddings', 'create a SiglipTokenizer instance from a SentencePiece vocab file with custom eos, unk, and pad tokens', 'build model input token IDs from one or two sequences by concatenating and adding special tokens', 'run text canonicalization that lowercases, removes punctuation, and normalizes whitespace', 'test tokenizing text into a list of SentencePiece tokens with proper subword handling', 'review converting a sequence of tokens back into a single decoded string with special token preservation']
```

Usage

```
{'convert_siglip_checkpoint': 'convert a SigLIP checkpoint from the original repository to HuggingFace transformers format', 'get_siglip_config': 'get a SiglipConfig object for a given model name with correct text and vision architecture parameters', 'get_tokenizer': 'get a tokenizer (GemmaTokenizerFast for siglip2 or SiglipTokenizer for v1) configured for the model', 'get_image_processor': 'get a SiglipImageProcessor configured with the correct image size and resampling settings', 'create_rename_keys': 'create a list of key rename mappings to transform original checkpoint keys to HuggingFace naming conventions'}
```

## File: huggingface_transformers/src/transformers/models/siglip/modeling_siglip.py

Prompts

```
['convert a SigLIP checkpoint from the original repository to HuggingFace transformers format', 'get a SiglipConfig object for a given model name with correct text and vision architecture parameters', 'get a tokenizer (GemmaTokenizerFast for siglip2 or SiglipTokenizer for v1) configured for the model', 'get a SiglipImageProcessor configured with the correct image size and resampling settings', 'create a list of key rename mappings to transform original checkpoint keys to HuggingFace naming conventions', 'run the SiglipModel forward pass with image and text inputs to compute contrastive loss and similarity scores', 'create text embeddings using SiglipTextModel from tokenized input IDs with bidirectional attention masking', 'create image embeddings using SiglipVisionModel from pixel values with optional position encoding interpolation', 'build a SiglipForImageClassification model with a linear classifier head on top of the vision encoder for ImageNet-style classification', 'test image-text similarity by computing logits_per_image and logits_per_text from normalized embeddings', 'create a SiglipTokenizer instance from a SentencePiece vocab file with custom eos, unk, and pad tokens', 'build model input token IDs from one or two sequences by concatenating and adding special tokens', 'run text canonicalization that lowercases, removes punctuation, and normalizes whitespace', 'test tokenizing text into a list of SentencePiece tokens with proper subword handling', 'review converting a sequence of tokens back into a single decoded string with special token preservation']
```

Usage

```
{'run_siglip_model': 'run the SiglipModel forward pass with image and text inputs to compute contrastive loss and similarity scores', 'create_text_embeddings': 'create text embeddings using SiglipTextModel from tokenized input IDs with bidirectional attention masking', 'create_image_embeddings': 'create image embeddings using SiglipVisionModel from pixel values with optional position encoding interpolation', 'build_image_classifier': 'build a SiglipForImageClassification model with a linear classifier head on top of the vision encoder for ImageNet-style classification', 'test_siglip_similarity': 'test image-text similarity by computing logits_per_image and logits_per_text from normalized embeddings'}
```

## File: huggingface_transformers/src/transformers/models/siglip/tokenization_siglip.py

Prompts

```
['convert a SigLIP checkpoint from the original repository to HuggingFace transformers format', 'get a SiglipConfig object for a given model name with correct text and vision architecture parameters', 'get a tokenizer (GemmaTokenizerFast for siglip2 or SiglipTokenizer for v1) configured for the model', 'get a SiglipImageProcessor configured with the correct image size and resampling settings', 'create a list of key rename mappings to transform original checkpoint keys to HuggingFace naming conventions', 'run the SiglipModel forward pass with image and text inputs to compute contrastive loss and similarity scores', 'create text embeddings using SiglipTextModel from tokenized input IDs with bidirectional attention masking', 'create image embeddings using SiglipVisionModel from pixel values with optional position encoding interpolation', 'build a SiglipForImageClassification model with a linear classifier head on top of the vision encoder for ImageNet-style classification', 'test image-text similarity by computing logits_per_image and logits_per_text from normalized embeddings', 'create a SiglipTokenizer instance from a SentencePiece vocab file with custom eos, unk, and pad tokens', 'build model input token IDs from one or two sequences by concatenating and adding special tokens', 'run text canonicalization that lowercases, removes punctuation, and normalizes whitespace', 'test tokenizing text into a list of SentencePiece tokens with proper subword handling', 'review converting a sequence of tokens back into a single decoded string with special token preservation']
```

Usage

```
{'create_SiglipTokenizer': 'create a SiglipTokenizer instance from a SentencePiece vocab file with custom eos, unk, and pad tokens', 'build_token_ids_with_special_tokens': 'build model input token IDs from one or two sequences by concatenating and adding special tokens', 'run_canonicalize_text': 'run text canonicalization that lowercases, removes punctuation, and normalizes whitespace', 'test_tokenize_text': 'test tokenizing text into a list of SentencePiece tokens with proper subword handling', 'review_convert_tokens_to_string': 'review converting a sequence of tokens back into a single decoded string with special token preservation'}
```

