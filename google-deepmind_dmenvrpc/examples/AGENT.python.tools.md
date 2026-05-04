# Agent Python Tools

- repo: google-deepmind/dmenvrpc
- repo_uri: https://github.com/google-deepmind/dm_env_rpc

## File: google-deepmind_dmenvrpc/examples/catch_environment.py

Prompts

```
['run the CatchEnvironmentService gRPC server to serve a Catch game environment over dm_env_rpc', 'create a CatchGame instance with specified rows, columns, and a random seed for the ball position', 'step the Catch game environment by sending a paddle action via the gRPC step message', 'reset the Catch game world with an optional seed setting via the gRPC reset message', 'join the Catch game world and receive action and observation specs via the gRPC join message', 'test the CatchGame class draw_board method to verify initial board state and shape', 'test the CatchGame update method to verify ball drops and paddle moves on action', 'test the CatchGame has_terminated and reward methods to verify game end conditions', 'test the ServerConnection class to start a gRPC server with CatchEnvironmentService and create a channel', 'test the DmEnvAdaptor wrapping an RPC connection to provide a dm_env compatible interface']
```

Usage

```
{'run_catch_grpc_server': 'run the CatchEnvironmentService gRPC server to serve a Catch game environment over dm_env_rpc', 'create_catch_game': 'create a CatchGame instance with specified rows, columns, and a random seed for the ball position', 'step_catch_environment': 'step the Catch game environment by sending a paddle action via the gRPC step message', 'reset_catch_world': 'reset the Catch game world with an optional seed setting via the gRPC reset message', 'join_catch_world': 'join the Catch game world and receive action and observation specs via the gRPC join message'}
```

## File: google-deepmind_dmenvrpc/examples/catch_test.py

Prompts

```
['run the CatchEnvironmentService gRPC server to serve a Catch game environment over dm_env_rpc', 'create a CatchGame instance with specified rows, columns, and a random seed for the ball position', 'step the Catch game environment by sending a paddle action via the gRPC step message', 'reset the Catch game world with an optional seed setting via the gRPC reset message', 'join the Catch game world and receive action and observation specs via the gRPC join message', 'test the CatchGame class draw_board method to verify initial board state and shape', 'test the CatchGame update method to verify ball drops and paddle moves on action', 'test the CatchGame has_terminated and reward methods to verify game end conditions', 'test the ServerConnection class to start a gRPC server with CatchEnvironmentService and create a channel', 'test the DmEnvAdaptor wrapping an RPC connection to provide a dm_env compatible interface']
```

Usage

```
{'test_catchgame_draw_board': 'test the CatchGame class draw_board method to verify initial board state and shape', 'test_catchgame_update_action': 'test the CatchGame update method to verify ball drops and paddle moves on action', 'test_catchgame_termination_reward': 'test the CatchGame has_terminated and reward methods to verify game end conditions', 'test_server_connection_grpc': 'test the ServerConnection class to start a gRPC server with CatchEnvironmentService and create a channel', 'test_dmenv_adaptor_integration': 'test the DmEnvAdaptor wrapping an RPC connection to provide a dm_env compatible interface'}
```

