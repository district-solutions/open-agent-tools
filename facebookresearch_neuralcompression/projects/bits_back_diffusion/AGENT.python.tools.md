# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/projects/bits_back_diffusion/encode.py

Prompts

```
['run the encode script to compress images using Bits-Back coding with a pretrained diffusion model', 'run the decode function to reconstruct compressed image batches from Bits-Back encoded data', 'run the main function with Hydra config to encode and optionally verify decoded image batches', 'encode image batches using a BitsBackCodec by quantizing and pushing data through the codec', 'decode compressed batches from a BitsBackCodec and save them as numpy files to disk', 'test the diagonal Gaussian codec with uniform bins using random mean and standard deviation data', 'test the Bits-Back codec for diffusion models by encoding and decoding discrete image data', 'create a CheatingDiffusionModel that uses the true posterior instead of the prior for diffusion', 'review the CheatingDiffusionModel generate_fn method that returns GaussianParams using the stored data', 'test the BitsBackCodec encode and decode roundtrip to verify data integrity and rate statistics']
```

Usage

```
{'run_encode_images_bits_back': 'run the encode script to compress images using Bits-Back coding with a pretrained diffusion model', 'run_decode_compressed_data': 'run the decode function to reconstruct compressed image batches from Bits-Back encoded data', 'run_main_with_hydra_config': 'run the main function with Hydra config to encode and optionally verify decoded image batches', 'encode_function_usage': 'encode image batches using a BitsBackCodec by quantizing and pushing data through the codec', 'decode_function_usage': 'decode compressed batches from a BitsBackCodec and save them as numpy files to disk'}
```

## File: facebookresearch_neuralcompression/projects/bits_back_diffusion/test.py

Prompts

```
['run the encode script to compress images using Bits-Back coding with a pretrained diffusion model', 'run the decode function to reconstruct compressed image batches from Bits-Back encoded data', 'run the main function with Hydra config to encode and optionally verify decoded image batches', 'encode image batches using a BitsBackCodec by quantizing and pushing data through the codec', 'decode compressed batches from a BitsBackCodec and save them as numpy files to disk', 'test the diagonal Gaussian codec with uniform bins using random mean and standard deviation data', 'test the Bits-Back codec for diffusion models by encoding and decoding discrete image data', 'create a CheatingDiffusionModel that uses the true posterior instead of the prior for diffusion', 'review the CheatingDiffusionModel generate_fn method that returns GaussianParams using the stored data', 'test the BitsBackCodec encode and decode roundtrip to verify data integrity and rate statistics']
```

Usage

```
{'test_gaussian_codec_with_uniform_bins': 'test the diagonal Gaussian codec with uniform bins using random mean and standard deviation data', 'test_bits_back_codec_for_diffusion': 'test the Bits-Back codec for diffusion models by encoding and decoding discrete image data', 'create_cheating_diffusion_model': 'create a CheatingDiffusionModel that uses the true posterior instead of the prior for diffusion', 'review_cheating_diffusion_model_generate_fn': 'review the CheatingDiffusionModel generate_fn method that returns GaussianParams using the stored data', 'test_codec_encode_decode_roundtrip': 'test the BitsBackCodec encode and decode roundtrip to verify data integrity and rate statistics'}
```

