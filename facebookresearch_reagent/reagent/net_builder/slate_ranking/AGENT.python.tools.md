# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/net_builder/slate_ranking/slate_ranking_scorer.py

Prompts

```
['build a slate ranking network using SlateRankingScorer with custom hidden layers and activations for reinforcement learning', 'create a ScoreCap PyTorch module that clips neural network outputs to a maximum value', 'configure a FinalLayer dataclass with sigmoid, tanh, or score_cap options for neural network output transformation', 'build an MLPScorer model with configurable hidden layers, batch norm, dropout, and layer normalization options', 'review the SlateRankingScorer class configuration including hidden layers, activations, and final layer settings', 'create a SlateRankingTransformer dataclass instance with default transformer parameters including 2 heads and 16 dim model', 'configure the transformer field with custom num_heads, dim_model, dim_feedforward, and num_stacked_layers values', 'set the output_arch attribute to Seq2SlateOutputArch.AUTOREGRESSIVE or another Seq2SlateOutputArch variant', 'review the SlateRankingTransformer class and its build_slate_ranking_network method for slate ranking network configuration']
```

Usage

```
{'build_slate_ranking_network': 'build a slate ranking network using SlateRankingScorer with custom hidden layers and activations for reinforcement learning', 'create_score_cap_module': 'create a ScoreCap PyTorch module that clips neural network outputs to a maximum value', 'configure_final_layer': 'configure a FinalLayer dataclass with sigmoid, tanh, or score_cap options for neural network output transformation', 'build_mlp_scorer': 'build an MLPScorer model with configurable hidden layers, batch norm, dropout, and layer normalization options', 'review_slate_ranking_scorer': 'review the SlateRankingScorer class configuration including hidden layers, activations, and final layer settings'}
```

## File: facebookresearch_reagent/reagent/net_builder/slate_ranking/slate_ranking_transformer.py

Prompts

```
['build a slate ranking network using SlateRankingScorer with custom hidden layers and activations for reinforcement learning', 'create a ScoreCap PyTorch module that clips neural network outputs to a maximum value', 'configure a FinalLayer dataclass with sigmoid, tanh, or score_cap options for neural network output transformation', 'build an MLPScorer model with configurable hidden layers, batch norm, dropout, and layer normalization options', 'review the SlateRankingScorer class configuration including hidden layers, activations, and final layer settings', 'create a SlateRankingTransformer dataclass instance with default transformer parameters including 2 heads and 16 dim model', 'configure the transformer field with custom num_heads, dim_model, dim_feedforward, and num_stacked_layers values', 'set the output_arch attribute to Seq2SlateOutputArch.AUTOREGRESSIVE or another Seq2SlateOutputArch variant', 'review the SlateRankingTransformer class and its build_slate_ranking_network method for slate ranking network configuration']
```

Usage

```
{'build_slate_ranking_network': 'build a Seq2SlateTransformerNet model using SlateRankingTransformer with state_dim, candidate_dim, candidate_size, and slate_size parameters', 'create_slate_ranking_transformer': 'create a SlateRankingTransformer dataclass instance with default transformer parameters including 2 heads and 16 dim model', 'configure_transformer_parameters': 'configure the transformer field with custom num_heads, dim_model, dim_feedforward, and num_stacked_layers values', 'set_output_architecture': 'set the output_arch attribute to Seq2SlateOutputArch.AUTOREGRESSIVE or another Seq2SlateOutputArch variant', 'review_slate_ranking_transformer': 'review the SlateRankingTransformer class and its build_slate_ranking_network method for slate ranking network configuration'}
```

