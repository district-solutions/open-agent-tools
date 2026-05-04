# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/models/segmentors/encoder_decoder_mask2former.py

Prompts

```
['build a Mask2Former encoder-decoder segmentor with backbone, decode head, and optional neck for semantic segmentation', 'train the EncoderDecoderMask2Former model using forward_train with input images and ground truth semantic segmentation masks', 'test the model using slide inference with overlapping crop windows for accurate segmentation of large images', 'test the model using whole image inference to produce segmentation logits for the entire input image at once', 'test the model with test-time augmentations by averaging predictions from multiple augmented versions of the input image']
```

Usage

```
{'build_encoder_decoder_mask2former': 'build a Mask2Former encoder-decoder segmentor with backbone, decode head, and optional neck for semantic segmentation', 'train_encoder_decoder_mask2former': 'train the EncoderDecoderMask2Former model using forward_train with input images and ground truth semantic segmentation masks', 'test_slide_inference': 'test the model using slide inference with overlapping crop windows for accurate segmentation of large images', 'test_whole_inference': 'test the model using whole image inference to produce segmentation logits for the entire input image at once', 'test_aug_test': 'test the model with test-time augmentations by averaging predictions from multiple augmented versions of the input image'}
```

