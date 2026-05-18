# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf_cli/hm_convert.py

Prompts

```
['run the HMConverter CLI to convert a Hateful Memes zip file into MMF dataset format', 'convert a password-protected Hateful Memes zip file into organized images and annotations directories', 'verify the SHA256 checksum of a downloaded Hateful Memes zip file against known valid hashes', 'decompress a password-protected zip file using unzip CLI or Python zipfile fallback', 'assert that required Phase 1 or Phase 2 JSONL and image files exist in the extracted folder', 'run the interactive CLI to perform multimodal inference on image URLs and text input', 'run construct_config to build an OmegaConf config from a dotlist of option strings', 'run inference.forward with an image URL and text dict to get a model response', 'review the interactive function that handles CLI argument parsing and inference loops', 'refactor construct_config to support additional default config keys beyond checkpoint_path', 'run MMF prediction by calling predict() which sets evaluation.predict=true and invokes the run engine', 'run MMF prediction with custom options by passing a list to predict(opts=my_opts)', 'run MMF prediction from the command line by executing predict.py directly as a script', 'review the predict function to understand how it extends sys.argv with evaluation.predict=true before calling run', 'refactor the predict function to accept a config dictionary instead of extending sys.argv', 'run an MMF training job programmatically by passing opts like training.batch_size=64', 'run an MMF model in prediction mode by setting predict=True in the run function', 'run an MMF job across multiple GPUs using torch multiprocessing spawn', 'run an MMF job from the command line using the flags parser and run entry point', 'run an MMF distributed job on TPU cores using torch_xla multiprocessing spawn']
```

Usage

```
{'run_hm_converter': 'run the HMConverter CLI to convert a Hateful Memes zip file into MMF dataset format', 'convert_hateful_memes_zip': 'convert a password-protected Hateful Memes zip file into organized images and annotations directories', 'checksum_zip_file': 'verify the SHA256 checksum of a downloaded Hateful Memes zip file against known valid hashes', 'decompress_password_zip': 'decompress a password-protected zip file using unzip CLI or Python zipfile fallback', 'assert_hm_files': 'assert that required Phase 1 or Phase 2 JSONL and image files exist in the extracted folder'}
```

## File: facebookresearch_mmf/mmf_cli/interactive.py

Prompts

```
['run the HMConverter CLI to convert a Hateful Memes zip file into MMF dataset format', 'convert a password-protected Hateful Memes zip file into organized images and annotations directories', 'verify the SHA256 checksum of a downloaded Hateful Memes zip file against known valid hashes', 'decompress a password-protected zip file using unzip CLI or Python zipfile fallback', 'assert that required Phase 1 or Phase 2 JSONL and image files exist in the extracted folder', 'run the interactive CLI to perform multimodal inference on image URLs and text input', 'run construct_config to build an OmegaConf config from a dotlist of option strings', 'run inference.forward with an image URL and text dict to get a model response', 'review the interactive function that handles CLI argument parsing and inference loops', 'refactor construct_config to support additional default config keys beyond checkpoint_path', 'run MMF prediction by calling predict() which sets evaluation.predict=true and invokes the run engine', 'run MMF prediction with custom options by passing a list to predict(opts=my_opts)', 'run MMF prediction from the command line by executing predict.py directly as a script', 'review the predict function to understand how it extends sys.argv with evaluation.predict=true before calling run', 'refactor the predict function to accept a config dictionary instead of extending sys.argv', 'run an MMF training job programmatically by passing opts like training.batch_size=64', 'run an MMF model in prediction mode by setting predict=True in the run function', 'run an MMF job across multiple GPUs using torch multiprocessing spawn', 'run an MMF job from the command line using the flags parser and run entry point', 'run an MMF distributed job on TPU cores using torch_xla multiprocessing spawn']
```

Usage

```
{'run_interactive_inference': 'run the interactive CLI to perform multimodal inference on image URLs and text input', 'run_construct_config': 'run construct_config to build an OmegaConf config from a dotlist of option strings', 'run_inference_forward': 'run inference.forward with an image URL and text dict to get a model response', 'review_interactive_function': 'review the interactive function that handles CLI argument parsing and inference loops', 'refactor_construct_config': 'refactor construct_config to support additional default config keys beyond checkpoint_path'}
```

## File: facebookresearch_mmf/mmf_cli/predict.py

Prompts

```
['run the HMConverter CLI to convert a Hateful Memes zip file into MMF dataset format', 'convert a password-protected Hateful Memes zip file into organized images and annotations directories', 'verify the SHA256 checksum of a downloaded Hateful Memes zip file against known valid hashes', 'decompress a password-protected zip file using unzip CLI or Python zipfile fallback', 'assert that required Phase 1 or Phase 2 JSONL and image files exist in the extracted folder', 'run the interactive CLI to perform multimodal inference on image URLs and text input', 'run construct_config to build an OmegaConf config from a dotlist of option strings', 'run inference.forward with an image URL and text dict to get a model response', 'review the interactive function that handles CLI argument parsing and inference loops', 'refactor construct_config to support additional default config keys beyond checkpoint_path', 'run MMF prediction by calling predict() which sets evaluation.predict=true and invokes the run engine', 'run MMF prediction with custom options by passing a list to predict(opts=my_opts)', 'run MMF prediction from the command line by executing predict.py directly as a script', 'review the predict function to understand how it extends sys.argv with evaluation.predict=true before calling run', 'refactor the predict function to accept a config dictionary instead of extending sys.argv', 'run an MMF training job programmatically by passing opts like training.batch_size=64', 'run an MMF model in prediction mode by setting predict=True in the run function', 'run an MMF job across multiple GPUs using torch multiprocessing spawn', 'run an MMF job from the command line using the flags parser and run entry point', 'run an MMF distributed job on TPU cores using torch_xla multiprocessing spawn']
```

Usage

```
{'run_mmF_prediction': 'run MMF prediction by calling predict() which sets evaluation.predict=true and invokes the run engine', 'run_prediction_with_custom_opts': 'run MMF prediction with custom options by passing a list to predict(opts=my_opts)', 'run_prediction_from_cli': 'run MMF prediction from the command line by executing predict.py directly as a script', 'review_predict_function': 'review the predict function to understand how it extends sys.argv with evaluation.predict=true before calling run', 'refactor_predict_to_accept_config': 'refactor the predict function to accept a config dictionary instead of extending sys.argv'}
```

## File: facebookresearch_mmf/mmf_cli/run.py

Prompts

```
['run the HMConverter CLI to convert a Hateful Memes zip file into MMF dataset format', 'convert a password-protected Hateful Memes zip file into organized images and annotations directories', 'verify the SHA256 checksum of a downloaded Hateful Memes zip file against known valid hashes', 'decompress a password-protected zip file using unzip CLI or Python zipfile fallback', 'assert that required Phase 1 or Phase 2 JSONL and image files exist in the extracted folder', 'run the interactive CLI to perform multimodal inference on image URLs and text input', 'run construct_config to build an OmegaConf config from a dotlist of option strings', 'run inference.forward with an image URL and text dict to get a model response', 'review the interactive function that handles CLI argument parsing and inference loops', 'refactor construct_config to support additional default config keys beyond checkpoint_path', 'run MMF prediction by calling predict() which sets evaluation.predict=true and invokes the run engine', 'run MMF prediction with custom options by passing a list to predict(opts=my_opts)', 'run MMF prediction from the command line by executing predict.py directly as a script', 'review the predict function to understand how it extends sys.argv with evaluation.predict=true before calling run', 'refactor the predict function to accept a config dictionary instead of extending sys.argv', 'run an MMF training job programmatically by passing opts like training.batch_size=64', 'run an MMF model in prediction mode by setting predict=True in the run function', 'run an MMF job across multiple GPUs using torch multiprocessing spawn', 'run an MMF job from the command line using the flags parser and run entry point', 'run an MMF distributed job on TPU cores using torch_xla multiprocessing spawn']
```

Usage

```
{'run_mmf_job_with_opts': 'run an MMF training job programmatically by passing opts like training.batch_size=64', 'run_mmf_inference': 'run an MMF model in prediction mode by setting predict=True in the run function', 'run_mmf_distributed': 'run an MMF job across multiple GPUs using torch multiprocessing spawn', 'run_mmf_from_cli': 'run an MMF job from the command line using the flags parser and run entry point', 'run_mmf_on_tpu': 'run an MMF distributed job on TPU cores using torch_xla multiprocessing spawn'}
```

