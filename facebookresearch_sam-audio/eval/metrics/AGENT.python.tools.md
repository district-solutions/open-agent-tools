# Agent Python Tools

- repo: facebookresearch/sam-audio
- repo_uri: https://github.com/facebookresearch/sam-audio

## File: facebookresearch_sam-audio/eval/metrics/judge.py

Prompts

```
['initialize a Judge model from the facebook/sam-audio-judge checkpoint on a specified device', 'run inference on input and target WAV tensors with descriptions to get judge scores', 'evaluate audio separation quality and get an overall judge score for input versus target audio', 'evaluate faithfulness of separated audio against the original input using the Judge model', 'evaluate recall and precision metrics for audio separation using the Judge model forward pass']
```

Usage

```
{'init_Judge_model': 'initialize a Judge model from the facebook/sam-audio-judge checkpoint on a specified device', 'forward_Judge_inference': 'run inference on input and target WAV tensors with descriptions to get judge scores', 'evaluate_Judge_overall': 'evaluate audio separation quality and get an overall judge score for input versus target audio', 'evaluate_Judge_faithfulness': 'evaluate faithfulness of separated audio against the original input using the Judge model', 'evaluate_Judge_recall_precision': 'evaluate recall and precision metrics for audio separation using the Judge model forward pass'}
```

