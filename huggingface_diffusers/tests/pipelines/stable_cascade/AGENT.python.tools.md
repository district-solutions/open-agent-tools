# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/pipelines/stable_cascade/test_stable_cascade_combined.py

Prompts

```
['run the StableCascadeCombinedPipelineFastTests to verify the StableCascadeCombinedPipeline generates correct image output', 'test the StableCascadeCombinedPipeline with sequential and model CPU offloading for memory efficiency', 'test batch inference with the StableCascadeCombinedPipeline to verify identical single batch results', 'create dummy model components including prior, decoder, VQGAN, text encoder, and tokenizer for testing', 'create dummy input parameters for the StableCascadeCombinedPipeline including prompt, guidance scales, and inference steps', 'test the StableCascadeDecoderPipeline with dummy components to verify image generation output shape and pixel values', 'test batch inference with single prompt and multiple image embeddings to verify correct output batch size', 'test the decoder pipeline with classifier-free guidance enabled to verify image generation with guidance scale', 'test attention slicing forward pass for the StableCascadeDecoderPipeline to verify memory optimization works correctly', 'test the StableCascadeDecoderPipeline integration with pretrained model from stabilityai/stable-cascade repository using bf16 precision', 'test the StableCascadePriorPipeline by running inference with a text prompt and verifying image embeddings output', 'test the Wuerstchen prior model by running dummy components through the pipeline and checking output slice values', 'test LoRA adapter integration with the prior model by adding a PEFT LoraConfig and comparing outputs', 'test the full StableCascadePriorPipeline integration using a pretrained model from HuggingFace with bf16 precision']
```

Usage

```
{'test_stable_cascade_combined_pipeline': 'run the StableCascadeCombinedPipelineFastTests to verify the StableCascadeCombinedPipeline generates correct image output', 'test_cpu_offload': 'test the StableCascadeCombinedPipeline with sequential and model CPU offloading for memory efficiency', 'test_inference_batch': 'test batch inference with the StableCascadeCombinedPipeline to verify identical single batch results', 'get_dummy_components': 'create dummy model components including prior, decoder, VQGAN, text encoder, and tokenizer for testing', 'get_dummy_inputs': 'create dummy input parameters for the StableCascadeCombinedPipeline including prompt, guidance scales, and inference steps'}
```

## File: huggingface_diffusers/tests/pipelines/stable_cascade/test_stable_cascade_decoder.py

Prompts

```
['run the StableCascadeCombinedPipelineFastTests to verify the StableCascadeCombinedPipeline generates correct image output', 'test the StableCascadeCombinedPipeline with sequential and model CPU offloading for memory efficiency', 'test batch inference with the StableCascadeCombinedPipeline to verify identical single batch results', 'create dummy model components including prior, decoder, VQGAN, text encoder, and tokenizer for testing', 'create dummy input parameters for the StableCascadeCombinedPipeline including prompt, guidance scales, and inference steps', 'test the StableCascadeDecoderPipeline with dummy components to verify image generation output shape and pixel values', 'test batch inference with single prompt and multiple image embeddings to verify correct output batch size', 'test the decoder pipeline with classifier-free guidance enabled to verify image generation with guidance scale', 'test attention slicing forward pass for the StableCascadeDecoderPipeline to verify memory optimization works correctly', 'test the StableCascadeDecoderPipeline integration with pretrained model from stabilityai/stable-cascade repository using bf16 precision', 'test the StableCascadePriorPipeline by running inference with a text prompt and verifying image embeddings output', 'test the Wuerstchen prior model by running dummy components through the pipeline and checking output slice values', 'test LoRA adapter integration with the prior model by adding a PEFT LoraConfig and comparing outputs', 'test the full StableCascadePriorPipeline integration using a pretrained model from HuggingFace with bf16 precision']
```

Usage

```
{'test_stable_cascade_decoder_pipeline': 'test the StableCascadeDecoderPipeline with dummy components to verify image generation output shape and pixel values', 'test_decoder_batch_inference': 'test batch inference with single prompt and multiple image embeddings to verify correct output batch size', 'test_decoder_guidance_scale': 'test the decoder pipeline with classifier-free guidance enabled to verify image generation with guidance scale', 'test_attention_slicing_forward_pass': 'test attention slicing forward pass for the StableCascadeDecoderPipeline to verify memory optimization works correctly', 'test_integration_stable_cascade_decoder': 'test the StableCascadeDecoderPipeline integration with pretrained model from stabilityai/stable-cascade repository using bf16 precision'}
```

## File: huggingface_diffusers/tests/pipelines/stable_cascade/test_stable_cascade_prior.py

Prompts

```
['run the StableCascadeCombinedPipelineFastTests to verify the StableCascadeCombinedPipeline generates correct image output', 'test the StableCascadeCombinedPipeline with sequential and model CPU offloading for memory efficiency', 'test batch inference with the StableCascadeCombinedPipeline to verify identical single batch results', 'create dummy model components including prior, decoder, VQGAN, text encoder, and tokenizer for testing', 'create dummy input parameters for the StableCascadeCombinedPipeline including prompt, guidance scales, and inference steps', 'test the StableCascadeDecoderPipeline with dummy components to verify image generation output shape and pixel values', 'test batch inference with single prompt and multiple image embeddings to verify correct output batch size', 'test the decoder pipeline with classifier-free guidance enabled to verify image generation with guidance scale', 'test attention slicing forward pass for the StableCascadeDecoderPipeline to verify memory optimization works correctly', 'test the StableCascadeDecoderPipeline integration with pretrained model from stabilityai/stable-cascade repository using bf16 precision', 'test the StableCascadePriorPipeline by running inference with a text prompt and verifying image embeddings output', 'test the Wuerstchen prior model by running dummy components through the pipeline and checking output slice values', 'test LoRA adapter integration with the prior model by adding a PEFT LoraConfig and comparing outputs', 'test the full StableCascadePriorPipeline integration using a pretrained model from HuggingFace with bf16 precision']
```

Usage

```
{'test_stable_cascade_prior_pipeline': 'test the StableCascadePriorPipeline by running inference with a text prompt and verifying image embeddings output', 'test_wuerstchen_prior_inference': 'test the Wuerstchen prior model by running dummy components through the pipeline and checking output slice values', 'test_attention_slicing_forward_pass': 'test attention slicing forward pass for the StableCascadePriorPipeline on CPU device', 'test_inference_with_prior_lora': 'test LoRA adapter integration with the prior model by adding a PEFT LoraConfig and comparing outputs', 'test_stable_cascade_prior_integration': 'test the full StableCascadePriorPipeline integration using a pretrained model from HuggingFace with bf16 precision'}
```

