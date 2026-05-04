# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/loss/dino_clstoken_loss.py

Prompts

```
['build a DINOLoss module with configurable student temperature and center momentum for DINO self-supervised learning', 'create softmax-centered teacher outputs by subtracting the moving average center and dividing by teacher temperature', 'create a normalized teacher assignment matrix using the Sinkhorn-Knopp algorithm for uniform label distribution', 'run the forward pass to compute cross-entropy loss between student log-softmax and teacher softmax outputs', 'create an asynchronous moving average center update from teacher outputs with distributed all-reduce support', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute the cross-entropy loss between student and teacher patch tokens using forward', 'compute the masked cross-entropy loss between student and teacher patch tokens using forward_masked', 'apply the Sinkhorn-Knopp algorithm to normalize teacher output into a soft assignment matrix', 'update the running center of teacher patch tokens using momentum-based async reduction', 'build a python module that uses KoLeoLoss to compute entropic regularization on student backbone output vectors', 'create a function that finds pairwise nearest neighbors for L2-normalized vectors using matrix dot products', 'test the KoLeoLoss forward pass by passing a batch of student output tensors and verifying the loss scalar', 'review the KoLeoLoss class and its pairwise nearest neighbor computation for L2-normalized vectors on GPU', 'summarize the KoLeoLoss module which computes Kozachenko-Leonenko entropic loss to spread embedding vectors for similarity search']
```

Usage

```
{'build_DINOLoss': 'build a DINOLoss module with configurable student temperature and center momentum for DINO self-supervised learning', 'create_softmax_center_teacher': 'create softmax-centered teacher outputs by subtracting the moving average center and dividing by teacher temperature', 'create_sinkhorn_knopp_teacher': 'create a normalized teacher assignment matrix using the Sinkhorn-Knopp algorithm for uniform label distribution', 'run_DINOLoss_forward': 'run the forward pass to compute cross-entropy loss between student log-softmax and teacher softmax outputs', 'create_update_center': 'create an asynchronous moving average center update from teacher outputs with distributed all-reduce support'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/loss/ibot_patch_loss.py

Prompts

```
['build a DINOLoss module with configurable student temperature and center momentum for DINO self-supervised learning', 'create softmax-centered teacher outputs by subtracting the moving average center and dividing by teacher temperature', 'create a normalized teacher assignment matrix using the Sinkhorn-Knopp algorithm for uniform label distribution', 'run the forward pass to compute cross-entropy loss between student log-softmax and teacher softmax outputs', 'create an asynchronous moving average center update from teacher outputs with distributed all-reduce support', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute the cross-entropy loss between student and teacher patch tokens using forward', 'compute the masked cross-entropy loss between student and teacher patch tokens using forward_masked', 'apply the Sinkhorn-Knopp algorithm to normalize teacher output into a soft assignment matrix', 'update the running center of teacher patch tokens using momentum-based async reduction', 'build a python module that uses KoLeoLoss to compute entropic regularization on student backbone output vectors', 'create a function that finds pairwise nearest neighbors for L2-normalized vectors using matrix dot products', 'test the KoLeoLoss forward pass by passing a batch of student output tensors and verifying the loss scalar', 'review the KoLeoLoss class and its pairwise nearest neighbor computation for L2-normalized vectors on GPU', 'summarize the KoLeoLoss module which computes Kozachenko-Leonenko entropic loss to spread embedding vectors for similarity search']
```

Usage

```
{'create_iBOTPatchLoss': 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute_forward_loss': 'compute the cross-entropy loss between student and teacher patch tokens using forward', 'compute_forward_masked_loss': 'compute the masked cross-entropy loss between student and teacher patch tokens using forward_masked', 'apply_sinkhorn_knopp': 'apply the Sinkhorn-Knopp algorithm to normalize teacher output into a soft assignment matrix', 'update_teacher_center': 'update the running center of teacher patch tokens using momentum-based async reduction'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/loss/koleo_loss.py

Prompts

```
['build a DINOLoss module with configurable student temperature and center momentum for DINO self-supervised learning', 'create softmax-centered teacher outputs by subtracting the moving average center and dividing by teacher temperature', 'create a normalized teacher assignment matrix using the Sinkhorn-Knopp algorithm for uniform label distribution', 'run the forward pass to compute cross-entropy loss between student log-softmax and teacher softmax outputs', 'create an asynchronous moving average center update from teacher outputs with distributed all-reduce support', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute the cross-entropy loss between student and teacher patch tokens using forward', 'compute the masked cross-entropy loss between student and teacher patch tokens using forward_masked', 'apply the Sinkhorn-Knopp algorithm to normalize teacher output into a soft assignment matrix', 'update the running center of teacher patch tokens using momentum-based async reduction', 'build a python module that uses KoLeoLoss to compute entropic regularization on student backbone output vectors', 'create a function that finds pairwise nearest neighbors for L2-normalized vectors using matrix dot products', 'test the KoLeoLoss forward pass by passing a batch of student output tensors and verifying the loss scalar', 'review the KoLeoLoss class and its pairwise nearest neighbor computation for L2-normalized vectors on GPU', 'summarize the KoLeoLoss module which computes Kozachenko-Leonenko entropic loss to spread embedding vectors for similarity search']
```

Usage

```
{'build_koleo_loss_regularization': 'build a python module that uses KoLeoLoss to compute entropic regularization on student backbone output vectors', 'create_pairwise_NNs_inner': 'create a function that finds pairwise nearest neighbors for L2-normalized vectors using matrix dot products', 'test_forward_koleo_loss': 'test the KoLeoLoss forward pass by passing a batch of student output tensors and verifying the loss scalar', 'review_KoLeoLoss_pairwise_NNs': 'review the KoLeoLoss class and its pairwise nearest neighbor computation for L2-normalized vectors on GPU', 'summarize_koleo_loss_usage': 'summarize the KoLeoLoss module which computes Kozachenko-Leonenko entropic loss to spread embedding vectors for similarity search'}
```

