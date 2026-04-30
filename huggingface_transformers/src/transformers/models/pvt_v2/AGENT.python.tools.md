# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pvt_v2/convert_pvt_v2_to_pytorch.py

Prompts

```
['convert a PVTv2 checkpoint from the original library to a PyTorch HuggingFace model', 'create a mapping of weight keys to rename from original PVTv2 checkpoint to HuggingFace format', 'split the combined key-value weight matrix into separate key and value weight matrices', 'download and load a sample COCO image for verifying converted model weights', 'run the PVTv2 checkpoint conversion script via argparse CLI with model size and checkpoint path', 'create a PvtV2Model transformer for hierarchical vision feature extraction from image inputs', 'build a PvtV2ForImageClassification model with a linear classifier head on top of the encoder', 'run a PvtV2Backbone to extract multi-stage feature maps for object detection frameworks like DETR', 'test the PvtV2SelfAttention class with spatial reduction and linear attention modes', 'review the PvtV2EncoderLayer with overlap patch embeddings and stochastic depth blocks']
```

Usage

```
{'convert_pvt_v2_checkpoint': 'convert a PVTv2 checkpoint from the original library to a PyTorch HuggingFace model', 'create_rename_keys': 'create a mapping of weight keys to rename from original PVTv2 checkpoint to HuggingFace format', 'read_in_k_v': 'split the combined key-value weight matrix into separate key and value weight matrices', 'prepare_img': 'download and load a sample COCO image for verifying converted model weights', 'run_convert_script': 'run the PVTv2 checkpoint conversion script via argparse CLI with model size and checkpoint path'}
```

## File: huggingface_transformers/src/transformers/models/pvt_v2/modeling_pvt_v2.py

Prompts

```
['convert a PVTv2 checkpoint from the original library to a PyTorch HuggingFace model', 'create a mapping of weight keys to rename from original PVTv2 checkpoint to HuggingFace format', 'split the combined key-value weight matrix into separate key and value weight matrices', 'download and load a sample COCO image for verifying converted model weights', 'run the PVTv2 checkpoint conversion script via argparse CLI with model size and checkpoint path', 'create a PvtV2Model transformer for hierarchical vision feature extraction from image inputs', 'build a PvtV2ForImageClassification model with a linear classifier head on top of the encoder', 'run a PvtV2Backbone to extract multi-stage feature maps for object detection frameworks like DETR', 'test the PvtV2SelfAttention class with spatial reduction and linear attention modes', 'review the PvtV2EncoderLayer with overlap patch embeddings and stochastic depth blocks']
```

Usage

```
{'create_pvt_v2_model': 'create a PvtV2Model transformer for hierarchical vision feature extraction from image inputs', 'build_image_classification_head': 'build a PvtV2ForImageClassification model with a linear classifier head on top of the encoder', 'run_backbone_feature_extraction': 'run a PvtV2Backbone to extract multi-stage feature maps for object detection frameworks like DETR', 'test_self_attention_mechanism': 'test the PvtV2SelfAttention class with spatial reduction and linear attention modes', 'review_encoder_layer': 'review the PvtV2EncoderLayer with overlap patch embeddings and stochastic depth blocks'}
```

