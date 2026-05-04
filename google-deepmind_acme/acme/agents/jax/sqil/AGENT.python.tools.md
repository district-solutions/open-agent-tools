# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/sqil/builder.py

Prompts

```
['build a SQIL agent using SQILBuilder with an off-policy RL agent and demonstration iterator', 'create interleaved samples mixing expert demonstrations with reward 1 and replay samples with reward 0', 'create a dataset iterator that alternates between expert demonstration data and policy replay data', 'build a learner from SQILBuilder by delegating to the underlying RL agent with a scoped counter', 'create replay buffer tables for the SQIL agent by delegating to the underlying RL agent builder', 'test the SQIL iterator that interleaves demonstration transitions with replay samples', 'review the BuilderTest class and its test_sqil_iterator test method', 'run the absltest-based BuilderTest suite to verify SQIL sample generation', 'summarize how _generate_sqil_samples interleaves demonstration and replay data', 'refactor the BuilderTest assertions to use a different testing pattern']
```

Usage

```
{'build_sqil_agent': 'build a SQIL agent using SQILBuilder with an off-policy RL agent and demonstration iterator', 'generate_sqil_samples': 'create interleaved samples mixing expert demonstrations with reward 1 and replay samples with reward 0', 'create_dataset_iterator': 'create a dataset iterator that alternates between expert demonstration data and policy replay data', 'build_learner': 'build a learner from SQILBuilder by delegating to the underlying RL agent with a scoped counter', 'create_replay_tables': 'create replay buffer tables for the SQIL agent by delegating to the underlying RL agent builder'}
```

## File: google-deepmind_acme/acme/agents/jax/sqil/builder_test.py

Prompts

```
['build a SQIL agent using SQILBuilder with an off-policy RL agent and demonstration iterator', 'create interleaved samples mixing expert demonstrations with reward 1 and replay samples with reward 0', 'create a dataset iterator that alternates between expert demonstration data and policy replay data', 'build a learner from SQILBuilder by delegating to the underlying RL agent with a scoped counter', 'create replay buffer tables for the SQIL agent by delegating to the underlying RL agent builder', 'test the SQIL iterator that interleaves demonstration transitions with replay samples', 'review the BuilderTest class and its test_sqil_iterator test method', 'run the absltest-based BuilderTest suite to verify SQIL sample generation', 'summarize how _generate_sqil_samples interleaves demonstration and replay data', 'refactor the BuilderTest assertions to use a different testing pattern']
```

Usage

```
{'test_sqil_iterator': 'test the SQIL iterator that interleaves demonstration transitions with replay samples', 'review_buildertest_class': 'review the BuilderTest class and its test_sqil_iterator test method', 'run_buildertest_tests': 'run the absltest-based BuilderTest suite to verify SQIL sample generation', 'summarize_generate_sqil_samples': 'summarize how _generate_sqil_samples interleaves demonstration and replay data', 'refactor_buildertest_assertions': 'refactor the BuilderTest assertions to use a different testing pattern'}
```

