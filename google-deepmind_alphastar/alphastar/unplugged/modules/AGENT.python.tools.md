# Agent Python Tools

- repo: google-deepmind/alphastar
- repo_uri: https://github.com/google-deepmind/alphastar

## File: google-deepmind_alphastar/alphastar/unplugged/modules/learner.py

Prompts

```
['build a SupervisedLearner with an architecture builder, loss builder, optax optimizer, and reverb data source', 'run a single SGD training step on the SupervisedLearner and log the loss and gradient metrics', 'save the current TrainingState including network parameters, optimizer state, and RNG key from the learner', 'restore a previously saved TrainingState and replicate it across all local devices for training', 'get the current network parameters from the first replica of the SupervisedLearner state', 'test the SupervisedLearner with alphastar.dummy and alphastar.lite architectures using parameterized test cases', 'run the setUpModule function to disable JAX optimizations before running learner tests', 'run the tearDownModule function to restore JAX config after learner tests complete', 'test the DistributedAgentLearnerTest class to verify integration of learner with dummy and lite architectures', 'review the test_agent_learner method that configures experiment settings and runs SupervisedLearner step iterations']
```

Usage

```
{'build_supervised_learner': 'build a SupervisedLearner with an architecture builder, loss builder, optax optimizer, and reverb data source', 'run_training_step': 'run a single SGD training step on the SupervisedLearner and log the loss and gradient metrics', 'save_training_state': 'save the current TrainingState including network parameters, optimizer state, and RNG key from the learner', 'restore_training_state': 'restore a previously saved TrainingState and replicate it across all local devices for training', 'get_learner_variables': 'get the current network parameters from the first replica of the SupervisedLearner state'}
```

## File: google-deepmind_alphastar/alphastar/unplugged/modules/learner_test.py

Prompts

```
['build a SupervisedLearner with an architecture builder, loss builder, optax optimizer, and reverb data source', 'run a single SGD training step on the SupervisedLearner and log the loss and gradient metrics', 'save the current TrainingState including network parameters, optimizer state, and RNG key from the learner', 'restore a previously saved TrainingState and replicate it across all local devices for training', 'get the current network parameters from the first replica of the SupervisedLearner state', 'test the SupervisedLearner with alphastar.dummy and alphastar.lite architectures using parameterized test cases', 'run the setUpModule function to disable JAX optimizations before running learner tests', 'run the tearDownModule function to restore JAX config after learner tests complete', 'test the DistributedAgentLearnerTest class to verify integration of learner with dummy and lite architectures', 'review the test_agent_learner method that configures experiment settings and runs SupervisedLearner step iterations']
```

Usage

```
{'test_supervised_learner': 'test the SupervisedLearner with alphastar.dummy and alphastar.lite architectures using parameterized test cases', 'run_setUpModule': 'run the setUpModule function to disable JAX optimizations before running learner tests', 'run_tearDownModule': 'run the tearDownModule function to restore JAX config after learner tests complete', 'test_DistributedAgentLearnerTest': 'test the DistributedAgentLearnerTest class to verify integration of learner with dummy and lite architectures', 'review_test_agent_learner': 'review the test_agent_learner method that configures experiment settings and runs SupervisedLearner step iterations'}
```

