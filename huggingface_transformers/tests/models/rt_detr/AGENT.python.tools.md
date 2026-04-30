# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/rt_detr/test_modeling_rt_detr.py

Prompts

```
['test the RT_DETR PyTorch model with configurable batch size, image size, and label generation for object detection', 'create an RTDetrModelTester instance to generate model configs, pixel values, masks, and labels for unit testing', 'test encoder, decoder, and cross-attention output shapes and layer counts for RTDetrModel and RTDetrForObjectDetection', 'test encoder and decoder hidden state output shapes and layer counts with output_hidden_states enabled', 'run inference on RTDetrForObjectDetection with a sample image and verify logits, boxes, and post-processed detection results', 'test the RTDetrResNetBackbone model class with default configuration and input tensors', 'create an RTDetrResNetConfig with custom hidden sizes, depths, and output feature stages', 'test the RTDetrResNetBackbone forward pass with pixel values and optional labels', 'test the backbone feature extraction for stages 2, 3, and 4 with varying image sizes', 'test RTDetrResNetConfig initialization with num_channels, embeddings_size, and hidden_act parameters']
```

Usage

```
{'test_modeling_rt_detr': 'test the RT_DETR PyTorch model with configurable batch size, image size, and label generation for object detection', 'create_rt_detr_model_tester': 'create an RTDetrModelTester instance to generate model configs, pixel values, masks, and labels for unit testing', 'test_attention_outputs': 'test encoder, decoder, and cross-attention output shapes and layer counts for RTDetrModel and RTDetrForObjectDetection', 'test_hidden_states_output': 'test encoder and decoder hidden state output shapes and layer counts with output_hidden_states enabled', 'test_inference_object_detection_head': 'run inference on RTDetrForObjectDetection with a sample image and verify logits, boxes, and post-processed detection results'}
```

## File: huggingface_transformers/tests/models/rt_detr/test_modeling_rt_detr_resnet.py

Prompts

```
['test the RT_DETR PyTorch model with configurable batch size, image size, and label generation for object detection', 'create an RTDetrModelTester instance to generate model configs, pixel values, masks, and labels for unit testing', 'test encoder, decoder, and cross-attention output shapes and layer counts for RTDetrModel and RTDetrForObjectDetection', 'test encoder and decoder hidden state output shapes and layer counts with output_hidden_states enabled', 'run inference on RTDetrForObjectDetection with a sample image and verify logits, boxes, and post-processed detection results', 'test the RTDetrResNetBackbone model class with default configuration and input tensors', 'create an RTDetrResNetConfig with custom hidden sizes, depths, and output feature stages', 'test the RTDetrResNetBackbone forward pass with pixel values and optional labels', 'test the backbone feature extraction for stages 2, 3, and 4 with varying image sizes', 'test RTDetrResNetConfig initialization with num_channels, embeddings_size, and hidden_act parameters']
```

Usage

```
{'test_RTDetrResNetBackbone_model': 'test the RTDetrResNetBackbone model class with default configuration and input tensors', 'create_RTDetrResNetConfig': 'create an RTDetrResNetConfig with custom hidden sizes, depths, and output feature stages', 'test_model_forward_pass': 'test the RTDetrResNetBackbone forward pass with pixel values and optional labels', 'test_backbone_feature_extraction': 'test the backbone feature extraction for stages 2, 3, and 4 with varying image sizes', 'test_model_config_parameters': 'test RTDetrResNetConfig initialization with num_channels, embeddings_size, and hidden_act parameters'}
```

