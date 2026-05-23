# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/sam_3d_body/build_models.py

Prompts

```
['load the SAM 3D Body model from a local checkpoint file and config YAML onto a CUDA device', 'load the SAM 3D Body model by downloading checkpoint and MHR assets from a Hugging Face repo', 'load the SAM 3D Body model from a checkpoint while specifying a custom MHR model path', 'review the load_sam_3d_body function to understand how it resolves config paths and loads state dicts', 'summarize the _hf_download helper that fetches model checkpoint and MHR model from Hugging Face snapshots', 'run the SAM3DBodyEstimator to estimate 3D body pose, keypoints, and mesh from a single input image', 'run full-body inference with both body and hand decoders using process_one_image with inference_type set to full', 'run body-only inference using process_one_image with inference_type set to body to skip hand decoder', 'run hand-only inference using process_one_image with inference_type set to hand for hand pose estimation', 'run mask-conditioned inference by providing pre-computed masks and bboxes to process_one_image with use_mask enabled']
```

Usage

```
{'load_sam_3d_body_from_checkpoint': 'load the SAM 3D Body model from a local checkpoint file and config YAML onto a CUDA device', 'load_sam_3d_body_from_hf': 'load the SAM 3D Body model by downloading checkpoint and MHR assets from a Hugging Face repo', 'load_sam_3d_body_with_mhr': 'load the SAM 3D Body model from a checkpoint while specifying a custom MHR model path', 'review_load_sam_3d_body': 'review the load_sam_3d_body function to understand how it resolves config paths and loads state dicts', 'summarize_hf_download': 'summarize the _hf_download helper that fetches model checkpoint and MHR model from Hugging Face snapshots'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/sam_3d_body_estimator.py

Prompts

```
['load the SAM 3D Body model from a local checkpoint file and config YAML onto a CUDA device', 'load the SAM 3D Body model by downloading checkpoint and MHR assets from a Hugging Face repo', 'load the SAM 3D Body model from a checkpoint while specifying a custom MHR model path', 'review the load_sam_3d_body function to understand how it resolves config paths and loads state dicts', 'summarize the _hf_download helper that fetches model checkpoint and MHR model from Hugging Face snapshots', 'run the SAM3DBodyEstimator to estimate 3D body pose, keypoints, and mesh from a single input image', 'run full-body inference with both body and hand decoders using process_one_image with inference_type set to full', 'run body-only inference using process_one_image with inference_type set to body to skip hand decoder', 'run hand-only inference using process_one_image with inference_type set to hand for hand pose estimation', 'run mask-conditioned inference by providing pre-computed masks and bboxes to process_one_image with use_mask enabled']
```

Usage

```
{'run_3d_body_estimation': 'run the SAM3DBodyEstimator to estimate 3D body pose, keypoints, and mesh from a single input image', 'run_full_body_inference': 'run full-body inference with both body and hand decoders using process_one_image with inference_type set to full', 'run_body_only_inference': 'run body-only inference using process_one_image with inference_type set to body to skip hand decoder', 'run_hand_only_inference': 'run hand-only inference using process_one_image with inference_type set to hand for hand pose estimation', 'run_mask_conditioned_inference': 'run mask-conditioned inference by providing pre-computed masks and bboxes to process_one_image with use_mask enabled'}
```

