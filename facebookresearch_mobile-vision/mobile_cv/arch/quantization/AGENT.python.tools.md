# Agent Python Tools

- repo: facebookresearch/mobile-vision
- repo_uri: https://github.com/facebookresearch/mobile-vision

## File: facebookresearch_mobile-vision/mobile_cv/arch/quantization/observer.py

Prompts

```
['create a FixedMinMaxObserver with hard-coded min and max quantization values for activations', 'create an UpdatableSymmetricMovingAverageMinMaxObserver that assumes activations are symmetric about zero', 'create an UpdateableReLUMovingAverageMinMaxObserver for non-negative activations with zero point', 'run update_stat on a model to update quantization observer statistics using model.apply', 'review the UpdatableMovingAverageMaxStatObserver forward method that tracks max stat with 4 sigma outlier truncation']
```

Usage

```
{'create_fixed_minmax_observer': 'create a FixedMinMaxObserver with hard-coded min and max quantization values for activations', 'create_symmetric_observer': 'create an UpdatableSymmetricMovingAverageMinMaxObserver that assumes activations are symmetric about zero', 'create_relu_observer': 'create an UpdateableReLUMovingAverageMinMaxObserver for non-negative activations with zero point', 'run_update_stat': 'run update_stat on a model to update quantization observer statistics using model.apply', 'review_observer_forward': 'review the UpdatableMovingAverageMaxStatObserver forward method that tracks max stat with 4 sigma outlier truncation'}
```

