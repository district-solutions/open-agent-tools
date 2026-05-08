# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/compiler_gym/envs/loop_tool/service/loop_tool_compilation_session.py

Prompts

```
['create a LoopToolCompilationSession instance with a working directory, action space, and benchmark URI', 'apply a toggle_mode, up, down, or toggle_thread action to the loop tool compilation session', 'resize the loop order at the current cursor by incrementing or decrementing split sizes', 'lower the IR to a LoopTree with parallel annotations for CPU or CUDA backends', 'get an observation for flops, loop_tree, or action_state from the compilation session']
```

Usage

```
{'create_loop_tool_session': 'create a LoopToolCompilationSession instance with a working directory, action space, and benchmark URI', 'apply_loop_tool_action': 'apply a toggle_mode, up, down, or toggle_thread action to the loop tool compilation session', 'resize_loop_order': 'resize the loop order at the current cursor by incrementing or decrementing split sizes', 'lower_loop_tree': 'lower the IR to a LoopTree with parallel annotations for CPU or CUDA backends', 'get_loop_tool_observation': 'get an observation for flops, loop_tree, or action_state from the compilation session'}
```

