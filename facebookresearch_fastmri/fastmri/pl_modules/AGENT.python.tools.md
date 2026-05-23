# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/fastmri/pl_modules/data_module.py

Prompts

```
['create a FastMriDataModule instance with data path, challenge type, and train val test transforms', 'build a data loader for a specific partition using _create_data_loader with transform and sample rate', 'test the FastMriDataModule by calling train_dataloader, val_dataloader, and test_dataloader methods', 'review the worker_init_fn function that handles random seeding for mask_func across DDP workers', 'summarize the add_data_specific_args static method that defines CLI arguments for the data module', 'build a PyTorch Lightning MRI reconstruction model by subclassing MriModule and implementing training_step', 'create a DistributedMetricSum metric to aggregate tensor values across distributed processes via sum reduction', 'test the validation_step_end method to verify it logs reconstruction images and computes MSE SSIM metrics', 'review the validation_epoch_end method to understand how NMSE SSIM and PSNR metrics are aggregated across files', 'run the test_epoch_end method to aggregate and save MRI reconstructions to a directory using fastmri', 'build a U-Net training module for accelerated MRI reconstruction with configurable channels and pooling layers', 'run a training step that computes L1 loss between U-Net output and target MRI data', 'run a validation step that returns unnormalized output, target, and L1 loss for MRI batches', 'run a test step that produces numpy output arrays from U-Net forward pass on MRI data', 'configure RMSprop optimizer with StepLR scheduler for U-Net model training', 'build a VarNetModule with custom cascades, pools, and channels for MRI reconstruction', 'run the VarNetModule forward pass on masked k-space data with a mask and low frequency count', 'train the VarNetModule using training_step with SSIM loss on batched MRI k-space data', 'validate the VarNetModule using validation_step to compute val_loss and crop output to target size', 'test the VarNetModule using test_step to produce cropped numpy output arrays for MRI slices']
```

Usage

```
{'create_FastMriDataModule': 'create a FastMriDataModule instance with data path, challenge type, and train val test transforms', 'build_data_loader': 'build a data loader for a specific partition using _create_data_loader with transform and sample rate', 'test_FastMriDataModule_dataloader': 'test the FastMriDataModule by calling train_dataloader, val_dataloader, and test_dataloader methods', 'review_worker_init_fn': 'review the worker_init_fn function that handles random seeding for mask_func across DDP workers', 'summarize_add_data_specific_args': 'summarize the add_data_specific_args static method that defines CLI arguments for the data module'}
```

## File: facebookresearch_fastmri/fastmri/pl_modules/mri_module.py

Prompts

```
['create a FastMriDataModule instance with data path, challenge type, and train val test transforms', 'build a data loader for a specific partition using _create_data_loader with transform and sample rate', 'test the FastMriDataModule by calling train_dataloader, val_dataloader, and test_dataloader methods', 'review the worker_init_fn function that handles random seeding for mask_func across DDP workers', 'summarize the add_data_specific_args static method that defines CLI arguments for the data module', 'build a PyTorch Lightning MRI reconstruction model by subclassing MriModule and implementing training_step', 'create a DistributedMetricSum metric to aggregate tensor values across distributed processes via sum reduction', 'test the validation_step_end method to verify it logs reconstruction images and computes MSE SSIM metrics', 'review the validation_epoch_end method to understand how NMSE SSIM and PSNR metrics are aggregated across files', 'run the test_epoch_end method to aggregate and save MRI reconstructions to a directory using fastmri', 'build a U-Net training module for accelerated MRI reconstruction with configurable channels and pooling layers', 'run a training step that computes L1 loss between U-Net output and target MRI data', 'run a validation step that returns unnormalized output, target, and L1 loss for MRI batches', 'run a test step that produces numpy output arrays from U-Net forward pass on MRI data', 'configure RMSprop optimizer with StepLR scheduler for U-Net model training', 'build a VarNetModule with custom cascades, pools, and channels for MRI reconstruction', 'run the VarNetModule forward pass on masked k-space data with a mask and low frequency count', 'train the VarNetModule using training_step with SSIM loss on batched MRI k-space data', 'validate the VarNetModule using validation_step to compute val_loss and crop output to target size', 'test the VarNetModule using test_step to produce cropped numpy output arrays for MRI slices']
```

Usage

```
{'build_MriModule_subclass': 'build a PyTorch Lightning MRI reconstruction model by subclassing MriModule and implementing training_step', 'create_DistributedMetricSum': 'create a DistributedMetricSum metric to aggregate tensor values across distributed processes via sum reduction', 'test_validation_step_end': 'test the validation_step_end method to verify it logs reconstruction images and computes MSE SSIM metrics', 'review_validation_epoch_end': 'review the validation_epoch_end method to understand how NMSE SSIM and PSNR metrics are aggregated across files', 'run_test_epoch_end': 'run the test_epoch_end method to aggregate and save MRI reconstructions to a directory using fastmri'}
```

## File: facebookresearch_fastmri/fastmri/pl_modules/unet_module.py

Prompts

```
['create a FastMriDataModule instance with data path, challenge type, and train val test transforms', 'build a data loader for a specific partition using _create_data_loader with transform and sample rate', 'test the FastMriDataModule by calling train_dataloader, val_dataloader, and test_dataloader methods', 'review the worker_init_fn function that handles random seeding for mask_func across DDP workers', 'summarize the add_data_specific_args static method that defines CLI arguments for the data module', 'build a PyTorch Lightning MRI reconstruction model by subclassing MriModule and implementing training_step', 'create a DistributedMetricSum metric to aggregate tensor values across distributed processes via sum reduction', 'test the validation_step_end method to verify it logs reconstruction images and computes MSE SSIM metrics', 'review the validation_epoch_end method to understand how NMSE SSIM and PSNR metrics are aggregated across files', 'run the test_epoch_end method to aggregate and save MRI reconstructions to a directory using fastmri', 'build a U-Net training module for accelerated MRI reconstruction with configurable channels and pooling layers', 'run a training step that computes L1 loss between U-Net output and target MRI data', 'run a validation step that returns unnormalized output, target, and L1 loss for MRI batches', 'run a test step that produces numpy output arrays from U-Net forward pass on MRI data', 'configure RMSprop optimizer with StepLR scheduler for U-Net model training', 'build a VarNetModule with custom cascades, pools, and channels for MRI reconstruction', 'run the VarNetModule forward pass on masked k-space data with a mask and low frequency count', 'train the VarNetModule using training_step with SSIM loss on batched MRI k-space data', 'validate the VarNetModule using validation_step to compute val_loss and crop output to target size', 'test the VarNetModule using test_step to produce cropped numpy output arrays for MRI slices']
```

Usage

```
{'build_unet_module': 'build a U-Net training module for accelerated MRI reconstruction with configurable channels and pooling layers', 'run_training_step': 'run a training step that computes L1 loss between U-Net output and target MRI data', 'run_validation_step': 'run a validation step that returns unnormalized output, target, and L1 loss for MRI batches', 'run_test_step': 'run a test step that produces numpy output arrays from U-Net forward pass on MRI data', 'configure_optimizers': 'configure RMSprop optimizer with StepLR scheduler for U-Net model training'}
```

## File: facebookresearch_fastmri/fastmri/pl_modules/varnet_module.py

Prompts

```
['create a FastMriDataModule instance with data path, challenge type, and train val test transforms', 'build a data loader for a specific partition using _create_data_loader with transform and sample rate', 'test the FastMriDataModule by calling train_dataloader, val_dataloader, and test_dataloader methods', 'review the worker_init_fn function that handles random seeding for mask_func across DDP workers', 'summarize the add_data_specific_args static method that defines CLI arguments for the data module', 'build a PyTorch Lightning MRI reconstruction model by subclassing MriModule and implementing training_step', 'create a DistributedMetricSum metric to aggregate tensor values across distributed processes via sum reduction', 'test the validation_step_end method to verify it logs reconstruction images and computes MSE SSIM metrics', 'review the validation_epoch_end method to understand how NMSE SSIM and PSNR metrics are aggregated across files', 'run the test_epoch_end method to aggregate and save MRI reconstructions to a directory using fastmri', 'build a U-Net training module for accelerated MRI reconstruction with configurable channels and pooling layers', 'run a training step that computes L1 loss between U-Net output and target MRI data', 'run a validation step that returns unnormalized output, target, and L1 loss for MRI batches', 'run a test step that produces numpy output arrays from U-Net forward pass on MRI data', 'configure RMSprop optimizer with StepLR scheduler for U-Net model training', 'build a VarNetModule with custom cascades, pools, and channels for MRI reconstruction', 'run the VarNetModule forward pass on masked k-space data with a mask and low frequency count', 'train the VarNetModule using training_step with SSIM loss on batched MRI k-space data', 'validate the VarNetModule using validation_step to compute val_loss and crop output to target size', 'test the VarNetModule using test_step to produce cropped numpy output arrays for MRI slices']
```

Usage

```
{'build_varnet_module': 'build a VarNetModule with custom cascades, pools, and channels for MRI reconstruction', 'run_forward_varnet': 'run the VarNetModule forward pass on masked k-space data with a mask and low frequency count', 'train_varnet_module': 'train the VarNetModule using training_step with SSIM loss on batched MRI k-space data', 'validate_varnet_module': 'validate the VarNetModule using validation_step to compute val_loss and crop output to target size', 'test_varnet_module': 'test the VarNetModule using test_step to produce cropped numpy output arrays for MRI slices'}
```

