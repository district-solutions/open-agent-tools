# Agent Python Tools

- repo: datalab-to/surya
- repo_uri: https://github.com/datalab-to/surya

## File: datalab-to_surya/surya/table_rec/model/config.py

Prompts

```
['create a SuryaTableRecConfig for a vision-encoder-decoder table recognition model', 'build a DonutSwinTableRecConfig with custom image size and embedding dimensions', 'create a SuryaTableRecDecoderConfig with custom attention layers and token IDs', 'create a TableRecModelOutput with box property logits and hidden states', 'summarize the BOX_PROPERTIES list defining bbox, category, merges, colspan, and is_header', 'create a LabelEmbedding module that converts table box tensors into combined bbox and property embeddings', 'build a SuryaTableRecDecoder model with label embeddings, box property heads, and pre-output normalization', 'test the LabelEmbedding forward method with box tensors to verify embedding concatenation', 'refactor the SuryaTableRecDecoder forward method to support table recognition with bbox sigmoid outputs', 'review the SuryaTableRecDecoder class with box property heads and decoder model integration', 'create a DonutSwinModel instance with a config, optional pooling layer, and mask token support', 'run the DonutSwinModel forward pass on pixel values with optional masked positions and head mask', 'get the input patch embeddings from a DonutSwinModel instance', 'refactor the DonutSwinModel to prune attention heads by layer and head indices', 'review the DonutSwinModel class that extends DonutSwinPreTrainedModel for table recognition encoding', 'create a TableRecEncoderDecoderModel instance with a VisionEncoderDecoderConfig for table recognition', 'run the TableRecEncoderDecoderModel forward pass with decoder input ids and encoder outputs to get box property logits', 'test the TableRecEncoderDecoderModel forward method returns a TableRecOutput with box_property_logits and decoder_hidden_states', 'review the TableRecEncoderDecoderModel class and its encoder decoder architecture with DonutSwinModel and SuryaTableRecDecoder', 'summarize the TableRecEncoderDecoderModel class that combines a vision encoder and table recognition decoder for layout analysis']
```

Usage

```
{'create_SuryaTableRecConfig': 'create a SuryaTableRecConfig for a vision-encoder-decoder table recognition model', 'build_DonutSwinTableRecConfig': 'build a DonutSwinTableRecConfig with custom image size and embedding dimensions', 'create_SuryaTableRecDecoderConfig': 'create a SuryaTableRecDecoderConfig with custom attention layers and token IDs', 'create_TableRecModelOutput': 'create a TableRecModelOutput with box property logits and hidden states', 'summarize_BOX_PROPERTIES': 'summarize the BOX_PROPERTIES list defining bbox, category, merges, colspan, and is_header'}
```

## File: datalab-to_surya/surya/table_rec/model/decoder.py

Prompts

```
['create a SuryaTableRecConfig for a vision-encoder-decoder table recognition model', 'build a DonutSwinTableRecConfig with custom image size and embedding dimensions', 'create a SuryaTableRecDecoderConfig with custom attention layers and token IDs', 'create a TableRecModelOutput with box property logits and hidden states', 'summarize the BOX_PROPERTIES list defining bbox, category, merges, colspan, and is_header', 'create a LabelEmbedding module that converts table box tensors into combined bbox and property embeddings', 'build a SuryaTableRecDecoder model with label embeddings, box property heads, and pre-output normalization', 'test the LabelEmbedding forward method with box tensors to verify embedding concatenation', 'refactor the SuryaTableRecDecoder forward method to support table recognition with bbox sigmoid outputs', 'review the SuryaTableRecDecoder class with box property heads and decoder model integration', 'create a DonutSwinModel instance with a config, optional pooling layer, and mask token support', 'run the DonutSwinModel forward pass on pixel values with optional masked positions and head mask', 'get the input patch embeddings from a DonutSwinModel instance', 'refactor the DonutSwinModel to prune attention heads by layer and head indices', 'review the DonutSwinModel class that extends DonutSwinPreTrainedModel for table recognition encoding', 'create a TableRecEncoderDecoderModel instance with a VisionEncoderDecoderConfig for table recognition', 'run the TableRecEncoderDecoderModel forward pass with decoder input ids and encoder outputs to get box property logits', 'test the TableRecEncoderDecoderModel forward method returns a TableRecOutput with box_property_logits and decoder_hidden_states', 'review the TableRecEncoderDecoderModel class and its encoder decoder architecture with DonutSwinModel and SuryaTableRecDecoder', 'summarize the TableRecEncoderDecoderModel class that combines a vision encoder and table recognition decoder for layout analysis']
```

Usage

```
{'create_LabelEmbedding': 'create a LabelEmbedding module that converts table box tensors into combined bbox and property embeddings', 'build_SuryaTableRecDecoder': 'build a SuryaTableRecDecoder model with label embeddings, box property heads, and pre-output normalization', 'test_LabelEmbedding_forward': 'test the LabelEmbedding forward method with box tensors to verify embedding concatenation', 'refactor_SuryaTableRecDecoder_forward': 'refactor the SuryaTableRecDecoder forward method to support table recognition with bbox sigmoid outputs', 'review_SuryaTableRecDecoder': 'review the SuryaTableRecDecoder class with box property heads and decoder model integration'}
```

## File: datalab-to_surya/surya/table_rec/model/encoder.py

Prompts

```
['create a SuryaTableRecConfig for a vision-encoder-decoder table recognition model', 'build a DonutSwinTableRecConfig with custom image size and embedding dimensions', 'create a SuryaTableRecDecoderConfig with custom attention layers and token IDs', 'create a TableRecModelOutput with box property logits and hidden states', 'summarize the BOX_PROPERTIES list defining bbox, category, merges, colspan, and is_header', 'create a LabelEmbedding module that converts table box tensors into combined bbox and property embeddings', 'build a SuryaTableRecDecoder model with label embeddings, box property heads, and pre-output normalization', 'test the LabelEmbedding forward method with box tensors to verify embedding concatenation', 'refactor the SuryaTableRecDecoder forward method to support table recognition with bbox sigmoid outputs', 'review the SuryaTableRecDecoder class with box property heads and decoder model integration', 'create a DonutSwinModel instance with a config, optional pooling layer, and mask token support', 'run the DonutSwinModel forward pass on pixel values with optional masked positions and head mask', 'get the input patch embeddings from a DonutSwinModel instance', 'refactor the DonutSwinModel to prune attention heads by layer and head indices', 'review the DonutSwinModel class that extends DonutSwinPreTrainedModel for table recognition encoding', 'create a TableRecEncoderDecoderModel instance with a VisionEncoderDecoderConfig for table recognition', 'run the TableRecEncoderDecoderModel forward pass with decoder input ids and encoder outputs to get box property logits', 'test the TableRecEncoderDecoderModel forward method returns a TableRecOutput with box_property_logits and decoder_hidden_states', 'review the TableRecEncoderDecoderModel class and its encoder decoder architecture with DonutSwinModel and SuryaTableRecDecoder', 'summarize the TableRecEncoderDecoderModel class that combines a vision encoder and table recognition decoder for layout analysis']
```

Usage

```
{'create_DonutSwinModel': 'create a DonutSwinModel instance with a config, optional pooling layer, and mask token support', 'run_DonutSwinModel_forward': 'run the DonutSwinModel forward pass on pixel values with optional masked positions and head mask', 'get_DonutSwinModel_embeddings': 'get the input patch embeddings from a DonutSwinModel instance', 'refactor_DonutSwinModel_prune_heads': 'refactor the DonutSwinModel to prune attention heads by layer and head indices', 'review_DonutSwinModel': 'review the DonutSwinModel class that extends DonutSwinPreTrainedModel for table recognition encoding'}
```

## File: datalab-to_surya/surya/table_rec/model/encoderdecoder.py

Prompts

```
['create a SuryaTableRecConfig for a vision-encoder-decoder table recognition model', 'build a DonutSwinTableRecConfig with custom image size and embedding dimensions', 'create a SuryaTableRecDecoderConfig with custom attention layers and token IDs', 'create a TableRecModelOutput with box property logits and hidden states', 'summarize the BOX_PROPERTIES list defining bbox, category, merges, colspan, and is_header', 'create a LabelEmbedding module that converts table box tensors into combined bbox and property embeddings', 'build a SuryaTableRecDecoder model with label embeddings, box property heads, and pre-output normalization', 'test the LabelEmbedding forward method with box tensors to verify embedding concatenation', 'refactor the SuryaTableRecDecoder forward method to support table recognition with bbox sigmoid outputs', 'review the SuryaTableRecDecoder class with box property heads and decoder model integration', 'create a DonutSwinModel instance with a config, optional pooling layer, and mask token support', 'run the DonutSwinModel forward pass on pixel values with optional masked positions and head mask', 'get the input patch embeddings from a DonutSwinModel instance', 'refactor the DonutSwinModel to prune attention heads by layer and head indices', 'review the DonutSwinModel class that extends DonutSwinPreTrainedModel for table recognition encoding', 'create a TableRecEncoderDecoderModel instance with a VisionEncoderDecoderConfig for table recognition', 'run the TableRecEncoderDecoderModel forward pass with decoder input ids and encoder outputs to get box property logits', 'test the TableRecEncoderDecoderModel forward method returns a TableRecOutput with box_property_logits and decoder_hidden_states', 'review the TableRecEncoderDecoderModel class and its encoder decoder architecture with DonutSwinModel and SuryaTableRecDecoder', 'summarize the TableRecEncoderDecoderModel class that combines a vision encoder and table recognition decoder for layout analysis']
```

Usage

```
{'create_model_encoder_decoder': 'create a TableRecEncoderDecoderModel instance with a VisionEncoderDecoderConfig for table recognition', 'run_model_forward': 'run the TableRecEncoderDecoderModel forward pass with decoder input ids and encoder outputs to get box property logits', 'test_model_forward': 'test the TableRecEncoderDecoderModel forward method returns a TableRecOutput with box_property_logits and decoder_hidden_states', 'review_model_encoder_decoder': 'review the TableRecEncoderDecoderModel class and its encoder decoder architecture with DonutSwinModel and SuryaTableRecDecoder', 'summarize_model_table_rec': 'summarize the TableRecEncoderDecoderModel class that combines a vision encoder and table recognition decoder for layout analysis'}
```

