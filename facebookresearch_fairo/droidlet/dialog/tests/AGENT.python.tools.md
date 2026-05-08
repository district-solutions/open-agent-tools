# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/dialog/tests/test_greeting.py

Prompts

```
['run the unittest GreetingTest class to test hello and goodbye greeting replies', 'test the DialogueManager get_greeting_reply method with a hello input', 'test the DialogueManager get_greeting_reply method with a goodbye input', 'review the GreetingTest class and its test_hello and test_goodbye test methods', 'refactor the GreetingTest class to add additional greeting test cases', 'run the SafetyTest unittest class to verify DialogueManager safety checks with blacklisted words', 'test that DialogueManager.is_safe returns False when given input containing blacklisted words', 'test that DialogueManager.is_safe returns True when given benign input without blacklisted words', 'review the SafetyTest class and its setUp method that configures DialogueManager with MockOpt', 'summarize how DialogueManager.is_safe evaluates text against a blacklist of unsafe words']
```

Usage

```
{'run_greeting_tests': 'run the unittest GreetingTest class to test hello and goodbye greeting replies', 'test_hello_greeting': 'test the DialogueManager get_greeting_reply method with a hello input', 'test_goodbye_greeting': 'test the DialogueManager get_greeting_reply method with a goodbye input', 'review_greeting_test': 'review the GreetingTest class and its test_hello and test_goodbye test methods', 'refactor_greeting_test': 'refactor the GreetingTest class to add additional greeting test cases'}
```

## File: facebookresearch_fairo/droidlet/dialog/tests/test_safety.py

Prompts

```
['run the unittest GreetingTest class to test hello and goodbye greeting replies', 'test the DialogueManager get_greeting_reply method with a hello input', 'test the DialogueManager get_greeting_reply method with a goodbye input', 'review the GreetingTest class and its test_hello and test_goodbye test methods', 'refactor the GreetingTest class to add additional greeting test cases', 'run the SafetyTest unittest class to verify DialogueManager safety checks with blacklisted words', 'test that DialogueManager.is_safe returns False when given input containing blacklisted words', 'test that DialogueManager.is_safe returns True when given benign input without blacklisted words', 'review the SafetyTest class and its setUp method that configures DialogueManager with MockOpt', 'summarize how DialogueManager.is_safe evaluates text against a blacklist of unsafe words']
```

Usage

```
{'run_safety_test': 'run the SafetyTest unittest class to verify DialogueManager safety checks with blacklisted words', 'test_unsafe_word_detection': 'test that DialogueManager.is_safe returns False when given input containing blacklisted words', 'test_safe_word_detection': 'test that DialogueManager.is_safe returns True when given benign input without blacklisted words', 'review_safetytest_class': 'review the SafetyTest class and its setUp method that configures DialogueManager with MockOpt', 'summarize_dialogue_manager_is_safe': 'summarize how DialogueManager.is_safe evaluates text against a blacklist of unsafe words'}
```

