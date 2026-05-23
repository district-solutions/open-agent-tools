# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/test/prediction/test_model_with_preprocessor.py

Prompts

```
['test the Seq2SlateTransformerNet model with FRECHET_SORT output architecture and preprocessor', 'test the Seq2SlateTransformerNet model with AUTOREGRESSIVE output architecture and preprocessor', 'run the Seq2SlateTransformerNet model wrapped with state and candidate preprocessors for slate ranking', 'verify that expected and scripted torch tensor outputs are equal using numpy array comparison', 'test that a JIT-compiled Seq2Slate model handles variable candidate and slate input lengths', 'create a NormalizationParameters object for continuous features with mean 0 and stddev 1', 'create a NormalizationParameters object for continuous actions with min -3 and max 3', 'test the change_cand_size_slate_ranking function with a prototype tuple and candidate size override', 'refactor change_cand_size_slate_ranking to support additional tensor dimensions for slate ranking prototypes', 'summarize the _cont_norm function that returns continuous feature normalization parameters', 'test the DiscreteDqnPredictorWrapper with a FullyConnectedDQN model and state preprocessor', 'test the ParametricDqnPredictorWrapper with state and action preprocessors for continuous actions', 'test the ActorPredictorWrapper with a FullyConnectedActor model and postprocessor', 'test the Seq2SlatePredictorWrapper with a transformer model for slate ranking', 'test the DeterminantalPointProcessPredictorWrapper with linear and RBF kernels for diverse ranking']
```

Usage

```
{'test_seq2slate_transformer_frechet_sort': 'test the Seq2SlateTransformerNet model with FRECHET_SORT output architecture and preprocessor', 'test_seq2slate_transformer_autoregressive': 'test the Seq2SlateTransformerNet model with AUTOREGRESSIVE output architecture and preprocessor', 'run_seq2slate_model_with_preprocessor': 'run the Seq2SlateTransformerNet model wrapped with state and candidate preprocessors for slate ranking', 'verify_results_tensor_comparison': 'verify that expected and scripted torch tensor outputs are equal using numpy array comparison', 'test_jit_compiled_model_variable_input': 'test that a JIT-compiled Seq2Slate model handles variable candidate and slate input lengths'}
```

## File: facebookresearch_reagent/reagent/test/prediction/test_prediction_utils.py

Prompts

```
['test the Seq2SlateTransformerNet model with FRECHET_SORT output architecture and preprocessor', 'test the Seq2SlateTransformerNet model with AUTOREGRESSIVE output architecture and preprocessor', 'run the Seq2SlateTransformerNet model wrapped with state and candidate preprocessors for slate ranking', 'verify that expected and scripted torch tensor outputs are equal using numpy array comparison', 'test that a JIT-compiled Seq2Slate model handles variable candidate and slate input lengths', 'create a NormalizationParameters object for continuous features with mean 0 and stddev 1', 'create a NormalizationParameters object for continuous actions with min -3 and max 3', 'test the change_cand_size_slate_ranking function with a prototype tuple and candidate size override', 'refactor change_cand_size_slate_ranking to support additional tensor dimensions for slate ranking prototypes', 'summarize the _cont_norm function that returns continuous feature normalization parameters', 'test the DiscreteDqnPredictorWrapper with a FullyConnectedDQN model and state preprocessor', 'test the ParametricDqnPredictorWrapper with state and action preprocessors for continuous actions', 'test the ActorPredictorWrapper with a FullyConnectedActor model and postprocessor', 'test the Seq2SlatePredictorWrapper with a transformer model for slate ranking', 'test the DeterminantalPointProcessPredictorWrapper with linear and RBF kernels for diverse ranking']
```

Usage

```
{'create_cont_norm': 'create a NormalizationParameters object for continuous features with mean 0 and stddev 1', 'create_cont_action_norm': 'create a NormalizationParameters object for continuous actions with min -3 and max 3', 'test_change_cand_size_slate_ranking': 'test the change_cand_size_slate_ranking function with a prototype tuple and candidate size override', 'refactor_change_cand_size_slate_ranking': 'refactor change_cand_size_slate_ranking to support additional tensor dimensions for slate ranking prototypes', 'summarize_cont_norm': 'summarize the _cont_norm function that returns continuous feature normalization parameters'}
```

## File: facebookresearch_reagent/reagent/test/prediction/test_predictor_wrapper.py

Prompts

```
['test the Seq2SlateTransformerNet model with FRECHET_SORT output architecture and preprocessor', 'test the Seq2SlateTransformerNet model with AUTOREGRESSIVE output architecture and preprocessor', 'run the Seq2SlateTransformerNet model wrapped with state and candidate preprocessors for slate ranking', 'verify that expected and scripted torch tensor outputs are equal using numpy array comparison', 'test that a JIT-compiled Seq2Slate model handles variable candidate and slate input lengths', 'create a NormalizationParameters object for continuous features with mean 0 and stddev 1', 'create a NormalizationParameters object for continuous actions with min -3 and max 3', 'test the change_cand_size_slate_ranking function with a prototype tuple and candidate size override', 'refactor change_cand_size_slate_ranking to support additional tensor dimensions for slate ranking prototypes', 'summarize the _cont_norm function that returns continuous feature normalization parameters', 'test the DiscreteDqnPredictorWrapper with a FullyConnectedDQN model and state preprocessor', 'test the ParametricDqnPredictorWrapper with state and action preprocessors for continuous actions', 'test the ActorPredictorWrapper with a FullyConnectedActor model and postprocessor', 'test the Seq2SlatePredictorWrapper with a transformer model for slate ranking', 'test the DeterminantalPointProcessPredictorWrapper with linear and RBF kernels for diverse ranking']
```

Usage

```
{'test_DiscreteDqnPredictorWrapper': 'test the DiscreteDqnPredictorWrapper with a FullyConnectedDQN model and state preprocessor', 'test_ParametricDqnPredictorWrapper': 'test the ParametricDqnPredictorWrapper with state and action preprocessors for continuous actions', 'test_ActorPredictorWrapper': 'test the ActorPredictorWrapper with a FullyConnectedActor model and postprocessor', 'test_Seq2SlatePredictorWrapper': 'test the Seq2SlatePredictorWrapper with a transformer model for slate ranking', 'test_DeterminantalPointProcessPredictorWrapper': 'test the DeterminantalPointProcessPredictorWrapper with linear and RBF kernels for diverse ranking'}
```

