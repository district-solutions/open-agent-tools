# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/clients/tests/test_async_client.py

Prompts

```
['test AsyncClientFactory.create to verify client start and end times match expected event schedule', 'test AsyncTrainingEventGenerator produces sequential training schedules where each client finishes before the next starts', 'test PerExampleGaussianDurationDistributionConfig to verify clients with fewer examples finish training first', 'test AsyncClientDevice training_started, train_local_model, and training_ended lifecycle methods end to end', 'test AsyncClientDevice less than comparison operator to verify correct heap ordering by event time', 'test the base Client class training loop with fake data and verify model delta generation', 'test the DPClient class differential privacy engine with noise multiplier and gradient clipping settings', 'test the MimeClient class server optimizer state reload and control variate handling', 'test the FedShuffleClient class local update generation with shuffled batch order and multiple epochs', 'calculate the differential privacy epsilon value using RDP analysis given sample rate noise multiplier and steps']
```

Usage

```
{'test_async_client_event_generation': 'test AsyncClientFactory.create to verify client start and end times match expected event schedule', 'test_sequential_training_schedule': 'test AsyncTrainingEventGenerator produces sequential training schedules where each client finishes before the next starts', 'test_per_example_gaussian_duration': 'test PerExampleGaussianDurationDistributionConfig to verify clients with fewer examples finish training first', 'test_async_client_training_lifecycle': 'test AsyncClientDevice training_started, train_local_model, and training_ended lifecycle methods end to end', 'test_async_client_less_than': 'test AsyncClientDevice less than comparison operator to verify correct heap ordering by event time'}
```

## File: facebookresearch_flsim/flsim/clients/tests/test_client.py

Prompts

```
['test AsyncClientFactory.create to verify client start and end times match expected event schedule', 'test AsyncTrainingEventGenerator produces sequential training schedules where each client finishes before the next starts', 'test PerExampleGaussianDurationDistributionConfig to verify clients with fewer examples finish training first', 'test AsyncClientDevice training_started, train_local_model, and training_ended lifecycle methods end to end', 'test AsyncClientDevice less than comparison operator to verify correct heap ordering by event time', 'test the base Client class training loop with fake data and verify model delta generation', 'test the DPClient class differential privacy engine with noise multiplier and gradient clipping settings', 'test the MimeClient class server optimizer state reload and control variate handling', 'test the FedShuffleClient class local update generation with shuffled batch order and multiple epochs', 'calculate the differential privacy epsilon value using RDP analysis given sample rate noise multiplier and steps']
```

Usage

```
{'test_base_client_training': 'test the base Client class training loop with fake data and verify model delta generation', 'test_dp_client_privacy': 'test the DPClient class differential privacy engine with noise multiplier and gradient clipping settings', 'test_mime_client_server_state': 'test the MimeClient class server optimizer state reload and control variate handling', 'test_fedshuffle_client_update': 'test the FedShuffleClient class local update generation with shuffled batch order and multiple epochs', 'calc_eps_privacy': 'calculate the differential privacy epsilon value using RDP analysis given sample rate noise multiplier and steps'}
```

