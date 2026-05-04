# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/loss/dino_clstoken_loss.py

Prompts

```
['create a DINOLoss module with out_dim, student_temp, and center_momentum parameters for DINOv3 training', 'build a cross-entropy loss computation between student logits and teacher probabilities with optional diagonal ignoring', 'run softmax centering and sharpening on teacher output using the learned center and teacher temperature', 'test the Sinkhorn-Knopp algorithm to compute normalized teacher assignment probabilities across distributed processes', 'review the async center update mechanism that reduces teacher output across processes and applies momentum-based centering', 'create a GramLoss module to compute MSE loss between student and teacher feature gram matrices', 'build a GramLoss module with apply_norm to normalize features before computing gram matrix similarities', 'run the GramLoss forward pass with output and target feature tensors of shape B, N, dim', 'test the GramLoss module with remove_neg to zero out negative similarity values in gram matrices', 'review the GramLoss forward method to compute gram matrices at image level or across the entire batch', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute cross-entropy loss between student and teacher patch tokens using masked student outputs', 'compute masked patch loss with optional custom mask weights and number of masked patches', 'run the Sinkhorn-Knopp algorithm to normalize teacher output assignments across distributed processes', 'update the moving average center of teacher patch tokens using async distributed all-reduce', 'build a KoLeoLoss module to compute entropic regularization loss on student backbone output vectors', 'build a KoLeoLossDistributed module to compute entropic loss across distributed GPU processes with all_gather', 'test the KoLeoLoss forward pass by passing normalized student output tensors and verifying scalar loss output', 'test the KoLeoLossDistributed forward pass with a custom topk parameter for multi-nearest neighbor search', 'review the pairwise_NNs_inner method that finds nearest neighbors via dot product on L2-normalized vectors']
```

Usage

```
{'create_DINOLoss': 'create a DINOLoss module with out_dim, student_temp, and center_momentum parameters for DINOv3 training', 'build_DINOLoss_forward': 'build a cross-entropy loss computation between student logits and teacher probabilities with optional diagonal ignoring', 'run_softmax_center_teacher': 'run softmax centering and sharpening on teacher output using the learned center and teacher temperature', 'test_sinkhorn_knopp_teacher': 'test the Sinkhorn-Knopp algorithm to compute normalized teacher assignment probabilities across distributed processes', 'review_update_center': 'review the async center update mechanism that reduces teacher output across processes and applies momentum-based centering'}
```

## File: facebookresearch_dinov3/dinov3/loss/gram_loss.py

Prompts

```
['create a DINOLoss module with out_dim, student_temp, and center_momentum parameters for DINOv3 training', 'build a cross-entropy loss computation between student logits and teacher probabilities with optional diagonal ignoring', 'run softmax centering and sharpening on teacher output using the learned center and teacher temperature', 'test the Sinkhorn-Knopp algorithm to compute normalized teacher assignment probabilities across distributed processes', 'review the async center update mechanism that reduces teacher output across processes and applies momentum-based centering', 'create a GramLoss module to compute MSE loss between student and teacher feature gram matrices', 'build a GramLoss module with apply_norm to normalize features before computing gram matrix similarities', 'run the GramLoss forward pass with output and target feature tensors of shape B, N, dim', 'test the GramLoss module with remove_neg to zero out negative similarity values in gram matrices', 'review the GramLoss forward method to compute gram matrices at image level or across the entire batch', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute cross-entropy loss between student and teacher patch tokens using masked student outputs', 'compute masked patch loss with optional custom mask weights and number of masked patches', 'run the Sinkhorn-Knopp algorithm to normalize teacher output assignments across distributed processes', 'update the moving average center of teacher patch tokens using async distributed all-reduce', 'build a KoLeoLoss module to compute entropic regularization loss on student backbone output vectors', 'build a KoLeoLossDistributed module to compute entropic loss across distributed GPU processes with all_gather', 'test the KoLeoLoss forward pass by passing normalized student output tensors and verifying scalar loss output', 'test the KoLeoLossDistributed forward pass with a custom topk parameter for multi-nearest neighbor search', 'review the pairwise_NNs_inner method that finds nearest neighbors via dot product on L2-normalized vectors']
```

Usage

```
{'create_gram_loss_module': 'create a GramLoss module to compute MSE loss between student and teacher feature gram matrices', 'build_gram_loss_with_normalization': 'build a GramLoss module with apply_norm to normalize features before computing gram matrix similarities', 'run_gram_loss_forward': 'run the GramLoss forward pass with output and target feature tensors of shape B, N, dim', 'test_gram_loss_negative_removal': 'test the GramLoss module with remove_neg to zero out negative similarity values in gram matrices', 'review_gram_loss_img_level': 'review the GramLoss forward method to compute gram matrices at image level or across the entire batch'}
```

## File: facebookresearch_dinov3/dinov3/loss/ibot_patch_loss.py

Prompts

```
['create a DINOLoss module with out_dim, student_temp, and center_momentum parameters for DINOv3 training', 'build a cross-entropy loss computation between student logits and teacher probabilities with optional diagonal ignoring', 'run softmax centering and sharpening on teacher output using the learned center and teacher temperature', 'test the Sinkhorn-Knopp algorithm to compute normalized teacher assignment probabilities across distributed processes', 'review the async center update mechanism that reduces teacher output across processes and applies momentum-based centering', 'create a GramLoss module to compute MSE loss between student and teacher feature gram matrices', 'build a GramLoss module with apply_norm to normalize features before computing gram matrix similarities', 'run the GramLoss forward pass with output and target feature tensors of shape B, N, dim', 'test the GramLoss module with remove_neg to zero out negative similarity values in gram matrices', 'review the GramLoss forward method to compute gram matrices at image level or across the entire batch', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute cross-entropy loss between student and teacher patch tokens using masked student outputs', 'compute masked patch loss with optional custom mask weights and number of masked patches', 'run the Sinkhorn-Knopp algorithm to normalize teacher output assignments across distributed processes', 'update the moving average center of teacher patch tokens using async distributed all-reduce', 'build a KoLeoLoss module to compute entropic regularization loss on student backbone output vectors', 'build a KoLeoLossDistributed module to compute entropic loss across distributed GPU processes with all_gather', 'test the KoLeoLoss forward pass by passing normalized student output tensors and verifying scalar loss output', 'test the KoLeoLossDistributed forward pass with a custom topk parameter for multi-nearest neighbor search', 'review the pairwise_NNs_inner method that finds nearest neighbors via dot product on L2-normalized vectors']
```

Usage

```
{'create_IBOTPatchLoss': 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute_patch_loss_forward': 'compute cross-entropy loss between student and teacher patch tokens using masked student outputs', 'compute_masked_patch_loss': 'compute masked patch loss with optional custom mask weights and number of masked patches', 'run_sinkhorn_knopp_teacher': 'run the Sinkhorn-Knopp algorithm to normalize teacher output assignments across distributed processes', 'update_teacher_center': 'update the moving average center of teacher patch tokens using async distributed all-reduce'}
```

## File: facebookresearch_dinov3/dinov3/loss/koleo_loss.py

Prompts

```
['create a DINOLoss module with out_dim, student_temp, and center_momentum parameters for DINOv3 training', 'build a cross-entropy loss computation between student logits and teacher probabilities with optional diagonal ignoring', 'run softmax centering and sharpening on teacher output using the learned center and teacher temperature', 'test the Sinkhorn-Knopp algorithm to compute normalized teacher assignment probabilities across distributed processes', 'review the async center update mechanism that reduces teacher output across processes and applies momentum-based centering', 'create a GramLoss module to compute MSE loss between student and teacher feature gram matrices', 'build a GramLoss module with apply_norm to normalize features before computing gram matrix similarities', 'run the GramLoss forward pass with output and target feature tensors of shape B, N, dim', 'test the GramLoss module with remove_neg to zero out negative similarity values in gram matrices', 'review the GramLoss forward method to compute gram matrices at image level or across the entire batch', 'create an iBOTPatchLoss module with a given patch output dimension and student temperature', 'compute cross-entropy loss between student and teacher patch tokens using masked student outputs', 'compute masked patch loss with optional custom mask weights and number of masked patches', 'run the Sinkhorn-Knopp algorithm to normalize teacher output assignments across distributed processes', 'update the moving average center of teacher patch tokens using async distributed all-reduce', 'build a KoLeoLoss module to compute entropic regularization loss on student backbone output vectors', 'build a KoLeoLossDistributed module to compute entropic loss across distributed GPU processes with all_gather', 'test the KoLeoLoss forward pass by passing normalized student output tensors and verifying scalar loss output', 'test the KoLeoLossDistributed forward pass with a custom topk parameter for multi-nearest neighbor search', 'review the pairwise_NNs_inner method that finds nearest neighbors via dot product on L2-normalized vectors']
```

Usage

```
{'build_koleo_loss_regularization': 'build a KoLeoLoss module to compute entropic regularization loss on student backbone output vectors', 'build_koleo_loss_distributed': 'build a KoLeoLossDistributed module to compute entropic loss across distributed GPU processes with all_gather', 'test_koleo_loss_forward': 'test the KoLeoLoss forward pass by passing normalized student output tensors and verifying scalar loss output', 'test_koleo_loss_distributed_topk': 'test the KoLeoLossDistributed forward pass with a custom topk parameter for multi-nearest neighbor search', 'review_koleo_pairwise_NNs_inner': 'review the pairwise_NNs_inner method that finds nearest neighbors via dot product on L2-normalized vectors'}
```

