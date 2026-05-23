# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/flamingo/adapter.py

Prompts

```
['extend a language model base with gated cross-attention layers for multimodal Flamingo adapter initialization', 'run the forward pass to condition Flamingo decoder layers on media locations before calling parent forward', 'clear all conditioned decoder layers by resetting vision embeddings, media locations, and attend previous state', 'check whether all decoder layers in the Flamingo adapter are already conditioned for the current forward pass', 'set the decoder layers attribute name path for recursive access to the language model decoder layers', 'build a Flamingo multimodal model with vision encoder, language encoder, and tokenizer configs', 'predict image captions using the Flamingo model with zero-shot or few-shot inference', 'extract vision features from input images using the Flamingo vision encoder and perceiver resampler', 'preprocess text prompts for zero-shot or few-shot inference by formatting and tokenizing them', 'post process generated outputs to extract captions or VQA answers from Flamingo model predictions', 'build a PerceiverResampler to compress image features into learnable latent tokens with frame and media time embeddings', 'create a PerceiverAttention module that computes cross-attention between image features and latent tokens using multi-head attention', 'build a MaskedCrossAttention layer that attends text features to visual media with optional temporal masking', 'create a GatedCrossAttentionBlock combining masked cross-attention and feed-forward layers with learnable gating parameters', 'build a FlamingoLayer that conditions a decoder layer on visual features via gated cross-attention before language processing', 'build a language model with an adapter by combining base module and adapter dict using ExtendModule', 'extend a base module instance with a mixin class to add new functions via ExtendModule.extend_instance', 'get a nested attribute from an object using dot notation like a.b.c with getattr_recursive', 'set a nested attribute on an object using dot notation like a.b.c with setattr_recursive', 'review the ExtendModule class and its mixin pattern for combining language models with adapters']
```

Usage

```
{'extend_init_flamingo': 'extend a language model base with gated cross-attention layers for multimodal Flamingo adapter initialization', 'forward_condition_layers': 'run the forward pass to condition Flamingo decoder layers on media locations before calling parent forward', 'clear_conditioned_layers': 'clear all conditioned decoder layers by resetting vision embeddings, media locations, and attend previous state', 'is_conditioned_check': 'check whether all decoder layers in the Flamingo adapter are already conditioned for the current forward pass', 'set_decoder_layers_attr_name': 'set the decoder layers attribute name path for recursive access to the language model decoder layers'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/flamingo/flamingo.py

Prompts

```
['extend a language model base with gated cross-attention layers for multimodal Flamingo adapter initialization', 'run the forward pass to condition Flamingo decoder layers on media locations before calling parent forward', 'clear all conditioned decoder layers by resetting vision embeddings, media locations, and attend previous state', 'check whether all decoder layers in the Flamingo adapter are already conditioned for the current forward pass', 'set the decoder layers attribute name path for recursive access to the language model decoder layers', 'build a Flamingo multimodal model with vision encoder, language encoder, and tokenizer configs', 'predict image captions using the Flamingo model with zero-shot or few-shot inference', 'extract vision features from input images using the Flamingo vision encoder and perceiver resampler', 'preprocess text prompts for zero-shot or few-shot inference by formatting and tokenizing them', 'post process generated outputs to extract captions or VQA answers from Flamingo model predictions', 'build a PerceiverResampler to compress image features into learnable latent tokens with frame and media time embeddings', 'create a PerceiverAttention module that computes cross-attention between image features and latent tokens using multi-head attention', 'build a MaskedCrossAttention layer that attends text features to visual media with optional temporal masking', 'create a GatedCrossAttentionBlock combining masked cross-attention and feed-forward layers with learnable gating parameters', 'build a FlamingoLayer that conditions a decoder layer on visual features via gated cross-attention before language processing', 'build a language model with an adapter by combining base module and adapter dict using ExtendModule', 'extend a base module instance with a mixin class to add new functions via ExtendModule.extend_instance', 'get a nested attribute from an object using dot notation like a.b.c with getattr_recursive', 'set a nested attribute on an object using dot notation like a.b.c with setattr_recursive', 'review the ExtendModule class and its mixin pattern for combining language models with adapters']
```

Usage

```
{'build_flamingo_model': 'build a Flamingo multimodal model with vision encoder, language encoder, and tokenizer configs', 'predict_image_caption': 'predict image captions using the Flamingo model with zero-shot or few-shot inference', 'extract_vision_features': 'extract vision features from input images using the Flamingo vision encoder and perceiver resampler', 'preprocess_text_prompts': 'preprocess text prompts for zero-shot or few-shot inference by formatting and tokenizing them', 'post_process_outputs': 'post process generated outputs to extract captions or VQA answers from Flamingo model predictions'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/flamingo/modules.py

Prompts

```
['extend a language model base with gated cross-attention layers for multimodal Flamingo adapter initialization', 'run the forward pass to condition Flamingo decoder layers on media locations before calling parent forward', 'clear all conditioned decoder layers by resetting vision embeddings, media locations, and attend previous state', 'check whether all decoder layers in the Flamingo adapter are already conditioned for the current forward pass', 'set the decoder layers attribute name path for recursive access to the language model decoder layers', 'build a Flamingo multimodal model with vision encoder, language encoder, and tokenizer configs', 'predict image captions using the Flamingo model with zero-shot or few-shot inference', 'extract vision features from input images using the Flamingo vision encoder and perceiver resampler', 'preprocess text prompts for zero-shot or few-shot inference by formatting and tokenizing them', 'post process generated outputs to extract captions or VQA answers from Flamingo model predictions', 'build a PerceiverResampler to compress image features into learnable latent tokens with frame and media time embeddings', 'create a PerceiverAttention module that computes cross-attention between image features and latent tokens using multi-head attention', 'build a MaskedCrossAttention layer that attends text features to visual media with optional temporal masking', 'create a GatedCrossAttentionBlock combining masked cross-attention and feed-forward layers with learnable gating parameters', 'build a FlamingoLayer that conditions a decoder layer on visual features via gated cross-attention before language processing', 'build a language model with an adapter by combining base module and adapter dict using ExtendModule', 'extend a base module instance with a mixin class to add new functions via ExtendModule.extend_instance', 'get a nested attribute from an object using dot notation like a.b.c with getattr_recursive', 'set a nested attribute on an object using dot notation like a.b.c with setattr_recursive', 'review the ExtendModule class and its mixin pattern for combining language models with adapters']
```

Usage

```
{'build_perceiver_resampler': 'build a PerceiverResampler to compress image features into learnable latent tokens with frame and media time embeddings', 'create_perceiver_attention': 'create a PerceiverAttention module that computes cross-attention between image features and latent tokens using multi-head attention', 'build_masked_cross_attention': 'build a MaskedCrossAttention layer that attends text features to visual media with optional temporal masking', 'create_gated_cross_attention_block': 'create a GatedCrossAttentionBlock combining masked cross-attention and feed-forward layers with learnable gating parameters', 'build_flamingo_layer': 'build a FlamingoLayer that conditions a decoder layer on visual features via gated cross-attention before language processing'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/flamingo/utils.py

Prompts

```
['extend a language model base with gated cross-attention layers for multimodal Flamingo adapter initialization', 'run the forward pass to condition Flamingo decoder layers on media locations before calling parent forward', 'clear all conditioned decoder layers by resetting vision embeddings, media locations, and attend previous state', 'check whether all decoder layers in the Flamingo adapter are already conditioned for the current forward pass', 'set the decoder layers attribute name path for recursive access to the language model decoder layers', 'build a Flamingo multimodal model with vision encoder, language encoder, and tokenizer configs', 'predict image captions using the Flamingo model with zero-shot or few-shot inference', 'extract vision features from input images using the Flamingo vision encoder and perceiver resampler', 'preprocess text prompts for zero-shot or few-shot inference by formatting and tokenizing them', 'post process generated outputs to extract captions or VQA answers from Flamingo model predictions', 'build a PerceiverResampler to compress image features into learnable latent tokens with frame and media time embeddings', 'create a PerceiverAttention module that computes cross-attention between image features and latent tokens using multi-head attention', 'build a MaskedCrossAttention layer that attends text features to visual media with optional temporal masking', 'create a GatedCrossAttentionBlock combining masked cross-attention and feed-forward layers with learnable gating parameters', 'build a FlamingoLayer that conditions a decoder layer on visual features via gated cross-attention before language processing', 'build a language model with an adapter by combining base module and adapter dict using ExtendModule', 'extend a base module instance with a mixin class to add new functions via ExtendModule.extend_instance', 'get a nested attribute from an object using dot notation like a.b.c with getattr_recursive', 'set a nested attribute on an object using dot notation like a.b.c with setattr_recursive', 'review the ExtendModule class and its mixin pattern for combining language models with adapters']
```

Usage

```
{'build_ExtendModule': 'build a language model with an adapter by combining base module and adapter dict using ExtendModule', 'extend_instance_mixin': 'extend a base module instance with a mixin class to add new functions via ExtendModule.extend_instance', 'get_nested_attribute': 'get a nested attribute from an object using dot notation like a.b.c with getattr_recursive', 'set_nested_attribute': 'set a nested attribute on an object using dot notation like a.b.c with setattr_recursive', 'review_ExtendModule': 'review the ExtendModule class and its mixin pattern for combining language models with adapters'}
```

