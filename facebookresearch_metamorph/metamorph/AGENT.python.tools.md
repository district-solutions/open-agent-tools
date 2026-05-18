# Agent Python Tools

- repo: facebookresearch/metamorph
- repo_uri: https://github.com/facebookresearch/metamorph

## File: facebookresearch_metamorph/metamorph/conversation.py

Prompts

```
['generate a formatted prompt string from a Conversation object using the configured separator style', 'append a new role and message pair to the Conversation message history', 'process a PIL image with padding cropping or resizing and return base64 or PIL', 'convert the Conversation message history into a Gradio chatbot compatible format with embedded images', 'create a deep copy of a Conversation instance preserving all messages and configuration', 'process a list of PIL images using pad or anyres aspect ratio strategies for a multimodal model', 'select the best fit resolution from a list of candidates based on an original image size', 'resize a PIL image to a target resolution while maintaining aspect ratio and padding with black', 'divide a PIL image into a list of smaller square patches of a specified size', 'tokenize a text prompt containing image placeholders by inserting image token indices at split points', 'build a logger with timed rotating file handler and stdout stderr redirection', 'create a StreamToLogger instance that redirects stdout or stderr writes to a logger', 'disable torch Linear and LayerNorm reset_parameters to accelerate model creation', 'check whether given text violates OpenAI moderation API guidelines', 'print a human-readable string representation of a semaphore object']
```

Usage

```
{'get_prompt_conversation': 'generate a formatted prompt string from a Conversation object using the configured separator style', 'append_message_conversation': 'append a new role and message pair to the Conversation message history', 'process_image_conversation': 'process a PIL image with padding cropping or resizing and return base64 or PIL', 'to_gradio_chatbot_conversation': 'convert the Conversation message history into a Gradio chatbot compatible format with embedded images', 'copy_conversation': 'create a deep copy of a Conversation instance preserving all messages and configuration'}
```

## File: facebookresearch_metamorph/metamorph/mm_utils.py

Prompts

```
['generate a formatted prompt string from a Conversation object using the configured separator style', 'append a new role and message pair to the Conversation message history', 'process a PIL image with padding cropping or resizing and return base64 or PIL', 'convert the Conversation message history into a Gradio chatbot compatible format with embedded images', 'create a deep copy of a Conversation instance preserving all messages and configuration', 'process a list of PIL images using pad or anyres aspect ratio strategies for a multimodal model', 'select the best fit resolution from a list of candidates based on an original image size', 'resize a PIL image to a target resolution while maintaining aspect ratio and padding with black', 'divide a PIL image into a list of smaller square patches of a specified size', 'tokenize a text prompt containing image placeholders by inserting image token indices at split points', 'build a logger with timed rotating file handler and stdout stderr redirection', 'create a StreamToLogger instance that redirects stdout or stderr writes to a logger', 'disable torch Linear and LayerNorm reset_parameters to accelerate model creation', 'check whether given text violates OpenAI moderation API guidelines', 'print a human-readable string representation of a semaphore object']
```

Usage

```
{'process_images_for_multimodal_model': 'process a list of PIL images using pad or anyres aspect ratio strategies for a multimodal model', 'select_best_resolution_for_image': 'select the best fit resolution from a list of candidates based on an original image size', 'resize_and_pad_image_to_target': 'resize a PIL image to a target resolution while maintaining aspect ratio and padding with black', 'divide_image_into_patches': 'divide a PIL image into a list of smaller square patches of a specified size', 'tokenize_prompt_with_image_tokens': 'tokenize a text prompt containing image placeholders by inserting image token indices at split points'}
```

## File: facebookresearch_metamorph/metamorph/utils.py

Prompts

```
['generate a formatted prompt string from a Conversation object using the configured separator style', 'append a new role and message pair to the Conversation message history', 'process a PIL image with padding cropping or resizing and return base64 or PIL', 'convert the Conversation message history into a Gradio chatbot compatible format with embedded images', 'create a deep copy of a Conversation instance preserving all messages and configuration', 'process a list of PIL images using pad or anyres aspect ratio strategies for a multimodal model', 'select the best fit resolution from a list of candidates based on an original image size', 'resize a PIL image to a target resolution while maintaining aspect ratio and padding with black', 'divide a PIL image into a list of smaller square patches of a specified size', 'tokenize a text prompt containing image placeholders by inserting image token indices at split points', 'build a logger with timed rotating file handler and stdout stderr redirection', 'create a StreamToLogger instance that redirects stdout or stderr writes to a logger', 'disable torch Linear and LayerNorm reset_parameters to accelerate model creation', 'check whether given text violates OpenAI moderation API guidelines', 'print a human-readable string representation of a semaphore object']
```

Usage

```
{'build_logger': 'build a logger with timed rotating file handler and stdout stderr redirection', 'create_StreamToLogger': 'create a StreamToLogger instance that redirects stdout or stderr writes to a logger', 'disable_torch_init': 'disable torch Linear and LayerNorm reset_parameters to accelerate model creation', 'check_violates_moderation': 'check whether given text violates OpenAI moderation API guidelines', 'print_semaphore': 'print a human-readable string representation of a semaphore object'}
```

