# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/models/video_gpt/gpt.py

Prompts

```
['build a MultimodalGPT model for cross-modality generation with input and output tokenizers and a multimodal transformer decoder', 'create a TransformerDecoder with stacked TransformerDecoderLayer instances for processing multimodal embedding sequences', 'create a TransformerDecoderLayer with multi-head self-attention and MLP blocks using pre-LN normalization', 'run the RightShift module to prepend a learnable SOS token and shift embedding vectors right along the sequence dimension', 'review the MultimodalTransformerDecoder class that concatenates input and output modality embeddings with position embeddings before decoding', 'build a VideoGPT model with default parameters for video generation using VQ-VAE and Transformers', 'build a VideoGPT model with custom input shape, latent shape, and number of decoder layers', 'build a Video VQ-VAE tokenizer with default convolution filter sizes and strides', 'build a Video VQ-VAE with custom embedding dimension, codebook size, and residual layers', 'review the VideoGPT model architecture including tokenizer construction, projection layers, and multimodal decoder', 'build a Video VQ-VAE model using video_vqvae with encoder, decoder, and codebook parameters', 'create a VideoEncoder with SamePadConv3d layers and AttentionResidualBlocks for encoding video data', 'create a VideoDecoder with SamePadConvTranspose3d layers and AttentionResidualBlocks for decoding video data', 'review the AxialAttentionBlock class that computes multihead axial attention across all input dimensions', 'test the AttentionResidualBlock class with axial attention and residual connections for video data']
```

Usage

```
{'build_MultimodalGPT': 'build a MultimodalGPT model for cross-modality generation with input and output tokenizers and a multimodal transformer decoder', 'create_TransformerDecoder': 'create a TransformerDecoder with stacked TransformerDecoderLayer instances for processing multimodal embedding sequences', 'create_TransformerDecoderLayer': 'create a TransformerDecoderLayer with multi-head self-attention and MLP blocks using pre-LN normalization', 'run_RightShift': 'run the RightShift module to prepend a learnable SOS token and shift embedding vectors right along the sequence dimension', 'review_MultimodalTransformerDecoder': 'review the MultimodalTransformerDecoder class that concatenates input and output modality embeddings with position embeddings before decoding'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/video_gpt/model.py

Prompts

```
['build a MultimodalGPT model for cross-modality generation with input and output tokenizers and a multimodal transformer decoder', 'create a TransformerDecoder with stacked TransformerDecoderLayer instances for processing multimodal embedding sequences', 'create a TransformerDecoderLayer with multi-head self-attention and MLP blocks using pre-LN normalization', 'run the RightShift module to prepend a learnable SOS token and shift embedding vectors right along the sequence dimension', 'review the MultimodalTransformerDecoder class that concatenates input and output modality embeddings with position embeddings before decoding', 'build a VideoGPT model with default parameters for video generation using VQ-VAE and Transformers', 'build a VideoGPT model with custom input shape, latent shape, and number of decoder layers', 'build a Video VQ-VAE tokenizer with default convolution filter sizes and strides', 'build a Video VQ-VAE with custom embedding dimension, codebook size, and residual layers', 'review the VideoGPT model architecture including tokenizer construction, projection layers, and multimodal decoder', 'build a Video VQ-VAE model using video_vqvae with encoder, decoder, and codebook parameters', 'create a VideoEncoder with SamePadConv3d layers and AttentionResidualBlocks for encoding video data', 'create a VideoDecoder with SamePadConvTranspose3d layers and AttentionResidualBlocks for decoding video data', 'review the AxialAttentionBlock class that computes multihead axial attention across all input dimensions', 'test the AttentionResidualBlock class with axial attention and residual connections for video data']
```

Usage

```
{'build_video_gpt_model': 'build a VideoGPT model with default parameters for video generation using VQ-VAE and Transformers', 'build_video_gpt_custom': 'build a VideoGPT model with custom input shape, latent shape, and number of decoder layers', 'build_video_vqvae': 'build a Video VQ-VAE tokenizer with default convolution filter sizes and strides', 'build_video_vqvae_custom': 'build a Video VQ-VAE with custom embedding dimension, codebook size, and residual layers', 'review_video_gpt_architecture': 'review the VideoGPT model architecture including tokenizer construction, projection layers, and multimodal decoder'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/video_gpt/video_vqvae.py

Prompts

```
['build a MultimodalGPT model for cross-modality generation with input and output tokenizers and a multimodal transformer decoder', 'create a TransformerDecoder with stacked TransformerDecoderLayer instances for processing multimodal embedding sequences', 'create a TransformerDecoderLayer with multi-head self-attention and MLP blocks using pre-LN normalization', 'run the RightShift module to prepend a learnable SOS token and shift embedding vectors right along the sequence dimension', 'review the MultimodalTransformerDecoder class that concatenates input and output modality embeddings with position embeddings before decoding', 'build a VideoGPT model with default parameters for video generation using VQ-VAE and Transformers', 'build a VideoGPT model with custom input shape, latent shape, and number of decoder layers', 'build a Video VQ-VAE tokenizer with default convolution filter sizes and strides', 'build a Video VQ-VAE with custom embedding dimension, codebook size, and residual layers', 'review the VideoGPT model architecture including tokenizer construction, projection layers, and multimodal decoder', 'build a Video VQ-VAE model using video_vqvae with encoder, decoder, and codebook parameters', 'create a VideoEncoder with SamePadConv3d layers and AttentionResidualBlocks for encoding video data', 'create a VideoDecoder with SamePadConvTranspose3d layers and AttentionResidualBlocks for decoding video data', 'review the AxialAttentionBlock class that computes multihead axial attention across all input dimensions', 'test the AttentionResidualBlock class with axial attention and residual connections for video data']
```

Usage

```
{'build_video_vqvae_model': 'build a Video VQ-VAE model using video_vqvae with encoder, decoder, and codebook parameters', 'create_video_encoder': 'create a VideoEncoder with SamePadConv3d layers and AttentionResidualBlocks for encoding video data', 'create_video_decoder': 'create a VideoDecoder with SamePadConvTranspose3d layers and AttentionResidualBlocks for decoding video data', 'review_axial_attention_block': 'review the AxialAttentionBlock class that computes multihead axial attention across all input dimensions', 'test_attention_residual_block': 'test the AttentionResidualBlock class with axial attention and residual connections for video data'}
```

