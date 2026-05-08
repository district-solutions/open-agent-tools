# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/interpreter/craftassist/tests/test_conditions.py

Prompts

```
['test the MoveDirectionUntilTest class to verify go left until cow is closer than 2 steps', 'test the FollowUntilTest class to verify follow the cow for 18 seconds or 2 minutes', 'test the DigRemoveConditionTest class to verify dig a hole 2 times command', 'run the add_sequence_mob helper to add a LoopMob with a movement sequence to the world', 'review the STOP_CONDITION_COMMANDS usage patterns for go left until, follow, and dig conditions', 'run the TwoCubesInterpreterTest suite to test build, destroy, move, and copy commands in a two-cube world', 'run the FillTest suite to test filling holes with default or specified block types', 'run the DestroyEverythingTest to verify the interpreter destroys all placed blocks in the world', 'run the DigTest suite to test single and n-by-n hole digging commands', 'run the SpawnSheep test to verify spawning a specified number of sheep mobs', 'test the size_str_to_int function by running the TestSizeWords unit test suite', 'test the size_str_to_int function with modifier phrases like really big', 'run the TestSizeWords unittest class to validate size word to integer conversion', 'review the TestSizeWords class and its assert_in_range helper method', 'summarize the test_size_words module that tests size word parsing functionality', 'test the UndoTest class to verify undo functionality restores destroyed Minecraft block objects with their original tags', 'run the UndoTest unit test suite to validate the craftassist interpreter undo command workflow', 'review the UndoTest class and test_undo_destroy method for undo destroy confirmation flow', 'refactor the UndoTest class to remove the speaker sleep TODO and use distinct speakers', 'summarize the UndoTest class which tests block object destruction, tagging, and undo confirmation via dialogue']
```

Usage

```
{'test_move_direction_until_condition': 'test the MoveDirectionUntilTest class to verify go left until cow is closer than 2 steps', 'test_follow_until_condition': 'test the FollowUntilTest class to verify follow the cow for 18 seconds or 2 minutes', 'test_dig_remove_condition': 'test the DigRemoveConditionTest class to verify dig a hole 2 times command', 'run_add_sequence_mob_helper': 'run the add_sequence_mob helper to add a LoopMob with a movement sequence to the world', 'review_stop_condition_commands': 'review the STOP_CONDITION_COMMANDS usage patterns for go left until, follow, and dig conditions'}
```

## File: facebookresearch_fairo/droidlet/interpreter/craftassist/tests/test_interpreter.py

Prompts

```
['test the MoveDirectionUntilTest class to verify go left until cow is closer than 2 steps', 'test the FollowUntilTest class to verify follow the cow for 18 seconds or 2 minutes', 'test the DigRemoveConditionTest class to verify dig a hole 2 times command', 'run the add_sequence_mob helper to add a LoopMob with a movement sequence to the world', 'review the STOP_CONDITION_COMMANDS usage patterns for go left until, follow, and dig conditions', 'run the TwoCubesInterpreterTest suite to test build, destroy, move, and copy commands in a two-cube world', 'run the FillTest suite to test filling holes with default or specified block types', 'run the DestroyEverythingTest to verify the interpreter destroys all placed blocks in the world', 'run the DigTest suite to test single and n-by-n hole digging commands', 'run the SpawnSheep test to verify spawning a specified number of sheep mobs', 'test the size_str_to_int function by running the TestSizeWords unit test suite', 'test the size_str_to_int function with modifier phrases like really big', 'run the TestSizeWords unittest class to validate size word to integer conversion', 'review the TestSizeWords class and its assert_in_range helper method', 'summarize the test_size_words module that tests size word parsing functionality', 'test the UndoTest class to verify undo functionality restores destroyed Minecraft block objects with their original tags', 'run the UndoTest unit test suite to validate the craftassist interpreter undo command workflow', 'review the UndoTest class and test_undo_destroy method for undo destroy confirmation flow', 'refactor the UndoTest class to remove the speaker sleep TODO and use distinct speakers', 'summarize the UndoTest class which tests block object destruction, tagging, and undo confirmation via dialogue']
```

Usage

```
{'run_TwoCubesInterpreterTest': 'run the TwoCubesInterpreterTest suite to test build, destroy, move, and copy commands in a two-cube world', 'run_FillTest': 'run the FillTest suite to test filling holes with default or specified block types', 'run_DestroyEverythingTest': 'run the DestroyEverythingTest to verify the interpreter destroys all placed blocks in the world', 'run_DigTest': 'run the DigTest suite to test single and n-by-n hole digging commands', 'run_SpawnSheep': 'run the SpawnSheep test to verify spawning a specified number of sheep mobs'}
```

## File: facebookresearch_fairo/droidlet/interpreter/craftassist/tests/test_size_words.py

Prompts

```
['test the MoveDirectionUntilTest class to verify go left until cow is closer than 2 steps', 'test the FollowUntilTest class to verify follow the cow for 18 seconds or 2 minutes', 'test the DigRemoveConditionTest class to verify dig a hole 2 times command', 'run the add_sequence_mob helper to add a LoopMob with a movement sequence to the world', 'review the STOP_CONDITION_COMMANDS usage patterns for go left until, follow, and dig conditions', 'run the TwoCubesInterpreterTest suite to test build, destroy, move, and copy commands in a two-cube world', 'run the FillTest suite to test filling holes with default or specified block types', 'run the DestroyEverythingTest to verify the interpreter destroys all placed blocks in the world', 'run the DigTest suite to test single and n-by-n hole digging commands', 'run the SpawnSheep test to verify spawning a specified number of sheep mobs', 'test the size_str_to_int function by running the TestSizeWords unit test suite', 'test the size_str_to_int function with modifier phrases like really big', 'run the TestSizeWords unittest class to validate size word to integer conversion', 'review the TestSizeWords class and its assert_in_range helper method', 'summarize the test_size_words module that tests size word parsing functionality', 'test the UndoTest class to verify undo functionality restores destroyed Minecraft block objects with their original tags', 'run the UndoTest unit test suite to validate the craftassist interpreter undo command workflow', 'review the UndoTest class and test_undo_destroy method for undo destroy confirmation flow', 'refactor the UndoTest class to remove the speaker sleep TODO and use distinct speakers', 'summarize the UndoTest class which tests block object destruction, tagging, and undo confirmation via dialogue']
```

Usage

```
{'test_size_str_to_int': 'test the size_str_to_int function by running the TestSizeWords unit test suite', 'test_size_str_to_int_mod': 'test the size_str_to_int function with modifier phrases like really big', 'run_test_size_words': 'run the TestSizeWords unittest class to validate size word to integer conversion', 'review_test_size_words_class': 'review the TestSizeWords class and its assert_in_range helper method', 'summarize_test_size_words': 'summarize the test_size_words module that tests size word parsing functionality'}
```

## File: facebookresearch_fairo/droidlet/interpreter/craftassist/tests/test_undo.py

Prompts

```
['test the MoveDirectionUntilTest class to verify go left until cow is closer than 2 steps', 'test the FollowUntilTest class to verify follow the cow for 18 seconds or 2 minutes', 'test the DigRemoveConditionTest class to verify dig a hole 2 times command', 'run the add_sequence_mob helper to add a LoopMob with a movement sequence to the world', 'review the STOP_CONDITION_COMMANDS usage patterns for go left until, follow, and dig conditions', 'run the TwoCubesInterpreterTest suite to test build, destroy, move, and copy commands in a two-cube world', 'run the FillTest suite to test filling holes with default or specified block types', 'run the DestroyEverythingTest to verify the interpreter destroys all placed blocks in the world', 'run the DigTest suite to test single and n-by-n hole digging commands', 'run the SpawnSheep test to verify spawning a specified number of sheep mobs', 'test the size_str_to_int function by running the TestSizeWords unit test suite', 'test the size_str_to_int function with modifier phrases like really big', 'run the TestSizeWords unittest class to validate size word to integer conversion', 'review the TestSizeWords class and its assert_in_range helper method', 'summarize the test_size_words module that tests size word parsing functionality', 'test the UndoTest class to verify undo functionality restores destroyed Minecraft block objects with their original tags', 'run the UndoTest unit test suite to validate the craftassist interpreter undo command workflow', 'review the UndoTest class and test_undo_destroy method for undo destroy confirmation flow', 'refactor the UndoTest class to remove the speaker sleep TODO and use distinct speakers', 'summarize the UndoTest class which tests block object destruction, tagging, and undo confirmation via dialogue']
```

Usage

```
{'test_undo_destroy': 'test the UndoTest class to verify undo functionality restores destroyed Minecraft block objects with their original tags', 'run_undo_test': 'run the UndoTest unit test suite to validate the craftassist interpreter undo command workflow', 'review_UndoTest': 'review the UndoTest class and test_undo_destroy method for undo destroy confirmation flow', 'refactor_UndoTest': 'refactor the UndoTest class to remove the speaker sleep TODO and use distinct speakers', 'summarize_UndoTest': 'summarize the UndoTest class which tests block object destruction, tagging, and undo confirmation via dialogue'}
```

