# Agent Python Tools

- repo: facebookresearch/multi-spatialmllm
- repo_uri: https://github.com/facebookresearch/multi-spatialmllm

## File: facebookresearch_multi-spatialmllm/spatial_engine/depth_perception/depth_comparison_coor_engine.py

Prompts

```
['generate training QA data for depth comparison tasks using 3D scene coordinates and camera depth', 'generate evaluation QA data for depth comparison tasks from scene info and visibility data', 'generate a list of visually distinct RGB colors for annotating points on images', 'annotate an image with a colored circle at a specified 2D coordinate point', 'convert a training sample conversation format into an evaluation sample with flattened text field', 'generate QA training data for depth comparison tasks and save to a JSONL file', 'generate evaluation data for depth comparison dot QA tasks and save to JSONL', 'generate QA training samples for a single scene by sampling visible 3D points', 'annotate an image with a colored circle at a specified point coordinate', 'generate depth estimation QA training data from ScanNet scene info and save to JSONL file', 'generate depth estimation QA evaluation data from ScanNet scene info and save to JSONL file', 'convert a training sample conversation format to evaluation text format']
```

Usage

```
{'generate_depth_comparison_training_data': 'generate training QA data for depth comparison tasks using 3D scene coordinates and camera depth', 'generate_depth_comparison_eval_data': 'generate evaluation QA data for depth comparison tasks from scene info and visibility data', 'generate_distinct_colors': 'generate a list of visually distinct RGB colors for annotating points on images', 'annotate_image_with_point': 'annotate an image with a colored circle at a specified 2D coordinate point', 'convert_train_sample_to_eval_sample': 'convert a training sample conversation format into an evaluation sample with flattened text field'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/depth_perception/depth_comparison_dot_engine.py

Prompts

```
['generate training QA data for depth comparison tasks using 3D scene coordinates and camera depth', 'generate evaluation QA data for depth comparison tasks from scene info and visibility data', 'generate a list of visually distinct RGB colors for annotating points on images', 'annotate an image with a colored circle at a specified 2D coordinate point', 'convert a training sample conversation format into an evaluation sample with flattened text field', 'generate QA training data for depth comparison tasks and save to a JSONL file', 'generate evaluation data for depth comparison dot QA tasks and save to JSONL', 'generate QA training samples for a single scene by sampling visible 3D points', 'annotate an image with a colored circle at a specified point coordinate', 'generate depth estimation QA training data from ScanNet scene info and save to JSONL file', 'generate depth estimation QA evaluation data from ScanNet scene info and save to JSONL file', 'convert a training sample conversation format to evaluation text format']
```

Usage

```
{'generate_qa_training_data': 'generate QA training data for depth comparison tasks and save to a JSONL file', 'generate_qa_eval_data': 'generate evaluation data for depth comparison dot QA tasks and save to JSONL', 'generate_qa_training_single_scene': 'generate QA training samples for a single scene by sampling visible 3D points', 'convert_train_sample_to_eval_sample': 'convert a training sample format to evaluation format by extracting text from conversations', 'annotate_image': 'annotate an image with a colored circle at a specified point coordinate'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/depth_perception/depth_estimation_coor_engine.py

Prompts

```
['generate training QA data for depth comparison tasks using 3D scene coordinates and camera depth', 'generate evaluation QA data for depth comparison tasks from scene info and visibility data', 'generate a list of visually distinct RGB colors for annotating points on images', 'annotate an image with a colored circle at a specified 2D coordinate point', 'convert a training sample conversation format into an evaluation sample with flattened text field', 'generate QA training data for depth comparison tasks and save to a JSONL file', 'generate evaluation data for depth comparison dot QA tasks and save to JSONL', 'generate QA training samples for a single scene by sampling visible 3D points', 'annotate an image with a colored circle at a specified point coordinate', 'generate depth estimation QA training data from ScanNet scene info and save to JSONL file', 'generate depth estimation QA evaluation data from ScanNet scene info and save to JSONL file', 'convert a training sample conversation format to evaluation text format']
```

Usage

```
{'generate_depth_qa_training_data': 'generate depth estimation QA training data from ScanNet scene info and save to JSONL file', 'generate_depth_qa_eval_data': 'generate depth estimation QA evaluation data from ScanNet scene info and save to JSONL file', 'generate_distinct_colors': 'generate a list of distinct RGB colors with minimum color distance threshold', 'annotate_image_with_point': 'annotate an image with a colored circle at specified 2D coordinates', 'convert_train_to_eval_sample': 'convert a training sample conversation format to evaluation text format'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/depth_perception/depth_estimation_dot_engine.py

Prompts

```
['generate training QA data for depth comparison tasks using 3D scene coordinates and camera depth', 'generate evaluation QA data for depth comparison tasks from scene info and visibility data', 'generate a list of visually distinct RGB colors for annotating points on images', 'annotate an image with a colored circle at a specified 2D coordinate point', 'convert a training sample conversation format into an evaluation sample with flattened text field', 'generate QA training data for depth comparison tasks and save to a JSONL file', 'generate evaluation data for depth comparison dot QA tasks and save to JSONL', 'generate QA training samples for a single scene by sampling visible 3D points', 'annotate an image with a colored circle at a specified point coordinate', 'generate depth estimation QA training data from ScanNet scene info and save to JSONL file', 'generate depth estimation QA evaluation data from ScanNet scene info and save to JSONL file', 'convert a training sample conversation format to evaluation text format']
```

Usage

```
{'generate_depth_qa_training_data': 'generate depth estimation QA training data from ScanNet scenes and save to JSONL format', 'generate_depth_qa_eval_data': 'generate depth estimation QA evaluation data from ScanNet validation scenes and save to JSONL', 'annotate_image_with_point': 'annotate an image with a colored dot at specified 2D coordinates using OpenCV', 'generate_distinct_colors': 'generate a list of visually distinct RGB colors for annotating multiple points on images', 'convert_train_to_eval_sample': 'convert a training QA sample to evaluation format by extracting text from conversations'}
```

