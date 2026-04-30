# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/flux2/test_pipeline_flux2.py

Prompts

```
['test the Flux2PipelineFastTests class to run all Flux2 pipeline unit tests', 'run get_dummy_components to create dummy transformer, text encoder, VAE, and scheduler for Flux2', 'run get_dummy_inputs to generate dummy input parameters for Flux2 pipeline inference', 'test fused QKV projections in Flux2 transformer to verify output consistency', 'test Flux2 pipeline image output shape validation for various height and width pairs', 'run the Flux2KleinPipelineFastTests unittest suite to verify pipeline functionality with dummy components', 'test that the Flux2KleinPipeline produces images with the expected height and width dimensions', 'test that the Flux2KleinPipeline correctly processes a PIL Image as input and generates expected output', 'create dummy transformer, text encoder, tokenizer, VAE, and scheduler components for testing Flux2KleinPipeline', 'test the Flux2KleinInpaintPipeline with dummy components and inputs for inpainting', 'test that Flux2KleinInpaintPipeline produces different outputs when given different text prompts', 'test that varying the strength parameter changes the inpainting output of the pipeline', 'test the Flux2KleinKVPipelineFastTests class to verify Flux2 Klein KV pipeline functionality with dummy components', 'test the Flux2KleinKVPipeline without an image input to verify text-only generation works', 'create dummy components including transformer, text encoder, tokenizer, VAE, and scheduler for Flux2KleinKVPipeline testing']
```

Usage

```
{'test_Flux2PipelineFastTests': 'test the Flux2PipelineFastTests class to run all Flux2 pipeline unit tests', 'run_get_dummy_components': 'run get_dummy_components to create dummy transformer, text encoder, VAE, and scheduler for Flux2', 'run_get_dummy_inputs': 'run get_dummy_inputs to generate dummy input parameters for Flux2 pipeline inference', 'test_fused_qkv_projections': 'test fused QKV projections in Flux2 transformer to verify output consistency', 'test_flux_image_output_shape': 'test Flux2 pipeline image output shape validation for various height and width pairs'}
```

## File: huggingface_diffusers/tests/pipelines/flux2/test_pipeline_flux2_klein.py

Prompts

```
['test the Flux2PipelineFastTests class to run all Flux2 pipeline unit tests', 'run get_dummy_components to create dummy transformer, text encoder, VAE, and scheduler for Flux2', 'run get_dummy_inputs to generate dummy input parameters for Flux2 pipeline inference', 'test fused QKV projections in Flux2 transformer to verify output consistency', 'test Flux2 pipeline image output shape validation for various height and width pairs', 'run the Flux2KleinPipelineFastTests unittest suite to verify pipeline functionality with dummy components', 'test that the Flux2KleinPipeline produces images with the expected height and width dimensions', 'test that the Flux2KleinPipeline correctly processes a PIL Image as input and generates expected output', 'create dummy transformer, text encoder, tokenizer, VAE, and scheduler components for testing Flux2KleinPipeline', 'test the Flux2KleinInpaintPipeline with dummy components and inputs for inpainting', 'test that Flux2KleinInpaintPipeline produces different outputs when given different text prompts', 'test that varying the strength parameter changes the inpainting output of the pipeline', 'test the Flux2KleinKVPipelineFastTests class to verify Flux2 Klein KV pipeline functionality with dummy components', 'test the Flux2KleinKVPipeline without an image input to verify text-only generation works', 'create dummy components including transformer, text encoder, tokenizer, VAE, and scheduler for Flux2KleinKVPipeline testing']
```

Usage

```
{'test_Flux2KleinPipeline_fast_tests': 'run the Flux2KleinPipelineFastTests unittest suite to verify pipeline functionality with dummy components', 'test_fused_qkv_projections': 'test that fusing and unfusing QKV projections in the transformer does not change pipeline outputs', 'test_image_output_shape': 'test that the Flux2KleinPipeline produces images with the expected height and width dimensions', 'test_image_input': 'test that the Flux2KleinPipeline correctly processes a PIL Image as input and generates expected output', 'get_dummy_components_Flux2KleinPipeline': 'create dummy transformer, text encoder, tokenizer, VAE, and scheduler components for testing Flux2KleinPipeline'}
```

## File: huggingface_diffusers/tests/pipelines/flux2/test_pipeline_flux2_klein_inpaint.py

Prompts

```
['test the Flux2PipelineFastTests class to run all Flux2 pipeline unit tests', 'run get_dummy_components to create dummy transformer, text encoder, VAE, and scheduler for Flux2', 'run get_dummy_inputs to generate dummy input parameters for Flux2 pipeline inference', 'test fused QKV projections in Flux2 transformer to verify output consistency', 'test Flux2 pipeline image output shape validation for various height and width pairs', 'run the Flux2KleinPipelineFastTests unittest suite to verify pipeline functionality with dummy components', 'test that the Flux2KleinPipeline produces images with the expected height and width dimensions', 'test that the Flux2KleinPipeline correctly processes a PIL Image as input and generates expected output', 'create dummy transformer, text encoder, tokenizer, VAE, and scheduler components for testing Flux2KleinPipeline', 'test the Flux2KleinInpaintPipeline with dummy components and inputs for inpainting', 'test that Flux2KleinInpaintPipeline produces different outputs when given different text prompts', 'test that varying the strength parameter changes the inpainting output of the pipeline', 'test the Flux2KleinKVPipelineFastTests class to verify Flux2 Klein KV pipeline functionality with dummy components', 'test the Flux2KleinKVPipeline without an image input to verify text-only generation works', 'create dummy components including transformer, text encoder, tokenizer, VAE, and scheduler for Flux2KleinKVPipeline testing']
```

Usage

```
{'test_Flux2KleinInpaintPipeline': 'test the Flux2KleinInpaintPipeline with dummy components and inputs for inpainting', 'run_get_dummy_components': 'run get_dummy_components to create minimal transformer, text encoder, tokenizer, vae, and scheduler', 'run_get_dummy_inputs': 'run get_dummy_inputs to generate test image, mask, and pipeline parameters for a device', 'test_inpaint_different_prompts': 'test that Flux2KleinInpaintPipeline produces different outputs when given different text prompts', 'test_inpaint_strength': 'test that varying the strength parameter changes the inpainting output of the pipeline'}
```

## File: huggingface_diffusers/tests/pipelines/flux2/test_pipeline_flux2_klein_kv.py

Prompts

```
['test the Flux2PipelineFastTests class to run all Flux2 pipeline unit tests', 'run get_dummy_components to create dummy transformer, text encoder, VAE, and scheduler for Flux2', 'run get_dummy_inputs to generate dummy input parameters for Flux2 pipeline inference', 'test fused QKV projections in Flux2 transformer to verify output consistency', 'test Flux2 pipeline image output shape validation for various height and width pairs', 'run the Flux2KleinPipelineFastTests unittest suite to verify pipeline functionality with dummy components', 'test that the Flux2KleinPipeline produces images with the expected height and width dimensions', 'test that the Flux2KleinPipeline correctly processes a PIL Image as input and generates expected output', 'create dummy transformer, text encoder, tokenizer, VAE, and scheduler components for testing Flux2KleinPipeline', 'test the Flux2KleinInpaintPipeline with dummy components and inputs for inpainting', 'test that Flux2KleinInpaintPipeline produces different outputs when given different text prompts', 'test that varying the strength parameter changes the inpainting output of the pipeline', 'test the Flux2KleinKVPipelineFastTests class to verify Flux2 Klein KV pipeline functionality with dummy components', 'test the Flux2KleinKVPipeline without an image input to verify text-only generation works', 'create dummy components including transformer, text encoder, tokenizer, VAE, and scheduler for Flux2KleinKVPipeline testing']
```

Usage

```
{'test_Flux2KleinKVPipelineFastTests': 'test the Flux2KleinKVPipelineFastTests class to verify Flux2 Klein KV pipeline functionality with dummy components', 'test_fused_qkv_projections': 'test the fused QKV projections in Flux2KleinKVPipeline to verify fusion and unfusion produce matching outputs', 'test_image_output_shape': 'test the Flux2KleinKVPipeline image output shape against expected height and width dimensions', 'test_without_image': 'test the Flux2KleinKVPipeline without an image input to verify text-only generation works', 'get_dummy_components': 'create dummy components including transformer, text encoder, tokenizer, VAE, and scheduler for Flux2KleinKVPipeline testing'}
```

