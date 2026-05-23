# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/sam_3d_body/models/meta_arch/base_model.py

Prompts

```
['review the BaseModel abstract class and its data preprocessing and batch initialization methods', 'build a subclass of BaseModel that implements the abstract _initialze_model method for 3D body estimation', 'test the data_preprocess method to normalize input images and optionally crop width for ViT backbones', 'test the _flatten_person and _unflatten_person methods to merge and restore person crops in batch dimension', 'test the convert_to_fp16 method to convert the model backbone and encoder to float16 or bfloat16', 'run full-body 3D pose inference with body and hand decoders on an input image batch', 'run a single forward step through the body or hand decoder branch on a batch', 'run the forward pass for the crop-image pose branch to get body and hand predictions', 'run keypoint prompting to refine body pose estimation using wrist and elbow locations from hand decoder', 'run the decoder forward pass with image embeddings, keypoint prompts, and condition info to get pose output']
```

Usage

```
{'review_BaseModel_class': 'review the BaseModel abstract class and its data preprocessing and batch initialization methods', 'build_subclass_of_BaseModel': 'build a subclass of BaseModel that implements the abstract _initialze_model method for 3D body estimation', 'test_data_preprocess': 'test the data_preprocess method to normalize input images and optionally crop width for ViT backbones', 'test_flatten_unflatten_person': 'test the _flatten_person and _unflatten_person methods to merge and restore person crops in batch dimension', 'test_convert_to_fp16': 'test the convert_to_fp16 method to convert the model backbone and encoder to float16 or bfloat16'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/models/meta_arch/sam3d_body.py

Prompts

```
['review the BaseModel abstract class and its data preprocessing and batch initialization methods', 'build a subclass of BaseModel that implements the abstract _initialze_model method for 3D body estimation', 'test the data_preprocess method to normalize input images and optionally crop width for ViT backbones', 'test the _flatten_person and _unflatten_person methods to merge and restore person crops in batch dimension', 'test the convert_to_fp16 method to convert the model backbone and encoder to float16 or bfloat16', 'run full-body 3D pose inference with body and hand decoders on an input image batch', 'run a single forward step through the body or hand decoder branch on a batch', 'run the forward pass for the crop-image pose branch to get body and hand predictions', 'run keypoint prompting to refine body pose estimation using wrist and elbow locations from hand decoder', 'run the decoder forward pass with image embeddings, keypoint prompts, and condition info to get pose output']
```

Usage

```
{'run_SAM3DBody_inference': 'run full-body 3D pose inference with body and hand decoders on an input image batch', 'run_SAM3DBody_forward_step': 'run a single forward step through the body or hand decoder branch on a batch', 'run_SAM3DBody_forward_pose_branch': 'run the forward pass for the crop-image pose branch to get body and hand predictions', 'run_SAM3DBody_keypoint_prompt': 'run keypoint prompting to refine body pose estimation using wrist and elbow locations from hand decoder', 'run_SAM3DBody_forward_decoder': 'run the decoder forward pass with image embeddings, keypoint prompts, and condition info to get pose output'}
```

