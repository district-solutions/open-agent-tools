# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/models/semantic_parsers/rnng/rnng_data_structures.py

Prompts

```
['create a StackLSTM instance with an nn.LSTM to manage push pop and embedding operations', 'push a tensor expression and Element onto the StackLSTM stack for RNNG parsing', 'forward a list of tensor embeddings through CompositionalNN to combine them with a biLSTM', 'forward a list of tensor embeddings through CompositionalSummationNN to combine them with summation', 'create a ParserState with three StackLSTM instances to track buffer stack and action state', 'build a recurrent neural network grammar parser for constituency parsing with intent and slot labels', 'create an RNNG parser config with blstm composition, ablation params, and intent slot nesting constraints', 'run the RNNG forward pass with tokens, sequence lengths, and oracle actions for training', 'review the valid actions method that restricts possible shift reduce and non-terminal predictions', 'test the push action method that updates parser state for shift, reduce, and non-terminal actions']
```

Usage

```
{'create_stacklstm': 'create a StackLSTM instance with an nn.LSTM to manage push pop and embedding operations', 'push_stacklstm_element': 'push a tensor expression and Element onto the StackLSTM stack for RNNG parsing', 'forward_compositionalnn': 'forward a list of tensor embeddings through CompositionalNN to combine them with a biLSTM', 'forward_compositionalsummationnn': 'forward a list of tensor embeddings through CompositionalSummationNN to combine them with summation', 'create_parserstate': 'create a ParserState with three StackLSTM instances to track buffer stack and action state'}
```

## File: facebookresearch_pytext/pytext/models/semantic_parsers/rnng/rnng_parser.py

Prompts

```
['create a StackLSTM instance with an nn.LSTM to manage push pop and embedding operations', 'push a tensor expression and Element onto the StackLSTM stack for RNNG parsing', 'forward a list of tensor embeddings through CompositionalNN to combine them with a biLSTM', 'forward a list of tensor embeddings through CompositionalSummationNN to combine them with summation', 'create a ParserState with three StackLSTM instances to track buffer stack and action state', 'build a recurrent neural network grammar parser for constituency parsing with intent and slot labels', 'create an RNNG parser config with blstm composition, ablation params, and intent slot nesting constraints', 'run the RNNG forward pass with tokens, sequence lengths, and oracle actions for training', 'review the valid actions method that restricts possible shift reduce and non-terminal predictions', 'test the push action method that updates parser state for shift, reduce, and non-terminal actions']
```

Usage

```
{'build_rnng_parser': 'build a recurrent neural network grammar parser for constituency parsing with intent and slot labels', 'create_rnng_config': 'create an RNNG parser config with blstm composition, ablation params, and intent slot nesting constraints', 'run_rnng_forward': 'run the RNNG forward pass with tokens, sequence lengths, and oracle actions for training', 'review_valid_actions': 'review the valid actions method that restricts possible shift reduce and non-terminal predictions', 'test_push_action': 'test the push action method that updates parser state for shift, reduce, and non-terminal actions'}
```

