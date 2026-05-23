# Agent Python Tools

- repo: facebookresearch/responsiblenlp
- repo_uri: https://github.com/facebookresearch/responsiblenlp

## File: facebookresearch_responsiblenlp/robbie/predictors/_base.py

Prompts

```
['build a Predictor subclass that generates predictions from an iterator of Prompt objects', 'generate predictions by calling the generate method on a Predictor with an iterator of Prompts', 'create a GenerationConfig dataclass with top_k, top_p, temperature, beam_size, max_length, and batch_size parameters', 'add command line arguments for predictor name and generation config to an ArgumentParser', 'build a GenerationConfig instance from argparse arguments using the from_args class method', 'create an HFCausalPredictor instance with a HuggingFace model ID and generation config', 'run batched text generation on prompts using a HuggingFace causal language model', 'configure generation arguments including top_k, top_p, temperature, beam size, and max tokens', 'register the HFCausalPredictor as an hf_causal predictor with argparse CLI support', 'review the HFCausalPredictor initialization that loads a pretrained model and tokenizer with pad token handling']
```

Usage

```
{'build_predictor': 'build a Predictor subclass that generates predictions from an iterator of Prompt objects', 'generate_predictions': 'generate predictions by calling the generate method on a Predictor with an iterator of Prompts', 'create_generation_config': 'create a GenerationConfig dataclass with top_k, top_p, temperature, beam_size, max_length, and batch_size parameters', 'add_predictor_args': 'add command line arguments for predictor name and generation config to an ArgumentParser', 'from_args_generation_config': 'build a GenerationConfig instance from argparse arguments using the from_args class method'}
```

## File: facebookresearch_responsiblenlp/robbie/predictors/hf.py

Prompts

```
['build a Predictor subclass that generates predictions from an iterator of Prompt objects', 'generate predictions by calling the generate method on a Predictor with an iterator of Prompts', 'create a GenerationConfig dataclass with top_k, top_p, temperature, beam_size, max_length, and batch_size parameters', 'add command line arguments for predictor name and generation config to an ArgumentParser', 'build a GenerationConfig instance from argparse arguments using the from_args class method', 'create an HFCausalPredictor instance with a HuggingFace model ID and generation config', 'run batched text generation on prompts using a HuggingFace causal language model', 'configure generation arguments including top_k, top_p, temperature, beam size, and max tokens', 'register the HFCausalPredictor as an hf_causal predictor with argparse CLI support', 'review the HFCausalPredictor initialization that loads a pretrained model and tokenizer with pad token handling']
```

Usage

```
{'create_HFCausalPredictor': 'create an HFCausalPredictor instance with a HuggingFace model ID and generation config', 'run_HFCausalPredictor_generate': 'run batched text generation on prompts using a HuggingFace causal language model', 'configure_HFCausalPredictor_generation_kwargs': 'configure generation arguments including top_k, top_p, temperature, beam size, and max tokens', 'register_HFCausalPredictor': 'register the HFCausalPredictor as an hf_causal predictor with argparse CLI support', 'review_HFCausalPredictor_init': 'review the HFCausalPredictor initialization that loads a pretrained model and tokenizer with pad token handling'}
```

