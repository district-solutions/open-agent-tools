# Agent Python Tools

- repo: facebookresearch/c3dponrsfm
- repo_uri: https://github.com/facebookresearch/c3dpo_nrsfm

## File: facebookresearch_c3dponrsfm/dataset/dataset_zoo.py

Prompts

```
['create a KeypointsDataset for h36m, pascal3d, or cub_birds by calling dataset_zoo with the dataset name', 'create train and val datasets by calling dataset_zoo with sets_to_load specifying which splits to load', 'create datasets and force re-download of JSON files by calling dataset_zoo with force_download set to True', 'download a dataset JSON file from a remote URL and verify its MD5 checksum using download_dataset_json', 'review the dataset_zoo function to understand supported datasets like h36m_hourglass, up3d_79kp, and pascal3d_hrnet', 'run eval_zoo to get the evaluation script and variables for a named dataset like h36m or pascal3d', 'run eval_pascal3d to evaluate 3D error metrics on Pascal3D predictions with per-class results', 'run eval_h36m to evaluate 3D pose predictions on the Human3.6M dataset with per-action breakdown', 'run calc_3d_errs to compute MPJPE and stress error metrics between predicted and ground truth 3D keypoints', 'run calc_stress_err to compute the stress error comparing pairwise Euclidean distance matrices of predicted and ground truth keypoints', 'create a KeypointsDataset instance from a JSON or pickle file containing object keypoint annotations', 'load keypoint annotation data from a JSON or pickle file into the dataset database', 'parse and group database entries by unique class masks for class-based random sampling', 'restrict the dataset to a limited number of randomly sampled entries using a fixed numpy seed', 'compute which keypoints fall within a bounding box with a 10% context margin and calculate visibility error']
```

Usage

```
{'create_dataset_zoo': 'create a KeypointsDataset for h36m, pascal3d, or cub_birds by calling dataset_zoo with the dataset name', 'create_dataset_zoo_custom_sets': 'create train and val datasets by calling dataset_zoo with sets_to_load specifying which splits to load', 'create_dataset_zoo_force_download': 'create datasets and force re-download of JSON files by calling dataset_zoo with force_download set to True', 'download_dataset_json': 'download a dataset JSON file from a remote URL and verify its MD5 checksum using download_dataset_json', 'review_dataset_zoo': 'review the dataset_zoo function to understand supported datasets like h36m_hourglass, up3d_79kp, and pascal3d_hrnet'}
```

## File: facebookresearch_c3dponrsfm/dataset/eval_zoo.py

Prompts

```
['create a KeypointsDataset for h36m, pascal3d, or cub_birds by calling dataset_zoo with the dataset name', 'create train and val datasets by calling dataset_zoo with sets_to_load specifying which splits to load', 'create datasets and force re-download of JSON files by calling dataset_zoo with force_download set to True', 'download a dataset JSON file from a remote URL and verify its MD5 checksum using download_dataset_json', 'review the dataset_zoo function to understand supported datasets like h36m_hourglass, up3d_79kp, and pascal3d_hrnet', 'run eval_zoo to get the evaluation script and variables for a named dataset like h36m or pascal3d', 'run eval_pascal3d to evaluate 3D error metrics on Pascal3D predictions with per-class results', 'run eval_h36m to evaluate 3D pose predictions on the Human3.6M dataset with per-action breakdown', 'run calc_3d_errs to compute MPJPE and stress error metrics between predicted and ground truth 3D keypoints', 'run calc_stress_err to compute the stress error comparing pairwise Euclidean distance matrices of predicted and ground truth keypoints', 'create a KeypointsDataset instance from a JSON or pickle file containing object keypoint annotations', 'load keypoint annotation data from a JSON or pickle file into the dataset database', 'parse and group database entries by unique class masks for class-based random sampling', 'restrict the dataset to a limited number of randomly sampled entries using a fixed numpy seed', 'compute which keypoints fall within a bounding box with a 10% context margin and calculate visibility error']
```

Usage

```
{'run_eval_zoo': 'run eval_zoo to get the evaluation script and variables for a named dataset like h36m or pascal3d', 'run_eval_pascal3d': 'run eval_pascal3d to evaluate 3D error metrics on Pascal3D predictions with per-class results', 'run_eval_h36m': 'run eval_h36m to evaluate 3D pose predictions on the Human3.6M dataset with per-action breakdown', 'run_calc_3d_errs': 'run calc_3d_errs to compute MPJPE and stress error metrics between predicted and ground truth 3D keypoints', 'run_calc_stress_err': 'run calc_stress_err to compute the stress error comparing pairwise Euclidean distance matrices of predicted and ground truth keypoints'}
```

## File: facebookresearch_c3dponrsfm/dataset/keypoints_dataset.py

Prompts

```
['create a KeypointsDataset for h36m, pascal3d, or cub_birds by calling dataset_zoo with the dataset name', 'create train and val datasets by calling dataset_zoo with sets_to_load specifying which splits to load', 'create datasets and force re-download of JSON files by calling dataset_zoo with force_download set to True', 'download a dataset JSON file from a remote URL and verify its MD5 checksum using download_dataset_json', 'review the dataset_zoo function to understand supported datasets like h36m_hourglass, up3d_79kp, and pascal3d_hrnet', 'run eval_zoo to get the evaluation script and variables for a named dataset like h36m or pascal3d', 'run eval_pascal3d to evaluate 3D error metrics on Pascal3D predictions with per-class results', 'run eval_h36m to evaluate 3D pose predictions on the Human3.6M dataset with per-action breakdown', 'run calc_3d_errs to compute MPJPE and stress error metrics between predicted and ground truth 3D keypoints', 'run calc_stress_err to compute the stress error comparing pairwise Euclidean distance matrices of predicted and ground truth keypoints', 'create a KeypointsDataset instance from a JSON or pickle file containing object keypoint annotations', 'load keypoint annotation data from a JSON or pickle file into the dataset database', 'parse and group database entries by unique class masks for class-based random sampling', 'restrict the dataset to a limited number of randomly sampled entries using a fixed numpy seed', 'compute which keypoints fall within a bounding box with a 10% context margin and calculate visibility error']
```

Usage

```
{'create_KeypointsDataset': 'create a KeypointsDataset instance from a JSON or pickle file containing object keypoint annotations', 'load_db_file': 'load keypoint annotation data from a JSON or pickle file into the dataset database', 'get_class_db': 'parse and group database entries by unique class masks for class-based random sampling', 'restrict_images': 'restrict the dataset to a limited number of randomly sampled entries using a fixed numpy seed', 'bbox_kp_visibility': 'compute which keypoints fall within a bounding box with a 10% context margin and calculate visibility error'}
```

