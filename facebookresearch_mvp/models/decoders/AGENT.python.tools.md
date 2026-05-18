# Agent Python Tools

- repo: facebookresearch/mvp
- repo_uri: https://github.com/facebookresearch/mvp

## File: facebookresearch_mvp/models/decoders/mvp.py

Prompts

```
['build a python module to instantiate the MVP Decoder with mesh topology data and primitive configuration', 'create a SlabContentDecoder with 2D or 3D convolutions for RGBA primitive content decoding', 'create a DeconvMotionModel that decodes primitive position, rotation, and scale deltas from an encoding', 'run compute_tbn to compute the tangent-bitangent-normal rotation matrix from mesh vertex and texture coordinates', 'run compute_postex to compute 3D coordinates of each texel in a UV map using barycentric interpolation', 'build a Decoder module with conv decoder type and 128 primitive size for neural volume rendering', 'create a ContentDecoder that upsamples from 4x4x4 to 128x128x128 using transposed 3D convolutions', 'test the Decoder forward pass with a 256-dim encoding tensor and camera view position', 'review the ContentDecoder forward method and its channels-last tensor reordering logic', 'refactor the Decoder to use a shared RGBA branch instead of separate RGB and alpha decoders']
```

Usage

```
{'build_Decoder': 'build a python module to instantiate the MVP Decoder with mesh topology data and primitive configuration', 'create_SlabContentDecoder': 'create a SlabContentDecoder with 2D or 3D convolutions for RGBA primitive content decoding', 'create_DeconvMotionModel': 'create a DeconvMotionModel that decodes primitive position, rotation, and scale deltas from an encoding', 'run_compute_tbn': 'run compute_tbn to compute the tangent-bitangent-normal rotation matrix from mesh vertex and texture coordinates', 'run_compute_postex': 'run compute_postex to compute 3D coordinates of each texel in a UV map using barycentric interpolation'}
```

## File: facebookresearch_mvp/models/decoders/nv.py

Prompts

```
['build a python module to instantiate the MVP Decoder with mesh topology data and primitive configuration', 'create a SlabContentDecoder with 2D or 3D convolutions for RGBA primitive content decoding', 'create a DeconvMotionModel that decodes primitive position, rotation, and scale deltas from an encoding', 'run compute_tbn to compute the tangent-bitangent-normal rotation matrix from mesh vertex and texture coordinates', 'run compute_postex to compute 3D coordinates of each texel in a UV map using barycentric interpolation', 'build a Decoder module with conv decoder type and 128 primitive size for neural volume rendering', 'create a ContentDecoder that upsamples from 4x4x4 to 128x128x128 using transposed 3D convolutions', 'test the Decoder forward pass with a 256-dim encoding tensor and camera view position', 'review the ContentDecoder forward method and its channels-last tensor reordering logic', 'refactor the Decoder to use a shared RGBA branch instead of separate RGB and alpha decoders']
```

Usage

```
{'build_decoder_for_neural_volumes': 'build a Decoder module with conv decoder type and 128 primitive size for neural volume rendering', 'create_content_decoder_with_3d_upsampling': 'create a ContentDecoder that upsamples from 4x4x4 to 128x128x128 using transposed 3D convolutions', 'test_decoder_forward_with_encoding': 'test the Decoder forward pass with a 256-dim encoding tensor and camera view position', 'review_ContentDecoder_channel_reordering': 'review the ContentDecoder forward method and its channels-last tensor reordering logic', 'refactor_Decoder_shared_rgba_branch': 'refactor the Decoder to use a shared RGBA branch instead of separate RGB and alpha decoders'}
```

