# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/predictors/chart.py

Prompts

```
['build a DensePoseChartPredictor module with ConvTranspose2d layers for coarse and fine segmentation using Detectron2 config', 'create a forward pass through DensePoseChartPredictor to produce coarse segmentation, fine segmentation, U and V coordinate tensors', 'test the interp2d method to bilinearly upscale a tensor using a configurable scale factor', 'review the four ConvTranspose2d layers for ann_index, index_uv, U, and V low-resolution outputs', 'summarize the DensePoseChartPredictorOutput structure containing coarse segmentation, fine segmentation, U and V coordinate tensors', 'initialize a DensePoseChartConfidencePredictorMixin with a CfgNode config and input channel count', 'run forward pass on head outputs to compute UV and segmentation confidence estimates', 'initialize confidence estimation ConvTranspose2d layers for IID_ISO or INDEP_ANISO UV confidence types', 'create a predictor output instance decorated with confidence fields from base predictor outputs', 'review the DensePoseChartConfidencePredictorMixin class to understand how it generates confidence estimates for segmentation and UV tensors', 'build a DensePoseEmbeddingPredictor module from a Detectron2 config node and input channel count', 'run the forward pass of DensePoseEmbeddingPredictor on head outputs to get CSE embeddings and coarse segmentation', 'create a DensePoseEmbeddingPredictorOutput with embedding and coarse segmentation tensors from head outputs', 'review the interp2d method that performs bilinear interpolation upscaling on NCHW tensors', 'test the coarse segmentation ConvTranspose2d branch producing low-resolution segmentation channels', 'initialize a DensePoseEmbeddingConfidencePredictorMixin with a CfgNode config and input channel count', 'run forward pass on head outputs to compute coarse segmentation confidence estimates', 'review the DensePoseEmbeddingConfidencePredictorMixin class for confidence estimation in coarse segmentation']
```

Usage

```
{'build_DensePoseChartPredictor': 'build a DensePoseChartPredictor module with ConvTranspose2d layers for coarse and fine segmentation using Detectron2 config', 'create_forward_predictions': 'create a forward pass through DensePoseChartPredictor to produce coarse segmentation, fine segmentation, U and V coordinate tensors', 'test_interp2d_upscaling': 'test the interp2d method to bilinearly upscale a tensor using a configurable scale factor', 'review_ConvTranspose2d_layers': 'review the four ConvTranspose2d layers for ann_index, index_uv, U, and V low-resolution outputs', 'summarize_DensePoseChartPredictorOutput': 'summarize the DensePoseChartPredictorOutput structure containing coarse segmentation, fine segmentation, U and V coordinate tensors'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/predictors/chart_confidence.py

Prompts

```
['build a DensePoseChartPredictor module with ConvTranspose2d layers for coarse and fine segmentation using Detectron2 config', 'create a forward pass through DensePoseChartPredictor to produce coarse segmentation, fine segmentation, U and V coordinate tensors', 'test the interp2d method to bilinearly upscale a tensor using a configurable scale factor', 'review the four ConvTranspose2d layers for ann_index, index_uv, U, and V low-resolution outputs', 'summarize the DensePoseChartPredictorOutput structure containing coarse segmentation, fine segmentation, U and V coordinate tensors', 'initialize a DensePoseChartConfidencePredictorMixin with a CfgNode config and input channel count', 'run forward pass on head outputs to compute UV and segmentation confidence estimates', 'initialize confidence estimation ConvTranspose2d layers for IID_ISO or INDEP_ANISO UV confidence types', 'create a predictor output instance decorated with confidence fields from base predictor outputs', 'review the DensePoseChartConfidencePredictorMixin class to understand how it generates confidence estimates for segmentation and UV tensors', 'build a DensePoseEmbeddingPredictor module from a Detectron2 config node and input channel count', 'run the forward pass of DensePoseEmbeddingPredictor on head outputs to get CSE embeddings and coarse segmentation', 'create a DensePoseEmbeddingPredictorOutput with embedding and coarse segmentation tensors from head outputs', 'review the interp2d method that performs bilinear interpolation upscaling on NCHW tensors', 'test the coarse segmentation ConvTranspose2d branch producing low-resolution segmentation channels', 'initialize a DensePoseEmbeddingConfidencePredictorMixin with a CfgNode config and input channel count', 'run forward pass on head outputs to compute coarse segmentation confidence estimates', 'review the DensePoseEmbeddingConfidencePredictorMixin class for confidence estimation in coarse segmentation']
```

Usage

```
{'init_chart_confidence_predictor': 'initialize a DensePoseChartConfidencePredictorMixin with a CfgNode config and input channel count', 'forward_chart_confidence': 'run forward pass on head outputs to compute UV and segmentation confidence estimates', 'initialize_confidence_layers': 'initialize confidence estimation ConvTranspose2d layers for IID_ISO or INDEP_ANISO UV confidence types', 'create_output_instance': 'create a predictor output instance decorated with confidence fields from base predictor outputs', 'review_chart_confidence_mixin': 'review the DensePoseChartConfidencePredictorMixin class to understand how it generates confidence estimates for segmentation and UV tensors'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/predictors/cse.py

Prompts

```
['build a DensePoseChartPredictor module with ConvTranspose2d layers for coarse and fine segmentation using Detectron2 config', 'create a forward pass through DensePoseChartPredictor to produce coarse segmentation, fine segmentation, U and V coordinate tensors', 'test the interp2d method to bilinearly upscale a tensor using a configurable scale factor', 'review the four ConvTranspose2d layers for ann_index, index_uv, U, and V low-resolution outputs', 'summarize the DensePoseChartPredictorOutput structure containing coarse segmentation, fine segmentation, U and V coordinate tensors', 'initialize a DensePoseChartConfidencePredictorMixin with a CfgNode config and input channel count', 'run forward pass on head outputs to compute UV and segmentation confidence estimates', 'initialize confidence estimation ConvTranspose2d layers for IID_ISO or INDEP_ANISO UV confidence types', 'create a predictor output instance decorated with confidence fields from base predictor outputs', 'review the DensePoseChartConfidencePredictorMixin class to understand how it generates confidence estimates for segmentation and UV tensors', 'build a DensePoseEmbeddingPredictor module from a Detectron2 config node and input channel count', 'run the forward pass of DensePoseEmbeddingPredictor on head outputs to get CSE embeddings and coarse segmentation', 'create a DensePoseEmbeddingPredictorOutput with embedding and coarse segmentation tensors from head outputs', 'review the interp2d method that performs bilinear interpolation upscaling on NCHW tensors', 'test the coarse segmentation ConvTranspose2d branch producing low-resolution segmentation channels', 'initialize a DensePoseEmbeddingConfidencePredictorMixin with a CfgNode config and input channel count', 'run forward pass on head outputs to compute coarse segmentation confidence estimates', 'review the DensePoseEmbeddingConfidencePredictorMixin class for confidence estimation in coarse segmentation']
```

Usage

```
{'build_cse_predictor': 'build a DensePoseEmbeddingPredictor module from a Detectron2 config node and input channel count', 'run_forward_cse': 'run the forward pass of DensePoseEmbeddingPredictor on head outputs to get CSE embeddings and coarse segmentation', 'create_embedding_output': 'create a DensePoseEmbeddingPredictorOutput with embedding and coarse segmentation tensors from head outputs', 'review_interp2d_upscale': 'review the interp2d method that performs bilinear interpolation upscaling on NCHW tensors', 'test_coarse_segm_branch': 'test the coarse segmentation ConvTranspose2d branch producing low-resolution segmentation channels'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/predictors/cse_confidence.py

Prompts

```
['build a DensePoseChartPredictor module with ConvTranspose2d layers for coarse and fine segmentation using Detectron2 config', 'create a forward pass through DensePoseChartPredictor to produce coarse segmentation, fine segmentation, U and V coordinate tensors', 'test the interp2d method to bilinearly upscale a tensor using a configurable scale factor', 'review the four ConvTranspose2d layers for ann_index, index_uv, U, and V low-resolution outputs', 'summarize the DensePoseChartPredictorOutput structure containing coarse segmentation, fine segmentation, U and V coordinate tensors', 'initialize a DensePoseChartConfidencePredictorMixin with a CfgNode config and input channel count', 'run forward pass on head outputs to compute UV and segmentation confidence estimates', 'initialize confidence estimation ConvTranspose2d layers for IID_ISO or INDEP_ANISO UV confidence types', 'create a predictor output instance decorated with confidence fields from base predictor outputs', 'review the DensePoseChartConfidencePredictorMixin class to understand how it generates confidence estimates for segmentation and UV tensors', 'build a DensePoseEmbeddingPredictor module from a Detectron2 config node and input channel count', 'run the forward pass of DensePoseEmbeddingPredictor on head outputs to get CSE embeddings and coarse segmentation', 'create a DensePoseEmbeddingPredictorOutput with embedding and coarse segmentation tensors from head outputs', 'review the interp2d method that performs bilinear interpolation upscaling on NCHW tensors', 'test the coarse segmentation ConvTranspose2d branch producing low-resolution segmentation channels', 'initialize a DensePoseEmbeddingConfidencePredictorMixin with a CfgNode config and input channel count', 'run forward pass on head outputs to compute coarse segmentation confidence estimates', 'review the DensePoseEmbeddingConfidencePredictorMixin class for confidence estimation in coarse segmentation']
```

Usage

```
{'init_confidence_predictor': 'initialize a DensePoseEmbeddingConfidencePredictorMixin with a CfgNode config and input channel count', 'initialize_confidence_layers': 'build confidence estimation layers using a transposed convolution for coarse segmentation confidence', 'forward_confidence_prediction': 'run forward pass on head outputs to compute coarse segmentation confidence estimates', 'create_output_instance': 'create a predictor output instance by decorating base outputs with confidence fields', 'review_confidence_mixin': 'review the DensePoseEmbeddingConfidencePredictorMixin class for confidence estimation in coarse segmentation'}
```

