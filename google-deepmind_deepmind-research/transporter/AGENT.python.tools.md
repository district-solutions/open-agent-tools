# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/transporter/transporter.py

Prompts

```
['build a Transporter module with an Encoder, KeyPointer, and Decoder to reconstruct image_b from image_a', 'create an Encoder module with configurable filters, kernel sizes, and normalization to extract image features', 'create a Decoder module with configurable initial filters and output size to reconstruct images from features', 'create a KeyPointer module with a keypoint encoder to extract Gaussian keypoint heatmaps from images', 'compute the L1 or L2 reconstruction loss between a target image and a predicted image', 'test the Transporter model output shape with batch, layer, and instance normalization types', 'test that mismatched encoder spatial dimensions raise a ValueError as expected', 'test the Encoder produces feature maps with correct spatial and channel dimensions', 'test the KeyPointer outputs centers and heatmaps with correct tensor shapes', 'test the Decoder reconstructs images from Encoder features with matching output shape']
```

Usage

```
{'build_transporter_model': 'build a Transporter module with an Encoder, KeyPointer, and Decoder to reconstruct image_b from image_a', 'create_encoder_module': 'create an Encoder module with configurable filters, kernel sizes, and normalization to extract image features', 'create_decoder_module': 'create a Decoder module with configurable initial filters and output size to reconstruct images from features', 'create_keypointer_module': 'create a KeyPointer module with a keypoint encoder to extract Gaussian keypoint heatmaps from images', 'compute_reconstruction_loss': 'compute the L1 or L2 reconstruction loss between a target image and a predicted image'}
```

## File: google-deepmind_deepmind-research/transporter/transporter_test.py

Prompts

```
['build a Transporter module with an Encoder, KeyPointer, and Decoder to reconstruct image_b from image_a', 'create an Encoder module with configurable filters, kernel sizes, and normalization to extract image features', 'create a Decoder module with configurable initial filters and output size to reconstruct images from features', 'create a KeyPointer module with a keypoint encoder to extract Gaussian keypoint heatmaps from images', 'compute the L1 or L2 reconstruction loss between a target image and a predicted image', 'test the Transporter model output shape with batch, layer, and instance normalization types', 'test that mismatched encoder spatial dimensions raise a ValueError as expected', 'test the Encoder produces feature maps with correct spatial and channel dimensions', 'test the KeyPointer outputs centers and heatmaps with correct tensor shapes', 'test the Decoder reconstructs images from Encoder features with matching output shape']
```

Usage

```
{'test_transporter_output_shape': 'test the Transporter model output shape with batch, layer, and instance normalization types', 'test_transporter_incorrect_encoder_shapes': 'test that mismatched encoder spatial dimensions raise a ValueError as expected', 'test_encoder_output_shape': 'test the Encoder produces feature maps with correct spatial and channel dimensions', 'test_keypointer_output_shape': 'test the KeyPointer outputs centers and heatmaps with correct tensor shapes', 'test_decoder_encoder_roundtrip': 'test the Decoder reconstructs images from Encoder features with matching output shape'}
```

