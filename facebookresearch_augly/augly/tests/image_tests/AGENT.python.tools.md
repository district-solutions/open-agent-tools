# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/tests/image_tests/base_unit_test.py

Prompts

```
['test two PIL images for perceptual hash equality using imagehash phash comparison', 'test two metadata lists for equality with support for excluding keys and relative paths', 'test an image augmentation function by comparing output against a reference image using phash', 'test an image transform class with bounding boxes and metadata against a reference image', 'test loading a reference image from the expected output directory by function name', 'test overlay_random_text_with_background to add random text overlays with configurable placement rotation and gradient backgrounds', 'test the rotate function with expand mode to verify expanded bounding box dimensions and fill color behavior', 'test the collage function to arrange multiple images into a 2x2 grid layout', 'test hstack and vstack functions to horizontally and vertically stack PIL images together', 'test masked_composite to apply a brightness transform to an image using a mask file', 'run the unittest suite for all augly image transform classes', 'test the Compose transform that chains Blur, ColorJitter, and OneOf transforms together', 'test the Rotate transform with expand=True to produce an expanded image canvas', 'test the MaskedComposite transform that applies a brightness function to a masked region', 'test the OverlayRandomTextWithBackground transform with placement, rotation, and gradient box parameters']
```

Usage

```
{'test_are_equal_images': 'test two PIL images for perceptual hash equality using imagehash phash comparison', 'test_are_equal_metadata': 'test two metadata lists for equality with support for excluding keys and relative paths', 'test_BaseImageUnitTest_evaluate_function': 'test an image augmentation function by comparing output against a reference image using phash', 'test_BaseImageUnitTest_evaluate_class': 'test an image transform class with bounding boxes and metadata against a reference image', 'test_BaseImageUnitTest_get_ref_image': 'test loading a reference image from the expected output directory by function name'}
```

## File: facebookresearch_augly/augly/tests/image_tests/functional_unit_test.py

Prompts

```
['test two PIL images for perceptual hash equality using imagehash phash comparison', 'test two metadata lists for equality with support for excluding keys and relative paths', 'test an image augmentation function by comparing output against a reference image using phash', 'test an image transform class with bounding boxes and metadata against a reference image', 'test loading a reference image from the expected output directory by function name', 'test overlay_random_text_with_background to add random text overlays with configurable placement rotation and gradient backgrounds', 'test the rotate function with expand mode to verify expanded bounding box dimensions and fill color behavior', 'test the collage function to arrange multiple images into a 2x2 grid layout', 'test hstack and vstack functions to horizontally and vertically stack PIL images together', 'test masked_composite to apply a brightness transform to an image using a mask file', 'run the unittest suite for all augly image transform classes', 'test the Compose transform that chains Blur, ColorJitter, and OneOf transforms together', 'test the Rotate transform with expand=True to produce an expanded image canvas', 'test the MaskedComposite transform that applies a brightness function to a masked region', 'test the OverlayRandomTextWithBackground transform with placement, rotation, and gradient box parameters']
```

Usage

```
{'test_overlay_random_text_with_background': 'test overlay_random_text_with_background to add random text overlays with configurable placement rotation and gradient backgrounds', 'test_rotate_expand': 'test the rotate function with expand mode to verify expanded bounding box dimensions and fill color behavior', 'test_collage': 'test the collage function to arrange multiple images into a 2x2 grid layout', 'test_hstack_vstack': 'test hstack and vstack functions to horizontally and vertically stack PIL images together', 'test_masked_composite': 'test masked_composite to apply a brightness transform to an image using a mask file'}
```

## File: facebookresearch_augly/augly/tests/image_tests/transforms_unit_test.py

Prompts

```
['test two PIL images for perceptual hash equality using imagehash phash comparison', 'test two metadata lists for equality with support for excluding keys and relative paths', 'test an image augmentation function by comparing output against a reference image using phash', 'test an image transform class with bounding boxes and metadata against a reference image', 'test loading a reference image from the expected output directory by function name', 'test overlay_random_text_with_background to add random text overlays with configurable placement rotation and gradient backgrounds', 'test the rotate function with expand mode to verify expanded bounding box dimensions and fill color behavior', 'test the collage function to arrange multiple images into a 2x2 grid layout', 'test hstack and vstack functions to horizontally and vertically stack PIL images together', 'test masked_composite to apply a brightness transform to an image using a mask file', 'run the unittest suite for all augly image transform classes', 'test the Compose transform that chains Blur, ColorJitter, and OneOf transforms together', 'test the Rotate transform with expand=True to produce an expanded image canvas', 'test the MaskedComposite transform that applies a brightness function to a masked region', 'test the OverlayRandomTextWithBackground transform with placement, rotation, and gradient box parameters']
```

Usage

```
{'run_transforms_unit_tests': 'run the unittest suite for all augly image transform classes', 'test_Compose_transform': 'test the Compose transform that chains Blur, ColorJitter, and OneOf transforms together', 'test_Rotate_expand': 'test the Rotate transform with expand=True to produce an expanded image canvas', 'test_MaskedComposite_transform': 'test the MaskedComposite transform that applies a brightness function to a masked region', 'test_OverlayRandomTextWithBackground': 'test the OverlayRandomTextWithBackground transform with placement, rotation, and gradient box parameters'}
```

