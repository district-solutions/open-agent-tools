# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/test/evaluation/test_evaluation_data_page.py

Prompts

```
['test the EvaluationDataPage creation and off-policy evaluation estimators for seq2slate ranking logs', 'create a FakeSeq2SlateRewardNetwork that predicts rewards based on state and target output index', 'create a FakeSeq2SlateTransformerNet that returns ranked indices or log probabilities by mode', 'run the DoublyRobustEstimator to estimate direct method, IPS, and doubly robust values from an evaluation data page', 'run SwitchEstimator and SwitchDREstimator via OPEstimatorAdapter to verify equivalence with IPS, DM, and DR', 'convert an RLEstimatorInput log into an EvaluationDataPage with mdp ids, propensities, rewards, and action masks', 'test the sequential doubly robust OPE estimator by evaluating a target policy on a gridworld environment with noisy model', 'test slate ranking OPE evaluation using Direct Method, IPS, and Doubly Robust estimators on synthetic seq2slate logs', 'run OPEstimatorAdapter with DM, IPS, DR, Switch, and SwitchDR estimators on an EvaluationDataPage to get CPE estimates', 'create an EvaluationDataPage from seq2slate tensors using a transformer net and reward net with eval greedy flag']
```

Usage

```
{'test_evaluation_data_page_seq2slate': 'test the EvaluationDataPage creation and off-policy evaluation estimators for seq2slate ranking logs', 'create_fake_reward_network': 'create a FakeSeq2SlateRewardNetwork that predicts rewards based on state and target output index', 'create_fake_transformer_net': 'create a FakeSeq2SlateTransformerNet that returns ranked indices or log probabilities by mode', 'run_doubly_robust_estimator': 'run the DoublyRobustEstimator to estimate direct method, IPS, and doubly robust values from an evaluation data page', 'run_switch_estimators': 'run SwitchEstimator and SwitchDREstimator via OPEstimatorAdapter to verify equivalence with IPS, DM, and DR'}
```

## File: facebookresearch_reagent/reagent/test/evaluation/test_ope_integration.py

Prompts

```
['test the EvaluationDataPage creation and off-policy evaluation estimators for seq2slate ranking logs', 'create a FakeSeq2SlateRewardNetwork that predicts rewards based on state and target output index', 'create a FakeSeq2SlateTransformerNet that returns ranked indices or log probabilities by mode', 'run the DoublyRobustEstimator to estimate direct method, IPS, and doubly robust values from an evaluation data page', 'run SwitchEstimator and SwitchDREstimator via OPEstimatorAdapter to verify equivalence with IPS, DM, and DR', 'convert an RLEstimatorInput log into an EvaluationDataPage with mdp ids, propensities, rewards, and action masks', 'test the sequential doubly robust OPE estimator by evaluating a target policy on a gridworld environment with noisy model', 'test slate ranking OPE evaluation using Direct Method, IPS, and Doubly Robust estimators on synthetic seq2slate logs', 'run OPEstimatorAdapter with DM, IPS, DR, Switch, and SwitchDR estimators on an EvaluationDataPage to get CPE estimates', 'create an EvaluationDataPage from seq2slate tensors using a transformer net and reward net with eval greedy flag']
```

Usage

```
{'convert_rlestimator_input_to_edp': 'convert an RLEstimatorInput log into an EvaluationDataPage with mdp ids, propensities, rewards, and action masks', 'test_gridworld_sequential_adapter': 'test the sequential doubly robust OPE estimator by evaluating a target policy on a gridworld environment with noisy model', 'test_seq2slate_eval_data_page': 'test slate ranking OPE evaluation using Direct Method, IPS, and Doubly Robust estimators on synthetic seq2slate logs', 'run_ope_estimators_on_edp': 'run OPEstimatorAdapter with DM, IPS, DR, Switch, and SwitchDR estimators on an EvaluationDataPage to get CPE estimates', 'create_edp_from_tensors_seq2slate': 'create an EvaluationDataPage from seq2slate tensors using a transformer net and reward net with eval greedy flag'}
```

