# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/tapas/convert_tapas_original_tf_checkpoint_to_pytorch.py

Prompts

```
['convert a TensorFlow TAPAS checkpoint to a PyTorch model for a given task like WTQ or TABFACT', 'load TensorFlow checkpoint weights into a PyTorch TAPAS model with cell selection and aggregation heads', 'convert a TensorFlow TAPAS checkpoint to PyTorch for question answering tasks like SQA, WTQ, or WIKISQL_SUPERVISED', 'convert a TensorFlow TAPAS checkpoint to PyTorch for sequence classification tasks like TABFACT', 'convert a TensorFlow TAPAS checkpoint to PyTorch for masked language modeling tasks', 'build a TAPAS model for answering questions about tabular data using cell selection and aggregation heads', 'create a TAPAS masked language model for predicting masked tokens in table-structured inputs', 'test the TAPAS sequence classification model for table entailment tasks like TabFact', 'run the base TAPAS encoder model with tabular-aware token type embeddings for row, column, and cell structure', 'summarize the IndexMap and segmented reduce utilities for aggregating values over table cells, rows, and columns', 'build a TAPAS tokenizer from a vocab file to tokenize tabular data with questions', 'encode a pandas DataFrame table and question into token IDs with column and row type IDs', 'batch encode multiple questions against the same table with answer coordinates', 'convert model logits to predicted answer coordinates and aggregation indices', 'parse numeric values and dates from text strings for table cell annotation']
```

Usage

```
{'convert_tf_checkpoint_to_pytorch': 'convert a TensorFlow TAPAS checkpoint to a PyTorch model for a given task like WTQ or TABFACT', 'load_tf_weights_in_tapas': 'load TensorFlow checkpoint weights into a PyTorch TAPAS model with cell selection and aggregation heads', 'convert_tapas_for_question_answering': 'convert a TensorFlow TAPAS checkpoint to PyTorch for question answering tasks like SQA, WTQ, or WIKISQL_SUPERVISED', 'convert_tapas_for_sequence_classification': 'convert a TensorFlow TAPAS checkpoint to PyTorch for sequence classification tasks like TABFACT', 'convert_tapas_for_masked_lm': 'convert a TensorFlow TAPAS checkpoint to PyTorch for masked language modeling tasks'}
```

## File: huggingface_transformers/src/transformers/models/tapas/modeling_tapas.py

Prompts

```
['convert a TensorFlow TAPAS checkpoint to a PyTorch model for a given task like WTQ or TABFACT', 'load TensorFlow checkpoint weights into a PyTorch TAPAS model with cell selection and aggregation heads', 'convert a TensorFlow TAPAS checkpoint to PyTorch for question answering tasks like SQA, WTQ, or WIKISQL_SUPERVISED', 'convert a TensorFlow TAPAS checkpoint to PyTorch for sequence classification tasks like TABFACT', 'convert a TensorFlow TAPAS checkpoint to PyTorch for masked language modeling tasks', 'build a TAPAS model for answering questions about tabular data using cell selection and aggregation heads', 'create a TAPAS masked language model for predicting masked tokens in table-structured inputs', 'test the TAPAS sequence classification model for table entailment tasks like TabFact', 'run the base TAPAS encoder model with tabular-aware token type embeddings for row, column, and cell structure', 'summarize the IndexMap and segmented reduce utilities for aggregating values over table cells, rows, and columns', 'build a TAPAS tokenizer from a vocab file to tokenize tabular data with questions', 'encode a pandas DataFrame table and question into token IDs with column and row type IDs', 'batch encode multiple questions against the same table with answer coordinates', 'convert model logits to predicted answer coordinates and aggregation indices', 'parse numeric values and dates from text strings for table cell annotation']
```

Usage

```
{'build_tapas_question_answering': 'build a TAPAS model for answering questions about tabular data using cell selection and aggregation heads', 'create_tapas_masked_lm': 'create a TAPAS masked language model for predicting masked tokens in table-structured inputs', 'test_tapas_sequence_classification': 'test the TAPAS sequence classification model for table entailment tasks like TabFact', 'run_tapas_base_model': 'run the base TAPAS encoder model with tabular-aware token type embeddings for row, column, and cell structure', 'summarize_index_map_utilities': 'summarize the IndexMap and segmented reduce utilities for aggregating values over table cells, rows, and columns'}
```

## File: huggingface_transformers/src/transformers/models/tapas/tokenization_tapas.py

Prompts

```
['convert a TensorFlow TAPAS checkpoint to a PyTorch model for a given task like WTQ or TABFACT', 'load TensorFlow checkpoint weights into a PyTorch TAPAS model with cell selection and aggregation heads', 'convert a TensorFlow TAPAS checkpoint to PyTorch for question answering tasks like SQA, WTQ, or WIKISQL_SUPERVISED', 'convert a TensorFlow TAPAS checkpoint to PyTorch for sequence classification tasks like TABFACT', 'convert a TensorFlow TAPAS checkpoint to PyTorch for masked language modeling tasks', 'build a TAPAS model for answering questions about tabular data using cell selection and aggregation heads', 'create a TAPAS masked language model for predicting masked tokens in table-structured inputs', 'test the TAPAS sequence classification model for table entailment tasks like TabFact', 'run the base TAPAS encoder model with tabular-aware token type embeddings for row, column, and cell structure', 'summarize the IndexMap and segmented reduce utilities for aggregating values over table cells, rows, and columns', 'build a TAPAS tokenizer from a vocab file to tokenize tabular data with questions', 'encode a pandas DataFrame table and question into token IDs with column and row type IDs', 'batch encode multiple questions against the same table with answer coordinates', 'convert model logits to predicted answer coordinates and aggregation indices', 'parse numeric values and dates from text strings for table cell annotation']
```

Usage

```
{'build_tapas_tokenizer': 'build a TAPAS tokenizer from a vocab file to tokenize tabular data with questions', 'encode_table_with_queries': 'encode a pandas DataFrame table and question into token IDs with column and row type IDs', 'batch_encode_table_queries': 'batch encode multiple questions against the same table with answer coordinates', 'convert_logits_to_predictions': 'convert model logits to predicted answer coordinates and aggregation indices', 'parse_numeric_values_from_text': 'parse numeric values and dates from text strings for table cell annotation'}
```

