# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/composer/observation/fake_physics.py

Prompts

```
['create a FakePhysics instance to unit test the dm_control observation framework', 'test the FakePhysics step method to increment the internal step counter', 'test the FakePhysics observables property to return registered Generic observable objects', 'test the FakePhysics twice method to return two times the step counter value', 'test the FakePhysics reset method to zero the step counter and clear state', 'create a Buffer instance with a given buffer size, shape, and dtype for observation management', 'insert a new observation with timestamp, delay, and value into the observation buffer', 'read the buffered observation array at a given current time timestamp', 'create an InFlightObservation object with a timestamp, delay, and observation value', 'drop upcoming observations from the schedule that will never be delivered within buffer size', 'test the Buffer class to handle observations arriving out of order with varying delays', 'test the Buffer class to strip singleton dimensions when buffer size is one', 'test the Buffer drop_unobserved_upcoming_items method to prune observation schedules that would never be read', 'test the Buffer read method to return correctly delayed observations at each timestep', 'test the InFlightObservation class to sort observations by their arrival time', 'create an Updater instance with observables dict to manage observation buffers for a DM Control environment', 'reset the Updater with physics and random_state to initialize observation buffers and update schedules', 'call observation_spec on the Updater to retrieve Array or BoundedArray specs for all enabled observations', 'call prepare_for_next_control_step to simulate the next control step and optimize the observation update schedule', 'call get_observation on the Updater to retrieve the current aggregated observation values as a dict', 'run the absltest suite to test the observation updater module', 'test nested observation specs and values using lists or tuples of observables', 'test automatic observation spec inference from physics observables with buffer sizes', 'test that custom array spec subclasses are preserved through the updater', 'test observation buffering with deterministic variable update intervals and delays']
```

Usage

```
{'create_fake_physics_instance': 'create a FakePhysics instance to unit test the dm_control observation framework', 'test_step_counter': 'test the FakePhysics step method to increment the internal step counter', 'test_observables_property': 'test the FakePhysics observables property to return registered Generic observable objects', 'test_twice_method': 'test the FakePhysics twice method to return two times the step counter value', 'test_reset_method': 'test the FakePhysics reset method to zero the step counter and clear state'}
```

## File: google-deepmind_dmcontrol/dm_control/composer/observation/obs_buffer.py

Prompts

```
['create a FakePhysics instance to unit test the dm_control observation framework', 'test the FakePhysics step method to increment the internal step counter', 'test the FakePhysics observables property to return registered Generic observable objects', 'test the FakePhysics twice method to return two times the step counter value', 'test the FakePhysics reset method to zero the step counter and clear state', 'create a Buffer instance with a given buffer size, shape, and dtype for observation management', 'insert a new observation with timestamp, delay, and value into the observation buffer', 'read the buffered observation array at a given current time timestamp', 'create an InFlightObservation object with a timestamp, delay, and observation value', 'drop upcoming observations from the schedule that will never be delivered within buffer size', 'test the Buffer class to handle observations arriving out of order with varying delays', 'test the Buffer class to strip singleton dimensions when buffer size is one', 'test the Buffer drop_unobserved_upcoming_items method to prune observation schedules that would never be read', 'test the Buffer read method to return correctly delayed observations at each timestep', 'test the InFlightObservation class to sort observations by their arrival time', 'create an Updater instance with observables dict to manage observation buffers for a DM Control environment', 'reset the Updater with physics and random_state to initialize observation buffers and update schedules', 'call observation_spec on the Updater to retrieve Array or BoundedArray specs for all enabled observations', 'call prepare_for_next_control_step to simulate the next control step and optimize the observation update schedule', 'call get_observation on the Updater to retrieve the current aggregated observation values as a dict', 'run the absltest suite to test the observation updater module', 'test nested observation specs and values using lists or tuples of observables', 'test automatic observation spec inference from physics observables with buffer sizes', 'test that custom array spec subclasses are preserved through the updater', 'test observation buffering with deterministic variable update intervals and delays']
```

Usage

```
{'create_buffer': 'create a Buffer instance with a given buffer size, shape, and dtype for observation management', 'insert_observation': 'insert a new observation with timestamp, delay, and value into the observation buffer', 'read_buffer': 'read the buffered observation array at a given current time timestamp', 'create_inflight_observation': 'create an InFlightObservation object with a timestamp, delay, and observation value', 'drop_unobserved_items': 'drop upcoming observations from the schedule that will never be delivered within buffer size'}
```

## File: google-deepmind_dmcontrol/dm_control/composer/observation/obs_buffer_test.py

Prompts

```
['create a FakePhysics instance to unit test the dm_control observation framework', 'test the FakePhysics step method to increment the internal step counter', 'test the FakePhysics observables property to return registered Generic observable objects', 'test the FakePhysics twice method to return two times the step counter value', 'test the FakePhysics reset method to zero the step counter and clear state', 'create a Buffer instance with a given buffer size, shape, and dtype for observation management', 'insert a new observation with timestamp, delay, and value into the observation buffer', 'read the buffered observation array at a given current time timestamp', 'create an InFlightObservation object with a timestamp, delay, and observation value', 'drop upcoming observations from the schedule that will never be delivered within buffer size', 'test the Buffer class to handle observations arriving out of order with varying delays', 'test the Buffer class to strip singleton dimensions when buffer size is one', 'test the Buffer drop_unobserved_upcoming_items method to prune observation schedules that would never be read', 'test the Buffer read method to return correctly delayed observations at each timestep', 'test the InFlightObservation class to sort observations by their arrival time', 'create an Updater instance with observables dict to manage observation buffers for a DM Control environment', 'reset the Updater with physics and random_state to initialize observation buffers and update schedules', 'call observation_spec on the Updater to retrieve Array or BoundedArray specs for all enabled observations', 'call prepare_for_next_control_step to simulate the next control step and optimize the observation update schedule', 'call get_observation on the Updater to retrieve the current aggregated observation values as a dict', 'run the absltest suite to test the observation updater module', 'test nested observation specs and values using lists or tuples of observables', 'test automatic observation spec inference from physics observables with buffer sizes', 'test that custom array spec subclasses are preserved through the updater', 'test observation buffering with deterministic variable update intervals and delays']
```

Usage

```
{'test_Buffer_out_of_order_arrival': 'test the Buffer class to handle observations arriving out of order with varying delays', 'test_Buffer_strip_singleton_dimension': 'test the Buffer class to strip singleton dimensions when buffer size is one', 'test_Buffer_drop_unobserved_upcoming_items': 'test the Buffer drop_unobserved_upcoming_items method to prune observation schedules that would never be read', 'test_Buffer_read_with_delay': 'test the Buffer read method to return correctly delayed observations at each timestep', 'test_InFlightObservation_sorting': 'test the InFlightObservation class to sort observations by their arrival time'}
```

## File: google-deepmind_dmcontrol/dm_control/composer/observation/updater.py

Prompts

```
['create a FakePhysics instance to unit test the dm_control observation framework', 'test the FakePhysics step method to increment the internal step counter', 'test the FakePhysics observables property to return registered Generic observable objects', 'test the FakePhysics twice method to return two times the step counter value', 'test the FakePhysics reset method to zero the step counter and clear state', 'create a Buffer instance with a given buffer size, shape, and dtype for observation management', 'insert a new observation with timestamp, delay, and value into the observation buffer', 'read the buffered observation array at a given current time timestamp', 'create an InFlightObservation object with a timestamp, delay, and observation value', 'drop upcoming observations from the schedule that will never be delivered within buffer size', 'test the Buffer class to handle observations arriving out of order with varying delays', 'test the Buffer class to strip singleton dimensions when buffer size is one', 'test the Buffer drop_unobserved_upcoming_items method to prune observation schedules that would never be read', 'test the Buffer read method to return correctly delayed observations at each timestep', 'test the InFlightObservation class to sort observations by their arrival time', 'create an Updater instance with observables dict to manage observation buffers for a DM Control environment', 'reset the Updater with physics and random_state to initialize observation buffers and update schedules', 'call observation_spec on the Updater to retrieve Array or BoundedArray specs for all enabled observations', 'call prepare_for_next_control_step to simulate the next control step and optimize the observation update schedule', 'call get_observation on the Updater to retrieve the current aggregated observation values as a dict', 'run the absltest suite to test the observation updater module', 'test nested observation specs and values using lists or tuples of observables', 'test automatic observation spec inference from physics observables with buffer sizes', 'test that custom array spec subclasses are preserved through the updater', 'test observation buffering with deterministic variable update intervals and delays']
```

Usage

```
{'create_updater_for_observables': 'create an Updater instance with observables dict to manage observation buffers for a DM Control environment', 'reset_updater_buffers': 'reset the Updater with physics and random_state to initialize observation buffers and update schedules', 'get_observation_spec': 'call observation_spec on the Updater to retrieve Array or BoundedArray specs for all enabled observations', 'prepare_for_next_control_step': 'call prepare_for_next_control_step to simulate the next control step and optimize the observation update schedule', 'get_observation_values': 'call get_observation on the Updater to retrieve the current aggregated observation values as a dict'}
```

## File: google-deepmind_dmcontrol/dm_control/composer/observation/updater_test.py

Prompts

```
['create a FakePhysics instance to unit test the dm_control observation framework', 'test the FakePhysics step method to increment the internal step counter', 'test the FakePhysics observables property to return registered Generic observable objects', 'test the FakePhysics twice method to return two times the step counter value', 'test the FakePhysics reset method to zero the step counter and clear state', 'create a Buffer instance with a given buffer size, shape, and dtype for observation management', 'insert a new observation with timestamp, delay, and value into the observation buffer', 'read the buffered observation array at a given current time timestamp', 'create an InFlightObservation object with a timestamp, delay, and observation value', 'drop upcoming observations from the schedule that will never be delivered within buffer size', 'test the Buffer class to handle observations arriving out of order with varying delays', 'test the Buffer class to strip singleton dimensions when buffer size is one', 'test the Buffer drop_unobserved_upcoming_items method to prune observation schedules that would never be read', 'test the Buffer read method to return correctly delayed observations at each timestep', 'test the InFlightObservation class to sort observations by their arrival time', 'create an Updater instance with observables dict to manage observation buffers for a DM Control environment', 'reset the Updater with physics and random_state to initialize observation buffers and update schedules', 'call observation_spec on the Updater to retrieve Array or BoundedArray specs for all enabled observations', 'call prepare_for_next_control_step to simulate the next control step and optimize the observation update schedule', 'call get_observation on the Updater to retrieve the current aggregated observation values as a dict', 'run the absltest suite to test the observation updater module', 'test nested observation specs and values using lists or tuples of observables', 'test automatic observation spec inference from physics observables with buffer sizes', 'test that custom array spec subclasses are preserved through the updater', 'test observation buffering with deterministic variable update intervals and delays']
```

Usage

```
{'run_updater_test': 'run the absltest suite to test the observation updater module', 'test_nested_specs_and_values': 'test nested observation specs and values using lists or tuples of observables', 'test_observation_spec_inference': 'test automatic observation spec inference from physics observables with buffer sizes', 'test_custom_spec_type_passed_through': 'test that custom array spec subclasses are preserved through the updater', 'test_variable_rates_and_delays': 'test observation buffering with deterministic variable update intervals and delays'}
```

