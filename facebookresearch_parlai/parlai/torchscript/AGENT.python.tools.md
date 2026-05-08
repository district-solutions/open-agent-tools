# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/torchscript/agents.py

Prompts

```
['create a TorchScriptAgent that loads a JIT-compiled model from disk using opt model_file', 'call act on a TorchScriptAgent to generate a response from conversation history via the scripted module', 'call observe on a TorchScriptAgent to append incoming text to the conversation history', 'call reset on a TorchScriptAgent to clear the conversation history and reset state', 'call share on a TorchScriptAgent to return a dict containing the shared scripted module object', 'build a TorchScriptGreedySearch module from a Parlai TorchAgent for greedy search text generation', 'run greedy search generation by calling forward on a TorchScriptGreedySearch instance with context text', 'build a TorchScriptTransformerClassifier module from a Parlai TorchAgent for classification tasks', 'run classification prediction by calling forward on a TorchScriptTransformerClassifier instance with context text', 'review the BaseIncrStateFlattener class methods for flattening and unflattening incremental state dicts for TorchScript', 'tokenize text into GPT-2 BPE tokens using ScriptableDictionaryAgent.gpt2_tokenize', 'tokenize text into subword BPE tokens using ScriptableDictionaryAgent.bpe_tokenize', 'convert text to a list of token indices using ScriptableDictionaryAgent.txt2vec', 'convert a list of token indices back to text using ScriptableDictionaryAgent.vec2txt', 'decode a list of GPT-2 BPE tokens into text using ScriptableGpt2BpeHelper.decode']
```

Usage

```
{'create_torchscript_agent': 'create a TorchScriptAgent that loads a JIT-compiled model from disk using opt model_file', 'act_torchscript_agent': 'call act on a TorchScriptAgent to generate a response from conversation history via the scripted module', 'observe_torchscript_agent': 'call observe on a TorchScriptAgent to append incoming text to the conversation history', 'reset_torchscript_agent': 'call reset on a TorchScriptAgent to clear the conversation history and reset state', 'share_torchscript_agent': 'call share on a TorchScriptAgent to return a dict containing the shared scripted module object'}
```

## File: facebookresearch_parlai/parlai/torchscript/modules.py

Prompts

```
['create a TorchScriptAgent that loads a JIT-compiled model from disk using opt model_file', 'call act on a TorchScriptAgent to generate a response from conversation history via the scripted module', 'call observe on a TorchScriptAgent to append incoming text to the conversation history', 'call reset on a TorchScriptAgent to clear the conversation history and reset state', 'call share on a TorchScriptAgent to return a dict containing the shared scripted module object', 'build a TorchScriptGreedySearch module from a Parlai TorchAgent for greedy search text generation', 'run greedy search generation by calling forward on a TorchScriptGreedySearch instance with context text', 'build a TorchScriptTransformerClassifier module from a Parlai TorchAgent for classification tasks', 'run classification prediction by calling forward on a TorchScriptTransformerClassifier instance with context text', 'review the BaseIncrStateFlattener class methods for flattening and unflattening incremental state dicts for TorchScript', 'tokenize text into GPT-2 BPE tokens using ScriptableDictionaryAgent.gpt2_tokenize', 'tokenize text into subword BPE tokens using ScriptableDictionaryAgent.bpe_tokenize', 'convert text to a list of token indices using ScriptableDictionaryAgent.txt2vec', 'convert a list of token indices back to text using ScriptableDictionaryAgent.vec2txt', 'decode a list of GPT-2 BPE tokens into text using ScriptableGpt2BpeHelper.decode']
```

Usage

```
{'build_TorchScriptGreedySearch': 'build a TorchScriptGreedySearch module from a Parlai TorchAgent for greedy search text generation', 'run_TorchScriptGreedySearch_forward': 'run greedy search generation by calling forward on a TorchScriptGreedySearch instance with context text', 'build_TorchScriptTransformerClassifier': 'build a TorchScriptTransformerClassifier module from a Parlai TorchAgent for classification tasks', 'run_TorchScriptTransformerClassifier_forward': 'run classification prediction by calling forward on a TorchScriptTransformerClassifier instance with context text', 'review_BaseIncrStateFlattener': 'review the BaseIncrStateFlattener class methods for flattening and unflattening incremental state dicts for TorchScript'}
```

## File: facebookresearch_parlai/parlai/torchscript/tokenizer.py

Prompts

```
['create a TorchScriptAgent that loads a JIT-compiled model from disk using opt model_file', 'call act on a TorchScriptAgent to generate a response from conversation history via the scripted module', 'call observe on a TorchScriptAgent to append incoming text to the conversation history', 'call reset on a TorchScriptAgent to clear the conversation history and reset state', 'call share on a TorchScriptAgent to return a dict containing the shared scripted module object', 'build a TorchScriptGreedySearch module from a Parlai TorchAgent for greedy search text generation', 'run greedy search generation by calling forward on a TorchScriptGreedySearch instance with context text', 'build a TorchScriptTransformerClassifier module from a Parlai TorchAgent for classification tasks', 'run classification prediction by calling forward on a TorchScriptTransformerClassifier instance with context text', 'review the BaseIncrStateFlattener class methods for flattening and unflattening incremental state dicts for TorchScript', 'tokenize text into GPT-2 BPE tokens using ScriptableDictionaryAgent.gpt2_tokenize', 'tokenize text into subword BPE tokens using ScriptableDictionaryAgent.bpe_tokenize', 'convert text to a list of token indices using ScriptableDictionaryAgent.txt2vec', 'convert a list of token indices back to text using ScriptableDictionaryAgent.vec2txt', 'decode a list of GPT-2 BPE tokens into text using ScriptableGpt2BpeHelper.decode']
```

Usage

```
{'gpt2_tokenize_text': 'tokenize text into GPT-2 BPE tokens using ScriptableDictionaryAgent.gpt2_tokenize', 'bpe_tokenize_text': 'tokenize text into subword BPE tokens using ScriptableDictionaryAgent.bpe_tokenize', 'txt2vec_convert': 'convert text to a list of token indices using ScriptableDictionaryAgent.txt2vec', 'vec2txt_convert': 'convert a list of token indices back to text using ScriptableDictionaryAgent.vec2txt', 'decode_gpt2_tokens': 'decode a list of GPT-2 BPE tokens into text using ScriptableGpt2BpeHelper.decode'}
```

