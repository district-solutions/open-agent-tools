# Agent Python Tools

- repo: facebookresearch/fashionplus
- repo_uri: https://github.com/facebookresearch/fashionplus

## File: facebookresearch_fashionplus/generation/util/image_pool.py

Prompts

```
['create an ImagePool instance with a specified pool size for caching generated images', 'query the ImagePool with a batch of images to get cached or new images back', 'test the ImagePool query method to verify it returns images from the pool or new ones', 'review the ImagePool class and its random 50% swap strategy for discriminator training', 'refactor the ImagePool constructor to initialize pool storage only when pool size is greater than zero', 'convert a PyTorch image tensor to a numpy array with optional normalization and clipping', 'convert a LAB color space tensor to an RGB numpy image using OpenCV color conversion', 'convert a one-hot label tensor into a colorful label map with a specified number of labels', 'convert a one-hot label tensor into a grayscale label map by taking the argmax', 'apply a colormap to a grayscale label tensor and return a colorized PyTorch ByteTensor image']
```

Usage

```
{'create_ImagePool': 'create an ImagePool instance with a specified pool size for caching generated images', 'query_ImagePool': 'query the ImagePool with a batch of images to get cached or new images back', 'test_ImagePool_query': 'test the ImagePool query method to verify it returns images from the pool or new ones', 'review_ImagePool_class': 'review the ImagePool class and its random 50% swap strategy for discriminator training', 'refactor_ImagePool_init': 'refactor the ImagePool constructor to initialize pool storage only when pool size is greater than zero'}
```

## File: facebookresearch_fashionplus/generation/util/util.py

Prompts

```
['create an ImagePool instance with a specified pool size for caching generated images', 'query the ImagePool with a batch of images to get cached or new images back', 'test the ImagePool query method to verify it returns images from the pool or new ones', 'review the ImagePool class and its random 50% swap strategy for discriminator training', 'refactor the ImagePool constructor to initialize pool storage only when pool size is greater than zero', 'convert a PyTorch image tensor to a numpy array with optional normalization and clipping', 'convert a LAB color space tensor to an RGB numpy image using OpenCV color conversion', 'convert a one-hot label tensor into a colorful label map with a specified number of labels', 'convert a one-hot label tensor into a grayscale label map by taking the argmax', 'apply a colormap to a grayscale label tensor and return a colorized PyTorch ByteTensor image']
```

Usage

```
{'convert_tensor_to_image': 'convert a PyTorch image tensor to a numpy array with optional normalization and clipping', 'convert_LAB_tensor_to_RGB_image': 'convert a LAB color space tensor to an RGB numpy image using OpenCV color conversion', 'convert_tensor_to_colored_label_map': 'convert a one-hot label tensor into a colorful label map with a specified number of labels', 'convert_tensor_to_grayscale_label_map': 'convert a one-hot label tensor into a grayscale label map by taking the argmax', 'colorize_grayscale_label_tensor': 'apply a colormap to a grayscale label tensor and return a colorized PyTorch ByteTensor image'}
```

