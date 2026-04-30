# Agent Python Tools

- repo: huggingface/optimum-executorch
- repo_uri: https://github.com/huggingface/optimum-executorch

## File: huggingface_optimum-executorch/optimum/executorch/modeling.py

Prompts

```
['load a pre-exported ExecuTorch causal language model from a HuggingFace repo or local path using ExecuTorchModelForCausalLM.from_pretrained', 'generate text tokens from a prompt using ExecuTorchModelForCausalLM.generate with echo and max_seq_len options', 'run sequence-to-sequence text generation with ExecuTorchModelForSeq2SeqLM.generate using encoder and decoder models', 'run object detection inference on pixel values using ExecuTorchModelForObjectDetection.forward to get logits and bounding boxes', 'transcribe audio input features to text using ExecuTorchModelForSpeechSeq2Seq.transcribe with a tokenizer and max sequence length', 'create a Stats instance to track LLM execution latency timestamps', 'call on_model_load_start and on_model_load_end to measure model loading duration', 'use on_inference_start and on_inference_end to measure total inference time', 'use on_sampling_begin and on_sampling_end to aggregate sampling time across tokens', 'call to_json or to_json_string to export stats as a JSON dictionary or string']
```

Usage

```
{'load_executorch_causal_lm': 'load a pre-exported ExecuTorch causal language model from a HuggingFace repo or local path using ExecuTorchModelForCausalLM.from_pretrained', 'generate_causal_lm_tokens': 'generate text tokens from a prompt using ExecuTorchModelForCausalLM.generate with echo and max_seq_len options', 'run_seq2seq_generation': 'run sequence-to-sequence text generation with ExecuTorchModelForSeq2SeqLM.generate using encoder and decoder models', 'run_object_detection': 'run object detection inference on pixel values using ExecuTorchModelForObjectDetection.forward to get logits and bounding boxes', 'transcribe_speech': 'transcribe audio input features to text using ExecuTorchModelForSpeechSeq2Seq.transcribe with a tokenizer and max sequence length'}
```

## File: huggingface_optimum-executorch/optimum/executorch/stats.py

Prompts

```
['load a pre-exported ExecuTorch causal language model from a HuggingFace repo or local path using ExecuTorchModelForCausalLM.from_pretrained', 'generate text tokens from a prompt using ExecuTorchModelForCausalLM.generate with echo and max_seq_len options', 'run sequence-to-sequence text generation with ExecuTorchModelForSeq2SeqLM.generate using encoder and decoder models', 'run object detection inference on pixel values using ExecuTorchModelForObjectDetection.forward to get logits and bounding boxes', 'transcribe audio input features to text using ExecuTorchModelForSpeechSeq2Seq.transcribe with a tokenizer and max sequence length', 'create a Stats instance to track LLM execution latency timestamps', 'call on_model_load_start and on_model_load_end to measure model loading duration', 'use on_inference_start and on_inference_end to measure total inference time', 'use on_sampling_begin and on_sampling_end to aggregate sampling time across tokens', 'call to_json or to_json_string to export stats as a JSON dictionary or string']
```

Usage

```
{'create_stats_instance': 'create a Stats instance to track LLM execution latency timestamps', 'track_model_load_time': 'call on_model_load_start and on_model_load_end to measure model loading duration', 'track_inference_timing': 'use on_inference_start and on_inference_end to measure total inference time', 'track_sampling_time': 'use on_sampling_begin and on_sampling_end to aggregate sampling time across tokens', 'export_stats_to_json': 'call to_json or to_json_string to export stats as a JSON dictionary or string'}
```

