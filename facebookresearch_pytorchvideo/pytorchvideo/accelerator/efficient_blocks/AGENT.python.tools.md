# Agent Python Tools

- repo: facebookresearch/pytorchvideo
- repo_uri: https://github.com/facebookresearch/pytorchvideo

## File: facebookresearch_pytorchvideo/pytorchvideo/accelerator/efficient_blocks/efficient_block_base.py

Prompts

```
['create a subclass of EfficientBlockBase that implements convert and forward methods', 'implement the convert method to transform an efficient block into deployable form', "implement the forward method to define the block's training-time computation graph", 'review the EfficientBlockBase abstract class and its convert and forward method contracts', 'summarize the EfficientBlockBase class and its original versus deployable form design', 'create a NoOpConvertBlock instance that wraps an nn.Module without applying conversion', 'use NoOpConvertBlock forward method to pass input through the wrapped model unchanged', 'call NoOpConvertBlock convert method which performs no operation on the wrapped model', 'review the NoOpConvertBlock class that provides a no-op wrapper for EfficientBlockBase compatibility', 'refactor NoOpConvertBlock to wrap an nn.Module that does not need hardware-specific conversion']
```

Usage

```
{'create_efficient_block_subclass': 'create a subclass of EfficientBlockBase that implements convert and forward methods', 'implement_convert_method': 'implement the convert method to transform an efficient block into deployable form', 'implement_forward_method': "implement the forward method to define the block's training-time computation graph", 'review_EfficientBlockBase': 'review the EfficientBlockBase abstract class and its convert and forward method contracts', 'summarize_EfficientBlockBase': 'summarize the EfficientBlockBase class and its original versus deployable form design'}
```

## File: facebookresearch_pytorchvideo/pytorchvideo/accelerator/efficient_blocks/no_op_convert_block.py

Prompts

```
['create a subclass of EfficientBlockBase that implements convert and forward methods', 'implement the convert method to transform an efficient block into deployable form', "implement the forward method to define the block's training-time computation graph", 'review the EfficientBlockBase abstract class and its convert and forward method contracts', 'summarize the EfficientBlockBase class and its original versus deployable form design', 'create a NoOpConvertBlock instance that wraps an nn.Module without applying conversion', 'use NoOpConvertBlock forward method to pass input through the wrapped model unchanged', 'call NoOpConvertBlock convert method which performs no operation on the wrapped model', 'review the NoOpConvertBlock class that provides a no-op wrapper for EfficientBlockBase compatibility', 'refactor NoOpConvertBlock to wrap an nn.Module that does not need hardware-specific conversion']
```

Usage

```
{'create_NoOpConvertBlock': 'create a NoOpConvertBlock instance that wraps an nn.Module without applying conversion', 'use_NoOpConvertBlock_forward': 'use NoOpConvertBlock forward method to pass input through the wrapped model unchanged', 'call_NoOpConvertBlock_convert': 'call NoOpConvertBlock convert method which performs no operation on the wrapped model', 'review_NoOpConvertBlock': 'review the NoOpConvertBlock class that provides a no-op wrapper for EfficientBlockBase compatibility', 'refactor_NoOpConvertBlock': 'refactor NoOpConvertBlock to wrap an nn.Module that does not need hardware-specific conversion'}
```

