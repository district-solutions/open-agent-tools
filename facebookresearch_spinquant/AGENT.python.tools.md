# Agent Python Tools

- repo: facebookresearch/spinquant
- repo_uri: https://github.com/facebookresearch/spinquant

## File: facebookresearch_spinquant/optimize_rotation.py

Prompts

```
['run the SpinQuant rotation optimization training on a quantized Llama model using wikitext calibration data', 'create a RotateModule with an initial rotation matrix to apply trainable rotations in forward passes', 'test the RotateModule forward method to verify matrix multiplication with and without transpose mode', 'review the train function that initializes distributed training, attaches rotation modules, and saves optimized R matrices', 'refactor the RotateModule class to support additional rotation matrix initialization strategies beyond random Hadamard', 'run post-training quantization on a Llama model and evaluate perplexity on WikiText-2', 'run the train function to initialize distributed training and apply PTQ to a Llama model', 'summarize the PTQ pipeline that loads a Llama model, quantizes it, and measures perplexity', 'test the PTQ quantization flow by running the train function with a Llama model and WikiText-2 data']
```

Usage

```
{'run_optimize_rotation': 'run the SpinQuant rotation optimization training on a quantized Llama model using wikitext calibration data', 'create_RotateModule': 'create a RotateModule with an initial rotation matrix to apply trainable rotations in forward passes', 'test_RotateModule_forward': 'test the RotateModule forward method to verify matrix multiplication with and without transpose mode', 'review_train_function': 'review the train function that initializes distributed training, attaches rotation modules, and saves optimized R matrices', 'refactor_RotateModule': 'refactor the RotateModule class to support additional rotation matrix initialization strategies beyond random Hadamard'}
```

## File: facebookresearch_spinquant/ptq.py

Prompts

```
['run the SpinQuant rotation optimization training on a quantized Llama model using wikitext calibration data', 'create a RotateModule with an initial rotation matrix to apply trainable rotations in forward passes', 'test the RotateModule forward method to verify matrix multiplication with and without transpose mode', 'review the train function that initializes distributed training, attaches rotation modules, and saves optimized R matrices', 'refactor the RotateModule class to support additional rotation matrix initialization strategies beyond random Hadamard', 'run post-training quantization on a Llama model and evaluate perplexity on WikiText-2', 'run the train function to initialize distributed training and apply PTQ to a Llama model', 'summarize the PTQ pipeline that loads a Llama model, quantizes it, and measures perplexity', 'test the PTQ quantization flow by running the train function with a Llama model and WikiText-2 data']
```

Usage

```
{'run_ptq_quantization': 'run post-training quantization on a Llama model and evaluate perplexity on WikiText-2', 'run_train_function': 'run the train function to initialize distributed training and apply PTQ to a Llama model', 'review_train_function': 'review the train function that handles model loading, PTQ quantization, and WikiText-2 evaluation', 'summarize_ptq_pipeline': 'summarize the PTQ pipeline that loads a Llama model, quantizes it, and measures perplexity', 'test_ptq_model': 'test the PTQ quantization flow by running the train function with a Llama model and WikiText-2 data'}
```

