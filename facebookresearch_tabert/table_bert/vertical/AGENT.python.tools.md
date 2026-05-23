# Agent Python Tools

- repo: facebookresearch/tabert
- repo_uri: https://github.com/facebookresearch/tabert

## File: facebookresearch_tabert/table_bert/vertical/config.py

Prompts

```
['create a VerticalAttentionTableBertConfig instance with custom vertical attention heads and layer count', 'add vertical attention arguments to an ArgumentParser using the add_args class method', 'validate a JSON config file to check if it contains num_vertical_layers key', 'configure a VerticalAttentionTableBertConfig to enable or disable cell token prediction', 'initialize a VerticalAttentionTableBertConfig from a pretrained model path using initialize_from', 'collate a list of table row examples into batched PyTorch tensors for training or inference', 'deserialize a serialized row data array back into a row instance dictionary with token ids and column mappings', 'serialize a row instance dictionary into a flat integer array for efficient storage in binary or HDF5 files', 'load training examples from multiple shard files in binary or HDF5 format using VerticalAttentionTableBertDataset', 'validate that a row example column token positions map to valid column ids within the table size', 'create a VerticalAttentionTableBertInputFormatter with config and tokenizer for table pretraining input formatting', 'get row instances from context strings and a Table object for vertical attention processing', 'get a single row input with column token position mappings for vertical attention', 'create a pretraining instance with masked column and context tokens for column-level masking strategy', 'get pretraining instances from an Example with context sampling and row sampling for vertical attention', 'build a VerticalAttentionTableBert model from a VerticalAttentionTableBertConfig for table understanding with vertical attention', 'run the VerticalSelfAttention forward pass on hidden states and attention mask tensors for vertical attention', 'test the BertVerticalLayer module combining vertical attention with intermediate and output sub-layers', 'review the SpanBasedPrediction module that predicts cell tokens from span and position embeddings', 'encode contexts and tables into context and schema encodings using the VerticalAttentionTableBert encode method']
```

Usage

```
{'create_vertical_attention_config': 'create a VerticalAttentionTableBertConfig instance with custom vertical attention heads and layer count', 'add_vertical_args_to_parser': 'add vertical attention arguments to an ArgumentParser using the add_args class method', 'validate_config_file': 'validate a JSON config file to check if it contains num_vertical_layers key', 'configure_cell_token_prediction': 'configure a VerticalAttentionTableBertConfig to enable or disable cell token prediction', 'initialize_from_pretrained': 'initialize a VerticalAttentionTableBertConfig from a pretrained model path using initialize_from'}
```

## File: facebookresearch_tabert/table_bert/vertical/dataset.py

Prompts

```
['create a VerticalAttentionTableBertConfig instance with custom vertical attention heads and layer count', 'add vertical attention arguments to an ArgumentParser using the add_args class method', 'validate a JSON config file to check if it contains num_vertical_layers key', 'configure a VerticalAttentionTableBertConfig to enable or disable cell token prediction', 'initialize a VerticalAttentionTableBertConfig from a pretrained model path using initialize_from', 'collate a list of table row examples into batched PyTorch tensors for training or inference', 'deserialize a serialized row data array back into a row instance dictionary with token ids and column mappings', 'serialize a row instance dictionary into a flat integer array for efficient storage in binary or HDF5 files', 'load training examples from multiple shard files in binary or HDF5 format using VerticalAttentionTableBertDataset', 'validate that a row example column token positions map to valid column ids within the table size', 'create a VerticalAttentionTableBertInputFormatter with config and tokenizer for table pretraining input formatting', 'get row instances from context strings and a Table object for vertical attention processing', 'get a single row input with column token position mappings for vertical attention', 'create a pretraining instance with masked column and context tokens for column-level masking strategy', 'get pretraining instances from an Example with context sampling and row sampling for vertical attention', 'build a VerticalAttentionTableBert model from a VerticalAttentionTableBertConfig for table understanding with vertical attention', 'run the VerticalSelfAttention forward pass on hidden states and attention mask tensors for vertical attention', 'test the BertVerticalLayer module combining vertical attention with intermediate and output sub-layers', 'review the SpanBasedPrediction module that predicts cell tokens from span and position embeddings', 'encode contexts and tables into context and schema encodings using the VerticalAttentionTableBert encode method']
```

Usage

```
{'collate_batch_examples': 'collate a list of table row examples into batched PyTorch tensors for training or inference', 'deserialize_row_data': 'deserialize a serialized row data array back into a row instance dictionary with token ids and column mappings', 'serialize_row_data': 'serialize a row instance dictionary into a flat integer array for efficient storage in binary or HDF5 files', 'load_epoch_shards': 'load training examples from multiple shard files in binary or HDF5 format using VerticalAttentionTableBertDataset', 'check_row_example': 'validate that a row example column token positions map to valid column ids within the table size'}
```

## File: facebookresearch_tabert/table_bert/vertical/input_formatter.py

Prompts

```
['create a VerticalAttentionTableBertConfig instance with custom vertical attention heads and layer count', 'add vertical attention arguments to an ArgumentParser using the add_args class method', 'validate a JSON config file to check if it contains num_vertical_layers key', 'configure a VerticalAttentionTableBertConfig to enable or disable cell token prediction', 'initialize a VerticalAttentionTableBertConfig from a pretrained model path using initialize_from', 'collate a list of table row examples into batched PyTorch tensors for training or inference', 'deserialize a serialized row data array back into a row instance dictionary with token ids and column mappings', 'serialize a row instance dictionary into a flat integer array for efficient storage in binary or HDF5 files', 'load training examples from multiple shard files in binary or HDF5 format using VerticalAttentionTableBertDataset', 'validate that a row example column token positions map to valid column ids within the table size', 'create a VerticalAttentionTableBertInputFormatter with config and tokenizer for table pretraining input formatting', 'get row instances from context strings and a Table object for vertical attention processing', 'get a single row input with column token position mappings for vertical attention', 'create a pretraining instance with masked column and context tokens for column-level masking strategy', 'get pretraining instances from an Example with context sampling and row sampling for vertical attention', 'build a VerticalAttentionTableBert model from a VerticalAttentionTableBertConfig for table understanding with vertical attention', 'run the VerticalSelfAttention forward pass on hidden states and attention mask tensors for vertical attention', 'test the BertVerticalLayer module combining vertical attention with intermediate and output sub-layers', 'review the SpanBasedPrediction module that predicts cell tokens from span and position embeddings', 'encode contexts and tables into context and schema encodings using the VerticalAttentionTableBert encode method']
```

Usage

```
{'create_VANILLA_INPUT_FORMATTER': 'create a VerticalAttentionTableBertInputFormatter with config and tokenizer for table pretraining input formatting', 'get_input_CONTEXT_TABLE': 'get row instances from context strings and a Table object for vertical attention processing', 'get_row_input_CONTEXT_HEADER_ROW': 'get a single row input with column token position mappings for vertical attention', 'create_pretraining_instance_CONTEXT_TABLE_EXAMPLE': 'create a pretraining instance with masked column and context tokens for column-level masking strategy', 'get_pretraining_instances_from_example_EXAMPLE_SAMPLER': 'get pretraining instances from an Example with context sampling and row sampling for vertical attention'}
```

## File: facebookresearch_tabert/table_bert/vertical/vertical_attention_table_bert.py

Prompts

```
['create a VerticalAttentionTableBertConfig instance with custom vertical attention heads and layer count', 'add vertical attention arguments to an ArgumentParser using the add_args class method', 'validate a JSON config file to check if it contains num_vertical_layers key', 'configure a VerticalAttentionTableBertConfig to enable or disable cell token prediction', 'initialize a VerticalAttentionTableBertConfig from a pretrained model path using initialize_from', 'collate a list of table row examples into batched PyTorch tensors for training or inference', 'deserialize a serialized row data array back into a row instance dictionary with token ids and column mappings', 'serialize a row instance dictionary into a flat integer array for efficient storage in binary or HDF5 files', 'load training examples from multiple shard files in binary or HDF5 format using VerticalAttentionTableBertDataset', 'validate that a row example column token positions map to valid column ids within the table size', 'create a VerticalAttentionTableBertInputFormatter with config and tokenizer for table pretraining input formatting', 'get row instances from context strings and a Table object for vertical attention processing', 'get a single row input with column token position mappings for vertical attention', 'create a pretraining instance with masked column and context tokens for column-level masking strategy', 'get pretraining instances from an Example with context sampling and row sampling for vertical attention', 'build a VerticalAttentionTableBert model from a VerticalAttentionTableBertConfig for table understanding with vertical attention', 'run the VerticalSelfAttention forward pass on hidden states and attention mask tensors for vertical attention', 'test the BertVerticalLayer module combining vertical attention with intermediate and output sub-layers', 'review the SpanBasedPrediction module that predicts cell tokens from span and position embeddings', 'encode contexts and tables into context and schema encodings using the VerticalAttentionTableBert encode method']
```

Usage

```
{'build_VerticalAttentionTableBert': 'build a VerticalAttentionTableBert model from a VerticalAttentionTableBertConfig for table understanding with vertical attention', 'run_VerticalSelfAttention_forward': 'run the VerticalSelfAttention forward pass on hidden states and attention mask tensors for vertical attention', 'test_BertVerticalLayer': 'test the BertVerticalLayer module combining vertical attention with intermediate and output sub-layers', 'review_SpanBasedPrediction': 'review the SpanBasedPrediction module that predicts cell tokens from span and position embeddings', 'encode_VerticalAttentionTableBert': 'encode contexts and tables into context and schema encodings using the VerticalAttentionTableBert encode method'}
```

