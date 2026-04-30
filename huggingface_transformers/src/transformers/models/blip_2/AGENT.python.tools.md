# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/blip_2/convert_blip_2_original_to_pytorch.py

Prompts

```
['convert a BLIP-2 checkpoint from Salesforce LAVIS to HuggingFace Transformers format', 'get a Blip2Config and image size for a given model name and eos token id', 'read q and v biases from the original state dict and concatenate them into qkv bias', 'create a list of key renaming pairs from original LAVIS to HuggingFace Transformers naming', 'download and return a demo image from the LAVIS assets URL', 'generate image captions using Blip2ForConditionalGeneration with pixel values and optional text prompts', 'run visual question answering with Blip2ForConditionalGeneration.generate on images and question prompts', 'retrieve relevant image-text pairs using Blip2ForImageTextRetrieval with contrastive or matching heads', 'extract normalized image embeddings from Blip2VisionModelWithProjection for contrastive retrieval tasks', 'extract normalized text embeddings from Blip2TextModelWithProjection for contrastive retrieval tasks']
```

Usage

```
{'convert_blip2_checkpoint': 'convert a BLIP-2 checkpoint from Salesforce LAVIS to HuggingFace Transformers format', 'get_blip2_config': 'get a Blip2Config and image size for a given model name and eos token id', 'read_in_q_v_bias': 'read q and v biases from the original state dict and concatenate them into qkv bias', 'create_rename_keys': 'create a list of key renaming pairs from original LAVIS to HuggingFace Transformers naming', 'load_demo_image': 'download and return a demo image from the LAVIS assets URL'}
```

## File: huggingface_transformers/src/transformers/models/blip_2/modeling_blip_2.py

Prompts

```
['convert a BLIP-2 checkpoint from Salesforce LAVIS to HuggingFace Transformers format', 'get a Blip2Config and image size for a given model name and eos token id', 'read q and v biases from the original state dict and concatenate them into qkv bias', 'create a list of key renaming pairs from original LAVIS to HuggingFace Transformers naming', 'download and return a demo image from the LAVIS assets URL', 'generate image captions using Blip2ForConditionalGeneration with pixel values and optional text prompts', 'run visual question answering with Blip2ForConditionalGeneration.generate on images and question prompts', 'retrieve relevant image-text pairs using Blip2ForImageTextRetrieval with contrastive or matching heads', 'extract normalized image embeddings from Blip2VisionModelWithProjection for contrastive retrieval tasks', 'extract normalized text embeddings from Blip2TextModelWithProjection for contrastive retrieval tasks']
```

Usage

```
{'generate_image_captions': 'generate image captions using Blip2ForConditionalGeneration with pixel values and optional text prompts', 'run_visual_question_answering': 'run visual question answering with Blip2ForConditionalGeneration.generate on images and question prompts', 'retrieve_image_text_pairs': 'retrieve relevant image-text pairs using Blip2ForImageTextRetrieval with contrastive or matching heads', 'extract_image_embeddings': 'extract normalized image embeddings from Blip2VisionModelWithProjection for contrastive retrieval tasks', 'extract_text_embeddings': 'extract normalized text embeddings from Blip2TextModelWithProjection for contrastive retrieval tasks'}
```

