# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/hubert/simple_kmeans/dump_hubert_feature.py

Prompts

```
['run the CLI to dump HuBERT features from audio files listed in a TSV to numpy arrays', 'create a HubertFeatureReader instance to extract features from audio using a HuBERT checkpoint and layer', 'run get_feats on a HubertFeatureReader to extract HuBERT features from a single audio file path', 'run read_audio on a HubertFeatureReader to load and normalize an audio WAV file to a 1D numpy array', 'run get_path_iterator to shard a TSV file of audio paths across multiple ranks for parallel processing', 'run the CLI to dump HuBERT features from speech-to-text zip archives using a checkpoint and TSV manifest', 'run the dump_feature function to extract HuBERT features from audio paths listed in a TSV file', 'create a HubertFeatureReaderS2T subclass that reads audio from uncompressed zip archives using offset and size metadata', 'review the read_audio method that extracts waveforms from zip archives and normalizes stereo to mono', 'run the script to dump kmeans labels for audio features from a feature directory', 'run the ApplyKmeans class to predict cluster labels for audio feature vectors', 'run the feature iterator to load and iterate over sharded audio feature files', 'run the dump_label function to apply kmeans clustering and save labels to a file', 'review the ApplyKmeans class which loads a kmeans model and predicts cluster assignments for features', 'run the script to dump MFCC features from audio files listed in a TSV shard', 'create an MfccFeatureReader instance with a sample rate to extract MFCC features from audio', 'run get_feats on an audio file path to extract MFCC, delta, and double-delta features', 'run dump_feature to extract and save MFCC features for a TSV shard to an output directory', 'run k-means clustering on HUBERT feature shards and save the model to disk', 'run k-means clustering on a sampled subset of HUBERT features using the percent flag', 'run k-means clustering with custom batch size, max iterations, and tolerance parameters', 'review the learn_kmeans function that loads features, fits MiniBatchKMeans, and dumps the model', 'review the get_km_model function that configures and returns a MiniBatchKMeans instance']
```

Usage

```
{'run_dump_hubert_feature': 'run the CLI to dump HuBERT features from audio files listed in a TSV to numpy arrays', 'create_HubertFeatureReader': 'create a HubertFeatureReader instance to extract features from audio using a HuBERT checkpoint and layer', 'run_HubertFeatureReader_get_feats': 'run get_feats on a HubertFeatureReader to extract HuBERT features from a single audio file path', 'run_HubertFeatureReader_read_audio': 'run read_audio on a HubertFeatureReader to load and normalize an audio WAV file to a 1D numpy array', 'run_get_path_iterator': 'run get_path_iterator to shard a TSV file of audio paths across multiple ranks for parallel processing'}
```

## File: facebookresearch_avhubert/fairseq/examples/hubert/simple_kmeans/dump_hubert_feature_s2t.py

Prompts

```
['run the CLI to dump HuBERT features from audio files listed in a TSV to numpy arrays', 'create a HubertFeatureReader instance to extract features from audio using a HuBERT checkpoint and layer', 'run get_feats on a HubertFeatureReader to extract HuBERT features from a single audio file path', 'run read_audio on a HubertFeatureReader to load and normalize an audio WAV file to a 1D numpy array', 'run get_path_iterator to shard a TSV file of audio paths across multiple ranks for parallel processing', 'run the CLI to dump HuBERT features from speech-to-text zip archives using a checkpoint and TSV manifest', 'run the dump_feature function to extract HuBERT features from audio paths listed in a TSV file', 'create a HubertFeatureReaderS2T subclass that reads audio from uncompressed zip archives using offset and size metadata', 'review the read_audio method that extracts waveforms from zip archives and normalizes stereo to mono', 'run the script to dump kmeans labels for audio features from a feature directory', 'run the ApplyKmeans class to predict cluster labels for audio feature vectors', 'run the feature iterator to load and iterate over sharded audio feature files', 'run the dump_label function to apply kmeans clustering and save labels to a file', 'review the ApplyKmeans class which loads a kmeans model and predicts cluster assignments for features', 'run the script to dump MFCC features from audio files listed in a TSV shard', 'create an MfccFeatureReader instance with a sample rate to extract MFCC features from audio', 'run get_feats on an audio file path to extract MFCC, delta, and double-delta features', 'run dump_feature to extract and save MFCC features for a TSV shard to an output directory', 'run k-means clustering on HUBERT feature shards and save the model to disk', 'run k-means clustering on a sampled subset of HUBERT features using the percent flag', 'run k-means clustering with custom batch size, max iterations, and tolerance parameters', 'review the learn_kmeans function that loads features, fits MiniBatchKMeans, and dumps the model', 'review the get_km_model function that configures and returns a MiniBatchKMeans instance']
```

Usage

```
{'run_dump_hubert_feature_s2t_cli': 'run the CLI to dump HuBERT features from speech-to-text zip archives using a checkpoint and TSV manifest', 'run_dump_feature_function': 'run the dump_feature function to extract HuBERT features from audio paths listed in a TSV file', 'create_HubertFeatureReaderS2T_class': 'create a HubertFeatureReaderS2T subclass that reads audio from uncompressed zip archives using offset and size metadata', 'run_get_path_iterator': 'run get_path_iterator to shard a TSV manifest into per-rank audio path iterators for distributed feature extraction', 'review_HubertFeatureReaderS2T_read_audio': 'review the read_audio method that extracts waveforms from zip archives and normalizes stereo to mono'}
```

## File: facebookresearch_avhubert/fairseq/examples/hubert/simple_kmeans/dump_km_label.py

Prompts

```
['run the CLI to dump HuBERT features from audio files listed in a TSV to numpy arrays', 'create a HubertFeatureReader instance to extract features from audio using a HuBERT checkpoint and layer', 'run get_feats on a HubertFeatureReader to extract HuBERT features from a single audio file path', 'run read_audio on a HubertFeatureReader to load and normalize an audio WAV file to a 1D numpy array', 'run get_path_iterator to shard a TSV file of audio paths across multiple ranks for parallel processing', 'run the CLI to dump HuBERT features from speech-to-text zip archives using a checkpoint and TSV manifest', 'run the dump_feature function to extract HuBERT features from audio paths listed in a TSV file', 'create a HubertFeatureReaderS2T subclass that reads audio from uncompressed zip archives using offset and size metadata', 'review the read_audio method that extracts waveforms from zip archives and normalizes stereo to mono', 'run the script to dump kmeans labels for audio features from a feature directory', 'run the ApplyKmeans class to predict cluster labels for audio feature vectors', 'run the feature iterator to load and iterate over sharded audio feature files', 'run the dump_label function to apply kmeans clustering and save labels to a file', 'review the ApplyKmeans class which loads a kmeans model and predicts cluster assignments for features', 'run the script to dump MFCC features from audio files listed in a TSV shard', 'create an MfccFeatureReader instance with a sample rate to extract MFCC features from audio', 'run get_feats on an audio file path to extract MFCC, delta, and double-delta features', 'run dump_feature to extract and save MFCC features for a TSV shard to an output directory', 'run k-means clustering on HUBERT feature shards and save the model to disk', 'run k-means clustering on a sampled subset of HUBERT features using the percent flag', 'run k-means clustering with custom batch size, max iterations, and tolerance parameters', 'review the learn_kmeans function that loads features, fits MiniBatchKMeans, and dumps the model', 'review the get_km_model function that configures and returns a MiniBatchKMeans instance']
```

Usage

```
{'run_dump_km_label': 'run the script to dump kmeans labels for audio features from a feature directory', 'run_ApplyKmeans': 'run the ApplyKmeans class to predict cluster labels for audio feature vectors', 'run_get_feat_iterator': 'run the feature iterator to load and iterate over sharded audio feature files', 'run_dump_label': 'run the dump_label function to apply kmeans clustering and save labels to a file', 'review_ApplyKmeans': 'review the ApplyKmeans class which loads a kmeans model and predicts cluster assignments for features'}
```

## File: facebookresearch_avhubert/fairseq/examples/hubert/simple_kmeans/dump_mfcc_feature.py

Prompts

```
['run the CLI to dump HuBERT features from audio files listed in a TSV to numpy arrays', 'create a HubertFeatureReader instance to extract features from audio using a HuBERT checkpoint and layer', 'run get_feats on a HubertFeatureReader to extract HuBERT features from a single audio file path', 'run read_audio on a HubertFeatureReader to load and normalize an audio WAV file to a 1D numpy array', 'run get_path_iterator to shard a TSV file of audio paths across multiple ranks for parallel processing', 'run the CLI to dump HuBERT features from speech-to-text zip archives using a checkpoint and TSV manifest', 'run the dump_feature function to extract HuBERT features from audio paths listed in a TSV file', 'create a HubertFeatureReaderS2T subclass that reads audio from uncompressed zip archives using offset and size metadata', 'review the read_audio method that extracts waveforms from zip archives and normalizes stereo to mono', 'run the script to dump kmeans labels for audio features from a feature directory', 'run the ApplyKmeans class to predict cluster labels for audio feature vectors', 'run the feature iterator to load and iterate over sharded audio feature files', 'run the dump_label function to apply kmeans clustering and save labels to a file', 'review the ApplyKmeans class which loads a kmeans model and predicts cluster assignments for features', 'run the script to dump MFCC features from audio files listed in a TSV shard', 'create an MfccFeatureReader instance with a sample rate to extract MFCC features from audio', 'run get_feats on an audio file path to extract MFCC, delta, and double-delta features', 'run dump_feature to extract and save MFCC features for a TSV shard to an output directory', 'run k-means clustering on HUBERT feature shards and save the model to disk', 'run k-means clustering on a sampled subset of HUBERT features using the percent flag', 'run k-means clustering with custom batch size, max iterations, and tolerance parameters', 'review the learn_kmeans function that loads features, fits MiniBatchKMeans, and dumps the model', 'review the get_km_model function that configures and returns a MiniBatchKMeans instance']
```

Usage

```
{'run_dump_mfcc_features': 'run the script to dump MFCC features from audio files listed in a TSV shard', 'create_MfccFeatureReader': 'create an MfccFeatureReader instance with a sample rate to extract MFCC features from audio', 'run_get_feats': 'run get_feats on an audio file path to extract MFCC, delta, and double-delta features', 'run_get_path_iterator': 'run get_path_iterator on a TSV file with nshard and rank to shard audio file paths', 'run_dump_feature': 'run dump_feature to extract and save MFCC features for a TSV shard to an output directory'}
```

## File: facebookresearch_avhubert/fairseq/examples/hubert/simple_kmeans/learn_kmeans.py

Prompts

```
['run the CLI to dump HuBERT features from audio files listed in a TSV to numpy arrays', 'create a HubertFeatureReader instance to extract features from audio using a HuBERT checkpoint and layer', 'run get_feats on a HubertFeatureReader to extract HuBERT features from a single audio file path', 'run read_audio on a HubertFeatureReader to load and normalize an audio WAV file to a 1D numpy array', 'run get_path_iterator to shard a TSV file of audio paths across multiple ranks for parallel processing', 'run the CLI to dump HuBERT features from speech-to-text zip archives using a checkpoint and TSV manifest', 'run the dump_feature function to extract HuBERT features from audio paths listed in a TSV file', 'create a HubertFeatureReaderS2T subclass that reads audio from uncompressed zip archives using offset and size metadata', 'review the read_audio method that extracts waveforms from zip archives and normalizes stereo to mono', 'run the script to dump kmeans labels for audio features from a feature directory', 'run the ApplyKmeans class to predict cluster labels for audio feature vectors', 'run the feature iterator to load and iterate over sharded audio feature files', 'run the dump_label function to apply kmeans clustering and save labels to a file', 'review the ApplyKmeans class which loads a kmeans model and predicts cluster assignments for features', 'run the script to dump MFCC features from audio files listed in a TSV shard', 'create an MfccFeatureReader instance with a sample rate to extract MFCC features from audio', 'run get_feats on an audio file path to extract MFCC, delta, and double-delta features', 'run dump_feature to extract and save MFCC features for a TSV shard to an output directory', 'run k-means clustering on HUBERT feature shards and save the model to disk', 'run k-means clustering on a sampled subset of HUBERT features using the percent flag', 'run k-means clustering with custom batch size, max iterations, and tolerance parameters', 'review the learn_kmeans function that loads features, fits MiniBatchKMeans, and dumps the model', 'review the get_km_model function that configures and returns a MiniBatchKMeans instance']
```

Usage

```
{'run_kmeans_clustering': 'run k-means clustering on HUBERT feature shards and save the model to disk', 'run_kmeans_with_subset': 'run k-means clustering on a sampled subset of HUBERT features using the percent flag', 'run_kmeans_custom_params': 'run k-means clustering with custom batch size, max iterations, and tolerance parameters', 'review_learn_kmeans': 'review the learn_kmeans function that loads features, fits MiniBatchKMeans, and dumps the model', 'review_get_km_model': 'review the get_km_model function that configures and returns a MiniBatchKMeans instance'}
```

