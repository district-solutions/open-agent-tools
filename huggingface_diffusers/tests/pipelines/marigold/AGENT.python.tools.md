# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/marigold/test_marigold_depth.py

Prompts

```
['run the MarigoldDepthPipelineFastTests unit tests with dummy components and expected output slices', 'run the MarigoldDepthPipelineIntegrationTests slow tests using pretrained model prs-eth/marigold-lcm-v1-0', 'test the get_dummy_components method that creates a UNet, LCMScheduler, VAE, and CLIP text encoder', 'test the MarigoldDepthPipeline with ensemble_size and ensembling_kwargs reduction mean for depth prediction', 'test the MarigoldDepthPipeline with match_input_resolution true or false and various processing resolutions', 'run the fast unit tests for MarigoldIntrinsicsPipeline using dummy components and small inputs', 'run the slow integration tests for MarigoldIntrinsicsPipeline with pretrained models on GPU', 'test batch inference consistency and identical output behavior for MarigoldIntrinsicsPipeline', 'test the dummy component creation method that builds a minimal UNet, VAE, scheduler, and CLIP text encoder', 'test the dummy input generation method that creates a random image tensor and generator for pipeline inference', 'run the MarigoldNormalsPipelineFastTests to validate pipeline with dummy UNet, VAE, and scheduler components', 'run the MarigoldNormalsPipelineIntegrationTests to validate pipeline with pretrained model prs-eth/marigold-normals-lcm-v0-1', 'test the MarigoldNormalsPipeline with default parameters and verify output slice values match expected', 'test the MarigoldNormalsPipeline with ensemble size 4 and batch size 2 using mean reduction', 'test the MarigoldNormalsPipeline in fp16 precision on CUDA with processing resolution 768']
```

Usage

```
{'run_MarigoldDepthPipeline_fast_tests': 'run the MarigoldDepthPipelineFastTests unit tests with dummy components and expected output slices', 'run_MarigoldDepthPipeline_integration_tests': 'run the MarigoldDepthPipelineIntegrationTests slow tests using pretrained model prs-eth/marigold-lcm-v1-0', 'test_MarigoldDepthPipeline_get_dummy_components': 'test the get_dummy_components method that creates a UNet, LCMScheduler, VAE, and CLIP text encoder', 'test_MarigoldDepthPipeline_ensemble_depth': 'test the MarigoldDepthPipeline with ensemble_size and ensembling_kwargs reduction mean for depth prediction', 'test_MarigoldDepthPipeline_resolution_modes': 'test the MarigoldDepthPipeline with match_input_resolution true or false and various processing resolutions'}
```

## File: huggingface_diffusers/tests/pipelines/marigold/test_marigold_intrinsics.py

Prompts

```
['run the MarigoldDepthPipelineFastTests unit tests with dummy components and expected output slices', 'run the MarigoldDepthPipelineIntegrationTests slow tests using pretrained model prs-eth/marigold-lcm-v1-0', 'test the get_dummy_components method that creates a UNet, LCMScheduler, VAE, and CLIP text encoder', 'test the MarigoldDepthPipeline with ensemble_size and ensembling_kwargs reduction mean for depth prediction', 'test the MarigoldDepthPipeline with match_input_resolution true or false and various processing resolutions', 'run the fast unit tests for MarigoldIntrinsicsPipeline using dummy components and small inputs', 'run the slow integration tests for MarigoldIntrinsicsPipeline with pretrained models on GPU', 'test batch inference consistency and identical output behavior for MarigoldIntrinsicsPipeline', 'test the dummy component creation method that builds a minimal UNet, VAE, scheduler, and CLIP text encoder', 'test the dummy input generation method that creates a random image tensor and generator for pipeline inference', 'run the MarigoldNormalsPipelineFastTests to validate pipeline with dummy UNet, VAE, and scheduler components', 'run the MarigoldNormalsPipelineIntegrationTests to validate pipeline with pretrained model prs-eth/marigold-normals-lcm-v0-1', 'test the MarigoldNormalsPipeline with default parameters and verify output slice values match expected', 'test the MarigoldNormalsPipeline with ensemble size 4 and batch size 2 using mean reduction', 'test the MarigoldNormalsPipeline in fp16 precision on CUDA with processing resolution 768']
```

Usage

```
{'run_MarigoldIntrinsicsPipelineFastTests': 'run the fast unit tests for MarigoldIntrinsicsPipeline using dummy components and small inputs', 'run_MarigoldIntrinsicsPipelineIntegrationTests': 'run the slow integration tests for MarigoldIntrinsicsPipeline with pretrained models on GPU', 'test_MarigoldIntrinsicsPipelineTesterMixin': 'test batch inference consistency and identical output behavior for MarigoldIntrinsicsPipeline', 'test_get_dummy_components': 'test the dummy component creation method that builds a minimal UNet, VAE, scheduler, and CLIP text encoder', 'test_get_dummy_inputs': 'test the dummy input generation method that creates a random image tensor and generator for pipeline inference'}
```

## File: huggingface_diffusers/tests/pipelines/marigold/test_marigold_normals.py

Prompts

```
['run the MarigoldDepthPipelineFastTests unit tests with dummy components and expected output slices', 'run the MarigoldDepthPipelineIntegrationTests slow tests using pretrained model prs-eth/marigold-lcm-v1-0', 'test the get_dummy_components method that creates a UNet, LCMScheduler, VAE, and CLIP text encoder', 'test the MarigoldDepthPipeline with ensemble_size and ensembling_kwargs reduction mean for depth prediction', 'test the MarigoldDepthPipeline with match_input_resolution true or false and various processing resolutions', 'run the fast unit tests for MarigoldIntrinsicsPipeline using dummy components and small inputs', 'run the slow integration tests for MarigoldIntrinsicsPipeline with pretrained models on GPU', 'test batch inference consistency and identical output behavior for MarigoldIntrinsicsPipeline', 'test the dummy component creation method that builds a minimal UNet, VAE, scheduler, and CLIP text encoder', 'test the dummy input generation method that creates a random image tensor and generator for pipeline inference', 'run the MarigoldNormalsPipelineFastTests to validate pipeline with dummy UNet, VAE, and scheduler components', 'run the MarigoldNormalsPipelineIntegrationTests to validate pipeline with pretrained model prs-eth/marigold-normals-lcm-v0-1', 'test the MarigoldNormalsPipeline with default parameters and verify output slice values match expected', 'test the MarigoldNormalsPipeline with ensemble size 4 and batch size 2 using mean reduction', 'test the MarigoldNormalsPipeline in fp16 precision on CUDA with processing resolution 768']
```

Usage

```
{'run_marigold_normals_fast_tests': 'run the MarigoldNormalsPipelineFastTests to validate pipeline with dummy UNet, VAE, and scheduler components', 'run_marigold_normals_integration_tests': 'run the MarigoldNormalsPipelineIntegrationTests to validate pipeline with pretrained model prs-eth/marigold-normals-lcm-v0-1', 'test_marigold_normals_dummy_defaults': 'test the MarigoldNormalsPipeline with default parameters and verify output slice values match expected', 'test_marigold_normals_ensemble_batch': 'test the MarigoldNormalsPipeline with ensemble size 4 and batch size 2 using mean reduction', 'test_marigold_normals_fp16_cuda': 'test the MarigoldNormalsPipeline in fp16 precision on CUDA with processing resolution 768'}
```

