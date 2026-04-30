# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/roformer/convert_roformer_original_tf_checkpoint_to_pytorch.py

Prompts

```
['convert a TensorFlow RoFormer checkpoint to a PyTorch model using config and checkpoint paths', 'load TensorFlow checkpoint weights into an existing PyTorch RoFormer model', 'run the CLI script to convert a TensorFlow RoFormer checkpoint to PyTorch format', 'build a PyTorch RoFormerForMaskedLM model from a RoFormerConfig JSON configuration file', 'review the convert_tf_checkpoint_to_pytorch function that converts TF checkpoints to PyTorch', 'build a RoFormer masked language model for bidirectional token prediction with cross-entropy loss', 'build a RoFormer causal language model for autoregressive next-token prediction with past key-value caching', 'build a RoFormer sequence classification model with a classification head for GLUE tasks and regression support', 'build a RoFormer token classification model for named entity recognition with per-token logits output', 'build a RoFormer question answering model that predicts start and end positions for span extraction', 'create a RoFormer tokenizer instance from a pretrained model or custom vocabulary', 'build model inputs from a sequence or pair of sequences by concatenating and adding special tokens', 'create token type IDs for RoFormer sequence pairs with segment labels', 'save the RoFormer tokenizer vocabulary and configuration to a directory', 'tokenize Chinese text using Jieba pre-tokenizer with WordPiece model', 'create a JiebaPreTokenizer instance with a vocab dictionary for Chinese text tokenization using rjieba', 'build a jieba_split method that tokenizes a NormalizedString into a list of NormalizedString segments using rjieba', 'test the pre_tokenize method that applies jieba splitting to a PreTokenizedString', 'review the JiebaPreTokenizer __init__ that configures BertNormalizer and loads rjieba', 'summarize the tokenization pipeline where jieba_split splits text and pre_tokenize applies it to PreTokenizedString']
```

Usage

```
{'convert_tf_checkpoint_to_pytorch': 'convert a TensorFlow RoFormer checkpoint to a PyTorch model using config and checkpoint paths', 'load_tf_weights_in_roformer': 'load TensorFlow checkpoint weights into an existing PyTorch RoFormer model', 'run_tf_to_pytorch_conversion_cli': 'run the CLI script to convert a TensorFlow RoFormer checkpoint to PyTorch format', 'build_pytorch_roformer_model': 'build a PyTorch RoFormerForMaskedLM model from a RoFormerConfig JSON configuration file', 'review_convert_tf_checkpoint_to_pytorch': 'review the convert_tf_checkpoint_to_pytorch function that converts TF checkpoints to PyTorch'}
```

## File: huggingface_transformers/src/transformers/models/roformer/modeling_roformer.py

Prompts

```
['convert a TensorFlow RoFormer checkpoint to a PyTorch model using config and checkpoint paths', 'load TensorFlow checkpoint weights into an existing PyTorch RoFormer model', 'run the CLI script to convert a TensorFlow RoFormer checkpoint to PyTorch format', 'build a PyTorch RoFormerForMaskedLM model from a RoFormerConfig JSON configuration file', 'review the convert_tf_checkpoint_to_pytorch function that converts TF checkpoints to PyTorch', 'build a RoFormer masked language model for bidirectional token prediction with cross-entropy loss', 'build a RoFormer causal language model for autoregressive next-token prediction with past key-value caching', 'build a RoFormer sequence classification model with a classification head for GLUE tasks and regression support', 'build a RoFormer token classification model for named entity recognition with per-token logits output', 'build a RoFormer question answering model that predicts start and end positions for span extraction', 'create a RoFormer tokenizer instance from a pretrained model or custom vocabulary', 'build model inputs from a sequence or pair of sequences by concatenating and adding special tokens', 'create token type IDs for RoFormer sequence pairs with segment labels', 'save the RoFormer tokenizer vocabulary and configuration to a directory', 'tokenize Chinese text using Jieba pre-tokenizer with WordPiece model', 'create a JiebaPreTokenizer instance with a vocab dictionary for Chinese text tokenization using rjieba', 'build a jieba_split method that tokenizes a NormalizedString into a list of NormalizedString segments using rjieba', 'test the pre_tokenize method that applies jieba splitting to a PreTokenizedString', 'review the JiebaPreTokenizer __init__ that configures BertNormalizer and loads rjieba', 'summarize the tokenization pipeline where jieba_split splits text and pre_tokenize applies it to PreTokenizedString']
```

Usage

```
{'build_roformer_masked_lm': 'build a RoFormer masked language model for bidirectional token prediction with cross-entropy loss', 'build_roformer_causal_lm': 'build a RoFormer causal language model for autoregressive next-token prediction with past key-value caching', 'build_roformer_sequence_classification': 'build a RoFormer sequence classification model with a classification head for GLUE tasks and regression support', 'build_roformer_token_classification': 'build a RoFormer token classification model for named entity recognition with per-token logits output', 'build_roformer_question_answering': 'build a RoFormer question answering model that predicts start and end positions for span extraction'}
```

## File: huggingface_transformers/src/transformers/models/roformer/tokenization_roformer.py

Prompts

```
['convert a TensorFlow RoFormer checkpoint to a PyTorch model using config and checkpoint paths', 'load TensorFlow checkpoint weights into an existing PyTorch RoFormer model', 'run the CLI script to convert a TensorFlow RoFormer checkpoint to PyTorch format', 'build a PyTorch RoFormerForMaskedLM model from a RoFormerConfig JSON configuration file', 'review the convert_tf_checkpoint_to_pytorch function that converts TF checkpoints to PyTorch', 'build a RoFormer masked language model for bidirectional token prediction with cross-entropy loss', 'build a RoFormer causal language model for autoregressive next-token prediction with past key-value caching', 'build a RoFormer sequence classification model with a classification head for GLUE tasks and regression support', 'build a RoFormer token classification model for named entity recognition with per-token logits output', 'build a RoFormer question answering model that predicts start and end positions for span extraction', 'create a RoFormer tokenizer instance from a pretrained model or custom vocabulary', 'build model inputs from a sequence or pair of sequences by concatenating and adding special tokens', 'create token type IDs for RoFormer sequence pairs with segment labels', 'save the RoFormer tokenizer vocabulary and configuration to a directory', 'tokenize Chinese text using Jieba pre-tokenizer with WordPiece model', 'create a JiebaPreTokenizer instance with a vocab dictionary for Chinese text tokenization using rjieba', 'build a jieba_split method that tokenizes a NormalizedString into a list of NormalizedString segments using rjieba', 'test the pre_tokenize method that applies jieba splitting to a PreTokenizedString', 'review the JiebaPreTokenizer __init__ that configures BertNormalizer and loads rjieba', 'summarize the tokenization pipeline where jieba_split splits text and pre_tokenize applies it to PreTokenizedString']
```

Usage

```
{'create_roformer_tokenizer': 'create a RoFormer tokenizer instance from a pretrained model or custom vocabulary', 'build_inputs_with_special_tokens': 'build model inputs from a sequence or pair of sequences by concatenating and adding special tokens', 'create_token_type_ids_from_sequences': 'create token type IDs for RoFormer sequence pairs with segment labels', 'save_roformer_tokenizer': 'save the RoFormer tokenizer vocabulary and configuration to a directory', 'tokenize_chinese_text': 'tokenize Chinese text using Jieba pre-tokenizer with WordPiece model'}
```

## File: huggingface_transformers/src/transformers/models/roformer/tokenization_utils.py

Prompts

```
['convert a TensorFlow RoFormer checkpoint to a PyTorch model using config and checkpoint paths', 'load TensorFlow checkpoint weights into an existing PyTorch RoFormer model', 'run the CLI script to convert a TensorFlow RoFormer checkpoint to PyTorch format', 'build a PyTorch RoFormerForMaskedLM model from a RoFormerConfig JSON configuration file', 'review the convert_tf_checkpoint_to_pytorch function that converts TF checkpoints to PyTorch', 'build a RoFormer masked language model for bidirectional token prediction with cross-entropy loss', 'build a RoFormer causal language model for autoregressive next-token prediction with past key-value caching', 'build a RoFormer sequence classification model with a classification head for GLUE tasks and regression support', 'build a RoFormer token classification model for named entity recognition with per-token logits output', 'build a RoFormer question answering model that predicts start and end positions for span extraction', 'create a RoFormer tokenizer instance from a pretrained model or custom vocabulary', 'build model inputs from a sequence or pair of sequences by concatenating and adding special tokens', 'create token type IDs for RoFormer sequence pairs with segment labels', 'save the RoFormer tokenizer vocabulary and configuration to a directory', 'tokenize Chinese text using Jieba pre-tokenizer with WordPiece model', 'create a JiebaPreTokenizer instance with a vocab dictionary for Chinese text tokenization using rjieba', 'build a jieba_split method that tokenizes a NormalizedString into a list of NormalizedString segments using rjieba', 'test the pre_tokenize method that applies jieba splitting to a PreTokenizedString', 'review the JiebaPreTokenizer __init__ that configures BertNormalizer and loads rjieba', 'summarize the tokenization pipeline where jieba_split splits text and pre_tokenize applies it to PreTokenizedString']
```

Usage

```
{'create_JiebaPreTokenizer': 'create a JiebaPreTokenizer instance with a vocab dictionary for Chinese text tokenization using rjieba', 'build_jieba_split': 'build a jieba_split method that tokenizes a NormalizedString into a list of NormalizedString segments using rjieba', 'test_pre_tokenize': 'test the pre_tokenize method that applies jieba splitting to a PreTokenizedString', 'review_JiebaPreTokenizer_init': 'review the JiebaPreTokenizer __init__ that configures BertNormalizer and loads rjieba', 'summarize_tokenization_pipeline': 'summarize the tokenization pipeline where jieba_split splits text and pre_tokenize applies it to PreTokenizedString'}
```

