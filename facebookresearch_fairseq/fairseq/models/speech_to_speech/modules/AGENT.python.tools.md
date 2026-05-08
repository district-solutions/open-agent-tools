# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/models/speech_to_speech/modules/ctc_decoder.py

Prompts

```
['create a CTCDecoder instance with a dictionary and input dimension for CTC-based speech decoding', 'run the CTCDecoder forward pass with source tokens to get projected encoder output', 'review the CTCDecoder linear projection layer that maps input dimensions to dictionary size', 'build a CTCDecoder module that extends FairseqEncoder with a linear projection for speech-to-speech tasks', 'summarize the CTCDecoder class that projects encoder features to dictionary logits via a linear layer', 'create a StackedEmbedding module with num_embeddings, embed_dim, padding_idx, and num_stacked parameters', 'build a forward pass through StackedEmbedding that decomposes stacked input indices into individual embeddings', 'test the StackedEmbedding constructor initializes weights with normal distribution and sets padding index to zero', 'review the StackedEmbedding forward method that expands input indices using vocab_size division and remainder logic', 'summarize the StackedEmbedding class that maps multiple stacked units to a single embedding via projection', 'create an AugTransformerUnitDecoder instance with args, dictionary, and embed_tokens for stacked unit decoding', 'run the forward pass of AugTransformerUnitDecoder with prev_output_tokens and encoder_out to get decoder output', 'run AugTransformerUnitDecoder forward with features_only=True to extract features without applying the output layer', 'upgrade a checkpoint state_dict by migrating project_in_dim weight keys to the new naming convention', 'review the AugTransformerUnitDecoder forward method and its multi-frame projection logic for stacked unit decoding', 'build a TransformerEncoderNoEmb instance with args to create a transformer encoder without token embeddings', 'run the forward method on TransformerEncoderNoEmb with input tensor x and encoder_padding_mask', 'reorder encoder output tensors by batch index using reorder_encoder_out with a new_order tensor', 'review the TransformerEncoderNoEmb class and its stacked TransformerEncoderLayer modules for configuration', 'summarize the encoder output dictionary structure with keys encoder_out, encoder_padding_mask, and encoder_states']
```

Usage

```
{'create_CTCDecoder': 'create a CTCDecoder instance with a dictionary and input dimension for CTC-based speech decoding', 'run_CTCDecoder_forward': 'run the CTCDecoder forward pass with source tokens to get projected encoder output', 'review_CTCDecoder_proj': 'review the CTCDecoder linear projection layer that maps input dimensions to dictionary size', 'build_CTCDecoder_module': 'build a CTCDecoder module that extends FairseqEncoder with a linear projection for speech-to-speech tasks', 'summarize_CTCDecoder_class': 'summarize the CTCDecoder class that projects encoder features to dictionary logits via a linear layer'}
```

## File: facebookresearch_fairseq/fairseq/models/speech_to_speech/modules/stacked_embedding.py

Prompts

```
['create a CTCDecoder instance with a dictionary and input dimension for CTC-based speech decoding', 'run the CTCDecoder forward pass with source tokens to get projected encoder output', 'review the CTCDecoder linear projection layer that maps input dimensions to dictionary size', 'build a CTCDecoder module that extends FairseqEncoder with a linear projection for speech-to-speech tasks', 'summarize the CTCDecoder class that projects encoder features to dictionary logits via a linear layer', 'create a StackedEmbedding module with num_embeddings, embed_dim, padding_idx, and num_stacked parameters', 'build a forward pass through StackedEmbedding that decomposes stacked input indices into individual embeddings', 'test the StackedEmbedding constructor initializes weights with normal distribution and sets padding index to zero', 'review the StackedEmbedding forward method that expands input indices using vocab_size division and remainder logic', 'summarize the StackedEmbedding class that maps multiple stacked units to a single embedding via projection', 'create an AugTransformerUnitDecoder instance with args, dictionary, and embed_tokens for stacked unit decoding', 'run the forward pass of AugTransformerUnitDecoder with prev_output_tokens and encoder_out to get decoder output', 'run AugTransformerUnitDecoder forward with features_only=True to extract features without applying the output layer', 'upgrade a checkpoint state_dict by migrating project_in_dim weight keys to the new naming convention', 'review the AugTransformerUnitDecoder forward method and its multi-frame projection logic for stacked unit decoding', 'build a TransformerEncoderNoEmb instance with args to create a transformer encoder without token embeddings', 'run the forward method on TransformerEncoderNoEmb with input tensor x and encoder_padding_mask', 'reorder encoder output tensors by batch index using reorder_encoder_out with a new_order tensor', 'review the TransformerEncoderNoEmb class and its stacked TransformerEncoderLayer modules for configuration', 'summarize the encoder output dictionary structure with keys encoder_out, encoder_padding_mask, and encoder_states']
```

Usage

```
{'create_stacked_embedding': 'create a StackedEmbedding module with num_embeddings, embed_dim, padding_idx, and num_stacked parameters', 'build_stacked_embedding_forward': 'build a forward pass through StackedEmbedding that decomposes stacked input indices into individual embeddings', 'test_stacked_embedding_init': 'test the StackedEmbedding constructor initializes weights with normal distribution and sets padding index to zero', 'review_stacked_embedding_forward': 'review the StackedEmbedding forward method that expands input indices using vocab_size division and remainder logic', 'summarize_stacked_embedding_class': 'summarize the StackedEmbedding class that maps multiple stacked units to a single embedding via projection'}
```

## File: facebookresearch_fairseq/fairseq/models/speech_to_speech/modules/transformer_decoder_aug.py

Prompts

```
['create a CTCDecoder instance with a dictionary and input dimension for CTC-based speech decoding', 'run the CTCDecoder forward pass with source tokens to get projected encoder output', 'review the CTCDecoder linear projection layer that maps input dimensions to dictionary size', 'build a CTCDecoder module that extends FairseqEncoder with a linear projection for speech-to-speech tasks', 'summarize the CTCDecoder class that projects encoder features to dictionary logits via a linear layer', 'create a StackedEmbedding module with num_embeddings, embed_dim, padding_idx, and num_stacked parameters', 'build a forward pass through StackedEmbedding that decomposes stacked input indices into individual embeddings', 'test the StackedEmbedding constructor initializes weights with normal distribution and sets padding index to zero', 'review the StackedEmbedding forward method that expands input indices using vocab_size division and remainder logic', 'summarize the StackedEmbedding class that maps multiple stacked units to a single embedding via projection', 'create an AugTransformerUnitDecoder instance with args, dictionary, and embed_tokens for stacked unit decoding', 'run the forward pass of AugTransformerUnitDecoder with prev_output_tokens and encoder_out to get decoder output', 'run AugTransformerUnitDecoder forward with features_only=True to extract features without applying the output layer', 'upgrade a checkpoint state_dict by migrating project_in_dim weight keys to the new naming convention', 'review the AugTransformerUnitDecoder forward method and its multi-frame projection logic for stacked unit decoding', 'build a TransformerEncoderNoEmb instance with args to create a transformer encoder without token embeddings', 'run the forward method on TransformerEncoderNoEmb with input tensor x and encoder_padding_mask', 'reorder encoder output tensors by batch index using reorder_encoder_out with a new_order tensor', 'review the TransformerEncoderNoEmb class and its stacked TransformerEncoderLayer modules for configuration', 'summarize the encoder output dictionary structure with keys encoder_out, encoder_padding_mask, and encoder_states']
```

Usage

```
{'init_aug_transformer_unit_decoder': 'create an AugTransformerUnitDecoder instance with args, dictionary, and embed_tokens for stacked unit decoding', 'forward_aug_decoder': 'run the forward pass of AugTransformerUnitDecoder with prev_output_tokens and encoder_out to get decoder output', 'forward_features_only': 'run AugTransformerUnitDecoder forward with features_only=True to extract features without applying the output layer', 'upgrade_state_dict_named': 'upgrade a checkpoint state_dict by migrating project_in_dim weight keys to the new naming convention', 'review_aug_decoder_forward': 'review the AugTransformerUnitDecoder forward method and its multi-frame projection logic for stacked unit decoding'}
```

## File: facebookresearch_fairseq/fairseq/models/speech_to_speech/modules/transformer_encoder.py

Prompts

```
['create a CTCDecoder instance with a dictionary and input dimension for CTC-based speech decoding', 'run the CTCDecoder forward pass with source tokens to get projected encoder output', 'review the CTCDecoder linear projection layer that maps input dimensions to dictionary size', 'build a CTCDecoder module that extends FairseqEncoder with a linear projection for speech-to-speech tasks', 'summarize the CTCDecoder class that projects encoder features to dictionary logits via a linear layer', 'create a StackedEmbedding module with num_embeddings, embed_dim, padding_idx, and num_stacked parameters', 'build a forward pass through StackedEmbedding that decomposes stacked input indices into individual embeddings', 'test the StackedEmbedding constructor initializes weights with normal distribution and sets padding index to zero', 'review the StackedEmbedding forward method that expands input indices using vocab_size division and remainder logic', 'summarize the StackedEmbedding class that maps multiple stacked units to a single embedding via projection', 'create an AugTransformerUnitDecoder instance with args, dictionary, and embed_tokens for stacked unit decoding', 'run the forward pass of AugTransformerUnitDecoder with prev_output_tokens and encoder_out to get decoder output', 'run AugTransformerUnitDecoder forward with features_only=True to extract features without applying the output layer', 'upgrade a checkpoint state_dict by migrating project_in_dim weight keys to the new naming convention', 'review the AugTransformerUnitDecoder forward method and its multi-frame projection logic for stacked unit decoding', 'build a TransformerEncoderNoEmb instance with args to create a transformer encoder without token embeddings', 'run the forward method on TransformerEncoderNoEmb with input tensor x and encoder_padding_mask', 'reorder encoder output tensors by batch index using reorder_encoder_out with a new_order tensor', 'review the TransformerEncoderNoEmb class and its stacked TransformerEncoderLayer modules for configuration', 'summarize the encoder output dictionary structure with keys encoder_out, encoder_padding_mask, and encoder_states']
```

Usage

```
{'build_transformer_encoder_no_emb': 'build a TransformerEncoderNoEmb instance with args to create a transformer encoder without token embeddings', 'run_forward_pass': 'run the forward method on TransformerEncoderNoEmb with input tensor x and encoder_padding_mask', 'reorder_encoder_output': 'reorder encoder output tensors by batch index using reorder_encoder_out with a new_order tensor', 'review_transformer_encoder_layers': 'review the TransformerEncoderNoEmb class and its stacked TransformerEncoderLayer modules for configuration', 'summarize_encoder_output_dict': 'summarize the encoder output dictionary structure with keys encoder_out, encoder_padding_mask, and encoder_states'}
```

