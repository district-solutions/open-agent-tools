# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/vcnplus/models/networks/DCNv2/DCN/dcn_v2.py

Prompts

```
['build a DCN deformable convolution layer with 256 input channels and a 3x3 kernel', 'build a DCNv2 module with external offset and mask tensors for deformable convolution', 'build a DCNPooling module that predicts offsets and masks from ROI features', 'test the dcn_v2_conv autograd function with sample input, offset, mask, weight, and bias tensors', 'test the dcn_v2_pooling function with feature maps, ROIs, and offset tensors', 'run the DCN deformable convolution example with a 2x64x128x128 input tensor and backward pass', 'run the DCNv2 deformable pooling example with ROI alignment on a 2x32x64x64 input tensor', 'run the DCNPooling multi-deformable pooling example with ROI regions and backward gradient computation', 'test the DCNv2 convolution zero offset check to verify identity behavior when offsets are zero', 'test the DCNv2 convolution gradient correctness using PyTorch gradcheck on input, offset, mask, weight, and bias', 'test the DCNv2 zero offset check to verify identity convolution behavior with zero offsets']
```

Usage

```
{'build_DCN_layer': 'build a DCN deformable convolution layer with 256 input channels and a 3x3 kernel', 'build_DCNv2_layer': 'build a DCNv2 module with external offset and mask tensors for deformable convolution', 'build_DCNPooling_layer': 'build a DCNPooling module that predicts offsets and masks from ROI features', 'test_dcn_v2_conv': 'test the dcn_v2_conv autograd function with sample input, offset, mask, weight, and bias tensors', 'test_dcn_v2_pooling': 'test the dcn_v2_pooling function with feature maps, ROIs, and offset tensors'}
```

## File: facebookresearch_banmo/third_party/vcnplus/models/networks/DCNv2/DCN/testcpu.py

Prompts

```
['build a DCN deformable convolution layer with 256 input channels and a 3x3 kernel', 'build a DCNv2 module with external offset and mask tensors for deformable convolution', 'build a DCNPooling module that predicts offsets and masks from ROI features', 'test the dcn_v2_conv autograd function with sample input, offset, mask, weight, and bias tensors', 'test the dcn_v2_pooling function with feature maps, ROIs, and offset tensors', 'run the DCN deformable convolution example with a 2x64x128x128 input tensor and backward pass', 'run the DCNv2 deformable pooling example with ROI alignment on a 2x32x64x64 input tensor', 'run the DCNPooling multi-deformable pooling example with ROI regions and backward gradient computation', 'test the DCNv2 convolution zero offset check to verify identity behavior when offsets are zero', 'test the DCNv2 convolution gradient correctness using PyTorch gradcheck on input, offset, mask, weight, and bias', 'test the DCNv2 zero offset check to verify identity convolution behavior with zero offsets']
```

Usage

```
{'run_deformable_conv_example': 'run the DCN deformable convolution example with a 2x64x128x128 input tensor and backward pass', 'run_deformable_pooling_example': 'run the DCNv2 deformable pooling example with ROI alignment on a 2x32x64x64 input tensor', 'run_mdformable_pooling_example': 'run the DCNPooling multi-deformable pooling example with ROI regions and backward gradient computation', 'test_zero_offset_dconv': 'test the DCNv2 convolution zero offset check to verify identity behavior when offsets are zero', 'test_gradient_dconv': 'test the DCNv2 convolution gradient correctness using PyTorch gradcheck on input, offset, mask, weight, and bias'}
```

## File: facebookresearch_banmo/third_party/vcnplus/models/networks/DCNv2/DCN/testcuda.py

Prompts

```
['build a DCN deformable convolution layer with 256 input channels and a 3x3 kernel', 'build a DCNv2 module with external offset and mask tensors for deformable convolution', 'build a DCNPooling module that predicts offsets and masks from ROI features', 'test the dcn_v2_conv autograd function with sample input, offset, mask, weight, and bias tensors', 'test the dcn_v2_pooling function with feature maps, ROIs, and offset tensors', 'run the DCN deformable convolution example with a 2x64x128x128 input tensor and backward pass', 'run the DCNv2 deformable pooling example with ROI alignment on a 2x32x64x64 input tensor', 'run the DCNPooling multi-deformable pooling example with ROI regions and backward gradient computation', 'test the DCNv2 convolution zero offset check to verify identity behavior when offsets are zero', 'test the DCNv2 convolution gradient correctness using PyTorch gradcheck on input, offset, mask, weight, and bias', 'test the DCNv2 zero offset check to verify identity convolution behavior with zero offsets']
```

Usage

```
{'run_deformable_conv_example': 'run the DCN deformable convolution example on a CUDA tensor and verify backward pass', 'run_deformable_pooling_example': 'run the DCNv2Pooling deformable pooling example with ROIs and offset tensors on CUDA', 'run_mdformable_pooling_example': 'run the DCNPooling multi-deformable pooling example with deform_fc_dim and backward pass', 'test_zero_offset_check': 'test the DCNv2 zero offset check to verify identity convolution behavior with zero offsets', 'test_gradient_dconv': 'test the dcn_v2_conv gradient correctness using torch.autograd.gradcheck on CUDA tensors'}
```

