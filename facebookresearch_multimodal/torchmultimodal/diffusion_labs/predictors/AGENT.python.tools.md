# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/predictors/noise_predictor.py

Prompts

```
['create a NoisePredictor instance with a DiscreteGaussianSchedule and optional clamp function for diffusion noise prediction', 'predict the original data x0 from noisy input xt and model prediction using NoisePredictor at timestep t', 'predict diffusion noise directly from the model output using NoisePredictor predict_noise method', 'review the NoisePredictor class to understand how it computes x0 predictions using schedule coefficients', 'refactor the NoisePredictor to customize the clamp function for bounding predicted x0 values during diffusion', 'implement a Predictor Protocol class with predict_x0 and predict_noise methods for diffusion models', 'review the Predictor Protocol class and its abstract methods for diffusion process prediction', 'create a concrete implementation of predict_x0 that takes prediction, xt, and t tensors', 'create a concrete implementation of predict_noise that takes prediction, xt, and t tensors', 'refactor the Predictor Protocol to use a custom DiscreteGaussianSchedule for diffusion steps', 'create a TargetPredictor instance with a DiscreteGaussianSchedule and optional clamp function', 'predict the original data x0 from a model prediction using TargetPredictor predict_x0 method', 'predict the noise at diffusion step t using TargetPredictor predict_noise method', 'review the TargetPredictor class that computes predicted noise and x0 at diffusion step t', 'refactor the TargetPredictor to customize the clamp_func for bounding prediction values', 'create a VPredictor instance with a DiscreteGaussianSchedule and optional clamp function', 'predict the original sample x0 from a v-prediction, noisy input xt, and timestep t', 'predict the noise epsilon from a v-prediction, noisy input xt, and timestep t', 'review the VPredictor class and its predict_x0 and predict_noise methods', 'summarize the VPredictor class which computes predicted noise and x0 using v-prediction']
```

Usage

```
{'create_NoisePredictor': 'create a NoisePredictor instance with a DiscreteGaussianSchedule and optional clamp function for diffusion noise prediction', 'predict_x0_NoisePredictor': 'predict the original data x0 from noisy input xt and model prediction using NoisePredictor at timestep t', 'predict_noise_NoisePredictor': 'predict diffusion noise directly from the model output using NoisePredictor predict_noise method', 'review_NoisePredictor_class': 'review the NoisePredictor class to understand how it computes x0 predictions using schedule coefficients', 'refactor_NoisePredictor_clamp': 'refactor the NoisePredictor to customize the clamp function for bounding predicted x0 values during diffusion'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/predictors/predictor.py

Prompts

```
['create a NoisePredictor instance with a DiscreteGaussianSchedule and optional clamp function for diffusion noise prediction', 'predict the original data x0 from noisy input xt and model prediction using NoisePredictor at timestep t', 'predict diffusion noise directly from the model output using NoisePredictor predict_noise method', 'review the NoisePredictor class to understand how it computes x0 predictions using schedule coefficients', 'refactor the NoisePredictor to customize the clamp function for bounding predicted x0 values during diffusion', 'implement a Predictor Protocol class with predict_x0 and predict_noise methods for diffusion models', 'review the Predictor Protocol class and its abstract methods for diffusion process prediction', 'create a concrete implementation of predict_x0 that takes prediction, xt, and t tensors', 'create a concrete implementation of predict_noise that takes prediction, xt, and t tensors', 'refactor the Predictor Protocol to use a custom DiscreteGaussianSchedule for diffusion steps', 'create a TargetPredictor instance with a DiscreteGaussianSchedule and optional clamp function', 'predict the original data x0 from a model prediction using TargetPredictor predict_x0 method', 'predict the noise at diffusion step t using TargetPredictor predict_noise method', 'review the TargetPredictor class that computes predicted noise and x0 at diffusion step t', 'refactor the TargetPredictor to customize the clamp_func for bounding prediction values', 'create a VPredictor instance with a DiscreteGaussianSchedule and optional clamp function', 'predict the original sample x0 from a v-prediction, noisy input xt, and timestep t', 'predict the noise epsilon from a v-prediction, noisy input xt, and timestep t', 'review the VPredictor class and its predict_x0 and predict_noise methods', 'summarize the VPredictor class which computes predicted noise and x0 using v-prediction']
```

Usage

```
{'implement_predictor_protocol': 'implement a Predictor Protocol class with predict_x0 and predict_noise methods for diffusion models', 'review_predictor_protocol': 'review the Predictor Protocol class and its abstract methods for diffusion process prediction', 'create_predict_x0_implementation': 'create a concrete implementation of predict_x0 that takes prediction, xt, and t tensors', 'create_predict_noise_implementation': 'create a concrete implementation of predict_noise that takes prediction, xt, and t tensors', 'refactor_predictor_schedule': 'refactor the Predictor Protocol to use a custom DiscreteGaussianSchedule for diffusion steps'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/predictors/target_predictor.py

Prompts

```
['create a NoisePredictor instance with a DiscreteGaussianSchedule and optional clamp function for diffusion noise prediction', 'predict the original data x0 from noisy input xt and model prediction using NoisePredictor at timestep t', 'predict diffusion noise directly from the model output using NoisePredictor predict_noise method', 'review the NoisePredictor class to understand how it computes x0 predictions using schedule coefficients', 'refactor the NoisePredictor to customize the clamp function for bounding predicted x0 values during diffusion', 'implement a Predictor Protocol class with predict_x0 and predict_noise methods for diffusion models', 'review the Predictor Protocol class and its abstract methods for diffusion process prediction', 'create a concrete implementation of predict_x0 that takes prediction, xt, and t tensors', 'create a concrete implementation of predict_noise that takes prediction, xt, and t tensors', 'refactor the Predictor Protocol to use a custom DiscreteGaussianSchedule for diffusion steps', 'create a TargetPredictor instance with a DiscreteGaussianSchedule and optional clamp function', 'predict the original data x0 from a model prediction using TargetPredictor predict_x0 method', 'predict the noise at diffusion step t using TargetPredictor predict_noise method', 'review the TargetPredictor class that computes predicted noise and x0 at diffusion step t', 'refactor the TargetPredictor to customize the clamp_func for bounding prediction values', 'create a VPredictor instance with a DiscreteGaussianSchedule and optional clamp function', 'predict the original sample x0 from a v-prediction, noisy input xt, and timestep t', 'predict the noise epsilon from a v-prediction, noisy input xt, and timestep t', 'review the VPredictor class and its predict_x0 and predict_noise methods', 'summarize the VPredictor class which computes predicted noise and x0 using v-prediction']
```

Usage

```
{'create_TargetPredictor': 'create a TargetPredictor instance with a DiscreteGaussianSchedule and optional clamp function', 'predict_x0_TargetPredictor': 'predict the original data x0 from a model prediction using TargetPredictor predict_x0 method', 'predict_noise_TargetPredictor': 'predict the noise at diffusion step t using TargetPredictor predict_noise method', 'review_TargetPredictor_class': 'review the TargetPredictor class that computes predicted noise and x0 at diffusion step t', 'refactor_TargetPredictor_clamp': 'refactor the TargetPredictor to customize the clamp_func for bounding prediction values'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/predictors/v_predictor.py

Prompts

```
['create a NoisePredictor instance with a DiscreteGaussianSchedule and optional clamp function for diffusion noise prediction', 'predict the original data x0 from noisy input xt and model prediction using NoisePredictor at timestep t', 'predict diffusion noise directly from the model output using NoisePredictor predict_noise method', 'review the NoisePredictor class to understand how it computes x0 predictions using schedule coefficients', 'refactor the NoisePredictor to customize the clamp function for bounding predicted x0 values during diffusion', 'implement a Predictor Protocol class with predict_x0 and predict_noise methods for diffusion models', 'review the Predictor Protocol class and its abstract methods for diffusion process prediction', 'create a concrete implementation of predict_x0 that takes prediction, xt, and t tensors', 'create a concrete implementation of predict_noise that takes prediction, xt, and t tensors', 'refactor the Predictor Protocol to use a custom DiscreteGaussianSchedule for diffusion steps', 'create a TargetPredictor instance with a DiscreteGaussianSchedule and optional clamp function', 'predict the original data x0 from a model prediction using TargetPredictor predict_x0 method', 'predict the noise at diffusion step t using TargetPredictor predict_noise method', 'review the TargetPredictor class that computes predicted noise and x0 at diffusion step t', 'refactor the TargetPredictor to customize the clamp_func for bounding prediction values', 'create a VPredictor instance with a DiscreteGaussianSchedule and optional clamp function', 'predict the original sample x0 from a v-prediction, noisy input xt, and timestep t', 'predict the noise epsilon from a v-prediction, noisy input xt, and timestep t', 'review the VPredictor class and its predict_x0 and predict_noise methods', 'summarize the VPredictor class which computes predicted noise and x0 using v-prediction']
```

Usage

```
{'create_vpredictor': 'create a VPredictor instance with a DiscreteGaussianSchedule and optional clamp function', 'predict_x0': 'predict the original sample x0 from a v-prediction, noisy input xt, and timestep t', 'predict_noise': 'predict the noise epsilon from a v-prediction, noisy input xt, and timestep t', 'review_vpredictor_class': 'review the VPredictor class and its predict_x0 and predict_noise methods', 'summarize_vpredictor': 'summarize the VPredictor class which computes predicted noise and x0 using v-prediction'}
```

