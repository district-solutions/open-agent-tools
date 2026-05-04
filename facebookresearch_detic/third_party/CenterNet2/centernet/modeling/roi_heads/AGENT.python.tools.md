# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/third_party/CenterNet2/centernet/modeling/roi_heads/custom_fast_rcnn.py

Prompts

```
['build a CustomFastRCNNOutputLayers instance with cfg and input_shape for ROI head classification and box regression', 'test the losses method to compute classification and box regression loss from predictions and proposals', 'test the sigmoid_cross_entropy_loss method to compute BCE loss with optional FED loss weighting', 'test the softmax_cross_entropy_loss method to compute cross entropy loss with optional FED loss weighting', 'test the inference method to predict boxes and scores with NMS and optional multi-proposal scoring', 'build a CustomROIHeads model using Detectron2 config to initialize box heads with CustomFastRCNNOutputLayers', 'build a CustomCascadeROIHeads model with multi-proposal scoring enabled via Detectron2 config', 'run the CustomROIHeads forward pass on images and proposals to get predictions or training losses', 'run the CustomCascadeROIHeads forward pass with cascade stages and multi-proposal score fusion at test time', 'review the CustomCascadeROIHeads _forward_box method to understand cascade stage predictions and score averaging', 'load class frequency data from an LVIS category info JSON file and return weighted frequencies as a tensor', 'sample category indices for frequency-enhanced decoupled loss using multinomial sampling with optional frequency weights', 'review the load_class_freq function to understand how it loads and weights LVIS category image counts', 'review the get_fed_loss_inds function to understand how it samples category indices for FED loss computation', 'refactor the get_fed_loss_inds function to support dynamic class counts instead of hardcoded C=1203']
```

Usage

```
{'build_CustomFastRCNNOutputLayers': 'build a CustomFastRCNNOutputLayers instance with cfg and input_shape for ROI head classification and box regression', 'test_losses_method': 'test the losses method to compute classification and box regression loss from predictions and proposals', 'test_sigmoid_cross_entropy_loss': 'test the sigmoid_cross_entropy_loss method to compute BCE loss with optional FED loss weighting', 'test_softmax_cross_entropy_loss': 'test the softmax_cross_entropy_loss method to compute cross entropy loss with optional FED loss weighting', 'test_inference_method': 'test the inference method to predict boxes and scores with NMS and optional multi-proposal scoring'}
```

## File: facebookresearch_detic/third_party/CenterNet2/centernet/modeling/roi_heads/custom_roi_heads.py

Prompts

```
['build a CustomFastRCNNOutputLayers instance with cfg and input_shape for ROI head classification and box regression', 'test the losses method to compute classification and box regression loss from predictions and proposals', 'test the sigmoid_cross_entropy_loss method to compute BCE loss with optional FED loss weighting', 'test the softmax_cross_entropy_loss method to compute cross entropy loss with optional FED loss weighting', 'test the inference method to predict boxes and scores with NMS and optional multi-proposal scoring', 'build a CustomROIHeads model using Detectron2 config to initialize box heads with CustomFastRCNNOutputLayers', 'build a CustomCascadeROIHeads model with multi-proposal scoring enabled via Detectron2 config', 'run the CustomROIHeads forward pass on images and proposals to get predictions or training losses', 'run the CustomCascadeROIHeads forward pass with cascade stages and multi-proposal score fusion at test time', 'review the CustomCascadeROIHeads _forward_box method to understand cascade stage predictions and score averaging', 'load class frequency data from an LVIS category info JSON file and return weighted frequencies as a tensor', 'sample category indices for frequency-enhanced decoupled loss using multinomial sampling with optional frequency weights', 'review the load_class_freq function to understand how it loads and weights LVIS category image counts', 'review the get_fed_loss_inds function to understand how it samples category indices for FED loss computation', 'refactor the get_fed_loss_inds function to support dynamic class counts instead of hardcoded C=1203']
```

Usage

```
{'build_CustomROIHeads': 'build a CustomROIHeads model using Detectron2 config to initialize box heads with CustomFastRCNNOutputLayers', 'build_CustomCascadeROIHeads': 'build a CustomCascadeROIHeads model with multi-proposal scoring enabled via Detectron2 config', 'run_CustomROIHeads_forward': 'run the CustomROIHeads forward pass on images and proposals to get predictions or training losses', 'run_CustomCascadeROIHeads_forward': 'run the CustomCascadeROIHeads forward pass with cascade stages and multi-proposal score fusion at test time', 'review_CustomCascadeROIHeads_forward_box': 'review the CustomCascadeROIHeads _forward_box method to understand cascade stage predictions and score averaging'}
```

## File: facebookresearch_detic/third_party/CenterNet2/centernet/modeling/roi_heads/fed_loss.py

Prompts

```
['build a CustomFastRCNNOutputLayers instance with cfg and input_shape for ROI head classification and box regression', 'test the losses method to compute classification and box regression loss from predictions and proposals', 'test the sigmoid_cross_entropy_loss method to compute BCE loss with optional FED loss weighting', 'test the softmax_cross_entropy_loss method to compute cross entropy loss with optional FED loss weighting', 'test the inference method to predict boxes and scores with NMS and optional multi-proposal scoring', 'build a CustomROIHeads model using Detectron2 config to initialize box heads with CustomFastRCNNOutputLayers', 'build a CustomCascadeROIHeads model with multi-proposal scoring enabled via Detectron2 config', 'run the CustomROIHeads forward pass on images and proposals to get predictions or training losses', 'run the CustomCascadeROIHeads forward pass with cascade stages and multi-proposal score fusion at test time', 'review the CustomCascadeROIHeads _forward_box method to understand cascade stage predictions and score averaging', 'load class frequency data from an LVIS category info JSON file and return weighted frequencies as a tensor', 'sample category indices for frequency-enhanced decoupled loss using multinomial sampling with optional frequency weights', 'review the load_class_freq function to understand how it loads and weights LVIS category image counts', 'review the get_fed_loss_inds function to understand how it samples category indices for FED loss computation', 'refactor the get_fed_loss_inds function to support dynamic class counts instead of hardcoded C=1203']
```

Usage

```
{'load_class_freq_from_json': 'load class frequency data from an LVIS category info JSON file and return weighted frequencies as a tensor', 'get_fed_loss_sampled_classes': 'sample category indices for frequency-enhanced decoupled loss using multinomial sampling with optional frequency weights', 'review_load_class_freq': 'review the load_class_freq function to understand how it loads and weights LVIS category image counts', 'review_get_fed_loss_inds': 'review the get_fed_loss_inds function to understand how it samples category indices for FED loss computation', 'refactor_get_fed_loss_inds': 'refactor the get_fed_loss_inds function to support dynamic class counts instead of hardcoded C=1203'}
```

