# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/textless_nlp/gslm/speech2unit/clustering/cluster_kmeans.py

Prompts

```
['run k-means clustering over acoustic features extracted from a manifest file', 'run k-means clustering on pre-loaded numpy feature arrays saved to disk', 'run k-means clustering using HuBERT features extracted from a pretrained checkpoint', 'create a MiniBatchKMeans model with configurable clusters, batch size, and initialization', 'train a k-means model on a batch of acoustic features and return timing', 'run the script to extract logmel hubert w2v2 or cpc acoustic features from audio files in a manifest', 'run the CLI tool with a manifest path and output path to dump flattened acoustic features to a numpy file', 'review the get_parser function that builds an argparse parser for acoustic feature extraction with logmel hubert w2v2 and cpc types', 'review the imported get_and_dump_features function that extracts features from audio files and saves them to a numpy file', 'refactor the get_logger function to customize the logging format or log level for the feature extraction script', 'run kmeans clustering to quantize acoustic features from audio files into discrete units', 'run kmeans quantization on pre-extracted numpy features without re-extracting acoustic features', 'run kmeans quantization using hubert features extracted from a pretrained acoustic model', 'run kmeans quantization on a specific channel of stereo audio files', 'run kmeans quantization and output predictions without file names in the output', 'parse a tab-separated manifest file to extract audio filenames and sizes', 'review the get_audio_files function that reads manifest files for audio clustering', 'test the get_audio_files function with a sample manifest file', 'refactor get_audio_files to support additional manifest column formats', 'summarize the get_audio_files function used for speech-to-unit clustering utilities']
```

Usage

```
{'run_kmeans_clustering': 'run k-means clustering over acoustic features extracted from a manifest file', 'run_kmeans_from_features': 'run k-means clustering on pre-loaded numpy feature arrays saved to disk', 'run_kmeans_with_hubert': 'run k-means clustering using HuBERT features extracted from a pretrained checkpoint', 'get_kmeans_model': 'create a MiniBatchKMeans model with configurable clusters, batch size, and initialization', 'train_kmeans': 'train a k-means model on a batch of acoustic features and return timing'}
```

## File: facebookresearch_fairseq/examples/textless_nlp/gslm/speech2unit/clustering/dump_feats.py

Prompts

```
['run k-means clustering over acoustic features extracted from a manifest file', 'run k-means clustering on pre-loaded numpy feature arrays saved to disk', 'run k-means clustering using HuBERT features extracted from a pretrained checkpoint', 'create a MiniBatchKMeans model with configurable clusters, batch size, and initialization', 'train a k-means model on a batch of acoustic features and return timing', 'run the script to extract logmel hubert w2v2 or cpc acoustic features from audio files in a manifest', 'run the CLI tool with a manifest path and output path to dump flattened acoustic features to a numpy file', 'review the get_parser function that builds an argparse parser for acoustic feature extraction with logmel hubert w2v2 and cpc types', 'review the imported get_and_dump_features function that extracts features from audio files and saves them to a numpy file', 'refactor the get_logger function to customize the logging format or log level for the feature extraction script', 'run kmeans clustering to quantize acoustic features from audio files into discrete units', 'run kmeans quantization on pre-extracted numpy features without re-extracting acoustic features', 'run kmeans quantization using hubert features extracted from a pretrained acoustic model', 'run kmeans quantization on a specific channel of stereo audio files', 'run kmeans quantization and output predictions without file names in the output', 'parse a tab-separated manifest file to extract audio filenames and sizes', 'review the get_audio_files function that reads manifest files for audio clustering', 'test the get_audio_files function with a sample manifest file', 'refactor get_audio_files to support additional manifest column formats', 'summarize the get_audio_files function used for speech-to-unit clustering utilities']
```

Usage

```
{'run_dump_acoustic_features': 'run the script to extract logmel hubert w2v2 or cpc acoustic features from audio files in a manifest', 'run_feature_extraction_cli': 'run the CLI tool with a manifest path and output path to dump flattened acoustic features to a numpy file', 'review_get_parser': 'review the get_parser function that builds an argparse parser for acoustic feature extraction with logmel hubert w2v2 and cpc types', 'review_get_and_dump_features': 'review the imported get_and_dump_features function that extracts features from audio files and saves them to a numpy file', 'refactor_get_logger': 'refactor the get_logger function to customize the logging format or log level for the feature extraction script'}
```

## File: facebookresearch_fairseq/examples/textless_nlp/gslm/speech2unit/clustering/quantize_with_kmeans.py

Prompts

```
['run k-means clustering over acoustic features extracted from a manifest file', 'run k-means clustering on pre-loaded numpy feature arrays saved to disk', 'run k-means clustering using HuBERT features extracted from a pretrained checkpoint', 'create a MiniBatchKMeans model with configurable clusters, batch size, and initialization', 'train a k-means model on a batch of acoustic features and return timing', 'run the script to extract logmel hubert w2v2 or cpc acoustic features from audio files in a manifest', 'run the CLI tool with a manifest path and output path to dump flattened acoustic features to a numpy file', 'review the get_parser function that builds an argparse parser for acoustic feature extraction with logmel hubert w2v2 and cpc types', 'review the imported get_and_dump_features function that extracts features from audio files and saves them to a numpy file', 'refactor the get_logger function to customize the logging format or log level for the feature extraction script', 'run kmeans clustering to quantize acoustic features from audio files into discrete units', 'run kmeans quantization on pre-extracted numpy features without re-extracting acoustic features', 'run kmeans quantization using hubert features extracted from a pretrained acoustic model', 'run kmeans quantization on a specific channel of stereo audio files', 'run kmeans quantization and output predictions without file names in the output', 'parse a tab-separated manifest file to extract audio filenames and sizes', 'review the get_audio_files function that reads manifest files for audio clustering', 'test the get_audio_files function with a sample manifest file', 'refactor get_audio_files to support additional manifest column formats', 'summarize the get_audio_files function used for speech-to-unit clustering utilities']
```

Usage

```
{'run_kmeans_quantize': 'run kmeans clustering to quantize acoustic features from audio files into discrete units', 'run_quantize_from_features': 'run kmeans quantization on pre-extracted numpy features without re-extracting acoustic features', 'run_quantize_hubert': 'run kmeans quantization using hubert features extracted from a pretrained acoustic model', 'run_quantize_stereo_channel': 'run kmeans quantization on a specific channel of stereo audio files', 'run_quantize_hide_fname': 'run kmeans quantization and output predictions without file names in the output'}
```

## File: facebookresearch_fairseq/examples/textless_nlp/gslm/speech2unit/clustering/utils.py

Prompts

```
['run k-means clustering over acoustic features extracted from a manifest file', 'run k-means clustering on pre-loaded numpy feature arrays saved to disk', 'run k-means clustering using HuBERT features extracted from a pretrained checkpoint', 'create a MiniBatchKMeans model with configurable clusters, batch size, and initialization', 'train a k-means model on a batch of acoustic features and return timing', 'run the script to extract logmel hubert w2v2 or cpc acoustic features from audio files in a manifest', 'run the CLI tool with a manifest path and output path to dump flattened acoustic features to a numpy file', 'review the get_parser function that builds an argparse parser for acoustic feature extraction with logmel hubert w2v2 and cpc types', 'review the imported get_and_dump_features function that extracts features from audio files and saves them to a numpy file', 'refactor the get_logger function to customize the logging format or log level for the feature extraction script', 'run kmeans clustering to quantize acoustic features from audio files into discrete units', 'run kmeans quantization on pre-extracted numpy features without re-extracting acoustic features', 'run kmeans quantization using hubert features extracted from a pretrained acoustic model', 'run kmeans quantization on a specific channel of stereo audio files', 'run kmeans quantization and output predictions without file names in the output', 'parse a tab-separated manifest file to extract audio filenames and sizes', 'review the get_audio_files function that reads manifest files for audio clustering', 'test the get_audio_files function with a sample manifest file', 'refactor get_audio_files to support additional manifest column formats', 'summarize the get_audio_files function used for speech-to-unit clustering utilities']
```

Usage

```
{'get_audio_files': 'parse a tab-separated manifest file to extract audio filenames and sizes', 'review_get_audio_files': 'review the get_audio_files function that reads manifest files for audio clustering', 'test_get_audio_files': 'test the get_audio_files function with a sample manifest file', 'refactor_get_audio_files': 'refactor get_audio_files to support additional manifest column formats', 'summarize_get_audio_files': 'summarize the get_audio_files function used for speech-to-unit clustering utilities'}
```

