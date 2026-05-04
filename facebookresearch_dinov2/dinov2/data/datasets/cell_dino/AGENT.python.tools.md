# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/data/datasets/cell_dino/chammi_cp.py

Prompts

```
['create a CHAMMI_CP dataset instance with a specified split and root directory for cell painting images', 'load image file paths and class labels from the morphem70k metadata CSV for a given split', 'get the raw bytes of an image file at a given index from the CHAMMI_CP dataset', 'get all target labels as a numpy array from the CHAMMI_CP dataset instance', 'review the CLASS_LABELS dictionary mapping compound names to integer labels for the CHAMMI benchmark', 'create a CHAMMI_HPA dataset instance with a specified split and root directory for cell painting', 'get the raw image bytes for a sample at a given index in the CHAMMI_HPA dataset', 'get all class label targets as a numpy array from the CHAMMI_HPA dataset', 'review the CHAMMI_HPA CLASS_LABELS mapping of organelle names to integer indices', 'create a CHAMMI_WTC dataset instance with a specified split and root directory for cell painting data', 'create an HPAFoV dataset instance with a specified split, mode, and root directory path', 'load HPAFoV training images and labels from CSV using _load_file_names_and_labels with train split', 'load HPAFoV SSL images and labels from whole_images_names.csv using _load_file_names_and_labels_ssl', 'list image file paths from a CSV file using _list_images_from_csv with img_path and csv_path', 'get the CSV file path for a given split like TRAIN or VAL using get_csv_fpath', 'create an HPAone dataset instance with a specified split and mode for HPA cell image data', 'parse a CSV file with protein localization and cell type labels into structured samples', 'load image file names and fake labels from the SSL pretrain CSV for self-supervised training', 'load image paths and labels for train or validation splits with protein or cell type mode']
```

Usage

```
{'create_CHAMMI_CP_dataset': 'create a CHAMMI_CP dataset instance with a specified split and root directory for cell painting images', 'load_file_names_and_targets': 'load image file paths and class labels from the morphem70k metadata CSV for a given split', 'get_image_data': 'get the raw bytes of an image file at a given index from the CHAMMI_CP dataset', 'get_targets': 'get all target labels as a numpy array from the CHAMMI_CP dataset instance', 'review_CLASS_LABELS': 'review the CLASS_LABELS dictionary mapping compound names to integer labels for the CHAMMI benchmark'}
```

## File: facebookresearch_dinov2/dinov2/data/datasets/cell_dino/chammi_hpa.py

Prompts

```
['create a CHAMMI_CP dataset instance with a specified split and root directory for cell painting images', 'load image file paths and class labels from the morphem70k metadata CSV for a given split', 'get the raw bytes of an image file at a given index from the CHAMMI_CP dataset', 'get all target labels as a numpy array from the CHAMMI_CP dataset instance', 'review the CLASS_LABELS dictionary mapping compound names to integer labels for the CHAMMI benchmark', 'create a CHAMMI_HPA dataset instance with a specified split and root directory for cell painting', 'get the raw image bytes for a sample at a given index in the CHAMMI_HPA dataset', 'get all class label targets as a numpy array from the CHAMMI_HPA dataset', 'review the CHAMMI_HPA CLASS_LABELS mapping of organelle names to integer indices', 'create a CHAMMI_WTC dataset instance with a specified split and root directory for cell painting data', 'create an HPAFoV dataset instance with a specified split, mode, and root directory path', 'load HPAFoV training images and labels from CSV using _load_file_names_and_labels with train split', 'load HPAFoV SSL images and labels from whole_images_names.csv using _load_file_names_and_labels_ssl', 'list image file paths from a CSV file using _list_images_from_csv with img_path and csv_path', 'get the CSV file path for a given split like TRAIN or VAL using get_csv_fpath', 'create an HPAone dataset instance with a specified split and mode for HPA cell image data', 'parse a CSV file with protein localization and cell type labels into structured samples', 'load image file names and fake labels from the SSL pretrain CSV for self-supervised training', 'load image paths and labels for train or validation splits with protein or cell type mode']
```

Usage

```
{'create_dataset_chammi_hpa': 'create a CHAMMI_HPA dataset instance with a specified split and root directory for cell painting', 'load_file_names_and_targets': 'load image file paths and class labels from the morphem70k metadata CSV for a given split', 'get_image_data_chammi_hpa': 'get the raw image bytes for a sample at a given index in the CHAMMI_HPA dataset', 'get_targets_chammi_hpa': 'get all class label targets as a numpy array from the CHAMMI_HPA dataset', 'review_chammi_hpa_class_labels': 'review the CHAMMI_HPA CLASS_LABELS mapping of organelle names to integer indices'}
```

## File: facebookresearch_dinov2/dinov2/data/datasets/cell_dino/chammi_wtc.py

Prompts

```
['create a CHAMMI_CP dataset instance with a specified split and root directory for cell painting images', 'load image file paths and class labels from the morphem70k metadata CSV for a given split', 'get the raw bytes of an image file at a given index from the CHAMMI_CP dataset', 'get all target labels as a numpy array from the CHAMMI_CP dataset instance', 'review the CLASS_LABELS dictionary mapping compound names to integer labels for the CHAMMI benchmark', 'create a CHAMMI_HPA dataset instance with a specified split and root directory for cell painting', 'get the raw image bytes for a sample at a given index in the CHAMMI_HPA dataset', 'get all class label targets as a numpy array from the CHAMMI_HPA dataset', 'review the CHAMMI_HPA CLASS_LABELS mapping of organelle names to integer indices', 'create a CHAMMI_WTC dataset instance with a specified split and root directory for cell painting data', 'create an HPAFoV dataset instance with a specified split, mode, and root directory path', 'load HPAFoV training images and labels from CSV using _load_file_names_and_labels with train split', 'load HPAFoV SSL images and labels from whole_images_names.csv using _load_file_names_and_labels_ssl', 'list image file paths from a CSV file using _list_images_from_csv with img_path and csv_path', 'get the CSV file path for a given split like TRAIN or VAL using get_csv_fpath', 'create an HPAone dataset instance with a specified split and mode for HPA cell image data', 'parse a CSV file with protein localization and cell type labels into structured samples', 'load image file names and fake labels from the SSL pretrain CSV for self-supervised training', 'load image paths and labels for train or validation splits with protein or cell type mode']
```

Usage

```
{'create_CHAMMI_WTC_dataset': 'create a CHAMMI_WTC dataset instance with a specified split and root directory for cell painting data', 'load_file_names_and_targets': 'load image file paths and labels from the morphem70k metadata CSV for a given split', 'get_image_data': 'get the raw bytes of an image file at a given index from the CHAMMI_WTC dataset', 'get_targets': 'get all target labels as a numpy array from the CHAMMI_WTC dataset instance', 'review_CLASS_LABELS': 'review the CLASS_LABELS mapping that defines cell morphology stage labels M0 through M6M7_single'}
```

## File: facebookresearch_dinov2/dinov2/data/datasets/cell_dino/hpafov.py

Prompts

```
['create a CHAMMI_CP dataset instance with a specified split and root directory for cell painting images', 'load image file paths and class labels from the morphem70k metadata CSV for a given split', 'get the raw bytes of an image file at a given index from the CHAMMI_CP dataset', 'get all target labels as a numpy array from the CHAMMI_CP dataset instance', 'review the CLASS_LABELS dictionary mapping compound names to integer labels for the CHAMMI benchmark', 'create a CHAMMI_HPA dataset instance with a specified split and root directory for cell painting', 'get the raw image bytes for a sample at a given index in the CHAMMI_HPA dataset', 'get all class label targets as a numpy array from the CHAMMI_HPA dataset', 'review the CHAMMI_HPA CLASS_LABELS mapping of organelle names to integer indices', 'create a CHAMMI_WTC dataset instance with a specified split and root directory for cell painting data', 'create an HPAFoV dataset instance with a specified split, mode, and root directory path', 'load HPAFoV training images and labels from CSV using _load_file_names_and_labels with train split', 'load HPAFoV SSL images and labels from whole_images_names.csv using _load_file_names_and_labels_ssl', 'list image file paths from a CSV file using _list_images_from_csv with img_path and csv_path', 'get the CSV file path for a given split like TRAIN or VAL using get_csv_fpath', 'create an HPAone dataset instance with a specified split and mode for HPA cell image data', 'parse a CSV file with protein localization and cell type labels into structured samples', 'load image file names and fake labels from the SSL pretrain CSV for self-supervised training', 'load image paths and labels for train or validation splits with protein or cell type mode']
```

Usage

```
{'create_HPAFoV_dataset': 'create an HPAFoV dataset instance with a specified split, mode, and root directory path', 'load_HPAFoV_train_images': 'load HPAFoV training images and labels from CSV using _load_file_names_and_labels with train split', 'load_HPAFoV_ssl_images': 'load HPAFoV SSL images and labels from whole_images_names.csv using _load_file_names_and_labels_ssl', 'list_images_from_csv': 'list image file paths from a CSV file using _list_images_from_csv with img_path and csv_path', 'get_csv_fpath_for_split': 'get the CSV file path for a given split like TRAIN or VAL using get_csv_fpath'}
```

## File: facebookresearch_dinov2/dinov2/data/datasets/cell_dino/hpaone.py

Prompts

```
['create a CHAMMI_CP dataset instance with a specified split and root directory for cell painting images', 'load image file paths and class labels from the morphem70k metadata CSV for a given split', 'get the raw bytes of an image file at a given index from the CHAMMI_CP dataset', 'get all target labels as a numpy array from the CHAMMI_CP dataset instance', 'review the CLASS_LABELS dictionary mapping compound names to integer labels for the CHAMMI benchmark', 'create a CHAMMI_HPA dataset instance with a specified split and root directory for cell painting', 'get the raw image bytes for a sample at a given index in the CHAMMI_HPA dataset', 'get all class label targets as a numpy array from the CHAMMI_HPA dataset', 'review the CHAMMI_HPA CLASS_LABELS mapping of organelle names to integer indices', 'create a CHAMMI_WTC dataset instance with a specified split and root directory for cell painting data', 'create an HPAFoV dataset instance with a specified split, mode, and root directory path', 'load HPAFoV training images and labels from CSV using _load_file_names_and_labels with train split', 'load HPAFoV SSL images and labels from whole_images_names.csv using _load_file_names_and_labels_ssl', 'list image file paths from a CSV file using _list_images_from_csv with img_path and csv_path', 'get the CSV file path for a given split like TRAIN or VAL using get_csv_fpath', 'create an HPAone dataset instance with a specified split and mode for HPA cell image data', 'parse a CSV file with protein localization and cell type labels into structured samples', 'load image file names and fake labels from the SSL pretrain CSV for self-supervised training', 'load image paths and labels for train or validation splits with protein or cell type mode']
```

Usage

```
{'create_HPAone_dataset': 'create an HPAone dataset instance with a specified split and mode for HPA cell image data', 'parse_csv_labels': 'parse a CSV file with protein localization and cell type labels into structured samples', 'load_ssl_file_names': 'load image file names and fake labels from the SSL pretrain CSV for self-supervised training', 'load_train_val_labels': 'load image paths and labels for train or validation splits with protein or cell type mode', 'get_image_data': 'get the raw bytes of an image file at a given index from the HPAone dataset'}
```

