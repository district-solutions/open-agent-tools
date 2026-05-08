# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/tools/hitl/vision_retrain/vision_annotation_jobs.py

Prompts

```
['run a VisionAnnotationJob to spin up HITs for turkers to annotate visual scenes with instance segmentation masks', 'create a VisionAnnotationJob instance with a batch_id, timestamp, list of scenes, and optional timeout value', 'upload vision annotation results to the droidlet-hitl S3 bucket and save locally in the HITL_TMP_DIR', 'launch a batch of Mephisto HITs by updating the annotation config and running run_annotation_with_qual.py', 'retrieve annotated scene data from Mephisto units and extract instance segmentation tags into output scenes', 'run a vision labeling job to generate voxel world scenes and launch HITs for crowdworkers to label objects', 'run a listener that polls S3 for labeled scene data and pushes annotation jobs to the task runner', 'run the vision labeling CLI with configurable scene dimensions, number of HITs, and timeout settings', 'create a VisionLabelingJob instance with scene parameters like length, height, ground depth, and max shapes', 'create a VisionLabelingListener instance with a batch ID and timeout to monitor S3 for labeled scene results']
```

Usage

```
{'run_vision_annotation_job': 'run a VisionAnnotationJob to spin up HITs for turkers to annotate visual scenes with instance segmentation masks', 'create_vision_annotation_job': 'create a VisionAnnotationJob instance with a batch_id, timestamp, list of scenes, and optional timeout value', 'upload_annotated_scenes_to_s3': 'upload vision annotation results to the droidlet-hitl S3 bucket and save locally in the HITL_TMP_DIR', 'launch_mephisto_hits': 'launch a batch of Mephisto HITs by updating the annotation config and running run_annotation_with_qual.py', 'retrieve_mephisto_annotation_data': 'retrieve annotated scene data from Mephisto units and extract instance segmentation tags into output scenes'}
```

## File: facebookresearch_fairo/droidlet/tools/hitl/vision_retrain/vision_labeling_jobs.py

Prompts

```
['run a VisionAnnotationJob to spin up HITs for turkers to annotate visual scenes with instance segmentation masks', 'create a VisionAnnotationJob instance with a batch_id, timestamp, list of scenes, and optional timeout value', 'upload vision annotation results to the droidlet-hitl S3 bucket and save locally in the HITL_TMP_DIR', 'launch a batch of Mephisto HITs by updating the annotation config and running run_annotation_with_qual.py', 'retrieve annotated scene data from Mephisto units and extract instance segmentation tags into output scenes', 'run a vision labeling job to generate voxel world scenes and launch HITs for crowdworkers to label objects', 'run a listener that polls S3 for labeled scene data and pushes annotation jobs to the task runner', 'run the vision labeling CLI with configurable scene dimensions, number of HITs, and timeout settings', 'create a VisionLabelingJob instance with scene parameters like length, height, ground depth, and max shapes', 'create a VisionLabelingListener instance with a batch ID and timeout to monitor S3 for labeled scene results']
```

Usage

```
{'run_vision_labeling_job': 'run a vision labeling job to generate voxel world scenes and launch HITs for crowdworkers to label objects', 'run_vision_labeling_listener': 'run a listener that polls S3 for labeled scene data and pushes annotation jobs to the task runner', 'run_vision_labeling_cli': 'run the vision labeling CLI with configurable scene dimensions, number of HITs, and timeout settings', 'create_vision_labeling_job': 'create a VisionLabelingJob instance with scene parameters like length, height, ground depth, and max shapes', 'create_vision_labeling_listener': 'create a VisionLabelingListener instance with a batch ID and timeout to monitor S3 for labeled scene results'}
```

