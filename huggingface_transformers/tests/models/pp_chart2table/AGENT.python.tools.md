# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/pp_chart2table/test_modeling_pp_chart2table.py

Prompts

```
['test the PPChart2TableIntegrationTest class loads the PaddlePaddle/PP-Chart2Table_safetensors model and verifies chart-to-table text generation', 'create an AutoModelForImageTextToText instance from the PaddlePaddle/PP-Chart2Table_safetensors pretrained checkpoint', 'create an AutoProcessor instance from the PaddlePaddle/PP-Chart2Table_safetensors checkpoint for image and text tokenization', 'run the model.generate method with apply_chat_template inputs to produce chart-to-table text output without sampling', 'test batched inference by passing two identical conversations and verifying matching decoded outputs from model.generate']
```

Usage

```
{'test_pp_chart2table_integration': 'test the PPChart2TableIntegrationTest class loads the PaddlePaddle/PP-Chart2Table_safetensors model and verifies chart-to-table text generation', 'create_model_from_pretrained': 'create an AutoModelForImageTextToText instance from the PaddlePaddle/PP-Chart2Table_safetensors pretrained checkpoint', 'create_processor_from_pretrained': 'create an AutoProcessor instance from the PaddlePaddle/PP-Chart2Table_safetensors checkpoint for image and text tokenization', 'run_model_generate': 'run the model.generate method with apply_chat_template inputs to produce chart-to-table text output without sampling', 'test_batched_inference': 'test batched inference by passing two identical conversations and verifying matching decoded outputs from model.generate'}
```

