# Agent Python Tools

- repo: facebookresearch/synsin
- repo_uri: https://github.com/facebookresearch/synsin

## File: facebookresearch_synsin/models/base_model.py

Prompts

```
['create a BaseModel instance with discriminator losses and Adam optimizers for GAN training', 'create a BaseModel instance without discriminator for standard supervised training with Adam optimizer', 'run init_weights on BaseModel to initialize Conv and Linear layers with kaiming or xavier normal', 'run the BaseModel call method with a dataloader to perform generator and discriminator training steps', 'run the BaseModel call method in validation mode to get losses and output images without training', 'build a depth-based view synthesis model using the Model class with camera intrinsics and depth images', 'create a DepthManipulator projector instance to project depth images for view transformation', 'run the forward pass of the depth model with a batch containing images, depths, and camera parameters', 'transform an input image to a new view using depth projection and camera rotation translation parameters', 'review the Model class for depth-based view synthesis evaluation and brute force point splatting', 'build a ViewAppearanceFlow model with an encoder, decoder, and angle transformer for view synthesis', 'build a Tatarchenko model with an encoder, decoder, and angle transformer for direct image synthesis', 'run the ViewAppearanceFlow forward pass on a batch with images and camera poses to get loss and predictions', 'run the ViewAppearanceFlow forward_angle method to synthesize images for multiple camera poses', 'run the Tatarchenko forward pass on a batch with images and camera poses to get loss and predictions', 'build a ZbufferModelPts instance with an opt config to synthesize novel views from input images and camera parameters', 'run the forward pass of ZbufferModelPts with a batch dict containing images and cameras to get synthesized output and loss', 'run forward_angle on ZbufferModelPts with a batch and list of RT matrices to generate images from multiple viewpoints', 'review the ZbufferModelPts pts_regressor Unet that regresses 3D depth points from input images using sigmoid normalization', 'review the ZbufferModelPts pts_transformer PtsManipulator that transforms 3D points between camera coordinate systems for view synthesis']
```

Usage

```
{'create_BaseModel_with_discriminator': 'create a BaseModel instance with discriminator losses and Adam optimizers for GAN training', 'create_BaseModel_without_discriminator': 'create a BaseModel instance without discriminator for standard supervised training with Adam optimizer', 'run_BaseModel_init_weights': 'run init_weights on BaseModel to initialize Conv and Linear layers with kaiming or xavier normal', 'run_BaseModel_call_train': 'run the BaseModel call method with a dataloader to perform generator and discriminator training steps', 'run_BaseModel_call_validate': 'run the BaseModel call method in validation mode to get losses and output images without training'}
```

## File: facebookresearch_synsin/models/depth_model.py

Prompts

```
['create a BaseModel instance with discriminator losses and Adam optimizers for GAN training', 'create a BaseModel instance without discriminator for standard supervised training with Adam optimizer', 'run init_weights on BaseModel to initialize Conv and Linear layers with kaiming or xavier normal', 'run the BaseModel call method with a dataloader to perform generator and discriminator training steps', 'run the BaseModel call method in validation mode to get losses and output images without training', 'build a depth-based view synthesis model using the Model class with camera intrinsics and depth images', 'create a DepthManipulator projector instance to project depth images for view transformation', 'run the forward pass of the depth model with a batch containing images, depths, and camera parameters', 'transform an input image to a new view using depth projection and camera rotation translation parameters', 'review the Model class for depth-based view synthesis evaluation and brute force point splatting', 'build a ViewAppearanceFlow model with an encoder, decoder, and angle transformer for view synthesis', 'build a Tatarchenko model with an encoder, decoder, and angle transformer for direct image synthesis', 'run the ViewAppearanceFlow forward pass on a batch with images and camera poses to get loss and predictions', 'run the ViewAppearanceFlow forward_angle method to synthesize images for multiple camera poses', 'run the Tatarchenko forward pass on a batch with images and camera poses to get loss and predictions', 'build a ZbufferModelPts instance with an opt config to synthesize novel views from input images and camera parameters', 'run the forward pass of ZbufferModelPts with a batch dict containing images and cameras to get synthesized output and loss', 'run forward_angle on ZbufferModelPts with a batch and list of RT matrices to generate images from multiple viewpoints', 'review the ZbufferModelPts pts_regressor Unet that regresses 3D depth points from input images using sigmoid normalization', 'review the ZbufferModelPts pts_transformer PtsManipulator that transforms 3D points between camera coordinate systems for view synthesis']
```

Usage

```
{'build_depth_model': 'build a depth-based view synthesis model using the Model class with camera intrinsics and depth images', 'create_depth_manipulator_projector': 'create a DepthManipulator projector instance to project depth images for view transformation', 'run_forward_pass': 'run the forward pass of the depth model with a batch containing images, depths, and camera parameters', 'transform_perfimage_view': 'transform an input image to a new view using depth projection and camera rotation translation parameters', 'review_Model_class': 'review the Model class for depth-based view synthesis evaluation and brute force point splatting'}
```

## File: facebookresearch_synsin/models/encoderdecoder.py

Prompts

```
['create a BaseModel instance with discriminator losses and Adam optimizers for GAN training', 'create a BaseModel instance without discriminator for standard supervised training with Adam optimizer', 'run init_weights on BaseModel to initialize Conv and Linear layers with kaiming or xavier normal', 'run the BaseModel call method with a dataloader to perform generator and discriminator training steps', 'run the BaseModel call method in validation mode to get losses and output images without training', 'build a depth-based view synthesis model using the Model class with camera intrinsics and depth images', 'create a DepthManipulator projector instance to project depth images for view transformation', 'run the forward pass of the depth model with a batch containing images, depths, and camera parameters', 'transform an input image to a new view using depth projection and camera rotation translation parameters', 'review the Model class for depth-based view synthesis evaluation and brute force point splatting', 'build a ViewAppearanceFlow model with an encoder, decoder, and angle transformer for view synthesis', 'build a Tatarchenko model with an encoder, decoder, and angle transformer for direct image synthesis', 'run the ViewAppearanceFlow forward pass on a batch with images and camera poses to get loss and predictions', 'run the ViewAppearanceFlow forward_angle method to synthesize images for multiple camera poses', 'run the Tatarchenko forward pass on a batch with images and camera poses to get loss and predictions', 'build a ZbufferModelPts instance with an opt config to synthesize novel views from input images and camera parameters', 'run the forward pass of ZbufferModelPts with a batch dict containing images and cameras to get synthesized output and loss', 'run forward_angle on ZbufferModelPts with a batch and list of RT matrices to generate images from multiple viewpoints', 'review the ZbufferModelPts pts_regressor Unet that regresses 3D depth points from input images using sigmoid normalization', 'review the ZbufferModelPts pts_transformer PtsManipulator that transforms 3D points between camera coordinate systems for view synthesis']
```

Usage

```
{'build_ViewAppearanceFlow_model': 'build a ViewAppearanceFlow model with an encoder, decoder, and angle transformer for view synthesis', 'build_Tatarchenko_model': 'build a Tatarchenko model with an encoder, decoder, and angle transformer for direct image synthesis', 'run_ViewAppearanceFlow_forward': 'run the ViewAppearanceFlow forward pass on a batch with images and camera poses to get loss and predictions', 'run_ViewAppearanceFlow_forward_angle': 'run the ViewAppearanceFlow forward_angle method to synthesize images for multiple camera poses', 'run_Tatarchenko_forward': 'run the Tatarchenko forward pass on a batch with images and camera poses to get loss and predictions'}
```

## File: facebookresearch_synsin/models/z_buffermodel.py

Prompts

```
['create a BaseModel instance with discriminator losses and Adam optimizers for GAN training', 'create a BaseModel instance without discriminator for standard supervised training with Adam optimizer', 'run init_weights on BaseModel to initialize Conv and Linear layers with kaiming or xavier normal', 'run the BaseModel call method with a dataloader to perform generator and discriminator training steps', 'run the BaseModel call method in validation mode to get losses and output images without training', 'build a depth-based view synthesis model using the Model class with camera intrinsics and depth images', 'create a DepthManipulator projector instance to project depth images for view transformation', 'run the forward pass of the depth model with a batch containing images, depths, and camera parameters', 'transform an input image to a new view using depth projection and camera rotation translation parameters', 'review the Model class for depth-based view synthesis evaluation and brute force point splatting', 'build a ViewAppearanceFlow model with an encoder, decoder, and angle transformer for view synthesis', 'build a Tatarchenko model with an encoder, decoder, and angle transformer for direct image synthesis', 'run the ViewAppearanceFlow forward pass on a batch with images and camera poses to get loss and predictions', 'run the ViewAppearanceFlow forward_angle method to synthesize images for multiple camera poses', 'run the Tatarchenko forward pass on a batch with images and camera poses to get loss and predictions', 'build a ZbufferModelPts instance with an opt config to synthesize novel views from input images and camera parameters', 'run the forward pass of ZbufferModelPts with a batch dict containing images and cameras to get synthesized output and loss', 'run forward_angle on ZbufferModelPts with a batch and list of RT matrices to generate images from multiple viewpoints', 'review the ZbufferModelPts pts_regressor Unet that regresses 3D depth points from input images using sigmoid normalization', 'review the ZbufferModelPts pts_transformer PtsManipulator that transforms 3D points between camera coordinate systems for view synthesis']
```

Usage

```
{'build_ZbufferModelPts': 'build a ZbufferModelPts instance with an opt config to synthesize novel views from input images and camera parameters', 'run_forward_ZbufferModelPts': 'run the forward pass of ZbufferModelPts with a batch dict containing images and cameras to get synthesized output and loss', 'run_forward_angle_ZbufferModelPts': 'run forward_angle on ZbufferModelPts with a batch and list of RT matrices to generate images from multiple viewpoints', 'review_ZbufferModelPts_pts_regressor': 'review the ZbufferModelPts pts_regressor Unet that regresses 3D depth points from input images using sigmoid normalization', 'review_ZbufferModelPts_pts_transformer': 'review the ZbufferModelPts pts_transformer PtsManipulator that transforms 3D points between camera coordinate systems for view synthesis'}
```

