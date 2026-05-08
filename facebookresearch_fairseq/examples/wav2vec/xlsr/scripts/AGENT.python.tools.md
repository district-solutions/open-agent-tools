# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/wav2vec/xlsr/scripts/eval_speaker_clf_task.py

Prompts

```
['run speaker classification evaluation on an NPZ file with logits using mean or first logit merge strategy', 'run speaker verification evaluation on audio embeddings using cosine similarity and a verification pair file', 'calculate the equal error rate and optimal threshold from ground truth labels and prediction scores', 'calculate the minimum detection cost function and its threshold from labels and scores with configurable costs', 'apply StandardScaler and PCA dimensionality reduction to audio latent embeddings before verification evaluation', 'run the script to extract audio embeddings and logits from a wav2vec model checkpoint for speech classification', 'run the script with a verification pair file to subset the manifest for speaker verification evaluation', 'run inference with multiple random crops using --infer-xtimes to extract augmented audio embeddings', 'create a subset manifest from a verification pair file filtering utterances needed for speaker verification', 'wrap a FileAudioDataset with target labels from a .label file using AddTargetDataset and LabelEncoder', 'resample audio source tensors with random cropping and padding to a fixed max sample length multiple times', 'resample a fairseq sample dict by cropping audio features and returning multiple augmented sample copies', 'review the main inference loop that batches audio samples, extracts latents and logits, and saves results to npz', 'review how the script loads a wav2vec checkpoint, overrides paths, and sets up the audio classification task']
```

Usage

```
{'run_classification_evaluation': 'run speaker classification evaluation on an NPZ file with logits using mean or first logit merge strategy', 'run_verification_evaluation': 'run speaker verification evaluation on audio embeddings using cosine similarity and a verification pair file', 'calculate_eer': 'calculate the equal error rate and optimal threshold from ground truth labels and prediction scores', 'calculate_minDCF': 'calculate the minimum detection cost function and its threshold from labels and scores with configurable costs', 'apply_scaler_and_pca': 'apply StandardScaler and PCA dimensionality reduction to audio latent embeddings before verification evaluation'}
```

## File: facebookresearch_fairseq/examples/wav2vec/xlsr/scripts/gen_audio_embedding.py

Prompts

```
['run speaker classification evaluation on an NPZ file with logits using mean or first logit merge strategy', 'run speaker verification evaluation on audio embeddings using cosine similarity and a verification pair file', 'calculate the equal error rate and optimal threshold from ground truth labels and prediction scores', 'calculate the minimum detection cost function and its threshold from labels and scores with configurable costs', 'apply StandardScaler and PCA dimensionality reduction to audio latent embeddings before verification evaluation', 'run the script to extract audio embeddings and logits from a wav2vec model checkpoint for speech classification', 'run the script with a verification pair file to subset the manifest for speaker verification evaluation', 'run inference with multiple random crops using --infer-xtimes to extract augmented audio embeddings', 'create a subset manifest from a verification pair file filtering utterances needed for speaker verification', 'wrap a FileAudioDataset with target labels from a .label file using AddTargetDataset and LabelEncoder', 'resample audio source tensors with random cropping and padding to a fixed max sample length multiple times', 'resample a fairseq sample dict by cropping audio features and returning multiple augmented sample copies', 'review the main inference loop that batches audio samples, extracts latents and logits, and saves results to npz', 'review how the script loads a wav2vec checkpoint, overrides paths, and sets up the audio classification task']
```

Usage

```
{'run_audio_embedding_extraction': 'run the script to extract audio embeddings and logits from a wav2vec model checkpoint for speech classification', 'run_verification_pair_subset': 'run the script with a verification pair file to subset the manifest for speaker verification evaluation', 'run_multi_augmentation_inference': 'run inference with multiple random crops using --infer-xtimes to extract augmented audio embeddings', 'subset_manifest_function': 'create a subset manifest from a verification pair file filtering utterances needed for speaker verification', 'wrap_target_dataset_function': 'wrap a FileAudioDataset with target labels from a .label file using AddTargetDataset and LabelEncoder', 'resample_data_function': 'resample audio source tensors with random cropping and padding to a fixed max sample length multiple times', 'resample_sample_function': 'resample a fairseq sample dict by cropping audio features and returning multiple augmented sample copies', 'review_main_inference_loop': 'review the main inference loop that batches audio samples, extracts latents and logits, and saves results to npz', 'review_model_loading': 'review how the script loads a wav2vec checkpoint, overrides paths, and sets up the audio classification task'}
```

