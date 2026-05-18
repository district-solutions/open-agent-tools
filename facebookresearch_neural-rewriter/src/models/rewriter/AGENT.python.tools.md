# Agent Python Tools

- repo: facebookresearch/neural-rewriter
- repo_uri: https://github.com/facebookresearch/neural-rewriter

## File: facebookresearch_neural-rewriter/src/models/rewriter/HalideRewriter.py

Prompts

```
['build a HalideRewriter instance with term and operator vocabularies for expression simplification', 'run algebraic constant folding on an expression tree node to simplify arithmetic operations', 'run comparison constant folding on an expression tree to simplify less than or equal checks', 'run select expression simplification to collapse conditional selects with constant conditions or equal branches', 'run min or max distribution over comparison operators to split into conjunctive or disjunctive forms', 'move a job to a new schedule time based on a neighbor job in the job scheduling DAG', 'review the jspRewriter move method that reschedules jobs and updates DAG edges and embeddings', 'refactor the jspRewriter move method to improve the cascading reschedule loop over time steps', 'summarize the jspRewriter class used for job scheduling problem rewriting and DAG manipulation', 'test the jspRewriter move method with a Dag instance and two job indices to verify rescheduling', 'build a python module that creates a vrpRewriter instance for vehicle routing problem optimization', 'create a move operation that swaps two vehicle routes and rebuilds the route considering capacity constraints', 'test the vrpRewriter move method by swapping routes and verifying the resulting vehicle state and total distance', 'refactor the vrpRewriter move method to support additional route manipulation strategies beyond simple swaps', 'review the vrpRewriter class and its move method for vehicle routing problem route optimization logic']
```

Usage

```
{'build_HalideRewriter': 'build a HalideRewriter instance with term and operator vocabularies for expression simplification', 'run_alg_const_calculation': 'run algebraic constant folding on an expression tree node to simplify arithmetic operations', 'run_cmp_const_calculation': 'run comparison constant folding on an expression tree to simplify less than or equal checks', 'run_select_simplification': 'run select expression simplification to collapse conditional selects with constant conditions or equal branches', 'run_minmax_distribution': 'run min or max distribution over comparison operators to split into conjunctive or disjunctive forms'}
```

## File: facebookresearch_neural-rewriter/src/models/rewriter/jspRewriter.py

Prompts

```
['build a HalideRewriter instance with term and operator vocabularies for expression simplification', 'run algebraic constant folding on an expression tree node to simplify arithmetic operations', 'run comparison constant folding on an expression tree to simplify less than or equal checks', 'run select expression simplification to collapse conditional selects with constant conditions or equal branches', 'run min or max distribution over comparison operators to split into conjunctive or disjunctive forms', 'move a job to a new schedule time based on a neighbor job in the job scheduling DAG', 'review the jspRewriter move method that reschedules jobs and updates DAG edges and embeddings', 'refactor the jspRewriter move method to improve the cascading reschedule loop over time steps', 'summarize the jspRewriter class used for job scheduling problem rewriting and DAG manipulation', 'test the jspRewriter move method with a Dag instance and two job indices to verify rescheduling', 'build a python module that creates a vrpRewriter instance for vehicle routing problem optimization', 'create a move operation that swaps two vehicle routes and rebuilds the route considering capacity constraints', 'test the vrpRewriter move method by swapping routes and verifying the resulting vehicle state and total distance', 'refactor the vrpRewriter move method to support additional route manipulation strategies beyond simple swaps', 'review the vrpRewriter class and its move method for vehicle routing problem route optimization logic']
```

Usage

```
{'move_job_in_schedule': 'move a job to a new schedule time based on a neighbor job in the job scheduling DAG', 'review_jspRewriter_move': 'review the jspRewriter move method that reschedules jobs and updates DAG edges and embeddings', 'refactor_jspRewriter_move': 'refactor the jspRewriter move method to improve the cascading reschedule loop over time steps', 'summarize_jspRewriter': 'summarize the jspRewriter class used for job scheduling problem rewriting and DAG manipulation', 'test_jspRewriter_move': 'test the jspRewriter move method with a Dag instance and two job indices to verify rescheduling'}
```

## File: facebookresearch_neural-rewriter/src/models/rewriter/vrpRewriter.py

Prompts

```
['build a HalideRewriter instance with term and operator vocabularies for expression simplification', 'run algebraic constant folding on an expression tree node to simplify arithmetic operations', 'run comparison constant folding on an expression tree to simplify less than or equal checks', 'run select expression simplification to collapse conditional selects with constant conditions or equal branches', 'run min or max distribution over comparison operators to split into conjunctive or disjunctive forms', 'move a job to a new schedule time based on a neighbor job in the job scheduling DAG', 'review the jspRewriter move method that reschedules jobs and updates DAG edges and embeddings', 'refactor the jspRewriter move method to improve the cascading reschedule loop over time steps', 'summarize the jspRewriter class used for job scheduling problem rewriting and DAG manipulation', 'test the jspRewriter move method with a Dag instance and two job indices to verify rescheduling', 'build a python module that creates a vrpRewriter instance for vehicle routing problem optimization', 'create a move operation that swaps two vehicle routes and rebuilds the route considering capacity constraints', 'test the vrpRewriter move method by swapping routes and verifying the resulting vehicle state and total distance', 'refactor the vrpRewriter move method to support additional route manipulation strategies beyond simple swaps', 'review the vrpRewriter class and its move method for vehicle routing problem route optimization logic']
```

Usage

```
{'build_vrp_rewriter': 'build a python module that creates a vrpRewriter instance for vehicle routing problem optimization', 'create_move_operation': 'create a move operation that swaps two vehicle routes and rebuilds the route considering capacity constraints', 'test_vrpRewriter_move': 'test the vrpRewriter move method by swapping routes and verifying the resulting vehicle state and total distance', 'refactor_vrpRewriter_move': 'refactor the vrpRewriter move method to support additional route manipulation strategies beyond simple swaps', 'review_vrpRewriter_class': 'review the vrpRewriter class and its move method for vehicle routing problem route optimization logic'}
```

