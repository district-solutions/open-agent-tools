# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/slanet/modeling_slanet.py

Prompts

```
['build a SLANetForTableRecognition model with SLANetConfig for table recognition tasks', 'create a SLANetSLAHead that generates structure predictions using attention GRU cells', 'build a SLANetBackbone with vision backbone and CSP-PAN for feature extraction', 'test the SLANetForTableRecognition forward pass with pixel values input tensor', 'summarize the SLANetCSPPAN class that implements path aggregation with cross stage partial layers', 'create a SLANetConfig with backbone, hidden_size, and CSP layer parameters for table recognition', 'build a SLANetBackbone with PP-LCNet vision backbone and CSP-PAN feature pyramid', 'build a Cross Stage Partial layer that splits, processes, and fuses feature maps']
```

Usage

```
{'build_slanet_table_recognition_model': 'build a SLANetForTableRecognition model with SLANetConfig for table recognition tasks', 'create_slanet_sla_head': 'create a SLANetSLAHead that generates structure predictions using attention GRU cells', 'build_slanet_backbone': 'build a SLANetBackbone with vision backbone and CSP-PAN for feature extraction', 'test_slanet_forward_pass': 'test the SLANetForTableRecognition forward pass with pixel values input tensor', 'summarize_slanet_csp_pan': 'summarize the SLANetCSPPAN class that implements path aggregation with cross stage partial layers'}
```

## File: huggingface_transformers/src/transformers/models/slanet/modular_slanet.py

Prompts

```
['build a SLANetForTableRecognition model with SLANetConfig for table recognition tasks', 'create a SLANetSLAHead that generates structure predictions using attention GRU cells', 'build a SLANetBackbone with vision backbone and CSP-PAN for feature extraction', 'test the SLANetForTableRecognition forward pass with pixel values input tensor', 'summarize the SLANetCSPPAN class that implements path aggregation with cross stage partial layers', 'create a SLANetConfig with backbone, hidden_size, and CSP layer parameters for table recognition', 'build a SLANetBackbone with PP-LCNet vision backbone and CSP-PAN feature pyramid', 'build a Cross Stage Partial layer that splits, processes, and fuses feature maps']
```

Usage

```
{'create_slanet_config': 'create a SLANetConfig with backbone, hidden_size, and CSP layer parameters for table recognition', 'build_slanet_table_recognition_model': 'build a SLANetForTableRecognition model that runs autoregressive structure and location decoding', 'build_slanet_backbone_with_csp_pan': 'build a SLANetBackbone with PP-LCNet vision backbone and CSP-PAN feature pyramid', 'build_slanet_csp_layer': 'build a Cross Stage Partial layer that splits, processes, and fuses feature maps', 'test_slanet_forward_pass': 'test the SLANetForTableRecognition forward pass with pixel values and return structure predictions'}
```

