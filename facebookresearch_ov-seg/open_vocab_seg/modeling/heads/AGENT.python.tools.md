# Agent Python Tools

- repo: facebookresearch/ov-seg
- repo_uri: https://github.com/facebookresearch/ov-seg

## File: facebookresearch_ov-seg/open_vocab_seg/modeling/heads/mask_former_head.py

Prompts

```
['build a MaskFormerHead module for semantic segmentation using a pixel decoder and transformer predictor', 'create a MaskFormerHead instance from a Detectron2 config object and input feature shapes', 'run the MaskFormerHead forward pass on image features to produce mask predictions', 'review the MaskFormerHead layers method that routes features through the pixel decoder and transformer predictor', 'refactor the MaskFormerHead _load_from_state_dict method to handle weight format version migration', 'build an OpenVocabMaskFormerHead instance with a pixel decoder and transformer predictor for semantic segmentation', 'create an OpenVocabMaskFormerHead from a detectron2 config object and input feature shape dictionary', 'run a forward pass through the OpenVocabMaskFormerHead layers to get mask predictions from features', 'freeze pretrained parameters in the OpenVocabMaskFormerHead pixel decoder while keeping the predictor trainable', 'load a state dict into OpenVocabMaskFormerHead with automatic key remigration from version 1 to version 2 format', 'build a pixel decoder model from config and input shape using build_pixel_decoder', 'create a BasePixelDecoder with FPN-style lateral and output convolutions for mask feature extraction', 'create a TransformerEncoderPixelDecoder that adds transformer encoder layers to the FPN feature pyramid', 'review the TransformerEncoderOnly class which wraps TransformerEncoder with position embedding and Xavier initialization', 'refactor the forward_features method to extract mask features and transformer encoder features from input feature maps']
```

Usage

```
{'build_maskformer_head': 'build a MaskFormerHead module for semantic segmentation using a pixel decoder and transformer predictor', 'create_maskformer_head_from_config': 'create a MaskFormerHead instance from a Detectron2 config object and input feature shapes', 'run_maskformer_forward': 'run the MaskFormerHead forward pass on image features to produce mask predictions', 'review_maskformer_head_layers': 'review the MaskFormerHead layers method that routes features through the pixel decoder and transformer predictor', 'refactor_maskformer_state_dict_loading': 'refactor the MaskFormerHead _load_from_state_dict method to handle weight format version migration'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/modeling/heads/open_vocab_mask_former_head.py

Prompts

```
['build a MaskFormerHead module for semantic segmentation using a pixel decoder and transformer predictor', 'create a MaskFormerHead instance from a Detectron2 config object and input feature shapes', 'run the MaskFormerHead forward pass on image features to produce mask predictions', 'review the MaskFormerHead layers method that routes features through the pixel decoder and transformer predictor', 'refactor the MaskFormerHead _load_from_state_dict method to handle weight format version migration', 'build an OpenVocabMaskFormerHead instance with a pixel decoder and transformer predictor for semantic segmentation', 'create an OpenVocabMaskFormerHead from a detectron2 config object and input feature shape dictionary', 'run a forward pass through the OpenVocabMaskFormerHead layers to get mask predictions from features', 'freeze pretrained parameters in the OpenVocabMaskFormerHead pixel decoder while keeping the predictor trainable', 'load a state dict into OpenVocabMaskFormerHead with automatic key remigration from version 1 to version 2 format', 'build a pixel decoder model from config and input shape using build_pixel_decoder', 'create a BasePixelDecoder with FPN-style lateral and output convolutions for mask feature extraction', 'create a TransformerEncoderPixelDecoder that adds transformer encoder layers to the FPN feature pyramid', 'review the TransformerEncoderOnly class which wraps TransformerEncoder with position embedding and Xavier initialization', 'refactor the forward_features method to extract mask features and transformer encoder features from input feature maps']
```

Usage

```
{'build_open_vocab_mask_former_head': 'build an OpenVocabMaskFormerHead instance with a pixel decoder and transformer predictor for semantic segmentation', 'create_from_config': 'create an OpenVocabMaskFormerHead from a detectron2 config object and input feature shape dictionary', 'run_forward_pass': 'run a forward pass through the OpenVocabMaskFormerHead layers to get mask predictions from features', 'freeze_pretrained_modules': 'freeze pretrained parameters in the OpenVocabMaskFormerHead pixel decoder while keeping the predictor trainable', 'load_state_dict_migration': 'load a state dict into OpenVocabMaskFormerHead with automatic key remigration from version 1 to version 2 format'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/modeling/heads/pixel_decoder.py

Prompts

```
['build a MaskFormerHead module for semantic segmentation using a pixel decoder and transformer predictor', 'create a MaskFormerHead instance from a Detectron2 config object and input feature shapes', 'run the MaskFormerHead forward pass on image features to produce mask predictions', 'review the MaskFormerHead layers method that routes features through the pixel decoder and transformer predictor', 'refactor the MaskFormerHead _load_from_state_dict method to handle weight format version migration', 'build an OpenVocabMaskFormerHead instance with a pixel decoder and transformer predictor for semantic segmentation', 'create an OpenVocabMaskFormerHead from a detectron2 config object and input feature shape dictionary', 'run a forward pass through the OpenVocabMaskFormerHead layers to get mask predictions from features', 'freeze pretrained parameters in the OpenVocabMaskFormerHead pixel decoder while keeping the predictor trainable', 'load a state dict into OpenVocabMaskFormerHead with automatic key remigration from version 1 to version 2 format', 'build a pixel decoder model from config and input shape using build_pixel_decoder', 'create a BasePixelDecoder with FPN-style lateral and output convolutions for mask feature extraction', 'create a TransformerEncoderPixelDecoder that adds transformer encoder layers to the FPN feature pyramid', 'review the TransformerEncoderOnly class which wraps TransformerEncoder with position embedding and Xavier initialization', 'refactor the forward_features method to extract mask features and transformer encoder features from input feature maps']
```

Usage

```
{'build_pixel_decoder': 'build a pixel decoder model from config and input shape using build_pixel_decoder', 'create_base_pixel_decoder': 'create a BasePixelDecoder with FPN-style lateral and output convolutions for mask feature extraction', 'create_transformer_encoder_pixel_decoder': 'create a TransformerEncoderPixelDecoder that adds transformer encoder layers to the FPN feature pyramid', 'review_transformer_encoder_only': 'review the TransformerEncoderOnly class which wraps TransformerEncoder with position embedding and Xavier initialization', 'refactor_forward_features': 'refactor the forward_features method to extract mask features and transformer encoder features from input feature maps'}
```

