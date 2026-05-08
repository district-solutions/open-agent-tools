# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/loss/tests/ctc_loss_test.py

Prompts

```
['test the CTCLoss class by comparing its output against PyTorch F.ctc_loss with random logits and targets', 'run the CTCLossTest unit test to verify CTC loss computation matches PyTorch native implementation', 'create a CTCLoss.Config object and set the blank label to 0 for CuDNN support', 'build a CTCLoss instance from config and call it with logits, targets, input lengths, and target lengths', 'review the CTCLossTest class and test_ctc_loss method to understand CTC loss validation against PyTorch', 'test the FocalLoss class by verifying it matches NLL loss when gamma is zero', 'test the BinaryFocalLoss class by verifying it matches binary cross entropy when gamma is zero', 'run the FocalLossTest unittest suite to validate focal loss implementations against baseline PyTorch losses', 'review the FocalLossTest class and its test methods for focal loss correctness', 'refactor the FocalLossTest class to add additional edge case tests for focal loss', 'test the LabelSmoothedCrossEntropyLoss forward pass with random logits and targets across 50 iterations', 'test the LabelSmoothedCrossEntropyLoss forward pass with SourceType.PROBS config and fixed input tensors', 'compute the negative cross-entropy loss from logits and targets with optional weight and ignore index', 'compute the negative KL divergence between log probabilities and uniform distribution across classes', 'compute the manual label-smoothed loss as a weighted combination of cross-entropy and KL divergence', 'test the SamplewiseLabelSmoothingLoss class to verify it produces equivalent results to LabelSmoothingLoss', 'run the unittest to compare LabelSmoothingLoss and SamplewiseLabelSmoothingLoss outputs with reduce true and false', 'create a LabelSmoothingLoss instance using LabelSmoothingLoss.Config with an ignore_index parameter', 'create a SamplewiseLabelSmoothingLoss instance using SamplewiseLabelSmoothingLoss.Config with an ignore_index parameter', 'review the SamplewiseLabelSmoothingLossTest class and its test_samplewise_label_smoothing_loss method for correctness']
```

Usage

```
{'test_ctc_loss': 'test the CTCLoss class by comparing its output against PyTorch F.ctc_loss with random logits and targets', 'run_ctc_loss_test': 'run the CTCLossTest unit test to verify CTC loss computation matches PyTorch native implementation', 'create_ctc_loss_config': 'create a CTCLoss.Config object and set the blank label to 0 for CuDNN support', 'build_ctc_loss_fn': 'build a CTCLoss instance from config and call it with logits, targets, input lengths, and target lengths', 'review_ctc_loss_test': 'review the CTCLossTest class and test_ctc_loss method to understand CTC loss validation against PyTorch'}
```

## File: facebookresearch_pytext/pytext/loss/tests/focal_loss_test.py

Prompts

```
['test the CTCLoss class by comparing its output against PyTorch F.ctc_loss with random logits and targets', 'run the CTCLossTest unit test to verify CTC loss computation matches PyTorch native implementation', 'create a CTCLoss.Config object and set the blank label to 0 for CuDNN support', 'build a CTCLoss instance from config and call it with logits, targets, input lengths, and target lengths', 'review the CTCLossTest class and test_ctc_loss method to understand CTC loss validation against PyTorch', 'test the FocalLoss class by verifying it matches NLL loss when gamma is zero', 'test the BinaryFocalLoss class by verifying it matches binary cross entropy when gamma is zero', 'run the FocalLossTest unittest suite to validate focal loss implementations against baseline PyTorch losses', 'review the FocalLossTest class and its test methods for focal loss correctness', 'refactor the FocalLossTest class to add additional edge case tests for focal loss', 'test the LabelSmoothedCrossEntropyLoss forward pass with random logits and targets across 50 iterations', 'test the LabelSmoothedCrossEntropyLoss forward pass with SourceType.PROBS config and fixed input tensors', 'compute the negative cross-entropy loss from logits and targets with optional weight and ignore index', 'compute the negative KL divergence between log probabilities and uniform distribution across classes', 'compute the manual label-smoothed loss as a weighted combination of cross-entropy and KL divergence', 'test the SamplewiseLabelSmoothingLoss class to verify it produces equivalent results to LabelSmoothingLoss', 'run the unittest to compare LabelSmoothingLoss and SamplewiseLabelSmoothingLoss outputs with reduce true and false', 'create a LabelSmoothingLoss instance using LabelSmoothingLoss.Config with an ignore_index parameter', 'create a SamplewiseLabelSmoothingLoss instance using SamplewiseLabelSmoothingLoss.Config with an ignore_index parameter', 'review the SamplewiseLabelSmoothingLossTest class and its test_samplewise_label_smoothing_loss method for correctness']
```

Usage

```
{'test_focal_loss_base': 'test the FocalLoss class by verifying it matches NLL loss when gamma is zero', 'test_binary_focal_loss_base': 'test the BinaryFocalLoss class by verifying it matches binary cross entropy when gamma is zero', 'run_focal_loss_tests': 'run the FocalLossTest unittest suite to validate focal loss implementations against baseline PyTorch losses', 'review_focal_loss_test': 'review the FocalLossTest class and its test methods for focal loss correctness', 'refactor_focal_loss_test': 'refactor the FocalLossTest class to add additional edge case tests for focal loss'}
```

## File: facebookresearch_pytext/pytext/loss/tests/label_smoothing_loss_test.py

Prompts

```
['test the CTCLoss class by comparing its output against PyTorch F.ctc_loss with random logits and targets', 'run the CTCLossTest unit test to verify CTC loss computation matches PyTorch native implementation', 'create a CTCLoss.Config object and set the blank label to 0 for CuDNN support', 'build a CTCLoss instance from config and call it with logits, targets, input lengths, and target lengths', 'review the CTCLossTest class and test_ctc_loss method to understand CTC loss validation against PyTorch', 'test the FocalLoss class by verifying it matches NLL loss when gamma is zero', 'test the BinaryFocalLoss class by verifying it matches binary cross entropy when gamma is zero', 'run the FocalLossTest unittest suite to validate focal loss implementations against baseline PyTorch losses', 'review the FocalLossTest class and its test methods for focal loss correctness', 'refactor the FocalLossTest class to add additional edge case tests for focal loss', 'test the LabelSmoothedCrossEntropyLoss forward pass with random logits and targets across 50 iterations', 'test the LabelSmoothedCrossEntropyLoss forward pass with SourceType.PROBS config and fixed input tensors', 'compute the negative cross-entropy loss from logits and targets with optional weight and ignore index', 'compute the negative KL divergence between log probabilities and uniform distribution across classes', 'compute the manual label-smoothed loss as a weighted combination of cross-entropy and KL divergence', 'test the SamplewiseLabelSmoothingLoss class to verify it produces equivalent results to LabelSmoothingLoss', 'run the unittest to compare LabelSmoothingLoss and SamplewiseLabelSmoothingLoss outputs with reduce true and false', 'create a LabelSmoothingLoss instance using LabelSmoothingLoss.Config with an ignore_index parameter', 'create a SamplewiseLabelSmoothingLoss instance using SamplewiseLabelSmoothingLoss.Config with an ignore_index parameter', 'review the SamplewiseLabelSmoothingLossTest class and its test_samplewise_label_smoothing_loss method for correctness']
```

Usage

```
{'test_label_smoothed_cross_entropy_loss_forward': 'test the LabelSmoothedCrossEntropyLoss forward pass with random logits and targets across 50 iterations', 'test_label_smoothed_cross_entropy_loss_forward_source_probs': 'test the LabelSmoothedCrossEntropyLoss forward pass with SourceType.PROBS config and fixed input tensors', 'compute_negative_cross_entropy_loss': 'compute the negative cross-entropy loss from logits and targets with optional weight and ignore index', 'compute_negative_kl_divergence': 'compute the negative KL divergence between log probabilities and uniform distribution across classes', 'compute_loss_manual': 'compute the manual label-smoothed loss as a weighted combination of cross-entropy and KL divergence'}
```

## File: facebookresearch_pytext/pytext/loss/tests/samplewise_label_smoothing_loss_test.py

Prompts

```
['test the CTCLoss class by comparing its output against PyTorch F.ctc_loss with random logits and targets', 'run the CTCLossTest unit test to verify CTC loss computation matches PyTorch native implementation', 'create a CTCLoss.Config object and set the blank label to 0 for CuDNN support', 'build a CTCLoss instance from config and call it with logits, targets, input lengths, and target lengths', 'review the CTCLossTest class and test_ctc_loss method to understand CTC loss validation against PyTorch', 'test the FocalLoss class by verifying it matches NLL loss when gamma is zero', 'test the BinaryFocalLoss class by verifying it matches binary cross entropy when gamma is zero', 'run the FocalLossTest unittest suite to validate focal loss implementations against baseline PyTorch losses', 'review the FocalLossTest class and its test methods for focal loss correctness', 'refactor the FocalLossTest class to add additional edge case tests for focal loss', 'test the LabelSmoothedCrossEntropyLoss forward pass with random logits and targets across 50 iterations', 'test the LabelSmoothedCrossEntropyLoss forward pass with SourceType.PROBS config and fixed input tensors', 'compute the negative cross-entropy loss from logits and targets with optional weight and ignore index', 'compute the negative KL divergence between log probabilities and uniform distribution across classes', 'compute the manual label-smoothed loss as a weighted combination of cross-entropy and KL divergence', 'test the SamplewiseLabelSmoothingLoss class to verify it produces equivalent results to LabelSmoothingLoss', 'run the unittest to compare LabelSmoothingLoss and SamplewiseLabelSmoothingLoss outputs with reduce true and false', 'create a LabelSmoothingLoss instance using LabelSmoothingLoss.Config with an ignore_index parameter', 'create a SamplewiseLabelSmoothingLoss instance using SamplewiseLabelSmoothingLoss.Config with an ignore_index parameter', 'review the SamplewiseLabelSmoothingLossTest class and its test_samplewise_label_smoothing_loss method for correctness']
```

Usage

```
{'test_samplewise_label_smoothing_loss': 'test the SamplewiseLabelSmoothingLoss class to verify it produces equivalent results to LabelSmoothingLoss', 'run_label_smoothing_loss_test': 'run the unittest to compare LabelSmoothingLoss and SamplewiseLabelSmoothingLoss outputs with reduce true and false', 'create_label_smoothing_loss': 'create a LabelSmoothingLoss instance using LabelSmoothingLoss.Config with an ignore_index parameter', 'create_samplewise_label_smoothing_loss': 'create a SamplewiseLabelSmoothingLoss instance using SamplewiseLabelSmoothingLoss.Config with an ignore_index parameter', 'review_samplewise_label_smoothing_loss_test': 'review the SamplewiseLabelSmoothingLossTest class and its test_samplewise_label_smoothing_loss method for correctness'}
```

