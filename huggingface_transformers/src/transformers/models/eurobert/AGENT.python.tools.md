# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/eurobert/configuration_eurobert.py

Prompts

```
['create an EuroBertConfig instance with default eurobert-base style configuration parameters', 'initialize a EuroBertModel from an EuroBertConfig for eurobert-base style architecture', 'access the model configuration via model.config after model instantiation', 'validate the EuroBertConfig architecture ensuring hidden_size is a multiple of num_attention_heads', 'configure EuroBertConfig with classifier_pooling strategy set to bos, mean, or late', 'create an EuroBertModel encoder with configurable hidden size, attention heads, and layers', 'build an EuroBertForMaskedLM model for fill-in-the-middle token prediction tasks', 'run sequence classification with EuroBertForSequenceClassification using bos, mean, or late pooling', 'create an EuroBertForTokenClassification model for per-token NER or tagging tasks', 'build an EuroBertRMSNorm layer equivalent to T5LayerNorm with configurable epsilon', 'build a masked language model using EuroBertForMaskedLM to predict masked tokens in text', 'create a sequence classifier using EuroBertForSequenceClassification with late, bos, or mean pooling', 'build a token classifier using EuroBertForTokenClassification for per-token label prediction', 'run the base EuroBertModel encoder to extract hidden state representations from input tokens', 'configure EuroBertConfig with custom hidden size, layers, attention heads, and pooling strategy']
```

Usage

```
{'create_eurobert_config': 'create an EuroBertConfig instance with default eurobert-base style configuration parameters', 'initialize_eurobert_model': 'initialize a EuroBertModel from an EuroBertConfig for eurobert-base style architecture', 'access_model_configuration': 'access the model configuration via model.config after model instantiation', 'validate_eurobert_architecture': 'validate the EuroBertConfig architecture ensuring hidden_size is a multiple of num_attention_heads', 'configure_eurobert_pooling': 'configure EuroBertConfig with classifier_pooling strategy set to bos, mean, or late'}
```

## File: huggingface_transformers/src/transformers/models/eurobert/modeling_eurobert.py

Prompts

```
['create an EuroBertConfig instance with default eurobert-base style configuration parameters', 'initialize a EuroBertModel from an EuroBertConfig for eurobert-base style architecture', 'access the model configuration via model.config after model instantiation', 'validate the EuroBertConfig architecture ensuring hidden_size is a multiple of num_attention_heads', 'configure EuroBertConfig with classifier_pooling strategy set to bos, mean, or late', 'create an EuroBertModel encoder with configurable hidden size, attention heads, and layers', 'build an EuroBertForMaskedLM model for fill-in-the-middle token prediction tasks', 'run sequence classification with EuroBertForSequenceClassification using bos, mean, or late pooling', 'create an EuroBertForTokenClassification model for per-token NER or tagging tasks', 'build an EuroBertRMSNorm layer equivalent to T5LayerNorm with configurable epsilon', 'build a masked language model using EuroBertForMaskedLM to predict masked tokens in text', 'create a sequence classifier using EuroBertForSequenceClassification with late, bos, or mean pooling', 'build a token classifier using EuroBertForTokenClassification for per-token label prediction', 'run the base EuroBertModel encoder to extract hidden state representations from input tokens', 'configure EuroBertConfig with custom hidden size, layers, attention heads, and pooling strategy']
```

Usage

```
{'create_model_eurobert_base': 'create an EuroBertModel encoder with configurable hidden size, attention heads, and layers', 'build_masked_lm_eurobert': 'build an EuroBertForMaskedLM model for fill-in-the-middle token prediction tasks', 'run_sequence_classification_eurobert': 'run sequence classification with EuroBertForSequenceClassification using bos, mean, or late pooling', 'create_token_classifier_eurobert': 'create an EuroBertForTokenClassification model for per-token NER or tagging tasks', 'build_rmsnorm_layer': 'build an EuroBertRMSNorm layer equivalent to T5LayerNorm with configurable epsilon'}
```

## File: huggingface_transformers/src/transformers/models/eurobert/modular_eurobert.py

Prompts

```
['create an EuroBertConfig instance with default eurobert-base style configuration parameters', 'initialize a EuroBertModel from an EuroBertConfig for eurobert-base style architecture', 'access the model configuration via model.config after model instantiation', 'validate the EuroBertConfig architecture ensuring hidden_size is a multiple of num_attention_heads', 'configure EuroBertConfig with classifier_pooling strategy set to bos, mean, or late', 'create an EuroBertModel encoder with configurable hidden size, attention heads, and layers', 'build an EuroBertForMaskedLM model for fill-in-the-middle token prediction tasks', 'run sequence classification with EuroBertForSequenceClassification using bos, mean, or late pooling', 'create an EuroBertForTokenClassification model for per-token NER or tagging tasks', 'build an EuroBertRMSNorm layer equivalent to T5LayerNorm with configurable epsilon', 'build a masked language model using EuroBertForMaskedLM to predict masked tokens in text', 'create a sequence classifier using EuroBertForSequenceClassification with late, bos, or mean pooling', 'build a token classifier using EuroBertForTokenClassification for per-token label prediction', 'run the base EuroBertModel encoder to extract hidden state representations from input tokens', 'configure EuroBertConfig with custom hidden size, layers, attention heads, and pooling strategy']
```

Usage

```
{'build_masked_lm': 'build a masked language model using EuroBertForMaskedLM to predict masked tokens in text', 'create_sequence_classifier': 'create a sequence classifier using EuroBertForSequenceClassification with late, bos, or mean pooling', 'build_token_classifier': 'build a token classifier using EuroBertForTokenClassification for per-token label prediction', 'run_base_encoder': 'run the base EuroBertModel encoder to extract hidden state representations from input tokens', 'configure_eurobert': 'configure EuroBertConfig with custom hidden size, layers, attention heads, and pooling strategy'}
```

