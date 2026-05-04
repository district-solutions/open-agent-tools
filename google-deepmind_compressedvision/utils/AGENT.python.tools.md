# Agent Python Tools

- repo: google-deepmind/compressedvision
- repo_uri: https://github.com/google-deepmind/compressed_vision

## File: google-deepmind_compressedvision/utils/checkpoint_loader.py

Prompts

```
['load model checkpoint params and state from a pickle file using load_params_state', 'load the config key from a model checkpoint file using load_params_state', 'load augmentation params and state from a checkpoint using load_params_state', 'validate a checkpoint pickle file contains all required keys using load_params_state', 'extract all saved values from a checkpoint file using load_params_state', 'build a python module that converts input images to discrete codes using a codec encoder', 'build a python module that decodes discrete codes back into images using a codec decoder', 'build a python module that encodes images to codes and decodes them back in one round trip', 'review the convert_im_to_codes function to understand how it encodes images using a JAX codec encoder', 'summarize the encode_decode function which performs a full encode-then-decode round trip on input data', 'compute the compression rate of images given their encoded codes and bits per element', 'calculate the bit ratio for a given number of bits per element using log2', 'measure the total size of encoded codes by summing their element counts', 'analyze the compression efficiency by comparing original image size to encoded code size', 'validate compression metrics by computing the ratio of image elements to code elements', 'reshape a single frame numpy array video sample into the correct shape', 'reshape four video frames into a 2x2 grid by concatenating horizontally and vertically', 'reshape multiple video frames by concatenating them all horizontally into one array', 'save a sequence of numpy array frames as an animated GIF file to a given path', 'save video frames as a looping GIF with a 40 millisecond duration per frame']
```

Usage

```
{'load_checkpoint_params_and_state': 'load model checkpoint params and state from a pickle file using load_params_state', 'load_model_config_from_checkpoint': 'load the config key from a model checkpoint file using load_params_state', 'load_augmentation_params_from_checkpoint': 'load augmentation params and state from a checkpoint using load_params_state', 'validate_checkpoint_keys': 'validate a checkpoint pickle file contains all required keys using load_params_state', 'extract_saved_values_from_checkpoint': 'extract all saved values from a checkpoint file using load_params_state'}
```

## File: google-deepmind_compressedvision/utils/data_utils.py

Prompts

```
['load model checkpoint params and state from a pickle file using load_params_state', 'load the config key from a model checkpoint file using load_params_state', 'load augmentation params and state from a checkpoint using load_params_state', 'validate a checkpoint pickle file contains all required keys using load_params_state', 'extract all saved values from a checkpoint file using load_params_state', 'build a python module that converts input images to discrete codes using a codec encoder', 'build a python module that decodes discrete codes back into images using a codec decoder', 'build a python module that encodes images to codes and decodes them back in one round trip', 'review the convert_im_to_codes function to understand how it encodes images using a JAX codec encoder', 'summarize the encode_decode function which performs a full encode-then-decode round trip on input data', 'compute the compression rate of images given their encoded codes and bits per element', 'calculate the bit ratio for a given number of bits per element using log2', 'measure the total size of encoded codes by summing their element counts', 'analyze the compression efficiency by comparing original image size to encoded code size', 'validate compression metrics by computing the ratio of image elements to code elements', 'reshape a single frame numpy array video sample into the correct shape', 'reshape four video frames into a 2x2 grid by concatenating horizontally and vertically', 'reshape multiple video frames by concatenating them all horizontally into one array', 'save a sequence of numpy array frames as an animated GIF file to a given path', 'save video frames as a looping GIF with a 40 millisecond duration per frame']
```

Usage

```
{'convert_images_to_codes': 'build a python module that converts input images to discrete codes using a codec encoder', 'convert_codes_to_images': 'build a python module that decodes discrete codes back into images using a codec decoder', 'encode_and_decode_images': 'build a python module that encodes images to codes and decodes them back in one round trip', 'review_convert_im_to_codes': 'review the convert_im_to_codes function to understand how it encodes images using a JAX codec encoder', 'summarize_encode_decode': 'summarize the encode_decode function which performs a full encode-then-decode round trip on input data'}
```

## File: google-deepmind_compressedvision/utils/metric_utils.py

Prompts

```
['load model checkpoint params and state from a pickle file using load_params_state', 'load the config key from a model checkpoint file using load_params_state', 'load augmentation params and state from a checkpoint using load_params_state', 'validate a checkpoint pickle file contains all required keys using load_params_state', 'extract all saved values from a checkpoint file using load_params_state', 'build a python module that converts input images to discrete codes using a codec encoder', 'build a python module that decodes discrete codes back into images using a codec decoder', 'build a python module that encodes images to codes and decodes them back in one round trip', 'review the convert_im_to_codes function to understand how it encodes images using a JAX codec encoder', 'summarize the encode_decode function which performs a full encode-then-decode round trip on input data', 'compute the compression rate of images given their encoded codes and bits per element', 'calculate the bit ratio for a given number of bits per element using log2', 'measure the total size of encoded codes by summing their element counts', 'analyze the compression efficiency by comparing original image size to encoded code size', 'validate compression metrics by computing the ratio of image elements to code elements', 'reshape a single frame numpy array video sample into the correct shape', 'reshape four video frames into a 2x2 grid by concatenating horizontally and vertically', 'reshape multiple video frames by concatenating them all horizontally into one array', 'save a sequence of numpy array frames as an animated GIF file to a given path', 'save video frames as a looping GIF with a 40 millisecond duration per frame']
```

Usage

```
{'compute_compression_rate': 'compute the compression rate of images given their encoded codes and bits per element', 'calculate_bit_ratio': 'calculate the bit ratio for a given number of bits per element using log2', 'measure_codes_size': 'measure the total size of encoded codes by summing their element counts', 'analyze_compression_efficiency': 'analyze the compression efficiency by comparing original image size to encoded code size', 'validate_compression_metrics': 'validate compression metrics by computing the ratio of image elements to code elements'}
```

## File: google-deepmind_compressedvision/utils/video_utils.py

Prompts

```
['load model checkpoint params and state from a pickle file using load_params_state', 'load the config key from a model checkpoint file using load_params_state', 'load augmentation params and state from a checkpoint using load_params_state', 'validate a checkpoint pickle file contains all required keys using load_params_state', 'extract all saved values from a checkpoint file using load_params_state', 'build a python module that converts input images to discrete codes using a codec encoder', 'build a python module that decodes discrete codes back into images using a codec decoder', 'build a python module that encodes images to codes and decodes them back in one round trip', 'review the convert_im_to_codes function to understand how it encodes images using a JAX codec encoder', 'summarize the encode_decode function which performs a full encode-then-decode round trip on input data', 'compute the compression rate of images given their encoded codes and bits per element', 'calculate the bit ratio for a given number of bits per element using log2', 'measure the total size of encoded codes by summing their element counts', 'analyze the compression efficiency by comparing original image size to encoded code size', 'validate compression metrics by computing the ratio of image elements to code elements', 'reshape a single frame numpy array video sample into the correct shape', 'reshape four video frames into a 2x2 grid by concatenating horizontally and vertically', 'reshape multiple video frames by concatenating them all horizontally into one array', 'save a sequence of numpy array frames as an animated GIF file to a given path', 'save video frames as a looping GIF with a 40 millisecond duration per frame']
```

Usage

```
{'reshape_video_single_frame': 'reshape a single frame numpy array video sample into the correct shape', 'reshape_video_2x2_grid': 'reshape four video frames into a 2x2 grid by concatenating horizontally and vertically', 'reshape_video_horizontal_concat': 'reshape multiple video frames by concatenating them all horizontally into one array', 'save_video_as_gif': 'save a sequence of numpy array frames as an animated GIF file to a given path', 'save_video_duration_loop': 'save video frames as a looping GIF with a 40 millisecond duration per frame'}
```

