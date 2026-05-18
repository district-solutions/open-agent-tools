# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/models/flava/image_encoder.py

Prompts

```
['build a FLAVA image transformer encoder using flava_image_encoder with custom hidden size and layers', 'create PatchEmbeddings to project image pixels into patch embeddings using a convolutional layer', 'create ImageEmbeddings with CLS token, position embeddings, and optional masking support for vision transformers', 'build an ImageTransformerWithVAE that combines an image transformer with a VAE for image label generation', 'review the ImageTransformer forward pass that processes pixel values through embeddings, encoder, and pooler', 'build a FLAVAModel with image, text, and multimodal encoders using the flava_model factory function', 'build a FLAVAForPreTraining model with image codebook and pretraining loss using flava_model_for_pretraining', 'build a FLAVAForClassification model with an MLP classifier using flava_model_for_classification', 'build a DalleVAEEncoder to extract DALL-E codebook indices from input images', 'build a FLAVATransformerWithoutEmbeddings multimodal encoder using the flava_multimodal_encoder factory function', 'build a FLAVA text encoder with default BERT-base hyperparameters returning a BERTTextEncoder', 'build a FLAVA text encoder with a custom hidden size for the transformer and embeddings', 'build a FLAVA text encoder with a custom number of hidden transformer layers', 'build a FLAVA text encoder with a custom vocabulary size for token embeddings', 'build a FLAVA text encoder with dropout enabled for regularization during training', 'build a FLAVA transformer model with an encoder, layernorm, pooler, and optional CLS token for multimodal encoding', 'create a transformer encoder layer with multihead self-attention and feedforward blocks supporting pre-norm or post-norm', 'build a stack of transformer encoder layers with optional final layer norm and attention weight collection', 'test the transformer weight initialization function that applies normal distribution to Linear, Conv2d, and Embedding modules', 'review the FLAVA transformer forward pass that prepends CLS tokens, runs the encoder, and applies layernorm and pooling']
```

Usage

```
{'build_image_transformer': 'build a FLAVA image transformer encoder using flava_image_encoder with custom hidden size and layers', 'create_patch_embeddings': 'create PatchEmbeddings to project image pixels into patch embeddings using a convolutional layer', 'create_image_embeddings': 'create ImageEmbeddings with CLS token, position embeddings, and optional masking support for vision transformers', 'build_image_transformer_with_vae': 'build an ImageTransformerWithVAE that combines an image transformer with a VAE for image label generation', 'review_image_transformer_forward': 'review the ImageTransformer forward pass that processes pixel values through embeddings, encoder, and pooler'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/flava/model.py

Prompts

```
['build a FLAVA image transformer encoder using flava_image_encoder with custom hidden size and layers', 'create PatchEmbeddings to project image pixels into patch embeddings using a convolutional layer', 'create ImageEmbeddings with CLS token, position embeddings, and optional masking support for vision transformers', 'build an ImageTransformerWithVAE that combines an image transformer with a VAE for image label generation', 'review the ImageTransformer forward pass that processes pixel values through embeddings, encoder, and pooler', 'build a FLAVAModel with image, text, and multimodal encoders using the flava_model factory function', 'build a FLAVAForPreTraining model with image codebook and pretraining loss using flava_model_for_pretraining', 'build a FLAVAForClassification model with an MLP classifier using flava_model_for_classification', 'build a DalleVAEEncoder to extract DALL-E codebook indices from input images', 'build a FLAVATransformerWithoutEmbeddings multimodal encoder using the flava_multimodal_encoder factory function', 'build a FLAVA text encoder with default BERT-base hyperparameters returning a BERTTextEncoder', 'build a FLAVA text encoder with a custom hidden size for the transformer and embeddings', 'build a FLAVA text encoder with a custom number of hidden transformer layers', 'build a FLAVA text encoder with a custom vocabulary size for token embeddings', 'build a FLAVA text encoder with dropout enabled for regularization during training', 'build a FLAVA transformer model with an encoder, layernorm, pooler, and optional CLS token for multimodal encoding', 'create a transformer encoder layer with multihead self-attention and feedforward blocks supporting pre-norm or post-norm', 'build a stack of transformer encoder layers with optional final layer norm and attention weight collection', 'test the transformer weight initialization function that applies normal distribution to Linear, Conv2d, and Embedding modules', 'review the FLAVA transformer forward pass that prepends CLS tokens, runs the encoder, and applies layernorm and pooling']
```

Usage

```
{'build_flava_model': 'build a FLAVAModel with image, text, and multimodal encoders using the flava_model factory function', 'build_flava_pretraining': 'build a FLAVAForPreTraining model with image codebook and pretraining loss using flava_model_for_pretraining', 'build_flava_classification': 'build a FLAVAForClassification model with an MLP classifier using flava_model_for_classification', 'build_dalle_vae_encoder': 'build a DalleVAEEncoder to extract DALL-E codebook indices from input images', 'build_flava_multimodal_encoder': 'build a FLAVATransformerWithoutEmbeddings multimodal encoder using the flava_multimodal_encoder factory function'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/flava/text_encoder.py

Prompts

```
['build a FLAVA image transformer encoder using flava_image_encoder with custom hidden size and layers', 'create PatchEmbeddings to project image pixels into patch embeddings using a convolutional layer', 'create ImageEmbeddings with CLS token, position embeddings, and optional masking support for vision transformers', 'build an ImageTransformerWithVAE that combines an image transformer with a VAE for image label generation', 'review the ImageTransformer forward pass that processes pixel values through embeddings, encoder, and pooler', 'build a FLAVAModel with image, text, and multimodal encoders using the flava_model factory function', 'build a FLAVAForPreTraining model with image codebook and pretraining loss using flava_model_for_pretraining', 'build a FLAVAForClassification model with an MLP classifier using flava_model_for_classification', 'build a DalleVAEEncoder to extract DALL-E codebook indices from input images', 'build a FLAVATransformerWithoutEmbeddings multimodal encoder using the flava_multimodal_encoder factory function', 'build a FLAVA text encoder with default BERT-base hyperparameters returning a BERTTextEncoder', 'build a FLAVA text encoder with a custom hidden size for the transformer and embeddings', 'build a FLAVA text encoder with a custom number of hidden transformer layers', 'build a FLAVA text encoder with a custom vocabulary size for token embeddings', 'build a FLAVA text encoder with dropout enabled for regularization during training', 'build a FLAVA transformer model with an encoder, layernorm, pooler, and optional CLS token for multimodal encoding', 'create a transformer encoder layer with multihead self-attention and feedforward blocks supporting pre-norm or post-norm', 'build a stack of transformer encoder layers with optional final layer norm and attention weight collection', 'test the transformer weight initialization function that applies normal distribution to Linear, Conv2d, and Embedding modules', 'review the FLAVA transformer forward pass that prepends CLS tokens, runs the encoder, and applies layernorm and pooling']
```

Usage

```
{'build_default_flava_text_encoder': 'build a FLAVA text encoder with default BERT-base hyperparameters returning a BERTTextEncoder', 'build_flava_text_encoder_custom_hidden_size': 'build a FLAVA text encoder with a custom hidden size for the transformer and embeddings', 'build_flava_text_encoder_custom_layers': 'build a FLAVA text encoder with a custom number of hidden transformer layers', 'build_flava_text_encoder_custom_vocab': 'build a FLAVA text encoder with a custom vocabulary size for token embeddings', 'build_flava_text_encoder_with_dropout': 'build a FLAVA text encoder with dropout enabled for regularization during training'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/flava/transformer.py

Prompts

```
['build a FLAVA image transformer encoder using flava_image_encoder with custom hidden size and layers', 'create PatchEmbeddings to project image pixels into patch embeddings using a convolutional layer', 'create ImageEmbeddings with CLS token, position embeddings, and optional masking support for vision transformers', 'build an ImageTransformerWithVAE that combines an image transformer with a VAE for image label generation', 'review the ImageTransformer forward pass that processes pixel values through embeddings, encoder, and pooler', 'build a FLAVAModel with image, text, and multimodal encoders using the flava_model factory function', 'build a FLAVAForPreTraining model with image codebook and pretraining loss using flava_model_for_pretraining', 'build a FLAVAForClassification model with an MLP classifier using flava_model_for_classification', 'build a DalleVAEEncoder to extract DALL-E codebook indices from input images', 'build a FLAVATransformerWithoutEmbeddings multimodal encoder using the flava_multimodal_encoder factory function', 'build a FLAVA text encoder with default BERT-base hyperparameters returning a BERTTextEncoder', 'build a FLAVA text encoder with a custom hidden size for the transformer and embeddings', 'build a FLAVA text encoder with a custom number of hidden transformer layers', 'build a FLAVA text encoder with a custom vocabulary size for token embeddings', 'build a FLAVA text encoder with dropout enabled for regularization during training', 'build a FLAVA transformer model with an encoder, layernorm, pooler, and optional CLS token for multimodal encoding', 'create a transformer encoder layer with multihead self-attention and feedforward blocks supporting pre-norm or post-norm', 'build a stack of transformer encoder layers with optional final layer norm and attention weight collection', 'test the transformer weight initialization function that applies normal distribution to Linear, Conv2d, and Embedding modules', 'review the FLAVA transformer forward pass that prepends CLS tokens, runs the encoder, and applies layernorm and pooling']
```

Usage

```
{'build_FLAVATransformerWithoutEmbeddings': 'build a FLAVA transformer model with an encoder, layernorm, pooler, and optional CLS token for multimodal encoding', 'create_TransformerEncoderLayer': 'create a transformer encoder layer with multihead self-attention and feedforward blocks supporting pre-norm or post-norm', 'build_TransformerEncoder': 'build a stack of transformer encoder layers with optional final layer norm and attention weight collection', 'test_init_transformer_weights': 'test the transformer weight initialization function that applies normal distribution to Linear, Conv2d, and Embedding modules', 'review_FLAVATransformerWithoutEmbeddings_forward': 'review the FLAVA transformer forward pass that prepends CLS tokens, runs the encoder, and applies layernorm and pooling'}
```

