# Agent Python Tools

- repo: facebookresearch/sparsh
- repo_uri: https://github.com/facebookresearch/sparsh

## File: facebookresearch_sparsh/tactile_ssl/loss/dino_loss.py

Prompts

```
['create a DINOLoss module with out_dim, student_temp, and center_momentum for DINO self-supervised learning', 'build a cross-entropy loss between student and teacher network softmax outputs using DINOLoss forward', 'run softmax centering and sharpening on teacher output with a given temperature', 'test the Sinkhorn-Knopp algorithm to compute normalized teacher assignment matrix across distributed GPUs', 'review the update_center method that asynchronously reduces and applies momentum-based center updates for teacher outputs', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute cross-entropy loss between student and teacher patch token tensors using forward', 'compute masked cross-entropy loss for student and teacher patch tokens with mask weighting', 'apply the Sinkhorn-Knopp algorithm to normalize teacher output distributions across prototypes and samples', 'update the moving average center of teacher patch tokens using async distributed reduction', 'build a python module that computes the Kozachenko-Leonenko entropic loss regularizer for spreading vectors', 'create a function that finds pairwise nearest neighbors for L2-normalized vectors using dot products', 'test the KoLeoLoss forward pass by passing student output tensors and verifying the loss scalar', 'review the pairwise_NNs_inner method that uses matrix multiplication to find nearest neighbors on GPU', 'summarize the KoLeoLoss class that normalizes vectors and computes negative log of nearest neighbor distances']
```

Usage

```
{'create_DINOLoss': 'create a DINOLoss module with out_dim, student_temp, and center_momentum for DINO self-supervised learning', 'build_forward_loss': 'build a cross-entropy loss between student and teacher network softmax outputs using DINOLoss forward', 'run_softmax_center_teacher': 'run softmax centering and sharpening on teacher output with a given temperature', 'test_sinkhorn_knopp_teacher': 'test the Sinkhorn-Knopp algorithm to compute normalized teacher assignment matrix across distributed GPUs', 'review_update_center': 'review the update_center method that asynchronously reduces and applies momentum-based center updates for teacher outputs'}
```

## File: facebookresearch_sparsh/tactile_ssl/loss/ibot_patch_loss.py

Prompts

```
['create a DINOLoss module with out_dim, student_temp, and center_momentum for DINO self-supervised learning', 'build a cross-entropy loss between student and teacher network softmax outputs using DINOLoss forward', 'run softmax centering and sharpening on teacher output with a given temperature', 'test the Sinkhorn-Knopp algorithm to compute normalized teacher assignment matrix across distributed GPUs', 'review the update_center method that asynchronously reduces and applies momentum-based center updates for teacher outputs', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute cross-entropy loss between student and teacher patch token tensors using forward', 'compute masked cross-entropy loss for student and teacher patch tokens with mask weighting', 'apply the Sinkhorn-Knopp algorithm to normalize teacher output distributions across prototypes and samples', 'update the moving average center of teacher patch tokens using async distributed reduction', 'build a python module that computes the Kozachenko-Leonenko entropic loss regularizer for spreading vectors', 'create a function that finds pairwise nearest neighbors for L2-normalized vectors using dot products', 'test the KoLeoLoss forward pass by passing student output tensors and verifying the loss scalar', 'review the pairwise_NNs_inner method that uses matrix multiplication to find nearest neighbors on GPU', 'summarize the KoLeoLoss class that normalizes vectors and computes negative log of nearest neighbor distances']
```

Usage

```
{'create_iBOTPatchLoss': 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute_forward_loss': 'compute cross-entropy loss between student and teacher patch token tensors using forward', 'compute_forward_masked_loss': 'compute masked cross-entropy loss for student and teacher patch tokens with mask weighting', 'apply_sinkhorn_knopp': 'apply the Sinkhorn-Knopp algorithm to normalize teacher output distributions across prototypes and samples', 'update_teacher_center': 'update the moving average center of teacher patch tokens using async distributed reduction'}
```

## File: facebookresearch_sparsh/tactile_ssl/loss/koleo_loss.py

Prompts

```
['create a DINOLoss module with out_dim, student_temp, and center_momentum for DINO self-supervised learning', 'build a cross-entropy loss between student and teacher network softmax outputs using DINOLoss forward', 'run softmax centering and sharpening on teacher output with a given temperature', 'test the Sinkhorn-Knopp algorithm to compute normalized teacher assignment matrix across distributed GPUs', 'review the update_center method that asynchronously reduces and applies momentum-based center updates for teacher outputs', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute cross-entropy loss between student and teacher patch token tensors using forward', 'compute masked cross-entropy loss for student and teacher patch tokens with mask weighting', 'apply the Sinkhorn-Knopp algorithm to normalize teacher output distributions across prototypes and samples', 'update the moving average center of teacher patch tokens using async distributed reduction', 'build a python module that computes the Kozachenko-Leonenko entropic loss regularizer for spreading vectors', 'create a function that finds pairwise nearest neighbors for L2-normalized vectors using dot products', 'test the KoLeoLoss forward pass by passing student output tensors and verifying the loss scalar', 'review the pairwise_NNs_inner method that uses matrix multiplication to find nearest neighbors on GPU', 'summarize the KoLeoLoss class that normalizes vectors and computes negative log of nearest neighbor distances']
```

Usage

```
{'build_koleo_loss_module': 'build a python module that computes the Kozachenko-Leonenko entropic loss regularizer for spreading vectors', 'create_pairwise_NNs_inner': 'create a function that finds pairwise nearest neighbors for L2-normalized vectors using dot products', 'test_forward_loss': 'test the KoLeoLoss forward pass by passing student output tensors and verifying the loss scalar', 'review_pairwise_NNs_inner': 'review the pairwise_NNs_inner method that uses matrix multiplication to find nearest neighbors on GPU', 'summarize_koleo_loss_class': 'summarize the KoLeoLoss class that normalizes vectors and computes negative log of nearest neighbor distances'}
```

