# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/habitat_ovmm/evaluator.py

Prompts

```
['run the OVMMEvaluator to evaluate an agent in local, vectorized, or remote environments', 'run the OVMMEvaluator local_evaluate method to evaluate an agent in a single local environment', 'run the OVMMEvaluator local_evaluate_vectorized method to evaluate an agent across multiple parallel environments', 'run the OVMMEvaluator remote_evaluate method to evaluate an agent via gRPC against a remote environment', 'review the OVMMEvaluator _aggregate_metrics method to understand how episode metrics are aggregated with mean, min, and max', 'run the CLI to aggregate receptacle positions, generate images, and create templated Q/A datasets for all scenes', 'run the script to aggregate receptacle positions by scene across all episodes and save to pickle', 'run the script to generate RGB images of receptacles from view points and save to HDF5', 'run the script to generate templated multiple choice Q/A pairs per episode and save to HDF5', 'run the script to extract a scene ID from a full scene file path string', 'run the habitat rendering test script to save robot third-person RGB images across episodes', 'run get_ac_cont to sample a continuous base_velocity action from the environment action space', 'run get_ac_disc to randomly select a discrete action excluding stop from the environment', 'run get_ac to automatically select continuous or discrete actions based on the environment type', 'run save_image to write a robot observation frame as a PNG to the scene_visuals_with_hbao folder']
```

Usage

```
{'run_OVMMEvaluator_evaluate': 'run the OVMMEvaluator to evaluate an agent in local, vectorized, or remote environments', 'run_OVMMEvaluator_local_evaluate': 'run the OVMMEvaluator local_evaluate method to evaluate an agent in a single local environment', 'run_OVMMEvaluator_local_evaluate_vectorized': 'run the OVMMEvaluator local_evaluate_vectorized method to evaluate an agent across multiple parallel environments', 'run_OVMMEvaluator_remote_evaluate': 'run the OVMMEvaluator remote_evaluate method to evaluate an agent via gRPC against a remote environment', 'review_OVMMEvaluator_aggregate_metrics': 'review the OVMMEvaluator _aggregate_metrics method to understand how episode metrics are aggregated with mean, min, and max'}
```

## File: facebookresearch_home-robot/projects/habitat_ovmm/receptacles_data_collection.py

Prompts

```
['run the OVMMEvaluator to evaluate an agent in local, vectorized, or remote environments', 'run the OVMMEvaluator local_evaluate method to evaluate an agent in a single local environment', 'run the OVMMEvaluator local_evaluate_vectorized method to evaluate an agent across multiple parallel environments', 'run the OVMMEvaluator remote_evaluate method to evaluate an agent via gRPC against a remote environment', 'review the OVMMEvaluator _aggregate_metrics method to understand how episode metrics are aggregated with mean, min, and max', 'run the CLI to aggregate receptacle positions, generate images, and create templated Q/A datasets for all scenes', 'run the script to aggregate receptacle positions by scene across all episodes and save to pickle', 'run the script to generate RGB images of receptacles from view points and save to HDF5', 'run the script to generate templated multiple choice Q/A pairs per episode and save to HDF5', 'run the script to extract a scene ID from a full scene file path string', 'run the habitat rendering test script to save robot third-person RGB images across episodes', 'run get_ac_cont to sample a continuous base_velocity action from the environment action space', 'run get_ac_disc to randomly select a discrete action excluding stop from the environment', 'run get_ac to automatically select continuous or discrete actions based on the environment type', 'run save_image to write a robot observation frame as a PNG to the scene_visuals_with_hbao folder']
```

Usage

```
{'run_receptacles_data_collection': 'run the CLI to aggregate receptacle positions, generate images, and create templated Q/A datasets for all scenes', 'run_receptacle_position_aggregate': 'run the script to aggregate receptacle positions by scene across all episodes and save to pickle', 'run_gen_receptacle_images': 'run the script to generate RGB images of receptacles from view points and save to HDF5', 'run_gen_dataset_question': 'run the script to generate templated multiple choice Q/A pairs per episode and save to HDF5', 'run_extract_scene_id': 'run the script to extract a scene ID from a full scene file path string'}
```

## File: facebookresearch_home-robot/projects/habitat_ovmm/test_rendering.py

Prompts

```
['run the OVMMEvaluator to evaluate an agent in local, vectorized, or remote environments', 'run the OVMMEvaluator local_evaluate method to evaluate an agent in a single local environment', 'run the OVMMEvaluator local_evaluate_vectorized method to evaluate an agent across multiple parallel environments', 'run the OVMMEvaluator remote_evaluate method to evaluate an agent via gRPC against a remote environment', 'review the OVMMEvaluator _aggregate_metrics method to understand how episode metrics are aggregated with mean, min, and max', 'run the CLI to aggregate receptacle positions, generate images, and create templated Q/A datasets for all scenes', 'run the script to aggregate receptacle positions by scene across all episodes and save to pickle', 'run the script to generate RGB images of receptacles from view points and save to HDF5', 'run the script to generate templated multiple choice Q/A pairs per episode and save to HDF5', 'run the script to extract a scene ID from a full scene file path string', 'run the habitat rendering test script to save robot third-person RGB images across episodes', 'run get_ac_cont to sample a continuous base_velocity action from the environment action space', 'run get_ac_disc to randomly select a discrete action excluding stop from the environment', 'run get_ac to automatically select continuous or discrete actions based on the environment type', 'run save_image to write a robot observation frame as a PNG to the scene_visuals_with_hbao folder']
```

Usage

```
{'run_test_rendering': 'run the habitat rendering test script to save robot third-person RGB images across episodes', 'run_get_ac_cont': 'run get_ac_cont to sample a continuous base_velocity action from the environment action space', 'run_get_ac_disc': 'run get_ac_disc to randomly select a discrete action excluding stop from the environment', 'run_get_ac': 'run get_ac to automatically select continuous or discrete actions based on the environment type', 'run_save_image': 'run save_image to write a robot observation frame as a PNG to the scene_visuals_with_hbao folder'}
```

