# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/eval/vocal_style_similarity/ecapa.py

Prompts

```
['build a speaker embedding extractor using ECAPA-TDNN by instantiating Ecapa with a checkpoint path', 'create an ECAPA-TDNN neural network model with configurable channel width C for speaker verification', 'test the Bottle2neck residual block forward pass with SE attention on 1D feature tensors', 'review the SEModule squeeze-and-excitation attention mechanism for channel-wise feature recalibration', 'refactor the FbankAug spectrogram augmentation to apply frequency and time masking on mel-spectrogram tensors', 'build a ValleEncoder to extract speaker embeddings from a list of audio file paths using wavlm_large', 'create an ECAPA_TDNN_SMALL model with fbank features and 256 dimensional embeddings for speaker verification', 'run init_model to load a wavlm_large ECAPA-TDNN model from a checkpoint file for voice embeddings', 'test the ValleEncoder forward pass by passing a list of audio paths and verifying embedding output shape', 'review the ECAPA_TDNN forward method to understand how audio features flow through Res2Blocks and attentive pooling', 'run the VocalStyleSimilarityModule to compute cosine similarity scores between source and target audio files', 'create a VocalStyleSimilarityConfig dataclass with input file paths, output file, model type, and model path', 'review the VocalStyleSimilarityModule class that extends StopesModule for vocal style similarity evaluation', 'build a pipeline using VocalStyleSimilarityModule to embed audio files and compute cosine similarity scores', 'validate the VocalStyleSimilarityModule output by checking if the output file exists after processing', 'get an ecapa vocal style embedder model from a given model path using get_embedder', 'get a valle vocal style embedder model from a given model path using get_embedder', 'compute cosine similarity between two batches of embedding vectors using compute_cosine_similarity', 'review the get_embedder factory function that returns ecapa or valle vocal embedder models', 'review the compute_cosine_similarity function that calculates batch-wise cosine similarity on numpy arrays']
```

Usage

```
{'build_speaker_embedding_extractor': 'build a speaker embedding extractor using ECAPA-TDNN by instantiating Ecapa with a checkpoint path', 'create_ecapa_tdnn_model': 'create an ECAPA-TDNN neural network model with configurable channel width C for speaker verification', 'test_Bottle2neck_forward': 'test the Bottle2neck residual block forward pass with SE attention on 1D feature tensors', 'review_SEModule_attention': 'review the SEModule squeeze-and-excitation attention mechanism for channel-wise feature recalibration', 'refactor_FbankAug_masking': 'refactor the FbankAug spectrogram augmentation to apply frequency and time masking on mel-spectrogram tensors'}
```

## File: facebookresearch_stopes/stopes/eval/vocal_style_similarity/valle_sv.py

Prompts

```
['build a speaker embedding extractor using ECAPA-TDNN by instantiating Ecapa with a checkpoint path', 'create an ECAPA-TDNN neural network model with configurable channel width C for speaker verification', 'test the Bottle2neck residual block forward pass with SE attention on 1D feature tensors', 'review the SEModule squeeze-and-excitation attention mechanism for channel-wise feature recalibration', 'refactor the FbankAug spectrogram augmentation to apply frequency and time masking on mel-spectrogram tensors', 'build a ValleEncoder to extract speaker embeddings from a list of audio file paths using wavlm_large', 'create an ECAPA_TDNN_SMALL model with fbank features and 256 dimensional embeddings for speaker verification', 'run init_model to load a wavlm_large ECAPA-TDNN model from a checkpoint file for voice embeddings', 'test the ValleEncoder forward pass by passing a list of audio paths and verifying embedding output shape', 'review the ECAPA_TDNN forward method to understand how audio features flow through Res2Blocks and attentive pooling', 'run the VocalStyleSimilarityModule to compute cosine similarity scores between source and target audio files', 'create a VocalStyleSimilarityConfig dataclass with input file paths, output file, model type, and model path', 'review the VocalStyleSimilarityModule class that extends StopesModule for vocal style similarity evaluation', 'build a pipeline using VocalStyleSimilarityModule to embed audio files and compute cosine similarity scores', 'validate the VocalStyleSimilarityModule output by checking if the output file exists after processing', 'get an ecapa vocal style embedder model from a given model path using get_embedder', 'get a valle vocal style embedder model from a given model path using get_embedder', 'compute cosine similarity between two batches of embedding vectors using compute_cosine_similarity', 'review the get_embedder factory function that returns ecapa or valle vocal embedder models', 'review the compute_cosine_similarity function that calculates batch-wise cosine similarity on numpy arrays']
```

Usage

```
{'build_ValleEncoder': 'build a ValleEncoder to extract speaker embeddings from a list of audio file paths using wavlm_large', 'create_ECAPA_TDNN_SMALL': 'create an ECAPA_TDNN_SMALL model with fbank features and 256 dimensional embeddings for speaker verification', 'run_init_model': 'run init_model to load a wavlm_large ECAPA-TDNN model from a checkpoint file for voice embeddings', 'test_ValleEncoder_forward': 'test the ValleEncoder forward pass by passing a list of audio paths and verifying embedding output shape', 'review_ECAPA_TDNN_forward': 'review the ECAPA_TDNN forward method to understand how audio features flow through Res2Blocks and attentive pooling'}
```

## File: facebookresearch_stopes/stopes/eval/vocal_style_similarity/vocal_style_sim_module.py

Prompts

```
['build a speaker embedding extractor using ECAPA-TDNN by instantiating Ecapa with a checkpoint path', 'create an ECAPA-TDNN neural network model with configurable channel width C for speaker verification', 'test the Bottle2neck residual block forward pass with SE attention on 1D feature tensors', 'review the SEModule squeeze-and-excitation attention mechanism for channel-wise feature recalibration', 'refactor the FbankAug spectrogram augmentation to apply frequency and time masking on mel-spectrogram tensors', 'build a ValleEncoder to extract speaker embeddings from a list of audio file paths using wavlm_large', 'create an ECAPA_TDNN_SMALL model with fbank features and 256 dimensional embeddings for speaker verification', 'run init_model to load a wavlm_large ECAPA-TDNN model from a checkpoint file for voice embeddings', 'test the ValleEncoder forward pass by passing a list of audio paths and verifying embedding output shape', 'review the ECAPA_TDNN forward method to understand how audio features flow through Res2Blocks and attentive pooling', 'run the VocalStyleSimilarityModule to compute cosine similarity scores between source and target audio files', 'create a VocalStyleSimilarityConfig dataclass with input file paths, output file, model type, and model path', 'review the VocalStyleSimilarityModule class that extends StopesModule for vocal style similarity evaluation', 'build a pipeline using VocalStyleSimilarityModule to embed audio files and compute cosine similarity scores', 'validate the VocalStyleSimilarityModule output by checking if the output file exists after processing', 'get an ecapa vocal style embedder model from a given model path using get_embedder', 'get a valle vocal style embedder model from a given model path using get_embedder', 'compute cosine similarity between two batches of embedding vectors using compute_cosine_similarity', 'review the get_embedder factory function that returns ecapa or valle vocal embedder models', 'review the compute_cosine_similarity function that calculates batch-wise cosine similarity on numpy arrays']
```

Usage

```
{'run_vocal_style_similarity': 'run the VocalStyleSimilarityModule to compute cosine similarity scores between source and target audio files', 'create_vocal_style_config': 'create a VocalStyleSimilarityConfig dataclass with input file paths, output file, model type, and model path', 'review_vocal_style_module': 'review the VocalStyleSimilarityModule class that extends StopesModule for vocal style similarity evaluation', 'build_similarity_pipeline': 'build a pipeline using VocalStyleSimilarityModule to embed audio files and compute cosine similarity scores', 'validate_similarity_output': 'validate the VocalStyleSimilarityModule output by checking if the output file exists after processing'}
```

## File: facebookresearch_stopes/stopes/eval/vocal_style_similarity/vocal_style_sim_tool.py

Prompts

```
['build a speaker embedding extractor using ECAPA-TDNN by instantiating Ecapa with a checkpoint path', 'create an ECAPA-TDNN neural network model with configurable channel width C for speaker verification', 'test the Bottle2neck residual block forward pass with SE attention on 1D feature tensors', 'review the SEModule squeeze-and-excitation attention mechanism for channel-wise feature recalibration', 'refactor the FbankAug spectrogram augmentation to apply frequency and time masking on mel-spectrogram tensors', 'build a ValleEncoder to extract speaker embeddings from a list of audio file paths using wavlm_large', 'create an ECAPA_TDNN_SMALL model with fbank features and 256 dimensional embeddings for speaker verification', 'run init_model to load a wavlm_large ECAPA-TDNN model from a checkpoint file for voice embeddings', 'test the ValleEncoder forward pass by passing a list of audio paths and verifying embedding output shape', 'review the ECAPA_TDNN forward method to understand how audio features flow through Res2Blocks and attentive pooling', 'run the VocalStyleSimilarityModule to compute cosine similarity scores between source and target audio files', 'create a VocalStyleSimilarityConfig dataclass with input file paths, output file, model type, and model path', 'review the VocalStyleSimilarityModule class that extends StopesModule for vocal style similarity evaluation', 'build a pipeline using VocalStyleSimilarityModule to embed audio files and compute cosine similarity scores', 'validate the VocalStyleSimilarityModule output by checking if the output file exists after processing', 'get an ecapa vocal style embedder model from a given model path using get_embedder', 'get a valle vocal style embedder model from a given model path using get_embedder', 'compute cosine similarity between two batches of embedding vectors using compute_cosine_similarity', 'review the get_embedder factory function that returns ecapa or valle vocal embedder models', 'review the compute_cosine_similarity function that calculates batch-wise cosine similarity on numpy arrays']
```

Usage

```
{'get_embedder_ecapa': 'get an ecapa vocal style embedder model from a given model path using get_embedder', 'get_embedder_valle': 'get a valle vocal style embedder model from a given model path using get_embedder', 'compute_cosine_similarity_batch': 'compute cosine similarity between two batches of embedding vectors using compute_cosine_similarity', 'review_get_embedder': 'review the get_embedder factory function that returns ecapa or valle vocal embedder models', 'review_compute_cosine_similarity': 'review the compute_cosine_similarity function that calculates batch-wise cosine similarity on numpy arrays'}
```

