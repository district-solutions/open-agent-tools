# Agent Python Tools

- repo: facebookresearch/meshtalk
- repo_uri: https://github.com/facebookresearch/meshtalk

## File: facebookresearch_meshtalk/models/context_model.py

Prompts

```
['create a MaskedContextConvolution layer with specified input output channels heads and audio dimension', 'build a ContextModel with configurable classes heads and audio dimension for audio driven expression prediction', 'run the ContextModel forward pass with one hot expression and audio code tensors to get logprobs', 'run the ContextModel sample method to generate one hot latent codes from audio embeddings using Gumbel softmax', 'review the MaskedContextConvolution forward_inference method for step by step autoregressive inference with masked head dependencies', 'build a Python module to encode 16kHz audio into latent embeddings using AudioEncoder with mel-spectrogram and dilated convolutions', 'build a Python module to encode face mesh geometries into latent expression embeddings using ExpressionEncoder with an LSTM', 'build a Python module to fuse expression and audio codes into categorical logprobs using FusionMlp with Gumbel softmax heads', 'build a Python module to jointly encode face geometry and audio into fused categorical logprobs using MultimodalEncoder', 'test the MultimodalEncoder forward pass with face geometry and audio tensors to verify logprobs output', 'build a VertexUnet model to generate animated face meshes from neutral templates and expression encodings', 'run the VertexUnet forward pass with geometry and expression encoding tensors to predict animated face meshes', 'create a VertexUnet encoder to compress neutral face mesh vertices into 128-dimensional latent encodings', 'test the VertexUnet fusion layer that combines geometric and expression encodings into a unified latent representation', 'review the VertexUnet decoder with LSTM temporal modeling and skip connections to reconstruct animated face meshes']
```

Usage

```
{'create_MaskedContextConvolution': 'create a MaskedContextConvolution layer with specified input output channels heads and audio dimension', 'build_ContextModel': 'build a ContextModel with configurable classes heads and audio dimension for audio driven expression prediction', 'run_ContextModel_forward': 'run the ContextModel forward pass with one hot expression and audio code tensors to get logprobs', 'run_ContextModel_sample': 'run the ContextModel sample method to generate one hot latent codes from audio embeddings using Gumbel softmax', 'review_MaskedContextConvolution_forward_inference': 'review the MaskedContextConvolution forward_inference method for step by step autoregressive inference with masked head dependencies'}
```

## File: facebookresearch_meshtalk/models/encoders.py

Prompts

```
['create a MaskedContextConvolution layer with specified input output channels heads and audio dimension', 'build a ContextModel with configurable classes heads and audio dimension for audio driven expression prediction', 'run the ContextModel forward pass with one hot expression and audio code tensors to get logprobs', 'run the ContextModel sample method to generate one hot latent codes from audio embeddings using Gumbel softmax', 'review the MaskedContextConvolution forward_inference method for step by step autoregressive inference with masked head dependencies', 'build a Python module to encode 16kHz audio into latent embeddings using AudioEncoder with mel-spectrogram and dilated convolutions', 'build a Python module to encode face mesh geometries into latent expression embeddings using ExpressionEncoder with an LSTM', 'build a Python module to fuse expression and audio codes into categorical logprobs using FusionMlp with Gumbel softmax heads', 'build a Python module to jointly encode face geometry and audio into fused categorical logprobs using MultimodalEncoder', 'test the MultimodalEncoder forward pass with face geometry and audio tensors to verify logprobs output', 'build a VertexUnet model to generate animated face meshes from neutral templates and expression encodings', 'run the VertexUnet forward pass with geometry and expression encoding tensors to predict animated face meshes', 'create a VertexUnet encoder to compress neutral face mesh vertices into 128-dimensional latent encodings', 'test the VertexUnet fusion layer that combines geometric and expression encodings into a unified latent representation', 'review the VertexUnet decoder with LSTM temporal modeling and skip connections to reconstruct animated face meshes']
```

Usage

```
{'build_audio_encoder': 'build a Python module to encode 16kHz audio into latent embeddings using AudioEncoder with mel-spectrogram and dilated convolutions', 'build_expression_encoder': 'build a Python module to encode face mesh geometries into latent expression embeddings using ExpressionEncoder with an LSTM', 'build_fusion_mlp': 'build a Python module to fuse expression and audio codes into categorical logprobs using FusionMlp with Gumbel softmax heads', 'build_multimodal_encoder': 'build a Python module to jointly encode face geometry and audio into fused categorical logprobs using MultimodalEncoder', 'test_multimodal_encoder_forward': 'test the MultimodalEncoder forward pass with face geometry and audio tensors to verify logprobs output'}
```

## File: facebookresearch_meshtalk/models/vertex_unet.py

Prompts

```
['create a MaskedContextConvolution layer with specified input output channels heads and audio dimension', 'build a ContextModel with configurable classes heads and audio dimension for audio driven expression prediction', 'run the ContextModel forward pass with one hot expression and audio code tensors to get logprobs', 'run the ContextModel sample method to generate one hot latent codes from audio embeddings using Gumbel softmax', 'review the MaskedContextConvolution forward_inference method for step by step autoregressive inference with masked head dependencies', 'build a Python module to encode 16kHz audio into latent embeddings using AudioEncoder with mel-spectrogram and dilated convolutions', 'build a Python module to encode face mesh geometries into latent expression embeddings using ExpressionEncoder with an LSTM', 'build a Python module to fuse expression and audio codes into categorical logprobs using FusionMlp with Gumbel softmax heads', 'build a Python module to jointly encode face geometry and audio into fused categorical logprobs using MultimodalEncoder', 'test the MultimodalEncoder forward pass with face geometry and audio tensors to verify logprobs output', 'build a VertexUnet model to generate animated face meshes from neutral templates and expression encodings', 'run the VertexUnet forward pass with geometry and expression encoding tensors to predict animated face meshes', 'create a VertexUnet encoder to compress neutral face mesh vertices into 128-dimensional latent encodings', 'test the VertexUnet fusion layer that combines geometric and expression encodings into a unified latent representation', 'review the VertexUnet decoder with LSTM temporal modeling and skip connections to reconstruct animated face meshes']
```

Usage

```
{'build_vertex_unet_model': 'build a VertexUnet model to generate animated face meshes from neutral templates and expression encodings', 'run_vertex_unet_forward': 'run the VertexUnet forward pass with geometry and expression encoding tensors to predict animated face meshes', 'create_vertex_unet_encoder': 'create a VertexUnet encoder to compress neutral face mesh vertices into 128-dimensional latent encodings', 'test_vertex_unet_fusion': 'test the VertexUnet fusion layer that combines geometric and expression encodings into a unified latent representation', 'review_vertex_unet_decoder': 'review the VertexUnet decoder with LSTM temporal modeling and skip connections to reconstruct animated face meshes'}
```

