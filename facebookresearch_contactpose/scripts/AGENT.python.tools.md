# Agent Python Tools

- repo: facebookresearch/contactpose
- repo_uri: https://github.com/facebookresearch/contactpose

## File: facebookresearch_contactpose/scripts/download_data.py

Prompts

```
['run the ContactPoseDownloader to download and extract all grasp data from Dropbox', 'run the ContactPoseDownloader to download contact maps for a specific participant and intent', 'run the ContactPoseDownloader to download color and depth images for a participant and intent', 'run the ContactPoseDownloader to download and extract 3D model files from Dropbox', 'run the ContactPoseDownloader to download 3D model marker location data from Dropbox', 'run the preprocess_images script to crop RGB and depth images and randomize backgrounds for ML training', 'run the preprocess function to crop and save depth images for a single person intent and object', 'run the preprocess_all function to batch preprocess images across multiple people intents and objects', 'review the inspect_dir function that lists all image filenames in a given directory', 'refactor the preprocess function to change the depth-based and color-based foreground masking logic', 'run the script to visualize a contact map with the simple mode using argparse CLI arguments', 'run the script to visualize a contact map colored by finger proximity using semantic_hands_fingers mode', 'run the script to visualize a contact map colored by phalange proximity using semantic_hands_phalanges mode', 'apply an inferno colormap to an Open3D mesh vertex colors with configurable sigmoid activation', 'apply different colormaps per semantic index to an Open3D mesh for finger or phalange visualization']
```

Usage

```
{'run_download_grasps': 'run the ContactPoseDownloader to download and extract all grasp data from Dropbox', 'run_download_contact_maps': 'run the ContactPoseDownloader to download contact maps for a specific participant and intent', 'run_download_images': 'run the ContactPoseDownloader to download color and depth images for a participant and intent', 'run_download_3d_models': 'run the ContactPoseDownloader to download and extract 3D model files from Dropbox', 'run_download_markers': 'run the ContactPoseDownloader to download 3D model marker location data from Dropbox'}
```

## File: facebookresearch_contactpose/scripts/preprocess_images.py

Prompts

```
['run the ContactPoseDownloader to download and extract all grasp data from Dropbox', 'run the ContactPoseDownloader to download contact maps for a specific participant and intent', 'run the ContactPoseDownloader to download color and depth images for a participant and intent', 'run the ContactPoseDownloader to download and extract 3D model files from Dropbox', 'run the ContactPoseDownloader to download 3D model marker location data from Dropbox', 'run the preprocess_images script to crop RGB and depth images and randomize backgrounds for ML training', 'run the preprocess function to crop and save depth images for a single person intent and object', 'run the preprocess_all function to batch preprocess images across multiple people intents and objects', 'review the inspect_dir function that lists all image filenames in a given directory', 'refactor the preprocess function to change the depth-based and color-based foreground masking logic', 'run the script to visualize a contact map with the simple mode using argparse CLI arguments', 'run the script to visualize a contact map colored by finger proximity using semantic_hands_fingers mode', 'run the script to visualize a contact map colored by phalange proximity using semantic_hands_phalanges mode', 'apply an inferno colormap to an Open3D mesh vertex colors with configurable sigmoid activation', 'apply different colormaps per semantic index to an Open3D mesh for finger or phalange visualization']
```

Usage

```
{'run_preprocess_images_cli': 'run the preprocess_images script to crop RGB and depth images and randomize backgrounds for ML training', 'run_preprocess_single': 'run the preprocess function to crop and save depth images for a single person intent and object', 'run_preprocess_all': 'run the preprocess_all function to batch preprocess images across multiple people intents and objects', 'review_inspect_dir': 'review the inspect_dir function that lists all image filenames in a given directory', 'refactor_preprocess_masking': 'refactor the preprocess function to change the depth-based and color-based foreground masking logic'}
```

## File: facebookresearch_contactpose/scripts/show_contactmap.py

Prompts

```
['run the ContactPoseDownloader to download and extract all grasp data from Dropbox', 'run the ContactPoseDownloader to download contact maps for a specific participant and intent', 'run the ContactPoseDownloader to download color and depth images for a participant and intent', 'run the ContactPoseDownloader to download and extract 3D model files from Dropbox', 'run the ContactPoseDownloader to download 3D model marker location data from Dropbox', 'run the preprocess_images script to crop RGB and depth images and randomize backgrounds for ML training', 'run the preprocess function to crop and save depth images for a single person intent and object', 'run the preprocess_all function to batch preprocess images across multiple people intents and objects', 'review the inspect_dir function that lists all image filenames in a given directory', 'refactor the preprocess function to change the depth-based and color-based foreground masking logic', 'run the script to visualize a contact map with the simple mode using argparse CLI arguments', 'run the script to visualize a contact map colored by finger proximity using semantic_hands_fingers mode', 'run the script to visualize a contact map colored by phalange proximity using semantic_hands_phalanges mode', 'apply an inferno colormap to an Open3D mesh vertex colors with configurable sigmoid activation', 'apply different colormaps per semantic index to an Open3D mesh for finger or phalange visualization']
```

Usage

```
{'run_show_contactmap_simple': 'run the script to visualize a contact map with the simple mode using argparse CLI arguments', 'run_show_contactmap_semantic_fingers': 'run the script to visualize a contact map colored by finger proximity using semantic_hands_fingers mode', 'run_show_contactmap_semantic_phalanges': 'run the script to visualize a contact map colored by phalange proximity using semantic_hands_phalanges mode', 'apply_colormap_to_mesh': 'apply an inferno colormap to an Open3D mesh vertex colors with configurable sigmoid activation', 'apply_semantic_colormap_to_mesh': 'apply different colormaps per semantic index to an Open3D mesh for finger or phalange visualization'}
```

