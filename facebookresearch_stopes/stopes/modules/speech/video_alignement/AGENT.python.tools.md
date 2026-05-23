# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/modules/speech/video_alignement/video_segment_aligner.py

Prompts

```
['run the LocalAlignmentModule to align bilingual video segments and output aligned parquet dataset', 'configure LocalAlignmentConfig with dataset_root, output_dir, language_pairs, and similarity thresholds for video segment alignment', 'compute pairwise cosine similarity between text and speech embeddings of two segment tables', 'apply the Blaser quality estimation model in batch mode to score speech embedding pairs', 'filter candidate aligned segment pairs by gap, duration ratio, speech sim, text sim, and blaser score thresholds', 'run the WhisperSegmentorModule to extract utterances from audio files and generate parquet segment datasets', 'build a WhisperSegmentorConfig dataclass to configure shards, output directory, whisper model, and segment length parameters', 'compute SONAR speech embeddings for audio waveform segments using the SpeechToEmbeddingModelPipeline', 'compute text embeddings for transcribed segment text using a SentenceTransformer model like LaBSE', 'get audio transcription and word-level timestamps from an audio file using Whisper with word timestamp support', 'build a python module to compute optimal monotonic alignment from a pairwise similarity matrix using Needleman-Wunsch', 'build a sparse CSR connectivity matrix where each entry indicates if two time segments intersect', 'build a sparse CSR matrix where each entry indicates if one time segment contains another', 'generate n-gram pairs from a list of words with configurable min and max depth', 'convert a list of PyTorch WAV segment tensors into a chunked PyArrow array for efficient storage']
```

Usage

```
{'run_LocalAlignmentModule': 'run the LocalAlignmentModule to align bilingual video segments and output aligned parquet dataset', 'configure_LocalAlignmentConfig': 'configure LocalAlignmentConfig with dataset_root, output_dir, language_pairs, and similarity thresholds for video segment alignment', 'compute_similarity': 'compute pairwise cosine similarity between text and speech embeddings of two segment tables', 'apply_blaser_model': 'apply the Blaser quality estimation model in batch mode to score speech embedding pairs', 'filter_candidate_pairs': 'filter candidate aligned segment pairs by gap, duration ratio, speech sim, text sim, and blaser score thresholds'}
```

## File: facebookresearch_stopes/stopes/modules/speech/video_alignement/video_segmentor.py

Prompts

```
['run the LocalAlignmentModule to align bilingual video segments and output aligned parquet dataset', 'configure LocalAlignmentConfig with dataset_root, output_dir, language_pairs, and similarity thresholds for video segment alignment', 'compute pairwise cosine similarity between text and speech embeddings of two segment tables', 'apply the Blaser quality estimation model in batch mode to score speech embedding pairs', 'filter candidate aligned segment pairs by gap, duration ratio, speech sim, text sim, and blaser score thresholds', 'run the WhisperSegmentorModule to extract utterances from audio files and generate parquet segment datasets', 'build a WhisperSegmentorConfig dataclass to configure shards, output directory, whisper model, and segment length parameters', 'compute SONAR speech embeddings for audio waveform segments using the SpeechToEmbeddingModelPipeline', 'compute text embeddings for transcribed segment text using a SentenceTransformer model like LaBSE', 'get audio transcription and word-level timestamps from an audio file using Whisper with word timestamp support', 'build a python module to compute optimal monotonic alignment from a pairwise similarity matrix using Needleman-Wunsch', 'build a sparse CSR connectivity matrix where each entry indicates if two time segments intersect', 'build a sparse CSR matrix where each entry indicates if one time segment contains another', 'generate n-gram pairs from a list of words with configurable min and max depth', 'convert a list of PyTorch WAV segment tensors into a chunked PyArrow array for efficient storage']
```

Usage

```
{'run_whisper_segmentor_module': 'run the WhisperSegmentorModule to extract utterances from audio files and generate parquet segment datasets', 'build_whisper_segmentor_config': 'build a WhisperSegmentorConfig dataclass to configure shards, output directory, whisper model, and segment length parameters', 'compute_sonar_speech_embedding': 'compute SONAR speech embeddings for audio waveform segments using the SpeechToEmbeddingModelPipeline', 'compute_text_segment_embedding': 'compute text embeddings for transcribed segment text using a SentenceTransformer model like LaBSE', 'get_transcription': 'get audio transcription and word-level timestamps from an audio file using Whisper with word timestamp support'}
```

## File: facebookresearch_stopes/stopes/modules/speech/video_alignement/video_utils.py

Prompts

```
['run the LocalAlignmentModule to align bilingual video segments and output aligned parquet dataset', 'configure LocalAlignmentConfig with dataset_root, output_dir, language_pairs, and similarity thresholds for video segment alignment', 'compute pairwise cosine similarity between text and speech embeddings of two segment tables', 'apply the Blaser quality estimation model in batch mode to score speech embedding pairs', 'filter candidate aligned segment pairs by gap, duration ratio, speech sim, text sim, and blaser score thresholds', 'run the WhisperSegmentorModule to extract utterances from audio files and generate parquet segment datasets', 'build a WhisperSegmentorConfig dataclass to configure shards, output directory, whisper model, and segment length parameters', 'compute SONAR speech embeddings for audio waveform segments using the SpeechToEmbeddingModelPipeline', 'compute text embeddings for transcribed segment text using a SentenceTransformer model like LaBSE', 'get audio transcription and word-level timestamps from an audio file using Whisper with word timestamp support', 'build a python module to compute optimal monotonic alignment from a pairwise similarity matrix using Needleman-Wunsch', 'build a sparse CSR connectivity matrix where each entry indicates if two time segments intersect', 'build a sparse CSR matrix where each entry indicates if one time segment contains another', 'generate n-gram pairs from a list of words with configurable min and max depth', 'convert a list of PyTorch WAV segment tensors into a chunked PyArrow array for efficient storage']
```

Usage

```
{'build_strict_monotonic_alignment': 'build a python module to compute optimal monotonic alignment from a pairwise similarity matrix using Needleman-Wunsch', 'build_segment_intersection_connection': 'build a sparse CSR connectivity matrix where each entry indicates if two time segments intersect', 'build_contains_matrix': 'build a sparse CSR matrix where each entry indicates if one time segment contains another', 'generate_ngrams': 'generate n-gram pairs from a list of words with configurable min and max depth', 'convert_wav_to_arrow_array': 'convert a list of PyTorch WAV segment tensors into a chunked PyArrow array for efficient storage'}
```

