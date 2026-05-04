# Agent Python Tools

- repo: facebookresearch/dvsr
- repo_uri: https://github.com/facebookresearch/dvsr

## File: facebookresearch_dvsr/model/base.py

Prompts

```
['create a subclass of BaseModel that implements init_weights, forward_train, forward_test, and train_step', 'run a forward pass on a BaseModel subclass with images and labels in training or test mode', 'review the parse_losses method that aggregates a dict of loss tensors into a total loss and log variables', 'test the val_step method that runs forward_test on a data batch and returns the output', 'refactor a BaseModel subclass train_step to process a data batch with an optimizer', 'build a BasicRestorer model with a generator config and pixel loss for depth restoration', 'run the training forward pass with lq depth, guide RGB, and ground truth tensors', 'run the test forward pass to generate restored depth output from lq and guide inputs', 'run a single training step with a data batch and optimizer for backpropagation', 'run evaluation to compute MAE between model output and ground truth depth maps', 'build a model from a config dict using build_model with optional train and test config', 'build a backbone network from a config dict using build_backbone', 'build a model component from a config dict using build_component', 'build a loss module from a config dict using build_loss', 'build a Sequential of modules from a list of config dicts using build', 'build a DVSR model instance with configurable mid_channels, num_blocks, and scale parameters', 'run the DVSR forward pass with lqs tensor and RGB guidance to predict depth maps', 'run a single stage forward pass of DVSR for depth and confidence prediction', 'test the SPyNet-based optical flow computation between consecutive guide frames', 'review the DVSR propagate method for bidirectional feature propagation across video frames', 'build a python module that converts a predicted depth map into a dToF sensor histogram using dtof_hist_torch', 'compute the histogram matching error between input CDFs and predicted depth using get_inp_error', 'generate positional encoding tensors for batched video frames using get_pos_encoding with batch size and pitch', 'create an HVSR model instance with configurable mid_channels, num_blocks, scale, and dToF sensor arguments', 'run the HVSR forward pass on low quality histogram sequences and RGB guidance to predict depth maps']
```

Usage

```
{'create_subclass_of_base_model': 'create a subclass of BaseModel that implements init_weights, forward_train, forward_test, and train_step', 'run_forward_pass': 'run a forward pass on a BaseModel subclass with images and labels in training or test mode', 'review_parse_losses': 'review the parse_losses method that aggregates a dict of loss tensors into a total loss and log variables', 'test_val_step': 'test the val_step method that runs forward_test on a data batch and returns the output', 'refactor_train_step': 'refactor a BaseModel subclass train_step to process a data batch with an optimizer'}
```

## File: facebookresearch_dvsr/model/basic_restorer.py

Prompts

```
['create a subclass of BaseModel that implements init_weights, forward_train, forward_test, and train_step', 'run a forward pass on a BaseModel subclass with images and labels in training or test mode', 'review the parse_losses method that aggregates a dict of loss tensors into a total loss and log variables', 'test the val_step method that runs forward_test on a data batch and returns the output', 'refactor a BaseModel subclass train_step to process a data batch with an optimizer', 'build a BasicRestorer model with a generator config and pixel loss for depth restoration', 'run the training forward pass with lq depth, guide RGB, and ground truth tensors', 'run the test forward pass to generate restored depth output from lq and guide inputs', 'run a single training step with a data batch and optimizer for backpropagation', 'run evaluation to compute MAE between model output and ground truth depth maps', 'build a model from a config dict using build_model with optional train and test config', 'build a backbone network from a config dict using build_backbone', 'build a model component from a config dict using build_component', 'build a loss module from a config dict using build_loss', 'build a Sequential of modules from a list of config dicts using build', 'build a DVSR model instance with configurable mid_channels, num_blocks, and scale parameters', 'run the DVSR forward pass with lqs tensor and RGB guidance to predict depth maps', 'run a single stage forward pass of DVSR for depth and confidence prediction', 'test the SPyNet-based optical flow computation between consecutive guide frames', 'review the DVSR propagate method for bidirectional feature propagation across video frames', 'build a python module that converts a predicted depth map into a dToF sensor histogram using dtof_hist_torch', 'compute the histogram matching error between input CDFs and predicted depth using get_inp_error', 'generate positional encoding tensors for batched video frames using get_pos_encoding with batch size and pitch', 'create an HVSR model instance with configurable mid_channels, num_blocks, scale, and dToF sensor arguments', 'run the HVSR forward pass on low quality histogram sequences and RGB guidance to predict depth maps']
```

Usage

```
{'build_BasicRestorer': 'build a BasicRestorer model with a generator config and pixel loss for depth restoration', 'run_forward_train': 'run the training forward pass with lq depth, guide RGB, and ground truth tensors', 'run_forward_test': 'run the test forward pass to generate restored depth output from lq and guide inputs', 'run_train_step': 'run a single training step with a data batch and optimizer for backpropagation', 'run_evaluate': 'run evaluation to compute MAE between model output and ground truth depth maps'}
```

## File: facebookresearch_dvsr/model/builder.py

Prompts

```
['create a subclass of BaseModel that implements init_weights, forward_train, forward_test, and train_step', 'run a forward pass on a BaseModel subclass with images and labels in training or test mode', 'review the parse_losses method that aggregates a dict of loss tensors into a total loss and log variables', 'test the val_step method that runs forward_test on a data batch and returns the output', 'refactor a BaseModel subclass train_step to process a data batch with an optimizer', 'build a BasicRestorer model with a generator config and pixel loss for depth restoration', 'run the training forward pass with lq depth, guide RGB, and ground truth tensors', 'run the test forward pass to generate restored depth output from lq and guide inputs', 'run a single training step with a data batch and optimizer for backpropagation', 'run evaluation to compute MAE between model output and ground truth depth maps', 'build a model from a config dict using build_model with optional train and test config', 'build a backbone network from a config dict using build_backbone', 'build a model component from a config dict using build_component', 'build a loss module from a config dict using build_loss', 'build a Sequential of modules from a list of config dicts using build', 'build a DVSR model instance with configurable mid_channels, num_blocks, and scale parameters', 'run the DVSR forward pass with lqs tensor and RGB guidance to predict depth maps', 'run a single stage forward pass of DVSR for depth and confidence prediction', 'test the SPyNet-based optical flow computation between consecutive guide frames', 'review the DVSR propagate method for bidirectional feature propagation across video frames', 'build a python module that converts a predicted depth map into a dToF sensor histogram using dtof_hist_torch', 'compute the histogram matching error between input CDFs and predicted depth using get_inp_error', 'generate positional encoding tensors for batched video frames using get_pos_encoding with batch size and pitch', 'create an HVSR model instance with configurable mid_channels, num_blocks, scale, and dToF sensor arguments', 'run the HVSR forward pass on low quality histogram sequences and RGB guidance to predict depth maps']
```

Usage

```
{'build_model_from_cfg': 'build a model from a config dict using build_model with optional train and test config', 'build_backbone_from_cfg': 'build a backbone network from a config dict using build_backbone', 'build_component_from_cfg': 'build a model component from a config dict using build_component', 'build_loss_from_cfg': 'build a loss module from a config dict using build_loss', 'build_sequential_modules': 'build a Sequential of modules from a list of config dicts using build'}
```

## File: facebookresearch_dvsr/model/dvsr.py

Prompts

```
['create a subclass of BaseModel that implements init_weights, forward_train, forward_test, and train_step', 'run a forward pass on a BaseModel subclass with images and labels in training or test mode', 'review the parse_losses method that aggregates a dict of loss tensors into a total loss and log variables', 'test the val_step method that runs forward_test on a data batch and returns the output', 'refactor a BaseModel subclass train_step to process a data batch with an optimizer', 'build a BasicRestorer model with a generator config and pixel loss for depth restoration', 'run the training forward pass with lq depth, guide RGB, and ground truth tensors', 'run the test forward pass to generate restored depth output from lq and guide inputs', 'run a single training step with a data batch and optimizer for backpropagation', 'run evaluation to compute MAE between model output and ground truth depth maps', 'build a model from a config dict using build_model with optional train and test config', 'build a backbone network from a config dict using build_backbone', 'build a model component from a config dict using build_component', 'build a loss module from a config dict using build_loss', 'build a Sequential of modules from a list of config dicts using build', 'build a DVSR model instance with configurable mid_channels, num_blocks, and scale parameters', 'run the DVSR forward pass with lqs tensor and RGB guidance to predict depth maps', 'run a single stage forward pass of DVSR for depth and confidence prediction', 'test the SPyNet-based optical flow computation between consecutive guide frames', 'review the DVSR propagate method for bidirectional feature propagation across video frames', 'build a python module that converts a predicted depth map into a dToF sensor histogram using dtof_hist_torch', 'compute the histogram matching error between input CDFs and predicted depth using get_inp_error', 'generate positional encoding tensors for batched video frames using get_pos_encoding with batch size and pitch', 'create an HVSR model instance with configurable mid_channels, num_blocks, scale, and dToF sensor arguments', 'run the HVSR forward pass on low quality histogram sequences and RGB guidance to predict depth maps']
```

Usage

```
{'build_dvsr_model': 'build a DVSR model instance with configurable mid_channels, num_blocks, and scale parameters', 'run_dvsr_forward': 'run the DVSR forward pass with lqs tensor and RGB guidance to predict depth maps', 'run_hg_forward': 'run a single stage forward pass of DVSR for depth and confidence prediction', 'test_compute_flow': 'test the SPyNet-based optical flow computation between consecutive guide frames', 'review_propagate': 'review the DVSR propagate method for bidirectional feature propagation across video frames'}
```

## File: facebookresearch_dvsr/model/hvsr.py

Prompts

```
['create a subclass of BaseModel that implements init_weights, forward_train, forward_test, and train_step', 'run a forward pass on a BaseModel subclass with images and labels in training or test mode', 'review the parse_losses method that aggregates a dict of loss tensors into a total loss and log variables', 'test the val_step method that runs forward_test on a data batch and returns the output', 'refactor a BaseModel subclass train_step to process a data batch with an optimizer', 'build a BasicRestorer model with a generator config and pixel loss for depth restoration', 'run the training forward pass with lq depth, guide RGB, and ground truth tensors', 'run the test forward pass to generate restored depth output from lq and guide inputs', 'run a single training step with a data batch and optimizer for backpropagation', 'run evaluation to compute MAE between model output and ground truth depth maps', 'build a model from a config dict using build_model with optional train and test config', 'build a backbone network from a config dict using build_backbone', 'build a model component from a config dict using build_component', 'build a loss module from a config dict using build_loss', 'build a Sequential of modules from a list of config dicts using build', 'build a DVSR model instance with configurable mid_channels, num_blocks, and scale parameters', 'run the DVSR forward pass with lqs tensor and RGB guidance to predict depth maps', 'run a single stage forward pass of DVSR for depth and confidence prediction', 'test the SPyNet-based optical flow computation between consecutive guide frames', 'review the DVSR propagate method for bidirectional feature propagation across video frames', 'build a python module that converts a predicted depth map into a dToF sensor histogram using dtof_hist_torch', 'compute the histogram matching error between input CDFs and predicted depth using get_inp_error', 'generate positional encoding tensors for batched video frames using get_pos_encoding with batch size and pitch', 'create an HVSR model instance with configurable mid_channels, num_blocks, scale, and dToF sensor arguments', 'run the HVSR forward pass on low quality histogram sequences and RGB guidance to predict depth maps']
```

Usage

```
{'build_dtof_histogram': 'build a python module that converts a predicted depth map into a dToF sensor histogram using dtof_hist_torch', 'compute_histogram_matching_error': 'compute the histogram matching error between input CDFs and predicted depth using get_inp_error', 'generate_positional_encoding': 'generate positional encoding tensors for batched video frames using get_pos_encoding with batch size and pitch', 'create_hvsr_model': 'create an HVSR model instance with configurable mid_channels, num_blocks, scale, and dToF sensor arguments', 'run_hvsr_forward': 'run the HVSR forward pass on low quality histogram sequences and RGB guidance to predict depth maps'}
```

