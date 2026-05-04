# Agent Python Tools

- repo: facebookresearch/dynamicstereo
- repo_uri: https://github.com/facebookresearch/dynamic_stereo

## File: facebookresearch_dynamicstereo/datasets/augmentor.py

Prompts

```
['create an AdjustGamma callable that applies random gamma and gain to a PIL image sample', 'create a SequenceDispFlowAugmentor with crop_size and optional scale, flip, saturation, and gamma params', 'run color_transform on a sequence of stereo image pairs with symmetric or asymmetric photometric augmentation', 'run eraser_transform on a sequence of stereo image pairs to randomly occlude regions with mean color', 'run spatial_transform on image and disparity pairs to apply random scaling, stretching, and cropping', 'create a DynamicReplicaDataset instance to load stereo image sequences with depth and mask annotations from a data root', 'create a SequenceSceneFlowDataset to load FlyingThings3D, Monkaa, or Driving stereo image and disparity pairs for training', 'create a SequenceSintelStereo dataset to load Sintel stereo training sequences with sparse disparity ground truth', 'fetch a PyTorch DataLoader combining SceneFlow and DynamicReplica datasets with configurable augmentation and batch size', 'load a 16-bit big-endian PNG depth map and convert it to a float32 numpy array using StereoSequenceDataset', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM file and return the image data as a numpy array with proper endianness', 'read a Sintel Stereo disparity PNG file and return disparity values with a validity mask', 'read a Middlebury ground truth disparity PFM file and return disparity with non-occlusion mask', 'read image, flow, or PFM files by extension and return the appropriate numpy array or PIL Image']
```

Usage

```
{'create_adjustgamma_augmentation': 'create an AdjustGamma callable that applies random gamma and gain to a PIL image sample', 'create_sequence_augmentor': 'create a SequenceDispFlowAugmentor with crop_size and optional scale, flip, saturation, and gamma params', 'run_color_transform': 'run color_transform on a sequence of stereo image pairs with symmetric or asymmetric photometric augmentation', 'run_eraser_transform': 'run eraser_transform on a sequence of stereo image pairs to randomly occlude regions with mean color', 'run_spatial_transform': 'run spatial_transform on image and disparity pairs to apply random scaling, stretching, and cropping'}
```

## File: facebookresearch_dynamicstereo/datasets/dynamic_stereo_datasets.py

Prompts

```
['create an AdjustGamma callable that applies random gamma and gain to a PIL image sample', 'create a SequenceDispFlowAugmentor with crop_size and optional scale, flip, saturation, and gamma params', 'run color_transform on a sequence of stereo image pairs with symmetric or asymmetric photometric augmentation', 'run eraser_transform on a sequence of stereo image pairs to randomly occlude regions with mean color', 'run spatial_transform on image and disparity pairs to apply random scaling, stretching, and cropping', 'create a DynamicReplicaDataset instance to load stereo image sequences with depth and mask annotations from a data root', 'create a SequenceSceneFlowDataset to load FlyingThings3D, Monkaa, or Driving stereo image and disparity pairs for training', 'create a SequenceSintelStereo dataset to load Sintel stereo training sequences with sparse disparity ground truth', 'fetch a PyTorch DataLoader combining SceneFlow and DynamicReplica datasets with configurable augmentation and batch size', 'load a 16-bit big-endian PNG depth map and convert it to a float32 numpy array using StereoSequenceDataset', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM file and return the image data as a numpy array with proper endianness', 'read a Sintel Stereo disparity PNG file and return disparity values with a validity mask', 'read a Middlebury ground truth disparity PFM file and return disparity with non-occlusion mask', 'read image, flow, or PFM files by extension and return the appropriate numpy array or PIL Image']
```

Usage

```
{'create_dynamic_replica_dataset': 'create a DynamicReplicaDataset instance to load stereo image sequences with depth and mask annotations from a data root', 'create_sceneflow_dataset': 'create a SequenceSceneFlowDataset to load FlyingThings3D, Monkaa, or Driving stereo image and disparity pairs for training', 'create_sintel_stereo_dataset': 'create a SequenceSintelStereo dataset to load Sintel stereo training sequences with sparse disparity ground truth', 'fetch_dataloader': 'fetch a PyTorch DataLoader combining SceneFlow and DynamicReplica datasets with configurable augmentation and batch size', 'load_16bit_depth_png': 'load a 16-bit big-endian PNG depth map and convert it to a float32 numpy array using StereoSequenceDataset'}
```

## File: facebookresearch_dynamicstereo/datasets/frame_utils.py

Prompts

```
['create an AdjustGamma callable that applies random gamma and gain to a PIL image sample', 'create a SequenceDispFlowAugmentor with crop_size and optional scale, flip, saturation, and gamma params', 'run color_transform on a sequence of stereo image pairs with symmetric or asymmetric photometric augmentation', 'run eraser_transform on a sequence of stereo image pairs to randomly occlude regions with mean color', 'run spatial_transform on image and disparity pairs to apply random scaling, stretching, and cropping', 'create a DynamicReplicaDataset instance to load stereo image sequences with depth and mask annotations from a data root', 'create a SequenceSceneFlowDataset to load FlyingThings3D, Monkaa, or Driving stereo image and disparity pairs for training', 'create a SequenceSintelStereo dataset to load Sintel stereo training sequences with sparse disparity ground truth', 'fetch a PyTorch DataLoader combining SceneFlow and DynamicReplica datasets with configurable augmentation and batch size', 'load a 16-bit big-endian PNG depth map and convert it to a float32 numpy array using StereoSequenceDataset', 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read a PFM file and return the image data as a numpy array with proper endianness', 'read a Sintel Stereo disparity PNG file and return disparity values with a validity mask', 'read a Middlebury ground truth disparity PFM file and return disparity with non-occlusion mask', 'read image, flow, or PFM files by extension and return the appropriate numpy array or PIL Image']
```

Usage

```
{'read_flow_middlebury': 'read a .flo optical flow file in Middlebury format and return a numpy array', 'read_pfm_file': 'read a PFM file and return the image data as a numpy array with proper endianness', 'read_disparity_sintel_stereo': 'read a Sintel Stereo disparity PNG file and return disparity values with a validity mask', 'read_disparity_middlebury': 'read a Middlebury ground truth disparity PFM file and return disparity with non-occlusion mask', 'read_generic_file': 'read image, flow, or PFM files by extension and return the appropriate numpy array or PIL Image'}
```

