# Agent Python Tools

- repo: facebookresearch/qinco
- repo_uri: https://github.com/facebookresearch/qinco

## File: facebookresearch_qinco/qinco/model/qinco_base.py

Prompts

```
['initialize QINCo model codebook weights from RQ centroids with configurable noise', 'run the QConcat module to concatenate and transform codeword and residual tensors', 'run a residual FFN block with up projection, ReLU, and down projection', 'encode input vectors through a QINCo quantization step with beam search and substep candidates', 'run the QINCo quantizer in train, encode, or decode mode on input tensors', 'build a QINCo inference wrapper that encodes and decodes vectors using a trained QINCo model', 'encode input vectors into discrete codes using the QINCoInferenceEncoder with beam search', 'decode discrete codes back to reconstructed vectors using the QINCoInferenceDecoder', 'optimize the QINCo encoder and decoder models using TorchScript JIT compilation for inference', 'review the QINCoInferenceStepEncoder class that performs sub-RQ candidate fetching and code assignment', 'create a RampCosineLRSchedule with a linear warmup ramp followed by a cosine decay schedule', 'create a NoLRScheduler that keeps the learning rate constant throughout training', 'review the RampCosineLRSchedule class and its step function for warmup and cosine decay logic', 'review the NoLRScheduler class and its constant learning rate lambda function', 'summarize the RampCosineLRSchedule and NoLRScheduler LambdaLR subclasses for PyTorch optimizer scheduling']
```

Usage

```
{'initialize_qinco_codebooks': 'initialize QINCo model codebook weights from RQ centroids with configurable noise', 'QConcat_forward': 'run the QConcat module to concatenate and transform codeword and residual tensors', 'QBlockFFN_forward': 'run a residual FFN block with up projection, ReLU, and down projection', 'QINCoStep_encode': 'encode input vectors through a QINCo quantization step with beam search and substep candidates', 'QINCo_forward': 'run the QINCo quantizer in train, encode, or decode mode on input tensors'}
```

## File: facebookresearch_qinco/qinco/model/qinco_inference.py

Prompts

```
['initialize QINCo model codebook weights from RQ centroids with configurable noise', 'run the QConcat module to concatenate and transform codeword and residual tensors', 'run a residual FFN block with up projection, ReLU, and down projection', 'encode input vectors through a QINCo quantization step with beam search and substep candidates', 'run the QINCo quantizer in train, encode, or decode mode on input tensors', 'build a QINCo inference wrapper that encodes and decodes vectors using a trained QINCo model', 'encode input vectors into discrete codes using the QINCoInferenceEncoder with beam search', 'decode discrete codes back to reconstructed vectors using the QINCoInferenceDecoder', 'optimize the QINCo encoder and decoder models using TorchScript JIT compilation for inference', 'review the QINCoInferenceStepEncoder class that performs sub-RQ candidate fetching and code assignment', 'create a RampCosineLRSchedule with a linear warmup ramp followed by a cosine decay schedule', 'create a NoLRScheduler that keeps the learning rate constant throughout training', 'review the RampCosineLRSchedule class and its step function for warmup and cosine decay logic', 'review the NoLRScheduler class and its constant learning rate lambda function', 'summarize the RampCosineLRSchedule and NoLRScheduler LambdaLR subclasses for PyTorch optimizer scheduling']
```

Usage

```
{'build_QINCoInferenceWrapper': 'build a QINCo inference wrapper that encodes and decodes vectors using a trained QINCo model', 'encode_vectors_with_QINCoInferenceEncoder': 'encode input vectors into discrete codes using the QINCoInferenceEncoder with beam search', 'decode_codes_with_QINCoInferenceDecoder': 'decode discrete codes back to reconstructed vectors using the QINCoInferenceDecoder', 'optimize_model_with_torch_jit': 'optimize the QINCo encoder and decoder models using TorchScript JIT compilation for inference', 'review_QINCoInferenceStepEncoder': 'review the QINCoInferenceStepEncoder class that performs sub-RQ candidate fetching and code assignment'}
```

## File: facebookresearch_qinco/qinco/model/scheduler.py

Prompts

```
['initialize QINCo model codebook weights from RQ centroids with configurable noise', 'run the QConcat module to concatenate and transform codeword and residual tensors', 'run a residual FFN block with up projection, ReLU, and down projection', 'encode input vectors through a QINCo quantization step with beam search and substep candidates', 'run the QINCo quantizer in train, encode, or decode mode on input tensors', 'build a QINCo inference wrapper that encodes and decodes vectors using a trained QINCo model', 'encode input vectors into discrete codes using the QINCoInferenceEncoder with beam search', 'decode discrete codes back to reconstructed vectors using the QINCoInferenceDecoder', 'optimize the QINCo encoder and decoder models using TorchScript JIT compilation for inference', 'review the QINCoInferenceStepEncoder class that performs sub-RQ candidate fetching and code assignment', 'create a RampCosineLRSchedule with a linear warmup ramp followed by a cosine decay schedule', 'create a NoLRScheduler that keeps the learning rate constant throughout training', 'review the RampCosineLRSchedule class and its step function for warmup and cosine decay logic', 'review the NoLRScheduler class and its constant learning rate lambda function', 'summarize the RampCosineLRSchedule and NoLRScheduler LambdaLR subclasses for PyTorch optimizer scheduling']
```

Usage

```
{'create_ramp_cosine_lr_schedule': 'create a RampCosineLRSchedule with a linear warmup ramp followed by a cosine decay schedule', 'create_no_lr_scheduler': 'create a NoLRScheduler that keeps the learning rate constant throughout training', 'review_ramp_cosine_lr_schedule': 'review the RampCosineLRSchedule class and its step function for warmup and cosine decay logic', 'review_no_lr_scheduler': 'review the NoLRScheduler class and its constant learning rate lambda function', 'summarize_scheduler_classes': 'summarize the RampCosineLRSchedule and NoLRScheduler LambdaLR subclasses for PyTorch optimizer scheduling'}
```

