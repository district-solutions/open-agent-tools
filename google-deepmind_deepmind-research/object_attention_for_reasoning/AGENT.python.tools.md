# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/object_attention_for_reasoning/model.py

Prompts

```
['build a ClevrerTransformerModel with 28 transformer layers, 10 attention heads, and relative position encoding', 'create a TensorFlow tensor by concatenating an id vector along a specified axis using append_ids', 'run the ClevrerTransformerModel on descriptive CLEVRER questions with question tokens and monet latents as inputs', 'run the ClevrerTransformerModel on multiple-choice CLEVRER questions with question tokens, choices, and monet latents', 'review the pretrained model config with 28 transformer layers, 10 heads, and 128 head size', 'run the ClevrerTransformerModel on a CLEVRER scene to answer descriptive and multiple-choice questions', 'load MONet latent representations from a .npz file for a given CLEVRER scene index', 'encode a CLEVRER question or choice sentence into a padded sequence of token IDs', 'encode multiple CLEVRER choice sentences into a padded array of token ID sequences', 'evaluate a descriptive CLEVRER question using the transformer model and return the predicted answer', 'build a TransformerTower with multi-head attention layers and MLP blocks for sequence modeling', 'create a MultiheadAttention module with optional state context and relative positional encodings', 'build a ResidualDropoutWrapper that applies residual connections, dropout, and layer normalization', 'create a causal attention mask preventing elements from attending to future positions', 'create sinusoidal positional encodings for transformer input sequences with configurable timescales']
```

Usage

```
{'build_ClevrerTransformerModel': 'build a ClevrerTransformerModel with 28 transformer layers, 10 attention heads, and relative position encoding', 'create_append_ids': 'create a TensorFlow tensor by concatenating an id vector along a specified axis using append_ids', 'run_apply_model_descriptive': 'run the ClevrerTransformerModel on descriptive CLEVRER questions with question tokens and monet latents as inputs', 'run_apply_model_mc': 'run the ClevrerTransformerModel on multiple-choice CLEVRER questions with question tokens, choices, and monet latents', 'review_PRETRAINED_MODEL_CONFIG': 'review the pretrained model config with 28 transformer layers, 10 heads, and 128 head size'}
```

## File: google-deepmind_deepmind-research/object_attention_for_reasoning/run_model.py

Prompts

```
['build a ClevrerTransformerModel with 28 transformer layers, 10 attention heads, and relative position encoding', 'create a TensorFlow tensor by concatenating an id vector along a specified axis using append_ids', 'run the ClevrerTransformerModel on descriptive CLEVRER questions with question tokens and monet latents as inputs', 'run the ClevrerTransformerModel on multiple-choice CLEVRER questions with question tokens, choices, and monet latents', 'review the pretrained model config with 28 transformer layers, 10 heads, and 128 head size', 'run the ClevrerTransformerModel on a CLEVRER scene to answer descriptive and multiple-choice questions', 'load MONet latent representations from a .npz file for a given CLEVRER scene index', 'encode a CLEVRER question or choice sentence into a padded sequence of token IDs', 'encode multiple CLEVRER choice sentences into a padded array of token ID sequences', 'evaluate a descriptive CLEVRER question using the transformer model and return the predicted answer', 'build a TransformerTower with multi-head attention layers and MLP blocks for sequence modeling', 'create a MultiheadAttention module with optional state context and relative positional encodings', 'build a ResidualDropoutWrapper that applies residual connections, dropout, and layer normalization', 'create a causal attention mask preventing elements from attending to future positions', 'create sinusoidal positional encodings for transformer input sequences with configurable timescales']
```

Usage

```
{'run_clevrer_model': 'run the ClevrerTransformerModel on a CLEVRER scene to answer descriptive and multiple-choice questions', 'load_monet_latents': 'load MONet latent representations from a .npz file for a given CLEVRER scene index', 'encode_sentence': 'encode a CLEVRER question or choice sentence into a padded sequence of token IDs', 'encode_choices': 'encode multiple CLEVRER choice sentences into a padded array of token ID sequences', 'eval_descriptive': 'evaluate a descriptive CLEVRER question using the transformer model and return the predicted answer'}
```

## File: google-deepmind_deepmind-research/object_attention_for_reasoning/transformer.py

Prompts

```
['build a ClevrerTransformerModel with 28 transformer layers, 10 attention heads, and relative position encoding', 'create a TensorFlow tensor by concatenating an id vector along a specified axis using append_ids', 'run the ClevrerTransformerModel on descriptive CLEVRER questions with question tokens and monet latents as inputs', 'run the ClevrerTransformerModel on multiple-choice CLEVRER questions with question tokens, choices, and monet latents', 'review the pretrained model config with 28 transformer layers, 10 heads, and 128 head size', 'run the ClevrerTransformerModel on a CLEVRER scene to answer descriptive and multiple-choice questions', 'load MONet latent representations from a .npz file for a given CLEVRER scene index', 'encode a CLEVRER question or choice sentence into a padded sequence of token IDs', 'encode multiple CLEVRER choice sentences into a padded array of token ID sequences', 'evaluate a descriptive CLEVRER question using the transformer model and return the predicted answer', 'build a TransformerTower with multi-head attention layers and MLP blocks for sequence modeling', 'create a MultiheadAttention module with optional state context and relative positional encodings', 'build a ResidualDropoutWrapper that applies residual connections, dropout, and layer normalization', 'create a causal attention mask preventing elements from attending to future positions', 'create sinusoidal positional encodings for transformer input sequences with configurable timescales']
```

Usage

```
{'build_transformer_tower': 'build a TransformerTower with multi-head attention layers and MLP blocks for sequence modeling', 'create_multihead_attention': 'create a MultiheadAttention module with optional state context and relative positional encodings', 'build_residual_dropout_wrapper': 'build a ResidualDropoutWrapper that applies residual connections, dropout, and layer normalization', 'create_future_mask': 'create a causal attention mask preventing elements from attending to future positions', 'create_position_encodings': 'create sinusoidal positional encodings for transformer input sequences with configurable timescales'}
```

