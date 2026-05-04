# Agent Python Tools

- repo: facebookresearch/eft
- repo_uri: https://github.com/facebookresearch/eft

## File: facebookresearch_eft/bodymocap/apps/eval.py

Prompts

```
['run evaluation on a trained HMR model against h36m-p1, 3dpw, or mpi-inf-3dhp datasets using a checkpoint file', 'run the run_evaluation function with a model, dataset name, and dataset object to compute MPJPE and reconstruction error metrics', 'run eval_main with a list of CLI arguments to load a checkpoint and evaluate across multiple datasets', 'evaluate 3D pose estimation quality by computing MPJPE and PA-MPJPE reconstruction error on Human3.6M or 3DPW datasets', 'save SMPL pose, betas, camera, and predicted joints to an npz file using the result_file argument', 'run 3D pose evaluation on a dataset by loading predictions from pickle files and computing MPJPE metrics', 'run the evalfrompkl script with a checkpoint path and dataset name via command-line arguments', 'evaluate a trained HMR model on the 3DPW dataset and print per-sequence MPJPE and reconstruction error', 'evaluate a trained HMR model on the Human3.6M dataset using Protocol 1 or Protocol 2', 'load an HMR model checkpoint and run evaluation on a BaseDataset with SMPL body model parameters', 'run the trainerWrapper_original function to train a body mocap model on 3DPW and H36M datasets', 'run the exemplarTrainerWrapper function to fit EFT exemplars across the entire database', 'run the eft3DPWTestWrapper function to test EFT fitting on the 3DPW dataset', 'run the smplifyAllWrapper function to apply SMPLify optimization across the entire database', 'run the exemplarTrainerWrapper_analysis function to analyze EFT fitting results on 3DPW and H36M datasets']
```

Usage

```
{'run_evaluation_on_dataset': 'run evaluation on a trained HMR model against h36m-p1, 3dpw, or mpi-inf-3dhp datasets using a checkpoint file', 'run_evaluation_function': 'run the run_evaluation function with a model, dataset name, and dataset object to compute MPJPE and reconstruction error metrics', 'eval_main_entry': 'run eval_main with a list of CLI arguments to load a checkpoint and evaluate across multiple datasets', 'evaluate_3d_pose_metrics': 'evaluate 3D pose estimation quality by computing MPJPE and PA-MPJPE reconstruction error on Human3.6M or 3DPW datasets', 'save_evaluation_results': 'save SMPL pose, betas, camera, and predicted joints to an npz file using the result_file argument'}
```

## File: facebookresearch_eft/bodymocap/apps/evalfrompkl.py

Prompts

```
['run evaluation on a trained HMR model against h36m-p1, 3dpw, or mpi-inf-3dhp datasets using a checkpoint file', 'run the run_evaluation function with a model, dataset name, and dataset object to compute MPJPE and reconstruction error metrics', 'run eval_main with a list of CLI arguments to load a checkpoint and evaluate across multiple datasets', 'evaluate 3D pose estimation quality by computing MPJPE and PA-MPJPE reconstruction error on Human3.6M or 3DPW datasets', 'save SMPL pose, betas, camera, and predicted joints to an npz file using the result_file argument', 'run 3D pose evaluation on a dataset by loading predictions from pickle files and computing MPJPE metrics', 'run the evalfrompkl script with a checkpoint path and dataset name via command-line arguments', 'evaluate a trained HMR model on the 3DPW dataset and print per-sequence MPJPE and reconstruction error', 'evaluate a trained HMR model on the Human3.6M dataset using Protocol 1 or Protocol 2', 'load an HMR model checkpoint and run evaluation on a BaseDataset with SMPL body model parameters', 'run the trainerWrapper_original function to train a body mocap model on 3DPW and H36M datasets', 'run the exemplarTrainerWrapper function to fit EFT exemplars across the entire database', 'run the eft3DPWTestWrapper function to test EFT fitting on the 3DPW dataset', 'run the smplifyAllWrapper function to apply SMPLify optimization across the entire database', 'run the exemplarTrainerWrapper_analysis function to analyze EFT fitting results on 3DPW and H36M datasets']
```

Usage

```
{'run_evaluation_from_pkl': 'run 3D pose evaluation on a dataset by loading predictions from pickle files and computing MPJPE metrics', 'run_evaluation_cli': 'run the evalfrompkl script with a checkpoint path and dataset name via command-line arguments', 'evaluate_3dpw_dataset': 'evaluate a trained HMR model on the 3DPW dataset and print per-sequence MPJPE and reconstruction error', 'evaluate_h36m_dataset': 'evaluate a trained HMR model on the Human3.6M dataset using Protocol 1 or Protocol 2', 'save_evaluation_results': 'save predicted SMPL pose, betas, camera, and joint results to an npz file for further processing'}
```

## File: facebookresearch_eft/bodymocap/apps/evalfrompkl_iter.py

Prompts

```
['run evaluation on a trained HMR model against h36m-p1, 3dpw, or mpi-inf-3dhp datasets using a checkpoint file', 'run the run_evaluation function with a model, dataset name, and dataset object to compute MPJPE and reconstruction error metrics', 'run eval_main with a list of CLI arguments to load a checkpoint and evaluate across multiple datasets', 'evaluate 3D pose estimation quality by computing MPJPE and PA-MPJPE reconstruction error on Human3.6M or 3DPW datasets', 'save SMPL pose, betas, camera, and predicted joints to an npz file using the result_file argument', 'run 3D pose evaluation on a dataset by loading predictions from pickle files and computing MPJPE metrics', 'run the evalfrompkl script with a checkpoint path and dataset name via command-line arguments', 'evaluate a trained HMR model on the 3DPW dataset and print per-sequence MPJPE and reconstruction error', 'evaluate a trained HMR model on the Human3.6M dataset using Protocol 1 or Protocol 2', 'load an HMR model checkpoint and run evaluation on a BaseDataset with SMPL body model parameters', 'run the trainerWrapper_original function to train a body mocap model on 3DPW and H36M datasets', 'run the exemplarTrainerWrapper function to fit EFT exemplars across the entire database', 'run the eft3DPWTestWrapper function to test EFT fitting on the 3DPW dataset', 'run the smplifyAllWrapper function to apply SMPLify optimization across the entire database', 'run the exemplarTrainerWrapper_analysis function to analyze EFT fitting results on 3DPW and H36M datasets']
```

Usage

```
{'run_evaluation_from_pkl': 'run evaluation on 3D pose datasets by loading reconstruction error data from pickle files', 'run_evaluation_function': 'run the run_evaluation function with an HMR model, dataset name, and DataLoader to compute MPJPE metrics', 'evaluate_3dpw_dataset': 'evaluate a trained HMR model on the 3DPW dataset using command-line arguments for checkpoint and dataset', 'evaluate_h36m_dataset': 'evaluate a trained HMR model on the Human3.6M dataset protocol 1 or 2 with configurable batch size', 'load_and_run_hmr_model': 'load an HMR model checkpoint and run evaluation on a BaseDataset with SMPL body model parameters'}
```

## File: facebookresearch_eft/bodymocap/apps/trainCaller.py

Prompts

```
['run evaluation on a trained HMR model against h36m-p1, 3dpw, or mpi-inf-3dhp datasets using a checkpoint file', 'run the run_evaluation function with a model, dataset name, and dataset object to compute MPJPE and reconstruction error metrics', 'run eval_main with a list of CLI arguments to load a checkpoint and evaluate across multiple datasets', 'evaluate 3D pose estimation quality by computing MPJPE and PA-MPJPE reconstruction error on Human3.6M or 3DPW datasets', 'save SMPL pose, betas, camera, and predicted joints to an npz file using the result_file argument', 'run 3D pose evaluation on a dataset by loading predictions from pickle files and computing MPJPE metrics', 'run the evalfrompkl script with a checkpoint path and dataset name via command-line arguments', 'evaluate a trained HMR model on the 3DPW dataset and print per-sequence MPJPE and reconstruction error', 'evaluate a trained HMR model on the Human3.6M dataset using Protocol 1 or Protocol 2', 'load an HMR model checkpoint and run evaluation on a BaseDataset with SMPL body model parameters', 'run the trainerWrapper_original function to train a body mocap model on 3DPW and H36M datasets', 'run the exemplarTrainerWrapper function to fit EFT exemplars across the entire database', 'run the eft3DPWTestWrapper function to test EFT fitting on the 3DPW dataset', 'run the smplifyAllWrapper function to apply SMPLify optimization across the entire database', 'run the exemplarTrainerWrapper_analysis function to analyze EFT fitting results on 3DPW and H36M datasets']
```

Usage

```
{'run_trainer_original': 'run the trainerWrapper_original function to train a body mocap model on 3DPW and H36M datasets', 'run_exemplar_trainer': 'run the exemplarTrainerWrapper function to fit EFT exemplars across the entire database', 'run_eft_3dpw_test': 'run the eft3DPWTestWrapper function to test EFT fitting on the 3DPW dataset', 'run_smplify_all': 'run the smplifyAllWrapper function to apply SMPLify optimization across the entire database', 'run_exemplar_analysis': 'run the exemplarTrainerWrapper_analysis function to analyze EFT fitting results on 3DPW and H36M datasets'}
```

