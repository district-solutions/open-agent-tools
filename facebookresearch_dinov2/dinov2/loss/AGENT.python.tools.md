# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/loss/dino_clstoken_loss.py

Prompts

```
['create a DINOLoss module with configurable output dimension, student temperature, and center momentum parameters', 'build a softmax-centered teacher output by subtracting the moving average center and applying temperature scaling', 'run the Sinkhorn-Knopp algorithm to compute a normalized assignment matrix from teacher output prototypes', 'test the DINOLoss forward pass computing cross-entropy between student log-softmax and teacher softmax outputs', 'review the DINOLoss update_center method that asynchronously reduces and applies momentum-based center updates across distributed processes', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'run the forward pass to compute cross-entropy loss between student and teacher patch tokens', 'run the forward masked pass to compute loss on masked patch tokens with optional weights', 'review the softmax_center_teacher method that centers and sharpens teacher patch tokens using momentum', 'review the sinkhorn_knopp_teacher method that normalizes teacher output into a doubly stochastic assignment matrix', 'build a python module that computes the Kozachenko-Leonenko entropic loss regularizer for DINOv2 student outputs', 'create a KoLeoLoss instance to regularize embedding vectors by maximizing their pairwise distances', 'run the KoLeoLoss forward pass on a batch of student backbone outputs to get the entropic loss', 'test the pairwise_NNs_inner method to find nearest neighbors for L2-normalized vectors on GPU', 'review the KoLeoLoss class and its entropic regularization approach for spreading vectors in similarity search']
```

Usage

```
{'create_DINOLoss': 'create a DINOLoss module with configurable output dimension, student temperature, and center momentum parameters', 'build_softmax_center_teacher': 'build a softmax-centered teacher output by subtracting the moving average center and applying temperature scaling', 'run_sinkhorn_knopp_teacher': 'run the Sinkhorn-Knopp algorithm to compute a normalized assignment matrix from teacher output prototypes', 'test_DINOLoss_forward': 'test the DINOLoss forward pass computing cross-entropy between student log-softmax and teacher softmax outputs', 'review_update_center': 'review the DINOLoss update_center method that asynchronously reduces and applies momentum-based center updates across distributed processes'}
```

## File: facebookresearch_dinov2/dinov2/loss/ibot_patch_loss.py

Prompts

```
['create a DINOLoss module with configurable output dimension, student temperature, and center momentum parameters', 'build a softmax-centered teacher output by subtracting the moving average center and applying temperature scaling', 'run the Sinkhorn-Knopp algorithm to compute a normalized assignment matrix from teacher output prototypes', 'test the DINOLoss forward pass computing cross-entropy between student log-softmax and teacher softmax outputs', 'review the DINOLoss update_center method that asynchronously reduces and applies momentum-based center updates across distributed processes', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'run the forward pass to compute cross-entropy loss between student and teacher patch tokens', 'run the forward masked pass to compute loss on masked patch tokens with optional weights', 'review the softmax_center_teacher method that centers and sharpens teacher patch tokens using momentum', 'review the sinkhorn_knopp_teacher method that normalizes teacher output into a doubly stochastic assignment matrix', 'build a python module that computes the Kozachenko-Leonenko entropic loss regularizer for DINOv2 student outputs', 'create a KoLeoLoss instance to regularize embedding vectors by maximizing their pairwise distances', 'run the KoLeoLoss forward pass on a batch of student backbone outputs to get the entropic loss', 'test the pairwise_NNs_inner method to find nearest neighbors for L2-normalized vectors on GPU', 'review the KoLeoLoss class and its entropic regularization approach for spreading vectors in similarity search']
```

Usage

```
{'create_iBOTPatchLoss': 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'run_forward_cross_entropy': 'run the forward pass to compute cross-entropy loss between student and teacher patch tokens', 'run_forward_masked_loss': 'run the forward masked pass to compute loss on masked patch tokens with optional weights', 'review_softmax_center_teacher': 'review the softmax_center_teacher method that centers and sharpens teacher patch tokens using momentum', 'review_sinkhorn_knopp_teacher': 'review the sinkhorn_knopp_teacher method that normalizes teacher output into a doubly stochastic assignment matrix'}
```

## File: facebookresearch_dinov2/dinov2/loss/koleo_loss.py

Prompts

```
['create a DINOLoss module with configurable output dimension, student temperature, and center momentum parameters', 'build a softmax-centered teacher output by subtracting the moving average center and applying temperature scaling', 'run the Sinkhorn-Knopp algorithm to compute a normalized assignment matrix from teacher output prototypes', 'test the DINOLoss forward pass computing cross-entropy between student log-softmax and teacher softmax outputs', 'review the DINOLoss update_center method that asynchronously reduces and applies momentum-based center updates across distributed processes', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'run the forward pass to compute cross-entropy loss between student and teacher patch tokens', 'run the forward masked pass to compute loss on masked patch tokens with optional weights', 'review the softmax_center_teacher method that centers and sharpens teacher patch tokens using momentum', 'review the sinkhorn_knopp_teacher method that normalizes teacher output into a doubly stochastic assignment matrix', 'build a python module that computes the Kozachenko-Leonenko entropic loss regularizer for DINOv2 student outputs', 'create a KoLeoLoss instance to regularize embedding vectors by maximizing their pairwise distances', 'run the KoLeoLoss forward pass on a batch of student backbone outputs to get the entropic loss', 'test the pairwise_NNs_inner method to find nearest neighbors for L2-normalized vectors on GPU', 'review the KoLeoLoss class and its entropic regularization approach for spreading vectors in similarity search']
```

Usage

```
{'build_koleo_loss_module': 'build a python module that computes the Kozachenko-Leonenko entropic loss regularizer for DINOv2 student outputs', 'create_koleo_loss_instance': 'create a KoLeoLoss instance to regularize embedding vectors by maximizing their pairwise distances', 'run_koleo_loss_forward': 'run the KoLeoLoss forward pass on a batch of student backbone outputs to get the entropic loss', 'test_pairwise_NNs_inner': 'test the pairwise_NNs_inner method to find nearest neighbors for L2-normalized vectors on GPU', 'review_koleo_loss_regularization': 'review the KoLeoLoss class and its entropic regularization approach for spreading vectors in similarity search'}
```

