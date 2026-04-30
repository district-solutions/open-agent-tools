# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/normalbae/nets/NNET.py

Prompts

```
['build a python module to instantiate an NNET normal prediction model with encoder and decoder', 'run the NNET forward pass on an input image tensor to predict surface normals', 'test the NNET get_1x_lr_params method to retrieve encoder parameters for differential learning rates', 'test the NNET get_10x_lr_params method to retrieve decoder parameters for differential learning rates', 'review the NNET forward method that chains encoder features through the decoder for normal estimation', 'create an Encoder using pretrained EfficientNet-B5 backbone that extracts multi-scale features', 'create a Decoder with upsampling blocks that processes encoder features for 4-class output', 'test the NNET model by getting encoder and decoder parameters with different learning rates']
```

Usage

```
{'build_NNET_model': 'build a python module to instantiate an NNET normal prediction model with encoder and decoder', 'run_NNET_forward': 'run the NNET forward pass on an input image tensor to predict surface normals', 'test_NNET_get_1x_lr_params': 'test the NNET get_1x_lr_params method to retrieve encoder parameters for differential learning rates', 'test_NNET_get_10x_lr_params': 'test the NNET get_10x_lr_params method to retrieve decoder parameters for differential learning rates', 'review_NNET_forward': 'review the NNET forward method that chains encoder features through the decoder for normal estimation'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/normalbae/nets/baseline.py

Prompts

```
['build a python module to instantiate an NNET normal prediction model with encoder and decoder', 'run the NNET forward pass on an input image tensor to predict surface normals', 'test the NNET get_1x_lr_params method to retrieve encoder parameters for differential learning rates', 'test the NNET get_10x_lr_params method to retrieve decoder parameters for differential learning rates', 'review the NNET forward method that chains encoder features through the decoder for normal estimation', 'create an Encoder using pretrained EfficientNet-B5 backbone that extracts multi-scale features', 'create a Decoder with upsampling blocks that processes encoder features for 4-class output', 'test the NNET model by getting encoder and decoder parameters with different learning rates']
```

Usage

```
{'build_NNET_model': 'build a python module to create an NNET encoder-decoder model for surface normal estimation', 'run_NNET_forward': 'run the NNET model forward pass on an input tensor to get normalized output', 'create_Encoder': 'create an Encoder using pretrained EfficientNet-B5 backbone that extracts multi-scale features', 'create_Decoder': 'create a Decoder with upsampling blocks that processes encoder features for 4-class output', 'test_NNET_parameters': 'test the NNET model by getting encoder and decoder parameters with different learning rates'}
```

