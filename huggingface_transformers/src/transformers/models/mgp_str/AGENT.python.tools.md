# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mgp_str/modeling_mgp_str.py

Prompts

```
['run the MGP-STR model for scene text recognition on input images using pixel values', 'build a vision encoder with patch embeddings, cls tokens, and positional encoding for image inputs', 'create three classification heads (character, bpe, wordpiece) on top of transformer encoder output', 'test the A3 token learner module that adaptively selects tokens via attention-based pooling', 'review the multi-head self-attention layer with qkv projection and scaled dot-product attention', 'build an MGP-STR processor that combines image processing with character, BPE, and wordpiece tokenization', 'create a DecodeType enum with CHARACTER, BPE, and WORDPIECE annotation formats for MGP-STR decoding', 'test the batch_decode method that fuses char, BPE, and wordpiece predictions into final text outputs', 'refactor the _decode_helper method to convert prediction logits into decoded strings with confidence scores', 'review the MgpstrProcessor __call__ method that processes images and text inputs into model-ready tensors', 'create a MgpstrTokenizer instance from a JSON vocabulary file for character-level tokenization', 'tokenize a string into character-level tokens using MgpstrTokenizer._tokenize', 'convert a token string to its vocabulary ID using MgpstrTokenizer._convert_token_to_id', 'convert a vocabulary ID back to its token string using MgpstrTokenizer._convert_id_to_token', 'save the MgpstrTokenizer vocabulary to a JSON file in a specified directory']
```

Usage

```
{'run_model_scene_text_recognition': 'run the MGP-STR model for scene text recognition on input images using pixel values', 'build_vision_encoder': 'build a vision encoder with patch embeddings, cls tokens, and positional encoding for image inputs', 'create_multi_head_classification': 'create three classification heads (character, bpe, wordpiece) on top of transformer encoder output', 'test_token_learner': 'test the A3 token learner module that adaptively selects tokens via attention-based pooling', 'review_attention_layer': 'review the multi-head self-attention layer with qkv projection and scaled dot-product attention'}
```

## File: huggingface_transformers/src/transformers/models/mgp_str/processing_mgp_str.py

Prompts

```
['run the MGP-STR model for scene text recognition on input images using pixel values', 'build a vision encoder with patch embeddings, cls tokens, and positional encoding for image inputs', 'create three classification heads (character, bpe, wordpiece) on top of transformer encoder output', 'test the A3 token learner module that adaptively selects tokens via attention-based pooling', 'review the multi-head self-attention layer with qkv projection and scaled dot-product attention', 'build an MGP-STR processor that combines image processing with character, BPE, and wordpiece tokenization', 'create a DecodeType enum with CHARACTER, BPE, and WORDPIECE annotation formats for MGP-STR decoding', 'test the batch_decode method that fuses char, BPE, and wordpiece predictions into final text outputs', 'refactor the _decode_helper method to convert prediction logits into decoded strings with confidence scores', 'review the MgpstrProcessor __call__ method that processes images and text inputs into model-ready tensors', 'create a MgpstrTokenizer instance from a JSON vocabulary file for character-level tokenization', 'tokenize a string into character-level tokens using MgpstrTokenizer._tokenize', 'convert a token string to its vocabulary ID using MgpstrTokenizer._convert_token_to_id', 'convert a vocabulary ID back to its token string using MgpstrTokenizer._convert_id_to_token', 'save the MgpstrTokenizer vocabulary to a JSON file in a specified directory']
```

Usage

```
{'build_mgpstr_processor': 'build an MGP-STR processor that combines image processing with character, BPE, and wordpiece tokenization', 'create_decode_type_enum': 'create a DecodeType enum with CHARACTER, BPE, and WORDPIECE annotation formats for MGP-STR decoding', 'test_batch_decode': 'test the batch_decode method that fuses char, BPE, and wordpiece predictions into final text outputs', 'refactor_decode_helper': 'refactor the _decode_helper method to convert prediction logits into decoded strings with confidence scores', 'review_mgpstr_processor_call': 'review the MgpstrProcessor __call__ method that processes images and text inputs into model-ready tensors'}
```

## File: huggingface_transformers/src/transformers/models/mgp_str/tokenization_mgp_str.py

Prompts

```
['run the MGP-STR model for scene text recognition on input images using pixel values', 'build a vision encoder with patch embeddings, cls tokens, and positional encoding for image inputs', 'create three classification heads (character, bpe, wordpiece) on top of transformer encoder output', 'test the A3 token learner module that adaptively selects tokens via attention-based pooling', 'review the multi-head self-attention layer with qkv projection and scaled dot-product attention', 'build an MGP-STR processor that combines image processing with character, BPE, and wordpiece tokenization', 'create a DecodeType enum with CHARACTER, BPE, and WORDPIECE annotation formats for MGP-STR decoding', 'test the batch_decode method that fuses char, BPE, and wordpiece predictions into final text outputs', 'refactor the _decode_helper method to convert prediction logits into decoded strings with confidence scores', 'review the MgpstrProcessor __call__ method that processes images and text inputs into model-ready tensors', 'create a MgpstrTokenizer instance from a JSON vocabulary file for character-level tokenization', 'tokenize a string into character-level tokens using MgpstrTokenizer._tokenize', 'convert a token string to its vocabulary ID using MgpstrTokenizer._convert_token_to_id', 'convert a vocabulary ID back to its token string using MgpstrTokenizer._convert_id_to_token', 'save the MgpstrTokenizer vocabulary to a JSON file in a specified directory']
```

Usage

```
{'create_mgpstr_tokenizer': 'create a MgpstrTokenizer instance from a JSON vocabulary file for character-level tokenization', 'tokenize_text_char': 'tokenize a string into character-level tokens using MgpstrTokenizer._tokenize', 'convert_token_to_id': 'convert a token string to its vocabulary ID using MgpstrTokenizer._convert_token_to_id', 'convert_id_to_token': 'convert a vocabulary ID back to its token string using MgpstrTokenizer._convert_id_to_token', 'save_tokenizer_vocab': 'save the MgpstrTokenizer vocabulary to a JSON file in a specified directory'}
```

