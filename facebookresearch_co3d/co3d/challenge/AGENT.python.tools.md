# Agent Python Tools

- repo: facebookresearch/co3d
- repo_uri: https://github.com/facebookresearch/co3d

## File: facebookresearch_co3d/co3d/challenge/co3d_submission.py

Prompts

```
['create a CO3DSubmission object for a manyview or fewview task on the dev or test set', 'add a predicted image with RGB, depth, and mask to the current CO3D submission', 'export all submission results to an HDF5 archive file ready for EvalAI upload', 'locally evaluate submission predictions against ground truth on the unredacted development set', 'submit the exported HDF5 submission archive to the EvalAI challenge server via CLI', 'load an RGBDA frame with image, depth, and mask from PNG files on disk', 'store an RGBDA frame as separate PNG files for image, depth, and mask', 'load all evaluation batch JSON files for a CO3D challenge task and sequence set', 'export a dictionary of result files into a single compressed HDF5 archive for EvalAI submission', 'create symlinks from an HDF5 archive to files under a target root directory', 'evaluate predicted and ground truth RGBDA frames computing PSNR, depth error, and IoU metrics', 'calculate the peak signal to noise ratio between two image tensors with optional masking', 'compute the intersection over union between predicted and target segmentation masks with thresholding', 'compute MSE and absolute depth error between predicted and ground truth depth maps with optimal scaling', 'calculate the mean absolute error between predicted and target RGB color arrays with optional masking', 'run the evaluate_file_folders function to compare prediction and ground truth folders and compute evaluation metrics', 'run the unzip function to extract a zip file to a specified output directory', 'run the get_result_directory_file_names function to parse a results directory and return example name to file path mappings', 'run the check_user_submission_file_paths function to validate that user submission files match ground truth files', 'run the check_same_rgbda_sizes function to verify that prediction and ground truth RGBDA frames have matching dimensions']
```

Usage

```
{'create_CO3DSubmission': 'create a CO3DSubmission object for a manyview or fewview task on the dev or test set', 'add_result_CO3DSubmission': 'add a predicted image with RGB, depth, and mask to the current CO3D submission', 'export_results_CO3DSubmission': 'export all submission results to an HDF5 archive file ready for EvalAI upload', 'evaluate_CO3DSubmission': 'locally evaluate submission predictions against ground truth on the unredacted development set', 'submit_to_eval_ai_CO3DSubmission': 'submit the exported HDF5 submission archive to the EvalAI challenge server via CLI'}
```

## File: facebookresearch_co3d/co3d/challenge/io.py

Prompts

```
['create a CO3DSubmission object for a manyview or fewview task on the dev or test set', 'add a predicted image with RGB, depth, and mask to the current CO3D submission', 'export all submission results to an HDF5 archive file ready for EvalAI upload', 'locally evaluate submission predictions against ground truth on the unredacted development set', 'submit the exported HDF5 submission archive to the EvalAI challenge server via CLI', 'load an RGBDA frame with image, depth, and mask from PNG files on disk', 'store an RGBDA frame as separate PNG files for image, depth, and mask', 'load all evaluation batch JSON files for a CO3D challenge task and sequence set', 'export a dictionary of result files into a single compressed HDF5 archive for EvalAI submission', 'create symlinks from an HDF5 archive to files under a target root directory', 'evaluate predicted and ground truth RGBDA frames computing PSNR, depth error, and IoU metrics', 'calculate the peak signal to noise ratio between two image tensors with optional masking', 'compute the intersection over union between predicted and target segmentation masks with thresholding', 'compute MSE and absolute depth error between predicted and ground truth depth maps with optimal scaling', 'calculate the mean absolute error between predicted and target RGB color arrays with optional masking', 'run the evaluate_file_folders function to compare prediction and ground truth folders and compute evaluation metrics', 'run the unzip function to extract a zip file to a specified output directory', 'run the get_result_directory_file_names function to parse a results directory and return example name to file path mappings', 'run the check_user_submission_file_paths function to validate that user submission files match ground truth files', 'run the check_same_rgbda_sizes function to verify that prediction and ground truth RGBDA frames have matching dimensions']
```

Usage

```
{'load_rgbda_frame': 'load an RGBDA frame with image, depth, and mask from PNG files on disk', 'store_rgbda_frame': 'store an RGBDA frame as separate PNG files for image, depth, and mask', 'load_all_eval_batches': 'load all evaluation batch JSON files for a CO3D challenge task and sequence set', 'export_result_file_dict_to_hdf5': 'export a dictionary of result files into a single compressed HDF5 archive for EvalAI submission', 'make_hdf5_file_links': 'create symlinks from an HDF5 archive to files under a target root directory'}
```

## File: facebookresearch_co3d/co3d/challenge/metric_utils.py

Prompts

```
['create a CO3DSubmission object for a manyview or fewview task on the dev or test set', 'add a predicted image with RGB, depth, and mask to the current CO3D submission', 'export all submission results to an HDF5 archive file ready for EvalAI upload', 'locally evaluate submission predictions against ground truth on the unredacted development set', 'submit the exported HDF5 submission archive to the EvalAI challenge server via CLI', 'load an RGBDA frame with image, depth, and mask from PNG files on disk', 'store an RGBDA frame as separate PNG files for image, depth, and mask', 'load all evaluation batch JSON files for a CO3D challenge task and sequence set', 'export a dictionary of result files into a single compressed HDF5 archive for EvalAI submission', 'create symlinks from an HDF5 archive to files under a target root directory', 'evaluate predicted and ground truth RGBDA frames computing PSNR, depth error, and IoU metrics', 'calculate the peak signal to noise ratio between two image tensors with optional masking', 'compute the intersection over union between predicted and target segmentation masks with thresholding', 'compute MSE and absolute depth error between predicted and ground truth depth maps with optimal scaling', 'calculate the mean absolute error between predicted and target RGB color arrays with optional masking', 'run the evaluate_file_folders function to compare prediction and ground truth folders and compute evaluation metrics', 'run the unzip function to extract a zip file to a specified output directory', 'run the get_result_directory_file_names function to parse a results directory and return example name to file path mappings', 'run the check_user_submission_file_paths function to validate that user submission files match ground truth files', 'run the check_same_rgbda_sizes function to verify that prediction and ground truth RGBDA frames have matching dimensions']
```

Usage

```
{'eval_one_rgbda': 'evaluate predicted and ground truth RGBDA frames computing PSNR, depth error, and IoU metrics', 'calc_psnr': 'calculate the peak signal to noise ratio between two image tensors with optional masking', 'calc_iou': 'compute the intersection over union between predicted and target segmentation masks with thresholding', 'calc_mse_abs_depth': 'compute MSE and absolute depth error between predicted and ground truth depth maps with optimal scaling', 'rgb_l1': 'calculate the mean absolute error between predicted and target RGB color arrays with optional masking'}
```

## File: facebookresearch_co3d/co3d/challenge/utils.py

Prompts

```
['create a CO3DSubmission object for a manyview or fewview task on the dev or test set', 'add a predicted image with RGB, depth, and mask to the current CO3D submission', 'export all submission results to an HDF5 archive file ready for EvalAI upload', 'locally evaluate submission predictions against ground truth on the unredacted development set', 'submit the exported HDF5 submission archive to the EvalAI challenge server via CLI', 'load an RGBDA frame with image, depth, and mask from PNG files on disk', 'store an RGBDA frame as separate PNG files for image, depth, and mask', 'load all evaluation batch JSON files for a CO3D challenge task and sequence set', 'export a dictionary of result files into a single compressed HDF5 archive for EvalAI submission', 'create symlinks from an HDF5 archive to files under a target root directory', 'evaluate predicted and ground truth RGBDA frames computing PSNR, depth error, and IoU metrics', 'calculate the peak signal to noise ratio between two image tensors with optional masking', 'compute the intersection over union between predicted and target segmentation masks with thresholding', 'compute MSE and absolute depth error between predicted and ground truth depth maps with optimal scaling', 'calculate the mean absolute error between predicted and target RGB color arrays with optional masking', 'run the evaluate_file_folders function to compare prediction and ground truth folders and compute evaluation metrics', 'run the unzip function to extract a zip file to a specified output directory', 'run the get_result_directory_file_names function to parse a results directory and return example name to file path mappings', 'run the check_user_submission_file_paths function to validate that user submission files match ground truth files', 'run the check_same_rgbda_sizes function to verify that prediction and ground truth RGBDA frames have matching dimensions']
```

Usage

```
{'evaluate_CO3D_predictions': 'run the evaluate_file_folders function to compare prediction and ground truth folders and compute evaluation metrics', 'extract_zip_archive': 'run the unzip function to extract a zip file to a specified output directory', 'parse_result_directory': 'run the get_result_directory_file_names function to parse a results directory and return example name to file path mappings', 'validate_submission_files': 'run the check_user_submission_file_paths function to validate that user submission files match ground truth files', 'check_RGBDA_frame_sizes': 'run the check_same_rgbda_sizes function to verify that prediction and ground truth RGBDA frames have matching dimensions'}
```

