# Agent Python Tools

- repo: facebookresearch/spiritlm
- repo_uri: https://github.com/facebookresearch/spiritlm

## File: facebookresearch_spiritlm/spiritlm/speech_tokenizer/hubert/hubert_tokenizer.py

Prompts

```
['create a HubertTokenizer instance with hubert and quantizer checkpoint paths to tokenize speech audio', 'run the HubertTokenizer forward pass on audio tensors or file paths to extract discrete speech tokens', 'extract dense continuous features from audio using the HubertTokenizer get_dense_features method', 'load an audio file and resample it to the expected sample rate using the load_audio method', 'review the HubertTokenizer class to understand its chunking, normalization, and quantization pipeline', 'load a quantizer model from a checkpoint path choosing between LinearQuantizer and KmeansModel', 'create a LinearQuantizerModel that maps upstream features to discrete codes using a trained encoder', 'create a KmeansModel that assigns input features to nearest cluster centers from a checkpoint', 'run the LinearQuantizerModel forward pass to convert feature embeddings into discrete token codes', 'run the KmeansModel forward pass to assign batched or unbatched features to cluster indices']
```

Usage

```
{'create_hubert_tokenizer': 'create a HubertTokenizer instance with hubert and quantizer checkpoint paths to tokenize speech audio', 'run_forward_tokenization': 'run the HubertTokenizer forward pass on audio tensors or file paths to extract discrete speech tokens', 'extract_dense_features': 'extract dense continuous features from audio using the HubertTokenizer get_dense_features method', 'load_audio_resample': 'load an audio file and resample it to the expected sample rate using the load_audio method', 'review_hubert_tokenizer_class': 'review the HubertTokenizer class to understand its chunking, normalization, and quantization pipeline'}
```

## File: facebookresearch_spiritlm/spiritlm/speech_tokenizer/hubert/quantizer_model.py

Prompts

```
['create a HubertTokenizer instance with hubert and quantizer checkpoint paths to tokenize speech audio', 'run the HubertTokenizer forward pass on audio tensors or file paths to extract discrete speech tokens', 'extract dense continuous features from audio using the HubertTokenizer get_dense_features method', 'load an audio file and resample it to the expected sample rate using the load_audio method', 'review the HubertTokenizer class to understand its chunking, normalization, and quantization pipeline', 'load a quantizer model from a checkpoint path choosing between LinearQuantizer and KmeansModel', 'create a LinearQuantizerModel that maps upstream features to discrete codes using a trained encoder', 'create a KmeansModel that assigns input features to nearest cluster centers from a checkpoint', 'run the LinearQuantizerModel forward pass to convert feature embeddings into discrete token codes', 'run the KmeansModel forward pass to assign batched or unbatched features to cluster indices']
```

Usage

```
{'load_quantizer_model': 'load a quantizer model from a checkpoint path choosing between LinearQuantizer and KmeansModel', 'create_linear_quantizer': 'create a LinearQuantizerModel that maps upstream features to discrete codes using a trained encoder', 'create_kmeans_model': 'create a KmeansModel that assigns input features to nearest cluster centers from a checkpoint', 'run_linear_quantizer_forward': 'run the LinearQuantizerModel forward pass to convert feature embeddings into discrete token codes', 'run_kmeans_forward': 'run the KmeansModel forward pass to assign batched or unbatched features to cluster indices'}
```

