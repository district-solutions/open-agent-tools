# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/ibert/modeling_ibert.py

Prompts

```
['build an I-BERT masked language model using IBertForMaskedLM for token prediction with quantized weights', 'build an I-BERT sequence classifier using IBertForSequenceClassification for GLUE task classification', 'build an I-BERT question answering model using IBertForQuestionAnswering for start and end token prediction', 'build an I-BERT token classifier using IBertForTokenClassification for named entity recognition tasks', 'run the I-BERT encoder using IBertModel with quantized embeddings and integer-only attention layers', 'build a quantized embedding layer using QuantEmbedding with configurable weight bitwidth', 'create a quantized activation module using QuantAct with EMA range tracking', 'test the quantized linear layer QuantLinear with per-channel scaling factors', 'refactor the integer GELU approximation IntGELU using polynomial fitting', 'summarize symmetric linear quantization with SymmetricQuantFunction and STE gradients']
```

Usage

```
{'build_ibert_masked_lm': 'build an I-BERT masked language model using IBertForMaskedLM for token prediction with quantized weights', 'build_ibert_sequence_classifier': 'build an I-BERT sequence classifier using IBertForSequenceClassification for GLUE task classification', 'build_ibert_question_answerer': 'build an I-BERT question answering model using IBertForQuestionAnswering for start and end token prediction', 'build_ibert_token_classifier': 'build an I-BERT token classifier using IBertForTokenClassification for named entity recognition tasks', 'run_ibert_encoder': 'run the I-BERT encoder using IBertModel with quantized embeddings and integer-only attention layers'}
```

## File: huggingface_transformers/src/transformers/models/ibert/quant_modules.py

Prompts

```
['build an I-BERT masked language model using IBertForMaskedLM for token prediction with quantized weights', 'build an I-BERT sequence classifier using IBertForSequenceClassification for GLUE task classification', 'build an I-BERT question answering model using IBertForQuestionAnswering for start and end token prediction', 'build an I-BERT token classifier using IBertForTokenClassification for named entity recognition tasks', 'run the I-BERT encoder using IBertModel with quantized embeddings and integer-only attention layers', 'build a quantized embedding layer using QuantEmbedding with configurable weight bitwidth', 'create a quantized activation module using QuantAct with EMA range tracking', 'test the quantized linear layer QuantLinear with per-channel scaling factors', 'refactor the integer GELU approximation IntGELU using polynomial fitting', 'summarize symmetric linear quantization with SymmetricQuantFunction and STE gradients']
```

Usage

```
{'build_quant_embedding': 'build a quantized embedding layer using QuantEmbedding with configurable weight bitwidth', 'create_quant_activation': 'create a quantized activation module using QuantAct with EMA range tracking', 'test_quant_linear': 'test the quantized linear layer QuantLinear with per-channel scaling factors', 'refactor_int_gelu': 'refactor the integer GELU approximation IntGELU using polynomial fitting', 'summarize_symmetric_quant': 'summarize symmetric linear quantization with SymmetricQuantFunction and STE gradients'}
```

