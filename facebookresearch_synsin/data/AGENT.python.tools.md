# Agent Python Tools

- repo: facebookresearch/synsin
- repo_uri: https://github.com/facebookresearch/synsin

## File: facebookresearch_synsin/data/create_rgb_dataset.py

Prompts

```
['create a RandomImageGenerator to sample RGB, depth, and semantic images from Habitat simulator scenes', 'build a Habitat simulator config with RGB, depth, and semantic sensors for point navigation tasks', 'sample multiple RGB and depth views with randomized camera positions and rotations from a Habitat environment', 'load and split PointNav datasets across multiple parallel Habitat vector environments for training', 'extract class-level semantic segmentation labels from instance-level Habitat simulator semantic annotations', 'create a HabitatImageGenerator dataset instance with split, opts, vectorize flag, and seed for Habitat simulation', 'use HabitatImageGenerator getitem to fetch a generated image sample from the Habitat environment', 'switch HabitatImageGenerator to training mode with totrain method and set the epoch seed', 'switch HabitatImageGenerator to validation mode with toval method and set the epoch seed', 'restart HabitatImageGenerator episodes for train or val split using the restart method', 'create a KITTIDataLoader instance to load KITTI dataset images with camera poses for training', 'initialize the KITTIDataLoader with opts to parse train IDs and camera pose data from files', 'get a pair of normalized images with relative camera transformation matrices and intrinsics', 'load a KITTI dataset image by ID and return it as an RGB numpy array', 'review the KITTIDataLoader class that loads image pairs with relative pose transformations for view synthesis', 'create a RealEstate10K dataset instance with configurable num_views and random seed for training', 'load a random pair of images and camera matrices from the RealEstate10K dataset', 'switch the RealEstate10K dataset to training split with a new random seed for the epoch', 'switch the RealEstate10K dataset to validation split with a new random seed for the epoch', 'create a RealEstate10KConsecutive dataset that loads consecutive frames from videos instead of random views']
```

Usage

```
{'create_RGB_dataset_generator': 'create a RandomImageGenerator to sample RGB, depth, and semantic images from Habitat simulator scenes', 'build_Habitat_config': 'build a Habitat simulator config with RGB, depth, and semantic sensors for point navigation tasks', 'sample_RGB_depth_views': 'sample multiple RGB and depth views with randomized camera positions and rotations from a Habitat environment', 'load_vector_datasets': 'load and split PointNav datasets across multiple parallel Habitat vector environments for training', 'extract_semantic_annotations': 'extract class-level semantic segmentation labels from instance-level Habitat simulator semantic annotations'}
```

## File: facebookresearch_synsin/data/habitat_data.py

Prompts

```
['create a RandomImageGenerator to sample RGB, depth, and semantic images from Habitat simulator scenes', 'build a Habitat simulator config with RGB, depth, and semantic sensors for point navigation tasks', 'sample multiple RGB and depth views with randomized camera positions and rotations from a Habitat environment', 'load and split PointNav datasets across multiple parallel Habitat vector environments for training', 'extract class-level semantic segmentation labels from instance-level Habitat simulator semantic annotations', 'create a HabitatImageGenerator dataset instance with split, opts, vectorize flag, and seed for Habitat simulation', 'use HabitatImageGenerator getitem to fetch a generated image sample from the Habitat environment', 'switch HabitatImageGenerator to training mode with totrain method and set the epoch seed', 'switch HabitatImageGenerator to validation mode with toval method and set the epoch seed', 'restart HabitatImageGenerator episodes for train or val split using the restart method', 'create a KITTIDataLoader instance to load KITTI dataset images with camera poses for training', 'initialize the KITTIDataLoader with opts to parse train IDs and camera pose data from files', 'get a pair of normalized images with relative camera transformation matrices and intrinsics', 'load a KITTI dataset image by ID and return it as an RGB numpy array', 'review the KITTIDataLoader class that loads image pairs with relative pose transformations for view synthesis', 'create a RealEstate10K dataset instance with configurable num_views and random seed for training', 'load a random pair of images and camera matrices from the RealEstate10K dataset', 'switch the RealEstate10K dataset to training split with a new random seed for the epoch', 'switch the RealEstate10K dataset to validation split with a new random seed for the epoch', 'create a RealEstate10KConsecutive dataset that loads consecutive frames from videos instead of random views']
```

Usage

```
{'create_HabitatImageGenerator': 'create a HabitatImageGenerator dataset instance with split, opts, vectorize flag, and seed for Habitat simulation', 'use_HabitatImageGenerator_getitem': 'use HabitatImageGenerator getitem to fetch a generated image sample from the Habitat environment', 'switch_HabitatImageGenerator_totrain': 'switch HabitatImageGenerator to training mode with totrain method and set the epoch seed', 'switch_HabitatImageGenerator_toval': 'switch HabitatImageGenerator to validation mode with toval method and set the epoch seed', 'restart_HabitatImageGenerator': 'restart HabitatImageGenerator episodes for train or val split using the restart method'}
```

## File: facebookresearch_synsin/data/kitti.py

Prompts

```
['create a RandomImageGenerator to sample RGB, depth, and semantic images from Habitat simulator scenes', 'build a Habitat simulator config with RGB, depth, and semantic sensors for point navigation tasks', 'sample multiple RGB and depth views with randomized camera positions and rotations from a Habitat environment', 'load and split PointNav datasets across multiple parallel Habitat vector environments for training', 'extract class-level semantic segmentation labels from instance-level Habitat simulator semantic annotations', 'create a HabitatImageGenerator dataset instance with split, opts, vectorize flag, and seed for Habitat simulation', 'use HabitatImageGenerator getitem to fetch a generated image sample from the Habitat environment', 'switch HabitatImageGenerator to training mode with totrain method and set the epoch seed', 'switch HabitatImageGenerator to validation mode with toval method and set the epoch seed', 'restart HabitatImageGenerator episodes for train or val split using the restart method', 'create a KITTIDataLoader instance to load KITTI dataset images with camera poses for training', 'initialize the KITTIDataLoader with opts to parse train IDs and camera pose data from files', 'get a pair of normalized images with relative camera transformation matrices and intrinsics', 'load a KITTI dataset image by ID and return it as an RGB numpy array', 'review the KITTIDataLoader class that loads image pairs with relative pose transformations for view synthesis', 'create a RealEstate10K dataset instance with configurable num_views and random seed for training', 'load a random pair of images and camera matrices from the RealEstate10K dataset', 'switch the RealEstate10K dataset to training split with a new random seed for the epoch', 'switch the RealEstate10K dataset to validation split with a new random seed for the epoch', 'create a RealEstate10KConsecutive dataset that loads consecutive frames from videos instead of random views']
```

Usage

```
{'create_KITTIDataLoader': 'create a KITTIDataLoader instance to load KITTI dataset images with camera poses for training', 'initialize_KITTIDataLoader': 'initialize the KITTIDataLoader with opts to parse train IDs and camera pose data from files', 'getitem_KITTIDataLoader': 'get a pair of normalized images with relative camera transformation matrices and intrinsics', 'load_image_KITTIDataLoader': 'load a KITTI dataset image by ID and return it as an RGB numpy array', 'review_KITTIDataLoader': 'review the KITTIDataLoader class that loads image pairs with relative pose transformations for view synthesis'}
```

## File: facebookresearch_synsin/data/realestate10k.py

Prompts

```
['create a RandomImageGenerator to sample RGB, depth, and semantic images from Habitat simulator scenes', 'build a Habitat simulator config with RGB, depth, and semantic sensors for point navigation tasks', 'sample multiple RGB and depth views with randomized camera positions and rotations from a Habitat environment', 'load and split PointNav datasets across multiple parallel Habitat vector environments for training', 'extract class-level semantic segmentation labels from instance-level Habitat simulator semantic annotations', 'create a HabitatImageGenerator dataset instance with split, opts, vectorize flag, and seed for Habitat simulation', 'use HabitatImageGenerator getitem to fetch a generated image sample from the Habitat environment', 'switch HabitatImageGenerator to training mode with totrain method and set the epoch seed', 'switch HabitatImageGenerator to validation mode with toval method and set the epoch seed', 'restart HabitatImageGenerator episodes for train or val split using the restart method', 'create a KITTIDataLoader instance to load KITTI dataset images with camera poses for training', 'initialize the KITTIDataLoader with opts to parse train IDs and camera pose data from files', 'get a pair of normalized images with relative camera transformation matrices and intrinsics', 'load a KITTI dataset image by ID and return it as an RGB numpy array', 'review the KITTIDataLoader class that loads image pairs with relative pose transformations for view synthesis', 'create a RealEstate10K dataset instance with configurable num_views and random seed for training', 'load a random pair of images and camera matrices from the RealEstate10K dataset', 'switch the RealEstate10K dataset to training split with a new random seed for the epoch', 'switch the RealEstate10K dataset to validation split with a new random seed for the epoch', 'create a RealEstate10KConsecutive dataset that loads consecutive frames from videos instead of random views']
```

Usage

```
{'create_RealEstate10K_dataset': 'create a RealEstate10K dataset instance with configurable num_views and random seed for training', 'load_RealEstate10K_item': 'load a random pair of images and camera matrices from the RealEstate10K dataset', 'switch_RealEstate10K_to_train': 'switch the RealEstate10K dataset to training split with a new random seed for the epoch', 'switch_RealEstate10K_to_val': 'switch the RealEstate10K dataset to validation split with a new random seed for the epoch', 'create_RealEstate10KConsecutive_dataset': 'create a RealEstate10KConsecutive dataset that loads consecutive frames from videos instead of random views'}
```

