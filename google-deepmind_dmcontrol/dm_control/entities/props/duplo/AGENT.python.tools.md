# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/entities/props/duplo/autotune.py

Prompts

```
['run the autotune script to tune Duplo stud radii for desired separation forces', 'tune the Duplo stud radius to achieve a desired separation force using bisection', 'measure the Duplo brick separation force for a given stud radius value', 'review the KeepBracketingSolutions class that wraps an objective function to track bracketing solutions', 'summarize the DESIRED_FORCES constant defining minimum, lower quartile, and maximum target forces', 'test the Duplo prop separation force is consistent when variation is zero across multiple seeds', 'test the Duplo prop separation force distribution stays within expected min max and median bounds', 'test the Duplo prop separation force is identical for the same random seed but different across seeds', 'test the Duplo class raises ValueError when color values are outside the 0 to 1 range', 'test that Duplo brick studs and holes align precisely when two bricks are stacked in physics simulation', 'create a function that stacks two Duplo bricks in a composer arena and returns the attachment frame', 'build a tool that measures the force needed to separate two Duplo bricks using binary search', 'run a simulation that stacks a top Duplo brick on a bottom brick with a freejoint', 'test the separation force measurement by bracketing min and max forces and bisecting to find the threshold', 'review the measure_separation_force function that applies upward force and checks height threshold for brick separation']
```

Usage

```
{'run_autotune_script': 'run the autotune script to tune Duplo stud radii for desired separation forces', 'tune_stud_radius': 'tune the Duplo stud radius to achieve a desired separation force using bisection', 'get_separation_force_for_radius': 'measure the Duplo brick separation force for a given stud radius value', 'review_KeepBracketingSolutions': 'review the KeepBracketingSolutions class that wraps an objective function to track bracketing solutions', 'summarize_DESIRED_FORCES': 'summarize the DESIRED_FORCES constant defining minimum, lower quartile, and maximum target forces'}
```

## File: google-deepmind_dmcontrol/dm_control/entities/props/duplo/duplo_test.py

Prompts

```
['run the autotune script to tune Duplo stud radii for desired separation forces', 'tune the Duplo stud radius to achieve a desired separation force using bisection', 'measure the Duplo brick separation force for a given stud radius value', 'review the KeepBracketingSolutions class that wraps an objective function to track bracketing solutions', 'summarize the DESIRED_FORCES constant defining minimum, lower quartile, and maximum target forces', 'test the Duplo prop separation force is consistent when variation is zero across multiple seeds', 'test the Duplo prop separation force distribution stays within expected min max and median bounds', 'test the Duplo prop separation force is identical for the same random seed but different across seeds', 'test the Duplo class raises ValueError when color values are outside the 0 to 1 range', 'test that Duplo brick studs and holes align precisely when two bricks are stacked in physics simulation', 'create a function that stacks two Duplo bricks in a composer arena and returns the attachment frame', 'build a tool that measures the force needed to separate two Duplo bricks using binary search', 'run a simulation that stacks a top Duplo brick on a bottom brick with a freejoint', 'test the separation force measurement by bracketing min and max forces and bisecting to find the threshold', 'review the measure_separation_force function that applies upward force and checks height threshold for brick separation']
```

Usage

```
{'test_duplo_separation_force_fixed': 'test the Duplo prop separation force is consistent when variation is zero across multiple seeds', 'test_duplo_separation_force_distribution': 'test the Duplo prop separation force distribution stays within expected min max and median bounds', 'test_duplo_separation_force_identical_seed': 'test the Duplo prop separation force is identical for the same random seed but different across seeds', 'test_duplo_color_validation': 'test the Duplo class raises ValueError when color values are outside the 0 to 1 range', 'test_duplo_stud_alignment': 'test that Duplo brick studs and holes align precisely when two bricks are stacked in physics simulation'}
```

## File: google-deepmind_dmcontrol/dm_control/entities/props/duplo/utils.py

Prompts

```
['run the autotune script to tune Duplo stud radii for desired separation forces', 'tune the Duplo stud radius to achieve a desired separation force using bisection', 'measure the Duplo brick separation force for a given stud radius value', 'review the KeepBracketingSolutions class that wraps an objective function to track bracketing solutions', 'summarize the DESIRED_FORCES constant defining minimum, lower quartile, and maximum target forces', 'test the Duplo prop separation force is consistent when variation is zero across multiple seeds', 'test the Duplo prop separation force distribution stays within expected min max and median bounds', 'test the Duplo prop separation force is identical for the same random seed but different across seeds', 'test the Duplo class raises ValueError when color values are outside the 0 to 1 range', 'test that Duplo brick studs and holes align precisely when two bricks are stacked in physics simulation', 'create a function that stacks two Duplo bricks in a composer arena and returns the attachment frame', 'build a tool that measures the force needed to separate two Duplo bricks using binary search', 'run a simulation that stacks a top Duplo brick on a bottom brick with a freejoint', 'test the separation force measurement by bracketing min and max forces and bisecting to find the threshold', 'review the measure_separation_force function that applies upward force and checks height threshold for brick separation']
```

Usage

```
{'stack_bricks': 'create a function that stacks two Duplo bricks in a composer arena and returns the attachment frame', 'measure_separation_force': 'build a tool that measures the force needed to separate two Duplo bricks using binary search', 'run_stack_bricks_simulation': 'run a simulation that stacks a top Duplo brick on a bottom brick with a freejoint', 'test_separation_force_bisection': 'test the separation force measurement by bracketing min and max forces and bisecting to find the threshold', 'review_measure_separation_force': 'review the measure_separation_force function that applies upward force and checks height threshold for brick separation'}
```

