# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/mugen/tests/generation/test_text_video_gpt.py

Prompts

```
['test the text_video_gpt model by encoding a text prompt into input tokens', 'test the text_video_gpt model by encoding a random video tensor into latent tokens', 'test the text_video_gpt model by decoding latent tokens back into a video tensor', 'test the text_video_gpt model lookup method for both input and output modalities', 'test the text_video_gpt forward pass with a pretrained GPT checkpoint', 'test the video_vqvae_mugen forward pass with random input tensors of varying sequence lengths', 'test the video_vqvae_mugen checkpoint loading with pretrained model keys like mugen_L8', 'test freezing all model parameters by setting freeze_model to True on video_vqvae_mugen', 'test that video_vqvae_mugen raises a KeyError when given an invalid pretrained model key', 'review the TestVideoVQVAEMUGEN pytest class and its parametrized test methods for video VQ-VAE generation']
```

Usage

```
{'test_encode_text': 'test the text_video_gpt model by encoding a text prompt into input tokens', 'test_encode_video': 'test the text_video_gpt model by encoding a random video tensor into latent tokens', 'test_decode_video': 'test the text_video_gpt model by decoding latent tokens back into a video tensor', 'test_lookup': 'test the text_video_gpt model lookup method for both input and output modalities', 'test_forward_gpt_pretrained': 'test the text_video_gpt forward pass with a pretrained GPT checkpoint'}
```

## File: facebookresearch_multimodal/examples/mugen/tests/generation/test_video_vqvae.py

Prompts

```
['test the text_video_gpt model by encoding a text prompt into input tokens', 'test the text_video_gpt model by encoding a random video tensor into latent tokens', 'test the text_video_gpt model by decoding latent tokens back into a video tensor', 'test the text_video_gpt model lookup method for both input and output modalities', 'test the text_video_gpt forward pass with a pretrained GPT checkpoint', 'test the video_vqvae_mugen forward pass with random input tensors of varying sequence lengths', 'test the video_vqvae_mugen checkpoint loading with pretrained model keys like mugen_L8', 'test freezing all model parameters by setting freeze_model to True on video_vqvae_mugen', 'test that video_vqvae_mugen raises a KeyError when given an invalid pretrained model key', 'review the TestVideoVQVAEMUGEN pytest class and its parametrized test methods for video VQ-VAE generation']
```

Usage

```
{'test_video_vqvae_forward_pass': 'test the video_vqvae_mugen forward pass with random input tensors of varying sequence lengths', 'test_video_vqvae_checkpoint_loading': 'test the video_vqvae_mugen checkpoint loading with pretrained model keys like mugen_L8', 'test_video_vqvae_freeze_model': 'test freezing all model parameters by setting freeze_model to True on video_vqvae_mugen', 'test_video_vqvae_invalid_key': 'test that video_vqvae_mugen raises a KeyError when given an invalid pretrained model key', 'review_TestVideoVQVAEMUGEN_class': 'review the TestVideoVQVAEMUGEN pytest class and its parametrized test methods for video VQ-VAE generation'}
```

