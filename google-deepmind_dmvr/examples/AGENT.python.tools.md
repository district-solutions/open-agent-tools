# Agent Python Tools

- repo: google-deepmind/dmvr
- repo_uri: https://github.com/google-deepmind/dmvr

## File: google-deepmind_dmvr/examples/generate_from_file.py

Prompts

```
['run the script to generate TFRecords of SequenceExample from raw videos listed in a CSV file', 'extract a list of JPEG bytes from a video file between start and end timestamps using ffmpeg', 'extract raw mono audio as a float list from a video file using ffmpeg', 'generate a TensorFlow SequenceExample with encoded frames, audio, labels, and metadata from a video clip', 'add a bytes list feature to a TensorFlow SequenceExample feature list by key', 'run the HMDB51 linear evaluation pipeline using an MMV model and LinearSVC classifier', 'compute top1 and top5 accuracy metrics from prediction and ground truth numpy arrays', 'extract video features from input frames using a TensorFlow Hub MMV model signature', 'collect feature vectors and labels from a TensorFlow dataset by iterating examples', 'train a sklearn LinearSVC classifier on extracted video features with StandardScaler normalization']
```

Usage

```
{'generate_tfrecords_from_csv': 'run the script to generate TFRecords of SequenceExample from raw videos listed in a CSV file', 'extract_frames_from_video': 'extract a list of JPEG bytes from a video file between start and end timestamps using ffmpeg', 'extract_audio_from_video': 'extract raw mono audio as a float list from a video file using ffmpeg', 'generate_sequence_example': 'generate a TensorFlow SequenceExample with encoded frames, audio, labels, and metadata from a video clip', 'add_bytes_list_to_sequence': 'add a bytes list feature to a TensorFlow SequenceExample feature list by key'}
```

## File: google-deepmind_dmvr/examples/linear_mmv_hmdb.py

Prompts

```
['run the script to generate TFRecords of SequenceExample from raw videos listed in a CSV file', 'extract a list of JPEG bytes from a video file between start and end timestamps using ffmpeg', 'extract raw mono audio as a float list from a video file using ffmpeg', 'generate a TensorFlow SequenceExample with encoded frames, audio, labels, and metadata from a video clip', 'add a bytes list feature to a TensorFlow SequenceExample feature list by key', 'run the HMDB51 linear evaluation pipeline using an MMV model and LinearSVC classifier', 'compute top1 and top5 accuracy metrics from prediction and ground truth numpy arrays', 'extract video features from input frames using a TensorFlow Hub MMV model signature', 'collect feature vectors and labels from a TensorFlow dataset by iterating examples', 'train a sklearn LinearSVC classifier on extracted video features with StandardScaler normalization']
```

Usage

```
{'run_linear_evaluation': 'run the HMDB51 linear evaluation pipeline using an MMV model and LinearSVC classifier', 'compute_accuracy_metrics': 'compute top1 and top5 accuracy metrics from prediction and ground truth numpy arrays', 'extract_video_features': 'extract video features from input frames using a TensorFlow Hub MMV model signature', 'collect_dataset_features': 'collect feature vectors and labels from a TensorFlow dataset by iterating examples', 'train_linear_classifier': 'train a sklearn LinearSVC classifier on extracted video features with StandardScaler normalization'}
```

