# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/convnextv2/test_modeling_convnextv2.py

Prompts

```
['test the ConvNextV2Model forward pass and verify output shape matches expected dimensions', 'test the ConvNextV2ForImageClassification model and verify logits shape matches batch size and number of labels', 'test the ConvNextV2Model hidden states output for all model classes with output_hidden_states enabled', 'test the ConvNextV2Model training loop with gradient computation for all model classes', 'test loading the ConvNextV2Model from pretrained weights and verify model is not None', 'test ConvNextV2ForImageClassification inference on a sample image and verify logits shape and slice values', 'test the ConvNextV2Backbone model using the BackboneTesterMixin common tests', 'test the ConvNextV2Config common properties including hidden_sizes and num_channels']
```

Usage

```
{'test_model_convnextv2': 'test the ConvNextV2Model forward pass and verify output shape matches expected dimensions', 'test_model_image_classification': 'test the ConvNextV2ForImageClassification model and verify logits shape matches batch size and number of labels', 'test_model_hidden_states': 'test the ConvNextV2Model hidden states output for all model classes with output_hidden_states enabled', 'test_model_training': 'test the ConvNextV2Model training loop with gradient computation for all model classes', 'test_model_from_pretrained': 'test loading the ConvNextV2Model from pretrained weights and verify model is not None', 'test_inference_image_classification': 'test ConvNextV2ForImageClassification inference on a sample image and verify logits shape and slice values', 'test_backbone_convnextv2': 'test the ConvNextV2Backbone model using the BackboneTesterMixin common tests', 'test_config_convnextv2': 'test the ConvNextV2Config common properties including hidden_sizes and num_channels'}
```

