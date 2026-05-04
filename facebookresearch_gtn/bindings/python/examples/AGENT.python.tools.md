# Agent Python Tools

- repo: facebookresearch/gtn
- repo_uri: https://github.com/facebookresearch/gtn

## File: facebookresearch_gtn/bindings/python/examples/linear_crf.py

Prompts

```
['run the linear chain CRF example to train and evaluate a sequence labeling model using gtn graphs', 'create a CRF loss function by composing feature graphs with potentials and transitions then computing forward scores', 'build a bigram transition graph for a linear chain CRF with a given number of output classes', 'sample sequences from a linear chain CRF model by composing potentials and transitions graphs then finding viterbi paths', 'update CRF model parameters by taking a gradient step on potentials and transitions graphs using learning rate', 'run the GTNLoss function to compute sequence-level loss between frame-level inputs and token-level targets using GTN graphs', 'create a forward pass that computes loss by intersecting target graphs with emission graphs and scoring them', 'create a backward pass that computes gradients for each batch example in parallel using gtn.backward', 'build a target graph where each token can align to one or more input frames with self-loop arcs', 'test the GTNLoss end-to-end by computing loss and verifying gradient shapes match input tensor dimensions', 'build a graph that transduces letters to word pieces using a lexicon and letter-to-index mapping', 'build a graph with individual token transition models that consume one or more consecutive word pieces', 'compose an input graph with a lexicon graph then project output to compute word decompositions', 'compute the alignment graph by composing a token graph with decomposition results and projecting input', 'compute sequence level loss by intersecting emissions with alignment graphs and subtracting forward scores']
```

Usage

```
{'run_linear_crf_training': 'run the linear chain CRF example to train and evaluate a sequence labeling model using gtn graphs', 'create_crf_loss': 'create a CRF loss function by composing feature graphs with potentials and transitions then computing forward scores', 'build_transition_graph': 'build a bigram transition graph for a linear chain CRF with a given number of output classes', 'sample_crf_model': 'sample sequences from a linear chain CRF model by composing potentials and transitions graphs then finding viterbi paths', 'update_crf_params': 'update CRF model parameters by taking a gradient step on potentials and transitions graphs using learning rate'}
```

## File: facebookresearch_gtn/bindings/python/examples/pytorch_loss.py

Prompts

```
['run the linear chain CRF example to train and evaluate a sequence labeling model using gtn graphs', 'create a CRF loss function by composing feature graphs with potentials and transitions then computing forward scores', 'build a bigram transition graph for a linear chain CRF with a given number of output classes', 'sample sequences from a linear chain CRF model by composing potentials and transitions graphs then finding viterbi paths', 'update CRF model parameters by taking a gradient step on potentials and transitions graphs using learning rate', 'run the GTNLoss function to compute sequence-level loss between frame-level inputs and token-level targets using GTN graphs', 'create a forward pass that computes loss by intersecting target graphs with emission graphs and scoring them', 'create a backward pass that computes gradients for each batch example in parallel using gtn.backward', 'build a target graph where each token can align to one or more input frames with self-loop arcs', 'test the GTNLoss end-to-end by computing loss and verifying gradient shapes match input tensor dimensions', 'build a graph that transduces letters to word pieces using a lexicon and letter-to-index mapping', 'build a graph with individual token transition models that consume one or more consecutive word pieces', 'compose an input graph with a lexicon graph then project output to compute word decompositions', 'compute the alignment graph by composing a token graph with decomposition results and projecting input', 'compute sequence level loss by intersecting emissions with alignment graphs and subtracting forward scores']
```

Usage

```
{'run_GTNLoss': 'run the GTNLoss function to compute sequence-level loss between frame-level inputs and token-level targets using GTN graphs', 'create_GTNLossFunction_forward': 'create a forward pass that computes loss by intersecting target graphs with emission graphs and scoring them', 'create_GTNLossFunction_backward': 'create a backward pass that computes gradients for each batch example in parallel using gtn.backward', 'build_make_target_graph': 'build a target graph where each token can align to one or more input frames with self-loop arcs', 'test_GTNLoss_end_to_end': 'test the GTNLoss end-to-end by computing loss and verifying gradient shapes match input tensor dimensions'}
```

## File: facebookresearch_gtn/bindings/python/examples/word_decompositions.py

Prompts

```
['run the linear chain CRF example to train and evaluate a sequence labeling model using gtn graphs', 'create a CRF loss function by composing feature graphs with potentials and transitions then computing forward scores', 'build a bigram transition graph for a linear chain CRF with a given number of output classes', 'sample sequences from a linear chain CRF model by composing potentials and transitions graphs then finding viterbi paths', 'update CRF model parameters by taking a gradient step on potentials and transitions graphs using learning rate', 'run the GTNLoss function to compute sequence-level loss between frame-level inputs and token-level targets using GTN graphs', 'create a forward pass that computes loss by intersecting target graphs with emission graphs and scoring them', 'create a backward pass that computes gradients for each batch example in parallel using gtn.backward', 'build a target graph where each token can align to one or more input frames with self-loop arcs', 'test the GTNLoss end-to-end by computing loss and verifying gradient shapes match input tensor dimensions', 'build a graph that transduces letters to word pieces using a lexicon and letter-to-index mapping', 'build a graph with individual token transition models that consume one or more consecutive word pieces', 'compose an input graph with a lexicon graph then project output to compute word decompositions', 'compute the alignment graph by composing a token graph with decomposition results and projecting input', 'compute sequence level loss by intersecting emissions with alignment graphs and subtracting forward scores']
```

Usage

```
{'build_lexicon_graph': 'build a graph that transduces letters to word pieces using a lexicon and letter-to-index mapping', 'build_token_graph': 'build a graph with individual token transition models that consume one or more consecutive word pieces', 'compose_and_project_decompositions': 'compose an input graph with a lexicon graph then project output to compute word decompositions', 'compute_alignment_graph': 'compute the alignment graph by composing a token graph with decomposition results and projecting input', 'compute_sequence_loss': 'compute sequence level loss by intersecting emissions with alignment graphs and subtracting forward scores'}
```

