# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/remote/test_remote_decode.py

Prompts

```
['test the remote_decode function with Stable Diffusion v1 endpoint using float16 latent tensors', 'test the remote_decode function with Stable Diffusion XL endpoint using 1024x1024 output dimensions', 'test the remote_decode function with Flux endpoint using bfloat16 dtype and shift_factor', 'test the remote_decode function with Hunyuan Video endpoint returning a list of PIL images', 'test the remote_decode function across multiple resolutions from 320x320 to 2048x2048', 'test remote encode and decode of images using the SD v1 autoencoder endpoint', 'test remote encode and decode of images using the SD XL autoencoder endpoint', 'test remote encode and decode of images using the Flux autoencoder endpoint', 'test remote encode and decode across multiple image resolutions for SD v1', 'review the RemoteAutoencoderKLEncodeMixin class and its test_image_input method for remote encoding tests']
```

Usage

```
{'test_remote_decode_sd_v1': 'test the remote_decode function with Stable Diffusion v1 endpoint using float16 latent tensors', 'test_remote_decode_sd_xl': 'test the remote_decode function with Stable Diffusion XL endpoint using 1024x1024 output dimensions', 'test_remote_decode_flux': 'test the remote_decode function with Flux endpoint using bfloat16 dtype and shift_factor', 'test_remote_decode_hunyuan_video': 'test the remote_decode function with Hunyuan Video endpoint returning a list of PIL images', 'test_remote_decode_multi_res': 'test the remote_decode function across multiple resolutions from 320x320 to 2048x2048'}
```

## File: huggingface_diffusers/tests/remote/test_remote_encode.py

Prompts

```
['test the remote_decode function with Stable Diffusion v1 endpoint using float16 latent tensors', 'test the remote_decode function with Stable Diffusion XL endpoint using 1024x1024 output dimensions', 'test the remote_decode function with Flux endpoint using bfloat16 dtype and shift_factor', 'test the remote_decode function with Hunyuan Video endpoint returning a list of PIL images', 'test the remote_decode function across multiple resolutions from 320x320 to 2048x2048', 'test remote encode and decode of images using the SD v1 autoencoder endpoint', 'test remote encode and decode of images using the SD XL autoencoder endpoint', 'test remote encode and decode of images using the Flux autoencoder endpoint', 'test remote encode and decode across multiple image resolutions for SD v1', 'review the RemoteAutoencoderKLEncodeMixin class and its test_image_input method for remote encoding tests']
```

Usage

```
{'test_remote_encode_sd_v1': 'test remote encode and decode of images using the SD v1 autoencoder endpoint', 'test_remote_encode_sd_xl': 'test remote encode and decode of images using the SD XL autoencoder endpoint', 'test_remote_encode_flux': 'test remote encode and decode of images using the Flux autoencoder endpoint', 'test_remote_encode_multi_res': 'test remote encode and decode across multiple image resolutions for SD v1', 'review_RemoteAutoencoderKLEncodeMixin': 'review the RemoteAutoencoderKLEncodeMixin class and its test_image_input method for remote encoding tests'}
```

