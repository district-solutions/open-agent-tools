# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/taming/models/cond_transformer.py

Prompts

```
['build a Net2NetTransformer model with transformer, first stage, and cond stage configs', 'sample conditional images from a Net2NetTransformer using temperature and top_k sampling', 'encode images to latent indices and decode them back to reconstructed images', 'train a Net2NetTransformer model using cross-entropy loss on image and conditioning inputs', 'configure an AdamW optimizer with selective weight decay for transformer parameters', 'create a DummyCondStage instance with a conditional key for pass-through conditioning', 'encode a torch Tensor using DummyCondStage to get a tuple with the original tensor', 'decode a torch Tensor using DummyCondStage and return the tensor unchanged', 'convert a torch Tensor to RGB format using DummyCondStage.to_rgb pass-through method', 'set a DummyCondStage instance to evaluation mode and return the instance', 'build a VQ-VAE model with encoder, decoder, and vector quantizer for image autoencoding', 'encode an input image tensor through the VQModel encoder and quantizer to get latent codes', 'decode quantized latent codes back to reconstructed images using the VQModel decoder', 'initialize a VQModel from a pretrained checkpoint file while optionally ignoring certain keys', 'create a Gumbel-Softmax VQ model with temperature scheduling for differentiable vector quantization']
```

Usage

```
{'build_cond_transformer_model': 'build a Net2NetTransformer model with transformer, first stage, and cond stage configs', 'sample_conditional_images': 'sample conditional images from a Net2NetTransformer using temperature and top_k sampling', 'encode_decode_latent_indices': 'encode images to latent indices and decode them back to reconstructed images', 'train_cond_transformer': 'train a Net2NetTransformer model using cross-entropy loss on image and conditioning inputs', 'configure_optimizer_with_weight_decay': 'configure an AdamW optimizer with selective weight decay for transformer parameters'}
```

## File: facebookresearch_stablesignature/src/taming/models/dummy_cond_stage.py

Prompts

```
['build a Net2NetTransformer model with transformer, first stage, and cond stage configs', 'sample conditional images from a Net2NetTransformer using temperature and top_k sampling', 'encode images to latent indices and decode them back to reconstructed images', 'train a Net2NetTransformer model using cross-entropy loss on image and conditioning inputs', 'configure an AdamW optimizer with selective weight decay for transformer parameters', 'create a DummyCondStage instance with a conditional key for pass-through conditioning', 'encode a torch Tensor using DummyCondStage to get a tuple with the original tensor', 'decode a torch Tensor using DummyCondStage and return the tensor unchanged', 'convert a torch Tensor to RGB format using DummyCondStage.to_rgb pass-through method', 'set a DummyCondStage instance to evaluation mode and return the instance', 'build a VQ-VAE model with encoder, decoder, and vector quantizer for image autoencoding', 'encode an input image tensor through the VQModel encoder and quantizer to get latent codes', 'decode quantized latent codes back to reconstructed images using the VQModel decoder', 'initialize a VQModel from a pretrained checkpoint file while optionally ignoring certain keys', 'create a Gumbel-Softmax VQ model with temperature scheduling for differentiable vector quantization']
```

Usage

```
{'create_DummyCondStage_instance': 'create a DummyCondStage instance with a conditional key for pass-through conditioning', 'encode_tensor_with_DummyCondStage': 'encode a torch Tensor using DummyCondStage to get a tuple with the original tensor', 'decode_tensor_with_DummyCondStage': 'decode a torch Tensor using DummyCondStage and return the tensor unchanged', 'convert_tensor_to_rgb': 'convert a torch Tensor to RGB format using DummyCondStage.to_rgb pass-through method', 'set_DummyCondStage_to_eval': 'set a DummyCondStage instance to evaluation mode and return the instance'}
```

## File: facebookresearch_stablesignature/src/taming/models/vqgan.py

Prompts

```
['build a Net2NetTransformer model with transformer, first stage, and cond stage configs', 'sample conditional images from a Net2NetTransformer using temperature and top_k sampling', 'encode images to latent indices and decode them back to reconstructed images', 'train a Net2NetTransformer model using cross-entropy loss on image and conditioning inputs', 'configure an AdamW optimizer with selective weight decay for transformer parameters', 'create a DummyCondStage instance with a conditional key for pass-through conditioning', 'encode a torch Tensor using DummyCondStage to get a tuple with the original tensor', 'decode a torch Tensor using DummyCondStage and return the tensor unchanged', 'convert a torch Tensor to RGB format using DummyCondStage.to_rgb pass-through method', 'set a DummyCondStage instance to evaluation mode and return the instance', 'build a VQ-VAE model with encoder, decoder, and vector quantizer for image autoencoding', 'encode an input image tensor through the VQModel encoder and quantizer to get latent codes', 'decode quantized latent codes back to reconstructed images using the VQModel decoder', 'initialize a VQModel from a pretrained checkpoint file while optionally ignoring certain keys', 'create a Gumbel-Softmax VQ model with temperature scheduling for differentiable vector quantization']
```

Usage

```
{'build_VQModel': 'build a VQ-VAE model with encoder, decoder, and vector quantizer for image autoencoding', 'encode_VQModel': 'encode an input image tensor through the VQModel encoder and quantizer to get latent codes', 'decode_VQModel': 'decode quantized latent codes back to reconstructed images using the VQModel decoder', 'init_from_ckpt_VQModel': 'initialize a VQModel from a pretrained checkpoint file while optionally ignoring certain keys', 'create_GumbelVQ': 'create a Gumbel-Softmax VQ model with temperature scheduling for differentiable vector quantization'}
```

