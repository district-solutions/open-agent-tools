# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/models/jepa/classifier/config.py

Prompts

```
['create a JepaClassifierConfig with custom encoder, pool depth, and number of classes', 'register the base JEPA classifier config architecture in a dependency container', 'register the large JEPA classifier config architecture in a dependency container', 'register the huge JEPA classifier config architecture in a dependency container', 'review the JepaClassifierConfig dataclass fields including encoder_config, pool_depth, decoder_projection, num_queries, and num_classes', 'create a JEPA classifier model from a JepaClassifierConfig using the factory function', 'create a full JEPA classifier model with encoder, pooler, and classification head', 'create an AttentivePooler with cross-attention decoder layer and optional encoder for pooling', 'create a CrossAttentionDecoderLayer with layer norms, cross-attention, and feed-forward network', 'create a linear classification head projecting model dimensions to the number of classes', 'build a JepaClassifierModel with encoder frontend, transformer encoder, attentive pooler, and head projection for classification', 'create an AttentivePooler with learnable query tokens and a cross-attention decoder layer for pooling encoder sequences', 'create a CrossAttentionDecoderLayer with cross-attention, feed-forward network, and layer normalization for decoder processing', 'test the JepaClassifierModel forward pass by passing sequences and batch layout through the full model pipeline', 'review the AttentivePooler reset_parameters method that initializes query tokens with truncated normal distribution']
```

Usage

```
{'create_jepa_classifier_config': 'create a JepaClassifierConfig with custom encoder, pool depth, and number of classes', 'register_jepa_classifier_base': 'register the base JEPA classifier config architecture in a dependency container', 'register_jepa_classifier_large': 'register the large JEPA classifier config architecture in a dependency container', 'register_jepa_classifier_huge': 'register the huge JEPA classifier config architecture in a dependency container', 'review_jepa_classifier_config': 'review the JepaClassifierConfig dataclass fields including encoder_config, pool_depth, decoder_projection, num_queries, and num_classes'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/jepa/classifier/factory.py

Prompts

```
['create a JepaClassifierConfig with custom encoder, pool depth, and number of classes', 'register the base JEPA classifier config architecture in a dependency container', 'register the large JEPA classifier config architecture in a dependency container', 'register the huge JEPA classifier config architecture in a dependency container', 'review the JepaClassifierConfig dataclass fields including encoder_config, pool_depth, decoder_projection, num_queries, and num_classes', 'create a JEPA classifier model from a JepaClassifierConfig using the factory function', 'create a full JEPA classifier model with encoder, pooler, and classification head', 'create an AttentivePooler with cross-attention decoder layer and optional encoder for pooling', 'create a CrossAttentionDecoderLayer with layer norms, cross-attention, and feed-forward network', 'create a linear classification head projecting model dimensions to the number of classes', 'build a JepaClassifierModel with encoder frontend, transformer encoder, attentive pooler, and head projection for classification', 'create an AttentivePooler with learnable query tokens and a cross-attention decoder layer for pooling encoder sequences', 'create a CrossAttentionDecoderLayer with cross-attention, feed-forward network, and layer normalization for decoder processing', 'test the JepaClassifierModel forward pass by passing sequences and batch layout through the full model pipeline', 'review the AttentivePooler reset_parameters method that initializes query tokens with truncated normal distribution']
```

Usage

```
{'create_jepa_classifier_model': 'create a JEPA classifier model from a JepaClassifierConfig using the factory function', 'create_jepa_classifier_model_full': 'create a full JEPA classifier model with encoder, pooler, and classification head', 'create_attentive_pooler': 'create an AttentivePooler with cross-attention decoder layer and optional encoder for pooling', 'create_cross_attention_decoder_layer': 'create a CrossAttentionDecoderLayer with layer norms, cross-attention, and feed-forward network', 'create_classification_head': 'create a linear classification head projecting model dimensions to the number of classes'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/jepa/classifier/model.py

Prompts

```
['create a JepaClassifierConfig with custom encoder, pool depth, and number of classes', 'register the base JEPA classifier config architecture in a dependency container', 'register the large JEPA classifier config architecture in a dependency container', 'register the huge JEPA classifier config architecture in a dependency container', 'review the JepaClassifierConfig dataclass fields including encoder_config, pool_depth, decoder_projection, num_queries, and num_classes', 'create a JEPA classifier model from a JepaClassifierConfig using the factory function', 'create a full JEPA classifier model with encoder, pooler, and classification head', 'create an AttentivePooler with cross-attention decoder layer and optional encoder for pooling', 'create a CrossAttentionDecoderLayer with layer norms, cross-attention, and feed-forward network', 'create a linear classification head projecting model dimensions to the number of classes', 'build a JepaClassifierModel with encoder frontend, transformer encoder, attentive pooler, and head projection for classification', 'create an AttentivePooler with learnable query tokens and a cross-attention decoder layer for pooling encoder sequences', 'create a CrossAttentionDecoderLayer with cross-attention, feed-forward network, and layer normalization for decoder processing', 'test the JepaClassifierModel forward pass by passing sequences and batch layout through the full model pipeline', 'review the AttentivePooler reset_parameters method that initializes query tokens with truncated normal distribution']
```

Usage

```
{'build_JepaClassifierModel': 'build a JepaClassifierModel with encoder frontend, transformer encoder, attentive pooler, and head projection for classification', 'create_AttentivePooler': 'create an AttentivePooler with learnable query tokens and a cross-attention decoder layer for pooling encoder sequences', 'create_CrossAttentionDecoderLayer': 'create a CrossAttentionDecoderLayer with cross-attention, feed-forward network, and layer normalization for decoder processing', 'test_JepaClassifierModel_forward': 'test the JepaClassifierModel forward pass by passing sequences and batch layout through the full model pipeline', 'review_AttentivePooler_reset_parameters': 'review the AttentivePooler reset_parameters method that initializes query tokens with truncated normal distribution'}
```

