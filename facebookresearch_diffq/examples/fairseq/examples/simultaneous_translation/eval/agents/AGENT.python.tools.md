# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/simultaneous_translation/eval/agents/agent.py

Prompts

```
['decode a range of sentences from a session using the Agent with multithreaded support', 'initialize the agent states by implementing init_states in a subclass of Agent', 'update agent states with new state data using the update_states method', 'run the agent policy loop to decide GET or SEND actions for simultaneous translation', 'reset the agent to its initial state before decoding a new sentence', 'build a SimulTransAgent instance by passing args with model-path and data-bin arguments', 'review the SimulTransAgent policy method that decides between read and write actions for simultaneous translation', 'test the SimulTransAgent write_action method to predict target tokens and return detokenized words', 'summarize the SimulTransAgent init_states method that returns a dictionary with src and tgt indices, tokens, segments, and steps', 'refactor the SimulTransAgent load_model method to load a pretrained checkpoint and build the fairseq model', 'build word splitters for source and target using SPLITTER_DICT and args splitter type and path', 'load source and target dictionaries from the task object into the agent dict attribute', 'update agent states by splitting new words into tokens and encoding them with the source dictionary', 'request the next source word by incrementing the source step counter and checking buffered tokens', 'check if all source segments and tokens have been fully read by comparing finish flag and step count', 'create a BPEWordSplitter from a model path and split a string into subword tokens', 'create a SentencePieceModelWordSplitter from a model path and split a string into sentence piece tokens', 'use BPEWordSplitter merge method to rejoin BPE subword tokens back into a space-separated string', 'use SentencePieceModelWordSplitter merge method to decode sentence piece tokens back into text', 'use end_idx_last_full_word on BPEWordSplitter or SentencePieceModelWordSplitter to find the index of the last complete word in a token list']
```

Usage

```
{'decode_corpus_sentences': 'decode a range of sentences from a session using the Agent with multithreaded support', 'init_agent_states': 'initialize the agent states by implementing init_states in a subclass of Agent', 'update_agent_states': 'update agent states with new state data using the update_states method', 'run_agent_policy': 'run the agent policy loop to decide GET or SEND actions for simultaneous translation', 'reset_agent': 'reset the agent to its initial state before decoding a new sentence'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/simultaneous_translation/eval/agents/simul_trans_agent.py

Prompts

```
['decode a range of sentences from a session using the Agent with multithreaded support', 'initialize the agent states by implementing init_states in a subclass of Agent', 'update agent states with new state data using the update_states method', 'run the agent policy loop to decide GET or SEND actions for simultaneous translation', 'reset the agent to its initial state before decoding a new sentence', 'build a SimulTransAgent instance by passing args with model-path and data-bin arguments', 'review the SimulTransAgent policy method that decides between read and write actions for simultaneous translation', 'test the SimulTransAgent write_action method to predict target tokens and return detokenized words', 'summarize the SimulTransAgent init_states method that returns a dictionary with src and tgt indices, tokens, segments, and steps', 'refactor the SimulTransAgent load_model method to load a pretrained checkpoint and build the fairseq model', 'build word splitters for source and target using SPLITTER_DICT and args splitter type and path', 'load source and target dictionaries from the task object into the agent dict attribute', 'update agent states by splitting new words into tokens and encoding them with the source dictionary', 'request the next source word by incrementing the source step counter and checking buffered tokens', 'check if all source segments and tokens have been fully read by comparing finish flag and step count', 'create a BPEWordSplitter from a model path and split a string into subword tokens', 'create a SentencePieceModelWordSplitter from a model path and split a string into sentence piece tokens', 'use BPEWordSplitter merge method to rejoin BPE subword tokens back into a space-separated string', 'use SentencePieceModelWordSplitter merge method to decode sentence piece tokens back into text', 'use end_idx_last_full_word on BPEWordSplitter or SentencePieceModelWordSplitter to find the index of the last complete word in a token list']
```

Usage

```
{'build_simul_trans_agent': 'build a SimulTransAgent instance by passing args with model-path and data-bin arguments', 'review_simul_trans_agent_policy': 'review the SimulTransAgent policy method that decides between read and write actions for simultaneous translation', 'test_write_action': 'test the SimulTransAgent write_action method to predict target tokens and return detokenized words', 'summarize_init_states': 'summarize the SimulTransAgent init_states method that returns a dictionary with src and tgt indices, tokens, segments, and steps', 'refactor_load_model': 'refactor the SimulTransAgent load_model method to load a pretrained checkpoint and build the fairseq model'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/simultaneous_translation/eval/agents/simul_trans_text_agent.py

Prompts

```
['decode a range of sentences from a session using the Agent with multithreaded support', 'initialize the agent states by implementing init_states in a subclass of Agent', 'update agent states with new state data using the update_states method', 'run the agent policy loop to decide GET or SEND actions for simultaneous translation', 'reset the agent to its initial state before decoding a new sentence', 'build a SimulTransAgent instance by passing args with model-path and data-bin arguments', 'review the SimulTransAgent policy method that decides between read and write actions for simultaneous translation', 'test the SimulTransAgent write_action method to predict target tokens and return detokenized words', 'summarize the SimulTransAgent init_states method that returns a dictionary with src and tgt indices, tokens, segments, and steps', 'refactor the SimulTransAgent load_model method to load a pretrained checkpoint and build the fairseq model', 'build word splitters for source and target using SPLITTER_DICT and args splitter type and path', 'load source and target dictionaries from the task object into the agent dict attribute', 'update agent states by splitting new words into tokens and encoding them with the source dictionary', 'request the next source word by incrementing the source step counter and checking buffered tokens', 'check if all source segments and tokens have been fully read by comparing finish flag and step count', 'create a BPEWordSplitter from a model path and split a string into subword tokens', 'create a SentencePieceModelWordSplitter from a model path and split a string into sentence piece tokens', 'use BPEWordSplitter merge method to rejoin BPE subword tokens back into a space-separated string', 'use SentencePieceModelWordSplitter merge method to decode sentence piece tokens back into text', 'use end_idx_last_full_word on BPEWordSplitter or SentencePieceModelWordSplitter to find the index of the last complete word in a token list']
```

Usage

```
{'build_word_splitter': 'build word splitters for source and target using SPLITTER_DICT and args splitter type and path', 'load_dictionary': 'load source and target dictionaries from the task object into the agent dict attribute', 'update_states': 'update agent states by splitting new words into tokens and encoding them with the source dictionary', 'read_action': 'request the next source word by incrementing the source step counter and checking buffered tokens', 'finish_read': 'check if all source segments and tokens have been fully read by comparing finish flag and step count'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/simultaneous_translation/eval/agents/word_splitter.py

Prompts

```
['decode a range of sentences from a session using the Agent with multithreaded support', 'initialize the agent states by implementing init_states in a subclass of Agent', 'update agent states with new state data using the update_states method', 'run the agent policy loop to decide GET or SEND actions for simultaneous translation', 'reset the agent to its initial state before decoding a new sentence', 'build a SimulTransAgent instance by passing args with model-path and data-bin arguments', 'review the SimulTransAgent policy method that decides between read and write actions for simultaneous translation', 'test the SimulTransAgent write_action method to predict target tokens and return detokenized words', 'summarize the SimulTransAgent init_states method that returns a dictionary with src and tgt indices, tokens, segments, and steps', 'refactor the SimulTransAgent load_model method to load a pretrained checkpoint and build the fairseq model', 'build word splitters for source and target using SPLITTER_DICT and args splitter type and path', 'load source and target dictionaries from the task object into the agent dict attribute', 'update agent states by splitting new words into tokens and encoding them with the source dictionary', 'request the next source word by incrementing the source step counter and checking buffered tokens', 'check if all source segments and tokens have been fully read by comparing finish flag and step count', 'create a BPEWordSplitter from a model path and split a string into subword tokens', 'create a SentencePieceModelWordSplitter from a model path and split a string into sentence piece tokens', 'use BPEWordSplitter merge method to rejoin BPE subword tokens back into a space-separated string', 'use SentencePieceModelWordSplitter merge method to decode sentence piece tokens back into text', 'use end_idx_last_full_word on BPEWordSplitter or SentencePieceModelWordSplitter to find the index of the last complete word in a token list']
```

Usage

```
{'split_text_with_BPEWordSplitter': 'create a BPEWordSplitter from a model path and split a string into subword tokens', 'split_text_with_SentencePieceModelWordSplitter': 'create a SentencePieceModelWordSplitter from a model path and split a string into sentence piece tokens', 'merge_tokens_with_BPEWordSplitter': 'use BPEWordSplitter merge method to rejoin BPE subword tokens back into a space-separated string', 'merge_tokens_with_SentencePieceModelWordSplitter': 'use SentencePieceModelWordSplitter merge method to decode sentence piece tokens back into text', 'find_last_full_word_index': 'use end_idx_last_full_word on BPEWordSplitter or SentencePieceModelWordSplitter to find the index of the last complete word in a token list'}
```

