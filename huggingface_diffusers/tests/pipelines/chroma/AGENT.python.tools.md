# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/chroma/test_pipeline_chroma.py

Prompts

```
['test ChromaPipeline to verify different prompts produce different image outputs', 'test ChromaPipeline fused QKV projections to verify outputs remain consistent after fusion', 'test ChromaPipeline image output shape matches expected dimensions for various height and width inputs', 'create dummy ChromaPipeline components including transformer, text encoder, tokenizer, VAE, and scheduler', 'create dummy input dictionary for ChromaPipeline with prompt, guidance scale, and inference steps', 'test the ChromaImg2ImgPipeline class by running fast unit tests with dummy components and inputs', 'run a test that verifies ChromaImg2ImgPipeline produces different outputs for different text prompts', 'test that fusing and unfusing QKV projections in the transformer does not affect pipeline outputs', 'create dummy transformer, text encoder, tokenizer, VAE, and scheduler components for ChromaImg2ImgPipeline testing']
```

Usage

```
{'test_chroma_pipeline_different_prompts': 'test ChromaPipeline to verify different prompts produce different image outputs', 'test_chroma_fused_qkv_projections': 'test ChromaPipeline fused QKV projections to verify outputs remain consistent after fusion', 'test_chroma_image_output_shape': 'test ChromaPipeline image output shape matches expected dimensions for various height and width inputs', 'create_chroma_dummy_components': 'create dummy ChromaPipeline components including transformer, text encoder, tokenizer, VAE, and scheduler', 'create_chroma_dummy_inputs': 'create dummy input dictionary for ChromaPipeline with prompt, guidance scale, and inference steps'}
```

## File: huggingface_diffusers/tests/pipelines/chroma/test_pipeline_chroma_img2img.py

Prompts

```
['test ChromaPipeline to verify different prompts produce different image outputs', 'test ChromaPipeline fused QKV projections to verify outputs remain consistent after fusion', 'test ChromaPipeline image output shape matches expected dimensions for various height and width inputs', 'create dummy ChromaPipeline components including transformer, text encoder, tokenizer, VAE, and scheduler', 'create dummy input dictionary for ChromaPipeline with prompt, guidance scale, and inference steps', 'test the ChromaImg2ImgPipeline class by running fast unit tests with dummy components and inputs', 'run a test that verifies ChromaImg2ImgPipeline produces different outputs for different text prompts', 'test that fusing and unfusing QKV projections in the transformer does not affect pipeline outputs', 'create dummy transformer, text encoder, tokenizer, VAE, and scheduler components for ChromaImg2ImgPipeline testing']
```

Usage

```
{'test_chroma_img2img_pipeline': 'test the ChromaImg2ImgPipeline class by running fast unit tests with dummy components and inputs', 'run_chroma_different_prompts_test': 'run a test that verifies ChromaImg2ImgPipeline produces different outputs for different text prompts', 'test_fused_qkv_projections': 'test that fusing and unfusing QKV projections in the transformer does not affect pipeline outputs', 'test_chroma_image_output_shape': 'test that ChromaImg2ImgPipeline produces images with the expected height and width dimensions', 'get_dummy_components_chroma': 'create dummy transformer, text encoder, tokenizer, VAE, and scheduler components for ChromaImg2ImgPipeline testing'}
```

