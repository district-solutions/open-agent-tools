# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/simultaneous_translation/eval/scorers/scorer.py

Prompts

```
['score simultaneous translation hypotheses against references using BLEU, TER, METEOR, and latency metrics', 'receive hypothesis tokens for a sentence and record them with their step numbers', 'write translation outputs, delay information, and quality scores to output files', 'load text from a file with optional token splitting for source or target data', 'load audio file paths and durations from a JSON manifest for speech translation', 'create a SimulTextScorer instance with args containing src_file and tgt_file paths for simultaneous translation evaluation', 'call send_src on SimulTextScorer with a sentence ID to retrieve the next source segment or EOS token', 'call src_lengths on SimulTextScorer to get a list of source sentence lengths including EOS tokens', 'call score on SimulTextScorer to compute BLEU, TER, METEOR, and latency metrics for simultaneous translation output', 'use the register_scorer decorator to register SimulTextScorer as the text scorer type in the fairseq scorer registry']
```

Usage

```
{'score_simultaneous_translation': 'score simultaneous translation hypotheses against references using BLEU, TER, METEOR, and latency metrics', 'recv_hyp_tokens': 'receive hypothesis tokens for a sentence and record them with their step numbers', 'write_results_to_file': 'write translation outputs, delay information, and quality scores to output files', 'load_text_file': 'load text from a file with optional token splitting for source or target data', 'load_wav_info_from_json': 'load audio file paths and durations from a JSON manifest for speech translation'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/simultaneous_translation/eval/scorers/text_scorer.py

Prompts

```
['score simultaneous translation hypotheses against references using BLEU, TER, METEOR, and latency metrics', 'receive hypothesis tokens for a sentence and record them with their step numbers', 'write translation outputs, delay information, and quality scores to output files', 'load text from a file with optional token splitting for source or target data', 'load audio file paths and durations from a JSON manifest for speech translation', 'create a SimulTextScorer instance with args containing src_file and tgt_file paths for simultaneous translation evaluation', 'call send_src on SimulTextScorer with a sentence ID to retrieve the next source segment or EOS token', 'call src_lengths on SimulTextScorer to get a list of source sentence lengths including EOS tokens', 'call score on SimulTextScorer to compute BLEU, TER, METEOR, and latency metrics for simultaneous translation output', 'use the register_scorer decorator to register SimulTextScorer as the text scorer type in the fairseq scorer registry']
```

Usage

```
{'init_simultextscorer': 'create a SimulTextScorer instance with args containing src_file and tgt_file paths for simultaneous translation evaluation', 'send_src_segment': 'call send_src on SimulTextScorer with a sentence ID to retrieve the next source segment or EOS token', 'get_src_lengths': 'call src_lengths on SimulTextScorer to get a list of source sentence lengths including EOS tokens', 'score_translation': 'call score on SimulTextScorer to compute BLEU, TER, METEOR, and latency metrics for simultaneous translation output', 'register_text_scorer': 'use the register_scorer decorator to register SimulTextScorer as the text scorer type in the fairseq scorer registry'}
```

