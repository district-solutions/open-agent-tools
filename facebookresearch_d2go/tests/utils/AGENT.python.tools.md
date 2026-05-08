# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/tests/utils/test_gpu_memory_profiler.py

Prompts

```
['run a Detectron2Go training loop with GPU memory profiler enabled and snapshot logging', 'test the GPU memory profiler silently passes when running on CPU without CUDA', 'test the GPU memory profiler generates snapshot pickle and trace plot files on CUDA', 'build a simple Conv2d-based meta architecture module registered with META_ARCH_REGISTRY for testing', 'create a local dataset with dummy images for use in memory profiler training tests', 'create toy images and a COCO-style annotation JSON file in a given data directory', 'create a dummy input dictionary with a zero image tensor and optional bounding box instances', 'test the VisualizerWrapper class by visualizing train input and asserting pixel values at scaled coordinates', 'test the DataLoaderVisWrapper by iterating once and verifying image data was written to the mock buffer', 'test the DataLoaderVisWrapper with a dict-based DummyMetaArch and verify multiple tagged images in the buffer']
```

Usage

```
{'train_with_memory_profiler': 'run a Detectron2Go training loop with GPU memory profiler enabled and snapshot logging', 'test_gpu_memory_profiler_no_gpu': 'test the GPU memory profiler silently passes when running on CPU without CUDA', 'test_gpu_memory_profiler_with_gpu': 'test the GPU memory profiler generates snapshot pickle and trace plot files on CUDA', 'register_MetaArchForTestSimple': 'build a simple Conv2d-based meta architecture module registered with META_ARCH_REGISTRY for testing', 'create_local_dataset': 'create a local dataset with dummy images for use in memory profiler training tests'}
```

## File: facebookresearch_d2go/tests/utils/test_visualization.py

Prompts

```
['run a Detectron2Go training loop with GPU memory profiler enabled and snapshot logging', 'test the GPU memory profiler silently passes when running on CPU without CUDA', 'test the GPU memory profiler generates snapshot pickle and trace plot files on CUDA', 'build a simple Conv2d-based meta architecture module registered with META_ARCH_REGISTRY for testing', 'create a local dataset with dummy images for use in memory profiler training tests', 'create toy images and a COCO-style annotation JSON file in a given data directory', 'create a dummy input dictionary with a zero image tensor and optional bounding box instances', 'test the VisualizerWrapper class by visualizing train input and asserting pixel values at scaled coordinates', 'test the DataLoaderVisWrapper by iterating once and verifying image data was written to the mock buffer', 'test the DataLoaderVisWrapper with a dict-based DummyMetaArch and verify multiple tagged images in the buffer']
```

Usage

```
{'create_test_images_and_dataset_json': 'create toy images and a COCO-style annotation JSON file in a given data directory', 'create_dummy_input_dict': 'create a dummy input dictionary with a zero image tensor and optional bounding box instances', 'test_visualizer_wrapper': 'test the VisualizerWrapper class by visualizing train input and asserting pixel values at scaled coordinates', 'test_dataloader_visualizer_wrapper': 'test the DataLoaderVisWrapper by iterating once and verifying image data was written to the mock buffer', 'test_dict_based_dataloader_visualizer_wrapper': 'test the DataLoaderVisWrapper with a dict-based DummyMetaArch and verify multiple tagged images in the buffer'}
```

