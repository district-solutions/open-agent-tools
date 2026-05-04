# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/predictors/chart.py

Prompts

```
['build a DensePoseChartPredictor instance from a CfgNode config and input channel count', 'run the forward pass on DensePose head outputs to produce chart predictor output tensors', 'create a bilinear interpolation upscaling of an NCHW tensor using the configured scale factor', 'review the four ConvTranspose2d deconvolution layers for coarse segmentation, fine segmentation, U and V coordinates', 'test the DensePoseChartPredictorOutput returned with coarse segmentation, fine segmentation, U and V coordinate tensors', 'build a DensePose chart confidence predictor mixin to generate UV and segmentation confidence estimates', 'initialize ConvTranspose2d layers for UV confidence and segmentation confidence estimation based on config', 'run forward pass on head outputs to compute UV and segmentation confidence values', 'create a predictor output instance decorated with confidence fields from base predictor outputs', 'review the DensePoseChartConfidencePredictorMixin class to understand confidence estimation for DensePose SIUV predictions', 'build a DensePoseEmbeddingPredictor module from a Detectron2 config node and input channel count', 'run the forward pass of DensePoseEmbeddingPredictor on head output tensors to get CSE embeddings', 'test the interp2d method of DensePoseEmbeddingPredictor for bilinear upsampling of NCHW tensors', 'review the DensePoseEmbeddingPredictor constructor to understand ConvTranspose2d layer setup for coarse segmentation and embedding', 'summarize the DensePoseEmbeddingPredictorOutput structure returned by the forward pass with embedding and coarse segmentation', 'initialize a DensePoseEmbeddingConfidencePredictorMixin with a CfgNode config and input channel count', 'run the forward pass on head outputs to compute coarse segmentation confidence estimates', 'create a predictor output instance by copying base predictor outputs and adding confidence fields', 'review the DensePoseEmbeddingConfidencePredictorMixin class to understand how it generates confidence estimates for coarse segmentation']
```

Usage

```
{'build_DensePoseChartPredictor': 'build a DensePoseChartPredictor instance from a CfgNode config and input channel count', 'run_forward_DensePoseChartPredictor': 'run the forward pass on DensePose head outputs to produce chart predictor output tensors', 'create_interp2d_upscaling': 'create a bilinear interpolation upscaling of an NCHW tensor using the configured scale factor', 'review_ConvTranspose2d_layers': 'review the four ConvTranspose2d deconvolution layers for coarse segmentation, fine segmentation, U and V coordinates', 'test_DensePoseChartPredictorOutput': 'test the DensePoseChartPredictorOutput returned with coarse segmentation, fine segmentation, U and V coordinate tensors'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/predictors/chart_confidence.py

Prompts

```
['build a DensePoseChartPredictor instance from a CfgNode config and input channel count', 'run the forward pass on DensePose head outputs to produce chart predictor output tensors', 'create a bilinear interpolation upscaling of an NCHW tensor using the configured scale factor', 'review the four ConvTranspose2d deconvolution layers for coarse segmentation, fine segmentation, U and V coordinates', 'test the DensePoseChartPredictorOutput returned with coarse segmentation, fine segmentation, U and V coordinate tensors', 'build a DensePose chart confidence predictor mixin to generate UV and segmentation confidence estimates', 'initialize ConvTranspose2d layers for UV confidence and segmentation confidence estimation based on config', 'run forward pass on head outputs to compute UV and segmentation confidence values', 'create a predictor output instance decorated with confidence fields from base predictor outputs', 'review the DensePoseChartConfidencePredictorMixin class to understand confidence estimation for DensePose SIUV predictions', 'build a DensePoseEmbeddingPredictor module from a Detectron2 config node and input channel count', 'run the forward pass of DensePoseEmbeddingPredictor on head output tensors to get CSE embeddings', 'test the interp2d method of DensePoseEmbeddingPredictor for bilinear upsampling of NCHW tensors', 'review the DensePoseEmbeddingPredictor constructor to understand ConvTranspose2d layer setup for coarse segmentation and embedding', 'summarize the DensePoseEmbeddingPredictorOutput structure returned by the forward pass with embedding and coarse segmentation', 'initialize a DensePoseEmbeddingConfidencePredictorMixin with a CfgNode config and input channel count', 'run the forward pass on head outputs to compute coarse segmentation confidence estimates', 'create a predictor output instance by copying base predictor outputs and adding confidence fields', 'review the DensePoseEmbeddingConfidencePredictorMixin class to understand how it generates confidence estimates for coarse segmentation']
```

Usage

```
{'build_chart_confidence_predictor': 'build a DensePose chart confidence predictor mixin to generate UV and segmentation confidence estimates', 'initialize_confidence_estimation_layers': 'initialize ConvTranspose2d layers for UV confidence and segmentation confidence estimation based on config', 'forward_confidence_prediction': 'run forward pass on head outputs to compute UV and segmentation confidence values', 'create_output_instance_with_confidences': 'create a predictor output instance decorated with confidence fields from base predictor outputs', 'review_DensePoseChartConfidencePredictorMixin': 'review the DensePoseChartConfidencePredictorMixin class to understand confidence estimation for DensePose SIUV predictions'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/predictors/cse.py

Prompts

```
['build a DensePoseChartPredictor instance from a CfgNode config and input channel count', 'run the forward pass on DensePose head outputs to produce chart predictor output tensors', 'create a bilinear interpolation upscaling of an NCHW tensor using the configured scale factor', 'review the four ConvTranspose2d deconvolution layers for coarse segmentation, fine segmentation, U and V coordinates', 'test the DensePoseChartPredictorOutput returned with coarse segmentation, fine segmentation, U and V coordinate tensors', 'build a DensePose chart confidence predictor mixin to generate UV and segmentation confidence estimates', 'initialize ConvTranspose2d layers for UV confidence and segmentation confidence estimation based on config', 'run forward pass on head outputs to compute UV and segmentation confidence values', 'create a predictor output instance decorated with confidence fields from base predictor outputs', 'review the DensePoseChartConfidencePredictorMixin class to understand confidence estimation for DensePose SIUV predictions', 'build a DensePoseEmbeddingPredictor module from a Detectron2 config node and input channel count', 'run the forward pass of DensePoseEmbeddingPredictor on head output tensors to get CSE embeddings', 'test the interp2d method of DensePoseEmbeddingPredictor for bilinear upsampling of NCHW tensors', 'review the DensePoseEmbeddingPredictor constructor to understand ConvTranspose2d layer setup for coarse segmentation and embedding', 'summarize the DensePoseEmbeddingPredictorOutput structure returned by the forward pass with embedding and coarse segmentation', 'initialize a DensePoseEmbeddingConfidencePredictorMixin with a CfgNode config and input channel count', 'run the forward pass on head outputs to compute coarse segmentation confidence estimates', 'create a predictor output instance by copying base predictor outputs and adding confidence fields', 'review the DensePoseEmbeddingConfidencePredictorMixin class to understand how it generates confidence estimates for coarse segmentation']
```

Usage

```
{'build_DensePoseEmbeddingPredictor': 'build a DensePoseEmbeddingPredictor module from a Detectron2 config node and input channel count', 'run_forward_DensePoseEmbeddingPredictor': 'run the forward pass of DensePoseEmbeddingPredictor on head output tensors to get CSE embeddings', 'test_interp2d_DensePoseEmbeddingPredictor': 'test the interp2d method of DensePoseEmbeddingPredictor for bilinear upsampling of NCHW tensors', 'review_DensePoseEmbeddingPredictor_init': 'review the DensePoseEmbeddingPredictor constructor to understand ConvTranspose2d layer setup for coarse segmentation and embedding', 'summarize_DensePoseEmbeddingPredictorOutput': 'summarize the DensePoseEmbeddingPredictorOutput structure returned by the forward pass with embedding and coarse segmentation'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/predictors/cse_confidence.py

Prompts

```
['build a DensePoseChartPredictor instance from a CfgNode config and input channel count', 'run the forward pass on DensePose head outputs to produce chart predictor output tensors', 'create a bilinear interpolation upscaling of an NCHW tensor using the configured scale factor', 'review the four ConvTranspose2d deconvolution layers for coarse segmentation, fine segmentation, U and V coordinates', 'test the DensePoseChartPredictorOutput returned with coarse segmentation, fine segmentation, U and V coordinate tensors', 'build a DensePose chart confidence predictor mixin to generate UV and segmentation confidence estimates', 'initialize ConvTranspose2d layers for UV confidence and segmentation confidence estimation based on config', 'run forward pass on head outputs to compute UV and segmentation confidence values', 'create a predictor output instance decorated with confidence fields from base predictor outputs', 'review the DensePoseChartConfidencePredictorMixin class to understand confidence estimation for DensePose SIUV predictions', 'build a DensePoseEmbeddingPredictor module from a Detectron2 config node and input channel count', 'run the forward pass of DensePoseEmbeddingPredictor on head output tensors to get CSE embeddings', 'test the interp2d method of DensePoseEmbeddingPredictor for bilinear upsampling of NCHW tensors', 'review the DensePoseEmbeddingPredictor constructor to understand ConvTranspose2d layer setup for coarse segmentation and embedding', 'summarize the DensePoseEmbeddingPredictorOutput structure returned by the forward pass with embedding and coarse segmentation', 'initialize a DensePoseEmbeddingConfidencePredictorMixin with a CfgNode config and input channel count', 'run the forward pass on head outputs to compute coarse segmentation confidence estimates', 'create a predictor output instance by copying base predictor outputs and adding confidence fields', 'review the DensePoseEmbeddingConfidencePredictorMixin class to understand how it generates confidence estimates for coarse segmentation']
```

Usage

```
{'init_confidence_predictor_mixin': 'initialize a DensePoseEmbeddingConfidencePredictorMixin with a CfgNode config and input channel count', 'initialize_confidence_estimation_layers': 'build confidence estimation layers using a deconv kernel size from the config and input dimensions', 'forward_confidence_predictor': 'run the forward pass on head outputs to compute coarse segmentation confidence estimates', 'create_output_instance': 'create a predictor output instance by copying base predictor outputs and adding confidence fields', 'review_confidence_predictor_mixin': 'review the DensePoseEmbeddingConfidencePredictorMixin class to understand how it generates confidence estimates for coarse segmentation'}
```

