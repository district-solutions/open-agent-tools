# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/polygen/data_utils.py

Prompts

```
['read vertices and faces from an OBJ file and return numpy arrays', 'write vertices and faces to an OBJ file with optional transpose and scaling', 'process mesh vertices and faces by centering, scaling, quantizing, and flattening', 'convert vertices in [-1, 1] range to discrete integer values for quantization', 'plot 3D mesh data with vertices, faces, and point clouds using matplotlib', 'run the VertexModelTest to verify the vertex model runs without crashing', 'run the FaceModelTest to verify the face model runs without crashing', 'test that VertexModel sample outputs fall within the quantization bit range', 'test that FaceModel sample outputs fall within the valid vertex index range', 'review the VertexModelTest class and its test_model_runs and test_sample_outputs_range methods', 'build a TransformerEncoder module with configurable hidden size, attention heads, and layer count for sequence encoding', 'build a TransformerDecoder module with cross-attention support and caching for autoregressive sequence decoding', 'build a VertexModel autoregressive generative model that samples quantized mesh vertex sequences with top-k and top-p sampling', 'build a FaceModel autoregressive generative model that samples n-gon mesh faces using pointer networks over vertex embeddings', 'build a ResNet module for 2D image or 3D voxel inputs with configurable residual blocks and downsampling']
```

Usage

```
{'read_obj_file': 'read vertices and faces from an OBJ file and return numpy arrays', 'write_obj': 'write vertices and faces to an OBJ file with optional transpose and scaling', 'process_mesh': 'process mesh vertices and faces by centering, scaling, quantizing, and flattening', 'quantize_verts': 'convert vertices in [-1, 1] range to discrete integer values for quantization', 'plot_meshes': 'plot 3D mesh data with vertices, faces, and point clouds using matplotlib'}
```

## File: google-deepmind_deepmind-research/polygen/model_test.py

Prompts

```
['read vertices and faces from an OBJ file and return numpy arrays', 'write vertices and faces to an OBJ file with optional transpose and scaling', 'process mesh vertices and faces by centering, scaling, quantizing, and flattening', 'convert vertices in [-1, 1] range to discrete integer values for quantization', 'plot 3D mesh data with vertices, faces, and point clouds using matplotlib', 'run the VertexModelTest to verify the vertex model runs without crashing', 'run the FaceModelTest to verify the face model runs without crashing', 'test that VertexModel sample outputs fall within the quantization bit range', 'test that FaceModel sample outputs fall within the valid vertex index range', 'review the VertexModelTest class and its test_model_runs and test_sample_outputs_range methods', 'build a TransformerEncoder module with configurable hidden size, attention heads, and layer count for sequence encoding', 'build a TransformerDecoder module with cross-attention support and caching for autoregressive sequence decoding', 'build a VertexModel autoregressive generative model that samples quantized mesh vertex sequences with top-k and top-p sampling', 'build a FaceModel autoregressive generative model that samples n-gon mesh faces using pointer networks over vertex embeddings', 'build a ResNet module for 2D image or 3D voxel inputs with configurable residual blocks and downsampling']
```

Usage

```
{'run_vertex_model_test': 'run the VertexModelTest to verify the vertex model runs without crashing', 'run_face_model_test': 'run the FaceModelTest to verify the face model runs without crashing', 'test_vertex_model_sample_range': 'test that VertexModel sample outputs fall within the quantization bit range', 'test_face_model_sample_range': 'test that FaceModel sample outputs fall within the valid vertex index range', 'review_vertexmodeltest_class': 'review the VertexModelTest class and its test_model_runs and test_sample_outputs_range methods'}
```

## File: google-deepmind_deepmind-research/polygen/modules.py

Prompts

```
['read vertices and faces from an OBJ file and return numpy arrays', 'write vertices and faces to an OBJ file with optional transpose and scaling', 'process mesh vertices and faces by centering, scaling, quantizing, and flattening', 'convert vertices in [-1, 1] range to discrete integer values for quantization', 'plot 3D mesh data with vertices, faces, and point clouds using matplotlib', 'run the VertexModelTest to verify the vertex model runs without crashing', 'run the FaceModelTest to verify the face model runs without crashing', 'test that VertexModel sample outputs fall within the quantization bit range', 'test that FaceModel sample outputs fall within the valid vertex index range', 'review the VertexModelTest class and its test_model_runs and test_sample_outputs_range methods', 'build a TransformerEncoder module with configurable hidden size, attention heads, and layer count for sequence encoding', 'build a TransformerDecoder module with cross-attention support and caching for autoregressive sequence decoding', 'build a VertexModel autoregressive generative model that samples quantized mesh vertex sequences with top-k and top-p sampling', 'build a FaceModel autoregressive generative model that samples n-gon mesh faces using pointer networks over vertex embeddings', 'build a ResNet module for 2D image or 3D voxel inputs with configurable residual blocks and downsampling']
```

Usage

```
{'build_transformer_encoder': 'build a TransformerEncoder module with configurable hidden size, attention heads, and layer count for sequence encoding', 'build_transformer_decoder': 'build a TransformerDecoder module with cross-attention support and caching for autoregressive sequence decoding', 'build_vertex_model': 'build a VertexModel autoregressive generative model that samples quantized mesh vertex sequences with top-k and top-p sampling', 'build_face_model': 'build a FaceModel autoregressive generative model that samples n-gon mesh faces using pointer networks over vertex embeddings', 'build_resnet': 'build a ResNet module for 2D image or 3D voxel inputs with configurable residual blocks and downsampling'}
```

