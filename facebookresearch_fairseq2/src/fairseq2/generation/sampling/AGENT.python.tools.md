# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/generation/sampling/generator.py

Prompts

```
['build a SamplingSequenceGenerator with a CausalLM model, sampler, and temperature for text generation', 'build a SamplingSeq2SeqGenerator with a Seq2SeqModel, sampler, and max_gen_len for translation', 'run the SamplingSequenceGenerator on prompt tensors with a BatchLayout to generate sequences', 'run the SamplingSeq2SeqGenerator on source and prompt tensors to generate translated sequences', 'register a StepHook callback on a SamplingSequenceGenerator to observe each generation step', 'create a TopPSampler instance with a cumulative probability threshold for nucleus sampling', 'sample token indices from a probability tensor using Top-P nucleus sampling', 'create a TopKSampler instance that selects from the k most likely candidates', 'sample token indices from a probability tensor using Top-K sampling strategy', 'review the Sampler abstract base class and its sample method signature']
```

Usage

```
{'build_sampling_sequence_generator': 'build a SamplingSequenceGenerator with a CausalLM model, sampler, and temperature for text generation', 'build_sampling_seq2seq_generator': 'build a SamplingSeq2SeqGenerator with a Seq2SeqModel, sampler, and max_gen_len for translation', 'run_sampling_sequence_generator': 'run the SamplingSequenceGenerator on prompt tensors with a BatchLayout to generate sequences', 'run_sampling_seq2seq_generator': 'run the SamplingSeq2SeqGenerator on source and prompt tensors to generate translated sequences', 'register_step_hook_on_generator': 'register a StepHook callback on a SamplingSequenceGenerator to observe each generation step'}
```

## File: facebookresearch_fairseq2/src/fairseq2/generation/sampling/sampler.py

Prompts

```
['build a SamplingSequenceGenerator with a CausalLM model, sampler, and temperature for text generation', 'build a SamplingSeq2SeqGenerator with a Seq2SeqModel, sampler, and max_gen_len for translation', 'run the SamplingSequenceGenerator on prompt tensors with a BatchLayout to generate sequences', 'run the SamplingSeq2SeqGenerator on source and prompt tensors to generate translated sequences', 'register a StepHook callback on a SamplingSequenceGenerator to observe each generation step', 'create a TopPSampler instance with a cumulative probability threshold for nucleus sampling', 'sample token indices from a probability tensor using Top-P nucleus sampling', 'create a TopKSampler instance that selects from the k most likely candidates', 'sample token indices from a probability tensor using Top-K sampling strategy', 'review the Sampler abstract base class and its sample method signature']
```

Usage

```
{'create_TopPSampler': 'create a TopPSampler instance with a cumulative probability threshold for nucleus sampling', 'sample_TopPSampler': 'sample token indices from a probability tensor using Top-P nucleus sampling', 'create_TopKSampler': 'create a TopKSampler instance that selects from the k most likely candidates', 'sample_TopKSampler': 'sample token indices from a probability tensor using Top-K sampling strategy', 'review_Sampler': 'review the Sampler abstract base class and its sample method signature'}
```

