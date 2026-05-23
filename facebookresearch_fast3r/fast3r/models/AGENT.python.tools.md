# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/fast3r/models/fast3r.py

Prompts

```
['build a Fast3R model with croco encoder, fast3r decoder, and dpt head for image-to-3d reconstruction', 'run the Fast3R forward pass on a list of view dicts to get 3D point predictions', 'load a Dust3R checkpoint into a Fast3R model to initialize encoder and head weights', 'build a CroCoEncoder with RoPE positional embeddings and configurable transformer blocks for image encoding', 'build a LlamaDecoder with precomputed freqs_cis and view0 embedding for object-centric 3D decoding', 'load a Fast3R network into MultiViewDUSt3RLitModule for inference using the load_for_inference class method', 'run multi-view DUSt3R training with a LightningModule that handles loss computation and metric logging', 'estimate camera poses and focal lengths from predicted 3D points using the estimate_camera_poses static method', 'align local head predicted 3D points to the global coordinate frame using rigid point registration', 'estimate focal length from predicted 3D points and confidence maps using the estimate_focal function']
```

Usage

```
{'build_Fast3R_model': 'build a Fast3R model with croco encoder, fast3r decoder, and dpt head for image-to-3d reconstruction', 'run_Fast3R_forward': 'run the Fast3R forward pass on a list of view dicts to get 3D point predictions', 'load_Fast3R_from_dust3r_checkpoint': 'load a Dust3R checkpoint into a Fast3R model to initialize encoder and head weights', 'build_CroCoEncoder': 'build a CroCoEncoder with RoPE positional embeddings and configurable transformer blocks for image encoding', 'build_LlamaDecoder': 'build a LlamaDecoder with precomputed freqs_cis and view0 embedding for object-centric 3D decoding'}
```

## File: facebookresearch_fast3r/fast3r/models/multiview_dust3r_module.py

Prompts

```
['build a Fast3R model with croco encoder, fast3r decoder, and dpt head for image-to-3d reconstruction', 'run the Fast3R forward pass on a list of view dicts to get 3D point predictions', 'load a Dust3R checkpoint into a Fast3R model to initialize encoder and head weights', 'build a CroCoEncoder with RoPE positional embeddings and configurable transformer blocks for image encoding', 'build a LlamaDecoder with precomputed freqs_cis and view0 embedding for object-centric 3D decoding', 'load a Fast3R network into MultiViewDUSt3RLitModule for inference using the load_for_inference class method', 'run multi-view DUSt3R training with a LightningModule that handles loss computation and metric logging', 'estimate camera poses and focal lengths from predicted 3D points using the estimate_camera_poses static method', 'align local head predicted 3D points to the global coordinate frame using rigid point registration', 'estimate focal length from predicted 3D points and confidence maps using the estimate_focal function']
```

Usage

```
{'load_MultiViewDUSt3RLitModule_for_inference': 'load a Fast3R network into MultiViewDUSt3RLitModule for inference using the load_for_inference class method', 'run_MultiViewDUSt3RLitModule_training': 'run multi-view DUSt3R training with a LightningModule that handles loss computation and metric logging', 'estimate_camera_poses_from_predictions': 'estimate camera poses and focal lengths from predicted 3D points using the estimate_camera_poses static method', 'align_local_pts3d_to_global': 'align local head predicted 3D points to the global coordinate frame using rigid point registration', 'estimate_focal_from_depth_and_confidence': 'estimate focal length from predicted 3D points and confidence maps using the estimate_focal function'}
```

